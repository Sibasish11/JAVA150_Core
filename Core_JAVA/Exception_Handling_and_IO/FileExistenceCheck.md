# Write a program that checks if a file or directory exists at a given path using java.io.File. [Low]

```java

import java.io.File;

public class FileExistenceCheck {
    public static void main(String[] args) {
        // Change the path as per your system
        String path = "output.txt";  

        File file = new File(path);

        if (file.exists()) {
            if (file.isFile()) {
                System.out.println("The file \"" + path + "\" exists.");
            } else if (file.isDirectory()) {
                System.out.println("The directory \"" + path + "\" exists.");
            }
        } else {
            System.out.println("The path \"" + path + "\" does not exist.");
        }
    }
}


```

## Output:

Example Output:

If output.txt exists in the same folder →

```java
The file "output.txt" exists.
```

If the given path is a directory →

```java
The directory "myFolder" exists.
```

If it doesn’t exist →

```java
The path "abc.txt" does not exist.
```
