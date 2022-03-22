```JAVA
/ Meta character
// we can use regular expression for true and false
/* if we use \d-----> digits
            \D------> Not digits
            \s------> space
            \S------> Not space
            \w---> alphabets or digits
            \W--------> Neither alphabets or digits
           
*/
public class Main
{
  public static void main (String[]args)
  {
    String str1 = "f";
      System.out.println (str1.matches ("\\d"));
      // it will show true value as per starting statement
      System.out.println (str1.matches ("\\D"));
      // it will show true value as per starting statement
       System.out.println (str1.matches ("\\s"));
      // it will show true value as per starting statement
      System.out.println (str1.matches ("\\S"));
      // it will show true value as per starting statement
       System.out.println (str1.matches ("\\w"));
      // it will show true value as per starting statement
      System.out.println (str1.matches ("\\W"));
      // it will show true value as per starting statement
    }
}


```
 
