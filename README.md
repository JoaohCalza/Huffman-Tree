# Implementação da Árvore de Huffman em C++

Este projeto implementa a compressão de dados usando a árvore de Huffman em C++. O código lê um arquivo de texto, constrói a árvore de Huffman, gera uma tabela de códigos e calcula a taxa de compactação.

## Funcionalidades

- **Leitura de Arquivo**: Calcula a frequência dos caracteres em um arquivo de texto.
- **Construção da Árvore de Huffman**: Cria uma árvore de Huffman com base nas frequências.
- **Geração de Tabela de Códigos**: Cria uma tabela de códigos Huffman para cada caractere.
- **Exibição da Árvore de Huffman**: Mostra a árvore usando uma estrutura de árvore binária de busca (BST).
- **Cálculo da Taxa de Compactação**: Calcula e exibe a taxa de compactação em relação ao tamanho original do arquivo.

## Como Funciona

1. **Leitura do Arquivo**: A função `lerArquivo` lê um arquivo e calcula a frequência de cada caractere.
2. **Construção da Árvore de Huffman**: A função `construirHuffman` cria a árvore com base nas frequências.
3. **Geração da Tabela de Códigos**: A função `gerarTabela` cria uma tabela de códigos binários para os caracteres.
4. **Exibição**: A função `exibirArvoreHuffman` mostra a árvore e a tabela de códigos.
5. **Taxa de Compactação**: A função `calcularCompactacao` calcula a eficiência da compactação.

## Observações

- O código lida com caracteres Unicode (`wchar_t`).
- A memória alocada dinamicamente para a árvore não é liberada no código atual.

