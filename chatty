package bot;

import java.util.Scanner;

public class SimpleBot {
    final static Scanner scanner = new Scanner(System.in); // Do not change this line

    public static void main(String[] args) {
        greet("Chattik", "2017"); 
        remindName();
        guessAge();
        count();
        test();
        end();
    }

    static void greet(String assistantName, String birthYear) {
        System.out.println("Hello! My name is " + assistantName + ".");
        System.out.println("I was created in " + birthYear + ".");
        System.out.println("Please, remind me your name.");
    }

    static void remindName() {
        String name = scanner.nextLine();
        System.out.println("What a great name you have, " + name + "!");
    }
static void guessAge() {
        System.out.println("Let me guess your age.");
        System.out.println("Enter remainders of dividing your age by 3, 5 and 7.");
        int rem3 = scanner.nextInt();
        int rem5 = scanner.nextInt();
        int rem7 = scanner.nextInt();
        int age = (rem3 * 70 + rem5 * 21 + rem7 * 15) % 105;
        System.out.println("Your age is " + age + "; that's a good time to start programming!");
    }

    static void count() {
        System.out.println("Now I will prove to you that I can count to any number you want.");
        int num = scanner.nextInt();
        for (int i = 0; i <= num; i++) {
            System.out.printf("%d!\n", i);
        }
    }

    static void test() {
        System.out.println("Let's test your programming knowledge.");
        
        int opt1 = 1; 
        int opt2 = 2;
        int opt3 = 3;
        System.out.println("Why do we use methods?");
        System.out.println(opt1 + ". To repeat a statement multiple times.");
        System.out.println(opt2 + ". To determine the execution time of a program.");
        System.out.println(opt3 + ". To decompose a program into several small subroutines.");
    }


    static void end() {
        int opt1 = 1; 
        int opt2 = 2;
        int opt3 = 3;
        while (true){
        int option = scanner.nextInt();
        if (option == opt3) {
            break;
            }
            System.out.println("Please, try again.");
        } 
        System.out.println("Congratulations, have a nice day!"); 
    }
}
