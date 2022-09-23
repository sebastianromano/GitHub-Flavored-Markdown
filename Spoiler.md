# Hiding spoiler text in Markdown

<details>
  <summary>
  This is how to write spoiler text in GitHub Flavored markdown(<i>click</i> to  <b>expand</b>)
  </summary>
  <!-- have to be followed by an empty line! -->

## *formatted* **heading** with [a](link)
```java
public class Test {
  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}
```

  <details>
    <summary>
    <u>nested</u> <b>stuff</b> (<i>click to expand</i>)
    </summary>
    <!-- have to be followed by an empty line! -->

A bit more than normal indentation is necessary to get the nesting correct,
1. list
1. with
    1. nested
    1. items
        ```java
        // including code
        ```
    1. blocks
1. and continued non-nested

  </details>
</details>