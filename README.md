#========= find the scound max value 

let number = [1, 2, 3, 4, 5, 6, 7, 8, 9];
let valueSort = number.sort((a, b) => b - a);
let findMaxValue = valueSort.find((element, index) => { return index === 1 });
console.log(findMaxValue);




#======== find method return the one value and paramitar (value, index , array )

let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];

let result = numbers.find((currentValue, Index, array) => {
    return currentValue > 4;
})

console.log(result);


#============= findIndex method return the one value and paramitar (value, index , array )

let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];

let result = numbers.findIndex((currentValue, Index, array) => {
    return currentValue > 4;
})

console.log(result);




#=========== fillter method return the next all value and new array return paramitar (value, index , array )

let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];

let result = numbers.filter((currentValue, Index, array) => {
    return currentValue > 4;
})

console.log(result);



#============ slice method is working process in start index and endIndex 

let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];

let result = numbers.slice(1,5);

console.log(result);



#=============== splice array te value add kore and remove kore  but splice main array change kore fele

let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];

let result = numbers.splice(1, 5, 10, 32, 23);

console.log(result);
console.log(numbers);


// ================== array concat not a change the array . but push method change the array element add the last


====  map method itarate in the all element in array . final return the array

let numbers = [1, 2, 3, 4, 5, 6, 7, 8];


let result = numbers.map((element) => {
    if (element == 1) {
        return element;
    }
    else {
        return 2 * element
    }
})

console.log(result);
erations by using an event queue, enabling the execution of code, collecting and processing events, and executing queued sub-tasks.

📌 4. Prototypes and Inheritance
JavaScript uses prototypal inheritance, where objects can inherit properties and methods from other objects. Every JavaScript object has a prototype property, which is a reference to another object from which it inherits properties and methods.

📌 5. Higher-Order Functions
These are functions that can take other functions as arguments or return them. 

📌 6. Hoisting
Hoisting is JavaScript's default behavior of moving declarations to the top of the current scope (global or local). This means variables and functions can be used before they are declared, although the initialization part of variables is not hoisted.

📌 7. Modules (ES6)
ES6 modules allow for better code organization and reuse. They enable you to export functions, objects, or primitive values from one module and import them into another, promoting modular programming practices.

📌 8. Spread and Rest Operators
The spread operator allows an iterable to expand in places where multiple arguments or elements are expected. The rest operator collects multiple elements or arguments into a single array, making functions more flexible and concise.

📌 9. Destructuring
Destructuring assignment allows for the extraction of values from arrays or properties from objects into distinct variables. It provides a convenient way to unpack values and assign them to new variables.

📌 10. Currying
Currying transforms a function with multiple arguments into a sequence of functions, each taking a single argument. 

📌 11. Event Delegation
Event delegation is a technique where a single event listener is added to a parent element to manage events for all of its child elements. This leverages event bubbling and makes it more efficient to handle events for multiple child elements.
