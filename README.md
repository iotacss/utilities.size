**iotaCSS is now a monorepo and all individual repositories are part of it. Please open issues or PRs here: [https://github.com/iotacss/iotacss](https://github.com/iotacss/iotacss).**

# Size Utility #

The size utility contains a set of classes for setting width in elements or grid columns. The sizes created are based on the [Settings.Column](https://github.com/iotacss/settings.column).


### Installation ###

```
npm install --save iotacss-utils-size
```


### Options ###

```
$iota-utils-size-namespace    : '' !default;

$iota-utils-size-columns      : $iota-global-columns !default;

$iota-utils-size-delimiter    : \/ !default;

$iota-utils-size-res          : false !default;
$iota-utils-size-breakpoints  : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-[column-number]/[total-column-number]  // Example .u-1/3


// Responsive Class Syntax

.u-[column-number]/[total-column-number]@[breakpoint-name]  // Example: .u-1/3@sm
```
