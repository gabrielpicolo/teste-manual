# Plano de Testes

## 1. Objetivo

Validar manualmente a funcionalidade de login da aplicação **The Internet — Form Authentication**.

A tela de login aceita um usuário e uma senha. A própria aplicação informa as credenciais válidas para teste.

## 2. Escopo

Serão testados os seguintes comportamentos:

- login com credenciais válidas;
- tentativa de login com usuário inválido;
- tentativa de login com senha inválida;
- tentativa de login com campos vazios;
- tentativa de login com usuário vazio;
- tentativa de login com senha vazia;
- logout após login bem-sucedido.

## 3. Fora do escopo

Neste primeiro projeto não serão realizados:

- testes automatizados;
- testes de API;
- testes de performance;
- testes de segurança;
- testes em vários dispositivos;
- testes em vários navegadores.

Esses assuntos serão estudados em projetos futuros.

## 4. Ambiente de teste

- Aplicação: https://the-internet.herokuapp.com/login
- Tipo de teste: Manual
- Navegador sugerido: Google Chrome
- Sistema operacional: o utilizado durante a execução

## 5. Credenciais de teste

- Usuário válido: `tomsmith`
- Senha válida: `SuperSecretPassword!`

## 6. Estratégia

Para cada caso de teste:

1. acessar a página de login;
2. seguir os passos descritos;
3. comparar o comportamento observado com o resultado esperado;
4. marcar o caso como `PASS` ou `FAIL`;
5. registrar evidência quando necessário;
6. caso exista uma falha, documentar o problema em `bugs.md`.

## 7. Critério de resultado

- `PASS`: o comportamento observado corresponde ao resultado esperado.
- `FAIL`: o comportamento observado é diferente do resultado esperado.
- `NÃO EXECUTADO`: o teste ainda não foi realizado.

## 8. Critério de conclusão

O projeto será considerado concluído quando todos os casos de teste tiverem sido executados e seus resultados registrados.
