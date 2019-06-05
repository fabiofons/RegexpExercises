## Regular Expressions
1. Write a regular expression to check if a string is a valid car plate:
```javascript
const r = /^([A-Z]{3})([0-9]{3})$/
```


2. Write a regular expression to check if a string is a valid hex color:
```javascript
const r = /^\#[a-f\d]{3}$|^\#[a-f\d]{6}$/i
```

3. Write a regular expression to check if a string is a valid date:
```javascript
// calendario configudo hasta el 2999 y desde el año 1000, si se necesita más rango de año solo hay que modificar '[12]'
const r = /^(3[01]|[0-2]\d)\/(0\d|1[0-2])\/([12]\d{3}$/
```
