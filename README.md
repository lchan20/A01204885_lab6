Q1. other key words include: "fixed", "fix", "Closes", "Closed", "Close", "resolve", "resolves", "resolved"

Q2. yes you can close multiple issues in one pull request
    you just need to write the fixes keyword or any similar key word before every issue number. (use full syntax) (separated by commas)

Q3. 
let numbers = [3, 7, 24, 57];

function double(value){*
    return value*2
}

<!--This is an example using map with an annonymous function that doubles each value of the array numbers-->
let x = numbers.map(function(value) {
    return {value*2};
} )

<!--the map function is parsing over each item in the numbers array and replacing each value by its doubled value-->


<!-- this is an example of using map with a named function that doubles all the values of an array numbers -->
let y = numbers.map(double(value));

<!--the map is parsing over the numbers array and the double function is acting on the value of each item in the array-->

callback function is a function that will execute after another function finishes executing
callback fucntion is passed as an argument to another function
it is then executed within the function
