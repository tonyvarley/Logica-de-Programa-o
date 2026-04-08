importar java.util.Scanner;
public class Revisão{
public static void main(String[] args){
Scanner leitor = new Scanner(System.in);
int valor, resto;
System.out.println(“Digite um Número”);
valor = leitor.nextInt();
resto = valor%2;
if(resto == 0){
System.out.println(valor + “ é par”)
} else {
System.out.println(valor + “ é impar”)
}
}
}
