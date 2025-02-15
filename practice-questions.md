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
    $i = 10;
    if($i % 2 ==0)
      echo "the $i is even ";
    else
      echo "the $i is odd "
  ?>
```
#### output:
```
    the 10 is even
```
---
### 6️⃣ Write a script to compare two user-input values using comparison operators.
#### Ans:
```php
  <?PHP
    $userinput1 = "hello";
    $userinput2 = "Hello World";
    if($userinput1 == $userinput2)
      echo "$userinput1 and $userinput2 are equal";
    else
      echo "not equal";
  ?>
```
#### output:
```
  not equal
```
---
### 7️⃣ Create a program that checks if a user is eligible to vote (age >= 18).
#### Ans:
```php
  <?PHP
    $age = 20;
    if($age >= 18)
      echo "eligible to vote";
    else
      echo "Not eligible to vote"
  ?>
```
#### output:
```
  eligible to vote
```
---
### 8️⃣ Write a PHP program that calculates the area of a rectangle using variables.
#### Ans:
```php
<?PHP
  $base = 20;
  $height = 15;
  $area = 1/2 * $base * $height;
  echo "the area of Triangle $area";
?>
```
#### output:
```
  the area of Triangle 150
```
---
### 9️⃣ Use logical operators to check if a year is a leap year.
#### Ans:
```php
<?PHP
  $n=2024;
  if(($n % 4 == 0 && $n % 100 != 0) || ($n % 400 == 0)){
    echo "$n is leap year";
  }else{
    echo "$n is not leap year";
  }
?>
```
#### output:
```
  2024 is leap year
```
---
### 🔟 Write a PHP script that determines whether a given number is positive, negative, or zero.
#### Ans:
```php
<?PHP
  $n =-4;
  if ($n < 0)
    echo "$n is negative";
  elseif($n > 0)
    echo "$n is positive";
  else
    echo "zero";
?>
```
#### output:
```
  -4 is negative
```
---
---
# Day 4️⃣ 
## ✅ **Practice Questions**
### 1️⃣ Use `if-else if-else` to assign grades (A, B, C, F) based on marks.
#### Ans:
```php
<?PHP
  $n=65; //marks obtain 
  if ($n>=80){
    echo "A";
	}elseif ($n<80 && $n>=65) {
    echo "B";
	}elseif ($n<65 && $n>=50) {
    echo "C";
	}else {
    echo "F";
	}
?>
```
#### output:
```
B
```
### 2️⃣ Create a switch statement that prints the name of the day based on a number (1 = Monday, 2 = Tuesday, etc.).
#### Ans:
```php
<?PHP
$n = 5;
switch($n){
    case 1:
      echo "Monday";
      break;
    case 2:
      echo "Tuesday";
      break;
    case 3:
      echo "Wednesday";
      break;
    case 4:
      echo "Thursday";
      break;
    case 5:
      echo "Friday";
      break;
    case 6:
      echo "Saturday";
      break;
    case 7:
      echo "Sunday";
      break;
    default:
      echo "not is days";
}
?>
```
#### output:
```
Friday
```

### 3️⃣ Develop a PHP script that categorizes a person's BMI (Underweight, Normal, Overweight, Obese).
#### Ans:
```php
<?PHP
$h=173; // height in cm
#w=70; // weight in kg
$h = $h / 100;

  $result = round($w / ($h * $h));
  if ($result < 18.5){
    echo "Underweight";
  }elseif ( $result <= 24.9) {
    echo "Normal";
  }elseif ($result <= 29.9) {
    echo "Overweight";
  }else{
    echo "Obese";
  }
?>
```
#### output:
```
Normal
```
### 4️⃣ Use `switch` to create a program that displays messages for different traffic light colors (Red, Yellow, Green).
#### Ans:
```php
<?PHP
$n = "Red";
switch($n){
  case "Red":
    echo "Stop";
    break;
  case "Yellow":
    echo "SLow down";
    break;
  case "Green":
    echo "Ready to go";
    break;
  default:
    echo "no colour";
}
?>
```
#### output:
```
Stop
```
### 5️⃣ Write a PHP script to check if a given character is a vowel or consonant using `switch`.
#### Ans:
```php
<?PHP
$h = 'e';
switch ($h) {
    case ($h=='a' || $h=='e' || $h=='i' || $h=='o' || $h=='u'):
      echo "vowel";
      break;
    default:
      echo "consonant";
      break;
  }
