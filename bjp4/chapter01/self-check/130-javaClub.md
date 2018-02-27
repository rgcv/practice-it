# BJP4 Self-Check 1.30: javaClub

> **Consider the following program, saved into a file named `Example.java`:**
>
> ```java
> public class Example {
>   public static void displayRule() {
>     System.out.println("The first rule ");
>     System.out.println("of Java Club is,");
>     System.out.println();
>     System.out.println("you do not talk about Java Club.");
>   }
>
>   public static void main(String[] args) {
>     System.out.println("The rules of Java Club.");
>     displayRule();
>     displayRule();
>   }
> }
> ```
>
> **What would happen if each of the following changes were made to the Example
> program? If there would be no change to the program, choose "nothing". If it
> would cause the program not to compile, choose "error". If it would change the
> program's output, choose "output". Treat each change independently of the
> others**

<table>
  <thead>
    <tr>
      <td><strong>Change</strong></td>
      <td><strong>Answer</strong></td>
    </tr>
  </thead>
  <tbody>
    <!-- Change line 1 -->
    <tr>
      <td>1. Change line 1 (class declaration) to</td>
      <td rowspan="2">
        <details>
          <summary><strong>View Answer</strong></summary>
          <strong>error</strong>
        </details>
      </td>
    </tr>
    <tr><td><code>public class Demonstration</code></td></tr>
    <!-- Change line 9 -->
    <tr>
      <td>2. Change line 9 (<code>main</code> method) to</td>
      <td rowspan="2">
        <details>
          <summary><strong>View Answer</strong></summary>
          <strong>error</strong>
        </details>
      </td>
    </tr>
    <tr><td><code>public static void MAIN(String[] args) {</code></td></tr>
    <!-- Insert new line after 11 -->
    <tr>
      <td>
        3. Insert a new line after line 11 (first call to
        <code>displayRule</code>) that reads
      </td>
      <td rowspan="2">
        <details>
          <summary><strong>View Answer</strong></summary>
          <strong>output</strong>
        </details>
      </td>
    </tr>
    <tr><td><code>System.out.println();</code></td></tr>
    <!-- Change line 2 -->
    <tr>
      <td>4. Change line 2 (<code>displayRule</code> method) to</td>
      <td rowspan="2">
        <details>
          <summary><strong>View Answer</strong></summary>
          <strong>error</strong>
        </details>
      </td>
    </tr>
    <tr><td><code>public static void printMessage() {</code></td></tr>
    <!-- Change line 2 and lines 11 and 12 -->
    <tr>
      <td>5. Change line 2 to</td>
      <td rowspan="4">
        <details>
          <summary><strong>View Answer</strong></summary>
          <strong>nothing</strong>
        </details>
      </td>
    </tr>
    <tr><td><code>public static void showMessage() {</code></td></tr>
    <tr>
      <td>and change lines 11 and 12 (calls to <code>displayRule</code>) to</td>
    </tr>
    <tr><td><code>showMessage();</code></td></tr>
    <!-- Replace lines 3-4 -->
    <tr>
      <td>
        6. Replace lines 3-4 (first 2 prints in <code>displayRule</code>) with
      </td>
      <td rowspan="2">
        <details>
          <summary><strong>View Answer</strong></summary>
          <strong>output</strong>
        </details>
      </td>
    </tr>
    <tr>
      <td>
        <code>System.out.println("The first rule of Java Club is,");</code>
      </td>
    </tr>
  </tbody>
</table>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s30-javaClub)
