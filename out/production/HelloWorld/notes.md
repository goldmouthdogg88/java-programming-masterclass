<style>
.vocab {
    font-size: 17px;
    font-weight: bold;
}
</style>

# Hello World Project

The public Java keyword is an access modifier. An access modifier allows us to define the scope or how other parts of your code or even someone else's code can access this code.

For now we'll use the public access modifier to give full access. We'll come back to access modifiers once we get further into the course.


### Defining a class
Defining a class. The class keyword is used to define a class with the name following the keyword - Hello in this case and left and right curly braces to define the class block.

"To define a class requires an optional access modifer, followed by class, followed by the left and right curly braces. The left and right curly braces are defining the class body - anything between them is "part" of this class. We can have data and code as you will see as we progress."


### Defining the Main Method

What is a method? It's a collection of statements (one or more) that performs an operation. We'll be using a special method called the main method that Java looks for when running a program. It's the entry point of any Java code.

You can create your own as you will see later, but for now, let's create this main method.



<strong class='vocab'>public </strong>is an access modifier we discussed when defining the class in the last video - same principle.

<strong class='vocab'>static</strong> is a Java keyword that needs an understanding of other concepts, for now, know that we need to have static for Java to find our method to run the code we are going to add.

<strong class='vocab'>void</strong> is yet another Java keyword used to indicate that the method will not return anything - more on that later.

The left and right parenthesis in a method declaration are mandatory and can optionally include or more parameters - which is a way to pass information to a method.

```java

public class Hello {
    public static void main(String[] args) {
        
    }
}
```


<strong class='vocab'>Code block</strong> - A code block is used to define a block of code. It's mandatory to have one in a method declaration, and it's here where we will be adding statements to perform certain tasks.

<strong class='vocab'>Statement</strong> - This is a complete command to be executed and can include one or more expression (we'll see these in action later).

```java

public class Hello {

    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```