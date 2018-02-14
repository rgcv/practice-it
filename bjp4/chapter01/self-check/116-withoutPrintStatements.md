# BJP4 Self-Check 1.15: printlnSlashes

> **Rewrite the following code as a series of equivalent System.out.println
> statements (i.e., without any System.out.print statements):**
>
> ```java
> System.out.print("Twas ");
> System.out.print("brillig and the ");
> System.out.println(" ");
> System.out.print(" slithy toves did");
> System.out.print(" ");
> System.out.println("gyre and");
> System.out.println(  "gimble");
> System.out.println();
> System.out.println(  "in the wabe." );
> ```

<details>
  <summary><strong>View Answer</strong></summary>

```java
System.out.println("Twas brillig and the  ");
System.out.println("  slithy toves did gyre and");
System.out.println(  "gimble");
System.out.println();
System.out.println(  "in the wabe." );
```

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s16-withoutPrintStatements)
