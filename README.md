# taksimetre
package patika;
import java.util.Scanner;

public class taksimetre {

	public static void main(String[] args) {
		int km;
		double perKm , total , startPrice = 10;
		Scanner input = new Scanner(System.in);
		System.out.println("Kilometreyi giriniz:");
		km = input.nextInt();
		perKm = 2.20;
		total = (km*perKm) + startPrice ;
		total  = (total < 20) ? 20 : total ;
		System.out.println("Toplam tutar: " + total);
		
		

	}

}
