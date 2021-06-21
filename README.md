

package UC1_Calculate_line_length;

import java.util.Scanner;

public class Length_line {
	
	public static double Coordinate_length() {
		
		double x1, x2, y1, y2;
		Scanner sc = new Scanner (System.in);
		System.out.print("Enter your x1 = ");
		x1 = sc.nextInt();
		System.out.print("Enter your x2 = ");
		x2 = sc.nextInt();
		System.out.print("Enter your y1 = ");
		y1 = sc.nextInt();
		System.out.print("Enter your y2 = ");
		y2 = sc.nextInt();
		
		double A = x2 - x1;
		double B = y2 - y1;
		double C = X*X + Y*Y;
		double Length = Math.sqrt(C);
		return Math.floor(Length);
	
	}

	public static void main(String[] args) {
		
		System.out.println("Length of line from given co-ordinates "+Coordinate_length());
	}

}
