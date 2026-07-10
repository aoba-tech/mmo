---
tags:
  - mmo
  - durabilidade
  - reparo
  - destruicao
aliases:
  - Durabilidade e Reparo
related:
  - "[[Economia-Viva]]"
  - "[[Core-Loop]]"
  - "[[RMT-e-Abuso-Economico]]"
status: draft
---

# Durabilidade, Reparo e Destruição

## Problema

Se o reparo apenas restaura o item sem consequência estrutural, itens de alto valor vivem demais. Isso reduz demanda por produção nova e favorece acumulação econômica.

## Proposta simples

Separar dois atributos:

- **Durabilidade atual**: condição operacional do item.
- **Integridade máxima**: limite estrutural depois de reparos sucessivos.

## Exemplo

```text
Espada 100/100
Após uso intenso: 34/100
Após reparo: 92/92
Após novo desgaste: 25/92
Após novo reparo: 81/81
```

## Decisão econômica

Com o tempo, o jogador precisa escolher:

- reparar e continuar usando;
- vender como item desgastado;
- destruir para recuperar parte dos recursos;
- substituir por item novo.

## Objetivo

Fazer o item circular, envelhecer e sair do sistema sem tornar o jogo punitivo demais.

## Cuidado de design

A perda estrutural não pode ser tão agressiva que o jogador sinta que todo progresso é inútil. Deve ser previsível, comunicada e balanceada por tier, raridade e risco da atividade.
