# Objects.Tables

The `Tables` module provides some useful helpers for common table patterns.


## Installation

Install via [npm](http://npmjs.org/): 
 
 	npm install bettercss-objects-tables
    
## Configuration Variables
 
### Enable Features
All features are turned off by default, To enable a feature just override the default variable. 
```scss
$bc-o-table-enable--tiny 
$bc-o-table-enable--small
$bc-o-table-enable--large
$bc-o-table-enable--huge
$bc-o-table-enable--cells-border
$bc-o-table-enable--rows-border
$bc-o-table-enable--columns-striped
$bc-o-table-enable--rows-striped
```

### Misc

```
// Spacing
$bc-o-tables-spacing-unit
$bc-o-tables-padding
$bc-o-table-padding--tiny
$bc-o-table-padding--small
$bc-o-table-padding--large
$bc-o-table-padding--huge

// Colors
$bc-o-table-color-background--columns-striped
$bc-o-table-color-background--rows-striped
$bc-o-table-color-border--cells-border
$bc-o-table-color-border--rows-border
```

## Available Classes
 
You can view a more in depth description of the classes usage in the source see [_objects.tables.scss](https://github.com/bettercss/objects.tables/blob/master/lib/_objects.tables.scss)
 
```scss
// Base
.o-table

// Spacing
.o-table--equal
.o-table--tiny
.o-table--small
.o-table--large
.o-table--huge

// Theming
.o-table--cells-border
.o-table--rows-border
.o-table--columns-striped
.o-table--rows-striped
 ```