# Módulo 15 — GitHub Actions (Introdução)

## Conceitos

**GitHub Actions / CI/CD**
- Ferramenta de automação do GitHub que executa tarefas automaticamente em resposta a eventos no repositório (push, Pull Request).
- **CI** (Integração Contínua) — testar/validar código automaticamente. **CD** (Entrega Contínua) — publicar automaticamente.
- Funciona como um portão de qualidade automático, consistente, sem depender de lembrança humana.

**Workflow**
- O "roteiro" que define o que deve acontecer automaticamente.
- Fica em arquivos `.yml` dentro da pasta especial `.github/workflows/`.

**Estrutura básica de um workflow (YAML)**
- `name:` — nome do workflow
- `on:` — evento que dispara a execução (ex: push)
- `jobs:` — tarefas a serem executadas
- `runs-on:` — sistema operacional onde a tarefa roda
- `steps:` — lista ordenada de passos dentro do job
- YAML é sensível à indentação.

**Actions prontas**
- É comum usar "receitas" prontas da comunidade (ex: `actions/checkout@v4`) em vez de escrever tudo do zero.

## Comandos usados

| Comando | O que faz |
|---|---|
| `mkdir -p .github/workflows` | Cria a pasta especial de workflows |

## Prática realizada
Criação do workflow `validar-html.yml`, rodando a cada push, confirmado com sucesso na aba Actions do GitHub.

[← Voltar ao Roadmap](../ROADMAP.md)
