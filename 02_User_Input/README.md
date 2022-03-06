```Java
import java.lang.*;
import java.util.*;
// util package is packedge which stores all data of class Scanner, it is a build in package in java
// java provide a class called Scanner that is used for reading data from diffrent sources 
class Main
{
    public static void main(String args[])
    {
        Scanner s= new Scanner(System.in);
        // here the scanner "s", s is accessing all the data form scanner class  
        // here 'System.in' means, At first we know that System is class because it's first letter is captail , here 'System.in' means it is storing some data
        System.out.println("Enter any value");
        int a,b,c;
        //here a,b,c is a integer type variable
        a=s.nextInt();
        // here "s.nextInt" is showing that we are taling integer type value from the user
        b=s.nextInt();
        c=a+b;
        // storing the adition of a and b
        System.out.println("Sum is---"+c);
    }
}
/* we have diifrent types of class scanner
nextInt()- it will store integer type value(0,1,2....)
nextFloat()- it will store floating type value(0.1,00.1,....)
next()- it will read string/word, only single word.
nextLine()-it will read a paragraph
hasNextInt()-if we want to cheak the value we are getting is an intger or not, then this type scanner
is used, True/False
hasNestFloat()-if we want to cheak the value we are getting is an Float or not, then this type scanner
is used, True/False
nextByte(),nextSort(),nextDouble(),nextLong(),nextBoolean()
*/
```
