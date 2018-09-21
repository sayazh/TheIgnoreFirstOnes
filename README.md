# TheIgnoreFirstOnes
String exercise
package stringAssignments;

import java.util.Scanner;

public class evenNumberCharacters {
    public static void main(String[] args) {
		
    	Scanner scan = new Scanner(System.in);
    	System.out.print("Enter please any word");
    	String word = scan.next();
    	
        	
    	if (word.length()%2==0) {
    		System.out.println(word.substring(0, word.length()/2));
    	} else {
    		System.out.println("Word should has even number of characters");
    	}
    	scan.close();
	
}
}
