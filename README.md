# Welcome to Intro to Java!

## Instructions

### Part 1

Whenever you open an assignment in repl.it, you'll see two things open. The instructions you are reading right now, and the stater code to the left.

For now try clicking the `run` button at the top of your screen.

### Part 2

After you run the program, try to figure out what parts of the program are printing stuff to the screen? Can you figure out how to change what it prints?

Work with your table to modify the starter code to print:

```
Hello World!
```

<details>
  <summary>Click here if you need a hint!</summary>

```java
System.out.println("message");
```

will print "message" to the console. 

You can remove all of the lines that start with `System.out.println` from the code to make it stop printing the messages out. However the following lines of code are **mandatory** and cannot be removed:

```java
public class Main {
    public static void main(String[] args) {
        System.out.print("Hello");
        System.out.println("World!");
    }
}
```

</details>

### Part 3

Now that you've written your first program! You'll need to make sure others know you wrote it.

The top of your program should say:

```java
/*
 * Program Title: 
 * Author: 
 * Date: 
 * Purpose: 
 */
 ```

 You should modify it to match your personal details, as well as what the program is. Similar to the following:

 ```java
 /*
 * Program Title: Hello World!
 * Author: Hayden Mankin
 * Date: 11/22/2021
 * Purpose: Prints "Hello World!" to the console.
 */
 ```

### Part 4

Now it's time to submit your work! You'll need to do a couple things to submit an assignment:

1. Download the `Main.java` file from repl.it
    * Hover over `Main.java`.
    * Click the three dots to the right of the file name.
    * Click Download.
2. Copy the link to the repl.it
    * Copy the url from the top of your web browser.

You'll need to submit both of these things to the google classroom assignment for credit.

Follow these steps and submit it to the Hello World assignment on google classroom.

### Part 5

Once you've completed all of the previous steps it's time to play with java a bit more to figure out how it works.

Change your code to the following:

```java
public class Main {
    public static void main(String[] args) {
        System.out.print("Hello");
        System.out.println("World!");
    }
}
```

Run it and see what happens. Was the output what you expected? Discuss with your table what the difference is between `System.out.print` and `System.out.println`.

<details>
  <summary>Click here if you need a hint!</summary>

Make sure you notice the distinction on each line. `print` and `println` are different becuase one has an `ln` at the end.

The `ln` is short for line.

Try changing the `print` to `println` and vice versa. How does the output change?

</details>

### Part 6

Change your code to the following:

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Peter Piper picked a peck of pickled peppers.");
        System.out.println("I like computer science");
        System.out.println(25 / 5);
        System.out.println(4 / 7.0445902);
        System.out.println(13 * 159.56);
    }
}
```

Think about what this might output? Discuss with your table.

Run it and see what happens. Was the output what you expected? Discuss with your table what each line actually outputted to the console.

### Part 7

Lastly it's important to notice something about this project. If you click the link on google classroom again, it will make a new project instead of taking you to the one you have worked on all class.

To access the project again in the future you'll want to take note of the project name at the top of your screen.

If you go to repl.it/repls you'll notice a list of all projects you've created. You'll need to find or search for the project you want to work on.