?>
```
#### output:
```
vowel
```
---

# Day 5️⃣
## ✅ **Practice Questions**
---
### 1️⃣ Write a PHP script using a `for` loop to print numbers from `1` to `100`.
#### Ans:
```php
<?PHP
for ($i=1;$i<=100;$i++){
	echo $i." ";
}
?>
```
#### output:
```
1 2 3 4 5 6 7 8 9 10 11 12 ..... 98 99 100
```
### 2️⃣ Create a `while` loop that prints the first 10 `odd` numbers.
#### Ans:
```php
<?PHP
$i=1;
while ($i<=20){
      if ($i%2!=0) {
          echo $i." ";
      }
      $i++;
}
?>
```
#### output:
```
1 3 5 7 9 11 13 15 17 19
```
### 3️⃣ Write a `do-while` loop that prints numbers from `5` to `1`.
#### Ans:
```php
<?PHP
$i=5;
while ($i>0){
     echo $i." ";
     $i--;
}
?>
```
#### output:
```
5 4 3 2 1
```
### 4️⃣ Use a `for` loop to find the sum of numbers from `1` to `50`.
#### Ans:
```php
<?PHP
$rel=0;
for($i=1;$i<=50;$i++){
    $rel += $i;
}
echo $rel." ";
?>
```
#### output:
```
1275
```
### 5️⃣ Create an array of five colors and use `foreach` to print each color.
#### Ans:
```php
<?PHP
$color = array('red','green','blue','gray','pink');
foreach ($color as $colors) {
        echo $colors." ";
}
?>
```
#### output:
```
red green blue gray pink
```
### 6️⃣ Write a PHP program using a `foreach` loop to display student names with their marks from an associative array.
#### Ans:
```php
<?PHP
$studinfo = array('ankit'=>75,'deepak'=>70,'anuska'=>85,'timmi'=>90,'zebun'=>87);
foreach ($studinfo as $key => $value) {
        echo "$key : $value <be>";
}
?>
```
#### output:
```
ankit : 75
deepak : 70
anuska : 85
timmi : 90
zebun : 87
```
### 7️⃣ Use a `while` loop to find the factorial of a number.
#### Ans:
```php
<?PHP
$i=5;
$rel = 1;
while ($i>=1){
      $rel *= $i;
      $i--;
}
echo $rel;
?>
```
#### output:
```
120
```
### 8️⃣ Write a `do-while` loop that prompts a user for input until they enter a positive number.
#### Ans:
```php
<?PHP
do {
$input = readline("Enter aa integer: ");
}while ($input < 1);
echo "You entered: " . $input;
?>
```
#### output:
```
Enter an integer: -6
Enter an integer: -4
Enter an integer: -7
Enter an integer: -2
Enter an integer: -4
Enter an integer:  6

You entered: 6
```
### 9️⃣ Use a `for` loop to display the multiplication table of a given number.
#### Ans:
```php
<?PHP
$input = readline("enter the number: ");
for($i =1;$i<=10;$i++){
  
  echo "$input x $i =".$input*$i."\n";
}
?>
```
#### output:
```
enter the number: 6

