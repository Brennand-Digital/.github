# 📌 Brennand Digital

## 📖 Sobre o Projeto
O **Sistema de Gestão de Visitantes** é um software desenvolvido em **Java** com o objetivo de facilitar o gerenciamento de informações dos visitantes.  

A aplicação tem como propósito fornecer uma solução simples, mas extensível, que poderá evoluir para incluir relatórios, integração com banco de dados e interface gráfica/web.

---

# 🚀 Entrega 1

### ✅ Escopo da Primeira Entrega
- Criação do **repositório no GitHub**.  
- Estrutura inicial do **README**.  
- Definição das **tecnologias a serem usadas** (Java, Trello, GitHub).  
- Criação do **quadro no Trello** para organizar as tarefas.  
- Prototipação inicial no **Figma**.

### 📌 Links
- **Figma:**  
  https://www.figma.com/design/5gw7g03K3NlFqpk4N44rt2/Brennand?node-id=0-1&p=f&t=jmqIZNbSJJSAi7aO-0  

  Histórias adicionadas:
  1°: Como usuário quero visualizar a home do site
  <img width="643" height="487" alt="image" src="https://github.com/user-attachments/assets/f6692a1e-08f2-4da1-ae29-ca0894771688" />
  
  2°: Como usuário quero ver as exposições do parque das esculturas
 <img width="250" height="498" alt="image" src="https://github.com/user-attachments/assets/690e2420-f441-4caf-b084-c8ebd6cd15b9" />

  3°: Como usuário gostaria de fazer login
  
 <img width="275" height="491" alt="image" src="https://github.com/user-attachments/assets/d83199d9-2551-4e00-b317-c77df906ccb7" />




- **Trello:**  
  https://trello.com/b/qq7pibmx/projetos-3

- ### 🎥 Screencast
- https://youtu.be/aLnS4tEiyCQ?si=iAgWqq4Dm9YmjAV7

---

# 🚀 Entrega 2

### ✅ Escopo da Segunda Entrega
- Desenvolvimento do **protótipo funcional em Java**.  
- Implementação das 2 histórias:
  **funcionalidades de cadastro** dentro do epico de comunicação no trello
  **Post/Get/Put/Delete/ de avisos** dentro do epico de comunicação no trello.  
- Documentação das instruções de execução.  
- Criação de um **screencast** mostrando o funcionamento do sistema.


- **Trello:**  
  https://trello.com/b/qq7pibmx/projetos-3

### 🎥 Screencast
https://youtu.be/ihUTc0tN9rY?si=IWaE20GcxCAhbUJt  

### 🛠 Tecnologias Utilizadas
- <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />  
- <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />  
- <img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white" />  

---


# 🚀 Entrega 3

### ✅ Escopo da Terceira Entrega
- Desenvolvimento do **protótipo funcional em Java**.  
- Implementação de mais 2 histórias:
  **funcionalidades de Login** dentro do epico de comunicação no trello
  **Segurança de Senha e Busca de Usuário** dentro do epico de comunicação no trello.
- Criação de Testes Automatizados  
- Criação de um **screencast** mostrando o funcionamento do sistema.



- **Trello:**  
  https://trello.com/b/qq7pibmx/projetos-3
  
### 🎥 Screencast
https://youtu.be/uiHuE2oqbjA

---


# 🚀 Entrega 4

### ✅ Escopo da Terceira Entrega
- Desenvolvimento do **protótipo funcional em Java**.  
- Implementação de mais 3 histórias:
- **Delete de Avisos pelo Id** 
  **Get de Avisos pelo Id** 
  **Get/Put/Delete/ de Usuário pelo Id**
- Criação de Testes Automatizados  
- Criação de um **screencast** mostrando o funcionamento do sistema.



- **Trello:**  
  https://trello.com/b/qq7pibmx/projetos-3
  
### 🎥 Screencast
https://youtu.be/uiHuE2oqbjA

# 👨‍💻 Como Executar o Projeto

Para rodar este projeto localmente, siga os passos abaixo.

## 1. Pré-requisitos

Para rodar o projeto, você precisará ter as seguintes ferramentas instaladas em sua máquina. Seja bem descritivo e verifique se as versões mínimas são atendidas.

Ferramenta
Java Development Kit (JDK) 17
O projeto é construído em Java e requer o ambiente de desenvolvimento e a máquina virtual (JVM) para compilar e executar.

Apache Maven v3.6+

Gerenciador de dependências e ferramenta de build do projeto. Responsável por baixar bibliotecas e empacotar a aplicação.

Git v2.0+
Sistema de controle de versão para clonar o repositório.

PostgreSQL v10+
O projeto utiliza este banco de dados relacional para persistência de dados e migrações Flyway.

Cliente API
Postman, Insomnia ou cURL
Necessário para testar os endpoints da API após a execução.


2. Configuração do Banco de Dados PostgreSQL

O projeto espera se conectar a uma instância do PostgreSQL.

2.1. Criação do Banco de Dados

Abra o terminal do seu PostgreSQL (ou use uma ferramenta como pgAdmin) e execute o seguinte comando SQL para criar o banco de dados:

CREATE DATABASE brennand_db;

2.2. Configuração do Projeto

O projeto utiliza o arquivo application.properties para as configurações de conexão.

1.
Localize o arquivo: backend/src/main/resources/application.properties

2.
Edite as seguintes linhas para corresponderem às suas credenciais locais do PostgreSQL.

# Configuração do Banco de Dados PostgreSQL
spring.datasource.url=jdbc:postgresql://localhost:5432/brennand_db
spring.datasource.username=seu_usuario_postgres
spring.datasource.password=sua_senha_postgres

# Configuração do Flyway (Migrações de Banco de Dados)
spring.flyway.enabled=true
spring.flyway.locations=classpath:db/migration


Atenção: Substitua seu_usuario_postgres e sua_senha_postgres pelas credenciais que você utiliza para acessar o PostgreSQL.

3. Clonagem e Execução do Projeto

Siga os comandos no terminal para clonar, compilar e executar a aplicação.

3.1. Clonagem do Repositório

Bash

# Comando para clonar o repositório
git clone https://github.com/Brennand-Digital/backend

# Navegue para o diretório raiz do projeto
cd backend

# Navegue para o subdiretório do módulo principal (onde está o pom.xml )
cd backend

3.2. Compilação e Execução

Utilize o Maven para compilar o projeto e rodar a aplicação Spring Boot.

Bash


# 1. Compilar o projeto e baixar as dependências
# O comando 'clean install' garante que o projeto será reconstruído do zero
mvn clean install

# 2. Executar a aplicação Spring Boot
# O comando 'spring-boot:run' inicia o servidor embutido (Tomcat)
mvn spring-boot:run


O servidor será iniciado na porta padrão (geralmente 8080). Você verá uma mensagem no console indicando que a aplicação Spring Boot foi iniciada com sucesso.

4. Testando a API

Com o servidor rodando, você pode testar as funcionalidades (endpoints) usando o Postman, Insomnia ou cURL.

Exemplo de Teste (Login):

•
Método: POST

•
URL: http://localhost:8080/auth/login

•
Corpo (Body ) - JSON:

---

## 👥 Nossa Equipe

- David Alves
- Gabriel Calado
- Eduardo de Medeiros Rocha
- Rafael Gomes
- Pedro Gomes
- Ravi Barbosa

