import java.util.Scanner;

public class App {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    
        String name = "sofea"; 
        System.out.println("HELLO " + name.toUpperCase());

            Scanner scan = new Scanner (System.in) ; 
            System.out.println(" whats your age?");
            String age  = scan.nextLine();
            System.out.println(age + "!" + "thats wonderful");
            scan.close(); 

        }
