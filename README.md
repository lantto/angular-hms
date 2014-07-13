angular-hms
===========

Filter for converting seconds to hours, minutes and seconds.

# Basic usage

```javascript
var myApp = angular.module('myApp',['hms']);
```

```html
<span>{{123 | hms}}</span> 
<!-- prints "2m 3s" -->

<span>{{12345 | hms:[' hours, ', ' minutes, ', ' seconds']}}</span> 
<!-- prints "3 hours, 25 minutes, 45 seconds" -->
```
