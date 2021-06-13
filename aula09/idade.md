```
algoritmo "semnome"
var
atual, nasc, idade: Inteiro
inicio
Escreval("------------------------")
EScreval("DEPARTAMENTO DE TRANSITO")
Escreval("------------------------")
Escreva("Ano atual (yyyy): ")
Leia(atual)
Escreva("Ano de Nascimento (yyyy): ")
Leia(nasc)
idade <- atual - nasc
se (idade >= 18) entao
   Escreval(
   Escreval("--------STATUS---------")
   Escreval("IDADE:",idade," ANOS")
   Escreval("APTO A TIRAR CARTEIRA")
   Escreva("-----------------------")
senao
   Escreval("--------STATUS---------")
   Escreval("IDADE: ",idade," ANOS")
   Escreval("INAPTO A TIRAR CARTEIRA")
   Escreva("----------------------")
Fimse
fimalgoritmo
```