# 📅 Day 1 — JavaScript Variables

Welcome to **Day 1 of my JavaScript learning journey**! 🚀

Today, I started learning the fundamentals of JavaScript, beginning with **variables**.

## 📚 What I Learned

Today I learned about:

* `let`
* `const`
* `var`
* Declaring variables
* Assigning values to variables
* Updating variable values
* Redeclaring variables
* Using `console.log()` to display output

## 🔹 1. `let`

`let` is used to declare a variable whose value can be changed later.

```javascript
let age = 20;

age = 21;

console.log(age);
```

**Output:**

```text
21
```

## 🔹 2. `const`

`const` is used when the value should not be reassigned.

```javascript
const country = "India";

console.log(country);
```

**Output:**

```text
India
```

## 🔹 3. `var`

`var` is an older way of declaring variables in JavaScript.

```javascript
var name = "Anjali";

name = "Anjali Negi";

console.log(name);
```

**Output:**

```text
Anjali Negi
```

## 🧠 Important Difference

| Keyword | Can Update Value? | Can Redeclare? |
| ------- | ----------------- | -------------- |
| `let`   | ✅ Yes             | ❌ No           |
| `const` | ❌ No              | ❌ No           |
| `var`   | ✅ Yes             | ✅ Yes          |

## 💻 Practice

Today I practiced:

* Creating variables
* Changing variable values
* Printing values using `console.log()`
* Understanding the difference between `let`, `const`, and `var`

## 📁 Practice Files

01-variables/
│
├── let.js
├── const.js
└── var.js

## 🎯 Day 1 Goal

Build a clear understanding of JavaScript variables and how `let`, `const`, and `var` work.

### 🚀 Progress

**Day 1 — Variables ✅**

> One step closer to becoming better at JavaScript! 💻
> # 📅 Day 2 — JavaScript Data Types

Welcome to **Day 2 of my JavaScript learning journey**! 🚀

Today, I continued learning the fundamentals of JavaScript by understanding **data types**.

## 📚 What I Learned

Today I learned about:

* What data types are
* Primitive data types
* `String`
* `Number`
* `Boolean`
* `Undefined`
* `Null`
* `BigInt`
* `Symbol`
* Using `typeof` to check the data type of a value

## 🔹 1. String

A `String` is used to store text.

```javascript
let name = "Anjali";

console.log(name);
console.log(typeof name);
```

**Output:**

```text
Anjali
string
```

## 🔹 2. Number

A `Number` is used to store numerical values, including integers and decimal numbers.

```javascript
let age = 20;
let height = 5.4;

console.log(age);
console.log(height);
console.log(typeof age);
```

**Output:**

```text
20
5.4
number
```

## 🔹 3. Boolean

A `Boolean` can have only two values:

* `true`
* `false`

```javascript
let isStudent = true;

console.log(isStudent);
console.log(typeof isStudent);
```

**Output:**

```text
true
boolean
```

## 🔹 4. Undefined

A variable has the value `undefined` when it has been declared but no value has been assigned to it.

```javascript
let city;

console.log(city);
console.log(typeof city);
```

**Output:**

```text
undefined
undefined
```

## 🔹 5. Null

`null` represents an intentional absence of a value.

```javascript
let address = null;

console.log(address);
console.log(typeof address);
```

**Output:**

```text
null
object
```

> **Note:** `typeof null` returns `"object"`. This is a historical behavior in JavaScript.

## 🔹 6. BigInt

`BigInt` is used for very large integer values that cannot be safely represented by the regular `Number` type.

```javascript
let bigNumber = 12345678901234567890n;

console.log(bigNumber);
console.log(typeof bigNumber);
```

**Output:**

```text
12345678901234567890n
bigint
```

## 🔹 7. Symbol

`Symbol` is used to create unique values.

```javascript
let id = Symbol("id");

console.log(typeof id);
```

**Output:**

```text
symbol
```

## 🧠 JavaScript Data Types

| Data Type | Example        | `typeof` Result |
| --------- | -------------- | --------------- |
| String    | `"Hello"`      | `string`        |
| Number    | `25`           | `number`        |
| Boolean   | `true`         | `boolean`       |
| Undefined | `undefined`    | `undefined`     |
| Null      | `null`         | `object`        |
| BigInt    | `123n`         | `bigint`        |
| Symbol    | `Symbol("id")` | `symbol`        |

## 🔍 Using `typeof`

The `typeof` operator is used to find the type of a value.

```javascript
let name = "Anjali";
let age = 20;
let isStudent = true;

console.log(typeof name);
console.log(typeof age);
console.log(typeof isStudent);
```

**Output:**

```text
string
number
boolean
```

## 💻 Practice

Today I practiced:

* Creating variables with different data types
* Using strings and numbers
* Working with boolean values
* Understanding `undefined` and `null`
* Learning about `BigInt` and `Symbol`
* Using `typeof` to check data types

