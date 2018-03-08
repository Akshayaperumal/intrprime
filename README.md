# intrprime
import java.util.*;
public class intrprime
{
public static void main(String args[])
{
int a,b;
int count=0;
Scanner s=new Scanner(System.in);
a=s.nextInt();
b=s.nextInt();
for(int i=1;i<=a;i++)
{
 for(int j=2;j<i;j++)
 {
 if(i%j==0)
 {
 count++;
 }
 else
 {
 count=0;
 }
 }
 if(count>1)
 {
 System.out.println(i);
 }
}
}

}
