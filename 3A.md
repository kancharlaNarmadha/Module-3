
# EX 3A String and its operations in java
## DATE:
## AIM:
To create a string then print particular string using substring() with given end index value. (0-7) , (0-5) ,(3-5)






## Algorithm

1.Create a class named prog and define the main() method to execute the program.

2.Use a Scanner object to read a full line of text input from the user.

3.Store the input in a String variable a using in.nextLine().

4.Use the substring() method to extract specific portions of the string and display them.

5.Print the extracted substrings using System.out.println().







## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;
class prog
{
    public static void main(String[] args){
        Scanner in=new Scanner(System.in);
        String a =in.nextLine();
        System.out.println(a.substring(0,7));
        System.out.println(a.substring(0,5));
        System.out.println(a.substring(3,5));
        
    }
}
    
```

## Output:
![image](https://github.com/user-attachments/assets/0bd5f653-968b-4b03-a45d-8ccb857e2b42)


## Result:
The program successfully accepts a string input from the user and demonstrates the use of the substring() method by printing specific portions of the string based on index positions.






