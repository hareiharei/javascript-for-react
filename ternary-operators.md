# ternary operators

- jsx
- write javascript and represent ui


- taking too much space
```
let age = 10;
let name = "Pedro";

if (age > 10) {
  name = "Pedro"
} else {
  name = "Jack"
}
```

- use ternary operators
```
let age = 16;
let name = age > 10 ? "Pedro" : "Jack";

const Component = () => {
  return age > 10 ? <div> Pedro </div> : <div> Jack </div>
}
```