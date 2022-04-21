# cin-zodyagi-hesaplama
Java101_14 Kullanıcıdan doğum tarihini alıp Çin Zodyağı değerini hesaplayan program

https://www.patika.dev/tr

/*Ödev - Çin Zodyağı Hesaplama
Java ile kullanıcıdan doğum tarihini alıp Çin Zodyağı değerini hesaplayan program yazınız.

Çin Zodyağı nedir?

4000 bin yıldır kullanılan bir astroloji çeşididir Çin astrolojisi ve insanları 12 değişik burç ve sembollerle tanımlar. Çin Zodyağı bu 12 burcun eşit aralıklarla
(10 derece genişliğinde) sıralandığı bir hayvan halkasıdır ve yıldızlarla pek bir ilgisi yoktur.

Çin Zodyağı nasıl hesaplanır?

Çin zodyağı hesaplanırken kişinin doğum yılının 12 ile bölümünde kalana göre bulunur.


import java.util.Scanner;
public class Main{
    public static void main (String[] args) {
        
        int yil;
        
        Scanner input=new Scanner(System.in);
        System.out.println("Doğum Yılınız : ");
        yil=input.nextInt();
        
        if (yil%12==0){
            System.out.println("Çin Zodyağı Burcunuz : Maymun");
        }
        else if (yil%12==1){
            System.out.println("Çin Zodyağı Burcunuz : Horoz");
        }
        else if (yil%12==2){
            System.out.println("Çin Zodyağı Burcunuz : Köpek");
        }
        else if (yil%12==3){
            System.out.println("Çin Zodyağı Burcunuz : Domuz");
        }
        else if (yil%12==4){
            System.out.println("Çin Zodyağı Burcunuz : Fare");
        }
        else if (yil%12==5){
            System.out.println("Çin Zodyağı Burcunuz : Öküz");
        }
        else if (yil%12==6){
            System.out.println("Çin Zodyağı Burcunuz : Kaplan");
        }
        else if (yil%12==7){
            System.out.println("Çin Zodyağı Burcunuz : Tavşan");
        }
        else if (yil%12==8){
            System.out.println("Çin Zodyağı Burcunuz : Ejderha");
        }
        else if (yil%12==9){
            System.out.println("Çin Zodyağı Burcunuz : Yılan");
        }
        else if (yil%12==10){
            System.out.println("Çin Zodyağı Burcunuz : At");
        }
        else if (yil%12==11){
            System.out.println("Çin Zodyağı Burcunuz : Koyun");
        }
        
    }
    
}
