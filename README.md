# trabalho git Mailson
 trabalho SI

algoritmo "semnome"
var
   ES:Inteiro
   N1,N2,N3,MA,MP:Real

inicio
      EscrevaL("-----------------------------------------------")
      EscrevaL("              MENU DE OPÇÕES                   ")
      EscrevaL("-----------------------------------------------")
      EscrevaL("[1]Para media aritmedica.")
      EscrevaL("[2]Para media ponderada.")
      EscrevaL("[3]Para sair.")
      EscrevaL("-----------------------------------------------")
      EscrevaL("         DIGITE A OPÇÃO DESEJADA               ")
      EscrevaL("-----------------------------------------------")
      Leia(ES)
      Escolha Es
      caso 1
           Escreva("Informe o valor da primeira nota:")
           Leia(N1)
           Escreva("Informe o valor da segunda nota:")
           Leia(N2)
           MA<- (N1+N2)/2
           EscrevaL("A media aritimedica é",MA)
      caso 2
           Escreva("Informe o valor da primeira nota:")
           Leia(N1)
           Escreva("Informe o valor da segunda nota:")
           Leia(N2)
           Escreva("Informe o valor da terceira nota:")
           Leia(N3)
           MP<-(N1*2)+(N2*3)+(N3*1)/2+3+1
           EscrevaL("A media ponderada é",MP)
      caso 3
           Escreval("Obrigado")
      FimEscolha
FimAlgoritmo