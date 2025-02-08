# Day1️⃣: there are no practical questions for day1
---
# Day 2️⃣
## ✅ **Practice Questions**
### Q1 Declare a variable $city and assign your city name. Print it.
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
### Q2 Store an integer, string, and float in variables and display them.
#### Ans:
```php
  <?PHP
    $int = 19;
    $string = "PHP";
    $float = 6.87;
    echo "<br>integer value is ".$int."<br>string value is ".$string."<br>float value is ".$float;
  ?>
```
#### output:
```
  integer value is 19
  string value is PHP
  float value is 6.87
```
---
### Q3 Define a constant WEBSITE with your website name and print it.
#### Ans:
```php
  <?PHP
    define("website","learn-PHP-from-scratch");
    echo website;
  ?>
```
#### output:
```
  learn-PHP-from-scratch
```
---
### Q4 Create an array of your favourite movies and print each using Echo.
#### Ans:
```php
  <?PHP
    $movies = ["Moana", "Ferdinand", "Zootopia", "IceAge", "Frozen"];
    echo $movies[0]."<br>";
    echo $movies[1]."<br>";
    echo $movies[2]."<br>";
    echo $movies[3]."<br>";
    echo $movies[4]."<br>";
  ?>
```
#### output:
```
  Moana
  Ferdinand
  Zootopia
  IceAge
  Frozen
```

---
### Q5 Write a multi-line comment explaining what your PHP script does.
#### Ans:
```php
  <?PHP
    /*
    below code, we define a constant value of Pi
    And calculating the area of the circle
    */
    define("PI",3.14);
    $r = 5;
    $area = PI*$r*$r;
    echo "the area of a circle is ".$area;
  ?>
```
#### output:
```
  the area of a circle is 78.5
```
---
# Day 3️⃣
## ✅ **Practice Questions**
### 1️⃣ Write a PHP program to add, subtract, multiply, divide, and find the remainder of two numbers.
#### Ans:
```php
  <?PHP
    $no1 = 8;
    $no2 = 2;
    $add = $no1 + $no2;
    $sub = $no1 - $no2;
    $mult = $no1 * $no2;
    $div = $no1 / $no2;
    $remd = $no1 % $no2;
    echo "addition of ".$no1." and ".$no2." is ".$add."<br>";
    echo "subtraction of ".$no1." and ".$no2." is ".$sub."<br>";
    echo "multiplication of ".$no1." and ".$no2." is ".$mult."<br>";
    echo "division of ".$no1." and ".$no2." is ".$div."<br>";
    echo "modulus of ".$no1." and ".$no2." is ".$mod."<br>";
  ?>
```
#### output:
```
  addition of 8 and 2 is 10
  subtraction of 8 and 2 is 6
  multiplication of 8 and 2 is 16
  division of 8 and 2 is 4
  modulus of 8 and 2 is
```
---
### 2️⃣ Compare two numbers using comparison operators and print the results.
#### Ans:
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
#### output:
```
    Is x equal to y? 
    Is x not equal to y? 1
    Is x greater than y? 1
    Is x less than or equal to y? 
```
---
### 3️⃣ Use logical operators to check if a number is greater than 5 AND less than 20.
#### Ans:
```php
  <?PHP
    $num = 2;
    if(($num > 5  and  $num < 20))
    echo $num." number is greater than 5 AND less than 20 ";
    else
    echo $num." number is not greater than 5 AND less than 20";
  ?>
```
#### output:
```
  number is not greater than 5 AND less than 20
```
---
### 4️⃣ Declare a variable and use assignment operators (+=, -=, *=, /=, %=) to modify it.
#### Ans:
```php
  <?PHP
    $num = 2;
    echo "num = 2 => ".$num."<br>";
    $num += 2;
    echo "num += 2 => ".$num."<br>";
    $num -= 1;
    echo "num -= 2 => ".$num."<br>";
    $num *= 2;
    echo "num *= 2 => ".$num."<br>";
    $num /= 2;
    echo "num /= 2 => ".$num."<br>";
    $num %= 2;
    echo "num %= 2 => ".$num."<be>";
  ?>
```
#### output:
```
  num = 2 => 2
  num += 2 => 4
  num -= 2 => 3
  num *= 2 => 6
  num /= 2 => 3
  num %= 2 => 1
```
---
### 5️⃣ Check if a number is even or odd using the modulus (%) operator.
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
### 6️⃣ Write a script to compare two user-input values using comparison operators.
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
### 7️⃣ Create a program that checks if a user is eligible to vote (age >= 18).
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
### 8️⃣ Write a PHP program that calculates the area of a rectangle using variables.
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
### 9️⃣ Use logical operators to check if a year is a leap year.
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
### 🔟 Write a PHP script that determines whether a given number is positive, negative, or zero.
#### Ans:
```php
  <?PHP
    $city = Jaipur;
    echo "city is ".$city;
  ?>
```
#### output:
```
  city is Jaipur
```
---
