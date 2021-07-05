<h3 align="center">Special Thanks to - </h3>
<h1 align="center"> Mithailaal</h1>
Click https://www.w3resource.com/cpp-exercises/basic/index.php?passed=passed to see the questions.
Thank you for visting this repo.
<br>
<br>
The solutions togther with the Questions are given below - 
<br>
<br>
1. Write a program in C++ to print a welcome text in a separate line.

```cpp
#include<iostream>
using namespace std;
int main(void)
{
    cout<<"Hello! viewer"<<endl;
    cout<<"Welcome to the repository"<<endl;
}

```

2. Write a program in C++ to print the sum of two numbers.
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    cout<<"Sum of "<<29<<" and "<<30<<" is "<<(29+30)<<endl;
}

```

3. Write a program in C++ to find Size of fundamental data types. Go to the editor

```cpp
#include<iostream>
using namespace std;
int main(void)
{
    cout<<"The sizeof(char) is : "<<sizeof(char)<<" bytes"<<endl;
    cout<<"The sizeof(short) is : "<<sizeof(short)<<" bytes"<<endl;
    cout<<"The sizeof(int) is : "<<sizeof(int)<<" bytes"<<endl;
    cout<<"The sizeof(long) is : "<<sizeof(long)<<" bytes"<<endl;
    cout<<"The sizeof(long long) is : "<<sizeof(long long)<<" bytes"<<endl;
    cout<<"The sizeof(float) is : "<<sizeof(float)<<" bytes"<<endl;
    cout<<"The sizeof(double) is : "<<sizeof(double)<<" bytes"<<endl;
    cout<<"The sizeof(long double) is : "<<sizeof(long double)<<" bytes"<<endl;
    cout<<"The sizeof(bool) is : "<<sizeof(bool)<<" bytes"<<endl;
}

```

4. Write a program in C++ to print the sum of two numbers using variables. Go to the editor
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int n1 = 29;
    int n2 = 30;
    int sum = 59;
    cout<<"The sum of "<<n1<<" and "<<n2<<" is : "<<sum<<endl;
}
```

5. Write a program in C++ to check the upper and lower limits of integer. Go to the editor
Expected Output:
Check the upper and lower limits of integer :
--------------------------------------------------
The maximum limit of int data type : 2147483647
The minimum limit of int data type : -2147483648
The maximum limit of unsigned int data type : 4294967295
The maximum limit of long long data type : 9223372036854775807
The minimum limit of long long data type : -9223372036854775808
The maximum limit of unsigned long long data type : 18446744073709551615
The Bits contain in char data type : 8
The maximum limit of char data type : 127
The minimum limit of char data type : -128
The maximum limit of signed char data type : 127
The minimum limit of signed char data type : -128
The maximum limit of unsigned char data type : 255
The minimum limit of short data type : -32768
The maximum limit of short data type : 32767
The maximum limit of unsigned short data type : 65535
Click me to see the sample solution

6. Write a program in C++ to check whether the primitive values crossing the limits or not. Go to the editor
Check whether the primitive values crossing the limits or not :
--------------------------------------------------------------------
The Gender is : F
Is she married? : 1
Number of sons she has : 2
Year of her appointment : 2009
Salary for a year : 1500000
Height is : 79.48
GPA is 4.69
Salary drawn upto : 12047235
Balance till : 995324987
Click me to see the sample solution

7. Write a program in C++ to display various type or arithmetic operation using mixed data type. Go to the editor
Sample output:
Display arithmetic operations with mixed data type :
---------------------------------------------------------
5 + 7 = 12
3.7 + 8.0 = 11.7
5 + 8.0 = 13.0
5 - 7 = -2
3.7 - 8.0 = -4.3
5 - 8.0 = -3.0
5 * 7 = 35
3.7 * 8.0 = 29.6
5 * 8.0 = 40.0
5 / 7 = 0
3.7 / 8.0 = 0.5
5 / 8.0 = 0.6
Click me to see the sample solution

8. Write a program in C++ to check overflow/underflow during various arithmetical operation. Go to the editor
Sample Output:
Check overflow/underflow during various arithmetical operation :
Range of int is [-2147483648, 2147483647]
---------------------------------------------------------------------
Overflow the integer range and set in minimum range : -2147483648
Increasing from its minimum range : -2147483647
Product is :1
Underflow the range and set in maximum range : 2147483647
Decreasing from its maximum range : 2147483646
Product is : 0
Click me to see the sample solution