## 📁 Practice Files

```text
02-data-types/
│
├── string.js
├── number.js
├── boolean.js
├── undefined.js
├── null.js
├── bigint.js
└── symbol.js
```

## 🎯 Day 2 Goal

Build a clear understanding of **JavaScript data types** and learn how to identify them using the `typeof` operator.

### 🚀 Progress

**Day 2 — Data Types ✅**

> Learning the building blocks of JavaScript, one day at a time! 💻🚀
> ## 🗓️ Day 3 — Operators

### 📚 Topic

**Operators in JavaScript**

Today I learned about the basic operators used to perform calculations, assign values, and compare values.

### 🔹 What I Learned

* **Arithmetic Operators**

  * `+` Addition
  * `-` Subtraction
  * `*` Multiplication
  * `/` Division
  * `%` Modulus
  * `**` Exponentiation

* **Assignment Operators**

  * `=` Assignment
  * `+=` Add and assign
  * `-=` Subtract and assign
  * `*=` Multiply and assign
  * `/=` Divide and assign

* **Comparison Operators**

  * `==` Equal to
  * `===` Strictly equal to
  * `!=` Not equal to
  * `!==` Strictly not equal to
  * `>` Greater than
  * `<` Less than
  * `>=` Greater than or equal to
  * `<=` Less than or equal to

### 💻 Practice

```js
// Arithmetic Operators
let a = 10;
let b = 3;

console.log(a + b);  // 13
console.log(a - b);  // 7
console.log(a * b);  // 30
console.log(a / b);  // 3.333...
console.log(a % b);  // 1
console.log(a ** b); // 1000

// Assignment Operators
let score = 10;

score += 5;
console.log(score); // 15

score -= 3;
console.log(score); // 12

// Comparison Operators
console.log(10 > 5);     // true
console.log(10 < 5);     // false
console.log(10 === 10);  // true
console.log(10 !== 5);   // true
```

### 📝 Key Takeaway

I learned how JavaScript operators are used to **calculate values, update variables, and compare data**.

**Day 3 completed ✅**
Day 4 — Logical Operators

Today you'll learn the three main logical operators in JavaScript:

1. && — AND

Returns true only when both conditions are true.

let age = 20;
let hasId = true;

console.log(age >= 18 && hasId); // true
2. || — OR

Returns true when at least one condition is true.

let isWeekend = false;
let isHoliday = true;

console.log(isWeekend || isHoliday); // true
3. ! — NOT

Reverses a Boolean value.

let isLoggedIn = true;

console.log(!isLoggedIn); // false
Quick practice

Try to predict the output before running each:

console.log(true && true);
console.log(true && false);
console.log(false || true);
console.log(false || false);
console.log(!true);
console.log(!false);
🏋️ Day 4 Exercises

Exercise 1: Create variables:

let age = 22;
let hasLicense = true;

Write a condition that checks whether the person is 18 or older AND has a license.

Exercise 2: Create:

let isStudent = true;
let isEmployee = false;

Check whether the person is a student OR an employee.

Exercise 3: Create:

let isRaining = false;

Use ! to check whether it is not raining.

Challenge:

let age = 25;
let hasTicket = true;
let isVIP = false;

A person can enter an event if they are 18+ AND have a ticket, OR if they are a VIP.

Write the logical condition for this.
## Day 5 — Strings

Today I learned about **Strings in JavaScript** and practiced using different string methods.

### 📚 Topics Covered

* Creating and working with strings
* String properties
* Common string methods
* Accessing characters in a string
* Converting strings to uppercase and lowercase
* Finding and extracting parts of a string
* Replacing text within a string

### 💻 Practice

I practiced methods such as:

* `length`
* `toUpperCase()`
* `toLowerCase()`
* `charAt()`
* `includes()`
* `indexOf()`
* `slice()`
* `substring()`
* `replace()`
* `trim()`

### 🎯 Goal

Understand how to manipulate and work with strings effectively in JavaScript through hands-on practice.

**Day 5 completed! ✅**
# 📅 Day 6 — Numbers & Math

Welcome to **Day 6 of my JavaScript learning journey!** 🚀

Today, I learned about **Numbers and Math methods in JavaScript**. I practiced different ways to work with numbers and perform mathematical operations using the built-in `Math` object.

## 📚 What I Learned

Today I learned about:

* Number data type
* Basic mathematical operations
* `Math.round()`
* `Math.floor()`
* `Math.ceil()`
* `Math.trunc()`
* `Math.abs()`
* `Math.pow()`
* `Math.sqrt()`
* `Math.max()`
* `Math.min()`
* `Math.random()`
* Using `console.log()` to display results

---

## 🔹 1. Numbers in JavaScript

JavaScript uses the `Number` data type to store both integers and decimal numbers.

```javascript
let age = 20;
let price = 99.99;

console.log(age);
console.log(price);
```

**Output:**

```text
20
99.99
```

