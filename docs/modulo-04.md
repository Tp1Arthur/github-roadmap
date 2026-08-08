# Módulo 4 — Markdown

## Conceitos

**Markdown**
- Linguagem de formatação usada pelo GitHub para transformar texto simples em conteúdo visual — títulos, listas, links, etc.

**Títulos**
- Criados com `#` no início da linha. Quanto mais `#`, menor o título.

**Listas**
- **Não ordenada** (`-`) — itens soltos, sem sequência obrigatória (ex: tecnologias usadas).
- **Ordenada** (`1.`) — usada quando a ordem importa, tipo passos de um processo.

**Blocos de código**
- Delimitados por três crases antes e depois do trecho.
- Especificar a linguagem ativa o **syntax highlighting** (destaque de cores).

**Links e imagens**
- Link: `[texto](url)`
- Imagem: `![texto alternativo](url)` — o `!` no início faz a imagem ser exibida.

**Editando pelo site vs. localmente**
- É possível editar arquivos direto no GitHub, sem passar pelo terminal.
- Isso cria um commit no remoto que ainda não existe na máquina local, até rodar `git pull`.

**`git pull` e Fast-forward**
- `git pull` busca as mudanças do remoto e atualiza o repositório local.
- "Fast-forward" é quando o Git consegue simplesmente avançar o histórico local até o ponto do remoto, sem conflito.

## Comandos usados

| Comando | O que faz |
|---|---|
| `git pull origin master` | Baixa as mudanças do repositório remoto e atualiza o local |

## Prática realizada
Escrita de um README profissional para o repositório, com as seções: Objetivo, Tecnologias, Estrutura do repositório, Autor.

[← Voltar ao Roadmap](../ROADMAP.md)
