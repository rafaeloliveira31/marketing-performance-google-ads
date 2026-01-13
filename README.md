# 📊 Marketing Performance – Google Ads (Jan–Jun/2025)

## 📌 Visão Geral
Projeto de análise de dados focado na performance de campanhas de Google Ads, avaliando funil de conversão, impacto financeiro e oportunidades de ganho.

## 🎯 Problema de Negócio
A empresa investe continuamente em campanhas de Google Ads, porém não possui clareza sobre onde ocorrem as maiores perdas de valor ao longo do funil, nem sobre quais campanhas realmente geram retorno financeiro.

O desafio central é entender:
- Se o investimento em mídia está sendo eficiente
- Onde estão os gargalos de conversão
- Qual é o impacto financeiro das conversões perdidas
- Quais campanhas devem ser priorizadas ou otimizadas

## 🌍 Contexto
O conjunto de dados analisados contempla o desempenho de campanhas de Google Ads entre janeiro e junho de 2025, incluindo métricas de:
- Impressões
- Cliques
- Conversões
- Custos
- Receita
- Lucro
- ROI, CPA, CPC e taxas de conversão

Os dados foram organizados e analisados com foco em performance, funil de conversão e impacto financeiro, resultando em um dashboard interativo desenvolvido no Power BI.

## 📐 Premissas da Análise
Para garantir consistência e coerência nos cálculos, foram adotadas as seguintes premissas:
- Conversão representa uma venda concluída
- Receita é gerada exclusivamente a partir das conversões
- Ticket médio implícito calculado a partir da receita total ÷ conversões
- ROI calculado como: (Receita - Custo) / Custo
- Ganho potencial considera a diferença entre conversões atuais e uma conversão projetada (ideal), mantendo o mesmo ticket médio
- Perda financeira representa a receita não capturada devido à baixa taxa de conversão
  
## 🧠 Estratégias da Solução
A solução foi estruturada em 4 camadas analíticas, refletidas nas páginas do dashboard:

### 1. Visão Geral
- KPIs estratégicos (Custo, Receita, Lucro, ROI, Conversão Geral)
- Evolução mensal de custos, receita e potencial de ganhos

### 2. Desempenho das Campanhas
- Análise comparativa de campanhas por receita, custo, CPC, ROI e taxa de conversão

### 3. Funil de Conversão
- Análise do funil macro (Impressões → Cliques → Conversões)
- Identificação do principal gargalo do processo

### 4. Financeiro e Impacto nas Vendas
- CPA ao longo do tempo
- Lucro por campanha
- Conversões perdidas vs. ganho potencial

Essa abordagem permite conectar métricas operacionais → impacto financeiro → tomada de decisão.

## 🔍 Insights da Análise
- O funil apresenta forte queda entre cliques e conversões, indicando que o principal gargalo está na experiência pós-clique (landing page, oferta ou processo de compra).
- Apesar da taxa de conversão geral ser baixa (0,07%), o ROI total é elevado (239,74%), mostrando que as conversões geradas são altamente rentáveis.
- A campanha Chuteiras Performance se destaca como a mais eficiente, com:
  - Maior receita
  - Maior lucro
  - ROI superior a 470%
- O CPA apresenta tendência de queda ao longo dos meses, indicando melhoria na eficiência das campanhas.
- Existe um ganho potencial estimado de R$ 4,88 milhões, caso parte das conversões perdidas seja recuperada.

## 📈 Resultados
- Receita total: R$ 376,94 mil
- Custo total: R$ 110,95 mil
- Lucro total: R$ 265,99 mil
- ROI geral: 239,74%
- Conversões perdidas: 27,53 mil
- Perda financeira estimada: R$ 4,50 milhões
- Ganho potencial: R$ 4,88 milhões

Os resultados mostram que, embora o retorno atual seja positivo, há um grande espaço para crescimento sem aumento proporcional de investimento, apenas otimizando conversões.

## 🚀 Próximos Passos
Com base nos achados, recomenda-se:
- Otimizar páginas de destino e fluxo de conversão (UX, copy e velocidade)
- Realocar orçamento para campanhas com maior ROI e menor CPA
- Testar estratégias de remarketing para usuários que clicaram e não converteram
- Acompanhar métricas de funil com maior granularidade (por dispositivo, canal e público)
- Definir metas de conversão projetada para mensurar ganhos incrementais

## 🔚 Consideração Final
Este projeto demonstra a aplicação de análise de dados para transformar métricas de marketing em insights financeiros acionáveis, conectando performance operacional ao impacto direto no resultado do negócio.

## 🛠️ Ferramentas Utilizadas
- Power BI
- DAX
- Google Ads (dados simulados/reais)
- Excel / CSV

## 📷 Dashboard
![Visão Geral](img1.png) 

![Desempenho das Campanhas](img2.png)

![Desempenho das Campanhas - pt 2](img3.png)

![Funil + Conversões](img4.png)

![Financeiro](img5.png)
