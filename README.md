import java.util.Scanner;

public class Main1 {
    public static void main() {

    
    //Java ile yarı çapını kullanıcıdan aldığınız dairenin alanını ve çevresini hesaplayan programı yazın.

              //  Alan Formülü : π * r * r;

        //Çevre Formülü : 2 * π * r;

        double r,cevre,alan;
        double pi=3.14;
        
        Scanner input = new Scanner(System.in);
        System.out.println("yarıçap giriniz: ");
        r=input.nextDouble();
        
        cevre=2*r*pi;
        alan=pi*r*r;
        
        System.out.println("cevre: "+cevre);
        System.out.println("alan: "+alan);

    }
}
