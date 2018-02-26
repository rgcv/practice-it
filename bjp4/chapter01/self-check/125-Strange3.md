# BJP4 Self-Check 1.25: Strange3

> **What is the output produced from the following program? You may wish to draw
> a structure diagram first. This is a slightly modified version of the previous
> problem, `Strange`.**
>
> ```java
> public class Strange {
>   public static void main(String[] args) {
>     second();
>     first();
>     second();
>     third();
>   }
>
>   public static void first() {
>     System.out.println("Inside first method.");
>   }
>
>   public static void second() {
>     System.out.println("Inside second method.");
>     first();
>   }
>
>   public static void third() {
>     System.out.println("Inside third method.");
>     first();
>     second();
>   }
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

    Inside second method.
    Inside first method.
    Inside first method.
    Inside second method.
    Inside first method.
    Inside third method.
    Inside first method.
    Inside second method.
    Inside first method.

</details>

**Author**: Roy McElmurry (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s25-Strange3)
