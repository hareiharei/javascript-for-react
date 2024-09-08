# Objects

```
const person = {
  name: "Pedro",
  age: 20,
  isMarried: false,
};
```

- taking too much space
  ```
  const name = person.name
  const age = person.age
  const isMarried = person.isMarried
  ```

- destruct properties
  ```
  const { name, age, isMarried } = person;
  ```

- insert constant as a property
  ``` 
  const name = "Pedro"

  const person = {
    name,                 // name: name
    age: 20,
    isMarried: false,
  };
  ```


- create a new object by just changing only one property
  ```
  const person = {
    name: "Pedro",
    age: 20,
    isMarried: false,
  };

  const person2 = {...person, name: "Jack"}
  ```

  ```
  const names = ["Pedro", "Jack", "Jessica"]
  const names2 = [...names, "Joel"]
  ```