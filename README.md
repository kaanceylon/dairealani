# dairealani
Dairenin Alanı Bulma Programı





import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
    int r;
    double pi = 3.14;



    Scanner input = new Scanner(System.in);
    System.out.print("r değerini giriniz : ");
    r = input.nextInt();

      double alan = pi * r * r;
      double cevre = 2 * pi * r;

      System.out.println("Dairenin alanını : " + alan );
      System.out.println(" Dairenin cevresi : " + cevre );
    }
}
