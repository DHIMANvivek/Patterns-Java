# 1

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

# 2

# Parallelogram Pattern

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->


#### Code you used for Submit/Run operation


```
// Pattern 
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
        Scanner s = new Scanner (System.in);
		int n = s.nextInt();
		
		
		
		int i = 1;
		
		while(i<=n) {
			int space = 1;
			while(space<=i-1) {
				System.out.print(" ");
				space = space + 1;
				
			}
			int j = 1;
			while (j<= n) {
				System.out.print("*");
				j = j + 1;
				
			}
			
			i = i + 1;
			System.out.println();
		}
		// Write your code here

	}
}

```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
Parallelogram Pattern


#### Screenshots


![parallelogram](https://user-images.githubusercontent.com/53940939/155984582-9014f83a-5a92-4edc-bf9d-25094f98f952.png)


# 3

# Half Diamond Pattern

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->


#### Code you used for Submit/Run operation


```
// Pattern 
import java.util.Scanner;
public class Solution {
    
     public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		int n = scan.nextInt();
		int i = 1;
		int n1 = n;
		int n2 = n1-1;
		
		System.out.println("*");
		while (i <= n1) {

			
			int star = 1;
System.out.print("*");
			while (star <= i) {
				// i+j-1;
				System.out.print(star);
				star++;
			}
			int dec = i - 1;
			while (dec >= 1) {
				System.out.print(dec);
				dec--;
			}
			System.out.print("*");
			System.out.println();
			i++;

		}

		i = n2;

		while (i > 0) {
			System.out.print("*");
			int star = 1;

			while (star <= i) {
				// i+j-1;
				System.out.print(star);
				star++;
			}
			int dec = i - 1;
			while (dec >= 1) {
				System.out.print(dec);
				dec--;
			}
			System.out.print("*");
			System.out.println();
			i--;

		}
		System.out.print("*");
	}
}

```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
 Half Diamond Pattern


#### Screenshots


![half diamond](https://user-images.githubusercontent.com/53940939/155985151-811353de-1999-4759-be03-b3748d9eb814.png)







