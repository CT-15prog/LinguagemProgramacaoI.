# Linguagem de Programação I

## Nome Completo
Carlos Tadeu Gama Filho.  

## Curso e Turma
Licenciatura em Computação 2025.1 

## O que espero aprender na disciplina
Minha expectativa principal é desenvolver uma base sólida de lógica de programação, compreender passo a passo como estruturar algoritmos simples e praticar até que esses conceitos se tornem naturais. Quero entender como a lógica se transforma em código e como isso se conecta com problemas reais. E assim estou buscando aproveitar o máximo de tudo que disciplina pode oferecer. 

## Quais são meus interesses em programação
Meus principais interesses na área de programação, que começam pela vontade de querer aprender desde o início, com calma e paciência porque não é algo que se aprende da noite para o dia, começando pela lógica básica bem solidificada para depois avançar para linguagens, ferramentas e projetos maiores. Meu objetivo final é trabalhar com programação no futuro e construir uma carreira nessa área.

## Código completo do meu primeiro programa em pascal
```
program calculomedia;

var
  qtd, i, aprovados, reprovados : integer;
  n1, n2, media : real;

begin
  writeln('Quantidade de alunos: ');
  readln(qtd);

  aprovados := 0;
  reprovados := 0;

  for i := 1 to qtd do
  begin
    writeln('Nota 1 do aluno ', i, ': ');
    readln(n1);

    writeln('Nota 2 do aluno ', i, ': ');
    readln(n2);

    media := (n1 + n2) / 2;

    if media >= 7 then
      aprovados := aprovados + 1
    else
      reprovados := reprovados + 1;
  end;

  writeln('Aprovados: ', aprovados);
  writeln('Reprovados: ', reprovados);
  readln
end.
```
  
