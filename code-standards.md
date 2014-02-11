## Code standards

* Do not complicate readability in exchange for terseness.
* Maintain a consistent style throughout entire code base.
* Document all non-trivial functions.

### Variable declaration

* Always use var when assigning a variable. If assigning a global variable,
explicitly declare it as a property of the global object.
* Use a new line for each assignment.
* Unassigned declarations can be done as a comma seperated line.

```js
var x = 5;
var y = 1;
var a, b, c;

window.z = 6;
```

### Spacing

```js
var bar = {
	'hello': world,
	'baz': true
};

var foo = function(x, y) {
	for (var i = 0; i < 5; i++) {
		console.log(i);
	}
	if (x === y) {
		return true;
	}
};
```