```Java
import java.lang.*;
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	  int x=5,y;
	  y=x++;
	  System.out.println(+y+" "+x);
	  // here we are first assiging the value of x into y then we are incrementing the value of x;
	  //when we print value of x and y x shows the value 6 and y shows the value 5
	  x=5;
	  y=++x;
	  System.out.println(+y+" "+x);
	  // and here we are first incrementing the value of x then we are assiging the value of x into y 
	  // that is why  y shows us same value as x
		}
}
// In boolean type of varible you can't perform increment and decrement.

```
