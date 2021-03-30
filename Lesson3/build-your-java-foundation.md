# 3. Build Your Java Foundation

| CONCEPT | A Java program (or application or app) has many moving parts that you must make some effort to understand early on in your Java career.|
| :---: | :-----------: |

In the previous lesson, I said a Java program is a class with a main method. In this lesson, I want to expand on that idea, and further introduce you to other relevant elements of a Java program. 

## 3.1 Anatomy of a Java Program

Your first step in learning Java is to learn and understand what makes up a Java program. We will explore the anatomy of a Java program by revisiting your first Java program

```java
public class MyFirstJavaProgram {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### 3.1.1 A Java Program is a class

To make this idea clearer, let's slightly modify your first program by dropping the opening brace to a new line, and removing everything, but the class definition (The line with the word class in it).

> A **class** has a header and a body

![A Java Program is a class](media/program-class.png)

> **NOTE:** It doesn't matter whether the opening brace is on the same line as the class' header or on the line below the header. However, many Java developers love having it on the same line as the class' header.

#### 3.1.1.1 A class' header

> A **class header** includes the class' name, which you choose, and a series of keywords that further defines the class.

![Class header](media/class-header.png)

#### 3.1.1.2 A class' body

The class' body is delimited by an opening and a closing brace. Inside a class' body is where you place the class' fields and methods. In your first program, you only have a single method, but there can be additional methods and one or more fields. We will continue to explore these as the semester moves along.

To further discuss the class' body, we will bring back the code we removed before.

