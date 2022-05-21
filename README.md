
--->Olá, meu nome é Filipe Lelis e venho apresentar alguns exercicios de lógica de progamação, desenvolvido no visualg

Algoritmo "ATIVIDADE FLAMINGO - EXERCICIO 23



// Disciplina: Lógica de Programação com JavaScript
// Professor : Jailson Santos
// Descrição   : calcular imc
// Autor(a)    : Filipe Lelis
// Data atual  : 12/04/2022
Var
   // Seção de Declarações das variáveis
   NOME: CARACTER
   SEXO: CARACTER
   ALTURA, PESO_IDEAL: REAL

Inicio
   // Seção de Comandos, procedimento, funções, operadores, etc...
   ESCREVAL("DIGITE O SEU NOME: ")
   LEIA(NOME)
   ESCREVAL("DIGITE O SEU SEXO: ")
   LEIA(SEXO)
   ESCREVAL("DIGITE A SUA ALTURA: ")
   LEIA(ALTURA)

   SE SEXO = "MASCULINO" ENTAO
      PESO_IDEAL <- (72.7 * ALTURA) - 58
   SENAO
      PESO_IDEAL <- (62.1 * ALTURA) - 44.7
   FIMSE

   ESCREVAL("O SEU PESO IDEAL É DE ", PESO_IDEAL, "KG")

Fimalgoritmo
