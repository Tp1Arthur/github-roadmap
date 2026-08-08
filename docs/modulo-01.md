# Módulo 1 — Entendendo Git e GitHub

## Conceitos

**Git x GitHub**
- Git é a ferramenta que roda localmente na máquina e controla as versões do código.
- GitHub é o site que hospeda esse histórico na nuvem e serve como vitrine/portfólio.
- Dá para usar Git sem nunca usar GitHub — GitHub é uma camada extra em cima do Git.

**Commit / Snapshot**
- Um commit é uma "foto" do estado dos arquivos em um momento específico.
- Serve como rede de segurança (voltar se algo quebrar) e como histórico (mostra a evolução do projeto).

**As 3 áreas do Git**
1. **Working Directory** — onde os arquivos são editados normalmente.
2. **Staging Area** — área de espera antes do commit. Um arquivo entra aqui com `git add`.
3. **Repository** — onde os commits ficam salvos de fato. Um arquivo entra aqui com `git commit`.

Fluxo completo: `Working Directory → git add → Staging Area → git commit → Repository`

## Comandos usados

| Comando | O que faz |
|---|---|
| `mkdir nome` | Cria uma pasta nova |
| `cd nome` | Entra em uma pasta |
| `pwd` | Mostra o caminho completo da pasta atual |
| `ls` | Lista os arquivos/pastas do diretório atual |
| `touch arquivo` | Cria um arquivo vazio |
| `git --version` | Mostra a versão do Git instalada |
| `git config --global user.name` | Mostra/define o nome que assina os commits |
| `git config --global user.email` | Mostra/define o e-mail que assina os commits |
| `git init` | Transforma a pasta atual em um repositório Git |
| `git status` | Mostra o estado atual dos arquivos |

[← Voltar ao Roadmap](../ROADMAP.md)
