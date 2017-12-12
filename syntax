## Module System

### Modules
```d
module test;
```

### Imports
```d
import test;
```
## Types

### Struct
```d
User: struct {
	name string;
	password string;
}
var User;
```

### Templated Struct
```d
UserTpl(T): struct {
	name T;
	password T;
}

var UserTpl!string;
```
```d
UserTpl(T) if T == string: struct {
	name T;
	password T;
}

var UserTpl!string;
```

### Function
```d
concatenated: (a string, b string) string {
	return a ~ b;
}

var auto = (`a`, `b`).concatenated;
```
```d
swapped: (a string, b string) (string, string) {
	return b, a;
}

var auto = (9, 5).swapped;
```

### Templated Function
```d
swapped(A, B): (a A, b B) (B, A) {
	return b, a;
}

var auto = (9, 'a').swapped;
```
```d
add(T) if T == int: (a T, b T) auto {
	return a + b;
}

var auto = add(9, 5);
var auto = 9.add(5);
var auto = (9, 5).add;
```

## Expressions

### if
```d
if a < 10 {
	a += b;
}
```
```d
var auto = if a == b { 0 } 
           else if a > b { 1 } 
           else { 2 };
```

### for
```d
for i = 0; i < 10; ++i {
	a += b;
}
```

### foreach
```d
foreach i; 0 .. 10 {
	a += b;
}
```

### scope
```d
scope {
	a int;
}
```

### scope(exit)
```d
scope(exit) {
	a int;
}
```

### scope(success)
```d
scope(success) {
	a int;
}
```

### scope(failure)
```d
scope(failure) {
	a int;
}
```
