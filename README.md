# Currency-Conversion-Calculator

    import java.util.Scanner;

     public class Main {
      public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("$--Currency Converter--₹");
        System.out.println();
        System.out.print("Enter the Amount of Money that needs to be converted into INR :$");
        double amount = scanner.nextDouble();

        double inr = usrToInr (amount);

        System.out.printf("According to the current conversion rates , The Amount comes down to :%.1f" , inr);

        scanner.close();
    }static double usrToInr (double amount) {
        return amount * 93.09 ;
    }
    }
