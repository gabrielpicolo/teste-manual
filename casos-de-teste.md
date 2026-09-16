# Casos de Teste

## CT01 - Adicionar tarefa

**Passos:**
1. Digitar `Estudar QA`.
2. Pressionar Enter.

**Esperado:** a tarefa aparece na lista.

**Resultado:** a tarefa foi adicionada normalmente.

**Status:** `PASS`

---

## CT02 - Concluir tarefa

**Passos:**
1. Adicionar uma tarefa.
2. Marcar a tarefa como concluída.

**Esperado:** a tarefa fica marcada como concluída.

**Resultado:** a tarefa ficou riscada após ser marcada como concluída.

**Status:** `PASS`

---

## CT03 - Excluir tarefa

**Passos:**
1. Adicionar uma tarefa.
2. Excluir a tarefa.

**Esperado:** a tarefa desaparece da lista.

**Resultado:** ao clicar no X, a tarefa foi excluída.

**Status:** `PASS`

---

## CT04 - Tarefa vazia

**Passos:**
1. Deixar o campo vazio.
2. Pressionar Enter.

**Esperado:** nenhuma tarefa é adicionada.

**Resultado:** nenhuma tarefa foi criada sem texto.

**Status:** `PASS`
