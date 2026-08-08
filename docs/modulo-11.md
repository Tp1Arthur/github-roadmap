# Módulo 11 — Pull Requests

## Conceitos

**Pull Request (PR)**
- Um pedido formal para mesclar uma branch dentro de outra, feito pelo site do GitHub, em vez de direto no terminal.
- Cria um **checkpoint de qualidade**: mostra visualmente o diff e permite comentários/revisão antes do merge se tornar definitivo.
- Vale a pena usar mesmo trabalhando sozinho, simulando o ambiente de um time.

**Fluxo completo de um PR**

criar branch → commits → push da branch → abrir PR → revisar → merge pelo site → git pull local

**Push de uma branch nova**
- Quando a branch ainda não existe no remoto, usa-se `-u` para criá-la lá e associá-la à local.

## Comandos usados

| Comando | O que faz |
|---|---|
| `git push -u origin nome-da-branch` | Envia uma branch nova e a associa à local |

## Prática realizada
Branch `feature/login`, enviada ao GitHub, PR aberto e mesclado pelo site, sincronizado depois com `git pull`.

[← Voltar ao Roadmap](../ROADMAP.md)
