// This is my progress so far, I'm not finished with code

import java.util.Scanner;
import java.util.Arrays;
import java.util.Random;

public class Main {
    public static void welcome() {
        System.out.println("Welcome! This program allows you to choose a game to play");
        System.out.println("In this program, choose either a Guessing Game");
        System.out.println("Or play Rock-Paper-Scissors");
        System.out.println("Good Luck and Have Fun!");



    }


    public static void main(String[] args) {
        System.out.println("I'm thinking of a number between 1 and 50");
        System.out.println("Guess what it is. You have 5 tries: ");
        int input;
        Random random = new Random();
        randomArray();



    }

    public static int[] randomArray(int size) {
        int[] array = randomArray(1);
        System.out.println(Arrays.toString(array));
//        Scanner in = new Scanner(System.in);
//        input = in.nextInt();
        return array;
    }


    }

