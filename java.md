package hi;
import java.util.scanner;
public class chai
{
public static void main(String[] args)
{
Scanner sc=new Scanner(System.in);
int a,b,min,max;
System.out.println("enter two numbers");
a=sc.nextInt();
b=sc.nextInt();
System.out.println("a="+a+"\tb="+b);
min=(a<b)?a:b;
max=(a>b)?a:b;
System.out.println("minimum="+min+"\nmaximum="+max);
}
}
