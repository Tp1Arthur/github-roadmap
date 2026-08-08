# Módulo 2 — Primeiro Commit

## Conceitos

**Os 3 estados de um arquivo no Git**
- **Untracked** — o Git não conhece o arquivo (nunca foi commitado).
- **Modified** — o Git já conhece o arquivo, mas o conteúdo mudou desde o último commit.
- **Staged** — o arquivo passou pelo `git add` e está pronto para entrar no próximo commit.

**Hash do commit**
- Cada commit recebe um identificador único (hash), como `c66f3a1` ou `e837d33`.
- Serve para identificar exatamente aquele snapshot no histórico — nunca se repete.
- O primeiro commit de um repositório é chamado de **root-commit**.

**Histórico (`git log`)**
- Mostra todos os commits feitos, do mais recente ao mais antigo, com hash, autor, data e mensagem.

**Insertions / Deletions**
- Ao commitar, o Git mostra quantas linhas foram adicionadas (`insertions`) e removidas (`deletions`) desde o commit anterior.

## Comandos usados

| Comando | O que faz |
|---|---|
| `nano arquivo` | Abre um editor de texto simples dentro do terminal |
| `Ctrl + O` → `Enter` | Salva o arquivo dentro do nano |
| `Ctrl + X` | Sai do nano |
| `git add arquivo` | Move o arquivo do Working Directory para a Staging Area |
| `git commit -m "mensagem"` | Salva o conteúdo da Staging Area como um novo commit |
| `git log` | Mostra o histórico completo de commits |

[← Voltar ao Roadmap](../ROADMAP.md)
