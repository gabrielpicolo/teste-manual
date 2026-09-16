# Casos de Teste

Os casos abaixo foram preparados para execução manual.

> Antes de executar um caso, altere o campo **Status** de `NÃO EXECUTADO` para `PASS` ou `FAIL` conforme o comportamento observado.

---

## CT01 — Login com credenciais válidas

**Objetivo:** verificar se um usuário consegue acessar a área segura usando credenciais válidas.

**Pré-condição:** estar na página de login.

**Passos:**

1. Informar `tomsmith` no campo Username.
2. Informar `SuperSecretPassword!` no campo Password.
3. Clicar em **Login**.

**Resultado esperado:** o sistema deve permitir o acesso à área segura e exibir uma mensagem indicando que o login foi realizado com sucesso.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## CT02 — Login com usuário inválido

**Objetivo:** verificar o comportamento quando o usuário informado é inválido.

**Pré-condição:** estar na página de login.

**Passos:**

1. Informar `usuarioinvalido` no campo Username.
2. Informar `SuperSecretPassword!` no campo Password.
3. Clicar em **Login**.

**Resultado esperado:** o sistema deve impedir o acesso e exibir uma mensagem de erro referente ao usuário inválido.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## CT03 — Login com senha inválida

**Objetivo:** verificar o comportamento quando a senha informada é inválida.

**Pré-condição:** estar na página de login.

**Passos:**

1. Informar `tomsmith` no campo Username.
2. Informar `senhaerrada` no campo Password.
3. Clicar em **Login**.

**Resultado esperado:** o sistema deve impedir o acesso e exibir uma mensagem de erro referente à senha inválida.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## CT04 — Login com os dois campos vazios

**Objetivo:** verificar o comportamento quando nenhuma credencial é informada.

**Pré-condição:** estar na página de login.

**Passos:**

1. Deixar o campo Username vazio.
2. Deixar o campo Password vazio.
3. Clicar em **Login**.

**Resultado esperado:** o sistema deve impedir o acesso e exibir uma mensagem de erro.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## CT05 — Login com usuário vazio

**Objetivo:** verificar o comportamento quando apenas a senha é informada.

**Pré-condição:** estar na página de login.

**Passos:**

1. Deixar o campo Username vazio.
2. Informar `SuperSecretPassword!` no campo Password.
3. Clicar em **Login**.

**Resultado esperado:** o sistema deve impedir o acesso e exibir uma mensagem de erro.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## CT06 — Login com senha vazia

**Objetivo:** verificar o comportamento quando apenas o usuário é informado.

**Pré-condição:** estar na página de login.

**Passos:**

1. Informar `tomsmith` no campo Username.
2. Deixar o campo Password vazio.
3. Clicar em **Login**.

**Resultado esperado:** o sistema deve impedir o acesso e exibir uma mensagem de erro.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## CT07 — Logout após login válido

**Objetivo:** verificar se o usuário consegue sair da área segura.

**Pré-condição:** estar autenticado na área segura.

**Passos:**

1. Realizar login com credenciais válidas.
2. Clicar em **Logout**.

**Resultado esperado:** o sistema deve encerrar a sessão e redirecionar o usuário para a página de login.

**Status:** `NÃO EXECUTADO`

**Evidência:** não adicionada.

---

## Resumo da execução

| Caso | Cenário | Status |
|---|---|---|
| CT01 | Login válido | NÃO EXECUTADO |
| CT02 | Usuário inválido | NÃO EXECUTADO |
| CT03 | Senha inválida | NÃO EXECUTADO |
| CT04 | Campos vazios | NÃO EXECUTADO |
| CT05 | Usuário vazio | NÃO EXECUTADO |
| CT06 | Senha vazia | NÃO EXECUTADO |
| CT07 | Logout | NÃO EXECUTADO |
