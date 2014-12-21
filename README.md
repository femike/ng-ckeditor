CKEditor + AngularJS Bower-Asset
====================

Code licensed under New BSD License.

## Installing via Bower
```
bower install ng-ckeditor-clear
```

##Usage
```html
<textarea ckeditor="editorOptions" ng-model="modelName"></textarea>
```

```js
// add dependency
angular.module('app', ['ngCkeditor'])

// setup editor options
$scope.editorOptions = {
    language: 'ru',
    uiColor: '#000000'
};
```
