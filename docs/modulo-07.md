# Módulo 7 — Merge Conflicts

## Conceitos

**Conflito de merge**
- Acontece quando duas branches alteram a **mesma linha** do **mesmo arquivo** de formas diferentes.
- O Git não tem contexto para saber qual versão é a "correta" — por isso para e devolve a decisão ao humano.

**Marcação visual do conflito**
- `<<<<<<< HEAD` → início do conteúdo da branch atual
- (conteúdo da branch atual)
- `=======` → divisória entre as duas versões
- (conteúdo da branch sendo mesclada)
- `>>>>>>> nome-da-branch` → fim do conteúdo da outra branch

**Resolvendo um conflito**
1. Decidir qual versão manter (ou escrever uma nova)
2. Remover todas as marcações
3. Deixar só o texto final, limpo
4. Marcar como resolvido com `git add`
5. Finalizar com `git commit`

**`git status` durante um conflito**
- Mostra "Você tem caminhos não mesclados" e lista os arquivos com "ambos modificados".

## Comandos usados

| Comando | O que faz |
|---|---|
| `git add arquivo` (durante conflito) | Marca o conflito como resolvido |
| `git commit` (sem `-m`) | Finaliza o merge com mensagem padrão pré-escrita |

## Prática realizada
Duas branches (`conflito-a` e `conflito-b`) alterando a mesma linha do README, mescladas gerando conflito real, resolvido manualmente.

[← Voltar ao Roadmap](../ROADMAP.md)