9. Write a program in C++ to display the operation of pre and post increment and decrement. Go to the editor
Sample Output:
Display the operation of pre and post increment and decrement :
--------------------------------------------------------------------
The number is : 57
After post increment by 1 the number is : 58
After pre increment by 1 the number is : 59
After increasing by 1 the number is : 60
After post decrement by 1 the number is : 59
After pre decrement by 1 the number is : 58
After decreasing by 1 the number is : 57
Click me to see the sample solution

10. Write a program in C++ to formatting the output. Go to the editor
Sample Output:
Formatting the output :
----------------------------
The value of pi : 3.1416
The value of pi 4 decimal place of total width 8 : | 3.1416|
The value of pi 4 decimal place of total width 10 : | 3.1416|
The value of pi 4 decimal place of total width 8 : |--3.1416|
The value of pi 4 decimal place of total width 10 : |----3.1416|
The value of pi in scientific format is : 3.1416e+00
Status in number : 0
Status in alphabet : false
Click me to see the sample solution

11. Write a program in C++ to print the result of the specified operations. Go to the editor
Sample Output:
Print the result of some specific operation :
--------------------------------------------------
Result of 1st expression is : 23
Result of 2nd expression is : 5
Result of 3rd expression is : 12
Result of 4th expression is : 3
Click me to see the sample solution

12. Write a program in C++ to add two numbers accept through keyboard.
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int a, b;
    cout<<"Input 1st number: ";
    cin>>a;
    cout<<"Input 2nd number: ";
    cin>>b;
    cout<<"The sum of the numbers is: "<< a + b << endl;
}
```
13. Write a program in C++ to swap two numbers. 
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int a, b, c;
    cout<<"Input 1st number: ";
    cin>>a;
    cout<<"Input 2nd number: ";
    cin>>b;
    c = a;
    a = b;
    b = c;
    cout<<"After swapping the 1st number is: "<< a <<endl;
    cout<<"After swapping the 2nd number is: "<< b <<endl;
}
```
14. Write a program in C++ to calculate the volume of a sphere. 
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int r, v;
    cout<<"Input radius of the Sphere: ";
    cin>>r;
    v = (4/3)*3.14*r*r*r;
    cout<<"Volume of the Sphere is: "<< v <<endl;
}
```
15. Write a program in C++ to calculate the volume of a cube. 
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int r, v;
    cout<<"Input side of the cube: ";
    cin>>r;
    v = r*r*r;
    cout<<"Volume of the Cube is: "<< v <<endl;
}
```
16. Write a program in C++ to calculate the volume of a cylinder.
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int r, h, v;
    cout<<"Input radius of the Cylinder: ";
    cin>>r;
    cout<<"Input height of the Cylinder: ";
    cin>>h;
    v = 2 * 3.14 * r * h;
    cout<<"Volume of the Cylinder is: "<< v <<endl;
}
```
17. Write a program in C++ to find the Area and Perimeter of a Rectangle. 
```cpp
#include<iostream>
using namespace std;
int main(void)
{
    int l, b, p, a;
    cout<<"Input Length of the rectangle: ";
    cin>>l;
    cout<<"Input Width of the rectangle: ";
    cin>>b;
    a = l * b;
    p = 2 * (l + b);
    cout<<"The area of the rectangle is : "<< a <<endl;
    cout<<"The perimeter of the rectangle is : "<< p <<endl;
}
```
18. Write a program in C++ to find the area of any triangle using Heron's Formula.
```cpp
#include<iostream>
#include<cmath>
using namespace std;
int main(void)
{
    double s1,s2,s3;
    cout<<"Input the length of 1st side of the triangle : ";
    cin>>s1;
    cout<<"Input the length of 1st side of the triangle : ";
    cin>>s2;
    cout<<"Input the length of 1st side of the triangle : ";
    cin>>s3;
    
    double sPeri = (s1 + s2 + s3) / 2;
    double area = sqrt(sPeri * (sPeri - s1) * (sPeri - s2) * (sPeri - s3));
    
    printf("The area of the triangle is : %.2f\n",area);
    
}

```

19. Write a program in C++ to find the area and circumference of a circle. 
```cpp
#include<iostream>
#include<cmath>
using namespace std;
int main(void)
{
    double r, a, c;
    cout<<"Input the radius(1/2 of diameter) of a circle :";
    cin>>r;
    a = 3.14*r*r;
    c = 2*3.14*r;
    printf("The area of the circle is : %.4f\n", a);
    printf("The circumference of the circle is : %.4f\n", c);
    
}

