```
algoritmo "semnome"
var
Cont, N, R : Inteiro
inicio
Cont <- 1
Escreva("Quer ver a tabuada de qual número? ")
Leia(N)
repita
   R <- N * Cont
   Escreval(N, " X ",Cont, " = ", R)
   Cont <- Cont + 1
ate (Cont > 10)
fimalgoritmo
```
```
algoritmo "semnome"
var
N, C, TotN: Inteiro
inicio
C <- 1
TotN <- 0
Repita
   Escreva("Digite um número: ")
   Leia (N)
   Se (N<0) entao
      TotN <- TotN + 1
   Fimse
   C <- C + 1
Ate (C > 5)
Escreval("Foram digitados ", TotN, " valores netagivos. ")
fimalgoritmo
```
```
algoritmo "semnome"
var
C, N, F: Inteiro
R: Caractere
inicio
Escreva("Digite um número: ")
Leia(N)
C <- N
F <- 1
Repita
   Escreva (C, " X ")
   F <- F * C
   C <- C - 1
Ate (C < 1)
Escreva ("O valor fatorial de ", N, " é iqual a ", F)
Escreva ("Quer continuar [S/N]")
Leia(R)
LimpaTela
Ate (R = "N")
fimalgoritmo
```
```
algoritmo "supercontador"
var
esc, cont : Inteiro
inicio
repita
   Escreval
   Escreval("=================")
   Escreval("|    M E N U    |")
   Escreval("=================")
   Escreval("| [1] de 1 a 10 |")
   Escreval("| [2] de 10 a 1 |")
   Escreval("| [3] Sair      |")
   Escreval("=================")
   Leia(esc)
   Escolha esc
   Caso 1
      Cont <- 1
      Repita
         Escreva (Cont, "..")
         Cont <- Cont + 1
      Ate (Cont > 10)
   caso 2
      Cont <- 10
      Repita
         Escreva (Cont, "..")
         Cont <- Cont - 1
      Ate (Cont < 1)
   caso 3
   Escreva("SAINDO..")
   FimEscolha
ate(esc = 3)
fimalgoritmo
```
```
algoritmo "escolhendo pessoas"
var
Sexo : Caractere
Idade, H18C, M2530L,Cabelo  : Inteiro
resp : Caractere

inicio
repita
   Escreval("=====================")
   Escreval(" SELETOR DE PESSOAS  ")
   Escreval("=====================")
   Escreva("Qual o sexo? [M/F] ")
   Leia(Sexo)
   Escreva("Qual a idade? ")
   Leia(idade)
   Escreval("Qual a cor do Cabelo? ")
   Escreval("-------------------------")
   Escreval("[1] Preto")
   Escreval("[2] Castanho")
   Escreval("[3] Loiro")
   Escreval("[4] Ruivo")
   Leia(Cabelo)
   Limpatela
   se (sexo = "M") e (idade >= 18) e (cabelo = 2) entao
      H18C <- H18C + 1
   fimse
   se (sexo = "F") e ((idade >= 25) e (idade <=30)) e (cabelo =3) entao
      M2530L <-  M2530L + 1
   fimse
   Escreva("Quer continuar? [S/N] ")
   Leia(resp)
ate (resp = "N")
Escreval("Total de homens com mais dde 18 e cabelos castanhos",H18C)
Escreva("Total de mulheres entre 25 e 30 e cabelos loiros",M2530L)
fimalgoritmo
```