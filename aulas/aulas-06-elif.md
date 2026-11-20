Aula 06 — elif (múltiplas condições)
Até agora, nossos programas tinham apenas duas possibilidades:
- if → se a condição for verdadeira.
- else → se não for verdadeira.
Mas e quando temos três ou mais possibilidades? É aí que entra o elif.

elif é uma abreviação de else if — ou seja, "senão, se".
1. Entendendo na prática
Imagine um programa que verifica a nota de um aluno:
- Nota 10 → Excelente!
- Nota 7 ou mais → Aprovado!
- Nota abaixo de 7 → Em recuperação.
Podemos escrever assim:
nota = 8if nota == 10:    print("Excelente!")elif nota >= 7:    print("Aprovado!")else:    print("Em recuperação.")



Como a nota é 8, o Python:
1. Verifica se a nota é igual a 10 → não.
2. Verifica se a nota é maior ou igual a 7 → sim.
3. Executa print("Aprovado!").
4. Ignora o restante das condições.
Resultado:
Aprovado!


2. Como funciona a estrutura?
if — verifica a primeira condição

↓ Se for falsa
elif — verifica outra condição

↓ Se todas forem falsas
else — executa a alternativa final


O Python verifica as condições de cima para baixo e executa apenas o primeiro bloco cuja condição seja verdadeira. Se nenhuma for verdadeira, executa o else, caso exista.
3. Outro exemplo: temperatura
Imagine um programa que analisa a temperatura:
temperatura = 30if temperatura >= 35:    print("Muito quente")elif temperatura >= 25:    print("Quente")elif temperatura >= 15:    print("Agradável")else:    print("Frio")



Como temperatura = 30, o resultado será:
Quente


Porque:
- 30 >= 35 → falso
- 30 >= 25 → verdadeiro → imprime "Quente"
- O restante nem precisa ser verificado.
