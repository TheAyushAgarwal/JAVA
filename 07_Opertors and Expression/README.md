```Java
//operaton and Expression
/* 1. Increment/Decrement
     ---------------------
     post++,post--,++pre,--pre
   2. Arthamatic
     ------------
     *,/,%- first priority
     +,- second priority
     
     note- we can change priority with one another by using ()
   3. Bitwise
     ---------
     &,|,^,<<,>>,>>>
   4. Relational
     ------------
     <,<=,>,>=,==,!=
   5. Logical
     ---------
    &&,||,!
    --------------------------------------------------------------------------
    
    note-
    we can add
    byte+byte    
    short+short
    byte+short
    int+int
    short+int
    
    from all this ddition we get integer thats why we can store into int type varible
    
    this process is known as CloneNotSupportedException
    
    */
import java.lang.*;
class Main
{
    public static void main (String[] args) {
        byte b=10;
        short s= 14;
        int i=7;
        long l=50l;
        float f=12.5f;
        double d= 14.3d;
        char c= 65;
        int x;
        float y;
        double z;
        
        x=b+s;
        System.out.println(x);
        // here two number one is byte type another is short type, we are storing it into a integer type data type
        x=s+i;
        System.out.println(x);
        //here two number one is int type another is short type, we are storing it into a integer type data type
        y=i+f;
        System.out.println(y);
        // here first number is float and second is integer, we are storing it into a float because after addition
        // it will give us floating value and it can't be store into a integer
        y=l+f;
        System.out.println(y);
        // here first number is long and second is float, we are storing it into a float because after addition
        // it will give us floating value and it can't be store into a long
        x=c+s;
        System.out.println(x);
        // here first number is chracter and second is short, we are storing it into a interger because after addition
        // it will give us interger value and it can't be store into a charcter
        x=c+i;
        System.out.println(x);
        z=f+d;
        System.out.println(z);
        z=l+d;
        System.out.println(z);
    
        
    }
}
```
