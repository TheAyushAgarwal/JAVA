```JAVA
// string Method
public class Main
{
	public static void main(String[] args) 
	
	{
	// 01) int length()    
	    String c="JAvA";
	   
	    int l= c.length();
	    System.out.println(l);
	// 02) string toLowerCase() 
	    String k= c.toLowerCase();
	    System.out.println(k);
	// 03) string toLowerCase()
	    String m=c.toUpperCase();
	    System.out.println(m);
	// 04) string trim()
	// trim string is used if array size is greater than number of string then it will reduced 
	// array size and make it as string size.
	    
	// 05) string substring(int begin)
	    String str="Welcome";
	    String sub=str.substring(3);
	    System.out.println(sub);
	    // here it will print from 3rd index to ending index
	// 06) string substring(int begin, int end)
	    String str1="Welcome";
	    String sub1=str1.substring(3,6);
	    System.out.println(sub1);
	    // here it will print from 3rd index to 6th index
	// 07) string replace(char old, char New)
	String str2="Welcome";
	    String sub2=str2.replace('W','k');
	    System.out.println(sub2);
	    // here we are replacing old letter with new letters
	// 08) boolean startsWith(String s)
	String str3="Welcome";
	    boolean sub3=str3.startsWith("W");
	    System.out.println(sub3);
	    // it will just show true or false nothing else
	// 09) boolean endsWith(String s)    
	   String str4="Welcome";
	    boolean sub4=str4.endsWith("e");
	    System.out.println(sub4);
	    // it will just show true or false nothing else.
	// 10) char charAt(int index)
	    String str5="Welcome";
	    char z=str5.charAt(3);
	    System.out.println(z);
	    // it will just print what kind of charcter it is stored in specified index
    // 11) int indexOf(string)
        String str6="Welcome";
	    int y= str6.indexOf("l");
	    System.out.println(y);
	    // it will just search the elements from begining if it is found then will print index value or 
	    // it will -1
	// 12) int LastIndexOf(String s)
	    String str7="Welcome";
	    int w= str7.lastIndexOf("e");
	    System.out.println(w);
	    // it will just search the elements from ending to begining if it is found then will print index value or 
	    // it will -1
	// 13) boolean equals(String s)
	    String str8="Welcome";
	    String str9="Welcome";
	    boolean v= str8.equals(str9);
	    System.out.println(v);
	    // two strings are exactly same then euals method shows us true otherwise false
	// 14) boolean equalsIgnoreCase(String s)
	    String strk="Welcome";
	    String strl="welcome";
	    boolean u= strk.equalsIgnoreCase(strl);
	    System.out.println(u);
	}
}
```
 
