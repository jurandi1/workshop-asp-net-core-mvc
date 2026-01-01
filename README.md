# Sistema Web ASP.NET Core 2.1 com Entity Framework Core

## 📌 Visão Geral

Este projeto é um **sistema Web desenvolvido em ASP.NET Core 2.1**, utilizando **Entity Framework Core** para acesso a dados e **MySQL** como banco de dados. O objetivo do projeto é demonstrar a construção de uma aplicação Web completa seguindo boas práticas de arquitetura, organização de código e desenvolvimento assíncrono.

O sistema implementa um **CRUD completo**, validações, tratamento de exceções, internacionalização e funcionalidades de pesquisa, simulando um cenário real de aplicação corporativa.

![SalesWebMvc](https://github.com/user-attachments/assets/7c308fc5-5149-475e-af44-978503b31e7b)

---

## 🚀 Tecnologias Utilizadas

* **ASP.NET Core 2.1 (MVC)**
* **Entity Framework Core**
* **MySQL**
* **C#**
* **Razor Views**

---

## 🧩 Funcionalidades Implementadas

* CRUD completo de entidades
* Operações assíncronas com `async` / `await`
* Camada de serviços (Service Layer)
* ViewModels para comunicação entre Controller e View
* Validações de dados
* Tratamento de exceções customizadas
* Integridade referencial (Foreign Keys)
* Migrations com Entity Framework Core
* Seeding inicial de dados
* Internacionalização:

  * Formatação de datas
  * Formatação de números
* Pesquisa simples
* Pesquisa agrupada
* Carregamento antecipado de dados (Eager Loading)
* Página de erro personalizada

---

## 🏗️ Estrutura do Projeto

O projeto segue uma separação clara de responsabilidades:

* **Controllers**: responsáveis pelo fluxo da aplicação
* **Services**: regras de negócio e acesso a dados
* **Models**: entidades do domínio
* **ViewModels**: dados preparados para as views
* **Views**: interface com o usuário (Razor)
* **Data**: contexto do Entity Framework e migrations

---

## ⚙️ Pré-requisitos

Para executar o projeto localmente, é necessário:

* .NET Core SDK 2.1
* MySQL Server
* Visual Studio (ou IDE compatível)

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/jurandi1/workshop-asp-net-core-mvc
   ```

2. Configure a string de conexão com o MySQL no arquivo `appsettings.json`

3. Execute as migrations (se necessário):

   ```bash
   dotnet ef database update
   ```

4. Execute a aplicação:

   ```bash
   dotnet run
   ```

5. Acesse no navegador:

   ```
   http://localhost:5000
   ```

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com fins **educacionais e de portfólio**, com foco em:

* Aplicação de boas práticas em ASP.NET Core
* Uso correto do Entity Framework Core
* Desenvolvimento assíncrono
* Organização e legibilidade de código
* Simulação de um sistema Web real

---

## 🏷️ Versão

* **v1.0.0** — Versão inicial estável do sistema

---

## 👤 Autor

**Jurandi Carlos Eduardo Junior**
