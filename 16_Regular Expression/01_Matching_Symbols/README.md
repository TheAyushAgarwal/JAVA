```JAVA
// Maching Symbols
// we can use regular expression for true and false
/* if we use .(dot)----> any Character
            [abc]------> exactly given letters
            [abc][vz]--> either first or second set
            [^abc]-----> except abc
            [a-z1-7]---> a-z or a-z1-7
            A|b--------> A or B
            xz---------> Exactly XZ
*/
public class Main
{
  public static void main (String[]args)
  {
    String str1 = "f";
      System.out.println (str1.matches ("."));
    // here . means it will searching any element as per statement of "." ,then it will show true or false
      System.out.println (str1.matches ("[abc]"));
    // here it will give us false because it will searching one pattern like "abc" in str1
    System.out.println(str1.matches("[^abc]"));
    // here [^abc] it will just complement for upper statement.
    System.out.println(str1.matches("[a-z0-9]"));
    // here it will search a-z and 0-9, note*=we can use one of these either number or Character
    System.out.println(str1.matches("[a-z][0-9]"));
    // it is the complement of upper statement we can use both, numbers and alphabets
    System.out.println(str1.matches("A|B"));
    // it will give true for only if we will choose A or B, any one from both
    System.out.println(str1.matches("xy"));
    // it will print true if string is exactly equal to xy
    }
}
```
 
