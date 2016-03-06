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

### Expressions
  * You could run maths 
  * AngularJS expressions do not support conditionals, loops, and exceptions, while JavaScript expressions do.
  * AngularJS expressions support filters, while JavaScript expressions do not.

```
<p>My first expression: {{ 5 + 5 }}</p>
```

### Application (or as they call it, Module)
  * You could name your app and put a controller to home the js code. 

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

### Directives 

  * [List of directives in Angularjs](http://www.w3schools.com/angular/angular_ref_directives.asp)
  * That is not the official one. Find that and share here. //TODO: 

### AngularJS Services

  * http://www.w3schools.com/angular/angular_services.asp
  * a service is a function, or object
  * $location - 
  * $http is an AngularJS service for reading data from remote servers.

### Arrays 

```
points=[1,15,19,2,40]

{{ points[2] }}

names=['Jani','Hege','Kai']

<li ng-repeat="x in names">
```

### Ref
  * http://www.w3schools.com/angular/
  * http://www.w3schools.com/angular/angular_intro.asp
  * http://www.w3schools.com/angular/angular_expressions.asp
