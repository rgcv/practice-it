# BJP4 Self-Check 1.24: Strange2

> **What would have been the output of the preceding program if the `third`
> method contained the following statements?**
>
> ```java
> public static void third() {
>   first();
>   second();
>   System.out.println("Inside third method");
> }
> ```

<details>
  <summary><strong>View Answer</strong></summary>

    Inside first method
    Inside first method
    Inside second method
    Inside first method
    Inside third method
    Inside second method
    Inside first method
    Inside first method
    Inside second method
    Inside first method
    Inside third method

</details>

**Author**: Marty Stepp (on 2016/09/08) • [Source](https://practiceit.cs.washington.edu/problem/view/bjp4/chapter1/s24-Strange2)
