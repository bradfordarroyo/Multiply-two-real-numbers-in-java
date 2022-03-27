# Multiply-two-real-numbers-in-java
Multiply two real numbers in java
import java.util.Scanner;
 
public class NhanHaiSo {
 
    public static void main(String[] args) {
 
        /* yêu cầu người dùng nhập từ bàn phím vào số thứ nhất và số thứ hai
         */
        Scanner scan = new Scanner(System.in);
        System.out.print("nhập vào số thứ nhất: ");
 
        double num1 = scan.nextDouble();
 
        System.out.print("Nhập vào số thứ hai:  ");
        double num2 = scan.nextDouble();
 
        // Thực hiện tính tích của hai số.
        double tich = num1*num2;
 
        // hiển thị kết quả ra màn hình
        System.out.println("Kết quả: "+tich);
    }
}
