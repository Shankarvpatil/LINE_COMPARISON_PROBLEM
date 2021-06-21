package UC3_Using_java_compareTo_method;

import UC1_Calculate_line_length.Length_line;

public class CompareTwoLength extends Length_line {
	

	public static void main(String[] args) {
		
		double length1, length2 ;
		System.out.println("Enter 1st line coordinate ");
		length1 = Coordinate_length();
		System.out.println("Enter 2nd line coordinate ");
		length2 = Coordinate_length();
		
		String len1 = length1+" ";
		String len2 = length2+" ";
		int ch = (len1.CompareTwoLength(len2));
		System.out.println(len2+" "+len1);
		
		if ( ch < 0 ) {
			System.out.println(" length2 is greater than length1 by margin of  "+ch);
		}
		
		else if ( ch > 0 ) {
			System.out.println(" length1 is greater than length2 by margin of  "+ch);
		}
		
		else {
			System.out.println(" length1 is equal to  length2 ");
		}
		
	}

}
