# BJP4 Self-Check 1.24: Strange2

> **What is the output produced from the following program? You may wish to draw
> a structure diagram first. This is a slightly modified version of the previous
> problem, `Strange`.**
>
> ```java
> public class Strange {
>   public static void main(String[] args) {
>     first();
>     third();
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
>     first();
>     second();
>     System.out.println("Inside third method.");
>   }
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

    Inside first method.
    Inside first method.
    Inside second method.
    Inside first method.
    Inside third method.
    Inside second method.
    Inside first method.
    Inside first method.
    Inside second method.
    Inside first method.
    Inside third method.

</details>

**Author**: Roy McElmurry (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s24-Strange2)
