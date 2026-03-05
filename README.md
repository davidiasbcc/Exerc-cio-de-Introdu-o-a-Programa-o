# exerciciodeintroducaoaprogramacao
Meu primeiro repositório no GitHub
import java.util.Scanner;

public class Uni2Exe04 {
public static void main(String[] args) {
    float notaA, notaB, media;
    Scanner sc = new Scanner(System.in);
    System.out.println("Digite notaA");
    notaA = sc.nextInt();
    System.out.println("Digite notaB");
    notaB = sc.nextInt();
    media = ((notaA * 3.5f) + (notaB * 7.5f))/11;
    System.out.println("Media: "+media);
