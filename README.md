# Desenhador 2D em C

## Descrição do Projeto

Este projeto consiste em um sistema de desenho bidimensional desenvolvido em linguagem C, que permite ao usuário criar e manipular elementos gráficos em uma matriz (canvas) representada no terminal.

O programa simula um ambiente de desenho simples, onde é possível inserir formas, linhas ou pontos em um plano 2D, utilizando estruturas de dados e lógica de programação para controlar posições e renderização.

O objetivo principal é aplicar conceitos fundamentais de programação e estruturas de dados na construção de um sistema interativo.

---

## Funcionalidades

* Criação de um plano 2D (matriz)
* Inserção de elementos gráficos em posições específicas
* Exibição do desenho no terminal
* Atualização dinâmica do conteúdo da matriz
* Interação com o usuário por meio de menu ou comandos

---

## Funcionamento

O programa mantém uma estrutura de dados (geralmente uma matriz) que representa o espaço de desenho.

Fluxo básico:

1. Inicialização da área de desenho
2. Entrada de comandos pelo usuário
3. Atualização da matriz conforme a ação escolhida
4. Exibição do estado atual do desenho

Cada posição da matriz pode armazenar um caractere que representa um elemento visual (por exemplo: `*`, `#`, `.`).

---

## Exemplos de Execução

### Exemplo de saída:

```
. . . . .
. . * . .
. * * * .
. . * . .
. . . . .
```

---

### Exemplo de interação:

```
1 - Inserir ponto
2 - Desenhar linha
3 - Mostrar desenho
4 - Sair
Escolha: 1

Digite a posição (x y): 2 2
```

---

## Observações Importantes

* O desenho é feito em modo texto (terminal)
* A matriz possui tamanho fixo definido no código
* Não há interface gráfica (GUI), apenas representação textual
* O sistema depende da entrada correta do usuário
* O projeto reforça lógica de manipulação de coordenadas

---

## Conceitos Praticados

* Matrizes (arrays bidimensionais)
* Estruturas de controle
* Modularização de código
* Entrada e saída de dados
* Manipulação de coordenadas
* Lógica de renderização em terminal
