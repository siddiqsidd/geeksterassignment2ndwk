# geeksterassignment2ndwk
package feb4;
import java.util.*;
public class reverseThree {
	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		System.out.println("enter a 3 digit number");
		String input=s.nextLine();
		String temp="";
		for(int i=input.length()-1;i>=0;i--) {
			temp=temp+input.charAt(i);
		}
		System.out.println("reverse string is : ");
		System.out.println(temp);
	}

}
