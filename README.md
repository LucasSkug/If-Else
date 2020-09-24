# If-Else
import java.util.Scanner;

//PROGRAMA PARA SABER QUAL DOS DOIS NUMEROS É MAIOR

		Scanner entradaDados = new Scanner(System.in);
		int valor1;
		int valor2;
		
		System.out.println("Digite o prieiro valor");
		valor1 = entradaDados.nextInt();
		System.out.println("Digite o segundo valor");
		valor2 = entradaDados.nextInt();
		
		if(valor1 > valor2) {
			System.out.println("O numero " + valor1 + " é maior");
		}else {
			System.out.println("O numero " + valor2 + " é maior");
		}
             entradaDados.close();


//PROGRAMA PARA SABER QUAL DOS DOIS NUMEROS É MAIOR

		Scanner entradaDados = new Scanner(System.in);
		int valor1;
		int valor2;
		int valor3;
		int valor4;
		
		System.out.println("Digite o prieiro valor");
		valor1 = entradaDados.nextInt();
		System.out.println("Digite o segundo valor");
		valor2 = entradaDados.nextInt();
		System.out.println("Digite o segundo valor");
		valor3 = entradaDados.nextInt();
		System.out.println("Digite o segundo valor");
		valor4 = entradaDados.nextInt();
		
		
		if(valor1 > valor2 && valor1 > valor3 && valor1 > valor4) {
			System.out.println("O numero " + valor1 + " é maior");
		}else if (valor2 > valor1 && valor2 > valor3 && valor2 > valor4){
			System.out.println("O numero " + valor2 + " é maior");
		}else if (valor3 > valor1 && valor3 > valor2 && valor3 > valor4) {
			System.out.println("O numero " + valor3 + " é maior");
		}else {
			System.out.println("O numero " + valor4 + " é maior");
		}

              entradaDados.close();

//PROGRAMA FEITO PARA SABER SE UMA PESSOA PODE VOTAR OU NÃO

		Scanner entradaDados = new Scanner(System.in);
		int anoNascimento;
		 
		 System.out.println("Digite o ano de nascimento");
		 anoNascimento = entradaDados.nextInt();
		 
		 if(2020 - anoNascimento >= 16) {
			 System.out.println("Você pode votar neste ano");
		 } else {
			 System.out.println("Você não podera votar esse ano");
		 }
		


//PROGRAMA PARA SABER SE A SENHA É VALIDA  
	
		Scanner entradaDeDados = new Scanner(System.in);
		int senha;
		
		System.out.println("Digite a senha valida");
		senha = entradaDeDados.nextInt();
		
		if (senha == 1234) {
			System.out.println("ACESSO PERMITIDO");
		} else 
			System.out.println("ACESSO NEGADO");
		
		
		entradaDeDados.close();
	


//TOTAL DE COMPRAS DE MAÇA
	
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
