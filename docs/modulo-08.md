# Módulo 8 — .gitignore

## Conceitos

**`.gitignore`**
- Arquivo que diz ao Git quais arquivos/pastas ignorar — nunca aparecem no `git status` nem são commitados.

**Por que é importante**
- Evita subir arquivos sensíveis (como `.env`, com senhas e chaves de API).
- Evita subir arquivos gerados automaticamente (`bin`, `obj`, `node_modules`).
- Evita subir configurações específicas da máquina (`.vscode`).

**Risco de histórico permanente**
- Mesmo que um arquivo sensível seja deletado depois, ele continua no histórico de commits — por isso nunca deve subir, nem uma vez.

**Itens usados na prática**
- `.vscode`, `bin`, `obj`, `node_modules`, `.env`

**Sobre o tipo de commit para `.gitignore`**
- Muitos times usam `chore:` para arquivos de configuração/manutenção, já que não é bem `docs:` nem `feat:`.

## Comandos usados

| Comando | O que faz |
|---|---|
| `touch .gitignore` | Cria o arquivo (o ponto indica arquivo oculto no Linux) |

## Prática realizada
Criação do `.gitignore` com 5 itens, testado com um arquivo `.env` fake que foi corretamente ignorado.

[← Voltar ao Roadmap](../ROADMAP.md)
