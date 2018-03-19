# Simple-Calculator
package com.example.simplecalculator;

import java.util.Scanner;


public class Calculator {

   public static void addition(){

        double n1, n2;
        Scanner kb = new Scanner(System.in);

        System.out.println("Addition");

        System.out.print("\nFirst Number: ");
        n1 = kb.nextDouble();

        System.out.print("\nSecond Number: ");
        n2 = kb.nextDouble();

        kb.close();
        System.out.println("\nSum: " + n1 + " + " + n2 + " = " + (n1 + n2));
    }

    public static void subtraction(){
    	double n1, n2;
        Scanner kb = new Scanner(System.in);

        System.out.println("Subtraction");

        System.out.print("\nFirst Number: ");
        n1 = kb.nextDouble();

        System.out.print("\nSecond Number: ");
        n2 = kb.nextDouble();

        kb.close();
        System.out.println("\nSum: " + n1 + " - " + n2 + " = " + (n1 - n2));
    }

    public static void division(){
    	Double n1, n2;
        Scanner kb = new Scanner(System.in);

        System.out.println("Division");

        System.out.print("\nFirst Number: ");
        n1 = kb.nextDouble();

        System.out.print("\nSecond Number: ");
        n2 = kb.nextDouble();

        kb.close();
        System.out.println("\nSum: " + n1 + " / " + n2 + " = " + (n1 / n2));
    }

    public static void multiplication(){
    	double n1, n2;
        Scanner kb = new Scanner(System.in);

        System.out.println("Multiplication");

        System.out.print("\nFirst Number: ");
        n1 = kb.nextDouble();

        System.out.print("\nSecond Number: ");
        n2 = kb.nextDouble();

        kb.close();
        System.out.println("\nSum: " + n1 + " x " + n2 + " = " + (n1 * n2));
    }
    public static void main(String[] args) {

        Scanner kb = new Scanner(System.in);

        System.out.println("Simple Calculator");

        System.out.println("\nHere are your options:");
        System.out.println("\n1. Addition");
        System.out.println("2. Subtraction");
        System.out.println("3. Division");
        System.out.println("4. Multiplication");

        System.out.print("\nWhat would you like to do?: ");
        Double choice = kb.nextDouble();
        System.out.println();


        if (choice == 1){
            addition();
        }
        else if (choice == 2){
            subtraction();
        }
        else if (choice == 3){
            division();
        }
        else if (choice == 4){
            multiplication();
        }

        System.out.println();
        kb.close();
    }
}
