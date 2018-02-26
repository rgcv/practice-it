# BJP4 Self-Check 1.27: Confusing2

> **What is the output of the following Java program?**
>
> ```java
> public class Confusing {
>   public static void main(String[] args) {
>     method1();
>     method3();
>     method2();
>     method3();
>   }
> 
>   public static void method2() {
>     method1();
>     System.out.println("I am method 2.");
>   }
>   
>   public static void method3() {
>     method1();
>     method2();
>     System.out.println("I am method 3.");
>   }
>   
>   public static void method1() {
>     System.out.println("I am method 1.");
>   }
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

    I am method 1.
    I am method 1.
    I am method 1.
    I am method 2.
    I am method 3.
    I am method 1.
    I am method 2.
    I am method 1.
    I am method 1.
    I am method 2.
    I am method 3.

</details>

**Author**: Roy McElmurry (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s27-Confusing2)
