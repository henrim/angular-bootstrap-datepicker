# angular-bootstrap-datepicker


Directive for use with:
http://eternicode.github.io/bootstrap-datepicker/


Based on 
https://github.com/cletourneau/angular-bootstrap-datepicker

Updated to use 
bsOptions instead of ngOptions



###Usage:

**Html:**
```html
<input type="text" ng-datepicker bs-options="datepickerOptions" ng-model="date" />
```

**Javascript**
```javascript

angular.module('mymodule', ['ng-bootstrap-datepicker'])
  ...
 controller: ['$scope', function ($scope) {
    $scope.datepickerOptions = {
      format: 'yyyy-mm-dd',
      language: 'en',
      autoclose: true
  };    
  
```
