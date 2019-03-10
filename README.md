/* # average-of-three
application that reads three integers from user and prints their average.
*/

import java.util.Scanner;
public class Orange {

	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in);
		
		int num1, num2, num3, average;
		
		System.out.println("Enter first number:");
		num1 = scan.nextInt();
		System.out.println("Enter second number:");
		num2 = scan.nextInt();
		System.out.println("Enter third number:");
		num3 = scan.nextInt();
		
		average = (num1 + num2 + num3)/3;
		
		System.out.println("Your numbers are: " + num1 + " " + num2 + " " + num3);
		System.out.println("Average is: "  + average);
		

	}

}
