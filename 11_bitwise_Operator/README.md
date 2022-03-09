```Java
//Bitwise Operator
//Note- bitwsie Operator perform on only integer type data type

public class Main
{
	public static void main(String[] args) {
	    
	    int x=10,y=6,z;
	    z=x&y;
	    // x&y means it is doing and operation of logic gates
	    // it is calculating z value by x and y bits value by its and operation of bits
	    /* x=10 - 00001010
	       y=6  - 00000110
	       ---------------
	       z=2    00000010=2 
	       then its answer will be 2*/
	       
	    z=x|y;
	    // x|y means it is doing or operation of logic gates
	    // it is calculating z value by x and y bits value by its or operation of bits
	    /* x=10 - 00001010
	       y=6  - 00000110
	       ---------------
	       z=14    00001110=14
	       then its answer will be 14*/
	    z=x^y;
	    /*x^y means it is doing Xor operation of logic gates
	    // it is calculating z value by x and y bits value by its Xor operation of bits
	       x=10 - 00001010
	       y=6  - 00000110
	       ---------------
	       z=12    00001100=12
	       then its answer will be 12*/
	    z=x<<1;
	    /* its means we shifting left our no of places those bits, here we shiting our bits by one places
	        x=10  00001010
	              ///////
	             00010100
	        ------------------
	        z=20 */
	    z=x>>1;
	    /* its means we shifting right our no of places those bits, here we are shiting right our bits by one places
	        x=10  00001010
	               \\\\\\\
	               00000101
	        ------------------
	        z=5 */
	    
	       
	    
		System.out.println(z);
	}
}
```