```
20. Write a program in C++ to convert temperature in Celsius to Fahrenheit. Go to the editor
```cpp
#include<iostream>
#include<cmath>
using namespace std;
int main(void)
{
    double c,f;
    cout<<"Input the temperature in Celsius : ";
    cin>>c;
    cout<<"The temperature in Celsius : "<<c<<endl;
    
    f = (c * 9/5) + 32;
    
    cout<<"The temperature in Fahrenheit : "<<f<<endl;
    
}
```

21. Write a program in C++ to convert temperature in Fahrenheit to Celsius.
```cpp
#include<iostream>
#include<cmath>
using namespace std;
int main(void)
{
    double c,f;
    cout<<"Input the temperature in Fahrenheit: ";
    cin>>f
    c = 5 * (f - 32) / 9;
    cout<<"The temperature in Celsius :"<<c<<endl;
}
```
22. Write a program in C++ to find the third angle of a triangle.
```cpp
#include<iostream>
#include<cmath>
using namespace std;
int main(void)
{
    int f,s,t;
    cout<<"Input the 1st angle of the triangle :";
    cin>>f;
    cout<<"Input the 2nd angle of the triangle :";
    cin>>s;
    t = 180 - f - s;
    cout<<"The 3rd of the triangle is :"<<t<endl;
}
```
23. Write a program in C++ that converts kilometers per hour to miles per hour. Go to the editor
Sample Output:
Convert kilometers per hour to miles per hour :
----------------------------------------------------
Input the distance in kilometer : 25
The 25 Km./hr. means 15.5343 Miles/hr.
Click me to see the sample solution

24. Write a program in C++ to convert temperature in Kelvin to Fahrenheit. Go to the editor
Sample Output:
Convert temperature in Kelvin to Fahrenheit :
---------------------------------------------------
Input the temperature in Kelvin : 300
The temperature in Kelvin : 300
The temperature in Fahrenheit : 80.33
Click me to see the sample solution

25. Write a program in C++ to convert temperature in Kelvin to Celsius. Go to the editor
Sample Output:
Convert temperature in Kelvin to Celsius :
------------------------------------------------
Input the temperature in Kelvin : 300
The temperature in Kelvin : 300
The temperature in Celsius : 26.85

Click me to see the sample solution

26. Write a program in C++ to convert temperature in Fahrenheit to Kelvin. Go to the editor
Sample Output:
Convert temperature in Fahrenheit to Kelvin :
---------------------------------------------------
Input the temperature in Fahrenheit : 80.33
The temperature in Fahrenheit : 80.33
The temperature in Kelvin : 300
Click me to see the sample solution

27. Write a program in C++ to convert temperature in Celsius to Kelvin. Go to the editor
Sample Output:
Convert temperature in Celsius to Kelvin :
---------------------------------------------------
Input the temperature in Celsius : 26.85
The temperature in Celsius : 26.85
The temperature in Kelvin : 300
Click me to see the sample solution

28. Write a program in C++ to find the area of Scalene Triangle. Go to the editor
Sample Output:
Find the area of Scalene Triangle :
----------------------------------------
Input the length of a side of the triangle : 5
Input the length of another side of the triangle : 6
Input the angle between these sides of the triangle : 6
The area of the Scalene Triangle is : 1.56793
Click me to see the sample solution

29. Write a program in C++ to compute quotient and remainder. Go to the editor
Sample Output:
Compute quotient and remainder :
-------------------------------------
Input the dividend : 25
Input the divisor : 3
The quotient of the division is : 8
The remainder of the division is : 1
Click me to see the sample solution

30. Write a program in C++ to compute the total and average of four numbers. Go to the editor
Sample Output:
Compute the total and average of four numbers :
----------------------------------------------------
Input 1st two numbers (separated by space) : 25 20
Input last two numbers (separated by space) : 15 25
The total of four numbers is : 85
The average of four numbers is : 21.25
Click me to see the sample solution

31. Write a program in C++ to input a single digit number and print a rectangular form of 4 columns and 6 rows. Go to the editor
Sample Output:
Make a rectangular shape by a single digit number :
--------------------------------------------------------
Input the number : 5
5555
5 5
5 5
5 5
5 5
5555
Click me to see the sample solution

32. Write a program in C++ to check whether a number is positive, negative or zero. Go to the editor
Sample Output:
Check whether a number is positive, negative or zero :
-----------------------------------------------------------
Input a number : 8
The entered number is positive.
Click me to see the sample solution

33. Write a program in C++ to divide two numbers and print on the screen. Go to the editor
Sample Output:
Divide two numbers and print:
----------------------------------
The quotient of 30 and 10 is : 3
Click me to see the sample solution

34. Write a C++ program to display the current date and time. Go to the editor
Sample Output:
Display the Current Date and Time :
----------------------------------------
seconds = 57
minutes = 33
hours = 12
day of month = 6
month of year = 7
year = 2017
weekday = 4
day of year = 186
daylight savings = 0
Current Date: 6/7/2017
Current Time: 12:33:57
Click me to see the sample solution

35. Write a program in C++ to compute the specified expressions and print the output. Go to the editor
Sample Output:
Compute the specified expressions and print the output:
------------------------------------------------------------
Result of the expression (25.5 * 3.5 - 3.5 * 3.5) / (40.5 - 4.5) is : 2.13889
Click me to see the sample solution

36. Write a program in C++ to test the Type Casting. Go to the editor
Sample Output:
Formatting the output using type casting:
----------------------------------------------
Print floating-point number in fixed format with 1 decimal place:
Test explicit type casting :
0
0.5
0.5
0.0
Test implicit type casting :
0
0
int implicitly casts to double:
4.0
double truncates to int!:
6
Click me to see the sample solution

37. Write a program in C++ to print a mystery series from 1 to 50. Go to the editor
Sample Output:
Print a mystery series:
-------------------------
The series are:
5 4 2 7 11 10 8 13 17 16 14 19 23 22 20 25 29 28 26 31 35 34 32 37 41 4 0 38 43 47 46 44 49
Click me to see the sample solution

38. Write a program in C++ that takes a number as input and prints its multiplication table upto 10. Go to the editor
Sample Output:
Print the multiplication table of a number upto 10:
--------------------------------------------------------
Input a number: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
Click me to see the sample solution

39. Write a program in C++ to print the following pattern. Go to the editor
Sample Output:
 xxxxx                                                                                                        
x     x       x        x                                                                                      
x             x        x                                                                                      
x          xxxxxxx  xxxxxxx                                                                                   
x             x        x                                                                                      
x     x       x        x                                                                                      
 xxxxx  

Click me to see the sample solution
40. Write a program in C++ to print the area and perimeter of a rectangle. Go to the editor
Sample Output:
Print the area and perimeter of a rectangle:
----------------------------------------------
Input the width of the rectangle: 8.5
Input the height of the rectangle: 5.6
The area of the rectangle is: 47.6
The perimeter of the rectangle is: 28.2
Click me to see the sample solution

41. Write a program in C++ to print an American flag on the screen. Go to the editor
Sample Output:

```cpp

