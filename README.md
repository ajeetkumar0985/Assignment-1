package main;
import java.util.Scanner;
public class Main {
 
    public static void main(String[] args) {
        String name;
        int Age;
        char bloodGroup;
        Scanner scanner=new Scanner(System.in);
        System.out.println("Enter your name:  ");
        name=scanner.nextLine();
        System.out.println("Enter your Age:  ");
        Age=scanner.nextInt();
        System.out.println("Enter your bloodGroup:  ");
        bloodGroup =scanner.next().charAt(0);


        System.out.println("Name  " + name);
        System.out.println("Age  " + Age);
        System.out.println("Bloodgroup  " + bloodGroup);


        String Student;
        if (Age>=20)  {
            Student = "Red";
        }
        else if (Age>=15)  {
            Student = "bule";
        }
        else {
            Student = "Yellow";
        }
        System.out.println("Your Group is  " + Student);
        
    }
    
}
