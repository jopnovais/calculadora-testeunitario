
# Calculadora Simples em Java com Swing
Este é um projeto de uma calculadora simples desenvolvida em Java, que utiliza a biblioteca Swing (JOptionPane) para criar uma interface gráfica de usuário (GUI) interativa baseada em caixas de diálogo.

O programa permite ao usuário inserir dois números e, em seguida, escolher uma das quatro operações aritméticas básicas para executar através de um menu.

## ✨ Funcionalidades
Leitura de Dados: Permite que o usuário insira dois valores numéricos (valor A e valor B).

Operações Básicas: Realiza as seguintes operações:

Soma (A + B)

Subtração (A - B)

Multiplicação (A * B)

Divisão (A / B)

Menu Interativo: Um menu em loop permite que o usuário realize múltiplas operações sem reiniciar o programa.

Sair: Uma opção para encerrar a execução do programa de forma limpa.

## 🛠️ Pré-requisitos
Para compilar e executar este projeto, você precisará ter o Java Development Kit (JDK) instalado em sua máquina (versão 8 ou superior é recomendada).

## 🚀 Como Executar
Salve os Arquivos:
Crie dois arquivos em um mesmo diretório: Principal.java e Calculadora.java. Copie e cole o código fornecido em seus respectivos arquivos.

Abra um Terminal:
Abra um terminal ou prompt de comando e navegue até o diretório onde você salvou os arquivos.

Compile o Código:
Execute o seguinte comando para compilar os dois arquivos Java:

Bash

```
javac Principal.java Calculadora.java
```
Execute o Programa:
Após a compilação bem-sucedida, execute o programa com o comando:

Bash

```
java Principal
```
O programa iniciará e a primeira caixa de diálogo com o menu de opções será exibida.

## 📂 Estrutura do Código
O projeto é dividido em duas classes principais, seguindo princípios básicos de orientação a objetos.

Calculadora.java
Esta classe é o "cérebro" da aplicação. Ela é responsável por:

Armazenar os dois valores (valorA e valorB) em atributos privados.

Fornecer os métodos que realizam os cálculos matemáticos (getSoma(), getDiferenca(), getProduto(), getQuociente()).

Encapsular a lógica de negócio, separando-a da interface do usuário.

Principal.java
Esta é a classe de entrada (main) do programa. Suas responsabilidades são:

Gerenciar o fluxo de execução e o loop do menu.

Interagir com o usuário através de caixas de diálogo (JOptionPane).

Instanciar um objeto da classe Calculadora.

Chamar os métodos de cálculo da classe Calculadora e exibir os resultados para o usuário.