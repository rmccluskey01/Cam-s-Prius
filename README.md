package com.company;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner keyboard = new Scanner(System.in);
        System.out.printf("Enter a colour: ");
        String colour = keyboard.nextLine();
        System.out.printf("The %s fox jumped through the %s. He was %n",colour,"valley");
        System.out.printf("travelling at %d kph.",50);
    }
}
