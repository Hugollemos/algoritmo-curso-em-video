```
algoritmo "semnome"
var
I, F, cont : Inteiro
inicio
Escreval("-----------------------")
Escreval(" CONTAGEM INTELIGENTE ")
Escreval("-----------------------")
Escreva("Início: ")
Leia(I)
Escreva("Fim: ")
Leia(F)
Escreval("-----------------")
Escreval(" C O N T A N D O ")
Escreval("-----------------")

se ( I < F) entao
   Enquanto (I <= F) faca
      Escreva(I,"..")
      I <- I + 1
   FimEnquanto
senao
   se(I > F) entao
      Enquanto (I >= F) faca
         Escreva(I,"..")
         I <- I - 1
      FimEnquanto
   Fimse
Fimse
fimalgoritmo
```