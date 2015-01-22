# Questions and Exercises: Getting Started
## Questions
<h3>Question 1: When you compile a program written in the Java programming language, the compiler converts the human-readable source file into platform-independent code that a Java Virtual Machine can understand. What is this platform-independent code called?</h3>
ByteCode

<h3>Question 2: Which of the following is not a valid comment:<br />a. /** comment */<br />b. /* comment */<br />c. /* comment<br />d. // comment</h3>
c., multi-line comment requires closing syntax(*/).

<h3>Question 3: What is the first thing you should check if you see the following error at runtime:<br /><pre>Exception in thread "main" java.lang.NoClassDefFoundError:
HelloWorldApp.java.</pre></h3>
The `java` launch command, the &lt;class name that implements `public static void main(String[])` method&gt; command argument shouldn't include file extension(.java).

<h3>Question 4: What is the correct signature of the <code>main</code> method?</h3>
`public static void main(String[])`

<h3>Question 5: When declaring the main method, which modifier must come first, <code>public</code> or <code>static</code>?</h3>
Both modifers can come first.

## Exercises
<h3>Exercise 1: Change the <code><a href='http://docs.oracle.com/javase/tutorial/getStarted/application/examples/HelloWorldApp.java' target='_blank'>HelloWorldApp.java</a></code> program so that it displays <code>Hola Mundo!</code> instead of <code>Hello World!</code>.</h3>
[HelloWorldApp.class](HelloWorldApp.class)

<h3>Exercise 2: You can find a slightly modified version of <code>HelloWorldApp</code> here: <code><a href='http://docs.oracle.com/javase/tutorial/getStarted/QandE/HelloWorldApp2.java' target='_blank'>HelloWorldApp2.java</a></code><br />
The program has an error. Fix the error so that the program successfully compiles and runs. What was the error?</h3>
[HelloWorldApp2.class](HelloWorldApp2.class)  
The string literal "Hello World!" is not closed.