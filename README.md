## Ex-3
## Java program to find the number of days in a month
### Aim:
To write a java program to find the number of days in a month

### Procedure:
* Import required packages.
* Declare main method with the signature "public static void main(String[] args)".
* Get the month input from user.
* Use switch method to find the number of days for the given month input.
* Display the output.

### Code:
```
import java.util.Scanner;
public class Ex3
{
    public static void main(String[] args)
    {
        Scanner in = new Scanner(System.in);
        System.out.println("Enter a month: ");
        String str = in.nextLine();
        System.out.println("The number of days in "+str+": ");
        switch(str)
        {
            case "January":
                System.out.print("31");
                break;
            case "February":
                System.out.print("28");
                break;
            case "March":
                System.out.print("31");
                break;
            case "April":
                System.out.print("30");
                break;
            case "May":
                System.out.print("31");
                break;
            case "June":
                System.out.print("30");
                break;
            case "July":
                System.out.print("31");
                break;
            case "August":
                System.out.print("31");
                break;
            case "September":
                System.out.print("30");
                break;
            case "October":
                System.out.print("31");
                break;
            case "November":
                System.out.print("30");
                break;
            case "December":
                System.out.print("31");
                break;
        }
    }
}
```
### Output:
<img width="185" alt="image" src="https://github.com/KeerthikaNagarajan/Java-Ex-3/assets/93427089/08980265-5b72-4334-b264-5cbd7f193ca1">

### Result:
To write a java program to find the number of days in a month was successfully done.

