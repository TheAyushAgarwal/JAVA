```Java
import java.lang.*;
import java.util.*;

class Main{
    public static void main(String args[])
    {
        int a,b,c;
        float s;
        double area;
        System.out.println("enter three length of the tringle");
        
        Scanner sc= new Scanner(System.in);
        a=sc.nextInt();
        b=sc.nextInt();
        c=sc.nextInt();
        s=(a+b+c)/2f;
        area=Math.sqrt(s*(s-a)*(s-b)*(s-c));
        // here we are assigning f with 1/2 becasue if can't assign it with float it will give zero
        System.out.println("Area is--"+area);
    }
    
}

```
