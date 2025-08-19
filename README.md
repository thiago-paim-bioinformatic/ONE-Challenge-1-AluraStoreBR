# 📊 Análise Comparativa de Desempenho de Lojas

Este projeto tem como objetivo realizar uma análise exploratória e comparativa entre quatro lojas distintas, com base em dados de vendas, avaliações de clientes, frete médio e desempenho por categoria de produto. A finalidade é apoiar decisões estratégicas, como a venda ou manutenção de unidades comerciais.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** – para manipulação e análise de dados tabulares.
- **Matplotlib** – para geração de gráficos e visualizações.

---

## 📁 Estrutura dos Dados

Os dados foram organizados em diferentes DataFrames, representando:

- Faturamento total por loja
- Vendas por categoria de produto
- Média e mediana das avaliações dos clientes
- Produtos mais e menos vendidos
- Frete médio por loja

Cada loja foi identificada por um nome único (`loja_1`, `loja_2`, etc.), e os dados foram tratados separadamente antes da comparação.

---

## 🔍 Metodologia

### 1. **Importação e Limpeza de Dados**

Os dados foram carregados em DataFrames utilizando `pandas.read_csv()` e agrupados em estruturas de dicionário. Foram aplicadas técnicas de limpeza como:

- Normalização de nomes de colunas
- Conversão de tipos (ex: valores tipo string para `datetime`, por exemplo)
- Remoção de valores nulos ou inconsistentes

### 2. **Análise Descritiva**

Foram calculadas estatísticas básicas como:

- Soma total de faturamento por loja
- Contagem de vendas por categoria
- Média e mediana das avaliações
- Custo médio de frete

Essas métricas permitiram uma visão geral do desempenho de cada loja.

### 3. **Visualizações**

Utilizando `matplotlib.pyplot`, foram gerados gráficos como:

- Barras comparativas de vendas por categoria
- Gráficos de linha para evolução de faturamento mensal entre as lojas
- Histogramas de avaliações entre as lojas

As visualizações foram fundamentais para destacar padrões e discrepâncias entre as lojas.

### 4. **Comparações Cruzadas**

Com os dados estruturados, foram feitas comparações diretas entre lojas, destacando:

- Pontos fortes e fracos de cada unidade
- Produtos com maior e menor saída
- Impacto do frete médio no desempenho geral

---

## 📌 Conclusão

Este projeto demonstra como o uso de bibliotecas como `pandas` e `matplotlib` pode facilitar a análise de dados comerciais e apoiar decisões estratégicas. A metodologia aplicada pode ser replicada para outros contextos empresariais, como avaliação de filiais, análise de portfólio de produtos ou otimização logística.

---

## 📎 Requisitos

Para executar este projeto, certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install pandas matplotlib
