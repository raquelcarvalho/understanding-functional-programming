# Functional programming

Enter the project folder

```
cd functional-programming
```

install the mocha

```
npm install -g mocha
```

Run the tests

```
mocha
```

Example:

```javascript
const name = "Raquel";

// impure
var helloName = function () {
  name = "Hello " + name;
  return name;
};

// pure
var helloName = function (name) {
  return "Hello " + name;
};
```
