
# 🏥 Sistema de Triagem para UBS

Aplicação interativa desenvolvida em **Python** para gerenciamento de triagem em Unidades Básicas de Saúde (UBS), com integração a banco de dados **PostgreSQL** e interface web construída com **Panel**.

---

## 📖 Sobre o Projeto

O sistema permite realizar o controle completo de triagens médicas, incluindo cadastro, consulta, atualização e remoção de registros, além de oferecer visualização dinâmica dos dados.

A aplicação foi desenvolvida com foco em:

* Organização do fluxo de atendimento
* Agilidade no registro de pacientes
* Análise e visualização de dados em tempo real

---

## 🖥️ Interface

A interface foi construída utilizando a biblioteca **Panel**, permitindo:

* Formulários interativos
* Filtros dinâmicos
* Tabela de dados com **Tabulator**
* Notificações em tempo real

---

## 🚀 Tecnologias Utilizadas

* 🐍 Python
* 🗄️ PostgreSQL
* 🔌 psycopg2
* ⚙️ SQLAlchemy
* 📊 Pandas
* 🎛️ Panel (interface web interativa)

---

## ⚙️ Funcionalidades

### 🔎 Consulta

* Visualização das triagens cadastradas
* Filtro por nível de prioridade

### ➕ Inserção

* Registro de nova triagem
* Associação com paciente e profissional

### ✏️ Atualização

* Edição de dados existentes
* Atualização parcial (somente campos desejados)

### ❌ Remoção

* Exclusão de triagem por ID

---


## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/sistema-triagem-ubs.git
cd sistema-triagem-ubs
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Configure o banco de dados

Crie um banco PostgreSQL e configure as variáveis no código:

```python
DB_USER = "seu_usuario"
DB_PASSWORD = "sua_senha"
DB_HOST = "localhost"
DB_PORT = "5432"
DB_NAME = "nome_do_banco"
```

Execute o script SQL (`esquema.sql`) para criar as tabelas.

---

### 4. Execute a aplicação

```bash
python triagem.py
```

A aplicação será iniciada em:

👉 [http://localhost:5007](http://localhost:5007)

---

## 📊 Estrutura dos Dados

A tabela de triagem contém:

* ID da triagem
* Paciente
* Profissional responsável
* Classificação de prioridade
* Descrição dos sintomas
* Data e hora

---

## 🧠 Conceitos Aplicados

* CRUD completo com SQL
* Integração Python + banco de dados
* Manipulação de dados com Pandas
* Interfaces interativas com Panel
* Tratamento de exceções
* Arquitetura modular simples

---

## 🔮 Melhorias Futuras

* Autenticação de usuários
* Dashboard com gráficos (Plotly/Matplotlib)
* Deploy em nuvem (Heroku, Render, etc.)
* API REST para integração com outros sistemas

---

## 👩‍💻 Autora

**Anna Beatryz**

---

## ⭐ Diferenciais do Projeto

* Interface interativa sem uso de frameworks pesados
* Integração direta com banco relacional
* Código organizado e modular
* Aplicação prática para área da saúde

---
