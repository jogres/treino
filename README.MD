###autor###
***Wesley rocha***
#DCS- Desenvolvimento Corporativo de software#
**I Encontro de Informatica do Instituto Federal de Rond�nia**
###vers�o###
***1.0***
###atividade 1 do livro de logica de programa��o co capitulo 6###
Programa Pzim;
USES CRT;
var
   o: array [1..10] de inteiro;
   i, j: integer; aux: integer;
In�cio
   writeln ('digite numeros aleatorio 10');
   para i: = 1 a 10 fazem
     in�cio
      writeln ('digte o', i, 'numero');
      ler (o [i]);
     fim;
    para i: = 1 a 9 fazer 
      in�cio 
       para j: = i + 1 e 10 n�o 
          in�cio
             se (o [i]> o [j]) ent�o
               in�cio
                 aux: = o [i];
                 o [i]: = o [j];
                 o [j]: = aux;
               fim; 
          fim;
      fim;            
     clrscr;
     writeln ('Listagem');
     para j: = 1 a 10 fazem
        in�cio
          writeln (o [j]);
        fim;
       ReadKey; 
Fim.