```Java
import java.lang.*;
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    int a,b,c, Area,volume;
	   
		Scanner s=new Scanner(System.in);
		System.out.println("please enter the value for length, breath and height");
		a=s.nextInt();
		b=s.nextInt();
		c=s.nextInt();
	    Area=2(a*b+b*c+c*a);
	    volume=a*b*c;
		
		System.out.println("area and volume-"+Area+" "+volume);
		}
}
```
