# Test-Files
Program Answers
package JavaTest;
import java.util.*;
public class Program2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the range");
		int num = sc.nextInt();
       for (int i=1;i<=2*num;i++) {
    	   if(i%2!=0)
    	   System.out.println("the numbers are"+" "+i);
    	   i=i+1;
       }
	}

}
