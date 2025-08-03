# Write a program that takes two integer numbers as input, calculates their sum, and prints the result. [Low]

```java
import java.io.*;
import java.util.*;

class sumcalc{
public static void main(String[] args){
Scanner sc = new Scanner(System.in);

System.out.println("Enter your first integer:");
int a = sc.nextInt();
System.out.println("Enter your second integer:");
int b = sc.nextInt();
int sum = a+b;
System.out.println("Sum of the two integers is: " + sum + ".");
}
}
```

## Output:
```java
Enter your first integer:
5
Enter your second integer:
10
Sum of the two integers is: 15.
```
