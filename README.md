# Assignment
public class MathUtils {

    public static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        // Example usage:
        int result = MathUtils.add(5, 7);
        System.out.println("The sum is: " + result);
    }
}
public class MathUtils {

    public static int subtract(int a, int b) {
        return a - b;
    }

    public static void main(String[] args) {
        // Example usage:
        int result = MathUtils.subtract(10, 3);
        System.out.println("The result of subtraction is: " + result);
    }
}
public class MathUtils {

    public static int multiply(int a, int b) {
        return a * b;
    }

    public static void main(String[] args) {
        // Example usage:
        int result = MathUtils.multiply(4, 6);
        System.out.println("The product is: " + result);
    }
}
public class MathUtils {

    public static double divide(int a, int b) {
        if (b == 0) {
            // Handle division by zero
            System.out.println("Error: Division by zero is not allowed.");
            return -1.0;
        } else {
            return (double) a / b;
        }
    }

    public static void main(String[] args) {
        // Example usage:
        double result1 = MathUtils.divide(8, 2);
        System.out.println("The result of division is: " + result1);

        double result2 = MathUtils.divide(5, 0);
        System.out.println("The result of division is: " + result2);
    }
}
