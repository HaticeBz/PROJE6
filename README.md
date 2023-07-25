import java.util.Scanner;
public class Main {
        public static void main(String[] args){
                Scanner input = new Scanner(System.in) ;
                double alan, kenar, taban, yukseklik;

                System.out.print("Taban uzunluğu :");
                taban = input.nextDouble() ;
                System.out.print("Kenar uzunluğu :");
                kenar = input.nextDouble() ;
                System.out.print("Yükseklik :");
                yukseklik = input.nextDouble() ;

                alan = ((taban * yukseklik) / 2);
                System.out.print("Alan : " + alan) ;

        }
}
