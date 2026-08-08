# Módulo 6 — Branches

## Conceitos

**Branch (ramo)**
- Uma "cópia paralela" da linha do tempo do repositório, para mudanças sem afetar a branch principal.
- Criar uma branch não move você para ela automaticamente.

**Trocando de branch**
- Nada é apagado ao trocar de branch — o Git só exibe a versão dos arquivos correspondente àquela branch.

**Merge**
- Junta o conteúdo de uma branch de volta em outra.
- **Fast-forward**: quando a branch de destino não teve mudanças próprias — o Git só avança o histórico.
- **Merge commit**: quando as branches divergiram — o Git cria um commit especial unindo os caminhos.

**Por que usar arquivos diferentes em cada branch**
- Evita conflito de merge, quando duas branches alteram a mesma parte do mesmo arquivo.

## Comandos usados

| Comando | O que faz |
|---|---|
| `git branch` | Lista as branches existentes |
| `git branch nome` | Cria uma nova branch |
| `git switch nome` | Troca para a branch especificada |
| `git merge nome` | Junta o conteúdo da branch na branch atual |
| `git log --oneline` | Mostra o histórico resumido, uma linha por commit |

## Prática realizada
Branches `feature/soma` e `feature/subtracao`, cada uma com um commit próprio, mescladas de volta ao `master`.

[← Voltar ao Roadmap](../ROADMAP.md)
