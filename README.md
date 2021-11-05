/**
 * JAVA 1 Homework2
 * 
 * @autor Oksana
 * @version 5.11.2021
 */
public class Homework2 {
        public static void main(String[] args) {
        System.out.println(doPoint1 (2, 11));
        doPoint2 (8);
        System.out.println(doPoint3 (-15));
        doPoint4 ("Hello", 5);
        System.out.println(doPoint5 (2020));
    }

    public static boolean doPoint1 (int a, int b) {
        int sum = a + b;
        if (sum >= 10 && sum <=20) {
            return true;
        }
        return false;
    }

    public static void doPoint2(int x) {
        if (x >= 0) {
            System.out.println("Positive");
        } else {
            System.out.println("Negative");
        }
    }

    public static boolean doPoint3(int x) {
        if (x >= 0) {
            return true;
        } else {
            return false;
        }
    }

    public static void doPoint4(String word, int times) {
        for (int i = 1; i <= times; i++) {
            System.out.println("[" + i + "]" + " " + word);
        }
    }

    public static boolean doPoint5(int year) {
        if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
            return true;
        } else {
            return false;
        }
    }
}
