# BJP4 Self-Check 1.20: FamousSpeech-errors

> **The following program contains four errors. Correct the errors and submit a
> working version of the program.**
>
> ```java
> public class FamousSpeech
>   public static void main(String[]) {
>     System.out.println("Four score and seven years ago,");
>     System.out.println("our fathers brought forth on");
>     System.out.println("this continent a new nation");
>     System.out.println("conceived in liberty,");
>     System.out.println("and dedicated to the proposition");
>     System.out.println("that");    /* this part should
>     System.out.println("all");        really say,
>     System.out.println("men");        "all PEOPLE!" */
>     System.out.println("are");
>     System.out.println("created");
>     System.out.println("equal");
>   }
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

```java
public class FamousSpeech {
  public static void main(String[] args) {
    System.out.println("Four score and seven years ago,");
    System.out.println("our fathers brought forth on");
    System.out.println("this continent a new nation");
    System.out.println("conceived in liberty,");
    System.out.println("and dedicated to the proposition");
    System.out.println("that");    // this part should
    System.out.println("all");     // really say,
    System.out.println("men");     // "all PEOPLE!"
    System.out.println("are");
    System.out.println("created");
    System.out.println("equal");
  }
}
```

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s20-FamousSpeech-errors)
