---
layout:     post
title:      Angularjs
date:       2016-03-06 
summary:    Getting started Angularjs. Just pure vanilla stuff. 
categories: howto angularjs
---

### Write a vanilla angularjs 
  * Create a HTML file
  * Add angularjs file to your HTML 
  * Declare an app
  * Inside the app, create a model 
  * Display the model. 


The total code 

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Playing with Angular.js</title>
<script
    src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>
</head>
<body>

<h1>Hello world.</h1>

<div ng-app="">
<input type="text" ng-model="name">
Hello {{name}}.   
</div>

</body>
</html>
```

You can initialize models. 

```
<div ng-app="" ng-init="firstName='John'">
```

You could run maths 
```
<p>My first expression: {{ 5 + 5 }}</p>
```

You could name your app and put a controller to home the js code. 
```
<div ng-app="myApp" ng-controller="myCtrl">
```

And put some code in the app and controller. 
```
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
    $scope.firstName= "John";
    $scope.lastName= "Doe";
});
</script>
```


http://www.w3schools.com/angular/
