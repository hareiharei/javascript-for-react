# Three Important Functions for Arrays

- .map()
- .filter()
- .reduce()

## map function

```
let names = ["Pedro", "Jessica", "Carol"];

names.map((name) => {
  return name + "1";
});

// nameは ["Pedro1", "Jessica1", "Carol1"] になる
```

```
let names = ["Pedro", "Jessica", "Carol"];

names.map((name) => {
  return <h1> {name} </h1>
})
```

## filter function

```
let names = ["Pedro", "Jessica", "Carol", "Pedro", "Pedro"];

names.filter((name) => {
  return name !== "Pedro"
})

// namesは ["Pedro", "Jessica", "Carol", "Pedro", "Pedro"] になる
```