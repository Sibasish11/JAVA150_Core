# Write a program to check if a given year is a leap year. (A year is a leap year if it is divisible by 4, but not by 100, unless it is also divisible by 400). [Medium]

```java
import java.io.*;
import java.util.Scanner;

public class LeapYearCheck {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a year: ");
        int year = sc.nextInt();

        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            System.out.println(year + " is a leap year.");
        } else {
            System.out.println(year + " is not a leap year.");
        }

        sc.close();
    }
}

```

# Output:
```java
 Enter a year: 2024
2024 is a leap year.

Enter a year: 1900
1900 is not a leap year.

Enter a year: 2000
2000 is a leap year.

```
