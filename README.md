# paradigm
public class HelloWorld {
    public static void main(String[] args) {
        Greeter greeter = new Greeter();
        greeter.greet();
    }
}

class Greeter {
    public void greet() {
        System.out.println("Hello, world!");
    }
}
