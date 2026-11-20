Aula 07 — Entrada de dados (input())
Até agora, quando queríamos mudar um valor, precisávamos alterar o código manualmente.

Por exemplo:
nome = "João"print("Olá,", nome)



Mas imagine se o próprio programa pudesse perguntar o nome da pessoa e receber a resposta.

É exatamente isso que o input() faz!
1. Conhecendo o input()
Observe:
nome = input("Qual é seu nome? ")print("Olá,", nome)



Quando você executar no Google Colab:
1. O Python perguntará: Qual é seu nome?
2. Você digitará seu nome.
3. O programa guardará a resposta na variável nome.
4. O print() mostrará uma saudação.

2. Recebendo números
Aqui existe um detalhe muito importante!

Por padrão, o input() recebe informações como texto (str), mesmo quando você digita um número.

Veja:
idade = input("Qual é sua idade? ")print(idade)



Se você digitar 20, o Python recebe "20" como texto.

Para transformar esse texto em número inteiro, usamos int():
idade = int(input("Qual é sua idade? "))print(idade + 5)



Se você digitar 20, o resultado será:
25


Guarde esta diferença:
- input() → recebe uma informação.
- int() → transforma em número inteiro.
- str() → transforma em texto.
- float() → transforma em número decimal.
3. Criando um programa interativo
Vamos juntar o que já aprendemos!

Imagine um programa que pergunta a idade de uma pessoa e informa se ela é maior ou menor de idade.
idade = int(input("Digite sua idade: "))if idade >= 18:    print("Maior de idade")else:    print("Menor de idade")



Perceba que agora não precisamos alterar o código para testar outras idades. Basta executar novamente e digitar outro valor!
4. Seu primeiro exercício da Aula 07
Hora de praticar
Vamos criar um programa que pergunta o nome e a idade de uma pessoa.

O programa precisa:
1. Perguntar o nome.
2. Perguntar a idade.
3. Mostrar uma mensagem de boas-vindas com o nome.
4. Mostrar quantos anos a pessoa terá daqui a 5 anos.
Exemplo de funcionamento:
Qual é seu nome? Ana
Qual é sua idade? 20

Olá, Ana!
Daqui a 5 anos você terá 25 anos.


Dicas para construir seu código:
- Use input() para receber o nome.
- Use int(input()) para receber a idade.
- Use print() para mostrar as mensagens.
- Use uma variável para calcular a idade futura.
