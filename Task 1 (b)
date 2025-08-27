import java.util.Scanner;

class Calculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("----- Simple Calculator -----");

        System.out.print("Enter first number: ");
        double num1 = sc.nextDouble();

        System.out.print("Enter operator (+, -, *, /): ");
        char op = sc.next().charAt(0);

        System.out.print("Enter second number: ");
        double num2 = sc.nextDouble();

        double result = 0;

        if (op == '+') {
            result = num1 + num2;
        } else if (op == '-') {
            result = num1 - num2;
        } else if (op == '*') {
            result = num1 * num2;
        } else if (op == '/') {
            if (num2 != 0) {
                result = num1 / num2;
            } else {
                System.out.println("Error: Division by zero!");
                sc.close();
                return;
            }
        } else {
            System.out.println("Invalid Operator!");
            sc.close();
            return;
        }

        System.out.println("Result: " + result);

        sc.close();
    }
}
