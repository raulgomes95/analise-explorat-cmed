## Análise Exploratória da Tabela CMED

Este repositório contém uma análise exploratória da Tabela CMED (Câmara de Regulação do Mercado de Medicamentos) com o uso de Python e suas bibliotecas, como pandas e matplotlib. O objetivo desta análise é obter insights e informações relevantes sobre os medicamentos listados na tabela, bem como explorar aspectos como preços, tipos de produtos, convênios e outras características.

### Bibliotecas Utilizadas

- pandas: Utilizada para a manipulação e análise de dados tabulares.
- matplotlib: Utilizada para a criação de gráficos e visualizações.

### Processo de Análise

1. **Importação dos Dados:** Os dados foram carregados a partir de um arquivo Excel ('CMED.xls') usando a biblioteca pandas.

2. **Limpeza dos Dados:** Linhas iniciais que continham informações não relevantes foram removidas, preparando o DataFrame para análise.

3. **Análise Estatística Geral:** Foi utilizado o método `.describe()` para obter uma visão estatística geral do DataFrame.

4. **Análise do Convênio Confaz 87:** Foram contados e visualizados percentualmente os produtos que fazem parte ou não do convênio Confaz 87.

5. **Análise das Tarjas:** A distribuição dos produtos com base em suas tarjas foi analisada e visualizada por meio de um gráfico de barras.

6. **Análise do Coeficiente de Adequação de Preços (CAP):** Foi analisada a distribuição dos produtos em relação à obrigatoriedade de aplicação do Coeficiente de Adequação de Preços e visualizado por meio de um gráfico de pizza.

7. **Análise de Produtos Confaz 87 e CAP:** A quantidade de produtos que fazem parte tanto do convênio Confaz 87 quanto da lista CAP foi contada.

8. **Análise da Lista Positiva de Concessão de Crédito Tributário (PIS/COFINS):** Foi verificado o número de produtos que fazem parte da lista positiva de concessão de crédito tributário.

9. **Análise dos Tipos de Produtos:** A distribuição dos produtos de acordo com seu tipo foi analisada e visualizada por meio de um gráfico de barras.

10. **Análise das Classes Terapêuticas:** Foi feita uma análise da distribuição dos produtos de acordo com suas classes terapêuticas.

11. **Análise do Regime de Preço:** A distribuição dos produtos em relação ao regime de preço foi analisada e visualizada por meio de um gráfico de pizza.

### Considerações Finais

Esta análise exploratória fornece uma visão inicial e informativa dos dados contidos na Tabela CMED. Ela pode servir como base para análises mais aprofundadas e insights sobre o mercado farmacêutico e a regulação de preços de medicamentos no Brasil. Sinta-se à vontade para explorar os códigos e gráficos aqui presentes e expandir essa análise de acordo com suas necessidades e objetivos.
