# Recursive-ile-Fibonacci-Serisi-Bulan-Program
Java Recursive ile Fibonacci Serisi Bulan Program

www.patika.dev

public class Main {
    
    static int fib(int n) {
        if (n == 1 || n == 2) {
            return 1;
        }
        return fib(n-1) + fib(n-2);
    }
    public static void main(String[] args) {
        System.out.println(fib(6));
    }
}
