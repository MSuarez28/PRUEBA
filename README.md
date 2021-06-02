
import java.util.Scanner;

public class JavaApplication {

    public static void main(String[] args) {
Scanner var=new Scanner(System.in);
double num1,cm;
        System.out.println("Ingrese el  numero de pulgadas:");
        num1=var.nextDouble();
        cm=num1/2.54;

        System.out.println("El numero de pulgadas ingresado convertido en centimetros da como resultado:"+cm);
        
        
    }
    
}
