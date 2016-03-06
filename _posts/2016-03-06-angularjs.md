---
layout:     post
title:      Angularjs
date:       2016-03-06 
summary:    Getting started Angularjs. Just pure vanilla stuff. 
categories: howto angularjs
---

Create a HTML file

Add angularjs file to your HTML 

```
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js">
</script>
```

Create an application  

```
<div ng-app="">
```

Create a model 

```
<input type="text" ng-model="name">
```

Show it 

```
Hello {{name}}.  
```

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


http://www.w3schools.com/angular/
