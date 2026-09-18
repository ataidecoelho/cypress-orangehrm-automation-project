# 🧪 Cypress E2E Automation - OrangeHRM

---

## 🌐 Idiomas / Languages
- [Português (Brasil)](#-português)
- [English](#-english)

---

## 🇧🇷 Português

### 📋 Sobre o Projeto
Este é um projeto em andamento realizando automação de testes ponta a ponta (E2E) com o **Cypress**, utilizando a plataforma Open Source [OrangeHRM Live Demo](https://opensource-demo.orangehrmlive.com/web/index.php).

O **Cypress** é um framework de testes baseado em JavaScript que executa diretamente em um navegador real, garantindo velocidade, controle e testes mais confiáveis.

### 🛠️ Cenários Cobertos

<details>
<summary><b>🔐 Funcionalidade de Login</b> (Clique para expandir)</summary>

*   **Login Válido:** Validação de acesso ao sistema com credenciais corretas.
*   **Login Inválido:** Verificação de mensagens de erro ao inserir dados incorretos ou campos vazios.
</details>

<details>
<summary><b>👤 Gestão de Perfil (My Info)</b> (Clique para expandir)</summary>

*   **Alteração de Informações:** Atualização dinâmica de dados cadastrais.
*   **Massa de Dados Dinâmica:** Utilização da biblioteca **ChanceJS** para gerar de forma randômica e realista informações como: *Nome, Sobrenome, ID, Datas, Nacionalidade, entre outros*.
</details>

### 🚀 Instalação e Execução

**Pré-requisitos:** Ter o [Node.js](https://nodejs.org) instalado.

1. **Inicializar o projeto Node e Instalar o Cypress:**
   ```bash
   npm init
   npm install cypress --save-dev
   ```

2. **Instalar a biblioteca ChanceJS:**
   ```bash
   npm install chance --save-dev
   ```

3. **Abrir a interface do Cypress:**
   ```bash
   npx cypress open
   ```

  
---

## 🇺🇸 English

### 📋 About the Project
This is an ongoing project conducting end-to-end (E2E) automation testing with **Cypress**, utilizing the Open Source platform [OrangeHRM Live Demo](https://opensource-demo.orangehrmlive.com/web/index.php).

**Cypress** is a JavaScript-based testing framework that runs directly in a real browser, ensuring fast, controlled, and reliable test executions.

### 🛠️ Covered Scenarios

<details>
<summary><b>🔐 Login Functionality</b> (Click to expand)</summary>

*   **Valid Login:** System access validation using correct credentials.
*   **Invalid Login:** Error message verification when entering incorrect data or blank fields.
</details>

<details>
<summary><b>👤 Profile Management (My Info)</b> (Click to expand)</summary>

*   **User Information Update:** Dynamic data update validation.
*   **Dynamic Data Management:** Implementation of the **ChanceJS** library to randomly generate realistic information such as: *First Name, Last Name, ID, Dates, Nationality, etc*.
</details>

### 🚀 Setup and Execution

**Prerequisites:** Ensure you have [Node.js](https://nodejs.org) installed.

1. **Initialize Node project and Install Cypress:**
   ```bash
   npm init
   npm install cypress --save-dev
   ```

2. **Install ChanceJS library:**
   ```bash
   npm install chance --save-dev
   ```

3. **Open Cypress Runner UI:**
   ```bash
   npx cypress open
   ```



---

## 📁 Estrutura do Projeto / Project Structure

```text
cypress/
  ├── e2e/
  │   ├── login.cy.js          # Testes de autenticação / Auth tests
  │   └── my-info.cy.js        # Testes de perfil com ChanceJS / Profile tests
  ├── fixtures/                # Dados estáticos / Static data
  └── support/                 # Comandos customizados / Custom commands
```

---
<div align="center">
  <sub>Desenvolvido para fins de portfólio e boas práticas de QA. / Developed for portfolio and QA best practices.</sub>
</div>
