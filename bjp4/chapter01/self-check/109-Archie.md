# BJP4 Self-Check 1.9: Archie

> **What is the output produced from the following statements? (Treat tabs as
> aligning to every multiple of eight spaces.)**
>
> ```java
> System.out.println("name\tage\theight");
> System.out.println("Archie\t17\t5'9\"");
> System.out.println("Betty\t17\t5'6\"");
> System.out.println("Jughead\t16\t6'");
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

    name    age     height
    Archie  17      5'9"
    Betty   17      5'6"
    Jughead 16      6'

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s9-Archie)
