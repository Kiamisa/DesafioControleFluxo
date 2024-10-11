# DesafioControleFluxo

Este projeto é uma aplicação simples em Java que demonstra o uso de controle de fluxo, leitura de parâmetros via terminal e lançamento de exceções customizadas. Ele foi desenvolvido como parte de um exercício prático para explorar conceitos importantes de programação orientada a objetos e manipulação de exceções em Java.
# 🛠 Estrutura do Projeto

## O projeto é composto por duas classes principais:

- Contador.java:
        Contém a lógica principal do programa.
        Realiza a leitura de dois números inteiros fornecidos via terminal.
        Implementa uma contagem progressiva entre os dois números fornecidos.
- ParametrosInvalidosException.java:
        Define uma exceção customizada.
        Lançada quando os parâmetros fornecidos pelo usuário não atendem aos critérios, como o primeiro número ser maior que o segundo.

# 🚀 Funcionalidades

- Leitura de Parâmetros via Terminal:
        O programa lê dois números inteiros fornecidos pelo usuário como argumentos de linha de comando.
- Contagem Progressiva:
        A partir dos dois números fornecidos, o programa calcula a diferença e realiza uma contagem, exibindo números incrementados no terminal.
- Tratamento de Exceções:
        Se o primeiro número for maior que o segundo, uma exceção customizada (ParametrosInvalidosException) é lançada para indicar o erro.

# ⚙️ Como Executar
## Pré-requisitos

Java 17 ou superior instalado na sua máquina.
Configuração de variáveis de ambiente para executar o Java via terminal.

## Passos

Clone este repositório em sua máquina local:

```bash

git clone https://github.com/SeuUsuario/DesafioControleFluxo.git
```
Compile o projeto:

```bash

javac Contador.java
```
Execute o programa, passando os dois números inteiros como parâmetros:

```bash

java Contador 3 8
```
Exemplo de saída:

```bash

3
4
5
6
7
8
```
Se o primeiro número for maior que o segundo, será exibida uma mensagem de erro devido à exceção:

```bash

java Contador 8 3
```
Saída esperada:

```bash

    ParametrosInvalidosException: O segundo número deve ser maior que o primeiro.
```
🧪 Testes

Para testar o comportamento da aplicação, passe diferentes combinações de números inteiros e observe o resultado.
📁 Estrutura de Pastas
```
├── src
│   ├── Contador.java
│   └── ParametrosInvalidosException.java
└── README.md
```
