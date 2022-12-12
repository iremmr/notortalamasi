# notortalamasi
```
import java.util.Scanner;



public class NotOrtalamasi {
    public static void main(String[] args){
        int mat,fzk,kimya,turkce,tarih,muzik;

        Scanner input = new Scanner(System.in);

        System.out.print("Matematik notunuz: ");
        mat = input.nextInt();

        System.out.print("Fizik notunuz: ");
        fzk = input.nextInt();

        System.out.print("Kimya notunuz: ");
        kimya = input.nextInt();

        System.out.print("Türkçe notunuz: ");
        turkce = input.nextInt();

        System.out.print("Tarih notunuz: ");
        tarih = input.nextInt();

        System.out.print("Müzik notunuz: ");
        muzik = input.nextInt();

        int toplam = (mat + fzk + kimya + turkce + tarih + muzik);
        double sonuc = (toplam / 6);
        System.out.println("Ortalamanız: " + sonuc);

        String durum =(sonuc>=60.0)?"Geçtiniz":"Kaldınız";
        System.out.println(durum);

    }
}
```
[Patika.dev](https://app.patika.dev/iremr)
