

# Projeto de API RESTful com Spring Boot
Este projeto é uma API RESTful desenvolvida em Java com o framework Spring Boot, dedicada ao gerenciamento completo de um sistema de e-commerce. A API oferece funcionalidades robustas para criar, atualizar, ler e excluir produtos através de endpoints HTTP, proporcionando uma integração flexível e eficiente com aplicações cliente.

##  Objetivo
O principal objetivo deste projeto é exemplificar a criação de uma API moderna e escalável utilizando tecnologias avançadas. A aplicação utiliza Java 17 para aproveitar as últimas melhorias da linguagem, enquanto o Spring Boot 3 simplifica o desenvolvimento ao oferecer configuração automática e produtividade elevada. A integração com o Spring Data JPA facilita o acesso e manipulação de dados em um banco de dados relacional, garantindo alta performance e confiabilidade.

# Funcionalidades Principais
+ Gerenciamento de Produtos: Operações completas de CRUD para produtos, permitindo criar novos produtos, visualizar detalhes específicos, atualizar informações existentes e remover produtos do sistema.
+ Documentação Automática: Utilização do Swagger (OpenAPI) para gerar documentação interativa da API. Isso facilita a compreensão dos endpoints disponíveis, seus parâmetros e respostas esperadas, simplificando o processo de integração para desenvolvedores externos.
+ Arquitetura Modular: Estrutura organizada em pacotes (controller, service, repository) para uma separação clara de responsabilidades e facilitar a manutenção do código ao longo do tempo.
+ Configuração Flexível: Utilização de arquivos de configuração do Spring Boot para personalizar o comportamento da aplicação, como configurações de banco de dados, segurança e propriedades específicas do ambiente.

# Tecnologias Utilizadas
+ Java 17: Versão mais recente da linguagem Java, oferecendo melhorias significativas em desempenho, segurança e funcionalidades.
+ Spring Boot 3: Framework baseado em Spring que simplifica o desenvolvimento de aplicações Java, fornecendo recursos avançados de autoconfiguração e facilitando a criação de APIs RESTful.
+ Spring Data JPA: Abstração de acesso a dados que simplifica a integração com bancos de dados relacionais, permitindo operações CRUD de forma eficiente.
+ Swagger (OpenAPI): Ferramenta poderosa para documentação automática de APIs, gerando uma interface interativa para explorar e testar os endpoints disponíveis.
+ Git e GitHub: Utilização de controle de versão distribuído e hospedagem de código-fonte no GitHub para colaboração e compartilhamento do projeto.
+ Postman: Ferramenta para testar requisições HTTP e verificar o funcionamento da API durante o desenvolvimento e testes.

# Estrutura do Projeto
O projeto segue uma estrutura organizada em módulos e camadas para melhor gerenciamento e escalabilidade:

+ com.example.ecommerce.controller: Controladores que recebem as requisições HTTP e delegam o processamento para os serviços correspondentes.
+ com.example.ecommerce.service: Serviços que implementam a lógica de negócio da aplicação, encapsulando operações sobre os dados e aplicando regras de negócio.
+ com.example.ecommerce.model: Modelos de dados que representam entidades como Product, definindo suas propriedades e comportamentos.
+ com.example.ecommerce.repository: Repositórios que abstraem o acesso ao banco de dados utilizando Spring Data JPA, permitindo consultas e atualizações eficientes.

# Como Usar
Para utilizar o projeto, siga estes passos:

+ Clone o Repositório: Clone este repositório para sua máquina local utilizando o Git.
+ Configuração do Ambiente: Certifique-se de ter o Java 17 e o Maven configurados corretamente em sua máquina.
+ Compilação e Execução: Compile o projeto com Maven e execute a aplicação Spring Boot.
+ Teste a API: Utilize ferramentas como Postman para enviar requisições HTTP para a API e verificar seu funcionamento.
+ Documentação: Acesse a documentação da API gerada automaticamente pelo Swagger para explorar os endpoints disponíveis e entender seus parâmetros e respostas.

# Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas para discutir melhorias ou enviar pull requests com novas funcionalidades para o projeto.
