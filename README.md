Sublime Text Editor 3 - JavaScript Snippets
===========================================

JavaScript / JS snippets for your Sublime Text 3.


Install
-------

### Mac OS X

    git clone git@github.com:EpiphanyMachine/sublime-js-snippets.git ~/Library/Application Support/Sublime Text 3/Packages/JavaScript


### Linux

    git clone git@github.com:EpiphanyMachine/sublime-js-snippets.git ~/.config/sublime-text-3/Packages/JavaScript



Vanilla Snippets
----------------

### [afn] anonymous function

```javascript
function (arguments) {
    // stuff...
};
```


### [if] if statement

```javascript
console.dir(obj);
```


### [cd] console.dir

```javascript
console.dir(obj);
```


### [ce] console.error

```javascript
console.error(error);
```


### [cl] console.log

```javascript
console.log(msg);
```


### [fn] function

```javascript
function methodName(arguments) {
    // stuff...
}
```


### [ii] Immediately-invoked function expression

```javascript
(function () {
    // stuff...
})();
```


### [proto] prototype

```javascript

```


### [sto] setTimeout

```javascript
setTimeout(function () {
    // stuff...
}, millis);
```


### [us] use strict

```javascript
'use strict';
```



Require
-------

### [req] require

```javascript
require('package');
```


### [def] define

```javascript
define(function (require) {
    'use strict';
    // stuff...
});
```



Underscore
----------

### [each] _.each

```javascript
_.each(collection, function (value, key) {
    // stuff...
});
```



Behaviorial Driven Development
------------------------------

### [desc] describe

```javascript
describe('description', function () {
    // stuff...
});
```


### [bfr] before or beforeEach

```javascript
beforeEach(function (done) {
    // stuff...
});
```


### [it] it - sync or async

```javascript
it('description', function (done) {
    // stuff...
}
```



Default Snippets
----------------

[if]
[proto]



Author
------

[Gregory Hilkert](https://github.com/EpiphanyMachine/)



Thanks To
-----------

[JP Richardson](https://github.com/jprichardson/) and his [Sublime Text Editor 2 - JavaScript Snippets](https://github.com/jprichardson/sublime-js-snippets) repo

[José F. Romaniello](https://github.com/jfromaniello/) and his [sublime text 2 snippets for mocha](https://github.com/jfromaniello/sublime-mocha-snippets) repo



License
-------

Copyright 2014, Gregory Hilkert  <EpiphanyMachine@gmail.com>

MIT
