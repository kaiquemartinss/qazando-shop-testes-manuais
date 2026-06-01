# 🛒 Automation Practice — Portfólio de Testes Manuais

![QA Manual](https://img.shields.io/badge/QA-Manual-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Construção-yellow?style=for-the-badge)

---

## 📋 Sobre o Projeto

O **Automation Practice** (QAZANDO Shop) é uma aplicação e-commerce desenvolvida especialmente para a prática de testes de software, simulando um ambiente real de loja virtual com funcionalidades como cadastro de usuário, login, busca de produtos e carrinho de compras.

Este projeto tem como objetivo demonstrar domínio em **testes manuais**, cobrindo desde o planejamento até a execução e registro de evidências, simulando o fluxo de trabalho de um QA em um projeto real.

🔗 Aplicação testada: [Automation Practice](https://www.automationpratice.com.br/)

---

## 🎯 Funcionalidades Testadas

| Funcionalidade | Casos de Teste | Evidências |
|---|---|---|
| Cadastro | CT001 – CT005 | ✅ |
| Login | CT006 – CT010 | ✅ |
| Busca de Produtos | CT011 – CT013 | ✅ |
| Carrinho | CT014 – CT018 | ✅ |

---

## 🗂️ Estrutura do Repositório

```
qazando-shop-testes-manuais/
├── 01-planejamento-de-testes/
│   ├── plano-de-teste.md         # Plano de testes com escopo e estratégia
│   └── cenarios-de-teste.md      # Cenários de teste mapeados por funcionalidade
├── 02-casos-de-teste/
│   ├── 1-cadastro/               # CT001 a CT005
│   ├── 2-login/                  # CT006 a CT010
│   ├── 3-busca-de-produtos/      # CT011 a CT013
│   └── 4-carrinho/               # CT014 a CT018
├── 03-evidencias/                # Prints de execução (EV-CT001 a EV-CT018)
├── 04-bug-report/                # 🚧 Em construção
└── 05-relatorio-final/           # 🚧 Em construção
```

---

## 🧪 Casos de Teste

### 📝 Cadastro
| ID | Cenário |
|---|---|
| CT001 | Cadastro com dados válidos |
| CT002 | Cadastro com e-mail já existente |
| CT003 | Cadastro com campos obrigatórios em branco |
| CT004 | Cadastro com senha menor que o mínimo permitido |
| CT005 | Cadastro com e-mail em formato inválido |

### 🔐 Login
| ID | Cenário |
|---|---|
| CT006 | Login com credenciais corretas |
| CT007 | Login com senha incorreta |
| CT008 | Login com e-mail não cadastrado |
| CT009 | Login com campo senha em branco |
| CT010 | Login com campo e-mail em branco |

### 🔍 Busca de Produtos
| ID | Cenário |
|---|---|
| CT011 | Busca por produto existente |
| CT012 | Busca por produto inexistente |
| CT013 | Busca com campo em branco |

### 🛒 Carrinho
| ID | Cenário |
|---|---|
| CT014 | Adicionar produto ao carrinho |
| CT015 | Remover produto do carrinho |
| CT016 | Atualizar quantidade de produto |
| CT017 | Validar cálculo do total do carrinho |
| CT018 | Carrinho vazio após remoção de todos os itens |

---

## 🏗️ Artefatos de QA

| Artefato | Status |
|---|---|
| Plano de Testes | ✅ Concluído |
| Cenários de Teste | ✅ Concluído |
| Casos de Teste (CT001–CT018) | ✅ Concluído |
| Evidências (EV-CT001–EV-CT018) | ✅ Concluído |
| Bug Report | 🚧 Em construção |
| Relatório Final | 🚧 Em construção |

---

## 👨‍💻 Autor

**Kaique Martins**  
Estudante de QA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaiquemartins/)
