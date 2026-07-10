---
tags:
  - mmo
  - adr
  - economia
aliases:
  - ADR 0001
related:
  - "[[../01-visao/Visao-do-Jogo]]"
  - "[[../02-game-design/Economia-Viva]]"
  - "[[../02-game-design/RMT-e-Abuso-Economico]]"
status: accepted
---

# ADR-0001: Foco Econômico Antes de Sistemas de Combate

## Status

Aceito inicialmente.

## Contexto

A discussão começou a partir da essência de Albion Online. O ponto mais relevante identificado não foi o combate em si, mas o ciclo econômico que mantém o mundo vivo.

## Decisão

Antes de definir classes, skills, visual ou narrativa, o projeto deve modelar:

- ciclo econômico principal;
- durabilidade, reparo e destruição;
- loot conectado à produção;
- recursos raros de mobs;
- riscos de RMT, bots e guildas dominantes;
- simplicidade do loop para novos jogadores.

## Consequências

- Combate será tratado como consumidor e gerador de risco econômico.
- PvE será avaliado pelo impacto na economia e diversão.
- Crafting deve ser simples o suficiente para ser entendido, mas relevante o suficiente para sustentar o mundo.
- Toda mecânica econômica passará por Red Team.
