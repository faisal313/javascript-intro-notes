
## Object

-   Everything in JavaScript is an Object.
    
-   Objects are used for collection of data, collection of functionality.
    
-   Example:
    
    ```javascript
      const person = {
      	name: 'Faisal', // property: value
      	age: 100 // i know i am too old man!
      };
      
      typeof person // object
      
      person.age = 101;
      console.log(person.age); // 101
    
    ```
    

.

-   Order of properties doesn't matter in an object.
-   **Accessing properties:**
    -   `person.name // Faisal` (dot notation)