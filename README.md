# TheIgnoreFirstOnes
String exercise
package stringAssignments;

import java.util.Scanner;

public class IgnoreTheFirstOnes {
   public static void main(String[] args) {
	
	   Scanner keyboard = new Scanner(System.in);
	   System.out.println("Enter first word ");
	    
	   String word1 = keyboard.next();
	   System.out.println("Enter second word");
	   String word2 = keyboard.next();
	   
	   System.out.println(word1.substring(1)+""+word2.substring(1));
	   keyboard.close();
	   
}
}
