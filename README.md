# Taksimetre Programı
Java ile gidilen mesafeye (KM) göre taksimetre tutarını ekrana yazdıran programı yazın.
* Taksimetre KM başına 2.20 TL tutmaktadır.
* Minimum ödenecek tutar 20 TL'dir. 20 TL altındaki ücrtlerde yine 20 TL alınacaktır.
* Taksimetre açılış ücreti 10 TL'dir.
```
import java.util.Scanner;

public class taxiMeter {
    public static void main(String[] args) {
        double total = 10 , km , perKm=2.2;
        Scanner input = new Scanner(System.in);
        System.out.print("Mesafeyi KM Cinsinden Giriniz : ");
        km = input.nextDouble();
        total += (km * perKm);

        total = (total < 20) ? 20 : total ;
        System.out.print("Toplam Tutar : " + total);
    }
}

```
# Patika Profilim :
***
<a href="https://app.patika.dev/krblttrkn">Patika Linkim</a>