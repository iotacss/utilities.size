# Size Utility #

The size utility contains a set of classes for setting width in elements or grid columns. The sizes created are based on the [Settings.Column](https://github.com/iotacss/settings.column).


### Installation ###

```
npm install --save iotacss-size
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Settings.Column](https://github.com/iotacss/settings.column)
* [Settings.Breakpoint](https://github.com/iotacss/settings.breakpoint)


### Options ###

```
$iotacss-size--res : false !default;
```


### Classes ###

```
.u-[column-number]/[total-column-number]  // Example .u-1/3


// Responsive Class Syntax

.u-[column-number]/[total-column-number]@[breakpoint-name]  // Example: .u-1/3@sm
```
