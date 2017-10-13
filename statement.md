# Java Programming Tests

The CodinGame Java online tests assess candidates' skills. They are perfect for pre-employment screening for developers. Most of the coding interview tools focus only on the candidates' ability to write efficient algorithms but algorithms are a tiny part of software development, mastering them is one skill among several other important skills. We are providing tests covering a wide scope of technical characteristics to evaluate candidates' ability to write good Java programs.

## Java Language
These questions check the candidate’s ability to use functionalities that are well-known to Java developers. Using the correct APIs and data structures determine the candidate's level of experience in the practice of the Java programming language. This skill is particularly important if you are looking for a developer who has to be quickly operational in a Java working environment.

An example of very simple task we provide consists in writing a method which returns `true` if the parameter equals to `"Hello World"`, `false` otherwise. The candidate has 2 minutes to solve it.

Try it yourself:
```java runnable
// { autofold
public class Main {

    
public static void main(String[] args) {
    isHelloWord("Hello World");
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

Too much simple, isn't it?


See some stats among all candidates who took this test:
- 4% did not write a solution which success (compilation error / the test fails)
- 14% write `return str == "Hello World";` 😱
- 63% write `return str.equals("Hello World");` 🤔 what happens if `str` is null?
- **19% write the expected code `return "Hello World".equals(str);`**

What we learned? 
- 1 programmer among 5 is not able to write a very simple line of code in Java (useful information to stop the hiring process quickly)
- 3 programner among 5 is able to write a very simple line of code
- 1 programmer among 5 is able to solve this simple problem the right way


