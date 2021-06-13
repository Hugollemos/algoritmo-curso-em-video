algoritmo "semnome"
var
   valor, Vimpo, parcela, total: Real
inicio
      Escreva("Olá, quantos R$ você gostaria de retirar do imprestimo?: ")
      Leia(valor)
      Escreval("Entendi, vamos ter um juros de 20% sobre esse valor.")
        Vimpo <- valor + (valor * 20)/100
      Escreval("O valor total desse imprestimo de",valor," R$ será de:",vimpo)
      //Vimpo <- valor + (valor * 20)/100
      Escreva("quantas parcelas você quer que esse valor seja pago? ")
      Leia(parcela)
      total <- Vimpo/parcela
      Escreva("O parcelamento de", Vimpo," R$ Será no total de",parcela," de")
      Escreva(total,"R$")
fimalgoritmo