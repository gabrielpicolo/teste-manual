# QA Login — Testes Manuais

Este é o meu primeiro projeto de estudos em **Quality Assurance (QA)**.

O objetivo é praticar os fundamentos de testes manuais usando uma funcionalidade simples de login. Neste projeto eu exercito a criação de um plano de testes, escrita de casos de teste, execução manual, registro de resultados e documentação de bugs.

## Aplicação utilizada

O projeto usa a página pública de prática **The Internet — Form Authentication**:

https://the-internet.herokuapp.com/login

A própria aplicação informa as credenciais válidas para teste:

- Usuário: `tomsmith`
- Senha: `SuperSecretPassword!`

## O que será testado

Os testes cobrem cenários básicos de autenticação, como:

- login com credenciais válidas;
- usuário inválido;
- senha inválida;
- campos vazios;
- usuário vazio;
- senha vazia;
- logout após login bem-sucedido.

## Estrutura do projeto

```text
qa-login-manual-testing/
├── README.md
├── plano-de-testes.md
├── casos-de-teste.md
├── bugs.md
└── evidencias/
    └── README.md
```

### `plano-de-testes.md`
Explica o objetivo, o escopo e a forma como os testes serão executados.

### `casos-de-teste.md`
Contém os cenários de teste, seus passos e os resultados esperados.

### `bugs.md`
Será usado para registrar defeitos encontrados durante a execução.

### `evidencias/`
Pasta destinada a screenshots que comprovem os resultados dos testes.

## Status do projeto

🟡 **Em execução / aprendizado**

Os casos de teste foram planejados e serão executados manualmente. Os resultados serão atualizados conforme os testes forem realizados.

## O que estou aprendendo

- fundamentos de QA;
- diferença entre cenário positivo e negativo;
- escrita de casos de teste;
- resultado esperado x resultado obtido;
- registro de bugs;
- organização de evidências;
- uso do GitHub para documentar projetos de QA.

---

Este projeto representa o início da minha evolução em QA. Projetos futuros irão adicionar testes de API, SQL, automação e CI/CD conforme meu aprendizado avançar.
