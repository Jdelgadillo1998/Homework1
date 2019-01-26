# Homework1
My first assignment!


import java.util.Scanner;

import java.lang.Math;    //Used to run the square root method

public class Calculator {

	//Global variables
	 int a;
	 int b;
	static int num = 7;
	double x,r;
	static double d;
	static double p = -16;
	static double q;
	static double z;

	public Calculator() {

	} 

        // Class to add
	public int add(int a, int b) {
		return a + b;
	}
	 // Class to subtract
	public int subtract(int a, int b) {
		return a - b;
	}
	 // Class to multiply
	public int multiply(int a, int b) {
		return a * b;
	}
	 // Class to divide
	public int divide(int a, int b) {
		return a/b;
	}
	 // Class to find square root
	public double squarerootNumber(double x){


		System.out.println(Math.sqrt(x));
		return x;


	}
	 // Class to find Factorial
	public static double factorialNumber(double n){

		int res = 1, i; 
		for (i=2; i<=n; i++) 
			res *= i; 
		return res; 
	} 
	
	public static void power(double q, double z)
	{
	 q = 4; 
     z = 6;  

		}
	
	public static void abs(double p)
	{
		p = -16;
	}
	
	public double floor(double r){


		 r = Math.floor(8.7);
		
		return r;

	}
	
	public double round(double d){


		 d = Math.round(3.7);
		
		return d;
	}

	 // Class to run the program
	public static void main(String[] args) {
		Calculator myCalculator = new Calculator();
		System.out.println(myCalculator.add(5,7));
		System.out.println(myCalculator.subtract(45,11));
		System.out.println(myCalculator.multiply(3,6));
		System.out.println(myCalculator.divide(6,2));
		System.out.println(myCalculator.squarerootNumber(7)); 
		System.out.println("Factorial of "+ num + " is " + factorialNumber(7)); 
		System.out.println(Math.pow(4, 6)); 
		System.out.println("Math.abs(" + p + ")=" + Math.abs(p));
		System.out.println(myCalculator.floor(8.7));
		 System.out.println(myCalculator.round(d));
	}
}
