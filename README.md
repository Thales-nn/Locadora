# LFS — Locadora de Filmes e Séries
Sistema de Gerenciamento de Locações

O **LFS (Locadora de Filmes e Séries)** é um sistema completo para gerenciamento de locações, permitindo controlar clientes, usuários, acervo, pagamentos e histórico de locações.  
O objetivo é automatizar processos, reduzir erros manuais e organizar as informações de forma eficiente.

Este repositório contém:

- **Frontend:** HTML, CSS e JavaScript  
- **Backend:** Java + Spring Boot  
- **Banco de Dados:** PostgreSQL  

---

# 📁 Estrutura do Repositório

```
1. Requisitos
│── Casos de Uso
│   ├── LFS - Caso de Uso 01 - Gerenciar Usuários.docx
│   ├── LFS - Caso de Uso 02 - Gerenciar Clientes.docx
│   ├── LFS - Caso de Uso 03 - Gerenciar Acervo.docx
│   ├── LFS - Caso de Uso 04 - Gerenciar Locações.docx
│   ├── LFS - Caso de Uso 05 - Gerenciar Pagamentos.docx
│   ├── LFS - Caso de Uso 06 - Consultar Histórico.docx
│   └── LFS - Caso de Uso 07 - Gerar Relatórios.docx
│── LFS - Visão.docx

2. Análise e Design
│── LFS - Modelo de Análise e Design.asta

3. Implementação
│── LFS---Backend (Spring Boot)
│── LFS---Frontend (HTML/CSS/JS)
│── application.properties
│── script.sql

4. Teste
│── LFS - Roteiro de Testes.xlsx

5. Implantação
│── LFS - Guia de Implantação.docx
│── LFS - Manual do Usuário.docx
│── LFS - Script de Implantação.docx

6. Gerenciamento de Projeto
│── LFS - Planejamento do Projeto.xlsx
│── LFS - Checklist de Verificação.xlsx

README.md
```

---

# ✔ Funcionalidades Principais

### **Gerenciar Usuários**
- Cadastro, atualização e remoção  
- Controle de permissões  
- Login e autenticação  

### **Gerenciar Clientes**
- Cadastro de clientes  
- Consulta e edição  
- Histórico vinculado a locações  

### **Gerenciar Acervo**
- Filmes  
- Séries  
- Categorias e status de disponibilidade  

### **Gerenciar Locações**
- Registrar nova locação  
- Renovar  
- Finalizar / Devolver  
- Cálculo automático de valores  

### **Gerenciar Pagamentos**
- Registro de pagamentos  
- Valores pendentes  
- Controle de multas  

### **Consultar Histórico**
- Histórico completo de locações  
- Filtros por cliente, mídia e datas  

### **Gerar Relatórios**
- Relatórios de movimentação  
- Relatórios de acervo  
- Relatórios financeiros  

---

# 🛠 Tecnologias Utilizadas

- Java 17  
- Spring Boot  
- HTML, CSS, JavaScript  
- PostgreSQL  
- MVC  
- API REST  

---

# 📦 Como Executar o Projeto

## Backend (Spring Boot)
```bash
cd LFS---Backend
mvn spring-boot:run
```

## Frontend
Abra o arquivo:
```
LFS---Frontend/index.html
```

## Banco de Dados
Execute no PostgreSQL:
```
script.sql
```

---

# 📜 Licença
Projeto acadêmico — uso educacional.
