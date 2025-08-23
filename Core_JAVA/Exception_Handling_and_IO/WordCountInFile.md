# Implement a program to count the number of words in a text file. [Medium]

```java

import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;

public class WordCountInFile {
    public static void main(String[] args) {

        String filePath = "sample.txt"; // Change to your file name

        int wordCount = 0;

        try (BufferedReader br = new BufferedReader(new FileReader(filePath))) {
            String line;

            while ((line = br.readLine()) != null) {
                
                String[] words = line.trim().split("\\s+");

                // Check if line is not empty
                if (!line.trim().isEmpty()) {
                    wordCount += words.length;
                }
            }

            System.out.println("Total number of words in file: " + wordCount);

        } catch (IOException e) {
            System.out.println("An error occurred while reading the file: " + e.getMessage());
        }
    }
}


```

🔎 Example Output (for a file containing):

```java
Hello world
This is a test file
```

```java
Total number of words in file: 6
```
