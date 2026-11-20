Aula 04 — Operador % (resto da divisão)
O operador %, chamado módulo ou operador de resto, retorna o resto de uma divisão entre dois números.

Ele não retorna o resultado completo da divisão, mas sim o que sobra.
1. Entendendo na prática
Imagine que você tem 10 balas e quer dividir igualmente entre 3 pessoas.
- Cada pessoa recebe 3 balas.
- Você distribui 9 balas.
- Sobra 1 bala.
- Na matemática:
\[
10 \div 3 = 3 \text{ e resto } 1
\]Na programação:
print(10 % 3)

Resultado:

1

2. Mais exemplos
Código	Resultado	Explicação
10 % 2	0	Divisão exata
9 % 2	1	Sobra 1
15 % 4	3	Sobra 3
20 % 6	2	Sobra 2
7 % 5	2	Sobra 2

Quando a divisão é exata, o resto é 0.

3. Uma aplicação muito importante: descobrir se um número é par ou ímpar
Essa é uma das utilizações mais famosas do %.

Observe:

print(8 % 2)

Resultado: 0

print(7 % 2)

Resultado: 1

