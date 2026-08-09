# 📜 Roadmap Original

Este é o roadmap que deu origem a este repositório — o documento-base que guiou os 15 módulos praticados aqui.

> **Objetivo:** sair do nível "sei dar push" para "consigo trabalhar em um projeto profissional".
> **Duração sugerida:** 3 a 4 semanas, 1 hora por dia.

---

## Módulo 1 — Entendendo Git e GitHub

**Teoria:** controle de versão, Git × GitHub, repositório local e remoto, histórico, snapshot, commit, branch.

**Comandos:** `pwd`, `ls`, `mkdir`, `cd`, `git --version`, `git config --global user.name`, `git config --global user.email`, `git config --list`

**Prática:** criar a pasta `github-roadmap`, adicionar um `README.md`, rodar `git init` e `git status`.

**Objetivo de aprendizado:** entender Working Directory, Staging Area e Repository.

## Módulo 2 — Primeiro Commit

**Comandos:** `git add`, `git commit`, `git log`

**Conceitos:** Modified, Untracked, Tracked

**Prática:** criar `index.html` com um `<h1>`, fazer o primeiro commit, alterar o conteúdo e commitar de novo.

**Desafio:** descobrir quantos commits existem e qual o hash do primeiro.

## Módulo 3 — GitHub

**Teoria:** novo repositório, público × privado, README, License.

**Prática:** criar o repositório `github-roadmap` no GitHub, conectar com `git remote add origin` e enviar com `git push`.

## Módulo 4 — Markdown

**Teoria:** títulos, listas, imagens, links, tabelas, blocos de código.

**Prática:** escrever um README profissional com Objetivo, Tecnologias, Como executar e Autor.

## Módulo 5 — Commits Profissionais

**Teoria:** Conventional Commits — `feat:`, `fix:`, `docs:`, `style:`, `refactor:`, `test:`

**Prática:** fazer 10 commits diferentes usando mensagens corretas.

## Módulo 6 — Branches

**Comandos:** `git branch`, `git checkout`, `git switch`, `git merge`

**Prática:** projeto de calculadora — criar `feature/soma`, implementar, criar `feature/subtracao`, implementar, e mesclar as duas.

## Módulo 7 — Merge Conflicts

Um dos assuntos mais importantes do módulo.

**Prática:** criar duas branches alterando a mesma linha do mesmo arquivo, de propósito, e resolver o conflito manualmente.

## Módulo 8 — .gitignore

**Itens a ignorar:** `.vscode`, `bin`, `obj`, `node_modules`, `.env`

**Prática:** criar arquivos que não devem subir e confirmar com `git status` que estão sendo ignorados.

## Módulo 9 — GitHub Pages

**Teoria:** deploy, atualização automática.

**Prática:** publicar um mini portfólio a partir de um projeto HTML.

## Módulo 10 — Issues

**Tipos:** Bug, Feature, Enhancement.

**Prática:** criar 5 Issues (ex: Adicionar Dark Mode, Criar Login, Corrigir Footer, Adicionar Responsividade, Melhorar README).

## Módulo 11 — Pull Requests

Mesmo trabalhando sozinho, simular o fluxo:

`feature/login` → push → Pull Request → merge

Isso simula um ambiente de equipe.

## Módulo 12 — Fork

**Prática:** fazer fork de um projeto simples, clonar, fazer uma pequena alteração, e entender como funcionaria um Pull Request de volta ao projeto original.

## Módulo 13 — GitHub Projects

**Prática:** montar um Kanban (To Do, Doing, Done) e organizar um projeto real.

## Módulo 14 — Releases

**Teoria:** Versionamento Semântico (SemVer).

**Prática:** criar `v1.0.0`, `v1.1.0`, `v2.0.0`.

## Módulo 15 — GitHub Actions (Introdução)

Não é preciso dominar ainda — só entender:

- O que é CI/CD
- O que faz um workflow
- Onde ficam os arquivos (`.github/workflows/`)

**Prática:** configurar um workflow simples para validar um projeto HTML/JavaScript, ou executar testes quando aplicável.

---

## Projeto Final

Repositório sugerido: `github-fundamentals`, contendo `README.md`, `LICENSE`, `.gitignore`, `index.html`, `style.css`, `script.js`, uma pasta `docs/` com `commits.md`, `branches.md` e `workflow.md`, e uma pasta `images/`.

## Checklist de conclusão

- [x] Inicializar um repositório Git
- [x] Fazer commits claros e organizados
- [x] Publicar um projeto no GitHub
- [x] Escrever um README profissional
- [x] Criar e mesclar branches
- [x] Resolver conflitos de merge
- [x] Usar .gitignore
- [x] Publicar um site com GitHub Pages
- [x] Organizar tarefas com Issues e Projects
- [x] Criar Pull Requests, mesmo em projetos pessoais
- [x] Criar Releases seguindo Versionamento Semântico
- [x] Entender o básico de GitHub Actions

## O que vem depois

Nível intermediário, focado em práticas de times de desenvolvimento:

- Git Flow e GitHub Flow
- Rebase (`git rebase`) e cherry-pick
- Tags e releases avançadas
- GitHub Actions para CI/CD
- Code Review
- Templates de Issues e Pull Requests
- Proteção de branches
- Colaboração em projetos Open Source
- Automatização de documentação e testes

[← Voltar ao Roadmap](../ROADMAP.md)
