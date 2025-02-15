# learn-PHP-from-scratch

[<img src="https://www.php.net/images/logos/php-logo-white.svg" width="250">](https://php.net/)

A curated list of resources for [PHP](https://php.net/)

# 🚀 PHP Learning Roadmap - One Month Guide

Welcome to the **PHP Learning Roadmap**! This guide is designed to help you master PHP from scratch in just **one month**. Follow this structured learning path to build a solid foundation and develop real-world PHP applications. 💡

---
## 📅 Week 1: PHP Basics
✅ **Goal:** Understand PHP syntax, basic programming concepts, and how PHP interacts with HTML.

### **[Day 1: Introduction to PHP](#introduction-to-php)**
- [What is PHP?](#1%EF%B8%8F⃣-what-is-php)
- [Installing XAMPP/WAMP/LAMP for local development](#2%EF%B8%8F⃣-installing-xamppwamplamp-for-local-development)
- [Writing your first PHP script](#3%EF%B8%8F⃣-writing-your-first-php-script) (`echo`, `phpinfo()`)
- [Running PHP scripts in a browser](#4%EF%B8%8F⃣-running-php-scripts-in-a-browser)

### **[Day 2](#day-2): PHP Syntax & Variables**
- [PHP tags](#1%EF%B8%8F⃣-php-tags-php-) (`<?php ?>`)
- [Variables](#3%EF%B8%8F⃣-php-data-types
) and [data types](#2%EF%B8%8F⃣-variables-in-php) *(String, Integer, Float, Boolean, Array, Object)*
- [Constants](#4%EF%B8%8F⃣-constants-in-php-define--const) (`define()`, `const`)
- [PHP comments](#5%EF%B8%8F⃣-php-comments)
- [practices Questions](practice-questions.md#day-2)

### **[Day 3](#day-3-operators-in-php-1): Operators in PHP**
- [Arithmetic Operators](#1%EF%B8%8F%E2%83%A3-arithmetic-operators) *(+, -, *, /, %)*
- [Comparison Operators](#2%EF%B8%8F⃣-comparison-operators) *(==, !=, >, <, >=, <=)*
- [Logical Operators](#3%EF%B8%8F⃣-logical-operators) *(&&, ||, !)*
- [Assignment Operators](#4%EF%B8%8F⃣-assignment-operators)

### **[Day 4](#day-4-conditional-statements-in-php): Conditional Statements**
- [`if`](#-if-statement), [`else`](#-if-else-statement), [`elseif`](#-if-elseif-else-statement)
- [`switch`](#2-switch-statement) statements

### **[Day 5](#-day-5-loops-in-php): Loops**
- [`for`](#-1%EF%B8%8F⃣-for-loop), [`while`](#-2%EF%B8%8F⃣-while-loop), [`do-while`](#-3%EF%B8%8F⃣-do-while-loop)
- [`foreach`](#-4%EF%B8%8F⃣-foreach-loop-for-arrays) for arrays

### **[Day 6: Arrays](#day-6-arrays-in-php-)**
- [`Indexed`](#-indexed-arrays-numeric-keys), [`Associative`](#-associative-arrays-key-value-pairs), and [`Multidimensional`](#-multidimensional-arrays-arrays-inside-arrays) arrays
- Array functions *([`array_push()`](#-adding-elements-array_push), [`array_pop()`](#-removing-last-element-array_pop), [`count()`](#-counting-elements-count), [`sort()`](#-sorting-an-array-sort), [`explode()`](#-converting-string-to-array-explode))*

### **[Day 7](): Functions in PHP**
- Defining and [`calling`]() functions
- Function parameters and return values
- Built-in PHP functions *([`isset()`](), [`empty()`](), [`var_dump()`]())*

---
## 📅 Week 2: Intermediate PHP
✅ **Goal:** Learn form handling, file handling, and error handling.

### **Day 8: Strings and String Functions**
- `strlen()`, `str_replace()`, `substr()`, `explode()`, `trim()`
- **Practice:** Reverse a string

### **Day 9: Forms and User Input Handling**
- `$_GET` vs `$_POST`
- Handling form data securely

### **Day 10: Superglobals**
- `$_SERVER`, `$_FILES`, `$_REQUEST`

### **Day 11: File Handling**
- Reading and writing files *(fopen(), fwrite(), fread())*
- Uploading files *(move_uploaded_file())*

### **Day 12: Error Handling**
- `try-catch` blocks
- Handling warnings and errors (`error_reporting()`)

### **Day 13: Sessions in PHP**
- Start and use sessions (`$_SESSION`)
- Logout mechanism

### **Day 14: Cookies in PHP**
- Setting, retrieving, and deleting cookies

---
## 📅 Week 3: Database and OOP in PHP
✅ **Goal:** Learn MySQL and Object-Oriented Programming.

### **Day 15: Introduction to MySQL**
- What is a database?
- SQL basics *(SELECT, INSERT, UPDATE, DELETE)*

### **Day 16: Connecting PHP with MySQL**
- `mysqli` vs `PDO`
- Fetching data from a database

### **Day 17: CRUD Operations**
- Create, Read, Update, Delete operations using PHP

### **Day 18: Prepared Statements and Security**
- Preventing SQL Injection
- Using prepared statements (`mysqli_prepare()`)

### **Day 19: Object-Oriented PHP (OOP) - Basics**
- Classes and Objects
- Constructors and Destructors

### **Day 20: OOP Advanced**
- Inheritance, Encapsulation, and Polymorphism

### **Day 21: Working with APIs**
- Using `cURL` and `file_get_contents()`

---
## 📅 Week 4: Advanced PHP Concepts
✅ **Goal:** Learn MVC, Authentication, and build a project.

### **Day 22: Introduction to MVC (Model-View-Controller)**
- Understanding MVC architecture

### **Day 23: Authentication System**
- User Registration & Login System

### **Day 24: Email Sending in PHP**
- Using PHPMailer

### **Day 25: PHP Frameworks Overview**
- Laravel, CodeIgniter *(Introduction)*

### **Day 26-28: PHP Project**
- Build a **Blog System** / CRUD Application

### **Day 29: Debugging & Optimization**
- Debugging tools (`var_dump()`, `print_r()`)

### **Day 30: Deployment**
- Hosting a PHP website

---
## 📚 Recommended Resources
🔗 [PHP Official Website](https://www.php.net/)
🔗 [W3Schools PHP Tutorial](https://www.w3schools.com/php/)
🔗 [PHP MySQL Tutorial](https://www.tutorialspoint.com/php/php_mysql_intro.htm)
🔗 [YouTube: PHP Full Course](https://www.youtube.com/watch?v=OK_JCtrrv-c)

---
## 🎯 Final Project Idea
After completing this roadmap, challenge yourself by building a **Personal Blog System** or a **Mini E-commerce Website** to showcase your PHP skills.

🌟 **Happy Coding!** 🚀

---

# Week 1  **Day 1**

# Introduction to PHP
## 1️⃣ What is PHP?
PHP (**Hypertext Preprocessor**) is a popular **server-side scripting language** primarily used for web development. It enables developers to create **dynamic and interactive web pages**.

### 🔹 Key Features of PHP:
- ✅ Open-source and free to use.
- ✅ Works on multiple platforms (**Windows, Linux, macOS**).
- ✅ Supports databases like **MySQL, PostgreSQL**, etc.
- ✅ Easily integrates with **HTML, CSS, and JavaScript**.
- ✅ Executes on the **server** and sends the output to the client’s browser.

### 💡 Example:
```php
<?php
    echo "Hello, World!";
?>
```
**Output:** `Hello, World!` in a web browser.

---

## 2️⃣ Installing XAMPP/WAMP/LAMP for Local Development
Since PHP is a **server-side** language, you need a **local server environment** to run PHP scripts on your computer. The most commonly used PHP development stacks are:

- ✅ **XAMPP** (Windows, macOS, Linux) *(Recommended for Beginners)*
- ✅ **WAMP** (Windows)
- ✅ **LAMP** (Linux)

### 🔹 Steps to Install **XAMPP**:
1. **Download** XAMPP from [Apache Friends](https://www.apachefriends.org/).
2. **Install and Open** XAMPP Control Panel.
3. **Start Apache** (for PHP) and **MySQL** (for databases).

---

## 3️⃣ Writing Your First PHP Script
Once XAMPP/WAMP/LAMP is installed, let's create and run a simple **PHP script**.

### 🔹 Steps to Write Your First PHP Script:
1. **Open** the `htdocs` folder (inside the XAMPP directory).
2. **Create a new file:** `first.php`
3. **Write the following code:**
```php
<?php
    echo "Welcome to PHP!";
?>
```
4. **Save the file.**

---

## 4️⃣ Running PHP Scripts in a Browser
Now, let's execute the PHP script in your browser.

### 🔹 Steps:
1. **Open XAMPP Control Panel** → Start **Apache**.
2. **Open a browser** and type:
```
http://localhost/first.php
```
3. **Press Enter** and see the output:
```
Welcome to PHP!
```

### 💡 Alternative Method *(Without XAMPP)*:
use an **Online PHP Compiler** to test simple scripts.

### 🎯 Congratulations! 🎯
You've successfully set up **PHP** and executed your first script. Keep learning and coding! 🚀

---
---
# Day 2: 

## PHP Syntax & Variables
## 1️⃣ PHP Tags (`<?php ?>`)
Every PHP script starts and ends with PHP tags, which tell the server where the PHP code begins and ends.

### 🔹 Example:
```php
<?php
    echo "Hello, PHP!";
?>
```
### ✅ Key Points:
- PHP code is enclosed within `<?php ?>`.
- PHP statements end with a **semicolon (`;`)**.
- The **`echo`** statement prints output to the screen.

---

## 2️⃣ Variables in PHP
A variable is used to store data, such as numbers or text, which can be reused in a script.

### ✅ Variable Rules:
- Starts with a **`$` sign** (e.g., `$name`).
- Must start with a **letter** or **underscore (`_`)**.
- Cannot start with a **number**.
- **Case-sensitive** (`$age` and `$AGE` are different).

### 🔹 Example:
```php
<?php
    $name = "John";
    $age = 25;
    echo "My name is " . $name . " and I am " . $age . " years old.";
?>
```
### 🔹 Output:
```
My name is John and I am 25 years old.
```

---

## 3️⃣ PHP Data Types
PHP supports various **data types**, which define the type of value a variable can hold.

| Data Type | Example |
|-----------|---------|
| **String** | "Hello, PHP!" |
| **Integer** | `25, -5, 1000` |
| **Float** | `3.14, -1.5, 0.99` |
| **Boolean** | `true, false` |
| **Array** | `["Apple", "Banana", "Mango"]` |
| **Object** | `new Car("BMW")` |

### 🔹 Example:
```php
<?php
    $string = "Hello, PHP!";
    $integer = 100;
    $float = 99.99;
    $boolean = true;
    $array = array("Apple", "Banana", "Mango");
    
    echo "String: " . $string . "<br>";
    echo "Integer: " . $integer . "<br>";
    echo "Float: " . $float . "<br>";
    echo "Boolean: " . $boolean . "<br>";
    echo "Array: " . implode(", ", $array) . "<br>";
?>
```
### 🔹 Output:
```
String: Hello, PHP!
Integer: 100
Float: 99.99
Boolean: 1
Array: Apple, Banana, Mango
```
✅ **`implode()`** converts an array to a string.

---

## 4️⃣ Constants in PHP (`define()` & `const`)
Constants are like variables, but their value **cannot be changed** once defined.

### **Using `define()` (Recommended)**
```php
<?php
    define("SITE_NAME", "MyPHPWebsite");
    echo "Welcome to " . SITE_NAME;
?>
```
### 🔹 Output:
```
Welcome to MyPHPWebsite
```

### **Using `const` (Used inside classes)**
```php
<?php
    const PI = 3.1416;
    echo "Value of PI: " . PI;
?>
```
### 🔹 Output:
```
Value of PI: 3.1416
```

---

## 5️⃣ PHP Comments
Comments are used to **write notes** or **disable code execution**.

### **Types of Comments:**

### ✅ Single-line comment (`//` or `#`)
```php
<?php
    // This is a single-line comment
    # Another single-line comment
    echo "PHP is fun!";
?>
```

### ✅ Multi-line comment (`/* ... */`)
```php
<?php
    /* This is a multi-line comment
       It spans multiple lines */
    echo "Learning PHP!";
?>
```

---

## 🎯 Congratulations! 🎯
You’ve learned **PHP Syntax, Variables, Data Types, Constants, and Comments**. Keep coding! 🚀

---
---
# Day 3: Operators in PHP

## 1️⃣ Arithmetic Operators
Arithmetic operators are used to perform mathematical operations on numbers.

| Operator | Description | Example | Result |
|----------|------------|---------|--------|
| + | Addition | `5 + 3` | `8` |
| - | Subtraction | `10 - 4` | `6` |
| * | Multiplication | `6 * 2` | `12` |
| / | Division | `10 / 2` | `5` |
| % | Modulus (Remainder) | `7 % 3` | `1` |

### Example:
```php
<?php
    $a = 10;
    $b = 5;
    
    echo "Addition: " . ($a + $b) . "<br>";
    echo "Subtraction: " . ($a - $b) . "<br>";
    echo "Multiplication: " . ($a * $b) . "<br>";
    echo "Division: " . ($a / $b) . "<br>";
    echo "Modulus: " . ($a % $b) . "<br>";
?>
```
**Output:**
```
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2
Modulus: 0
```

## 2️⃣ Comparison Operators
Comparison operators compare two values and return `true` (1) or `false` (0).

| Operator | Description | Example | Result |
|----------|------------|---------|--------|
| == | Equal | `$x == $y` | true if `$x` is equal to `$y` |
| != | Not equal | `$x != $y` | true if `$x` is not equal to `$y` |
| > | Greater than | `$x > $y` | true if `$x` is greater than `$y` |
| < | Less than | `$x < $y` | true if `$x` is less than `$y` |
| >= | Greater than or equal to | `$x >= $y` | true if `$x` is greater than or equal to `$y` |
| <= | Less than or equal to | `$x <= $y` | true if `$x` is less than or equal to `$y` |

### Example:
```php
<?php
    $x = 15;
    $y = 10;

    echo "Is x equal to y? " . ($x == $y) . "<br>";
    echo "Is x not equal to y? " . ($x != $y) . "<br>";
    echo "Is x greater than y? " . ($x > $y) . "<br>";
    echo "Is x less than or equal to y? " . ($x <= $y) . "<br>";
?>
```
**Output:**
```
Is x equal to y? 
Is x not equal to y? 1
Is x greater than y? 1
Is x less than or equal to y? 
```
(Note: `true` is displayed as `1`, and `false` is empty.)

## 3️⃣ Logical Operators
Logical operators are used to combine multiple conditions.

| Operator | Description | Example | Result |
|----------|------------|---------|--------|
| && | AND (Both conditions must be true) | `$x > 5 && $x < 20` | true if both conditions are true |
| \|\| | OR (At least one condition must be true) | `$x > 10 || $x < 20` | true if at least one condition is true |
| ! | NOT (Reverses the result) | `!($x > 5)` | true if `$x > 5` is false |

### Example:
```php
<?php
    $a = 8;
    $b = 15;

    echo "AND Operator: " . ($a > 5 && $b < 20) . "<br>";
    echo "OR Operator: " . ($a > 10 || $b < 20) . "<br>";
    echo "NOT Operator: " . !($a > 10) . "<br>";
?>
```
**Output:**
```
AND Operator: 1
OR Operator: 1
NOT Operator: 1
```

## 4️⃣ Assignment Operators
Assignment operators are used to assign values to variables.

| Operator | Example | Equivalent To |
|----------|---------|--------------|
| = | `$x = 5` | `$x = 5` |
| += | `$x += 3` | `$x = $x + 3` |
| -= | `$x -= 2` | `$x = $x - 2` |
| *= | `$x *= 4` | `$x = $x * 4` |
| /= | `$x /= 2` | `$x = $x / 2` |
| %= | `$x %= 3` | `$x = $x % 3` |

### Example:
```php
<?php
    $num = 10;

    $num += 5; // Equivalent to $num = $num + 5
    echo "After += : " . $num . "<br>";

    $num -= 3; // Equivalent to $num = $num - 3
    echo "After -= : " . $num . "<br>";

    $num *= 2; // Equivalent to $num = $num * 2
    echo "After *= : " . $num . "<br>";

    $num /= 2; // Equivalent to $num = $num / 2
    echo "After /= : " . $num . "<br>";

    $num %= 4; // Equivalent to $num = $num % 4
    echo "After %= : " . $num . "<br>";
?>
```
**Output:**
```
After += : 15
After -= : 12
After *= : 24
After /= : 12
After %= : 0
```
---
---
# Day 4: Conditional Statements in PHP

Conditional statements in PHP allow a program to execute different code blocks based on conditions. They help in making dynamic decisions within a script.

## 1 if, else, and elseif Statements
These statements check conditions and execute code based on whether the condition is true or false.

### 🔹 if Statement
Executes a block of code only if the condition is true.

#### Syntax:
```php
if (condition) {
    // Code to execute if condition is true
}
```
#### Example:
```php
<?php
    $age = 20;

    if ($age >= 18) {
        echo "You are eligible to vote.";
    }
?>
```
#### Output:
```
You are eligible to vote.
```

### 🔹 if-else Statement
Executes one block if the condition is true, otherwise executes another block.

#### Syntax:
```php
if (condition) {
    // Code if condition is true
} else {
    // Code if condition is false
}
```
#### Example:
```php
<?php
    $temperature = 30;

    if ($temperature > 25) {
        echo "It's a hot day!";
    } else {
        echo "It's a cool day.";
    }
?>
```
#### Output:
```
It's a hot day!
```

### 🔹 if-elseif-else Statement
Allows checking multiple conditions.

#### Syntax:
```php
if (condition1) {
    // Code if condition1 is true
} elseif (condition2) {
    // Code if condition2 is true
} else {
    // Code if all conditions are false
}
```
#### Example:
```php
<?php
    $score = 85;

    if ($score >= 90) {
        echo "Grade: A";
    } elseif ($score >= 75) {
        echo "Grade: B";
    } elseif ($score >= 50) {
        echo "Grade: C";
    } else {
        echo "Grade: F (Fail)";
    }
?>
```
#### Output:
```
Grade: B
```

## 2 switch Statement
The `switch` statement is used when you have multiple conditions to check against a single value.

#### Syntax:
```php
switch (variable) {
    case value1:
        // Code to execute if variable == value1
        break;
    case value2:
        // Code to execute if variable == value2
        break;
    default:
        // Code to execute if no case matches
}
```
#### Example:
```php
<?php
    $day = "Monday";

    switch ($day) {
        case "Monday":
            echo "Start of the work week!";
            break;
        case "Friday":
            echo "Weekend is coming!";
            break;
        case "Sunday":
            echo "Enjoy your weekend!";
            break;
        default:
            echo "It's a regular day.";
    }
?>
```
#### Output:
```
Start of the work week!
```

### 🔹 switch vs if-elseif-else
✅ Use `if-elseif-else` when conditions involve complex expressions.
✅ Use `switch` when checking a variable against multiple values.

---
🚀 Keep coding and mastering PHP! Stay tuned for more. Happy Learning! 😊

---

---

# 🚀 Day 5: Loops in PHP

Loops in PHP allow you to execute a block of code multiple times based on a condition. They are essential for handling repetitive tasks such as iterating over arrays, processing user input, or fetching database records.
---

## 🔄 1️⃣ for Loop
The **for** loop is used when the number of iterations is known beforehand.

### 🔹 Syntax:
```php
for (initialization; condition; increment/decrement) {
    // Code to execute
}
```

### 🔹 Example: Print numbers from 1 to 5
```php
<?php
    for ($i = 1; $i <= 5; $i++) {
        echo "Number: $i <br>";
    }
?>
```
✅ **Output:**
```
Number: 1  
Number: 2  
Number: 3  
Number: 4  
Number: 5  
```

---

## 🔄 2️⃣ while Loop
The **while** loop executes as long as the condition is true. It is useful when the number of iterations is not known in advance.

### 🔹 Syntax:
```php
while (condition) {
    // Code to execute
}
```

### 🔹 Example: Print numbers from 1 to 5
```php
<?php
    $i = 1;
    while ($i <= 5) {
        echo "Number: $i <br>";
        $i++;
    }
?>
```
✅ **Output:**
```
Number: 1  
Number: 2  
Number: 3  
Number: 4  
Number: 5  
```

---

## 🔄 3️⃣ do-while Loop
The **do-while** loop is similar to while, but it executes the code **at least once**, even if the condition is false.

### 🔹 Syntax:
```php
do {
    // Code to execute
} while (condition);
```

### 🔹 Example: Print numbers from 1 to 5
```php
<?php
    $i = 1;
    do {
        echo "Number: $i <br>";
        $i++;
    } while ($i <= 5);
?>
```
✅ **Output:**
```
Number: 1  
Number: 2  
Number: 3  
Number: 4  
Number: 5  
```

### 🔹 Example: Demonstrating at least one execution
```php
<?php
    $x = 10;
    do {
        echo "Executed once!";
    } while ($x < 5);
?>
```
✅ **Output:**
```
Executed once!
```
(Even though `$x < 5` is false, the loop still runs once.)

---

## 🔄 4️⃣ foreach Loop (For Arrays)
The **foreach** loop is specifically designed for iterating over arrays.

### 🔹 Syntax:
```php
foreach ($array as $value) {
    // Code to execute
}
```

### 🔹 Example: Iterate through an indexed array
```php
<?php
    $colors = array("Red", "Green", "Blue");
    foreach ($colors as $color) {
        echo "$color <br>";
    }
?>
```
✅ **Output:**
```
Red  
Green  
Blue  
```

### 🔹 Example: Iterate through an associative array
```php
<?php
    $person = array("Name" => "John", "Age" => 25, "City" => "New York");
    foreach ($person as $key => $value) {
        echo "$key: $value <br>";
    }
?>
```
✅ **Output:**
```
Name: John  
Age: 25  
City: New York  
```

---
🚀 Keep coding and exploring PHP loops! 🔥
📌 **Follow me on GitHub for more PHP learning resources!** 👨‍💻🚀

---

---

# Day 6: Arrays in PHP 🚀

Arrays in PHP allow you to store multiple values in a single variable, making data management and manipulation more efficient. Let's explore the different types of arrays and some useful functions! 🔥

---

## 📌 1. Types of Arrays in PHP

### 🔹 Indexed Arrays (Numeric Keys)
An indexed array stores elements with numeric indices (starting from 0).

#### ✅ Creating an Indexed Array:
```php
<?php
    $fruits = array("Apple", "Banana", "Cherry");
    echo $fruits[0]; // Output: Apple
?>
```

#### ✅ Looping Through an Indexed Array:
```php
<?php
    $colors = ["Red", "Green", "Blue"];
    foreach ($colors as $color) {
        echo "$color <br>";
    }
?>
```
📝 **Output:**
```
Red  
Green  
Blue  
```

---

### 🔹 Associative Arrays (Key-Value Pairs)
Associative arrays use custom keys instead of numeric indices.

#### ✅ Creating an Associative Array:
```php
<?php
    $person = array("Name" => "John", "Age" => 25, "City" => "New York");
    echo $person["Name"]; // Output: John
?>
```

#### ✅ Looping Through an Associative Array:
```php
<?php
    foreach ($person as $key => $value) {
        echo "$key: $value <br>";
    }
?>
```
📝 **Output:**
```
Name: John  
Age: 25  
City: New York  
```

---

### 🔹 Multidimensional Arrays (Arrays Inside Arrays)
Multidimensional arrays contain one or more arrays within them.

#### ✅ Creating a Multidimensional Array:
```php
<?php
    $students = array(
        array("Alice", 85, "A"),
        array("Bob", 78, "B"),
        array("Charlie", 92, "A+")
    );
    echo $students[1][0]; // Output: Bob
?>
```

#### ✅ Looping Through a Multidimensional Array:
```php
<?php
    foreach ($students as $student) {
        echo "Name: $student[0], Marks: $student[1], Grade: $student[2] <br>";
    }
?>
```
📝 **Output:**
```
Name: Alice, Marks: 85, Grade: A  
Name: Bob, Marks: 78, Grade: B  
Name: Charlie, Marks: 92, Grade: A+  
```

---

## 🔥 2. Useful Array Functions in PHP

### 🔹 Adding Elements: `array_push()`
```php
<?php
    $fruits = ["Apple", "Banana"];
    array_push($fruits, "Cherry", "Mango");
    print_r($fruits);
?>
```
📝 **Output:**
```
Array ( [0] => Apple [1] => Banana [2] => Cherry [3] => Mango )
```

### 🔹 Removing Last Element: `array_pop()`
```php
<?php
    $fruits = ["Apple", "Banana", "Cherry"];
    array_pop($fruits);
    print_r($fruits);
?>
```
📝 **Output:**
```
Array ( [0] => Apple [1] => Banana )
```

### 🔹 Counting Elements: `count()`
```php
<?php
    $fruits = ["Apple", "Banana", "Cherry"];
    echo count($fruits); // Output: 3
?>
```

### 🔹 Sorting an Array: `sort()`
```php
<?php
    $numbers = [4, 2, 8, 1];
    sort($numbers);
    print_r($numbers);
?>
```
📝 **Output:**
```
Array ( [0] => 1 [1] => 2 [2] => 4 [3] => 8 )
```

### 🔹 Converting String to Array: `explode()`
```php
<?php
    $text = "Apple,Banana,Cherry";
    $fruits = explode(",", $text);
    print_r($fruits);
?>
```
📝 **Output:**
```
Array ( [0] => Apple [1] => Banana [2] => Cherry )
```
---
📌 **Next Step:** Explore **array_merge()**, **array_filter()**, and advanced PHP array functions. Stay tuned for Day 7! 🚀

📢 **Follow me on GitHub for more updates!** 😃
---
---
# Day 7: Functions in PHP

## 📌 Introduction
Functions in PHP allow you to write reusable blocks of code, making your programs more efficient and modular. They help organize logic, reduce redundancy, and improve code readability.

---

## 🔹 Defining and Calling Functions
A function is a block of code that runs only when it is called.

### ✅ Syntax
```php
function functionName() {
    // Code to be executed
}
```

### ✅ Example: Creating and Calling a Function
```php
<?php
    function sayHello() {
        echo "Hello, PHP! <br>";
    }
    
    sayHello(); // Function Call
?>
```
#### 🖥 Output:
```
Hello, PHP!
```

---

## 🔹 Function Parameters and Return Values

### ✅ Passing Parameters to Functions
```php
<?php
    function greet($name) {
        echo "Hello, $name! <br>";
    }
    
    greet("Alice"); // Output: Hello, Alice!
    greet("Bob");   // Output: Hello, Bob!
?>
```

### ✅ Default Parameter Values
```php
<?php
    function greet($name = "Guest") {
        echo "Hello, $name! <br>";
    }
    
    greet();        // Output: Hello, Guest!
    greet("David"); // Output: Hello, David!
?>
```

### ✅ Returning Values from a Function
```php
<?php
    function add($a, $b) {
        return $a + $b;
    }
    
    $sum = add(5, 10);
    echo "Sum: $sum"; // Output: Sum: 15
?>
```

---

## 🔹 Built-in PHP Functions
PHP provides many built-in functions to perform common operations.

### ✅ `isset()` – Check if a Variable is Set
```php
<?php
    $name = "Alice";
    echo isset($name) ? "Variable is set" : "Variable is not set";
    // Output: Variable is set
?>
```

### ✅ `empty()` – Check if a Variable is Empty
```php
<?php
    $var = "";
    echo empty($var) ? "Variable is empty" : "Variable is not empty";
    // Output: Variable is empty
?>
```

### ✅ `var_dump()` – Print Detailed Variable Information
```php
<?php
    $num = 10;
    $text = "Hello";
    $arr = array(1, 2, 3);

    var_dump($num);
    var_dump($text);
    var_dump($arr);
?>
```
#### 🖥 Output:
```
int(10)  
string(5) "Hello"  
array(3) { [0]=> int(1) [1]=> int(2) [2]=> int(3) }
```

---
---
---
# 📌 Day 8: Strings and String Functions in PHP

## 🔥 Introduction
Strings are a fundamental part of PHP and are used to store and manipulate text. PHP provides several built-in functions to work with strings effectively. Let's explore some of the most commonly used string functions!

---

## 1️⃣ Important String Functions in PHP

### 📌 `strlen()` – Get the Length of a String
The `strlen()` function returns the number of characters in a string, including spaces.

```php
<?php
    $text = "Hello, PHP!";
    echo strlen($text); // Output: 11
?>
```

### 📌 `str_replace()` – Replace Substrings in a String
The `str_replace()` function replaces occurrences of a substring with another string.

```php
<?php
    $text = "I love PHP!";
    $newText = str_replace("PHP", "Python", $text);
    echo $newText; // Output: I love Python!
?>
```

### 📌 `substr()` – Extract a Part of a String
The `substr()` function extracts a portion of a string.

```php
<?php
    $text = "Hello, World!";
    echo substr($text, 0, 5);  // Output: Hello
    echo substr($text, -6);    // Output: World!
?>
```

### 📌 `explode()` – Split a String into an Array
The `explode()` function splits a string into an array based on a delimiter.

```php
<?php
    $text = "apple,banana,grape";
    $fruits = explode(",", $text);
    print_r($fruits);
?>
```

📌 **Output:**
```
Array ( [0] => apple [1] => banana [2] => grape )
```

### 📌 `trim()` – Remove Spaces from the Beginning and End
The `trim()` function removes whitespace (spaces, newlines, tabs) from the start and end of a string.

```php
<?php
    $text = "  Hello, World!  ";
    echo trim($text); // Output: "Hello, World!"
?>
```

---

## 2️⃣ Practice: Reverse a String
Write a function to reverse a string using `strrev()`.

```php
<?php
    function reverseString($str) {
        return strrev($str);
    }

    echo reverseString("PHP"); // Output: PHP
?>
```

---
---
# **Day 9: Forms and User Input Handling in PHP**

Forms are an essential part of web development, allowing users to interact with a website by submitting data. PHP provides two primary methods for handling form data: **$_GET** and **$_POST**.

---

## 1. $_GET vs $_POST

### $_GET Method
- Sends form data as URL parameters (visible in the browser).
- Best for search queries, filtering, and retrieving data.
- Not secure for sensitive data like passwords.
- Has a character limit (~2048 characters).

**Example:**
```php
<form method="GET" action="process.php">
    Name: <input type="text" name="username">
    <input type="submit" value="Submit">
</form>
```
**Processing in PHP (process.php):**
```php
<?php
    if(isset($_GET['username'])){
        echo "Hello, " . $_GET['username'];
    }
?>
```
📌 **URL Example:** `process.php?username=John`

---

### $_POST Method
- Sends form data in the request body (hidden from the URL).
- Used for login forms, user registration, and secure data submissions.
- No size limit on data.
- More secure than $_GET.

**Example:**
```php
<form method="POST" action="process.php">
    Name: <input type="text" name="username">
    <input type="submit" value="Submit">
</form>
```
**Processing in PHP (process.php):**
```php
<?php
    if(isset($_POST['username'])){
        echo "Hello, " . $_POST['username'];
    }
?>
```
📌 **Data is not visible in the URL.**

---

## 2. Handling Form Data Securely
To prevent security vulnerabilities like **XSS (Cross-Site Scripting)** and **SQL Injection**, it's crucial to validate and sanitize user input.

### Validate User Input
Ensure input fields are not empty and follow the required format.
```php
<?php
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        if (empty($_POST["username"])) {
            echo "Name is required!";
        } else {
            echo "Hello, " . htmlspecialchars($_POST["username"]);
        }
    }
?>
```
📌 `htmlspecialchars()` prevents **XSS attacks** by converting HTML characters.

---

### Secure Form Submission
Use `trim()`, `htmlspecialchars()`, and `stripslashes()` to sanitize input.
```php
<?php
    function sanitize_input($data) {
        $data = trim($data);
        $data = stripslashes($data);
        $data = htmlspecialchars($data);
        return $data;
    }
    
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        $name = sanitize_input($_POST["username"]);
        echo "Hello, " . $name;
    }
?>
```
📌 **Prevents malicious code injection.**

---

### Use Prepared Statements for Database Security
If storing form data in a database, avoid **SQL Injection** by using **prepared statements**.
```php
<?php
    $conn = new mysqli("localhost", "root", "", "test_db");

    if ($conn->connect_error) {
        die("Connection failed: " . $conn->connect_error);
    }

    $stmt = $conn->prepare("INSERT INTO users (name) VALUES (?)");
    $stmt->bind_param("s", $name);
    
    $name = sanitize_input($_POST["username"]);
    $stmt->execute();
    
    echo "Data inserted successfully!";
    
    $stmt->close();
    $conn->close();
?>
```
📌 **Prevents SQL Injection attacks.**

---
---
# Day 10: Superglobals in PHP

## Overview
Superglobals are built-in PHP variables that are accessible from anywhere in a script. They store useful information about server settings, user inputs, and file uploads. Today, we will focus on three important superglobals:

- `$_SERVER`: Provides information about the server and execution environment.
- `$_FILES`: Handles file uploads.
- `$_REQUEST`: Collects form data from both `$_GET` and `$_POST`.

---

## 1️⃣ $_SERVER: Server and Execution Environment Information
The `$_SERVER` superglobal holds details about headers, paths, and script execution.

### Commonly Used `$_SERVER` Variables
| Variable | Description |
|----------|------------|
| `$_SERVER['PHP_SELF']` | Returns the filename of the executing script |
| `$_SERVER['SERVER_NAME']` | Returns the server's hostname |
| `$_SERVER['HTTP_HOST']` | Returns the host header from the request |
| `$_SERVER['REQUEST_METHOD']` | Returns the request method (GET, POST, etc.) |
| `$_SERVER['REMOTE_ADDR']` | Returns the user's IP address |
| `$_SERVER['HTTP_USER_AGENT']` | Returns details about the user’s browser |

### Example Usage
```php
<?php
    echo "Script Name: " . $_SERVER['PHP_SELF'] . "<br>";
    echo "Server Name: " . $_SERVER['SERVER_NAME'] . "<br>";
    echo "Request Method: " . $_SERVER['REQUEST_METHOD'] . "<br>";
    echo "User IP Address: " . $_SERVER['REMOTE_ADDR'] . "<br>";
    echo "User Browser: " . $_SERVER['HTTP_USER_AGENT'] . "<br>";
?>
```
📌 **Use Case:** `$_SERVER['REQUEST_METHOD']` helps determine whether a form was submitted via GET or POST.

---

## 2️⃣ $_FILES: Handling File Uploads
The `$_FILES` superglobal allows users to upload files via PHP.

### Steps to Handle File Uploads
1. **Create an HTML form** with `enctype="multipart/form-data"`:
```html
<form action="upload.php" method="POST" enctype="multipart/form-data">
    Select file: <input type="file" name="uploadedFile">
    <input type="submit" value="Upload">
</form>
```

2. **Process the uploaded file in PHP (`upload.php`)**:
```php
<?php
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        if (isset($_FILES["uploadedFile"])) {
            $file_name = $_FILES["uploadedFile"]["name"];
            $file_tmp = $_FILES["uploadedFile"]["tmp_name"];
            $upload_dir = "uploads/";

            if (move_uploaded_file($file_tmp, $upload_dir . $file_name)) {
                echo "File uploaded successfully!";
            } else {
                echo "File upload failed.";
            }
        }
    }
?>
```

### Understanding `$_FILES` Properties
| Property | Description |
|----------|------------|
| `$_FILES['uploadedFile']['name']` | Original file name |
| `$_FILES['uploadedFile']['tmp_name']` | Temporary location of the file |
| `$_FILES['uploadedFile']['size']` | Size of the uploaded file (bytes) |
| `$_FILES['uploadedFile']['type']` | MIME type of the uploaded file |
| `$_FILES['uploadedFile']['error']` | Error code (`0` = no error) |

📌 **Use Case:** Used for uploading profile pictures, documents, or media files.

---

## 3️⃣ $_REQUEST: Collecting Form Data
The `$_REQUEST` superglobal retrieves data from both `$_GET` and `$_POST`.

### Example Usage
#### **HTML Form**
```html
<form method="POST" action="process.php">
    Name: <input type="text" name="username">
    <input type="submit" value="Submit">
</form>
```

#### **Processing Data (`process.php`)**
```php
<?php
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        echo "Hello, " . $_REQUEST["username"];
    }
?>
```

⚠️ **Note:**
- `$_REQUEST` **combines** `$_GET` and `$_POST` data, which may lead to security risks.
- It’s recommended to **use `$_POST` for sensitive data** instead.

---
---
