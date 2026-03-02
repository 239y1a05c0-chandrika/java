import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int k = sc.nextInt();
        while (k >= n) {
            k = k - n;
        }
        System.out.println(k);
        sc.close();
    }
}

