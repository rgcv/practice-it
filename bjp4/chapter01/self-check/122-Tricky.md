# BJP4 Self-Check 1.22: Tricky

> **What is the output of the following program? (You may wish to draw a
> structure diagram first.)**
>
> ```java
> public class Tricky {
>   public static void main(String[] args) {
>     message1();
>     message2();
>     System.out.println("Done with main.");
>   }
> 
>   public static void message1() {
>     System.out.println("This is message1.");
>   }
>  
>   public static void message2() {
>     System.out.println("This is message2.");
>     message1();
>     System.out.println("Done with message2.");
>   }
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

    This is message1.
    This is message2.
    This is message1.
    Done with message2.
    Done with main.

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s22-Tricky)
