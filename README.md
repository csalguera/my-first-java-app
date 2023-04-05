## My-First-Java-App

This repo hosts various exercises to learn Java, the same exercises can be found at [Codecademy](https://www.codecademy.com/learn/java-introduction). The purpose of this repo is to practice Java utilizing an IDE (Integrated Development Environment), namely [VS Code](https://code.visualstudio.com/download).

## Contents

* Install Java
* [Create a Java Project](https://github.com/csalguera/my-first-java-app#create-a-java-project)
* [Cloning this Repo](https://github.com/csalguera/my-first-java-app#cloning-this-repo)
* [Exercise 1 - HelloYou](https://github.com/csalguera/my-first-java-app#helloyou)
* [Exercise 2 - HideAndSeek](https://github.com/csalguera/my-first-java-app#hideandseek)
* [Exercise 3 - Timeline](https://github.com/csalguera/my-first-java-app#timeline)
* [Exercise 4 - LanguageFacts](https://github.com/csalguera/my-first-java-app#languagefacts)
* [Exercise 5 - Compiling](https://github.com/csalguera/my-first-java-app#compiling)
* [Exercise 6 - Review](https://github.com/csalguera/my-first-java-app#review)
* [Attributions](https://github.com/csalguera/my-first-java-app#attributions)

## Install Java

* Visit [java.com](https://www.java.com/en/) and download the [Mac](https://javadl.oracle.com/webapps/download/AutoDL?BundleId=247939_0ae14417abb444ebb02b9815e2103550) version or [Windows](https://javadl.oracle.com/webapps/download/AutoDL?BundleId=247917_0ae14417abb444ebb02b9815e2103550) version

* Go to [visualstudio.com](https://code.visualstudio.com/docs/languages/java) and install the Java Development Kit for [Mac](https://aka.ms/vscode-java-installer-mac) or for [Windows](https://aka.ms/vscode-java-installer-win)

* Optionally download the [Extension Pack for Java](vscode:extension/vscjava.vscode-java-pack)

## Create a Java Project

### Mac:

* Inside of Visual Studio Code hold ```command``` + ```shift``` + ```p``` type ```Java: Create Java Project...``` and hit ```return```

### Windows:

* Inside of Visual Studio Code hold ```ctrl``` + ```shift``` + ```p``` type ```Java: Create Java Project...``` and hit ```enter```


A prompt will appear, select ```No build tools``` for now.

Select a desired location for your Java Project (Note: A directory will be created at the desired location)

Finally you will be prompted to name your Java Project

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## Cloning this Repo

To clone this repo, ```cd``` into your desired directory and sinmply run the command:

```
git clone https://github.com/csalguera/my-first-java-app
```

To make a blank slate for practice of these exercises, run the following commands:

```
cd my-first-java-app
rm -rf ./src
mkdir ./src ./.vscode ./lib
touch ./.vscode/settings.json
```

Open your local repository in VS Code by running the following command:

```
open -a "Visual Studio Code" .
```

Inside of your ```.vscode``` directory, locate the ```settings.json``` file and paste the following:

```
{
  "java.project.sourcePaths": ["src"],
  "java.project.outputPath": "bin",
  "java.project.referencedLibraries": [
    "lib/**/*.jar"
  ]
}
```

Finally if you would like to have your own Remote Repo, run the following commands:

```
rm -rf .git
git init
git remote add origin <YourRemoteRepository>
```

Make your first commit with the following commands:

```
git add .
git commit -m "initial commit"
git push -u origin main
```

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## HelloYou

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

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## HideAndSeek

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

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## Timeline

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

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## LanguageFacts

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

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## Compiling

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

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## Review

Inside of your ```src``` directory touch a ```Review.java``` file and fill it in!

Define a public class named Review.

Use opening and closing curly braces for the scope of the class.

Remember, no semicolons for classes or methods!

This code produces an error because Java programs need a main() method.

Define the main() method within the curly braces of the Review class.

Inside of the curly braces for the main() method, write ```The main method executes the tasks of the class``` as a single-line comment.

Below the comment, write a statement that prints the following: My first Java program from scratch!.

##### [Back to Contents](https://github.com/csalguera/my-first-java-app#contents)

## Attributions

View the [attributions](https://github.com/csalguera/my-first-java-app/blob/main/attributions.md)