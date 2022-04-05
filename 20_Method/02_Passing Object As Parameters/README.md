```JAVA
//Methods

public class Main
{
    // at first we have to assign any methods inside class
    // here we are using static before int, reason is that in main function we defind static before main,
    // that's why we can call those function which is also static that's why we used static.
    static int max(int x,int y)
    {
        if(x>y)
        {
            return x;
        }
        else
            return y;
    }
	public static void main(String[] args) {
	    int a=10, b=15,c;
	    // here we are  calling the function to excutes our code
	    c=max(a,b);
		System.out.println(c);
	}
}

// if we don't want to create our function max static, then we can use objects
/* public static void main(String[] args) {
	    int a=10, b=15,c;
	    Method mp= new method();
	    // here we created one object name as mp
		System.out.println(mp.max(a,b);*/
```
 
