# Write a program that uses a switch statement to print the day of the week (e.g., "Monday") given a number (1 for Monday, etc.). Handle invalid input. [Low]

```java
import java.util.Scanner;

public class DayOfWeek {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Input number for day
        System.out.print("Enter a number (1-7) for the day of the week: ");
        int day = sc.nextInt();

        // Switch statement to print day name
        switch (day) {
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("Wednesday");
                break;
            case 4:
                System.out.println("Thursday");
                break;
            case 5:
                System.out.println("Friday");
                break;
            case 6:
                System.out.println("Saturday");
                break;
            case 7:
                System.out.println("Sunday");
                break;
            default:
                System.out.println("Invalid input! Please enter a number between 1 and 7.");
        }

        sc.close();
    }
}
```

```java
Enter a number (1-7) for the day of the week: 3
Wednesday

Enter a number (1-7) for the day of the week: 9
Invalid input! Please enter a number between 1 and 7.
```
