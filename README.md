# Projeto de Data Analytics com Power BI

## Sobre o Projeto
Este é um projeto de portfólio focado na criação de um relatório financeiro interativo. O desenvolvimento foi guiado pelos pontos a serem considerados no desafio, com atenção especial à disposição dos visuais e em como o cliente irá consumir o conteúdo.

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

O projeto foi dividido em três páginas principais para garantir uma navegação fluida e uma análise detalhada:

### 1. Home
Uma tela de entrada amigável com o título "Report Financeiro". Ela conta com um botão interativo de "Explorar análise", que direciona o usuário diretamente para as visões gerenciais, oferecendo uma experiência de navegação profissional.

**![Página Home](./imagens/Home.PNG)**

### 2. Principal (Sales Report)
Esta página atua como o painel gerencial de alto nível, trazendo um panorama geral das vendas:
* **Cartões de Indicadores (KPIs):** Apresentam o resumo financeiro com o Total de Vendas (118,73 Mi), Unidades Vendidas (1,13 Mi), Soma de Descontos e Soma de COGS.
* **Análise Temporal:** Um gráfico de área mostrando a evolução da "Soma de Sales por Mês" ao longo do ano.
* **Análise de Segmentos:** Um gráfico de rosca que divide as vendas por segmento de mercado (Government, Small Business, Enterprise, etc.).
* **Performance de Produtos:** Um gráfico de barras horizontais destacando a performance individual, evidenciando os TOP produtos (Paseo, VTT, Velo).
* **Visão Geográfica:** Um visual de Treemap identificando as representações dos países nas vendas (United States, France, Germany, Canada, Mexico).

**![Página Principal](./imagens/Principal.PNG)**

### 3. Detalhes (Report de Lucro Detalhado)
Página voltada para o aprofundamento analítico e segmentação avançada:
* **Análise Mensal e Semestral:** Um gráfico de colunas agrupadas destacando o Total de Vendas por Mês, complementado por filtros interativos para Semestre e Meses.
* **Detalhamento em Matriz:** Uma tabela estruturada que quebra os resultados por Trimestre (Qtr 1 a Qtr 4) e por ano (2013 e 2014), facilitando a visualização de totais e subtotais.
* **Compartimentação de Dados:** Um Histograma focado nas Unidades Vendidas, permitindo entender a distribuição e a compartimentação do volume de vendas.
* **Ranking de Produtos:** Um gráfico de barras adicional comparando as vendas totais por produto.

**![Página Detalhes](./imagens/Detalhes.PNG)**
