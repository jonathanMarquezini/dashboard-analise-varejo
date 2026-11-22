# 📊 Dashboard de Análise de Varejo (Power BI)

Projeto de análise de dados comerciais desenvolvido no **Power BI** com foco no acompanhamento de indicadores de vendas, comportamento da base de clientes e desempenho de categorias e produtos no varejo de tecnologia/eletrônicos.

---

## 🎯 Objetivo do Projeto

Consolidar os dados comerciais em um painel interativo dividido em três visões complementares para apoiar a tomada de decisão:
- Monitorar o faturamento total, quantidade vendida, descontos, base de clientes e ticket médio.
- Analisar o perfil demográfico, a frequência de compra e a distribuição geográfica dos clientes.
- Identificar produtos destaque, categorias com maior receita e participação no faturamento.

---

## 🛠️ Ferramentas e Abordagem

- **Power BI:** modelagem de dados, criação de medidas e construção dos visuais interativos.
- **Métricas acompanhadas:** Total de Vendas, Quantidade Vendida, Total de Descontos, Quantidade de Clientes, Ticket Médio, Frequência Média de Compra, Idade Média dos Clientes, Receita por Produto e Participação por Categoria.
- **Filtros e segmentações:** análise por **Ano**, **Mês** e **Canal de Venda** (Online e Loja Física), além de comparativos temporais entre **2023 e 2024**.

---

## 🖥️ Estrutura do Dashboard

### 1. Visão Geral
Painel executivo com os principais indicadores e distribuições de venda:
- **KPIs principais:** Total de Vendas de **R$ 15,70 Mi**, Quantidade Vendida de **5.303** unidades, Total de Descontos de **R$ 1,02 Mi**, **300** clientes e Ticket Médio de **R$ 52,34 Mil**.
- **Canais de atendimento:** **Online** representa **R$ 9,40 Mi (59,87%)** e **Loja Física** representa **R$ 6,30 Mi (40,13%)**.
- **Visuais incluídos:** evolução mensal de vendas (2023 x 2024), distribuição de vendas por estado, distribuição por canal de atendimento e total de vendas por categoria de produto (liderado por *Informática*, com **R$ 4.735,31 Mil**).

### 2. Análise de Clientes
Visão focada no relacionamento e perfil da base de clientes:
- **KPIs principais:** **300** clientes ativos, Ticket Médio por Cliente de **R$ 52,34 Mil**, Frequência Média de Compra de **17,68** e Idade Média dos Clientes de **35,87** anos.
- **Perfil por gênero:** distribuição equilibrada entre **Feminino** (**155** clientes / **51,67%**) e **Masculino** (**145** clientes / **48,33%**).
- **Visuais incluídos:** clientes cadastrados por mês (comparativo 2023 x 2024), distribuição por gênero e distribuição geográfica por estado. *(Nota: o visual de novos clientes no ano atual e o cartão correspondente aparecem sem dados no recorte exibido).*

### 3. Análise de Produtos
Visão voltada ao desempenho do catálogo e rentabilidade por linha de produto:
- **KPIs principais:** Receita Total de Produtos de **R$ 15,70 Mi**, Quantidade Vendida Total de **5.303**, **HD Externo 1TB** como produto mais vendido, **Smartwatch Esportivo** como produto com menor venda e **Informática** como top categoria.
- **Visuais incluídos:** evolução mensal da receita (2023 x 2024), Top 10 produtos por receita (liderado por *Teclado Mecânico RGB* com **1,57 Mi**), receita total por categoria e participação das categorias no faturamento total (*Informática* com **4,74 Mi / 30,16%**, *Armazenamento* com **1,84 Mi / 11,7%** e *Periféricos* com **1,82 Mi / 11,61%**).

---

## 💡 Principais Observações do Painel

- O canal **Online** concentra a maior parcela do faturamento (**59,87%**), enquanto a **Loja Física** responde por **40,13%**[cite: 8].
- **Informática** lidera com folga a receita por categoria (**R$ 4,74 Mi**, cerca de **30,16%** do faturamento)[cite: 8, 10], seguida por *Armazenamento* e *Periféricos*[cite: 8, 10].
- A base de **300 clientes** apresenta frequência média de **17,68** compras e divisão próxima entre os gêneros feminino e masculino[cite: 8, 9].

---

## 📂 Como Abrir o Arquivo

1. Faça o download do arquivo `.pbix` do projeto (quando adicionado ao repositório).
2. Abra o arquivo no **Power BI Desktop**.
3. Utilize os filtros de **Ano**, **Mês** e **Canal de Venda** para explorar os dados.
