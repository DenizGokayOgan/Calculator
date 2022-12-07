# Calculator
    import java.util.Scanner;
     public class Main {

    public static void main(String[] args) {
        double x, y;
        int secim;

        Scanner input = new Scanner(System.in);
        System.out.print("Birinci sayıyı giriniz : ");
        x = input.nextDouble();
        System.out.print("İkinci sayıyı giriniz : ");
        y = input.nextDouble();
        System.out.println("1-Toplama\n2-Çıkarma\n3-Çarpma\n4-Bölme");
        System.out.println("İşlemi seçiniz:");
        secim = input.nextInt();
        switch (secim) {
            case 1:
                System.out.println("Toplam: " + (x + y));
                break;
            case 2:
                System.out.println("Çıkarma: " + (x - y));
                break;
            case 3:
                System.out.println("Çarpma: " + (x * y));
                break;
            case 4:
                System.out.println("Bölme: " + (x / y));
                break;
            default:
                System.out.println("Seçtiğiniz işlem hatalı ");
        }
    }
}
