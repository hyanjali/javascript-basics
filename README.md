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


