# Write a program to count the number of lines in a text file. [Medium]

```java

import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;

public class LineCountInFile {
    public static void main(String[] args) {
        
        String filePath = "sample.txt"; // Change to your file name

        int lineCount = 0;

        try (BufferedReader br = new BufferedReader(new FileReader(filePath))) {
            while (br.readLine() != null) {
                lineCount++;
            }

            System.out.println("Total number of lines in file: " + lineCount);

        } catch (IOException e) {
            System.out.println("An error occurred while reading the file: " + e.getMessage());
        }
    }
}


```

## Output:


🔎 Example Output (for a file containing):

```java
Hello world
This is a test file
Java File Handling
```

Output:

```java
Total number of lines in file: 3
```
