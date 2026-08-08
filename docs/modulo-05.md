# Módulo 5 — Commits Profissionais (Conventional Commits)

## Conceitos

**Conventional Commits**
- Padrão de mensagens de commit usado por times profissionais: `tipo: descrição curta`.
- A descrição é escrita no **imperativo** (ex: "adiciona", "corrige").

**Tipos praticados**

| Tipo | Quando usar |
|---|---|
| `docs:` | Mudança em documentação |
| `feat:` | Nova funcionalidade |
| `style:` | Mudança de formatação, sem alterar lógica |
| `fix:` | Correção de um erro/bug |
| `refactor:` | Reorganização, sem mudar comportamento |

**Diagnóstico de pasta errada**
- `pwd` confirma em qual pasta você está.
- `git status` ajuda a identificar arquivos fora de contexto.
- `mv origem destino` move um arquivo entre pastas.

**Commits locais x remoto**
- Commits ficam salvos localmente, independente de internet.
- Só o `git push` depende de conexão — se falhar, os commits continuam seguros na máquina.
- Erro `Could not resolve host` = problema de rede/DNS, sem relação com Git.

## Comandos usados

| Comando | O que faz |
|---|---|
| `mv origem destino` | Move um arquivo de um lugar para outro |
| `git commit -m "tipo: descrição"` | Registra um commit seguindo Conventional Commits |
| `git push` | Envia commits locais para o repositório remoto |

## Prática realizada
10 commits usando 5 tipos diferentes de Conventional Commits.

[← Voltar ao Roadmap](../ROADMAP.md)
