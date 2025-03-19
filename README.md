# Super Trunfo - Cidades do Rio de Janeiro

Este projeto é uma implementação do jogo **Super Trunfo**, onde as cartas são representadas por **cidades do Rio de Janeiro**. O jogo compara diferentes propriedades das cidades e decide um vencedor com base em critérios como **densidade populacional**, **PIB**, **número de pontos turísticos** e o **super poder** (soma das propriedades).

## Funcionalidades

O projeto está dividido em três níveis:

### Nível Novato
- Cadastro das cartas, onde o usuário insere informações sobre cada cidade do Rio de Janeiro.
- As informações inseridas são armazenadas em um sistema e exibidas para o usuário.

### Nível Aventureiro
- Adição de propriedades calculadas:
  - **Densidade Populacional**: População dividida pela área da cidade.
  - **PIB per Capita**: PIB total dividido pela população.
  
### Nível Mestre
- Comparação entre duas cidades com base nas propriedades cadastradas e calculadas.
- Determinação do vencedor em cada categoria:
  - **Densidade Populacional**: Vence a carta com a menor densidade populacional.
  - **PIB**: Vence a carta com o maior PIB.
  - **Pontos Turísticos**: Vence a carta com mais pontos turísticos.
  - **Super Poder**: A soma de todas as propriedades, vence a carta com maior super poder.

## Como Executar

### Requisitos

- **C**: O código foi escrito em C. Você precisará de um compilador para rodá-lo. Recomendamos o [GCC](https://gcc.gnu.org/).

### Compilação e Execução

1. **Baixe o repositório**:
   - Clique no botão **"Code"** e depois em **"Download ZIP"**, ou clone o repositório com o comando:
     ```bash
     git clone https://github.com/SEU_USUARIO/SuperTrunfo-RJ.git
     ```

2. **Compile o código**:
   - Se você está usando o GCC, basta rodar o comando:
     ```bash
     gcc super_trunfo_rj.c -o super_trunfo
     ```

3. **Execute o programa**:
   - No terminal, execute:
     ```bash
     ./super_trunfo
     ```

4. **Interaja com o programa**:
   - O programa irá pedir que você insira dados sobre as cidades do Rio de Janeiro (nome, população, PIB, pontos turísticos).
   - Após inserir as cidades, você poderá comparar duas delas e ver qual é a vencedora de acordo com as propriedades.

## Estrutura do Projeto

- **super_trunfo_rj.c**: Código principal com a lógica de cadastro, cálculo e comparação das cidades.
- **README.md**: Documentação deste projeto.

## Próximos Passos

- Implementação de mais funcionalidades, como um sistema de **rankings** para as cidades.
- Melhorias na interface, como uma interface gráfica (GUI) ou um menu mais interativo.
- Expansão para outras cidades além do Rio de Janeiro, com a inclusão de mais propriedades e dados.

## Contribuições

Sinta-se à vontade para fazer contribuições! Se você tem sugestões de melhorias ou encontrou um bug, crie uma **issue** ou envie um **pull request**.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
