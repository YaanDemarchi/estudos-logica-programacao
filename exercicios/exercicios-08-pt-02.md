EXERCÍCIO PARTE 2 

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

if(idade <18):
  print("Faltam",18-idade,"anos para você completar 18")
