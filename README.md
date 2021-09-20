import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        //1
        Scanner sc = new Scanner(System.in);
        int size;

        //2
        System.out.println("Enter the size of the matrix :");
        size = sc.nextInt();

        //3
        for (int i = 0; i < size; i++) {
            //4
            for (int j = 0; j < size; j++) {
                //5
                if (i == j) {
                    System.out.print("8 ");
                } else {
                    System.out.print("8
 ");
                }
            }
            //6
            System.out.println();
        }

    }

}
