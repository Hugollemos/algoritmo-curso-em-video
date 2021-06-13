```
algoritmo "semnome"
var
Nome: Caractere
Sal, Nsal : Real
Dep : Inteiro
inicio
      Escreva ("Qual o nome do Funcionário? ")
      Leia(Nome)
      Escreva ("Qual o salário do Funcionário? R$")
      Leia (Sal)
      Escreva ("Qual é a quantidade de dependentes? ")
      Leia (Dep)
      Escolha Dep
              Caso 0
                   Nsal <- Sal + (Sal*5/100)
              Caso 1, 2, 3
                   Nsal <- Sal + (Sal*10/100)
              Caso 4, 5, 6
                   Nsal <- Sal + (Sal*15/100)
              outrocaso
                       Nsal <- Sal + (Sal*18/100)
      FimEscolha
      Escreval(" O Novo Sálario de ", Nome, "sera de R$", Nsal:5:2)
fimalgoritmo
```