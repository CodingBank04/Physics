import java.util.Scanner;
public class PrintStarCrossV2 {
    public static void main(String[] args) {
        Scanner read= new Scanner(System.in);
        System.out.println("What size square you want?");

        int a = read.nextInt();
        int x = 1;
        int y = 1;

        for (int i = 0; i <= a; i++) {
            for (int j = 0; j <= a; j++) {
                if (i == 0 || j == 0 || i == a || j == a) {
                    System.out.print("x ");
                } else if (j == a - y && i == y) {
                    System.out.print("x ");
                    y++;
                    if (a % 2 == 0 && x == a / 2) {
                        x++;
                    }

                } else if (i == x && j == x) {
                    System.out.print("x ");
                    x++;
                } else {
                    System.out.print("  ");
                }

            }
            System.out.println();
        }

    }
}
