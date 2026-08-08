# Módulo 12 — Fork

## Conceitos

**Fork**
- Uma cópia completa de um repositório de outra pessoa, criada dentro da própria conta do GitHub.
- Usado quando não se tem permissão de escrita no repositório original.
- Base da colaboração em projetos open source.

**Fork x Branch**
- **Branch** → ramificação dentro do mesmo repositório.
- **Fork** → cópia completa em outro repositório/conta.

**`git clone`**
- Comando usado para baixar um repositório já existente para a máquina local, já conectando o `origin` automaticamente.

**Fluxo conceitual de contribuição via Fork**

Fork do projeto original → clone para a máquina → alterações → commit e push (para o fork) → Pull Request do fork para o projeto original → revisão pelo dono do projeto

## Comandos usados

| Comando | O que faz |
|---|---|
| `git clone <link>` | Baixa um repositório existente, conectando o origin automaticamente |

## Prática realizada
Fork do repositório de prática `octocat/Spoon-Knife`, clonado, editado, e enviado de volta ao fork.

[← Voltar ao Roadmap](../ROADMAP.md)
