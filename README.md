# Problem-2.T2021-2-2

SingleIntegersInput.java

import java.util.Scanner;

public class SingleIntegersInput {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the value of x: ");
        int x = scanner.nextInt();

        System.out.print("Output: ");
        for (int i = 1; i <= x; i++) {
            int num = 2 * i - 1;
            if (i != x) {
                System.out.print(num + ", ");
            } else {
                System.out.print(num);
                
                scanner.close();
            }
        }
    }
}
