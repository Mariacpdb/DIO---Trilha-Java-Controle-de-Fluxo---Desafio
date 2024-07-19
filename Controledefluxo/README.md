# Desafio de Controle de Fluxo - Java
Este projeto é um exercício prático para consolidar os conceitos de controle de fluxo em Java, desenvolvido como parte do módulo de Controle de Fluxo da DIO (Digital Innovation One).

## Descrição do Projeto
O sistema é projetado para receber dois números inteiros via terminal e realizar a impressão dos números incrementados com base na diferença entre esses dois números. Se o primeiro número for maior que o segundo, uma exceção customizada será lançada.

## Estrutura do Projeto
O projeto é composto por duas classes principais:

Contador.java: Classe responsável pela lógica de leitura dos parâmetros e execução do loop de contagem.
ParametrosInvalidosException.java: Classe que representa a exceção personalizada a ser lançada quando o primeiro parâmetro for maior que o segundo.
## Funcionalidades
Entrada de Dados: O sistema solicita dois números inteiros via terminal.
Validação: Verifica se o primeiro número é maior que o segundo, lançando uma exceção personalizada se a validação falhar.
Contagem: Realiza a contagem e imprime os números incrementados no console.
## Como Executar
Clone o repositório:
```java

git clone https://github.com/seu-usuario/Controledefluxo.git
````
Navegue até o diretório do projeto:
````java

cd Controledefluxo/src
````
Compile os arquivos Java:
````java

javac -d ../bin desafio/controlefluxo/*.java
````
Execute o programa:
````sh

java -cp ../bin desafio.controlefluxo.Contador
````
## Exemplo de Uso
Ao executar o programa, você será solicitado a inserir dois números inteiros:

````sh

Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
````
O sistema então imprimirá a seguinte saída:

````sh

Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
````

Se o primeiro número for maior que o segundo:

````sh

Digite o primeiro parâmetro
30
Digite o segundo parâmetro
12
````
O sistema lançará a seguinte exceção:

````sh

O segundo parâmetro deve ser maior que o primeiro
````
Autor
Maria Clara Palhares - GitHub

