AngularNotify Module
=====================

### REQUERIMIENTOS ###
* jQuery 1.10 or Higher

### USO DE ESTE MODULO ###
Nombre del modulo y del Servicio

```html
<button type="button" ng-click="click()">Notify</button>
```

```JavaScript
angular.module('myapp',['ngNotify'])
controller('ctrlmain', function($scope, $notify){
	$scope.click = function(){
		$notify.success('title','message');
	}

	$notify.info('title','message');
	$notify.warning('title','message');
	$notify.error('title','message');
});
```