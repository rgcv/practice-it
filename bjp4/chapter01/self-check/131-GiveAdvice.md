# BJP4 Self-Check 1.32: Messy

> **The following program is legal under Java syntax rules, but it is difficult
> to read because of its layout and lack of comments. Reformat it using the
> rules given in Chapter 1, and add a comment header at the top of the
> program.**
>
> **(Practice-it isn't really able to check that you satisfied the requirements
> of this question. You will receive credit as long as you supply a reasonable
> amount of indentation and two lines of `//` comments)**
>
> ```java
> public
> class Messy{public
> static void main(String[]args){message ()
>   ;System.out.println() ; message ( );} public static void
> message() { System.out.println(
>     "I really wish that"
>     );System.out.println
> ("I had formatted my source")
> ;System.out.println("code correctly!");}}
> ```

<details>
  <summary><strong>View Answer</strong></summary>

```java
public class Messy {
  // Another 2 pieces of magnificent
  // poetry. Shakespeare would be proud..
  public static void main(String[] args) {
    message();
    System.out.println();
    message();
  }

  public static void message() {
    System.out.println("I really wish that");
    System.out.println("I had formatted my source");
    System.out.println("code correctly!");
  }
}
```

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s32-Messy)
