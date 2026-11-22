# 📊 Dashboard de Análise de Varejo

Projeto de análise de dados comerciais desenvolvido com foco no monitoramento de indicadores-chave de desempenho (KPIs), comportamento de compra dos clientes e rentabilidade do portfólio de produtos.

---

## 🎯 Objetivo do Projeto

Transformar registros brutos de vendas em uma visão gerencial estruturada para responder a perguntas essenciais do negócio:
- Qual é a evolução do faturamento, volume de vendas e ticket médio ao longo do tempo?
- Quem são os clientes mais representativos e como está distribuído o perfil de consumo?
- Quais produtos e categorias concentram a maior receita e quais demandam atenção comercial?

---

## 🛠️ Ferramentas e Técnicas Utilizadas

- **ETL e Tratamento de Dados:** [Power Query / Excel / Python] — limpeza de registros, padronização de tipos de dados, tratamento de valores nulos e criação de colunas calculadas.
- **Modelagem e Métricas:** [DAX / Fórmulas Dinâmicas] — criação de medidas para Faturamento Total, Ticket Médio, Quantidade Vendida e Margem/Participação (%).
- **Visualização de Dados:** [Power BI / Excel] — construção de painel interativo com segmentadores de período, categoria e região.

---

## 🖥️ Estrutura do Dashboard

### 1. Visão Geral (Executiva)
Consolidado estratégico com os principais KPIs da operação (Faturamento, Volume de Pedidos e Ticket Médio), evolução temporal das vendas e comparativo de desempenho por canal/região.

![Visão Geral](imagens/01_visao_geral.png)

---

### 2. Análise de Clientes
Detalhamento da base de consumidores, destacando concentração de receita por perfil, recorrência de compra e ranking dos principais clientes.

![Análise de Clientes](imagens/02_analise_clientes.png)

---

### 3. Análise de Produtos
Avaliação de performance por categoria e SKU, identificando os itens campeões de venda, representatividade no faturamento total (Curva ABC) e oportunidades de giro de estoque.

![Análise de Produtos](imagens/03_analise_produtos.png)

---

## 💡 Principais Insights

- **[Insight 1 - Geral]:** Ex.: *O faturamento apresentou sazonalidade positiva no último trimestre, impulsionado pelo aumento no ticket médio.*
- **[Insight 2 - Clientes]:** Ex.: *Cerca de X% da receita está concentrada em um grupo específico de clientes recorrentes.*
- **[Insight 3 - Produtos]:** Ex.: *A categoria X lidera o volume de unidades vendidas, enquanto a categoria Y garante a maior margem unitária.*

---

## 📂 Como Visualizar

1. Faça o download do arquivo do dashboard na pasta [`dashboard/`](dashboard/).
2. Abra o arquivo utilizando o **[Power BI Desktop / Microsoft Excel]**.
3. Utilize os filtros laterais/superiores para navegar entre períodos, categorias e segmentos.
