```
algoritmo "semnome"
var
turma, cont : Inteiro
nota, maior: Real
nome,nomeM : caractere
inicio
Escreval("-----------------------")
Escreval("Escola Santa Panciência")
Escreval("-----------------------")

Escreva("Quantos alunos a turma tem? ")
Leia(turma)
cont<- 1
Enquanto (turma >= cont) faca
   Escreval("----------------")
   Escreval("Aluno",cont)
   Escreva("Nome do aluno: ")
   Leia(nome)
   Escreva("Nota de ",nome,": ")
   Leia(nota)
   cont <- cont + 1
   se (nota > maior)e (nome > nomeM) entao
      maior <- nota  
      nomeM <- nome
   fimse
FimEnquanto
//Escreva(nomeM)
Escreva("O melhor aproveitamento foi de ",nomeM," com a nota",maior)
fimalgoritmo
```