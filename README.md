import java.util.Scanner;
class QuadraticEquation{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the value of a: ");
        double a = sc.nextDouble();
        System.out.print("Enter the value of b: ");
        double b = sc.nextDouble();
        System.out.print("Enter the value of c: ");
        double c = sc.nextDouble();
        double d =b*b-4*a*c;
        if (d > 0)
        {
            double root1 = (-b + Math.sqrt(d)) / (2*a);
        }
        else if (d < 0)
        {
            double root2 = (-b - Math.sqrt(d)) / (2*a);
        }
        else if (d == 0)
        {
            double root1 = -b / (2*a);
        }
    }
}
