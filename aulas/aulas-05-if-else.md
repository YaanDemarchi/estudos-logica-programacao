Aula 05 — Condições (if e else)
Imagine que queremos fazer um programa que descubra se um número é par ou ímpar, automaticamente.

Até agora, o Python apenas fazia cálculos. Agora vamos ensiná-lo a tomar decisões.
1. O if
A palavra if significa "se".

Ela permite que o Python verifique uma condição e execute um código somente quando essa condição for verdadeira.

Exemplo:
idade = 18if idade >= 18:    print("Maior de idade")



Nesse código:
- if → se;
- idade >= 18 → verifica se a idade é maior ou igual a 18;
- : → indica que começa o bloco da condição;
- print() → executa se a condição for verdadeira.
Resultado:
Maior de idade


2. O else
E se a condição não for verdadeira? Para isso usamos else, que significa "senão".
idade = 15if idade >= 18:    print("Maior de idade")else:    print("Menor de idade")



O Python verifica a idade. Como 15 não é maior ou igual a 18, ele executa o else.

Resultado:
Menor de idade


3. Vamos usar o que você aprendeu com %
Agora vamos juntar duas coisas: operador % + if + else.

Vamos criar um programa que descobre se um número é par ou ímpar.
numero = 25if numero % 2 == 0:    print("Esse número é par")else:    print("Esse número é ímpar")



Como o Python pensa?
1. Ele pega o número 25.

2. Calcula 25 % 2, que resulta em 1.

3. Verifica se o resto é igual a 0.

4. Como não é, a condição é falsa.

5. Executa o else e escreve "Esse número é ímpar".

Resultado no Colab:
Esse número é ímpar


O símbolo == significa comparar se dois valores são iguais. Ele é diferente do =, que usamos para guardar valores em variáveis.
- = → atribuição (guardar)
- == → comparação (verificar se é igual)
