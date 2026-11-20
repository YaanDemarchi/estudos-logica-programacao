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

4. Seu exercício de hoje
Abra o Colab e escreva o programa abaixo, mas troque o número 25 por 48.
numero = 48if numero % 2 == 0:    print("Esse número é par")else:    print("Esse número é ímpar")



Depois, faça três testes com números diferentes:
- 7
- 100
- 33
Tente prever o resultado antes de apertar Executar.
5. O que você aprendeu hoje
Código	Significado
if	Se
else	Senão
==	É igual a
>=	Maior ou igual a
%	Resto da divisão

Você acabou de aprender a fazer seu programa tomar decisões sozinho. Isso é um dos fundamentos mais importantes da programação. 🚀

Quando terminar o exercício, podemos seguir para elif, que permite ao programa tomar várias decisões, e depois aprender a receber informações digitadas pelo usuário.
