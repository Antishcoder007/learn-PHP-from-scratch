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

### **Day 3: Operators in PHP**
- Arithmetic Operators *(+, -, *, /, %)*
- Comparison Operators *(==, !=, >, <, >=, <=)*
- Logical Operators *(&&, ||, !)*
- Assignment Operators

### **Day 4: Conditional Statements**
- `if`, `else`, `elseif`
- `switch` statements

### **Day 5: Loops**
- `for`, `while`, `do-while`
- `foreach` for arrays

### **Day 6: Arrays**
- Indexed, Associative, and Multidimensional arrays
- Array functions *(array_push(), array_pop(), count(), sort(), explode())*

### **Day 7: Functions in PHP**
- Defining and calling functions
- Function parameters and return values
- Built-in PHP functions *(isset(), empty(), var_dump())*

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
