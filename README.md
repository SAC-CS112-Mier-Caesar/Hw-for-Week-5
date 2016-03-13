# Hw-for-Week-5

package test;

import java.util.Scanner;

public class Calculator {
	public static void main(String args[]){
		
		
		Scanner input = new Scanner(System.in);
		double fnum;
		double snum;
		double userChoice;
		double result;
		double tryAgain;
		
		do{
		System.out.println("Enter first number: ");
		fnum = input.nextDouble();
		System.out.println("Enter second number: ");
		snum = input.nextDouble();
		
		
		System.out.println("Enter 1 to add, 2 to Subtract, 3 to Multiply, or 4 to divide");
		userChoice = input.nextDouble();
		if (userChoice == 1)
			System.out.println(result = fnum + snum);
		if (userChoice == 2)
			System.out.println(result = fnum - snum);
		if (userChoice == 3)
			System.out.println(result = fnum * snum);
		if (userChoice == 4)
			System.out.println(result = fnum / snum);
				
		System.out.println("Try again? (1 = Yes, 0 = No) ");
		tryAgain = input.nextDouble();
		} while(tryAgain == 1);
	}

}
