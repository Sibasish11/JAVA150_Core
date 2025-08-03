# Write a program to convert a given temperature from Celsius to Fahrenheit. Take Celsius as input. Formula: F=C∗(9.0/5.0)+32. [Low]

```java
import java.io.*;
import java.util.*;
class tempconv{
public static void main(String [] args){
Scanner sc = new Scanner(System.in);
System.out.println("Enter temperature in terms of celcius:");
double a = sc.nextDouble();

double Formula = a*9/5 + 32;
System.out.println("Your temperature in form of Fahrenheit is: " + Formula + " Degree Fahrenheit." );
}
}
```

## Output:

```java
Enter temperature in terms of celcius:
20
Your temperature in form of Fahrenheit is: 68.0 Degree Fahrenheit.
```
