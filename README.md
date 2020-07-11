# Numeros-Primos
Logica para sequenciar números primos
var
   Valor_Inicial,Cont,Divisiveis,Cont2,D:Inteiro
inicio
   Escreva("Escreva um valo: ")
   Leia(Valor_Inicial)
   Cont<-1
   Repita
      D<-0
      Cont2<-1
      Se ((Cont%2<>0) ou (Cont=2)) entao
         Repita
            Se (Cont%Cont2=0) entao
               D<-D+1
            FimSe
            Cont2<-Cont2+1
         Ate (Cont2>Cont)
      FimSe
      Se (D=2) entao
         EscrevaL(Cont)
      FimSe
      Cont<-Cont+1
   Ate (Cont>Valor_Inicial)
fimalgoritmo
