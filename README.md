package com.example;
import java.util.Scanner;
public class App {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter Basic Salary: ");
        double basicSalary = sc.nextDouble();
        double hra = basicSalary * 0.20; // 20% of basic salary
        double da = basicSalary * 0.10;  // 10% of basic salary
        double netSalary = basicSalary + hra + da;
        System.out.println("\nSalary Details");
        System.out.println("Basic Salary : " + basicSalary);
        System.out.println("HRA (20%)    : " + hra);
        System.out.println("DA (10%)     : " + da);
        System.out.println("Net Salary   : " + netSalary);
        sc.close();
    }
}
