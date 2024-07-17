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
