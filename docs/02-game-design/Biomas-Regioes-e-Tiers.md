---
title: Biomas, Regiões e Tiers
project: MMO Sandbox
status: hypothesis
type: world-design
tags:
  - mmo
  - biomas
  - regioes
  - tiers
  - worldbuilding
related:
  - "[[../01-visao/Visao-do-Jogo]]"
  - "[[Core-Loop]]"
  - "[[Economia-Viva]]"
  - "[[Piloto-Cerrado]]"
  - "[[Continente-Royal-Candalor]]"
---

# Biomas, Regiões e Tiers

Este documento pertence ao **game design canônico do MMO**. Sua definição independe de edital, mecanismo de financiamento ou estratégia de captação.

## Princípio central

> **Ambiente define identidade. Tier define progressão. Zona define risco.**

Essas três dimensões devem permanecer independentes.

## Estrutura macro do mundo

O mundo utiliza **cinco famílias mecânicas de ambiente**, com **seis identidades visuais**: Amazônia e Mata Atlântica compartilham a família Floresta. A organização atual do Continente Royal e a capital **Candalor** estão detalhadas em [[Continente-Royal-Candalor]]. A hipótese anterior de uma cidade-base por família permanece sujeita à definição do papel da capital e do polo Cerrado.

| Ambiente | Referência principal | Identidade | Papel econômico inicial |
|---|---|---|---|
| Floresta | Amazônia / Norte | mata densa, rios, umidade | recursos florestais, fibras, fauna, exploração |
| Cerrado | Centro-Oeste | campos, chapadas, árvores retorcidas, veredas | mineração, recursos de campo, rotas terrestres |
| Alagado | Pantanal | rios, áreas inundadas, ilhas, fauna aquática | pesca, couro, recursos de áreas úmidas |
| Árido | Caatinga | solo pedregoso, seca, vegetação espinhosa | minerais, fibras resistentes, recursos escassos |
| Frio | Sul + Andes/Chile | campos frios, serras, neve, montanhas | metais raros, recursos de altitude, criação animal |

**Mata Atlântica** é uma identidade florestal visual distinta, no leste/sudeste, compartilhando a família mecânica Floresta com a Amazônia. **Pampas** podem aparecer como variação ou transição, sem novo tipo-base.

## Polos regionais e capital Candalor

O modelo considera cinco polos regionais (nomes provisórios) e **Candalor**, capital central no Cerrado, adicional na representação atual. A configuração definitiva das cidades e o papel do polo Cerrado ainda precisam ser decididos. Cada polo regional funciona como centro econômico, social e logístico.

```text
Cidade-base
   ↓
Mercado / Craft / Refino / Serviços
   ↓
Territórios do ambiente
   ↓
Conexões com outras regiões
```

A cidade não é apenas cenário. Ela ancora a economia daquela região.

## Regiões conectadas

A geografia deve gerar circulação e comércio naturalmente.

Exemplo conceitual atualizado (não é grafo final):

```text
     AMAZÔNIA (N/NW)        CAATINGA (NE)
              \\              /
               CERRADO / CANDALOR
              /       |       \\
     PANTANAL (SW)  FRIO (S)  MATA ATLÂNTICA (E/SE)
```

Candalor é cercada por mapas Red Zone, sem relevo montanhoso artificial. A cor da zona deve aparecer apenas no ícone de tier do mapa; não se deve colorir o terreno.

A topologia final pode mudar. O princípio é que os ambientes se conectem e criem rotas de deslocamento, risco, arbitragem e circulação de recursos.

## Tier dentro de cada ambiente

Um ambiente não representa uma etapa única de progressão.

Exemplo:

```text
Cerrado T2
Cerrado T3
Cerrado T4
Cerrado T5
Cerrado T6
Cerrado T7
```

O mesmo princípio vale para as demais regiões, conforme balanceamento futuro. **No Continente Royal em discussão, os mapas representados vão de T2 a T7, sem Red T8 e sem Black Zone.** Referência atual: Blue T2–T5; Yellow T5–T6; Red T5–T7 (inclusive Red T5). Tier não determina sozinho a cor da zona: um T5 pode ter mais de uma classificação de risco. Ver [[Continente-Royal-Candalor]].

### Intensidade por tier

Sem criar um novo bioma:

- tiers baixos: áreas mais acessíveis, recursos comuns e infraestrutura próxima;
- tiers médios: território mais selvagem, recursos melhores e maior deslocamento;
- tiers altos: regiões extremas, recursos excepcionais, mobs mais perigosos e maior risco.

## Distribuição de recursos

Evitar exclusividade rígida como regra geral.

Um ambiente pode ter **vantagem relativa** em certos recursos sem torná-los absolutamente inexistentes nas demais regiões. Isso cria motivos para viajar sem transformar a geografia em trava artificial.

## Worldbuilding

As referências territoriais podem aparecer por meio de:

- paisagem;
- fauna e flora;
- materiais e recursos;
- arquitetura;
- ritmos e sons;
- modos de produção;
- padrões de ocupação territorial;
- mitos e narrativas reinterpretados com cuidado.

A intenção não é reproduzir literalmente o Brasil ou a América do Sul, mas transformar referências reais em uma linguagem de fantasia coerente.

## Anti-objetivos

- um bioma por tier;
- dezenas de ambientes-base;
- mapa enciclopédico dos biomas brasileiros;
- cada região com sistemas completamente diferentes;
- cadeias econômicas complexas apenas para justificar diversidade regional.
