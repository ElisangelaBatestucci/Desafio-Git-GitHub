# Algoritmo Desvio Condicional

/*Função do algoritmo: Menu de opções (Desvio Condicional)
Elisangela Batestucci
21/11/2021 */

## programa

{
	

	funcao inicio()
	{
		escreva("Escolha um opção no menu:")
		escreva("\n 1 - Abrir NetFlix \n 2 - Abrir Amazon Prime \n 3 - Abrir HBO \n 4 - Sair ")
	      inteiro menu = 0
	      escreva("\n Sua opção: ")
	      leia(menu)
	
	      escolha(menu)
		{
	      caso 1:	//testa se valor é igual a 1
	      escreva("Ok! Abrir NetFilx")
	      pare
	
	      caso 2:	//testa se valor é igual a 2
	      escreva("Ok! Abrir Amazon Prime")
	      pare
	
	      caso 3:	//testa se valor é igual a 3
	      escreva("Ok! Abrir HBO")
	      pare
	
	      caso 4:	//testa se valor é igual a 4
	      escreva("Sair do menu...")
	      pare
	
	      caso contrario:
	      escreva("\n Você precisa escolhar uma opção válida")
	                }
	                
		//outra forma de resolver o mesmo problema
		/*....*/ //comentário em bloco utilizamos a barra e asterisco 
	      /*se(menu==1) {
	      	escreva("Ok! Abrir NetFilx")
	      }
	
	      se(menu==2) {
	      	escreva("Ok! Abrir Amazon Prime")
	    / }
	
	     se(menu==3) {
	      	escreva("Ok! Abrir HBO")
	     }
	
	      se(menu==4) {
	      	escreva("Saindo do Menu...")
	      }*/ finalizando o comentário em bloco
	}
}