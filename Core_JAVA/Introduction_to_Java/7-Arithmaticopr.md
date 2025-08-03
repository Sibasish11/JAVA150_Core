# Write a program to demonstrate the use of arithmetic operators (+, -, *, /, %). Take two numbers as input and show the result of each operation. [Low]

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

int c = a+b;
int d = a-b;
int e = a*b;
int f = a/b;
int g = a%b;
System.out.println("a+b= " + c);
System.out.println("a-b= " + d);
System.out.println("a*b= " + e);
System.out.println("a/b= " + f);
System.out.println("a%b= " + g);

}
}
```

## Output:

```java
Enter your first number:
31
Enter your second number:
11
a+b= 42
a-b= 20
a*b= 341
a/b= 2
a%b= 9
```
