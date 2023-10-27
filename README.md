# Projeto 1 - Desenvolvimento de Game em linguagem Python

O intuito desse projeto é aplicar todo o conhecimento aprendido até o final da primeira etapa do curso "Fundamentos de Linguagem Python Para Análise de Dados e Data Science" para desenvolver um jogo em Python.

## Ferramenta utilizada

> Jupyter Notebook: 3.11.4

> Python (Random)

## Programa: Jogo da forca (Hangman)

O jogo da forca é um jogo de palavras em que uma palavra é escolhida e o jogador tenta adivinhar as letras dessa palavra, uma por uma, até adivinhar a palavra completa ou até cometer um número máximo de erros, geralmente representados por partes do corpo de uma pessoa forca. 

Para desenvolver o jogo da forca em código Python, foi primeiramente desenvolvido o pseudocódigo com seguintes passos:

1- Definir a lista de palavras possíveis

2- Escolher uma palavra aleatória da lista

3- Criar uma lista vazia para armazenar as letras adivinhadas

4- Definir o número máximo de tentativas permitidas

5- Enquanto o número de tentativas não atingir o limite máximo:
  
* Mostrar a palavra como uma série de underscores, com as letras adivinhadas preenchidas nos espaços corretos
* Pedir ao jogador que adivinhe uma letra
* Verificar se a letra adivinhada está na palavra
* Se a letra adivinhada está na palavra, adicionar a letra à lista de letras adivinhadas e atualizar a exibição da palavra
* Se a letra adivinhada não está na palavra, reduzir o número de tentativas restantes e exibir a mensagem "Letra incorreta. Tentativas restantes: [número de tentativas restantes]"
* Verificar se todas as letras da palavra foram adivinhadas
* Se todas as letras foram adivinhadas, exibir a mensagem "Você venceu!"
* Se o número de tentativas restantes chegar a zero, exibir a mensagem "Você perdeu. A palavra era [palavra escolhida]" e encerrar o jogo.


O arquivo com os códigos comentado segue em anexo neste diretório.
