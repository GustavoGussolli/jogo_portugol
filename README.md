programa
{
	inclua biblioteca Util --> u
	
	funcao inicio()
	{
		
	inteiro volta
	inteiro lado
	inteiro portas_da_esquerda
	inteiro codigo
	cadeia nome
	inteiro confirma
	inteiro escolha_final
	inteiro escolha_mostro
	
	escreva("Imagine que voce acorde num corredor e voce não sabe onde está, mas voce sabe que tem que ir embora desse lugar")
	u.aguarde(6000)
	limpa()

	escreva("Informe seu nome: ")
	leia(nome)
	u.aguarde(2000)
	limpa()
	
	
	escreva(nome , " Nome bonito ")
	u.aguarde(3000)
	limpa()


	escreva("Temos dois lados o lado direito e o lado esquerdo ")
	u.aguarde(4000)
	limpa()
     
     
	escreva("Digite 1 para esqueda e 2 para direita: " )		
	leia(lado)
	u.aguarde(1000)
	limpa()

		se(lado == 1)
		{

		escreva("Tem duas portas escolha uma delas, digite 1 para a primeira porta e 2 para segunda porta:  ")
		leia(portas_da_esquerda)
		u.aguarde(3000)
		limpa()

		se(portas_da_esquerda == 1)
			{

			 escreva("Precisa de um codigo, insira o codigo:  ")
			 leia(codigo)
			 u.aguarde(3000)
			 limpa()
				
			

			se(codigo == 371){
				
		escreva("A porta esta aberta  ")	
			
		}
		
		senao{

			escreva("Incorreto, digite 9 para sair:  ")
			leia(volta)
			u.aguarde(2000)
			limpa()
			
			se(volta == 9)
			{

			escreva("Tem duas portas escolha uma delas, digite 1 para a primeira porta e 2 para segunda porta:  ")
			leia(portas_da_esquerda)
			u.aguarde(3000)
			limpa()

			se(portas_da_esquerda == 2){


			escreva("Esta aberta  ")
			u.aguarde(3000)
			limpa()

			escreva("Dentro da sala possui uma mesa há um codigo na mesa  ")
			u.aguarde(4000)
			limpa()

			escreva("O codigo é: 371")
			u.aguarde(4000)
			limpa()

			escreva("Para sair da sala digite 8:  ")
			leia(volta)
			u.aguarde(2000)
			limpa()

			se(volta == 8){

				escreva("Tem duas portas escolha uma delas, digite 1 para a primeira porta e 2 para segunda porta:  ")
			leia(portas_da_esquerda)
			u.aguarde(3000)
			limpa()

			
			se(portas_da_esquerda == 1)
			{

			 escreva("Precisa de um codigo, insira o codigo:  ")
			 leia(codigo)
			 u.aguarde(3000)
			 limpa()
				
			

			se(codigo == 371){
				
		escreva("A porta esta aberta  ")	
		u.aguarde(2000)
		limpa()

		escreva("Dentro da sala possui uma porta que está escrito saída ")
		u.aguarde(4000)
		limpa()

		escreva("Voce olha para aquela porta e fala: ")
		u.aguarde(3000)
		limpa()

		escreva("- Agora posso ir embora finalmente")
		u.aguarde(4000)
		limpa()

		escreva("Quando " , nome ," saiu daquele lugar ele avistou um carro passando então ele gritou ")
		u.aguarde(5000)
		limpa()

		escreva("- Ei")
		u.aguarde(2000)
		limpa()

		escreva("-Por favor me ajude ")
		u.aguarde(3000)
		limpa()

		escreva("O carro parrou e resgatou voce ")
		u.aguarde(3000)
		limpa()

		escreva(" FIM \n Criador:Gustavo do Nascimento \n Obrigado por jogar \n")
			
			}
			
			}
				
			}

			}
			
		}
		
	}
}
}

		se(lado == 2 ){

		escreva("Ok, possui um corredor ")
		u.aguarde(3000)
		limpa()

		escreva("No fim do corredor há uma porta ")
		u.aguarde(3000)
		limpa()

		escreva("Deseja abrir a porta digite 1 para sim: ")
		leia(confirma)
		u.aguarde(2000)
		limpa()

		se(confirma > 1 ou confirma < 1){

		escreva("Voce digitou errado faça tudo de novo ")
		u.aguarde(3000)
		limpa()      	
			
		}

		se(confirma == 1){

			escreva("Voce abriu a porta e dentro daquela sala possui uma pessoa e tambem possui uma porta escrita saida ")
			u.aguarde(6000)
			limpa()

			escreva("Voce quer ajudar a pessoa ou fujir sozinho ")
			u.aguarde(3000)
			limpa()

			escreva("Digite 1 para ajudar ou 2 para fujir: ")
			leia(escolha_final)
			u.aguarde(2000)
			limpa()

			se(escolha_final == 2){

				escreva("Voce vai para a saida e vai embora daquele local")
				u.aguarde(3000)
				limpa()

				escreva("FIM \n Criador: Gustavo do Nascimento \n Obrigado por jogar ")
				u.aguarde(3000)
				limpa()


			}



			se(escolha_final == 1){

				escreva("Voce tem um bom coração ")
				u.aguarde(3000)
				limpa()

				escreva("Voce foi ajudar a pessoa ")
				u.aguarde(3000)
				limpa()

				escreva("Voce pergunta para a pessoa")
				u.aguarde(3000)
				limpa()

				escreva("-Voce está bem? ")
				u.aguarde(3000)
				limpa()

				escreva("Quando voce olhou para o rosto da pessoa,voce viu que a pessoa estava morta ")
				u.aguarde(3000)
				limpa()

				escreva("Voce se assusta com aquele situação e escuta um barulho  atras de voce")
				u.aguarde(3000)
				limpa()

				escreva("Quando voce olhou para tras")
				u.aguarde(3000)
				limpa()

				escreva("Tinha um mostro olhando fixamente para voce")
				u.aguarde(3000)
				limpa()

				escreva("...")
				u.aguarde(3000)
				limpa()

				escreva("Um silencio absoluto estava naquele local")
				u.aguarde(3000)
				limpa()

				escreva("Voce olhando para o mostro e o mostro olhando para voce")
				u.aguarde(3000)
				limpa()

				escreva("Voce quer correr ou ficar parado para ver oque vai acontecer ")
				u.aguarde(3000)
				limpa()

				escreva("Digite 1 para correr ou 2 para ficar parado :  ")
				leia(escolha_mostro)
				u.aguarde(3000)
				limpa()

				se(escolha_mostro == 1){

				escreva("Quando voce vai correr ")
				u.aguarde(3000)
				limpa()

				escreva(" O mostro te devora ")
				u.aguarde(3000)
				limpa()

				
			}


			se(escolha_mostro == 2 ){

				escreva("Voce decidi ficar paralizado para ver oque vai acontecer ")
				u.aguarde(3000)
				limpa()

				escreva("O mostro olha atentamente para voce e chega cada vez mais perto de voce ")
				u.aguarde(3000)
				limpa()

				escreva("O mostro chega em voce e te ignora e vai embora")
				u.aguarde(3000)
				limpa()

				escreva("Então depois que o mostro vai embora voce corre para a saida")
				u.aguarde(3000)
				limpa()

				escreva("Voce abre a porta e ve que esta fora daquele lugar ")
				u.aguarde(3000)
				limpa()

				escreva("Quando voce vai sair o mostro te aguarra para dentro ")
				u.aguarde(3000)
				limpa()

				escreva("E voce grita pedindo socorro ")
				u.aguarde(3000)
				limpa()

				escreva("- AAAAAAAAAAAAAAAAAAAAA ")
				u.aguarde(3000)
				limpa()

				escreva("SOCORRO ")
				u.aguarde(3000)
				limpa()

				escreva("Infelizmente voce acaba morrendo dentro daquele lugar ")
				u.aguarde(3000)
				limpa()

				escreva("FIM \n Criador: Gustavo do Nascimento \n Obrigado por jogar")
				u.aguarde(3000)
				limpa()






			}
		}

		se(confirma > 1 ou confirma < 1 ){


			escreva("Tem certeza, se voce não digita 1 voce perderra todo o progresso ")
			u.aguarde(4000)
			limpa()

			escreva("Deseja abrir a porta digite 1 para sim: ")
			leia(confirma)
			u.aguarde(2000)
			limpa()

		se(confirma == 1){

			

			
			escreva("Voce abriu a porta e dentro daquela sala possui uma pessoa e tambem possui uma porta escrita saida ")
			u.aguarde(6000)
			limpa()

			escreva("Voce quer ajudar a pessoa ou fujir sozinho ")
			u.aguarde(3000)
			limpa()

			escreva("Digite 1 para ajudar ou 2 para fujir: ")
			leia(escolha_final)
			u.aguarde(2000)
			limpa()

			se(escolha_final == 2){

				escreva("Voce vai para a saida e vai embora daquele local")
				u.aguarde(3000)
				limpa()

				escreva("FIM \n Criador: Gustavo do Nascimento \n Obrigado por jogar ")
				u.aguarde(3000)
				limpa()


			}



			se(escolha_final == 1){

				escreva("Voce tem um bom coração ")
				u.aguarde(3000)
				limpa()

				escreva("Voce foi ajudar a pessoa ")
				u.aguarde(3000)
				limpa()

				escreva("Voce pergunta para a pessoa")
				u.aguarde(3000)
				limpa()

				escreva("-Voce está bem? ")
				u.aguarde(3000)
				limpa()

				escreva("Quando voce olhou para o rosto da pessoa,voce viu que a pessoa estava morta ")
				u.aguarde(3000)
				limpa()

				escreva("Voce se assusta com aquele situação e escuta um barulho  atras de voce")
				u.aguarde(3000)
				limpa()

				escreva("Quando voce olhou para tras")
				u.aguarde(3000)
				limpa()

				escreva("Tinha um mostro olhando fixamente para voce")
				u.aguarde(3000)
				limpa()

				escreva("...")
				u.aguarde(3000)
				limpa()

				escreva("Um silencio absoluto estava naquele local")
				u.aguarde(3000)
				limpa()

				escreva("Voce olhando para o mostro e o mostro olhando para voce")
				u.aguarde(3000)
				limpa()

				escreva("Voce quer correr ou ficar parado para ver oque vai acontecer ")
				u.aguarde(3000)
				limpa()

				escreva("Digite 1 para correr ou 2 para ficar parado :  ")
				leia(escolha_mostro)
				u.aguarde(3000)
				limpa()

				se(escolha_mostro == 1){

				escreva("Quando voce vai correr ")
				u.aguarde(3000)
				limpa()

				escreva(" O mostro te devora ")
				u.aguarde(3000)
				limpa()

				escreva("FIM \n Criador: Gustavo do Nascimento \n Obrigado por jogar")
				u.aguarde(3000)
				limpa()

				
			}


			se(escolha_mostro == 2 ){

				escreva("Voce decidi ficar paralizado para ver oque vai acontecer ")
				u.aguarde(3000)
				limpa()

				escreva("O mostro olha atentamente para voce e chega cada vez mais perto de voce ")
				u.aguarde(3000)
				limpa()

				escreva("O mostro chega em voce e te ignora e vai embora")
				u.aguarde(3000)
				limpa()

				escreva("Então depois que o mostro vai embora voce corre para a saida")
				u.aguarde(3000)
				limpa()

				escreva("Voce abre a porta e ve que esta fora daquele lugar ")
				u.aguarde(3000)
				limpa()

				escreva("Quando voce vai sair o mostro te aguarra para dentro ")
				u.aguarde(3000)
				limpa()

				escreva("E voce grita pedindo socorro ")
				u.aguarde(3000)
				limpa()

				escreva("- AAAAAAAAAAAAAAAAAAAAA ")
				u.aguarde(3000)
				limpa()

				escreva("SOCORRO ")
				u.aguarde(3000)
				limpa()

				escreva("Infelizmente voce acaba morrendo dentro daquele lugar ")
				u.aguarde(3000)
				limpa()

				escreva("FIM \n Criador: Gustavo do Nascimento \n Obrigado por jogar")
				u.aguarde(3000)
				limpa()


			
		}
		
		}


		}


		}

		}
		


			
		}
		
	
	}
}
