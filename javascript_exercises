// Alert with the message "Hello"
alert("Hello");

// Iterate over the array and alert each value
[1, 2].forEach(alert);

// Variable assignment and display
let admin;
let newName = "john";
admin = newName; // Assign the value of name to admin
alert(admin); // Displays "john"

// Variable declaration for future use
let myPlanet;
let newVisitor;

// Prompt user for their name and display a greeting
let age = prompt("What is your name?");
alert("Hello " + age); // Displays "Hello <name>"

// Using template literals for dynamic message display
alert(`You are ${age} years old!`);

// Prompt user for a test input
let test = prompt("Test");

// Confirm if the user is the boss and display the result
let isBoss = confirm("Are you the boss?");
alert(isBoss); // Displays true if OK is pressed, false otherwise

// Demonstration of prefix increment
let counter = 1;
let a = ++counter; // Increments counter before assignment
alert(a); // Displays 2

// Prefix increment and multiplication example
counter = 1;
alert(2 * ++counter); // Increments and multiplies, result is 4

// Type coercion examples
console.log("" + 1 + 0); // "10"
console.log("" - 1 + 0); // -1
console.log(true + false); // 1
console.log(6 / "3"); // 2
console.log("2" * "3"); // 6
console.log(4 + 5 + "px"); // "9px"
console.log("$" + 4 + 5); // "$45"
console.log("4" - 2); // 2
console.log("4px" - 2); // NaN
console.log("  -9  " + 5); // "  -9  5"
console.log("  -9  " - 5); // -14
console.log(null + 1); // 1
console.log(undefined + 1); // NaN
console.log(" \t \n" - 2); // -2

// Prompt for two numbers and alert their sum
let num1 = prompt("First number?", 1);
let num2 = prompt("Second number?", 2);
alert(+num1 + +num2); // The plus signs convert strings to numbers

// Comparison examples
console.log(5 > 4); // true
console.log("apple" > "pineapple"); // false
console.log("2" > "12"); // true
console.log(undefined == null); // true
console.log(undefined === null); // false
console.log(null == "\n0\n"); // false
console.log(null === +"\n0\n"); // false

// Conditional message based on age input
age = prompt("What is your age: ", 18);
let message =
  age < 3
    ? "Hi baby!"
    : age < 18
      ? "You are not 18, go to school!"
      : age < 55
        ? "You are taking care of your family"
        : "What's your real age?";
alert(message);

// Simple if condition with string evaluation
if ("0") {
  alert("Hello"); // This will run since "0" is truthy
}

// Prompt and conditional comparison example
let zen = prompt("Enter a number: ");
if (zen > 0) {
  alert("Greater than 0");
} else if (zen > 1) {
  alert("Greater than 1");
} else {
  alert("Not 0 and not 1");
}

// Using ternary operator for comparison
let result = a + b < 4 ? "Below" : "Over";

// Switch statement with multiple cases for browser detection
let browser = prompt("Which browser do you use?", "");
switch (browser) {
  case "Edge":
    alert("You've got the Edge!");
    break;
  case "Chrome":
  case "Firefox":
  case "Safari":
  case "Opera":
    alert("Okay, we support these browsers too");
    break;
  default:
    alert("We hope this page looks okay!");
}

// Switch statement with a number comparison
a = +prompt("a?", "");
switch (a) {
  case 0:
    alert(0);
    break;
  case 1:
    alert(1);
    break;
  case 2:
  case 3:
    alert("2,3");
    break;
}

// Function to display prime numbers up to n
function showPrimes(n) {
  for (let i = 2; i < n; i++) {
    if (!isPrime(i)) continue;
    alert(i); // A prime number
  }
}

// Helper function to check for prime numbers
function isPrime(n) {
  for (let i = 2; i < n; i++) {
    if (n % i == 0) return false;
  }
  return true;
}

// Function to check if the user is of age using the question mark operator
function checkAge(age) {
  return age > 18 ? true : confirm("Did your parents allow you?");
}

// OR || version of the age check
function checkAge(age) {
  return age > 18 || confirm("Did your parents allow you?");
}

// Function to return the smaller of two numbers
function leastNumber(a, b) {
  return a > b ? b : a;
}

// Function to calculate the power of a number
function getPowerOfNumber(x, n) {
  let output = x;
  for (let i = 1; i < n; i++) {
    output *= x;
  }
  return output;
}

// Arrow function based on age
age = prompt("What is your age: ");
let welcome = age < 18 ? () => alert("Hello...") : () => alert("Greetings...");
welcome();

// Function to ask a question with yes/no callbacks
function ask(question, yes, no) {
  if (confirm(question)) yes();
  else no();
}

ask(
  "Do you agree?",
  () => alert("You agreed."),
  () => alert("You canceled the execution.")
);

// Object manipulation example
let user = {
  name: "John",
  surname: "Smith",
};
user.name = "Pete";
delete user.name;

// Function to check if an object is empty
function isEmpty(obj) {
  for (let key in obj) {
    return false;
  }
  return true;
}

// Sum of salaries
let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130,
};
let sum = 0;
for (let key in salaries) {
  sum += salaries[key];
}
alert(sum); // 390

// Function to multiply numeric properties of an object
function multiplyNumeric(obj) {
  for (let key in obj) {
    if (typeof obj[key] === "number") {
      obj[key] *= 2;
    }
  }
}
