import java.util.Scanner;

public class Senha {
       public static void  main (String[] args){

        Scanner sc = new
Scanner(System.in);

      int senha;
      int correta = 1234;

      do{
        System.out.print("digite a senha: ");
        senha = sc.nextInt();
      }while(senha != correta);

      System.out.println("senha correta!");
       }
    
}
