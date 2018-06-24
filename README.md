# JSNotes

Identical:

```
var createScream = function(logger) {
 return function(message) {
 logger(message.toUpperCase() + "!!!")
 }
}
```

vs.

```
const createScream = logger => message =>
 logger(message.toUpperCase() + "!!!")
```
