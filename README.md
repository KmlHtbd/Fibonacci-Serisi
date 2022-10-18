# Fibonacci-Serisi
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class fibonacci {
    public static void main(String[] args) {
        int i, n;
        int num1 = 0, num2 = 1;
        int counter = 0;

        Scanner input = new Scanner(System.in);
        System.out.print("Fibonacci Serisinin basamak sayısını giriniz: ");
        n = input.nextInt();
        
        while (counter <n) {
            System.out.print(num1 + " ");
            int num3 = num2 + num1;
            num1 = num2;
            num2 = num3;
            counter = counter + 1;
        }
    }
}
```
