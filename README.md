package hi;
import java.util.Scanner;
public class chai
{
public static void main(String[] args)
{
Scanner sc=new Scanner(System.in);
int age;
System.out.println("enter your age");
age=sc.nextInt();
System.out.println("entered age="+age);
if(age>=18)
{
System.out.println("congo");
System.out.println("you are eligible to vote");
}
System.out.println("thank you");
}
}
