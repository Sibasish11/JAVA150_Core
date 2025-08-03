# Write a program to demonstrate the use of relational operators (==, !=, <, >, <=, >=). Compare two numbers and print the boolean result for each operator. [Low]

```java
import java.io.*;
import java.util.*;
class xyz{
public static void main(String[] args){
Scanner sc = new Scanner(System.in);

System.out.println("Enter your first number:");
int a = sc.nextInt();
System.out.println("Enter your second number:");
int b = sc. nextInt();

boolean c = (a==b);
boolean d = (a!=b);
boolean e = (a<b);
boolean f = (a>b);
boolean g = (a<=b);
boolean h = (a>=b);
System.out.println("a==b= " + c);
System.out.println("a!=b= " + d);
System.out.println("a<b= " + e);
System.out.println("a>b= " + f);
System.out.println("a<=b= " + g);
System.out.println("a>=b= " + h);

}
}
```

## Output:
```java
Enter your first number:
31
Enter your second number:
11
a==b= false
a!=b= true
a<b= false
a>b= true
a<=b= false
a>=b= true
```
