# DesafioControleFluxo

## Descrição
Este projeto é uma aplicação Java que recebe dois parâmetros inteiros via terminal. A aplicação imprime uma sequência de números incrementados com base na diferença entre os dois parâmetros. Se o primeiro parâmetro for maior que o segundo, uma exceção customizada chamada `ParametrosInvalidosException` será lançada.

## Propósito Educacional
Este projeto foi criado para fins de aprendizado pessoal. Ele demonstra conceitos básicos de entrada e saída de dados no terminal, exceções personalizadas, e lógica de controle de fluxo em Java. É uma ótima prática para iniciantes que desejam melhorar suas habilidades em programação Java.

## Pré-requisitos
- Java JDK 8 ou superior
- Um terminal ou IDE para executar o programa

## Como compilar e executar

### Compilação
1. Abra o terminal e navegue até o diretório `DesafioControleFluxo/src`.
    ```sh
    cd DesafioControleFluxo/src
    ```
2. Compile os arquivos `.java`:
    ```sh
    javac -d ../bin *.java
    ```

### Execução
1. Navegue até o diretório `bin`:
    ```sh
    cd ../bin
    ```
2. Execute o programa:
    ```sh
    java Contador
    ```

## Uso
Ao executar o programa, você será solicitado a inserir dois números inteiros:

- **Parâmetro 1**: O primeiro número inteiro.
- **Parâmetro 2**: O segundo número inteiro, que deve ser maior que o primeiro.
