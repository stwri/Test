Question 1.how to integrate css file in html file?
Ans: b) using <link> tag

Question 2. How do you make a new paragraph in HTML?
Ans : b) using p tag

Question 3. Div tag is a inline-block element?
Ans : 
b) false
Question 4. Span is an inline-block element?
Ans : a) true

Question 5. What is the output of following code?(1 mark)

function ValueOfC(){

Var y = 10;

Var c = y ** y

console.log(c);

Return c;

}

ValueOfC() // —-->

Ans : 
c) 10000000000



Q6. Consider this array :

const people = [

{ id: 1, name: 'John', age: 30 },

{ id: 2, name: 'Jane', age: 25 },

{ id: 3, name: 'Bob', age: 40 },

]; (apply all operations on this array)

only use map and filter functions to get the output array.

A) Output array : ['John', 'Jane', 'Bob']


outputcode:

const people = [

    { id: 1, name: 'John', age: 30 },

    { id: 2, name: 'Jane', age: 25 },

    { id: 3, name: 'Bob', age: 40 },

];

const names = people.map(person => person.name);

console.log(names);  // Output: ['John', 'Jane', 'Bob']

B) Output array :

[{ "id":1,"name":"John","age":30,"salary":50000},

{"id": 2,"name": "Jane","age": 25,"salary": 50000},

{"id": 3,"name": "Bob","age": 40,"salary": 50000}]

output code:

const updatedPeople = people.map(person => ({

    ...person,

    salary: 50000

}));

console.log(updatedPeople);

// Output: [

//     { id: 1, name: 'John', age: 30, salary: 50000 },

//     { id: 2, name: 'Jane', age: 25, salary: 50000 },

//     { id: 3, name: 'Bob', age: 40, salary: 50000 }

// ]


Q7: write a function main and pass two functions as

parameter to it cb1 and cb2. main(cb1, cb2, x, y)

Define cb1 in such a way that will add two numbers

Define cb2 in such a way that will give you the

difference of two numbers.

X and y are two numbers ex- x=11, y =4.


outputcode:

// Define cb1 to add two numbers

function cb1(x, y) {

    return x + y;

}

// Define cb2 to subtract two numbers

function cb2(x, y) {

    return x - y;

}

// Define the main function that takes two callback functions and two numbers

function main(cb1, cb2, x, y) {

    const sum = cb1(x, y);

    const difference = cb2(x, y);

    return { sum, difference };

}

// Example usage

const x = 11;

const y = 4;

const result = main(cb1, cb2, x, y);

console.log(result);  // Output: { sum: 15, difference: 7 }

Q8 : given an array

var users = [

{firstName : "Susan", lastName: "Steward"},

{firstName : "Daniel", lastName: "Longbottom"},

{firstName : "Jacob", lastName: "Black"}

];

outputarray = ["Susan Steward", "Daniel Longbottom", "Jacob Black"]

to get the output array from users array which array method

will give you correct result?

Ans : c)map function



Q10: what will be the value of arr?

var arr = [1,2,3,4,5].filter(func)

function func(v){

return false;

}

Ans : C)[ ]


Q11: what is the key difference between these two

properties?Choose appropriate option.

Display : none and visibility:hidden

 Ans :
 C)display : none apply property to element opacity

: 0,while visibility : hidden just remove that

element from dom.


Q12: what will be the output of following code?

var a = 1;

var b = 0;

while (a <= 3)

{

a++;

b += a * 2;

console.log(b);

}

Ans : a)4 10 18



Q13: at the end of both operations what will be the value of arr? (2 marks)

Var arr= [1,2,3,4]

arr.unshift(100)

arr.shift()

Ans : A) [1,2,3,4]
