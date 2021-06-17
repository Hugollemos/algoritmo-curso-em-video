```
algoritmo "semnome"
var
contador,valor : Inteiro

inicio
Contador <- 0
Escreva("Quer contar até quanto? ")
Leia(valor)
Enquanto (contador <=valor) faca
   Escreval(contador)
   contador <- contador + 1
Fimenquanto
Escreval("Terminei de contar")
fimalgoritmo
```

```
algoritmo "semnome"
var
cont, N, S, maior: Inteiro
inicio
cont <- 1
S <- 0
Enquanto (cont <= 5) faca
   Escreva ("Digite o ", cont, "o. valor : ")
   Leia (N)
   Se (N > maior) entao
      maior <- N
   Fimse
   S <- S + N
   cont <- cont + 1
FimEnquanto
Escreval("A soma de todos os valores foi ", S)
fimalgoritmo
```

```
algoritmo "semnome"
var
R, D, C: Real
inicio
C <- 1
Enquanto (C <= 4) faca
   Escreva("Qual o valor em R$? ")
   Leia(R)
   D <- R/5.07
   Escreval(" valor convertido e US$", D:5:2)
   C <- c+ 1
FimEnquanto
fimalgoritmo
```