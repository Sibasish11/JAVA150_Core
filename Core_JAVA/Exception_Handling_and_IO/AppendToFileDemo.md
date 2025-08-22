# Write a program that appends new text to an existing file without overwriting its content. [Medium]

```java

import java.io.FileWriter;
import java.io.IOException;

public class AppendToFileDemo {
    public static void main(String[] args) {
        try {

            FileWriter fw = new FileWriter("output.txt", true);

            // Text to append
            fw.write("\nThis is the newly appended text.");

            fw.close();

            System.out.println("Text appended successfully!");

        } catch (IOException e) {
            System.out.println("An error occurred while appending to the file.");
            e.printStackTrace();
        }
    }
}


```

### Output:


📂 Example:

If output.txt originally contains:

```java
This is some text.
```

After running the program, it will become:

```java
This is some text.
This is the newly appended text.
```
