Aula 09 — while (repetição)
O while serve para repetir um bloco de código enquanto uma condição for verdadeira.
1. Entendendo na prática
contador = 1while contador <= 5:    print(contador)    contador = contador + 1



O resultado será:
1
2
3
4
5


2. Como o código funciona?
- contador = 1 → começa em 1.
- while contador <= 5 → enquanto contador for menor ou igual a 5, continua.
- print(contador) → mostra o valor atual.
- contador = contador + 1 → aumenta 1 a cada repetição.
O segredo do while
Se você não aumentar o contador (ou não alterar a condição de alguma forma), o programa pode ficar repetindo para sempre. Isso é chamado de loop infinito.

3. Seu primeiro exercício de hoje
Quero que você crie um programa que:
1. Comece com uma variável contador = 0.
2. Use while para repetir enquanto contador for menor que 10.
3. Mostre o contador na tela.
4. Aumente o contador de 1 em 1.
Tente fazer sozinho, usando o que acabamos de aprender. Não precisa ter pressa. Se der erro, pode me mandar o código que corrigimos juntos, como fizemos nas aulas anteriores.


O while precisa estar alinhado com o contador = 1. Já o print() e o incremento precisam ficar recuados, pois estão dentro do while.
