```Java
import java.lang.*;
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    int a,b,c;
	    double r1,r2;
		Scanner s=new Scanner(System.in);
		System.out.println("please enter the value for a,b,c");
		a=s.nextInt();
		b=s.nextInt();
		c=s.nextInt();
		r1=(-b+Math.sqrt(b*b-4*a*c))/(2*a);
		r2=(-b-Math.sqrt(b*b-4*a*c))/(2*a);
		
		System.out.println("roots of your quarditic equation are--"+r1+" "+r2);
		}
}

```
