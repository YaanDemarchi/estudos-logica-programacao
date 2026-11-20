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

nome = input("digite seu nome")
print("Olá,",nome)

idade = int(input("digite sua idade"))
print("Sua idade daqui 5 anos será",idade+5, "anos")

if(idade>=18):
  print("Você é maior de idade")
else:
  print("Você é menor de idade")
