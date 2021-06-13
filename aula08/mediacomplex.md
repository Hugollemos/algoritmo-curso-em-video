```
algoritmo "semnome"
var
P1, P2, MEDIA: real
inicio
Escreval("---------------------")
Escreval("ESCOLA JAVALI CANÇADO")
Escreval("---------------------")
Escreva("Primeira Nota: ")
Leia(P1)
Escreva("Segunda Nota: ")
Leia(P2)
Escreval("---------------------")
MEDIA <-(P1 + P2)/2

Se (MEDIA >=9) e (MEDIA < 10) entao
   Escreval("MEDIA ",MEDIA)
   Escreval("APROVEITAMENTO: A")
senao
   se(MEDIA >=8) e (MEDIA < 9) entao
      Escreval("MEDIA",MEDIA)
      Escreval("APROVEITAMENTO: B")
   Senao
      se(MEDIA >=7) e (MEDIA < 8) entao
         Escreval("MEDIA",MEDIA)
         Escreval("APROVEITAMENTO: C")
      senao
         se(MEDIA <=6) e (MEDIA < 7) entao
            Escreval("MEDIA",MEDIA)
            Escreval("APROVEITAMENTO: D")
         senao
            se(MEDIA <=5) e (MEDIA < 6 )entao
               Escreval("MEDIA",MEDIA)
               Escreval("APROVEITAMENTO: E")
            senao
               Escreval("MEDIA",MEDIA)
               Escreval("APROVEITAMENTO: F")
            Fimse
         Fimse
      Fimse
   Fimse
Fimse
Escreval("---------------------")
fimalgoritmo
```




