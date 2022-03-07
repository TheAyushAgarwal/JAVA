```Java
import java.lang.*;
import java.util.*;

class Main{
    public static void main(String args[])
    {
        float base, height, area;
        System.out.println("enter the base and height value");
        
        Scanner sc= new Scanner(System.in);
        base=sc.nextFloat();
        height=sc.nextFloat();
        area=1f/2f*(base*height);
        // here we are assigning f with 1/2 becasue if can't assign it with float it will give zero
        System.out.println("Area is--"+area);
    }
    
}

```
