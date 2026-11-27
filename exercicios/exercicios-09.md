EXERCICIO WHILE 

Quero que você crie um programa que:
1. Comece com uma variável contador = 0.
2. Use while para repetir enquanto contador for menor que 10.
3. Mostre o contador na tela.
4. Aumente o contador de 1 em 1.


R: 
contador=0
while contador<=10:
  print(contador)
  contador=contador+1


Exercício 2 — Um pequeno desafio
Agora vamos mudar um pouco. Faça um programa que:
- Comece com contador = 0.
- Repita enquanto o contador for menor ou igual a 20.
- Mostre somente os números pares (2, 4, 6, 8...).
- O contador deve aumentar de 2 em 2.
Dica: Você não precisa usar if neste exercício. É possível fazer isso apenas ajustando o valor que o contador recebe a cada repetição.

contador=0
while contador<=20:
  print(contador)
  contador=contador+2

Exercício 2 — Um pequeno desafio
Agora vamos mudar um pouco. Faça um programa que:
- Comece com contador = 0.
- Repita enquanto o contador for menor ou igual a 20.
- Mostre somente os números pares (2, 4, 6, 8...).
- O contador deve aumentar de 2 em 2.
Dica: Você não precisa usar if neste exercício. É possível fazer isso apenas ajustando o valor que o contador recebe a cada repetição.

Desafio 3
Faça um programa que conte de 1 até 20, mas:
- Se o número for par, mostre É par.
- Se o número for ímpar, mostre É ímpar.

- 
contador=1
while contador<=20:
  if contador%2==0:
    print(contador,"-Ele é um numero par")
  else:
    print(contador,"-Ele é um numero impar")
  contador=contador+1


Observe os recuos (indentação):
- contador = 0 fica no início, sem recuo.
- while contador < 10: também fica no início.
- print(contador) fica recuado, pois está dentro do while.
- contador = contador + 1 também fica recuado, pois precisa ser executado em cada repetição.
   Agora é sua vez!
Não copie o código acima ainda. Quero que você tente escrever sozinho, seguindo estas instruções:
1. Crie contador = 0.
2. Faça o while repetir enquanto contador < 10.
3. Mostre o contador com print().
4. Aumente o contador em 1.
Pode mandar seu código aqui que eu vou conferir com você, linha por linha, sem pular etapas. Vamos ver se você já pegou o jeito do while!


contador = 0 
while contador<10:
  print(contador)

  contador=contador+1


Perfeito!!  Seu código está correto! Você acertou a estrutura do while, a condição e o incremento.

Seu código:

contador = 0

while contador < 10:
    print(contador)

    contador = contador + 1

    
