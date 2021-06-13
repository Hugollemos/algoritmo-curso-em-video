__Imposto__
```
algoritmo "semnome"
var
   preco, imposto: real
inicio
      Escreva("Qual o preco do produto? US$: ")
      Leia(preco)
      imposto <- (preco * 60)/100
      Escreva("O imposto sera de US$", imposto:5:1)
fimalgoritmo
```