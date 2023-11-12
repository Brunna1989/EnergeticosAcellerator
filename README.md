# Sistema de Entregas com Cálculos de Impostos

## Tecnologias Utilizadas

- Java
- Lombok
- Maven

## Descrição

Este projeto simula um sistema de entregas de mercadorias, calculando os impostos (ICMS, IPI, PIS, COFINS) sobre o valor total das entregas.

## Estrutura do Projeto

- `entrega/Entrega.java`: Define a estrutura das entregas.
- `application/Application.java`: Classe principal que interage com o usuário e realiza os cálculos.
- `pom.xml`: Arquivo de configuração do Maven.

## Como Executar o Projeto

Certifique-se de ter o Java instalado e seguir os passos abaixo:

1. Clone o repositório.
2. Abra o terminal na pasta do projeto.
3. Execute o comando `mvn clean install` para baixar as dependências e compilar o projeto.
4. Execute o comando `java -jar target/teste-1.0-SNAPSHOT.jar` para rodar o programa.

## Como Utilizar o Programa

1. O programa solicitará o nome e a quantidade de produtos para dois estabelecimentos.
2. Os valores totais e os impostos de cada entrega serão calculados e exibidos.
3. Ao final, o programa mostrará o total de impostos, o total das mercadorias e o total geral.

## Observações

- Este projeto é um exemplo educacional.
- Certifique-se de ajustar as quantidades e valores conforme necessário no arquivo `application/Application.java`.

