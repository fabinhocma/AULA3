# AULA3
EX3
//teste
import java.util.Scanner;

class main
 {
  public static void main(String[] args) {
    Scanner teste = new Scanner (System.in);
    int n1,n2 = 0;

    System.out.println("Digite o primeiro numero:");
    n1 = teste.nextInt();

    System.out.println("Digite o segundo numero:");
    n2 = teste.nextInt();

    int n3 = n1+n2;
    System.out.println("A soma dos numeros foi:"+ n3);
}
}
