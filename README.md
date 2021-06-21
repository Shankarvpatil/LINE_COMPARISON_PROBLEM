package UC2_Check_equality_between_line;

import UC1_Calculate_Length_of_line.Length_line;

public class Equality extends Length_line {
	
	public static void main(String[] args) {
		
		double length1, length2 ;
		System.out.println("Enter your 1st line coordinate ");
		length1 = Coordinate_length();
		System.out.println("Enter your 2nd line coordinate ");
		length2 = Coordinate_length();
		
		String len1 = length1+" ";
		String len2 = length2+" ";
		System.out.println("Two lines are equal "+len2.equals(len1));
		
	}

}
