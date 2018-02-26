# BJP4 Self-Check 1.23: Strange

> **What is the output produced from the following program? You may wish to
> draw a structure diagram first.**
>
> ```java
> public class Strange {
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
>   
>   public static void main(String[] args) {
>     first();
>     third();
>     second();
>     third();
>   }
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

    Inside first method.
    Inside third method.
    Inside first method.
    Inside second method.
    Inside first method.
    Inside second method.
    Inside first method.
    Inside third method.
    Inside first method.
    Inside second method.
    Inside first method.

</details>

**Author**: Roy McElmurry (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s23-Strange)
