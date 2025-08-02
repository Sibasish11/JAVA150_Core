# Write a program to take your name as a string input from the console and print a personalized greeting message. [Low]

```java
import java.io.*;
import java.util.*;

class name{
public static void main(String args[]){
Scanner sc = new Scanner(System.in);
System.out.println("What is your name?");
String name = sc.nextLine();
System.out.println("Hi " + name + ", Warm greetings!");
}
}
```
### Output:

```java
What is your name?
Sibasish
Hi Sibasish, Warm greetings!
```
