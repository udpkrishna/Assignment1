package basic;

import java.util.Scanner;

public class Assignment1 {

	public static void main(String[] args) {

		// Input the age from User
		System.out.print("Enter the age:");
		Scanner inp = new Scanner(System.in);
		int age = inp.nextInt();

		// Age check condition
		if (age >= 18) {
			System.out.println("Eligible to Vote");
		} else if (age < 18) {
			System.out.println("Not eligible to Vote");
		}
	}

}
