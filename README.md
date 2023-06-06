# Exp-4 Java program to print the even numbers between 1-20
## Aim:-
To write a java program to print the even numbers between 1-20

## Procedure:-
### Step 1:
Import the required packages

### Step 2:
Get the start and end value for the even numbers to be printed.

### Step 3:
Display the even numbers using loop.

### Step 4:
Stop the execution.

### Program:-
#### Developed By : Kirupanandhan T
#### Register Number : 212221230051
```java
import java.util.*;
public class EvenNumbers {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter start and stop value: ");
        int start=sc.nextInt();
        int end=sc.nextInt();
        System.out.print("Even numbers between "+start+" and "+end+" is ");
        for(int i=start+2;i<end;i+=2)
        {
            System.out.print(i+" ");
        }

    }
}
```
## Output:-
![image](https://github.com/Kirupanandhan/-Java-program-to-print-the-even-numbers-between-1-20/assets/94386222/0a8499a2-b1a3-476f-a65a-b21462b71103)
## Result:-
A java program to print the even numbers between 1-20 has been executed successfully.
