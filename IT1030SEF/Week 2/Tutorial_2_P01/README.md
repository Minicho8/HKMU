# IT1030SEF - Tutorial 2 Live Coding Demo Kit

An interactive demonstration of JavaScript fundamentals including comparison operators, variables, arithmetic operations, user input, type conversion, and conditional statements.

**Created by:** Ethan Lee  
**Course:** IT1030SEF - Internet Application Development  
**Tutorial:** Week 2 - JavaScript Fundamentals

## 🚀 Quick Start

1. **Open in VS Code**: Launch VS Code and open this project folder
2. **Open index.html**: Double-click `index.html` to see all available demos
3. **Start Live Server**: Right-click any demo file and select "Open with Live Server"
4. **Start Learning**: Edit the `<script>` sections and see changes instantly!

## 📁 Project Structure

```
Tutorial2_Demo/
├── index.html                    # Navigation page - start here!
├── demo1_comparison.html         # Demo 1: Comparison operators
├── demo2_variables.html          # Demo 2: Variables & arithmetic
├── demo3_simple_variable.html    # Demo 3: Simple variable operations
├── demo4_userinput.html          # Demo 4: User input (prompt/alert)
├── demo5_typeconversion.html     # Demo 5: Type conversion
├── demo6_conditional.html        # Demo 6: Conditional statements (if/else)
└── README.md                     # This file
```

**Note:** Each demo file is self-contained with inline `<script>` tags. No external CSS or JavaScript files needed!

## 🎯 Learning Objectives Demonstrated

### 1. Comparison Operators

- **Equal to**: `==`
- **Not equal**: `!=`
- **Less than**: `<`
- **Greater than**: `>`
- **Less than or equal**: `<=`
- **Greater than or equal**: `>=`
- **Boolean results**: `true` or `false`

### 2. Variables & Arithmetic

- **Variable declaration**: `var`, `let`, `const`
- **Undefined variables**: Behavior and handling
- **Arithmetic operators**: `+`, `-`, `*`, `/`, `%`
- **Assignment operations**: `=`, `+=`, `-=`

### 3. User Input & Output

- **window.prompt()**: Get user input as string
- **window.alert()**: Display message dialog
- **document.write()**: Write to HTML document
- **String concatenation**: Joining strings with `+`

### 4. Type Conversion

- **parseFloat()**: Convert string to decimal number
- **parseInt()**: Convert string to integer
- **String vs Number**: Understanding type differences
- **Type coercion**: Automatic type conversion

### 5. Conditional Statements

- **if statement**: Execute code based on condition
- **else statement**: Alternative execution path
- **Comparison in conditions**: Using operators in if/else
- **Boolean logic**: true/false evaluation

## 🎮 Interactive Demos

### Demo 1: Comparison Operators

**File**: `demo1_comparison.html`  
**Edit**: Lines 52-58 (inside `<script>` tag)

**What you'll learn:**
- How comparison operators work (==, !=, <, >, <=, >=)
- Boolean results (true/false)
- Testing different comparison expressions

**Try this:**
```javascript
document.write("Task 1-1: (4 <= 3) = ", (4 <= 3));
// Change to: (10 <= 15) or (5 > 3) and see the result!
```

### Demo 2: Variables & Arithmetic

**File**: `demo2_variables.html`  
**Edit**: Lines 52-61 (inside `<script>` tag)

**What you'll learn:**
- Variable declaration and assignment
- Undefined variables
- Arithmetic operations (+, -, *, /)

**Try this:**
```javascript
firstNumber = 10;
// Change to: firstNumber = 50; and see how it affects the calculations
```

### Demo 3: Simple Variable Operations

**File**: `demo3_simple_variable.html`  
**Edit**: Lines 54-57 (inside `<script>` tag)

**What you'll learn:**
- Basic variable reassignment
- Modifying a variable's value
- Simple arithmetic in action