6 x 1 =6
6 x 2 =12
6 x 3 =18
6 x 4 =24
6 x 5 =30
6 x 6 =36
6 x 7 =42
6 x 8 =48
6 x 9 =54
6 x 10 =60
```
### 🔟 Write a PHP script that counts the number of even and odd numbers in an array using a `foreach` loop.
#### Ans:
```php
<?PHP
$numarr = array(1,4,3,2,5,6,7,8,9,11,15,13,16,31);
$odd=0;
$even=0;
foreach($numarr as $val){
  if($val % 2 == 0){
    $odd+=1;
  }else{
    $even+=1;
  }
}
echo ("The number of even: $even \n The number of odd: $odd ");
?>
```
#### output:
```
The number of even: 5 
The number of odd: 9
```
---
---
# Day 6️⃣ 
## ✅ Practice Questions
### 1️⃣ Create an indexed array of five cities and print all cities using a foreach loop.
#### Ans:
```php
<?PHP
$city = array("Delhi","Jaipur","Pune","Banglore","Bhopal");
foreach($city as $i){
    echo $i."\n";
}
?>
```
#### output:
```
Delhi
Jaipur
Pune
Banglore
Bhopal
```
### 2️⃣ Create an associative array of a student's details (Name, Age, Course) and print them.
#### Ans:
```php
<?PHP
$city = array("Name"=>"Ankit", "Age"=>23, "Course"=>"Mca");
foreach ($city as $key => $value){
    echo "$key : $value\n";
}
?>
```
#### output:
```
Name : Ankit
Age : 23
Course : Mca
```
### 3️⃣ Create a multidimensional array of 3 products with Name, Price, and Quantity. Print all products.
#### Ans:
```php
<?PHP
$product = array(
    array("Mobile", 10000, 20),
    array("Toy car", 1500, 50),
    array("Ankelet", 500, 100)
);
foreach ($product as $products){
    echo "Name : $products[0], Price : $products[1], Quantity : $products[2]\n";
}
?>
```
#### output:
```
Name : Mobile, Price : 10000, Quantity : 20
Name : Toy car, Price : 1500, Quantity : 50
Name : Ankelet, Price : 500, Quantity : 100
```
### 4️⃣ Use `array_push()` to add two elements to an array.
#### Ans:
```php
<?PHP
$product = array(1,2,3,4);
echo "before modify";
print_r($product);
array_push($product,5,6);
echo "After modify";
print_r($product);
?>
```
#### output:
```
before modifyArray
(  [0] => 1 [1] => 2 [2] => 3 [3] => 4 )
After modifyArray
(  [0] => 1 [1] => 2 [2] => 3 [3] => 4 [4] => 5 [5] => 6 )
```
### 5️⃣ Use `array_pop()` to remove the last element of an array.
#### Ans:
```php
<?PHP
$product = array(1,2,3,4);
echo "before modify";
print_r($product);
array_pop($product);
echo "After modify";
print_r($product);
?>
```
#### output:
```
before modifyArray
(  [0] => 1 [1] => 2 [2] => 3 [3] => 4 )
After modifyArray
(  [0] => 1 [1] => 2 [2] => 3 )
```
### 6️⃣ Use `count()` to display the number of elements in an array.
#### Ans:
```php
<?PHP
$product = array(1,2,3,4);
echo (count($product));
?>
```
#### output:
```
4
```
### 7️⃣ Use `sort()` to sort an array of five numbers in ascending order.
#### Ans:
```php
<?PHP
$product = array(2,1,4,3);
sort($product);
print_r($product);
?>
```
#### output:
```
Array
( [0] => 1 [1] => 2 [2] => 3 [3] => 4 )
```
### 8️⃣ Convert the string "PHP,HTML,CSS,JavaScript" into an array using `explode()`.
#### Ans:
```php
<?PHP
$text = "Php,HTML,CSS,JavaScript";
$language = explode(",", $text);
print_r($language);
?>
```
#### output:
```
Array
(  [0] => Php [1] => HTML [2] => CSS [3] => JavaScript  )
```
### 9️⃣ Write a script to check if a key exists in an associative array.
#### Ans:
```php
<?PHP
$city = array("Name"=>"Ankit", "Age"=>23, "Course"=>"Mca");

