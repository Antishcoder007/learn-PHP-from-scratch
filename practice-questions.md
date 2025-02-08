# Day1: there are no practical questions for day1
---
# Day 2
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
# Q2 Store an integer, string, and float in variables and display them.
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
# Q3 Define a constant WEBSITE with your website name and print it.
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
# Q4 Create an array of your favourite movies and print each using Echo.
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
# Q5 Write a multi-line comment explaining what your PHP script does.
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
