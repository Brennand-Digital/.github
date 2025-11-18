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

✔ Pré-requisitos

Antes de iniciar, instale as ferramentas:

Ferramenta	Versão mínima
JDK	17
Maven	3.6+
PostgreSQL	10+
Git	2.0+
Cliente API	Postman, Insomnia ou cURL
🗄 Configuração do Banco de Dados
1. Criando o banco
CREATE DATABASE brennand_db;

2. Configurando o application.properties

Edite:

backend/src/main/resources/application.properties

spring.datasource.url=jdbc:postgresql://localhost:5432/brennand_db
spring.datasource.username=SEU_USUARIO
spring.datasource.password=SUA_SENHA

spring.flyway.enabled=true
spring.flyway.locations=classpath:db/migration

📥 Clonagem e Execução
1. Clonar o repositório
git clone https://github.com/Brennand-Digital/backend
cd backend
cd backend

2. Build + Run
mvn clean install
mvn spring-boot:run


Servidor disponível em:

http://localhost:8080

🔐 Variáveis de Ambiente (Opcional)

Se quiser usar .env + Spring dotenv:

DB_HOST=localhost
DB_PORT=5432
DB_NAME=brennand_db
DB_USER=postgres
DB_PASS=postgres

🧪 Testando a API
Exemplo – Login

POST http://localhost:8080/auth/login

{
  "email": "seu_email@example.com",
  "password": "sua_senha"
}

📁 Estrutura de Pastas
backend/
 ├── src/
 │   ├── main/
 │   │   ├── java/com/brennand/...
 │   │   ├── resources/
 │   │   │   ├── application.properties
 │   │   │   └── db/migration/
 │   └── test/
 ├── pom.xml
 └── README.md

🌐 Rotas da API (Exemplo)
🔒 Auth
Método	Rota	Descrição
POST	/auth/login	Autenticação
POST	/auth/register	Criar usuário
🗿 Obras
Método	Rota	Descrição
GET	/obras	Lista todas
GET	/obras/{id}	Detalhes
POST	/obras	Criar obra
PUT	/obras/{id}	Atualizar
DELETE	/obras/{id}	Excluir

(Posso gerar as rotas completas se você quiser.)

🤝 Como Contribuir

Faça um fork do repositório

Crie uma branch:

git checkout -b feature/minha-feature


Commit:

git commit -m "Minha nova feature"


Push:

git push origin feature/minha-feature


Abra um Pull Request
---

## 👥 Nossa Equipe

- David Alves
- Gabriel Calado
- Eduardo de Medeiros Rocha
- Rafael Gomes
- Pedro Gomes
- Ravi Barbosa

