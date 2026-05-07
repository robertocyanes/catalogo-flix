# 🎬 Catalogo-Flix

## 📌 Sobre o Projeto

O **Catalogo-Flix** é uma API serverless desenvolvida utilizando **Azure Functions** e **.NET 7**, criada para gerenciamento de registros de catálogo de filmes e séries.

O projeto foi desenvolvido com foco em computação em nuvem, arquitetura serverless e desenvolvimento backend moderno, permitindo criar e listar registros de forma simples, leve e escalável.

A aplicação utiliza armazenamento em memória para gerenciamento temporário dos registros, utilizando estruturas nativas do .NET como `List` e `Dictionary`.

---

# 🚀 Tecnologias Utilizadas

## Backend
- .NET 7
- C#
- Azure Functions v4

## Estruturas de Dados
- List
- Dictionary
- Collections.Generic

## Cloud
- Microsoft Azure
- Azure Functions Runtime

## Ferramentas
- Azure Functions Core Tools
- Visual Studio Code
- Git
- GitHub
- Postman

---

# 🟡 Arquitetura Serverless

O projeto utiliza o modelo **Serverless Computing**, executando funções sob demanda através da Azure Functions.

## Benefícios
- escalabilidade automática
- baixo custo operacional
- deploy simplificado
- alta disponibilidade
- execução sob demanda

---

# 🟡 Funcionalidades

- Adicionar registros ao catálogo
- Listar registros cadastrados
- Armazenamento em memória
- Manipulação de coleções em C#
- Estrutura serverless escalável

---

# 🟡 Estrutura dos Registros

Cada registro contém:

```json
{
  "titulo": "Interestelar",
  "genero": "Ficção Científica"
}
```

---

# 🟡 Estrutura do Projeto

```text
Catalogo-Flix/
│
├── Functions/
├── CatalogoStore.cs
├── CriarRegistro.cs
├── host.json
├── local.settings.json
├── .gitignore
└── README.md
```

---

# 🟡 Armazenamento em Memória

O projeto utiliza uma estrutura global compartilhada para armazenar os registros temporariamente:

```csharp
public static class CatalogoStore
{
    public static List<Dictionary<string, string>> Registros
}
```

Essa abordagem foi utilizada para fins educacionais e demonstração de funcionamento da API serverless.

---

# ▶️ Como Executar o Projeto

## 1. Clonar o repositório

```bash
git clone https://github.com/robertocyanes/catalogo-flix.git
```

## 2. Entrar na pasta

```bash
cd catalogo-flix
```

## 3. Restaurar dependências

```bash
dotnet restore
```

## 4. Executar o projeto

```bash
func start
```

---

# 🟡 Conceitos Aplicados

- Azure Functions
- Serverless Computing
- APIs REST
- Estruturas de Dados em C#
- Collections
- Cloud Computing
- Organização Backend
- Git e Versionamento

---

# 🟡 Objetivo do Projeto

O principal objetivo do **Catalogo-Flix** é demonstrar conhecimentos em:

- desenvolvimento backend
- computação em nuvem
- arquitetura serverless
- Azure Functions
- APIs RESTful
- .NET 7
- organização de projetos

---

# 🟡 Melhorias Futuras

- integração com banco de dados
- autenticação JWT
- Swagger/OpenAPI
- persistência em Azure Cosmos DB
- testes automatizados
- deploy automatizado
- validações avançadas

---

# Autor

**Roberto César Yanes**

## LinkedIn
https://github.com/robertocyanes

