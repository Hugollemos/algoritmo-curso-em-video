```
algoritmo "semnome"
var
gols1, gols2, dif: Inteiro
inicio
Escreval("BANGU X MADEREIRA")
Escreval("----------------------")
Escreva("Quantos gols do BANGU? ")
Leia(gols1)
Escreva("Quantos gols de MADUREIRA? ")
Leia(gols2)
dif <- (gols1 - gols2)

Se (dif = 0) entao
   Escreval("-------------")
   Escreval("DIFERENÇA:",dif)
   Escreval("STATUS: Empate")
   Escreva("-------------")
senao
   se(dif >=1) e (dif <=3) entao
      Escreval("-------------")
      Escreval("DIFERENÇA:",dif)
      Escreval("STATUS: PARTIDA NORMAL")
      Escreva("--------------")
   senao
      Se (dif >= 5) entao
         Escreval("-------------")
         Escreval("DIFERENÇA:",dif)
         Escreval("STATUS: GOLEADA")
         Escreva("--------------")
      Fimse
   Fimse
Fimse

fimalgoritmo
```