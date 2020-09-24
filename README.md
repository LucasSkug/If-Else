# If-Else
import java.util.Scanner;

public class Votarounao {
//PROGRAMA FEITO PARA SABER SE UMA PESSOA PODE VOTAR OU NÃO
	public static void main(String[] args) {
		Scanner entradaDados = new Scanner(System.in);
		int anoNascimento;
		 
		 System.out.println("Digite o ano de nascimento");
		 anoNascimento = entradaDados.nextInt();
		 
		 if(2020 - anoNascimento >= 16) {
			 System.out.println("Você pode votar neste ano");
		 } else {
			 System.out.println("Você não podera votar esse ano");
		 }
		
		
	}
}


import java.util.Scanner;

public class Senha {
//PROGRAMA PARA SABER SE A SENHA É VALIDA  
	public static void main(String[] args) {
		Scanner entradaDeDados = new Scanner(System.in);
		int senha;
		
		System.out.println("Digite a senha valida");
		senha = entradaDeDados.nextInt();
		
		if (senha == 1234) {
			System.out.println("ACESSO PERMITIDO");
		} else 
			System.out.println("ACESSO NEGADO");
		
		
		entradaDeDados.close();
	}

}


import java.util.Scanner;

public class Macas {
//TOTAL DE COMPRAS DE MAÇA
	public static void main(String[] args) {
		Scanner entradaDeDados = new Scanner(System.in);
		int macas;
		
		System.out.println("Quantas maças deseja comprar?");
		macas = entradaDeDados.nextInt();
		
		if(macas >= 12) {
			System.out.println("Cada maça saiu por R$0,25");
		} else {
			System.out.println("Cada maça saiu por R$0,30");
		}

		
		
		
		
		entradaDeDados.close();
	}

}
