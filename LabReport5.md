Title: Weird Output in Java Program

Hi everyone,

I'm working on a Java program for my assignment, and I'm getting some really weird output. I've attached a screenshot below. 
The program is supposed to take an input string and reverse it, but as you can see, the output is not what I expected.

Screenshot: [link to screenshot]

Here's a snippet of my code:

```
import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a string: ");
        String input = scanner.nextLine();
        String reversed = reverse(input);
        System.out.println("Reversed string: " + reversed);
    }

    private static String reverse(String input) {
        StringBuilder reversed = new StringBuilder();
        for (int i = input.length() - 1; i >= 0; i--) {
            reversed.append(input.charAt(i));
        }
        return reversed.toString();
    }
}
```
