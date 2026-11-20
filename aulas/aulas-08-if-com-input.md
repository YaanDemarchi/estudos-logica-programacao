Aula 8 — if com input()

Até agora, você fez programas que recebem informações e mostram resultados. Agora vamos fazer o programa tomar decisões com base no que o usuário digita.
1. Relembrando
Você já sabe receber a idade assim:
idade = int(input("Digite sua idade: "))



Agora vamos usar essa variável em uma condição if.
2. Juntando as coisas
Digite este código no Colab:
idade = int(input("Digite sua idade: "))if idade >= 18:    print("Você é maior de idade.")else:    print("Você é menor de idade.")



3. Entendendo cada parte
- input() pergunta a idade.
- int() transforma a resposta em número.
- idade >= 18 verifica se a idade é 18 ou maior.
- if executa o código se a condição for verdadeira.
- else executa o código se a condição for falsa.
Exemplo de funcionamento

Se você digitar 20, o programa exibirá:

Você é maior de idade.

Se digitar 15, exibirá:

Você é menor de idade.

4. Seu exercício
Agora faça três testes, executando o programa com:
- Idade 12
- Idade 18
- Idade 25
Observe como a resposta muda.



Por enquanto, só faça isso. Depois me diga o que apareceu em cada teste, e vamos para a próxima parte da aula.
