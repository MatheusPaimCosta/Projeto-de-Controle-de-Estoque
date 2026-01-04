# ERP de Controle e Gestão de Estoque

Sistema corporativo desenvolvido para controle e gestão de estoque, com foco em
boas práticas de engenharia de software, arquitetura em camadas e desenvolvimento
full stack.

Este projeto faz parte de um plano de estudo prático com objetivo de consolidar
conhecimentos e servir como portfólio profissional.

---

## 🎯 Objetivo do Projeto

Simular um sistema corporativo real utilizado por pequenas e médias empresas,
permitindo o controle de produtos, categorias, fornecedores e movimentações de
estoque, garantindo rastreabilidade e organização das informações.

---

## 🛠️ Tecnologias Utilizadas

### Back-end
- ASP.NET Core (API REST)
- Entity Framework Core
- C#

### Front-end
- React
- TypeScript
- Axios

### Banco de Dados
- PostgreSQL
- Docker

### Infraestrutura e Ferramentas
- Docker Compose
- Git
- GitHub

---

## 📦 Funcionalidades

### Funcionalidades já planejadas
- Cadastro de produtos
- Cadastro de categorias
- Cadastro de fornecedores
- Controle de entrada e saída de estoque
- Histórico de movimentações
- Autenticação e controle de usuários
- Relatórios básicos de estoque

---

## 🧱 Arquitetura

O projeto segue uma arquitetura em camadas, separando responsabilidades para
facilitar manutenção, testes e escalabilidade.

Camadas principais:
- **Domain**: regras de negócio e entidades
- **Application**: casos de uso e lógica da aplicação
- **Infrastructure**: acesso a dados e serviços externos
- **API**: camada de apresentação (endpoints)

---

## 🚀 Como Executar o Projeto (resumo)

### Pré-requisitos
- Docker
- Node.js (LTS)
- .NET SDK (LTS)

### Passos iniciais
```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/erp-estoque-corporativo.git
