# Hava-Sicakligina-Gore-Etkinlik-Onerme

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int heat;
        Scanner input = new Scanner(System.in);
        System.out.println("Sıcaklık değerini giriniz");

        heat = input.nextInt();
        System.out.println("Sıcaklık: " + heat);
        if (heat<5){
            System.out.println("Kayak yapmalısınız!");
        }else if (heat>=5 && heat<15 ){
            System.out.println("Sinemaya Gitmelisiniz!");
        }else if (heat>=15 && heat<25){
            System.out.println("Pikniğe Gitmelisiniz!");
        }else {
            System.out.println("Yüzmeye Gitmelisiniz!");
        }

    }
}
