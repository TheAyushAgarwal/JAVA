```Java
//LITERALS--literals are constant value that are used in program
// Decimal-- 0,1,2,3,4,5,6,7,8,9
// Binary-- 0,1
// octal-- 0,1,2,3,4,5,6,7
//Hexadecimal-- 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F
// BYTE- int
// short-int
// int- int
// long- L or L
// float- F or f 
// double- D or D
// char- ''
// boolean- true/false
import java.lang.*;
class Main
{
    public static void main (String[] args) {
        byte b=15;
        short a=15;
        int c=15;
        // these three data types allows integers literals 
        
        long l=999999999999;
        //when we are printing l its showing integer number is too large
        long l=999999999999L;
        // after putting L at its end it is converted into form int 
        // to long Now compiler can accept it  
        
        // accpording to rule of literals you can't asssign any other literals with diffrent data types
        
        float f=12.56;
        // here 12.56 is a double we can't assign it with float data type
        // for assigning it with float data types we have to amke it float 
        // for making float we have to assign it with f at the end of 12.56
        float f=12.56f;
        // now it converted into float now we can print it 
        
        
        
        // if any number in Java is shown as big figure we can assign it like 
        // example
        long=999_9999_999;
        // we can use underscore for seeing it comfortabally, it can traeted as 999999999
        // we can use it for diffrent data types also 
        // one exception- we can't assign underscore before and after the numbers it should be between 
        // the numbers, we can't assign underscore before and after in float point (eg- 12_._06 not allowed)
        System.out.println(b);
    }
}
```
