
import java.util.Scanner;
public class Minutes{
 public static void main(String[] args) {
 Scanner sc = new Scanner(System.in);
 System.out.println("Enter the number of minutes=");
  double min = sc.nextDouble();
  long years = (long) (min / (60*24*365));
  long days = (long) (min / 60 / 24) % 365;
    System.out.println( min + "  is approx " + years + " years and " + days + " days"); 
    }
}
