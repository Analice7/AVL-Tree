# Árvore AVL

Este projeto consiste em uma implementação de árvore AVL em linguagem C, incluindo operações de inserção, remoção e rotações para manter o balanceamento da árvore.

## Funcionalidades

- **Inserção de elementos**: Adiciona um novo valor à árvore AVL, garantindo que a estrutura continue balanceada.
- **Remoção de elementos**: Remove um valor específico da árvore, realizando as rotações necessárias para manter o balanceamento.
- **Rotações**:
  - Rotação Simples à Esquerda
  - Rotação Simples à Direita
  - Rotação Dupla à Esquerda
  - Rotação Dupla à Direita

## Estrutura do Projeto

O projeto contém os seguintes arquivos:

- `avl.h` - Arquivo de cabeçalho contendo a definição da estrutura da árvore AVL e as assinaturas das funções.
- `avl.c` - Implementação das funções de manipulação da árvore AVL.
- `main.c` - Arquivo principal para testes das funções.

## Como Compilar e Executar

Para compilar o programa, utilize o GCC:

```bash
gcc -o avl main.c avl.c
```

Para executar:

```bash
./avl
```

