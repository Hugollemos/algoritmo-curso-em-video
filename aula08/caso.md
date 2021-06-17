
```
algoritmo "PartidaFutebol"
algoritmo "semnome"
var
   gols1, gols2, dif: Inteiro
inicio
      EscrevaL("-----------------------")
      EscrevaL("   BANGU x MADUREIRA   ")
      EscrevaL("-----------------------")
      Escreva ("Quantos gols BANGU fez? ")
      Leia(gols1)
      Escreva ("Quantos gols MADUREIRA fez: ")
      Leia(gols2)
      se (gols1 > gols2) entao
         dif <- gols1 - gols2
      senao
           dif <- gols2 - gols1
      Fimse
          Escolha dif
                 Caso 0
                 Escreval("--------------------")
                 Escreval("DIFERENÇA: ", dif)
                 Escreval("STATUS: EMPATE ")
                 Escreval("--------------------")
                 Caso 1, 2, 3
                 Escreval("--------------------")
                 Escreval("DIFERENÇA: ", dif)
                 Escreval("STATUS: PARTIDA NORMAL ")
                 Escreval("--------------------")
                 Caso 6, 7, 8
                 Escreval("--------------------")
                 Escreval("DIFERENÇA: ", dif)
                 Escreval("STATUS: GOLEADA ")
                 Escreval("--------------------")
                 OutroCaso
                 Escreva("Você digitou o valor certo?")
          FimEscolha

fimalgoritmo
```
```
algoritmo "semnome"
var
gols1, gols2, dif: Inteiro
inicio
EscrevaL("-----------------------")
EscrevaL("   BANGU x MADUREIRA   ")
EscrevaL("-----------------------")
Escreva ("Quantos gols BANGU fez? ")
Leia(gols1)
Escreva ("Quantos gols MADUREIRA fez: ")
Leia(gols2)
se (gols1 > gols2) entao
   dif <- gols1 - gols2
senao
   dif <- gols2 - gols1
Fimse

se (dif = 0)entao
   Escreval("--------------------")
   Escreval("DIFERENÇA: ", dif)
   Escreval("STATUS: EMPATE ")
   Escreval("--------------------")
senao
   se(dif >=1) e (dif<=3)entao
      Escreval("--------------------")
      Escreval("DIFERENÇA: ", dif)
      Escreval("STATUS: PARTIDA NORMAL ")
      Escreval("--------------------")
   senao
      se(dif >=4) e (dif<=6)entao
         Escreval("--------------------")
         Escreval("DIFERENÇA: ", dif)
         Escreval("STATUS: GOLEADA ")
         Escreval("--------------------")
      senao
         Escreva(" VOCÊ DIGITOU OS VALORES CERTOS???")
      fimse
   fimse
fimse
fimalgoritmo
```