# meu-novo-projeto


programa
{
	inclua biblioteca Matematica
	
	funcao inicio()
	{
		cadeia nome

		real altura
		real peso
		real imc

		escreva("Informe seu nome: ")
		leia(nome)

		escreva("Informe sua altura:")
		leia(altura)

		escreva("Informe seu peso:")
		leia(peso)

		imc = peso/(altura*altura)

		escreva("Olá ", nome, " seu imc é ", Matematica.arredondar(imc,2))


		//IMC menor que 18.5: Status: Magresa
		//IMC entre 18.5 e 25: Status: Normal
		//IMC entre 25.1 e 30: Sobrepeso
		//IMC maior que 30: obsidade

		 se(imc<=18.5){
			escreva("\nOlá", nome, "você tem que comer mais, kkkk, está magro!")
		}senao se((imc>=18.5) e (imc<=25)){
			escreva("\nOlá", nome, "Parabéns, você está bem! normal")
		}senao se(((imc>25.1) e (imc<=30))){
			escreva("\nOlá", nome, "Fecha a boca! sobrepeso")
		}senao se(imc>30){	
			escreva("\nOlá", nome, " Se cuida!você está obeso")
		

		}
	}
		
}
