# Projeto de Data Analytics com Power BI

## Sobre o Projeto
Este é um projeto de portfólio focado na criação de um relatório financeiro interativo. O desenvolvimento foi guiado pelos pontos a serem considerados no desafio, com atenção especial à disposição dos visuais, usabilidade (UX/UI) e em como o cliente irá consumir o conteúdo. 

## Requisitos do Desafio
O dashboard foi construído respeitando estritamente as diretrizes do projeto:
* Estruturação em múltiplas páginas, dependendo da disposição dos visuais.
* Desenvolvimento da página detalhes conforme mostrado no desafio de projeto.
* Criação de todas as medidas necessárias para as análises financeiras.
* Implementação dos visuais que podem compor o relatório, incluindo:
  * Visuais sobre os TOP3 Produtos.
  * Visuais destacando os principais países em termos de vendas e/ou profit.
  * Gráfico de dispersão sobre Unidades vendidas e Vendas por mês.
  * Visuais focados em agrupamentos de dados.
  * Visuais voltados para a compartimentação dos dados.

## Estrutura do Relatório e Visuais

O projeto foi expandido e estruturado em seis páginas interativas para garantir uma navegação fluida, utilizando técnicas avançadas de interatividade e um design em *Dark Mode* para melhor contraste:

### 1. Home Page
Uma tela de entrada amigável com o título "Report Financeiro". Ela conta com um botão interativo de "Explorar análise", que direciona o usuário diretamente para as visões gerenciais, oferecendo uma experiência de navegação profissional.

[!](./Imagens/HomePage.jpg)

### 2. Principal (Sales Report)
Esta página atua como o painel gerencial de alto nível, trazendo um panorama geral das vendas com alternância dinâmica de visuais:
* **Cartões de Indicadores (KPIs):** Apresentam o resumo financeiro com o Total de Vendas (118,73 Mi), Unidades Vendidas (1,13 Mi), Soma de Descontos e Soma de COGS.
* **Análise Temporal:** Um gráfico de área mostrando a evolução da "Soma de Sales por Mês" ao longo do ano.
* **Interatividade com Indicadores (Bookmarks):** Botões interativos que permitem ao usuário alternar a visualização no mesmo espaço da tela. É possível trocar a Análise de Segmentos entre um **Gráfico de Rosca** (Pie Chart) e um **Gráfico de Barras** (Bar Chart), e a Visão Geográfica entre um **Treemap** e um **Mapa** (Map Chart).
* **Performance de Produtos:** Um gráfico de barras horizontais destacando a performance individual dos produtos.

[!](./Imagens/Principal(A).PNG)
[!](./Imagens/Principal(B).PNG)

### 3. Detalhes (Report de Lucro Detalhado)
Página voltada para o aprofundamento analítico e segmentação avançada:
* **Análise Mensal e Semestral:** Um gráfico de colunas agrupadas destacando o Total de Vendas por Mês, complementado por botões interativos para alternar as visões de "Semestre" e "Meses".
* **Detalhamento em Matriz:** Uma tabela estruturada que quebra os resultados por Trimestre (Qtr 1 a Qtr 4) e por ano (2013 e 2014), facilitando a visualização de totais e subtotais.
* **Compartimentação de Dados (Binning):** Um Histograma focado nas Unidades Vendidas, permitindo entender a distribuição e a compartimentação do volume de vendas em blocos.
* **Ranking de Produtos:** Um gráfico de barras adicional comparando as vendas totais por produto.

[!](./Imagens/Detalhes(A).PNG)

### 4. Data Analytics (Report de Performance)
Focada em extrair correlações e os maiores impulsionadores de receita:
* **Correlação Volume x Receita:** Gráfico de dispersão relacionando a Soma de Unidades Vendidas com a Soma de Vendas Mensais, incluindo uma linha de tendência.
* **Top 5 Meses:** Gráfico de colunas empilhadas filtrado para exibir apenas os 5 melhores meses em Vendas e Lucro.
* **Análise de Máximas:** Container dedicado exibindo o valor máximo de unidades vendidas e um gráfico ranqueando os TOP 3 Países em faturamento.

[!](./Imagens/DataAnalytics.PNG)

### 5. Categorias & Cluster
Página dedicada ao agrupamento avançado de dados para inteligência de negócios:
* **Agrupamento Automático (Clusters):** Gráfico de dispersão utilizando a inteligência da ferramenta para identificar e colorir automaticamente padrões de comportamento (Clusters 1, 2 e 3) entre Unidades Vendidas e Lucratividade.
* **Sankey Chart:** Visualização de fluxo demonstrando a distribuição das vendas entre Continentes ao longo dos anos de 2013 e 2014.
* **Agrupamento Manual de Dados:** Gráfico de colunas onde os segmentos originais foram reagrupados estrategicamente em "Destaque" (Government e Small Business) versus "Outro", permitindo uma comparação focada.

[!](./Imagens/CategoriasClusters.PNG)

### 6. TOPN & Outliers (Report de Ranking)
Focada na identificação de exceções e variação temporal:
* **Gráfico de Dispersão Animado:** Visual cruzando Vendas e Unidades Vendidas por Produto, equipado com um **Eixo de Reprodução (Play Axis)**. Isso permite dar "Play" na linha do tempo e assistir à movimentação dos produtos mês a mês, facilitando a identificação visual de outliers temporais.
* **Rankings de TOP 3:** Gráficos configurados com filtros de TOP N para exibir estritamente os 3 melhores Produtos e a performance cruzada de Vendas e TOP 3 Produtos por País.

[!](./Imagens/TOPNOutliers.PNG)

---
**Desenvolvido por Diego Floriano Costa**
*Projeto prático focado em Business Intelligence e visualização de dados.*
