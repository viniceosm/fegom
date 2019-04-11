# Fegom

Simple css

## CSS
Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load our CSS.
```html
<link rel="stylesheet" href="fegom.css">
```

## Starter template
```html
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Hello, world!</title>

	<link rel="stylesheet" href="fegom.css">
</head>

<body>
	<h1>Hello, world!</h1>
</body>

</html>
```
## Basic Elements

### Button

Button block
```html
<button class="btn-fegon btn-block">
```

## Grid system

|				| *Mobile* <600px | *Tablet* >= 600px | *Desktop* >= 768px |
|---------------|-----------------|------------------|-------------------
| *Class prefix*| `.col-`		| `.col-s-`			 | `.col-m`			 |
| *# of columns*| 12

## Offset classes

|				| *Mobile* <600px | *Tablet* >= 600px | *Desktop* >= 768px |
|---------------|-----------------|------------------|-------------------
| *Class prefix*| `.col-x-offset-*` | `.col-s-offset-*` | `.col-m-offset-*`|