**Try this:**
```javascript
myNumber = myNumber - 2;
// Change to: myNumber = myNumber + 10; or myNumber = myNumber * 3;
```

### Demo 4: User Input (prompt & alert)

**File**: `demo4_userinput.html`  
**Edit**: Lines 52-55 (inside `<script>` tag)

**What you'll learn:**
- Getting user input with `window.prompt()`
- Displaying messages with `window.alert()`
- String concatenation with `+`

**Try this:**
```javascript
var nameVar = window.prompt("Enter your name:");
// Change the message to: "What is your name?"
```

### Demo 5: Type Conversion

**File**: `demo5_typeconversion.html`  
**Edit**: Lines 58-63 (inside `<script>` tag)

**What you'll learn:**
- Difference between string concatenation and numeric addition
- Using `parseFloat()` to convert strings to numbers
- Why type conversion matters

**Try this:**
```javascript
var firstNumber = '123';
// Change to: '999' and see both concatenation and addition results
```

### Demo 6: Conditional Statements

**File**: `demo6_conditional.html`  
**Edit**: Lines 56-64 (inside `<script>` tag)

**What you'll learn:**
- Making decisions with `if/else`
- Using comparison operators in conditions
- Calculating and comparing values

**Try this:**
```javascript
if (age >= 18) {
// Change to: if (age >= 21) to test a different age threshold
```

## 🎨 Practice Exercises

### Exercise 1: Test Different Comparisons

**File**: `demo1_comparison.html`

Add more comparison tests to see how different operators work:

```javascript
document.write("<br>Test: (100 > 50) = ", (100 > 50));
document.write("<br>Test: (5 == 5) = ", (5 == 5));
document.write("<br>Test: (10 != 20) = ", (10 != 20));
```

### Exercise 2: Create New Variables

**File**: `demo2_variables.html`

Practice creating and using your own variables:

```javascript
var thirdNumber = 100;
var total = firstNumber + secondNumber + thirdNumber;
document.write('<br>Total of all three: ' + total);
```

### Exercise 3: Multiple Operations

**File**: `demo3_simple_variable.html`

Practice chaining multiple operations:

```javascript
var myNumber;
myNumber = 10;
myNumber = myNumber + 5;
myNumber = myNumber * 2;
document.write(myNumber); // Result: 30
```

### Exercise 4: Customize User Prompts

**File**: `demo4_userinput.html`

Add more prompts to collect different information:

```javascript
var ageVar = window.prompt("Enter your age:");
var cityVar = window.prompt("Enter your city:");
window.alert("You are " + ageVar + " years old from " + cityVar);
```

### Exercise 5: Compare parseInt vs parseFloat

**File**: `demo5_typeconversion.html`

See the difference between parseInt and parseFloat:

```javascript
var decimal = '3.14';
thirdNumber_3 = parseInt(decimal);
thirdNumber_4 = parseFloat(decimal);
document.write('<br>parseInt result: ' + thirdNumber_3);
document.write('<br>parseFloat result: ' + thirdNumber_4);
```

### Exercise 6: Add Multiple Conditions

**File**: `demo6_conditional.html`

Create more complex conditions with `else if`:

```javascript
if (age >= 65) {
    document.write("You are a senior citizen");
} else if (age >= 18) {
    document.write("You are an adult");
} else {
    document.write("You are a minor");
}
```

## 💡 Key Concepts to Understand

### Comparison Operators
- Operators return **boolean values** (true or false)
- Use parentheses to control order of operations
- Common mistake: using `=` (assignment) instead of `==` (comparison)
- `==` compares values, `===` compares values AND types

### Variables & Arithmetic
- **Declaration**: Creating a variable with `var`
- **Assignment**: Giving a variable a value with `=`
- **Undefined**: Variables declared but not assigned have value `undefined`
- **Arithmetic**: Use +, -, *, / for math operations

### User Input
- `window.prompt()` always returns a **string** (even if you type numbers)
- `window.alert()` displays a message to the user
- Use `+` to join (concatenate) strings together
- If user clicks Cancel, prompt returns `null`

