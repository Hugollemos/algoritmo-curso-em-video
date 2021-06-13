__Média escolar__
```
algoritmo "semnome"
var
p1, p2, media: real
inicio
Escreval("---------------------")
EScreval("ESCOLA JAVALI CANSADO")
Escreval("---------------------")
Escreva("Primeira Nota: ")
Leia(p1)
Escreva("Segunda Nota: ")
Leia(p2)
media <- (p1 + p2) / 2
se (media >= 7) entao
   Escreval("---------------------")
   Escreval("Primeira Nota:", p1)
   Escreval("Segunda Nota:", p2)
   Escreval("---------------------")
   Escreval("MEDIA ",media:2:1)
   Escreval("ALUNO APROVADO")
senao
   Escreval("---------------------")
   Escreval("Primeira Nota:", p1)
   Escreval("Segunda Nota:", p2)
   Escreval("---------------------")
   Escreval("media ",media:2:1)
   Escreval("ALUNO REPROVADO")
   Escreval("---------------------")
Fimse
fimalgoritmo
```