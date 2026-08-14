---
title: AGENTS — MMO
project: MMO Sandbox
status: canonical
type: agent-instructions
tags:
  - mmo
  - agentes
  - governanca
  - obsidian
related:
  - "[[README]]"
  - "[[docs/03-squads/Squad-Living-Economy]]"
  - "[[docs/06-rouanet/00-Hub-Rouanet]]"
---

# AGENTS.md

Este arquivo define como agentes de IA devem trabalhar no projeto MMO. Ele não substitui os documentos canônicos de visão, game design ou decisões.

## Ordem de leitura

Antes de executar tarefa relevante:

1. ler `README.md`;
2. consultar [[docs/01-visao/Visao-do-Jogo]] e [[docs/01-visao/Principios-de-Design]];
3. consultar o documento canônico específico do tema;
4. para análise do edital, consultar [[docs/06-rouanet/00-Hub-Rouanet]];
5. distinguir explicitamente fato, hipótese, proposta, decisão e item a validar.

## Método de atualização incremental

Toda atualização deve seguir:

**ANALISAR → COMPARAR → IDENTIFICAR DELTA → PRESERVAR → CORRIGIR/ADICIONAR → VALIDAR**

Não recriar documentos consolidados como padrão.

- **Delta:** menor conjunto de mudanças necessário para levar o estado atual ao novo estado correto.
- **Consolidar:** integrar conhecimento válido sem resumir a ponto de perder decisões ou hipóteses úteis.
- **Corrigir:** substituir somente informação comprovadamente incorreta ou superada.
- **A VALIDAR:** manter explicitamente quando ainda não houver evidência suficiente.

## Prioridade atual

O projeto está na fase de definição e desenvolvimento do **piloto jogável**.

O piloto deve priorizar:

1. experiência do jogador;
2. core loop;
3. simplicidade;
4. diversão e desejo de repetição;
5. economia percebida pelo jogador;
6. menor escopo que demonstre a identidade do MMO.

RMT, bots, arquitetura definitiva, escalabilidade e economia de longo prazo continuam relevantes como validações internas, mas não devem ampliar o escopo do piloto sem necessidade.

## Método do squad

Toda exploração relevante usa três movimentos:

1. **DIVERGIR** — gerar possibilidades sem matar ideias prematuramente;
2. **STRESS TEST** — testar diversão, simplicidade, economia, execução, riscos e aderência ao objetivo;
3. **CONVERGIR** — selecionar a versão mais simples e forte.

O Red Team não deve impedir a divergência; ele atua antes da convergência.

## Source of Truth

1. GitHub — documentos canônicos versionados;
2. fontes oficiais externas — quando houver edital, norma ou requisito atual;
3. discussões — origem de hipóteses, somente promovidas a decisão após consolidação;
4. exports e derivados — nunca fonte primária.

## Regras de preservação

- Não transformar referência em decisão sem aprovação.
- Não inventar dados ausentes.
- Não criar complexidade por realismo.
- Não introduzir mercados intermediários como objetivo do projeto.
- Não associar automaticamente bioma a tier.
- Não expandir o piloto para representar o MMO completo.
- Preservar compatibilidade com Markdown e Obsidian.

## Git e commits

- Preferir commits pequenos e semanticamente claros.
- Um commit deve representar um delta compreensível.
- Não misturar alteração conceitual de game design com análise jurídica/regulatória quando puderem ser separadas.
