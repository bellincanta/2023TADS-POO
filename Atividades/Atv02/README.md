# Modelo para Apresentação da Atividades

Segue abaixo o modelo de como devem ser documentadas as entregas.

<hr>


## Notebook Teste - AtvTeste

> Descrever os passos realizados para a resolução da atividade.  

> Inserir o código Java criado para a resolução da atividade, conforme exemplo de código abaixo.

/*
Classe exemplo diretiva If: DiretivaIf.java 
IFPR - Campus Cascavel
Disciplina: Programação Orientada à Objetos
Professor: Nelson Bellincanta 
Data da criação: 05/04/2023
*/

public class DiretivaIf {
	public static void main (String args[]) {
		if (args.length > 0) { //Testa presença de argumentos
			// converte 1º argumento para inteiro
			int max = Integer.parseInt(args[0]);
			for (int j=0; j<max; j++) {
				System.out.print(j + " ");
			}
			System.out.println("\nFim da Contagem"); //Exibe mensagem fim da contagem
		}
		System.out.println("Fim do Programa"); //Exibe mensagem fim do programa
	}
}

<hr>