if(array_key_exists("Age",$city)){
    echo "the Age key is exist";
}else{
    echo "no Age key exist";
}
?>
```
#### output:
```
the Age key is exist
```
### 🔟 Write a script to merge two arrays and remove duplicate values.
#### Ans:
```php
<?PHP
$arr1 = array(1,2,3,4,5,2,4,3,6);
$arr2 = array(7,6,3,4,8,1,9,2,5);
$margedarr=array_unique(array_merge($arr1,$arr2));
print_r($margedarr);
?>
```
#### output:
```
Array
(  [0] => 1 [1] => 2 [2] => 3 [3] => 4 [4] => 5 [8] => 6 [9] => 7 [13] => 8 [15] => 9  )
```
---
---
# Day 6️⃣
## ✅ Practice Questions
### 1️⃣ Write a function `multiply()` that takes two numbers and returns their product.
#### Ans:
```php
<?PHP
function multiply($a, $b) {
     return $a * $b;
  }
    
$mult = multiply(5, 10);
echo "multiple: $mult";
?>
```
#### output:
```
multiplye: 50
```
### 2️⃣ Create a function `isEven()` that checks if a number is even and returns true or false.
#### Ans:
```php
<?PHP
function isEven($a) {
     if ($a %2 ==0){
       return "True";
     }else{
       return "False";
     }
}    
echo isEven(2)." ";
echo isEven(3)." ";
echo isEven(5);
?>
```
#### output:
```
True False False
```
### 3️⃣ Write a function `calculateArea()` that takes length and width and returns the area of a rectangle.
#### Ans:
```php
<?PHP
function calculateArea($len,$wid) {
        $area = $len * $wid;
        return $area;
    }
    $length = 5;
    $width = 4;
    $result =calculateArea($length,$width);
    echo "The area of rectangel is:".$result;
?>
```
#### output:
```
The area of rectangel is:20
```
### 4️⃣ Write a function `greetUser()` that takes a username as input and returns "Welcome, [username]!".
#### Ans:
```php
<?PHP
function greetUser($name) {
        return "Welcome, $name!";
    }
    $input = readline("Enter the unser name: ");
    echo greetUser($input);
?>
```
#### output:
```
Enter the unser name: Antish kumar

Welcome, Antish kumar!
```
### 5️⃣ Use `isset()` to check if a variable $email is set before printing it.
#### Ans:
```php
<?PHP
$email = 'ankit@gmail.com';
echo isset($email) ? 'email is :'.$email : 'not set';

?>
```
#### output:
```
email is : ankit@gmail.com
```
### 6️⃣ Use `empty()` to check if a variable $password is empty.
#### Ans:
```php
<?PHP
$var ="";
echo empty($var) ? "empty var" : "not empty";
?>
```
#### output:
```
empty var
```
### 7️⃣ Use `var_dump()` to debug an array of student names.
#### Ans:
```php
<?PHP
$var =array("ankit","rahul","ritu","ankita");
var_dump($var);

?>
```
#### output:
```
array(4) {
  [0]=>
  string(5) "ankit"
  [1]=>
  string(5) "rahul"
  [2]=>
  string(4) "ritu"
  [3]=>
  string(6) "ankita"
}
```
### 8️⃣ Write a function `reverseString()` that takes a string and returns the reversed version of it.
#### Ans:
```php
<?PHP
function reverseString($str){
    $len = strlen($str);
    for($len;$len>=0;$len--){
        echo ($str[$len]);
    }
}

$str = readline("enter the string: ");
reverseString($str);
?>
```
#### output:
```
enter the string: php programming

gnimmargorp php
```
### 9️⃣ Create a function `convertToUpperCase()` that takes a string and converts it to uppercase.
#### Ans:
```php
<?PHP

?>
```
#### output:
```
```
### 🔟 Write a function `findLargest()` that takes an array of numbers and returns the largest number.
#### Ans:
```php
<?PHP
function findLargest($num){
    $max=$num[0];
    for($i=1;$i<5;$i++){
        if ($max < $num[$i]){
            $max = $num[$i];
        }
    }
    return $max;
}
$arr =[];
echo ("enter 5 numbers\n");
for ($i = 0;$i<5;$i++){
    $num = readline("enter" .($i+1)." number: ");
    array_push($arr,$num);
}

echo findLargest($arr);
?>
```
#### output:
```
enter 5 numbers
enter1 number: 123

enter2 number: 4

enter3 number: 5

enter4 number: 6

enter5 number: 7

123
```
