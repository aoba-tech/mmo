---
tags:
  - mmo
  - obsidian
  - mapa
  - piloto
aliases:
  - MMO Design Vault
related:
  - "[[docs/01-visao/Visao-do-Jogo]]"
  - "[[docs/01-visao/Principios-de-Design]]"
  - "[[docs/02-game-design/Core-Loop]]"
  - "[[docs/02-game-design/Biomas-Regioes-e-Tiers]]"
  - "[[docs/02-game-design/Piloto-Cerrado]]"
  - "[[docs/02-game-design/Continente-Royal-Candalor]]"
  - "[[docs/03-squads/Squad-Living-Economy]]"
status: draft
---

# MMO Design Vault

Este vault organiza a discussão de um MMO sandbox inspirado em princípios econômicos observados em Albion Online, mas com identidade própria, foco em simplicidade, diversão, envolvimento, economia viva e worldbuilding inspirado em referências brasileiras e sul-americanas.

## Estado atual

O projeto está na fase de definição do **piloto jogável**.

O piloto deve provar a experiência central do MMO antes de tentar representar todo o mundo, toda a economia ou todos os riscos sistêmicos.

## Mapa principal — jogo

- [[docs/01-visao/Visao-do-Jogo]]
- [[docs/01-visao/Principios-de-Design]]
- [[docs/02-game-design/Core-Loop]]
- [[docs/02-game-design/Economia-Viva]]
- [[docs/02-game-design/Biomas-Regioes-e-Tiers]]
- [[docs/02-game-design/Continente-Royal-Candalor]]
- [[docs/02-game-design/Piloto-Cerrado]]
- [[docs/02-game-design/Durabilidade-Reparo-e-Destruicao]]
- [[docs/02-game-design/Mercado-Negro-e-Loot]]
- [[docs/02-game-design/Recursos-Raros-de-Mobs]]
- [[docs/02-game-design/RMT-e-Abuso-Economico]]
- [[docs/03-squads/Squad-Living-Economy]]
- [[docs/04-red-team/Red-Team-RMT-Bots-Guildas]]
- [[docs/05-decisoes/ADR-0001-Foco-Economico]]

## Pergunta central do jogo

> Qual ciclo faz o mundo continuar vivo e faz o jogador querer repetir a experiência?

## Hipótese atual

O motor principal combina:

```text
Coleta
  ↓
Refino
  ↓
Fabricação
  ↓
Uso
  ↓
Desgaste / Perda / Quebra
  ↓
Reposição
  ↓
Nova exploração
```

com desejo, risco, conquista, apego e perda.

## Estrutura ambiental

O Continente Royal de **Candalor** trabalha com cinco famílias mecânicas de ambiente e seis identidades visuais, incluindo as duas florestas; a configuração definitiva dos polos regionais ainda está em discussão:

- Floresta Amazônica — Norte/Noroeste;
- Mata Atlântica — Leste/Sudeste (segunda identidade da família Floresta);
- Cerrado — Centro-Oeste;
- Alagado — Pantanal;
- Árido — Caatinga;
- Frio — Sul + referências andinas/chilenas.

> **Ambiente define identidade. Tier define progressão. Zona define risco.**

**Candalor** é a capital central, inspirada nos construtores de Brasília. O Cerrado central permanece visível e é cercado por mapas Red Zone (inclusive T5). No Royal não há Black Zone; cores de Blue, Yellow e Red aparecem **somente nos ícones de tier**, nunca como sombra sobre o terreno. Ver [[docs/02-game-design/Continente-Royal-Candalor]].

## Piloto

O recorte atual prioriza **uma cidade-base no Cerrado e múltiplos tiers do mesmo ambiente**, suficientes para demonstrar progressão, coleta, crafting, PvE, economia e ciclo de vida dos itens.

## Regra de design

Toda mecânica deve fortalecer a experiência sem ampliar complexidade desnecessariamente. RMT, bots, exploits e economia de longo prazo permanecem validações internas, mas não dirigem o escopo do piloto.
