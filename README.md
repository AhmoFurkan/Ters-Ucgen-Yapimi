# Ters-Ucgen-Yapimi
Java ile basamak sayısının kullanıcıdan alınan ve döngüler kullanılarak, yıldızlar(*) ile ekrana ters üçgen çizen programı yazın.


    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Bir sayı giriniz :");
        int number = inp.nextInt();


        for (int i = 0; i <= number; i++) {
            for (int a = number; a >= (number - i); a--) {
                System.out.print(" ");
            }
            for (int h = 1; h <= (number - i) * 2 - 1; h++) {
                System.out.print("*");
            }


            System.out.println();
        }

      }
    }
 https://app.patika.dev/ahmetfurkan
 ![image](https://user-images.githubusercontent.com/107626332/182610636-ee7f4265-8a69-4515-8710-aae8817ad0e9.png)

    
    
    
    
    
    
