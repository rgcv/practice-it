# BJP4 Self-Check 1.12: DoubleSlash

> **What is the output from the following Java program? (Assume that a tab is
> expanded into eight spaces.)**
>
> ```java
> public class Letter {
>   public static void main() {
>     System.out.println("Dear \"DoubleSlash\" magazine,");
>     System.out.println();
>     System.out.println("\tYour publication confuses me.  Is it");
>     System.out.println("a \\\\ slash or a //// slash?");
>     System.out.println("\nSincerely,");
>     System.out.println("Susan \"Suzy\" Smith");
>   }
> }
> ```
>
> (**NOTE ABOUT SPACING:** Many students fail this problem by not understanding
> how the `\t` character works, causing them to have the wrong number of spaces.
> A tab inserts multiple spaces until the total number of characters on the
> current line so far is a multiple of 8. So for example, in the string
> `"hi\thello\tgoodbye\tbeautiful\thi"`, the first `\t` becomes 6 spaces
> (because `"hi"` is 2 characters, so it takes 6 more to get to 8), the second
> `\t` is 3 spaces (because `"hello"` is 5 characters wide, so it takes 3 more
> characters to get to 8), the third is 1 (because `"goodbye"` is 7 characters),
> and the fourth `\t` is 7 spaces (because `"beautiful"` is 9 characters, so it
> takes 7 more to get to 16, which is the next multiple of 8).

<details>
  <summary><strong>View Answer</strong></summary>

    Dear "DoubleSlash" magazine,

            Your publication confuses me.  Is it
    a \\ slash or a //// slash?

    Sincerely,
    Susan "Suzy" Smith

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s12-DoubleSlash)
