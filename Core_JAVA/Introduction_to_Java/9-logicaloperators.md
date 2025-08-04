# Write a program to demonstrate the use of logical operators (&&, ||, !). Use boolean variables to show their behaviour. [Low]

```java
import java.io.*;

class xyz {
    public static void main(String args[]) {
        int a = 10;
        int b = 20;

        boolean k = (a <= b) && (a >= 6);
        System.out.println("k = " + k);  

        boolean x = (a == b) || (a >= b);
        System.out.println("x = " + x);  

        boolean m = !(a > 0); 
        System.out.println("m = " + m); 
    }
}

```
# Output:
```java
k = true
x = false
m = false
```
