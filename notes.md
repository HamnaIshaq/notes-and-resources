# Notes

## Short Circuiting in JS

logical operators OR (||) AND (&&) are used for this

### OR (||)

Return the first truethy value

```
false || true

// true
```
Examples:

```
let x;
let y = "Y";
let z = "Z";

const name = x || y || z;

// name = "Y";
```

```
let x = "name1";
let y = "name2";

const name = x === "name1" || y === "name1";

// name = true;
```

### AND (&&)

Returns the first falsy value. In case of all truethy values, the last truethy value is returned

```
false || true

// false
```

Examples

```
let x;
let y = "Y";
let z = "Z";

const name = x && y && z;

// name = undefined;
```

```
let x = "name1";
let y = "name2";

const name = x === "name1" && y === "name1";

// name = false;
```
Resource:
<a href="https://medium.com/khojchakra/understanding-short-circuit-evaluation-in-javascript-31b5770a41f7">Understanding short circuit evaluation in JS</a>

## Aria

1- aria-required --> will tell this field is required



