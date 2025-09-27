Super Trunfo de Países – Cadastro de Cartas

📌 Descrição

Esse é o meu primeiro projeto em C para a faculdade, onde desenvolvi a primeira etapa de um jogo no estilo Super Trunfo.
O objetivo dessa parte foi criar um programa que permite o cadastro de duas cartas, cada uma representando uma cidade, e depois mostrar os dados na tela de forma organizada.

Cada carta tem os seguintes dados:

Estado (A até H)

Código da carta (a letra do estado + número de 01 a 04, por exemplo A01 ou B03)

Nome da cidade

População

Área em km²

PIB (em bilhões de reais)

Número de pontos turísticos

No final, o programa mostra tudo o que foi digitado pelo usuário.

⚙️ O que o programa faz

Cadastra duas cartas.

Lê os dados digitados pelo usuário.

Armazena em variáveis.

Exibe todos os dados de forma clara e formatada.

Foi feito exatamente como pedido: sem laços (for, while) e sem condições (if, else).

🛠️ Tecnologias usadas

Linguagem C

Compilador GCC (ou outro compatível)

▶️ Como compilar e executar

Para compilar o programa:

gcc super_trunfo.c -o super_trunfo

Para executar:

./super_trunfo

📖 Exemplo de uso

Abaixo um exemplo de como eu digitei no console:

Cadastro da Carta 1:
Digite o estado (A-H): A
Digite o codigo da carta (ex: A01): A01
Digite o nome da cidade: São Paulo
Digite a populacao: 12325000
Digite a area em km²: 1521.11
Digite o PIB (em bilhoes de reais): 699.28
Digite o numero de pontos turisticos: 50

Cadastro da Carta 2:
Digite o estado (A-H): B
Digite o codigo da carta (ex: B02): B02
Digite o nome da cidade: Rio de Janeiro
Digite a populacao: 6748000
Digite a area em km²: 1200.25
Digite o PIB (em bilhoes de reais): 300.50
Digite o numero de pontos turisticos: 30

E a saída que o programa mostra é:


Carta 1:
Estado: A
Codigo: A01
Nome da Cidade: São Paulo
Populacao: 12325000
Area: 1521.11 km²
PIB: 699.28 bilhoes de reais
Numero de Pontos Turisticos: 50

Carta 2:
Estado: B
Codigo: B02
Nome da Cidade: Rio de Janeiro
Populacao: 6748000
Area: 1200.25 km²
PIB: 300.50 bilhoes de reais
Numero de Pontos Turisticos: 30
