# Briefing do projeto · Dashboard de Logística e Transportes

## Contexto do negócio

Uma empresa despacha mercadorias para todo o Brasil por meio de **seis transportadoras parceiras**: SudesteCargo, CentroFrete, VelozLog, TransBrasil, NordLog e NorteExpress. Os envios podem ser de frete **convencional** ou **urgente**.

A base reúne **1.755 entregas** feitas de janeiro a dezembro de 2025. Cada registro traz transportadora, tipo de frete, origem, destino, peso, valor da nota fiscal, valor do frete, data do pedido, prazo combinado, data prevista, data real de entrega e o tipo de desvio, quando houve.

A empresa tem uma meta de **85% de entregas no prazo** (OTD, On Time Delivery). Nos últimos meses, a área de operações percebeu mais atrasos e reclamações e quer entender o que está acontecendo.

Como stakeholder, quero saber se estamos cumprindo a meta, quais transportadoras e rotas puxam o resultado para baixo e quais problemas mais afetam as entregas.

## Objetivo principal

Medir o nível de serviço das entregas, identificar as causas dos atrasos e desvios e indicar onde agir para voltar a cumprir a meta de 85% de OTD.

## Perguntas de negócio

### 1. Nível de serviço

- Qual é o OTD geral do ano? Estamos acima ou abaixo da meta?
- Como o OTD evoluiu mês a mês?
- Quantas entregas atrasaram e por quantos dias, em média?

### 2. Transportadoras

- Qual é o OTD de cada transportadora?
- Quais transportadoras cumprem a meta de 85%?
- Quais concentram mais desvios?
- O custo do frete muda entre elas?

### 3. Tipo de frete e prazo

- O frete urgente entrega mais no prazo que o convencional?
- Quanto custa a mais o frete urgente?
- Prazos mais longos têm OTD menor?

### 4. Regiões

- Para onde vão as entregas?
- Quais regiões de destino têm o pior OTD?

### 5. Desvios

- Quantas entregas tiveram algum desvio?
- Quais são os desvios mais frequentes?
- Qual é o valor em nota fiscal das cargas extraviadas ou roubadas?
- Entregas com desvio atrasam mais?

## Entregáveis esperados

- Dashboard em Power BI com filtros por mês, transportadora e tipo de frete.
- Análise de causa raiz do OTD por transportadora.
- Análise executiva com os principais insights.
- Recomendações práticas para voltar a cumprir a meta.

## KPIs principais

- OTD (% de entregas no prazo) geral e por mês
- OTD por transportadora, região e tipo de frete
- Meta de OTD: 85%
- Quantidade e tipo de desvios
- Atraso médio, em dias
- Frete médio e frete sobre o valor da nota fiscal

## Pergunta central

> Por que o OTD caiu ao longo de 2025, e quais transportadoras, rotas e problemas precisam ser tratados para voltar a cumprir a meta de 85%?
