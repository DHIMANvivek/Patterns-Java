# Patterns-Java

# Sum Pattern

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->



#### Code you used for Submit/Run operation


```
// Sum Pattern
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int n = s.nextInt();
        int currRow = 1;
        int sum = 0;
        while(currRow <= n) {
            sum += currRow;
            int currCol = 1;
            while(currCol <= currRow) {
                System.out.print(currCol);
                if(currCol == currRow)
                	System.out.print("=");
                else
                	System.out.print("+");
                currCol += 1;
            }
            System.out.println(sum);
            currRow += 1;
        }
    }
}
```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
milestone 1 pattern-2

#### Screenshots

![sum pattern](https://user-images.githubusercontent.com/53940939/155983142-287d0dfd-f055-4d6a-90ee-8719777a0ead.png)






Thankyou :)
