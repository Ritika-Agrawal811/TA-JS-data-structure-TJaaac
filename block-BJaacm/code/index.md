```js
let user = {
  name: "Arya",
  sibling: ["Robb", "Ryan", "John"],
};
let allBrothers = ["Robb", "Ryan", "John"];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` // output and reason
- `user === newUser;`
- `user.name === newUser.name;`
- `user.name == newUser.name;`
- `user.sibling == newUser.sibling;`
- `user.sibling === newUser.sibling;`
- `user.sibling == allBrothers;`
- `user.sibling === allBrothers;`
- `brothersCopy === allBrothers;`
- `brothersCopy == allBrothers;`
- `brothersCopy == user.sibling;`
- `brothersCopy === user.sibling;`
- `brothersCopy[0] === user.sibling[0];`
- `brothersCopy[1] === user.sibling[1];`
- `user.sibling[1] === newUser.sibling[1];`

console.log(user == newUser); // true
console.log(user === newUser); // true
console.log(user.name === newUser.name); // true
console.log(user.name == newUser.name); // true
console.log(user.sibling == newUser.sibling); // true
console.log(user.sibling === newUser.sibling); // true
console.log(user.sibling == allBrothers); // false
console.log(user.sibling === allBrothers); // false
console.log(brothersCopy === allBrothers); // false
console.log(brothersCopy == allBrothers); // false
console.log(brothersCopy == user.sibling); // true
console.log(brothersCopy === user.sibling); // true
console.log(brothersCopy[0] === user.sibling[0]); // true
console.log(brothersCopy[1] === user.sibling[1]); // true
console.log(user.sibling[1] === newUser.sibling[1]); // true
