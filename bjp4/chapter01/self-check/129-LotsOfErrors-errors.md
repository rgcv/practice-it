# BJP4 Self-Check 1.29: LotsOfErrors-errors

> **The following program contains at least 10 errors. Correct the errors and
> submit a working version of the program.**
>
> ```java
> public class LotsOf Errors {
>   public static main(String args) {
>     System.println(Hello, world!);
>     message()
>   }
>   
>   public static void message {
>     System.out.println("This program surely cannot ";
>     System.out.println("have any "errors" in it");
>   }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

```java
public class LotsOfErrors {
  public static void main(String[] args) {
    System.out.println("Hello, world!");
    message();
  }
  
  public static void message() {
    System.out.println("This program surely cannot ");
    System.out.println("have any \"errors\" in it");
  }
}
```

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s29-LotsOfErrors-errors)
