---
title: Continente Royal — Candalor
project: MMO Sandbox
status: concept-approved
type: world-map
tags: [mmo, royal, candalor, mapa, zonas, biomas]
related:
  - "[[Biomas-Regioes-e-Tiers]]"
  - "[[Piloto-Cerrado]]"
  - "[[../01-visao/Visao-do-Jogo]]"
---
# Continente Royal — Candalor

## Status e proveniência
Consolidação das decisões visuais e territoriais discutidas com o usuário até 2026-11-04. **Referência conceitual aprovada para evolução, não mapa de produção nem grafo final de mapas.** A imagem isométrica v0.4 foi produzida na conversa; seu arquivo binário não está versionado neste commit. Nomes de cidades periféricas que aparecem na ilustração são **rótulos de trabalho**, não nomes canônicos aprovados. Não confundir a proposta do MMO com regras oficiais de Albion.

## Princípios fechados
- Inspiração na estrutura de mapas conectados do Continente Royal de Albion, com geografia de fantasia referenciada no Brasil e na América do Sul; **não** copiar literalmente o mapa de Albion.
- **Candalor** substitui Brasília como **capital central** do continente, homenagem aos candangos/construtores de Brasília.
- O **Cerrado domina o centro** e deve continuar visível em volta de Candalor; **sem cordilheiras artificiais** cercando a capital.
- **Candalor é cercada por mapas Red Zone**; Red Zone pode ter **T5**, além de T6 e T7.
- **Não há Black Zone no continente Royal**.
- **Cor de zona aparece somente no escudo/ícone de tier de cada mapa**. Nunca colorir, tingir ou sombrear o terreno, o anel ao redor da capital ou os limites de biomas em azul/amarelo/vermelho. O terreno mostra o bioma natural.
- Ambiente/bioma, tier e risco são **atributos independentes**. Cada mapa é um nó com biome, tier, zone_color, ligações e pontos de interesse.
- Biomas devem **convergir naturalmente para o Cerrado central**, com transições ambientais perceptíveis, não barreiras montanhosas artificiais.
- A orientação visual se inspira na América do Sul: **Floresta Amazônica no norte/noroeste**, **Caatinga no nordeste**, **Pantanal/Alagado no sudoeste**, **Mata Atlântica no leste/sudeste**, **Frio no sul**, **Cerrado central**.
- A inspiração visual é uma rotação aproximada de 160° do arranjo geral do mapa Royal de Albion, adaptada à distribuição ambiental sul-americana; **não é uma transformação cartográfica exata**.

## Cinco famílias mecânicas, seis identidades visuais
| Família mecânica | Região/identidade visual | Localização | Paisagem e recursos referenciais |
|---|---|---|---|
| Floresta | Amazônia | Norte/Noroeste | mata tropical densa, rios largos, madeira, fibras, fauna |
| Floresta | Mata Atlântica | Leste/Sudeste | floresta úmida, serras costeiras e vales, cachoeiras, madeira e fibras |
| Cerrado | Cerrado | Centro | campos, veredas, chapadas suaves, mineração e rotas |
| Alagado | Pantanal | Sudoeste | áreas inundáveis, ilhas, pesca, couro |
| Árido | Caatinga | Nordeste | vegetação espinhosa, terrenos secos, minerais, fibras resistentes |
| Frio | Sul/Andes | Sul | campos frios, montanhas e neve, metais e recursos de altitude |

A Mata Atlântica é uma **segunda identidade florestal**, não um sexto sistema mecânico obrigatório. Pampas podem surgir como transição visual. A cidade-base adicional no setor da Mata Atlântica **não está aprovada**; o rótulo "Verde Mar" da ilustração é provisório.

## Capital e polos econômicos
- **Candalor**: capital continental no Cerrado, centro político/visual e nó de circulação; seu papel econômico preciso deve ser balanceado para não eliminar a relevância dos mercados regionais.
- Cinco cidades-base regionais permanecem a **hipótese de estrutura**, uma por família mecânica principal. Na ilustração: Jatobá (Amazônia), Ipê (Cerrado), Araguaia (Pantanal), Mandacaru (Caatinga), Araucária (Frio). **Esses nomes periféricos são provisórios**.
- Candalor é **adicional** aos cinco polos regionais na representação atual; total conceitual de **seis centros nomeados**, sujeito a decisão sobre o papel da cidade Cerrado/Ipê.
- Mata Atlântica pode ter mapas e assentamentos sem receber cidade-base independente.

## Tiers e cores — convenção do mapa em discussão
| Zona | Tiers de referência para o nosso mapa | Risco |
|---|---|---|
| Blue | T2–T5 | sem PvP hostil comum; sem perda integral de itens |
| Yellow | T5–T6 | PvP condicionado; sem full loot comum |
| Red | **T5–T7** | PvP letal com sinalização; full loot |
| Black | **não existe neste continente** | não se aplica |

Essas faixas são **parâmetros de design do nosso continente**, não afirmação de distribuição oficial atual de Albion. **Red T8 está excluído** desta versão. Não colorir a progressão T2–T7 como se cada tier tivesse uma única cor fixa: **T5 pode ser Blue, Yellow ou Red**; T6 pode ser Yellow ou Red. O escudo de cada nó deve mostrar simultaneamente tier e cor de zona.

## Estrutura de mapas
- Um **mapa jogável = um nó** com identificador, bioma/variação, tier, zona (Blue/Yellow/Red), conexões, cidade próxima, recursos e pontos de interesse.
- Rotas e limites devem ser legíveis, mas **sem pintar áreas de terreno** com a cor de PvP.
- O cinturão Red ao redor de Candalor é uma **propriedade do grafo de mapas**, não um anel vermelho de montanhas, lava ou filtro.
- As regiões externas apresentam zonas Blue/Yellow e rotas de aproximação; a distribuição de nós por tier e cor, as distâncias e a geometria ainda precisam de validação.
- Referência conceitual de conexões: Amazônia ↔ Cerrado; Caatinga ↔ Cerrado; Pantanal ↔ Cerrado; Mata Atlântica ↔ Cerrado; Sul/Frio ↔ Cerrado; rotas secundárias podem conectar biomas adjacentes. Não tratar essas arestas como topologia final.

## Diretrizes para arte
1. Priorizar leitura de geografia e vegetação, especialmente Cerrado em torno da capital.
2. Mostrar rios, veredas e transições orgânicas entre biomas até o centro.
3. Deixar Blue/Yellow/Red **apenas nos escudos dos nós**; sem contornos luminosos de zona no chão.
4. Nunca inserir T8 Red, Black Zone ou cordilheiras no entorno de Candalor.
5. Não transformar automaticamente os rótulos de trabalho em nomes oficiais.
6. Toda arte futura deve ser confrontada com esta especificação antes de ser apresentada como representação fiel.

## Decisões em aberto
- Nome final dos cinco polos e existência/posição de cidade-base exclusiva da Mata Atlântica.
- Papel de Ipê versus Candalor no Cerrado.
- Grafo de mapas, número de nós por tier/zona, conexões e regras de acesso.
- Geometria, escala e locais definitivos de recursos, PvE e mercados.
- Verificação posterior das regras de Albion se forem usadas como benchmark atual.

Este documento é **exclusivamente game design**; análises de financiamento ficam em trilha separada.
