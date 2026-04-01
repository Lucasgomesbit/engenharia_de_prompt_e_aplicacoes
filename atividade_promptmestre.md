Atividade – Prompt Mestre em Programação de Computadores 

Tema: Listas e Análise de Dados 

Prompt Mestre Inicial 

"Escreva um programa em Python que receba uma lista de números e calcule a média dos valores." 

Variação 1 

"Escreva o programa em Python e explique passo a passo como funciona."  

numeros = [10, 20, 30, 40, 50] 
 
soma = sum(numeros) 
quantidade = len(numeros) 
media = soma / quantidade 
 
print("A média é:", media) 

Explicação passo a passo: 

Criamos uma lista chamada numeros com alguns valores.  

Usamos sum() para somar todos os elementos da lista.  

Usamos len() para contar quantos números existem na lista.  

Dividimos a soma pela quantidade para obter a média.  

Exibimos o resultado com print().  

 

Variação 2 

"Otimize o programa em Python usando compreensão de listas." 
Resposta do LLM: 

numeros = [10, 20, 30, 40, 50] 
 
media = sum([n for n in numeros]) / len(numeros) 
 
print("A média é:", media) 

 

Variação 3 

"Explique o programa em linguagem simples, como se fosse para um iniciante." 
Resposta do LLM: 
Esse programa pega vários números guardados em uma lista e calcula a média deles. 

Primeiro, ele soma todos os números. Depois, conta quantos números existem. 
Por fim, divide a soma pela quantidade — isso é exatamente o que fazemos para descobrir a média. 

Por exemplo: se você tem 5 números, soma todos e divide por 5. 

 

Reflexão 

Nessa atividade, foi possível aprender como trabalhar com listas em Python e realizar cálculos básicos como a média. Também foi interessante ver que existem diferentes formas de escrever o mesmo programa, como usando compreensão de listas para deixar o código mais compacto. Além disso, adaptar a explicação para iniciantes ajuda a reforçar o entendimento do conteúdo. 
