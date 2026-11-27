AULA 10 - Decremento

Vamos para a próxima aula! 💻 Hoje vamos aprender a fazer o contador andar para trás, de 20 até 0. Isso se chama decremento.

Até agora, usamos:
contador = contador + 1



Isso aumenta o contador em 1 (incremento).

Agora vamos fazer o contrário:
contador = contador - 1



Isso diminui o contador em 1 (decremento).
1. Entendendo o contador regressivo
Veja este exemplo:
contador = 5while contador >= 0:    print(contador)    contador = contador - 1



O resultado será:
5
4
3
2
1
0


2. Como o código funciona?
- contador = 5 → começa no número 5.
- while contador >= 0: → continua enquanto o contador for maior ou igual a zero.
- print(contador) → mostra o número atual.
- contador = contador - 1 → diminui 1 a cada repetição.
Veja como o contador muda
5

4

3

2


1

0

-1


O contador chega a 0, mas não vai até -1, porque o while deixa de ser verdadeiro.
Quando o contador chega a -1, a condição contador >= 0 se torna falsa e o loop termina.

3. Seu exercício de hoje 🎯
Agora quero que você faça sozinho, sem copiar o exemplo:

Crie um programa que:
1. Comece com contador = 20.
2. Use while para repetir enquanto o contador for maior ou igual a 0.
3. Mostre o contador na tela.
4. Diminua o contador de 1 em 1.
Dica: você já sabe fazer tudo isso. Só precisa trocar o incremento pelo decremento e ajustar a condição do while.