// Indian flag first
#include<iostream>
#include<cmath>
using namespace std;
int main(void)
{

    // kesariya
    for (int i = 0; i < 10; i++)
    {
        for (int j = 0; j < 90; j ++)
        {
            cout<<"=";
        }
        cout<<endl;
    }

    int circle_radius = 9; // or whatever you want
    float console_ratio = 4.0/3.0;
    float a = console_ratio*circle_radius;
    float b = circle_radius;
    
    //Safed
    for (int y = -circle_radius; y <= circle_radius; y++)
    {
        for (int i = 0; i < 30; i ++)
        {
            cout<<" ";
        }
        for (int x = -console_ratio*circle_radius; x <= console_ratio*circle_radius; x++)
        {
            float d = (x/a)*(x/a) + (y/b)*(y/b);
            if (d > 0.90 && d < 1.1)
            {
                cout << "*";
            }
            else
            {
                 cout << " ";
            }
        }
        cout << endl;
    }

    // Hara
    for (int i = 0; i < 10; i++)
    {
        for (int j = 0; j < 90; j ++)
        {
            cout<<"#";
        }
        cout<<endl;
    }
}

```
 Print the American flag:                                              
-----------------------------                                          
* * * * * * ==================================                         
 * * * * *  ==================================                         
* * * * * * ==================================                         
 * * * * *  ==================================                         
* * * * * * ==================================                         
 * * * * *  ==================================                         
* * * * * * ==================================                         
 * * * * *  ==================================                         
* * * * * * ==================================                         
==============================================                         
==============================================                         
==============================================                         
==============================================                         
==============================================                         
==============================================
Click me to see the sample solution
42. Write a language program in C++ which accepts the user's first and last name and print them in reverse order with a space between them. Go to the editor
Sample Output:
Print the name in reverse where last name comes first:
-----------------------------------------------------------
Input First Name: Alexandra
Input Last Name: Abramov
Name in reverse is: Abramov Alexandra
Click me to see the sample solution

43. Write a language program which accepts the radius of a circle from the user and compute the area and circumference. Go to the editor
Sample Output:
Find the area and circumference of any circle :
----------------------------------------------------
Input the radius(1/2 of diameter) of a circle : 5
The area of the circle is : 78.5397
The circumference of the circle is : 31.4159
Click me to see the sample solution

44. Write a language program to get the volume of a sphere with radius 6. Go to the editor
Sample Output:
Calculate the volume of a sphere :
---------------------------------------
Input the radius of a sphere : 5
The volume of a sphere is : 523.333
Click me to see the sample solution

45. Write a program in C++ to calculate the volume of a cube. Go to the editor
Sample Output:
Calculate the volume of a cube :
---------------------------------------
Input the side of a cube : 5
The volume of a cube is : 125
Click me to see the sample solution

46. Write a program in C++ to calculate the volume of a cylinder. Go to the editor
Sample Output:
Calculate the volume of a cylinder :
-----------------------------------------
Input the radius of the cylinder : 4
Input the height of the cylinder : 8
The volume of a cylinder is : 401.92
Click me to see the sample solution

47. Write a program in C++ to find the area of any triangle using Heron's Formula. Go to the editor
Sample Output:
Find the area of any triangle using Heron's Formula :
----------------------------------------------------------
Input the length of 1st side of the triangle : 5
Input the length of 2nd side of the triangle : 6
Input the length of 3rd side of the triangle : 7
The area of the triangle is : 14.6969
Click me to see the sample solution

48. Write a program in C++ which swap the values of two variables not using third variable. Go to the editor
Sample Output:
Swap two numbers without using third variable:
---------------------------------------------------
Input 1st number : 25
Input 2nd number : 20
After swapping the 1st number is : 20
After swapping the 2nd number is : 25
Click me to see the sample solution

49. Write a program in C++ to print the code (ASCII code / Unicode code etc.) of a given character. Go to the editor
Sample Output:
Print code (ASCII code / Unicode code etc.) of a given character:
-----------------------------------------------------------------------
Input a character: a
The ASCII value of a is: 97
The character for the ASCII value 97 is: a
Click me to see the sample solution

50. Write a program in C++ to enter length in centimeter and convert it into meter and kilometer. Go to the editor
Sample Output:
Convert centimeter into meter and kilometer :
--------------------------------------------------
Input the distance in centimeter : 250000
The distance in meter is: 2500
The distance in kilometer is: 2.5
Click me to see the sample solution

51. Write a program in C++ that converts kilometers per hour to miles per hour. Go to the editor
Sample Output:
Convert kilometers per hour to miles per hour :
----------------------------------------------------
Input the distance in kilometer : 5
The 5 Km./hr. means 3.10686 Miles/hr.
Click me to see the sample solution

52. Write a program in C++ to enter two angles of a triangle and find the third angle. Go to the editor
Sample Output:
Find the third angle of a triangle :
-----------------------------------------
Input the 1st angle of the triangle : 35
Input the 2nd angle of the triangle : 35
The 3rd of the triangle is : 110
Click me to see the sample solution

53. Write a program in C++ to calculate area of an equilateral triangle. Go to the editor
Sample Output:
Calculate the area of the Equilateral Triangle :
----------------------------------------------------
Input the value of the side of the equilateral triangle: 5
The area of equilateral triangle is: 10.8253
Click me to see the sample solution

54. Write a program in C++ to enter P, T, R and calculate Simple Interest. Go to the editor
Sample Output:
Calculate the Simple Interest :
-----------------------------------
Input the Principle: 20000
Input the Rate of Interest: 10
Input the Time: 1.5
The Simple interest for the amount 20000 for 1 years @ 10 % is: 2000
Click me to see the sample solution

55. Write a program in C++ to enter P, T, R and calculate Compound Interest. Go to the editor
Sample Output:
Calculate the Compound Interest :
------------------------------------- Input the Principle: 20000
Input the Rate of Interest: 10
Input the Time: 1.5
The Interest after compounded for the amount 20000 for 1.5 years @ 10
% is: 3073.8 The total amount after compounded for the amount 20000 for 1.5 years @
10 % is: 23073.8
Click me to see the sample solution

56. Write a program in C++ to show the manipulation of a string. Go to the editor
Sample Output:
Show the manipulation of a string:
-------------------------------------
The string:: welcome, w3resource
The length of the string:: 19
The char at index 1 of the string:: e
The char at index 1 of the string [using array ]:: e
Is the string empty:: 0
Retrieve the sub-string from 3rd position for 4 characters:: come
The sub-string replace by 'went':: welwent, w3resource
Append a string 'end' at last of the string:: welwent, w3resource end
Append a string 'end' at last of the string using operator:: welwent, w3resource end end
The string 'insert' inserting at 3rd position of the string:: wel inse rt went, w3resource end
The new string is:: wel insert went, w3resource end
Input a sentence:: The quick brown fox jumps over the lazy dog.
The quick brown fox jumps over the lazy dog.
Click me to see the sample solution

57. Write a program in C++ to print the area of a hexagon. Go to the editor
Sample Output:
Print the area of a hexagon:
---------------------------------
Input the side of the hexagon: 6
The area of the hexagon is: 93.5307
Click me to see the sample solution

58. Write a program in C++ to print the area of a polygon. Go to the editor
Sample Output:
Print the area of a polygon:
---------------------------------
Input the number of sides of the polygon: 7
Input the length of each side of the polygon: 6
The area of the polygon is: 130.821
Click me to see the sample solution

59. Write a program in C++ to compute the distance between two points on the surface of earth. Go to the editor
Sample Output:
Print the the distance between two points on the surface of earth:
-----------------------------------------------------------------------
Input the latitude of coordinate 1: 25
Input the longitude of coordinate 1: 35
Input the latitude of coordinate 2: 35.5
Input the longitude of coordinate 2: 25.5
The distance between those points is: 1480.08
Click me to see the sample solution

60. Write a program in C++ to add two binary numbers. Go to the editor
Sample Output:
Addition of two binary numbers:
-----------------------------------
Input the 1st binary number: 1010
Input the 2nd binary number: 0011
The sum of two binary numbers is: 1101
Click me to see the sample solution

61. Write a C++ program to swap first and last digits of any number. Go to the editor
Sample Output:
Input any number: 12345
The number after swapping the first and last digits are: 52341
Click me to see the sample solution

62. Write a C++ program to which reads an given integer n and prints a twin prime which has the maximum size among twin primes less than or equals to n. Go to the editor
According to wikipedia "A twin prime is a prime number that is either 2 less or 2 more than another prime number" for example, either member of the twin prime pair (41, 43). In other words, a twin prime is a prime that has a prime gap of two".
Click me to see the sample solution

63. Write a C++ program which prints three highest numbers from a list of numbers in descending order. Go to the editor
Click me to see the sample solution

64. Write a C++ program to compute the sum of the two given integers and count the number of digits of the sum value. Go to the editor
Click me to see the sample solution

65. Write a C++ program to check whether given length of three side form a right triangle. Go to the editor
Click me to see the sample solution

66. Write a C++ program to add all the numbers from 1 to a given number. Go to the editor
Add 1 to 4: 10
Add 1 to 100: 5050
Click me to see the sample solution

67. Write a C++ program to which prints the central coordinate and the radius of a circumscribed circle of a triangle which is created by three points on the plane surface. Go to the editor
Click me to see the sample solution

68. Write a C++ program to read seven numbers and sorts them in descending order. Go to the editor
Click me to see the sample solution

69. Write a C++ program to read an integer n and prints the factorial of n, assume that n = 10. Go to the editor
Click me to see the sample solution

70. Write a C++ program to replace all the lower-case letters of a given string with the corresponding capital letters.Go to the editor
Click me to see the sample solution

71. Write a C++ program which reads a sequence of integers and prints mode values of the sequence. The number of integers is greater than or equals to 1 and less than or equals to 100. Go to the editor
Note: The mode of a set of data values is the value that appears most often.
Click me to see the sample solution

72. Write a C++ program to which reads n digits chosen from 0 to 9 and counts the number of combinations where the sum of the digits equals to given number. Do not use the same digits in a combination. Go to the editor
For example, the combinations where n = 2 and s = 5 are as follows:
0 + 5 = 5
1 + 4 = 5
3 + 2 = 5
Click me to see the sample solution

73. Write a C++ program that accepts sales unit price and sales quantity of various items and compute total sales amount and the average sales quantity. All input values must greater than or equal to 0 and less than or equal to 1,000, and the number of pairs of sales unit and sales quantity does not exceed 100. If a fraction occurs in the average of the sales quantity, round the first decimal place. Go to the editor
Click me to see the sample solution

74. Write a C++ program that accepts various numbers and compute the difference between the highest number and the lowest number. All input numbers should be real numbers between 0 and 1,000,000. The output (real number) may include an error of 0.01 or less. Go to the editor
Click me to see the sample solution

75. Write a C++ program to compute the sum of the specified number of Prime numbers. Go to the editor
For example when n = 7,
s = 2 + 3 + 5 + 7 + 11 + 13 + 17 = 58.
Click me to see the sample solution

76. An even number of 4 or more can be represented by the sum of two prime numbers. This is called Goldbach expectation, and it is confirmed that it is correct up to a considerably large number by computer calculation. For example, 10 can be expressed as the sum of two prime numbers 7 + 3, 5 + 5. Write a C++ program that accept an integer (n) from the user and outputs the number of combinations that express n as a sum of two prime numbers. Go to the editor
Note: n should be greater than or equal to 4 and less than or equal to 50,000.
Click me to see the sample solution

77. There are four different points on a plane: A(x1, y1), B(x2, y2), C(x3, y3) and D(x4, y4).
Write a C++ program to check whether two straight lines AB and CD are orthogonal or not. Go to the editor
Input:
0 6
5 6
3 8
3 2
Output:
yes
Click me to see the sample solution

78. Write a C++ program to sum of all positive integers in a sentence. Go to the editor
Sample string: There are 12 chairs, 15 desks, 1 blackboard and 2 fans.
Output: 30
Click me to see the sample solution

79. Write a C++ program to display all the leap years between two given years. If there is no leap year in the given period,display a suitable message. Go to the editor
Note: Range of the two given years: ( 0 < year1 = year2 < 3,000).
Click me to see the sample solution

80. Write a C++ program that accepts n different numbers (0 to 100) and s which is equal to the sum of the n different numbers. Go to the editor
Your job is to find the number of combination of n numbers and the same number can not be used for one combination.
Click me to see the sample solution

81. Write a C++ program to which replace all the words "dog" with "cat" Go to the editor
Sample Text: The quick brown fox jumps over the lazy dog. You can assume that the number of characters in a text is less than or equal to 1000.
Click me to see the sample solution

82. Write a C++ program which reads a list of pairs of a word and a page number, and prints the word and a list of the corresponding page numbers.Go to the editor
Click me to see the sample solution

+
83. Write a C++ program to convert a given number into hours and minutes. Separate the number of hours and minutes with a colon. Go to the editor
For example if a given number is 67 the output should be 1:7
Click me to see the sample solution

84. Write a C++ program to check whether the sequence of the numbers in a given array is a "Arithmetic" or "Geometric" sequence. Return -1 if the sequenc is not "Arithmetic" or "Geometric". Go to the editor
From Wikipedia
In mathematics, an arithmetic progression (AP) or arithmetic sequence is a sequence of numbers such that the difference between the consecutive terms is constant. Difference here means the second minus the first. For instance, the sequence 5, 7, 9, 11, 13, 15, . . . is an arithmetic progression with common difference of 2.
In mathematics, a geometric progression, also known as a geometric sequence, is a sequence of numbers where each term after the first is found by multiplying the previous one by a fixed, non-zero number called the common ratio. For example, the sequence 2, 6, 18, 54, ... is a geometric progression with common ratio 3. Similarly 10, 5, 2.5, 1.25, ... is a geometric sequence with common ratio 1/2.
Example:
Sample Input: int nums1[] = { 1, 3, 5, 7 }
Sample Output: Arithmetic sequence
Click me to see the sample solution

85. Write a C++ program find the total number of minutes between two given times (formatted with a colon and am or pm). Go to the editor
Example:
Sample Input: Minutes between 12:01AM to 12:00PM:
Sample Output: Minutes between 12:01AM to 12:00PM: 1439
Click me to see the sample solution
