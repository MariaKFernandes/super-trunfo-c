Super Trunfo - Batalha de Cartas com Super Poder

Este projeto implementa um jogo de Super Trunfo em C, onde os jogadores comparam cartas de cidades, com base em diferentes atributos, para determinar qual carta é superior. As cartas incluem informações como população, área, PIB, pontos turísticos, entre outras.


Funcionalidades Implementadas
Níveis do Jogo:
Cadastro das Cartas: O usuário pode inserir os dados de duas cartas, incluindo:

Nome da cidade
População
Área
PIB
Pontos Turísticos
Cálculos Adicionais:

Densidade Populacional: Calculada como a razão entre a população e a área da cidade.
PIB per Capita: Calculado como o PIB dividido pela população da cidade.
Super Poder: O super poder é calculado somando todos os atributos numéricos e aplicando um valor inverso na densidade populacional (quanto menor a densidade, maior o poder). A fórmula do Super Poder é:
java
Copiar
Editar
Super Poder = População + Área + PIB + Pontos Turísticos + (1 / Densidade Populacional) + PIB per Capita
Comparação das Cartas:

As cartas são comparadas atributo por atributo, incluindo:
População (maior valor vence)
Área (maior valor vence)
PIB (maior valor vence)
Pontos Turísticos (maior valor vence)
Densidade Populacional (menor valor vence)
PIB per Capita (maior valor vence)
Super Poder (maior valor vence)
Exibição dos Resultados:

Após comparar todos os atributos, o programa exibe o vencedor de cada comparação.
No final, o programa mostra quem venceu no total, considerando o número de vitórias em cada atributo comparado.
Exemplo de Execução
bash
Copiar
Editar
Insira os dados para a Carta 1:
Nome: Cidade A
População: 1000000
Área (em km²): 500.5
PIB: 100000000
Pontos Turísticos: 15

Insira os dados para a Carta 2:
Nome: Cidade B
População: 1200000
Área (em km²): 600.3
PIB: 120000000
Pontos Turísticos: 20

Comparação de Cartas:
População: Carta 2 venceu
Área: Carta 1 venceu
PIB: Carta 1 venceu
Pontos Turísticos: Carta 1 venceu
Densidade Populacional: Carta 1 venceu
PIB per Capita: Carta 2 venceu
Super Poder: Carta 1 venceu

Carta 1 venceu no total com 4 vitórias!
Como Jogar
Compile o código em C utilizando um compilador C, como o gcc.
Execute o programa no terminal.
Insira os dados das duas cartas que deseja comparar.
O programa exibirá os vencedores de cada atributo e o vencedor geral da rodada.
Requisitos
Compilador C (gcc ou similar)
Sistema operacional: Funciona em sistemas Linux e Windows.
Como Contribuir
Faça um fork deste repositório.
Crie uma branch com suas alterações (git checkout -b minha-feature).
Faça o commit das suas alterações (git commit -m 'Adicionando nova funcionalidade').
Envie suas alterações para o repositório remoto (git push origin minha-feature).
Crie um pull request.

Dicas:
Atualizações: Como você fez algumas alterações no código, é bom destacar isso no README, como fiz acima.
Exemplo de Execução: Inclua sempre um exemplo de como o jogo se comporta após a atualização, para que quem for usar o código saiba o que esperar.
Instruções de Compilação: Certifique-se de que o repositório contenha instruções de compilação claras.
