---
name: token-optimizer
short-description: Audita e reduz o contexto automático carregado pelo Claude Code, economizando tokens em qualquer projeto.
description: |
  Audita arquivos de contexto (CLAUDE.md, .claude/CLAUDE.md, AGENTS.md, MEMORY.md, hooks.json) e sugere otimizações para eliminar duplicações, unificar hooks e centralizar informações essenciais, reduzindo drasticamente o consumo de tokens por sessão.
---

# Token Optimizer Skill

## O que faz
- Analisa todos os arquivos de contexto carregados automaticamente pelo Claude Code.
- Identifica duplicações e referências expansivas (@arquivo).
- Sugere remoção de redundâncias e centralização de informações.
- Unifica hooks para evitar execuções desnecessárias.
- Gera um relatório com recomendações de otimização e estimativa de economia de tokens.

## Como usar
1. Invoque a skill para auditar o contexto do projeto.
2. Siga as recomendações do relatório para editar/remover arquivos e hooks.
3. Valide a redução de tokens em novas sessões.

## Exemplo de uso

"Audite e otimize o contexto do meu projeto para Claude Code."

A skill irá:
- Listar todos os arquivos carregados automaticamente.
- Apontar duplicações e referências expansivas.
- Sugerir como unificar hooks e centralizar contexto.
- Gerar um checklist de ações para implementar a economia de tokens.

## Observação
A skill não edita arquivos automaticamente, mas entrega um plano detalhado para você aplicar as mudanças com segurança.