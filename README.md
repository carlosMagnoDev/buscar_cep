# Buscador de CEP em Java

Este é um projeto de um buscador de CEP desenvolvido em Java, utilizando o framework Window Builder e as bibliotecas Atxy2 e dom4j. O objetivo deste buscador é permitir que o usuário informe um CEP e obtenha as informações relacionadas a ele, como rua, bairro, cidade e estado.

## Funcionalidades

- Buscar informações de um CEP específico
- Exibir os dados encontrados, incluindo rua, bairro, cidade e estado
- Tratamento de erros para CEPs inválidos ou não encontrados
- Interface gráfica intuitiva desenvolvida com o auxílio do Window Builder

## Tecnologias utilizadas

- Java
- Window Builder
- Atxy2 framework
- dom4j library

## Configuração

Certifique-se de ter o Java JDK (Java Development Kit) instalado em sua máquina.

1. Faça o clone deste repositório para o seu ambiente local.
2. Importe o projeto em sua IDE de preferência.
3. Certifique-se de que as bibliotecas Atxy2 e dom4j estejam adicionadas ao classpath do projeto.

## Como usar

1. Digite o CEP desejado no campo de busca.
2. Clique no botão "Buscar".
3. As informações relacionadas ao CEP serão exibidas na interface gráfica.
4. Caso o CEP seja inválido ou não seja encontrado, uma mensagem de erro será exibida.

## Fonte de dados

O projeto utiliza a API do República Virtual para acessar as informações relacionadas aos CEPs. Acesse o link [Exemplos](https://www.republicavirtual.com.br/cep/exemplos.php#exXML) para obter mais informações sobre o formato XML dos dados retornados pela API.

## Contribuição

Contribuições para este projeto são bem-vindas! Sinta-se à vontade para abrir issues relatando problemas, propor melhorias ou enviar pull requests com novos recursos.

