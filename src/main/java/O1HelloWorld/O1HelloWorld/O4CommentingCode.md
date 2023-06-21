# Commenting Code

- // single-line syntax for short comments

````java
// calculate customer satisfaction rating
````

- /\*...*/ multi-line syntax for long comments

````java
/* We chose to store information across multiple databases to
minimize the possibility of data loss. We'll need to be careful to make sure it does not go out of sync!*/
````

- Javadoc comment: /\**...\*/ : used to create documentation for API's (Application Programming Interfaces)
  - Be careful when using because they will be used in documentation that users might read
  - usually written before declaration of fields, methods and classes

````java
/**
 * The following class accomplishes the following task...
 */
````

````java
/**
* The following class shows what a comment would look like in a program.
*/
public class CommentExample {
  // I'm a comment inside the class
  public static void main(String[] args) {
    // I'm a comment inside a method
    System.out.println("This program has comments!");
  }
}
````