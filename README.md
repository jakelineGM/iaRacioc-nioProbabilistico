# Trabalho de Raciocínio Probabilístico

Este repositório contém a implementação de um sistema de diagnóstico para um farol de bicicleta movido a dínamo usando uma rede bayesiana, como parte do curso de Inteligência Artificial.

## Descrição do Trabalho

O trabalho consiste em duas partes principais:

1. **Criação de uma Rede Bayesiana**
    - Desenhar a rede de causalidade entre as variáveis.
    - Inserir as Tabelas de Probabilidades Condicionais (CPTs).
    - Atribuir valores plausíveis para as probabilidades.
    - Demonstrar que a rede não contém uma aresta específica.
    - Calcular a probabilidade de uma variável dada uma condição específica.

2. **Implementação em ProbLog**
    - Implementar a rede bayesiana descrita em Prolog.
    - Calcular a probabilidade usando evidências fornecidas.

## Estrutura do Repositório

- `bayesian_network.pl`: Arquivo Prolog contendo a implementação da rede bayesiana e a consulta para cálculo da probabilidade.

## Como Usar

### Requisitos

- [SWI-Prolog](https://www.swi-prolog.org/) ou [ProbLog](https://dtai.cs.kuleuven.be/problog/) para executar o código Prolog.

### Executando o Código Prolog

1. Clone este repositório:
    ```sh
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    cd nome-do-repositorio
    ```

2. Abra o arquivo `bayesian_network.pl` em seu ambiente Prolog e execute a consulta:
    ```prolog
    ?- [bayesian_network].
    ?- query(v).
    ```
