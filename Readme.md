AngularNotify Module
=====================

### REQURIMIENTOS ###
* jQuery 1.10 or Higher

### USO DE ESTE MODULO ###
`Module Name and Service Name
`Nombre del modulo y del Servicio

```
angular.module('myapp',['ngNotify'])
controller('ctrlmain', function($scope, $notify){
	$notify.success('title','message');
	$notify.info('title','message');
	$notify.warning('title','message');
	$notify.error('title','message');
});
```