### Type Conversion
- **String concatenation**: `'5' + '3'` = `'53'` (joined together)
- **Numeric addition**: `5 + 3` = `8` (added together)
- `parseFloat()` converts string to decimal number
- `parseInt()` converts string to whole number
- Always convert strings to numbers before doing math!

### Conditional Statements
- `if (condition)` runs code only when condition is **true**
- `else` runs code when condition is **false**
- Conditions use comparison operators (==, !=, <, >, <=, >=)
- Code inside `{ }` only runs if the condition matches

## 🛠️ Browser Compatibility

- **Modern Browsers**: Chrome, Firefox, Safari, Edge
- **Features Used**: Standard JavaScript ES5/ES6
- **No Dependencies**: Pure vanilla JavaScript

## 🎓 Challenge Yourself

### Level 1: Beginner

1. **Prediction Game**: Change comparison operators and predict the result before running
2. **Variable Math**: Modify variable values and calculate the final result
3. **Custom Greetings**: Change prompt messages to ask different questions
4. **Age Limits**: Change the age threshold from 18 to different values (13, 21, 65)

### Level 2: Intermediate

1. **More Comparisons**: Add 5 more comparison tests with different operators
2. **Simple Calculator**: Create a calculator that adds, subtracts, multiplies, or divides two numbers
3. **Personal Info**: Build a greeting system that asks for name, age, and city
4. **Grade Calculator**: Use if/else if/else to show letter grades (A, B, C, D, F) based on score

### Level 3: Advanced

1. **BMI Calculator**: Ask for height and weight, calculate BMI, show if underweight/normal/overweight
2. **Temperature Converter**: Convert between Celsius and Fahrenheit with user input
3. **Quiz Game**: Create a 3-question quiz that tracks correct answers and shows final score
4. **Number Guessing**: Make a game where user guesses a number and you tell them if too high/low

## 🔧 Troubleshooting

### Live Server Not Working

1. Install Live Server extension in VS Code
2. Right-click `index.html` → "Open with Live Server"
3. Check port 5500 or similar in browser

### Demos Not Running

1. Check browser console (F12) for errors
2. Verify JavaScript is enabled in browser
3. Ensure all files are in correct folders

### Prompts Not Appearing

1. Check if pop-up blocker is enabled
2. Allow pop-ups for localhost
3. Try different browser

### Type Conversion Issues

1. Verify input is a valid number string
2. Check for null/undefined values
3. Use console.log() to debug values

## 📚 Additional Resources

### JavaScript Basics

- **MDN Web Docs**: Comprehensive JavaScript documentation
- **W3Schools**: Beginner-friendly tutorials
- **JavaScript.info**: In-depth JavaScript guide

### Specific Topics

- **Comparison Operators**: MDN Comparison Operators Guide
- **Type Conversion**: JavaScript Type Coercion
- **Conditionals**: Control Flow and Error Handling

## 💡 Learning Tips

1. **Start Simple**: Begin with Demo 1, then work through each demo in order
2. **Experiment**: Don't be afraid to change values and see what happens
3. **Make Mistakes**: Errors are part of learning - read error messages in the browser console (F12)
4. **Test Your Ideas**: Try your own values and see if you can predict the results
5. **Real Examples**: Think of real-world uses (age verification, price calculations, grade checking)
6. **Ask Questions**: If something doesn't work as expected, that's a learning opportunity!

## 🎯 How to Learn Effectively

1. **Read the code** in each demo file carefully
2. **Run the demo** to see how it works
3. **Make small changes** one at a time
4. **Predict the result** before saving
5. **Check if you were right** by viewing in browser
6. **Try the exercises** to practice what you learned

---

**Happy Coding!** 🎉

This demo kit is designed to help you learn JavaScript fundamentals through hands-on practice. Take your time, experiment, and have fun learning!

**Created by:** Ethan Lee  
**Last Updated:** January 2026
