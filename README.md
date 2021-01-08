# java-programm-to-calculate-persentage

# the code
package com.company;
import java.lang.*;
import java.util.*;
class Main
{
    public static void main(String[]args)
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter English number - ");
        int a = sc.nextInt();
        System.out.print("Enter Hindi number - ");
        int b = sc.nextInt();
        System.out.print("Enter maths number - ");
        int c = sc.nextInt();
        System.out.print("Enter Science number - ");
        int d = sc.nextInt();
        System.out.print("Enter social number - ");
        int e = sc.nextInt();
        int f = a+b+c+d+e;
        System.out.println("Your total is = " +f);
        int g = f*100;
        int i = g/500;
        System.out.println("Your Persent is = " +i);
    }
}
