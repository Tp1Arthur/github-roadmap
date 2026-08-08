# Módulo 3 — GitHub

## Conceitos

**Repositório remoto**
- É a versão do repositório hospedada na nuvem (no GitHub), separada do repositório local na máquina.
- Por padrão, o Git chama esse remoto de **`origin`**.

**Por que usar o GitHub além do backup**
- Transforma o histórico de código em algo visual e navegável, sem precisar do terminal.
- É público e acessível por qualquer pessoa — vira uma vitrine profissional (portfólio).

**`.gitignore` e License**
- `.gitignore`: arquivo que diz ao Git quais arquivos/pastas ignorar. Configurado em detalhe no Módulo 8.
- License: define legalmente o que outras pessoas podem fazer com o código. Pode ser adicionada depois.

**Conectando local ↔ remoto**
- `git remote add origin <link>` cria a ponte entre o repositório local e o do GitHub.
- `git remote -v` mostra para onde essa ponte aponta (`fetch` e `push`).

**Push**
- Envia os commits locais para o repositório remoto.
- O `-u` associa o branch local ao branch remoto — depois basta `git push`.

## Comandos usados

| Comando | O que faz |
|---|---|
| `git remote add origin <link>` | Conecta o repositório local a um repositório remoto no GitHub |
| `git remote -v` | Mostra os remotos configurados |
| `git push -u origin master` | Envia os commits e associa o branch local ao remoto |
| `git push` | Envia novos commits, sem precisar repetir origin/branch |

[← Voltar ao Roadmap](../ROADMAP.md)
