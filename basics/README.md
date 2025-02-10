# Java Basics

This repository contains the foundational steps to begin learning Java programming, starting with the traditional "Hello, World!" program. This program introduces key concepts and workflows required to write, compile, and execute Java programs. Below, you'll find a streamlined guide to the basics.

---

## Steps to Create and Run a Java Program

### 1. Write the Program
- Use a text editor or an IDE (Integrated Development Environment) to write your Java program.
- Example: "Hello, World!" Program:

```java
/** A program to display the message "Hello, World!" */
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### 2. Save the Program
- Save the file with the name matching the public class name. For the above program, the file must be saved as `HelloWorld.java`.

### 3. Compile the Program
- Use the Java compiler (`javac`) to compile the source code into bytecode.
- Command:
  ```bash
  javac HelloWorld.java
  ```
- Output: A compiled file named `HelloWorld.class` is generated.

### 4. Run the Program
- Use the Java interpreter (`java`) to execute the compiled bytecode.
- Command:
  ```bash
  java HelloWorld
  ```
- Output: The message `Hello, World!` will be displayed.

---

## Key Concepts

### Java Program Structure
1. **Class Declaration**:
   - All Java programs are defined within classes.
   - Example: `public class HelloWorld`.

2. **Main Method**:
   - The entry point for program execution.
   - Syntax:
     ```java
     public static void main(String[] args) {
         // statements
     }
     ```

3. **Statements**:
   - The main logic of the program is written inside the `main()` method.
   - Example: `System.out.println("Hello, World!");` is a statement that prints text to the standard output.

4. **Comments**:
   - Used for documentation and ignored by the compiler.
   - Single-line comments: `// This is a comment`
   - Multi-line comments: `/* This is a multi-line comment */`

---

## File Naming and Compilation
1. **File Name**:
   - Must match the public class name.
   - Example: For `public class HelloWorld`, the file name must be `HelloWorld.java`.

2. **Compilation**:
   - Translates the source code (`.java` file) into bytecode (`.class` file).
   - Bytecode is platform-independent and executed by the Java Virtual Machine (JVM).

3. **Execution**:
   - The compiled `.class` file is executed using the `java` command.

---

## Example Workflow
1. Write `HelloWorld.java` with the following content:
   ```java
   public class HelloWorld {
       public static void main(String[] args) {
           System.out.println("Hello, World!");
       }
   }
   ```

2. Compile the program:
   ```bash
   javac HelloWorld.java
   ```

3. Run the program:
   ```bash
   java HelloWorld
   ```

---

## Notes
- Java programs are case-sensitive.
- Indentation and layout are not mandatory for the compiler but are crucial for human readability.
- Always ensure that your working directory aligns with the package structure, if using packages.