---

## 🔹 2. Basic Arithmetic Operations

We can perform mathematical calculations using operators such as:

* `+` → Addition
* `-` → Subtraction
* `*` → Multiplication
* `/` → Division
* `%` → Remainder
* `**` → Power

```javascript
let a = 10;
let b = 3;

console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);
console.log(a % b);
console.log(a ** b);
```

**Output:**

```text
13
7
30
3.3333333333333335
1
1000
```

---

## 🔹 3. `Math.round()`

`Math.round()` rounds a number to the nearest integer.

```javascript
console.log(Math.round(4.6));
console.log(Math.round(4.3));
```

**Output:**

```text
5
4
```

👉 **Easy trick:** `round` = nearest number.

---

## 🔹 4. `Math.floor()`

`Math.floor()` rounds a number **down** to the nearest integer.

```javascript
console.log(Math.floor(4.9));
```

**Output:**

```text
4
```

👉 **Easy trick:** `floor` = go down.

---

## 🔹 5. `Math.ceil()`

`Math.ceil()` rounds a number **up** to the nearest integer.

```javascript
console.log(Math.ceil(4.1));
```

**Output:**

```text
5
```

👉 **Easy trick:** `ceil` = ceiling = go up.

---

## 🔹 6. `Math.trunc()`

`Math.trunc()` removes the decimal part without rounding.

```javascript
console.log(Math.trunc(9.87));
```

**Output:**

```text
9
```

👉 **Easy trick:** `trunc` = remove decimal.

---

## 🔹 7. `Math.abs()`

`Math.abs()` returns the positive value of a number.

```javascript
console.log(Math.abs(-25));
```

**Output:**

```text
25
```

👉 **Easy trick:** `abs` = absolute value.

---

## 🔹 8. `Math.pow()`

`Math.pow()` is used to calculate the power of a number.

```javascript
console.log(Math.pow(2, 3));
```

**Output:**

```text
8
```

This means:

```text
2³ = 8
```

We can also use the `**` operator:

```javascript
console.log(2 ** 3);
```

**Output:**

```text
8
```

---

## 🔹 9. `Math.sqrt()`

`Math.sqrt()` returns the square root of a number.

```javascript
console.log(Math.sqrt(25));
```

**Output:**

```text
5
```

---

## 🔹 10. `Math.max()`

`Math.max()` returns the largest number.

```javascript
console.log(Math.max(10, 25, 5, 40, 15));
```

**Output:**

```text
40
```

👉 **Easy trick:** `max` = maximum = biggest.

---

## 🔹 11. `Math.min()`

`Math.min()` returns the smallest number.

```javascript
console.log(Math.min(10, 25, 5, 40, 15));
```

**Output:**

```text
5
```

👉 **Easy trick:** `min` = minimum = smallest.

---

## 🔹 12. `Math.random()`

`Math.random()` generates a random decimal number between `0` and less than `1`.

```javascript
console.log(Math.random());
```

Example output:

```text
0.73648291
```

The output will be different each time.

### Random number from 1 to 10

```javascript
let number = Math.floor(Math.random() * 10) + 1;

console.log(number);
```

This gives a random number between:

```text
1 → 10
```

---

## 🧠 Quick Revision

| Method          | Meaning         | Example           | Result |
| --------------- | --------------- | ----------------- | ------ |
| `Math.round()`  | Nearest integer | `Math.round(4.6)` | `5`    |
| `Math.floor()`  | Round down      | `Math.floor(4.9)` | `4`    |
| `Math.ceil()`   | Round up        | `Math.ceil(4.1)`  | `5`    |
| `Math.trunc()`  | Remove decimal  | `Math.trunc(4.9)` | `4`    |
| `Math.abs()`    | Positive value  | `Math.abs(-10)`   | `10`   |
| `Math.pow()`    | Power           | `Math.pow(2,3)`   | `8`    |
| `Math.sqrt()`   | Square root     | `Math.sqrt(25)`   | `5`    |
| `Math.max()`    | Largest value   | `Math.max(2,8,5)` | `8`    |
| `Math.min()`    | Smallest value  | `Math.min(2,8,5)` | `2`    |
| `Math.random()` | Random number   | `Math.random()`   | `0–<1` |

## 💻 Practice

Today I practiced creating programs using numbers and `Math` methods, including:

1. Finding the largest number.
2. Finding the smallest number.
3. Finding the square root.
4. Rounding decimal numbers.
5. Removing decimal values.
6. Finding the absolute value.
7. Generating random numbers.
8. Creating a random number between 1 and 10.

## 🎯 Key Takeaway

Today I learned that JavaScript provides the built-in **`Math` object** to perform many mathematical operations easily.

I'm getting more comfortable with JavaScript **one day at a time!** 🚀💻

**#JavaScript #100DaysOfCode #LearningJavaScript #WebDevelopment #CodingJourney #Day6 #Programming**




