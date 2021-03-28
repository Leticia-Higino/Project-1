# Project-1
Project 1 - in test
var jogador = prompt("Escolha P para PAR ou I impar");
var numeroJogador = parseInt(prompt("Quantos dedos?"));


var numeroComputador = Math.floor(Math.random()*10) + 1;
alert(numeroComputador);

var resultado = (numeroJogador + numeroComputador);
var resultadoFinal =  resultado % 2;

if(jogador == "P")
{
 
 if( resultadoFinal == 0)
 {
    document.write("Você ganhou");
 }

 else 
 {
   document.write("você perdeu");
 }
}
else
{
   if(resultadoFinal == 1)
   {
     document.write("Você ganhou");
   }
   else
   {
     document.write("Você perdeu");
   }
}
