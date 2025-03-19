package com.mycompany.task_5;
import java.util.Scanner;

public class series {  
      public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter number of terms (n) = ");
        int n = input.nextInt();
        int sum = 0;
        System.out.print("Series: ");
        for (int i = 1; i <= n; i++) {
            if (i % 2 == 0) {
                System.out.print("-" + i + " ");
                sum -= i;  
            } else {
                System.out.print(i + " ");
                sum += i; 
            }
        }
        System.out.println("\nSum of series: " + sum);        
    }
    }
