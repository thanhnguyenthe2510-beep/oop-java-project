import java.util.Scanner;

public class Circle {
    // ===== Thuộc tính =====
    private double radius;

    // ===== Constructor mặc định (bán kính = 1) =====
    public Circle() {
        this.radius = 1;
    }

    // ===== Constructor có tham số =====
    public Circle(double radius) {
        this.radius = radius;
    }

    // ===== Getter & Setter =====
    public double getRadius() {
        return radius;
    }

    public void setRadius(double radius) {
        this.radius = radius;
    }

    // ===== Nhập bán kính từ bàn phím =====
    public void input() {
        Scanner sc = new Scanner(System.in);
        System.out.print("Nhap ban kinh r: ");
        this.radius = sc.nextDouble();
    }

    // ===== Xuất thông tin hình tròn =====
    public void output() {
        System.out.println("Ban kinh r: " + radius);
    }

    // ===== Tính diện tích =====
    public double getArea() {
        return Math.PI * radius * radius;
    }

    // ===== Tính chu vi =====
    public double getCircumference() {
        return 2 * Math.PI * radius;
    }

    // ===== Hàm main để kiểm tra =====
    public static void main(String[] args) {
        // 1. Tạo hình tròn bằng constructor mặc định
        Circle c = new Circle();
        System.out.println("Thong tin hinh tron mac dinh:");
        c.output();

        // 2. Nhập bán kính mới
        System.out.println("\nNhap hinh tron:");
        c.input();

        // 3. Xuất thông tin + tính toán
        System.out.println("\nThong tin hinh tron vua nhap:");
        c.output();
        System.out.println("Dien tich hinh tron: " + c.getArea());
        System.out.println("Chu vi hinh tron: " + c.getCircumference());
    }
}
