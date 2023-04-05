## My-First-Java-App

This repo hosts various exercises to learn Java.

## Contents

* Exercise 1 - HelloYou
* Exercise 2 - HideAndSeek
* Exercise 3 - Timeline
* Exercise 4 - LanguageFacts
* Exercise 5 - Compiling
* Exercise 6 - Review


### HelloYou

Inside your ```src``` directory touch a ```HelloYou.java``` file, that contains a HelloYou class with a main() method.

Inside main(), add a statement which prints ```Hello someName!```, with your name replacing ```someName```. Make sure to end the statement with a semicolon.

For example, if your name were “Maria,” the program would print ```Hello Maria!```.

```
public class HelloYou {
  public static void main(String[] args) {
    System.out.println();
  }
}
```

### HideAndSeek

Inside your ```src``` directory touch a ```HideAndSekk.java``` file.

Inside main() and underneath the print statement ```System.out.println("Let's play hide and seek.");```, output the following two statements using System.out.print():

```"Three..."```

```"Two..."```

Underneath your previous statements, output the following two text values using System.out.println():

```"One..."```

```"Ready or not, here I come!"```

```
public class HideAndSeek {
  public static void main(String[] args) {
    System.out.println("Let's play hide and seek.");
  }
}
```

### Timeline

Inside your ```src``` directory touch a ```Timeline.java``` file with plain text information about Java.

Plain text facts aren’t valid syntax. We’ll use comments to avoid breaking the program.

Use the single-line comment syntax for the first fact.

Change this line into a comment:

```Sun Microsystems announced the release of Java in 1995```

```
public class Timeline {
  public static void main(String[] args) {
    System.out.println("Hello Java!");

    System.out.println("You were born in 1995");

    Sun Microsystems announced the release of Java in 1995

    System.out.println("You were created by James Gosling");

    James Gosling is a Canadian engineer who 
    created Java while working at Sun Microsystems.
    His favorite number is the square root of 2!

    System.out.println("You are a fun language!");
  }
}
```

Our program is still broken!

Use the multi-line syntax to make these lines into a single comment:

```James Gosling is a Canadian engineer who```

```created Java while working at Sun Microsystems.```

```His favorite number is the square root of 2!```

You should still see You are a fun language! printed!

### LanguageFacts

Inside your ```src``` directory touch a ```LanguageFacts.java``` file that prints information about Java to the screen.

Unfortunately, the file does not have whitespace.

Make the file easier to read by adding a newline after each statement!

Press ```enter``` or ```return``` after each semicolon!

```
public class LanguageFacts {
  public static void main(String[] args) {
    System.out.println("Java is a class-based language.");System.out.println("Java classes have a 'main' method.");System.out.println("Java statements end with a semicolon.");
  }
}
```

Inside main(), add a new statement printing how you feel about coding.

Start the message with: ```“Programming is… “```.

Remember to place a semicolon at the end of the statement!

### Compiling

Let’s practice compiling and executing a file by entering commands in the terminal!

Our text editor contains a broken program so we can see how compilers help us catch mistakes. Don’t make any corrections!

Inside your ```src``` directory touch a ```Compiling.java``` file.

In the terminal, type this command: ```javac Compiling.java``` and press ```enter``` or ```return```.

```
public class Compiling {
  public static void main(String[] args) {
    System.out.println("Java is a class-based language.");
    System.out.println("Java classes have a 'main' method.");
    System.out.println("Java statements end with a semicolon.")
    System.out.println("Programming is... fun!");
  }
}
```

Do you see the error?

The compiler is telling us one of the print statements is missing a semicolon.

Change into your ```src``` directory by running the command: ```cd ./src```

In the terminal, type ```ls``` and press ```return``` or ```enter```.

```ls``` is short for "list" and this command lists all the available files.

There should be a ```Compiling.java``` file, we did not successfully compile the file because of the error.

Add the missing semicolon in the text editor.

Let’s compile and execute our program!

Run the ```ls``` command in the terminal to see the uncompiled ```.java``` file.

Compile the file from the terminal.

Enter ```ls``` again to see the new ```.class``` file.

Run the executable file from the terminal by running this command: ```java Compiling```

After executing your file, delete it by running the command: ```rm -rf Compiling.class``` and change back to the parent directory by running the command: ```cd ..```

(Note: Java files are automatically compiled from your ```src``` directory into your ```bin``` directory. Alternatively you can change into you ```bin``` directory with the command: ```cd ./bin``` and run the executable file from the terminal by running this command: ```java Compiling```. To change back into your parent directory run the command: ```cd ..```)

### Review

Inside of your ```src``` directory touch a ```Review.java``` file and fill it in!

Define a public class named Review.

Use opening and closing curly braces for the scope of the class.

Remember, no semicolons for classes or methods!

This code produces an error because Java programs need a main() method.

Define the main() method within the curly braces of the Review class.

Inside of the curly braces for the main() method, write ```The main method executes the tasks of the class``` as a single-line comment.

Below the comment, write a statement that prints the following: My first Java program from scratch!.