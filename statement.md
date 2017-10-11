# Java Programming Tests

The CodinGame Java online tests assess candidates' skills. They are perfect for pre-employment screening for developers. Most of the coding interview tools focus only on the candidates' ability to write efficient algorithms but algorithms are a tiny part of software development, mastering them is one skill among several other important skills. We are providing tests covering a wide scope of technical characteristics to evaluate candidates' ability to write good Java programs.

## Java Language
These questions check the candidate’s ability to use functionalities that are well-known to Java developers. Using the correct APIs and data structures determine the candidate's level of experience in the practice of the Java programming language. This skill is particularly important if you are looking for a developer who has to be quickly operational in a Java working environment.

An example of very simple task we provide consists in writing a method which returns `true` if the parameter equals to `"Hello World"`, `false` otherwise.

```java runnable
// { autofold
public class Main {

    
public static void main(String[] args) {
    isHelloWord(new String("Hello World"));
}
// }

/** Returns true if str is equal to "Hello World", false otherwise. **/
static boolean isHelloWord(String str) {
    return ??
}

//{ autofold
}
//}
```

30% of the candidates write: `return str == "Hello World";` scary!
55% write `return str.equals("Hello World");` correct, but what happens if `str` is null?
15% write `return "Hello World".equals(str);` expected solution

