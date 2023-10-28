# Array Exercises

For each of the exercises below, assume you are starting with the following ***people*** array.

```jsx
const people = ["Greg", "Mary", "Devon", "James"];
```

1. Write the command to remove “Greg” from the array.
    - `people.shift();`
2. Write the command to remove “James” from the array.
    - `people.pop();`
3. Write the command to add “Matt” to the front of the array.
    - `people.unshift("Matt");`
4. Write the command to add your name to the end of the array.
    - `people.push("Patrick");`
5. Write the command to make a copy of the array using ***slice***. The copy should **NOT** include “Mary” or “Matt”.
    - `let cpy = people.slice(2);`
6. Write the command that gives the indexOf where “Mary” is located.
    - `people.indexOf("Mary");`
7. Write the command that gives the indexOf where “Foo” is located (this should return ***-1***).
    - `people.indexOf("Foo");`
8. Redefine the people variable with the value you started with. Using the ***splice*** command, remove “Devon” from the array and add “Elizabeth” and “Artie”. Your array should look like this when you are done ***[“Greg”, “Mary”, “Elizabeth”, “Artie”, “James”]***.
    ```js
    let people = ["Greg", "Mary", "Devon", "James"];
    people.splice(2, 1, "Elizabeth", "Artie");
    ```
9. Create a new variable called ***withBob*** and set it equal to the ***people*** array concatenated with the string of ***“Bob”***.
    ```js
    let withBob = people.concat("Bob");
    ```