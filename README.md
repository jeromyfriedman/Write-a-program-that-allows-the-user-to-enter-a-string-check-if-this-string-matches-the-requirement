# Write-a-program-that-allows-the-user-to-enter-a-string-check-if-this-string-matches-the-requirement
Write a program that allows the user to enter a string, check if this string matches the requirements or not.
import java.util.Scanner;
public class BaiTapJavaCoBan20
{
    public static void main(String[] args)
    {
       String String;
       Scanner sc = new Scanner(System.in);

       System.out.println("Enter a string: ");
       string = sc.nextLine();

       if(chuoi.matches("^[A-Z][^\\s]{0.18}\\d$"))
          System.out.println("Browse");
       else
          System.out.println("Do not browse");
    }
}
