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
  **Delete de Avisos pelo Id**
  
  **Get de Avisos pelo Id**
  
  **Get/Put/Delete/ de Usuário pelo Id**
- Criação de Testes Automatizados  
- Criação de um **screencast** mostrando o funcionamento do sistema.



- **Trello:**  
  https://trello.com/b/qq7pibmx/projetos-3
  
### 🎥 Screencast
https://youtu.be/uiHuE2oqbjA

---

## ✔ Pré-requisitos

-   JDK 17\
-   Maven 3.6+\
-   PostgreSQL 10+\
-   Git 2.0+\
-   Postman/Insomnia/cURL

## 🗄 Configuração do Banco de Dados

``` sql
CREATE DATABASE brennand_db;
```

Edite `application.properties` com suas credenciais.

## 📥 Clonagem e Execução

``` bash
git clone https://github.com/Brennand-Digital/backend
cd backend/backend

mvn clean install
mvn spring-boot:run
```

## 🧪 Testando a API no Postman

**POST** `http://localhost:8080/auth/login`

``` json
{
  "email": "seu_email@example.com",
  "password": "sua_senha"
}
```

## 📁 Estrutura

    backend/
     ├── src/
     ├── pom.xml
     └── README.md

## 🤝 Como Contribuir

1.  Fork\
2.  Criar branch\
3.  Commit\
4.  Push\
5.  Pull Request
---

## 👥 Nossa Equipe

- David Alves
- Gabriel Calado
- Eduardo de Medeiros Rocha
- Rafael Gomes
- Pedro Gomes
- Ravi Barbosa

