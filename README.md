# 🛍️ AluraStoreBR: Análise de indicadores de uma rede fictícia de quatro Lojas
### 📅 Abril de 2025 | 💻 Projeto de Data Science – ONE G8

Este projeto analisa os dados de vendas de quatro lojas da AluraStore, utilizando Python para explorar aspectos como **faturamento**, **avaliações** e **distribuição geográfica** das vendas. A partir dos dados fornecidos, são gerados gráficos estáticos e mapas interativos que revelam insights valiosos sobre o desempenho das lojas. Este projeto responde ao primeiro desafio da turma de DataScience do programa [Oracle Next Education (ONE) G8](https://www.oracle.com/br/education/oracle-next-education/), oferecido através de uma parceria da [Oracle](https://www.oracle.com/br/) com a [Alura](https://www.alura.com.br). 

---

## 📌 Objetivos

- Calcular e comparar o faturamento bruto de cada loja
- Analisar a média de frete e avaliação das compras
- Determinar os produtos e categorias de produtos mais e menos vendidos
- Visualizar a **distribuição geográfica** das vendas por coordenadas
- Identificar regiões com maior volume de vendas
- Explorar padrões de concentração por meio de **gráficos de dispersão** e **heatmaps**
- Indicar, com base nas análises feitas, qual das quatro lojas deveria ter suas atividades encerradas
---

## 🗂️ Estrutura dos Dados

Cada loja possui um dataset próprio com colunas como:

- Produto e Categoria: Itens vendidos e suas classificações.

- Preço e Frete: Valores das vendas e custos associados.

- Data de Compra e Local: Informações temporais e geográficas.

- Avaliação da Compra: Feedback dos clientes.

- Tipo de Pagamento e Parcelas: Métodos utilizados pelos clientes.

- Coordenadas Geográficas: Localização das transações.

---

## 📊 Visualizações

O notebook inclui:

### 📈 Gráficos de Barras e Pizza
- Faturamento bruto por loja
- Distribuição percentual de faturamento, de vendas por produtos e participação percentual das categorias de produtos no total de vendas de cada loja e da franquia.

### 🌍 Gráficos Geográficos
- **Dispersão de coordenadas** com tamanho proporcional à quantidade de vendas
- **Heatmap interativo com Folium**, exibindo pontos de maior concentração

---

## 🔧 Tecnologias Utilizadas

- `pandas` – Manipulação de dados
- `matplotlib` – Geração de gráficos estáticos
- `folium` + `HeatMap` – Criação de mapas interativos
- `collections.Counter` – Contagem de coordenadas repetidas

---

## ▶️ Como Executar

1. Clone o repositório ou baixe o notebook `AluraStoreBr.ipynb`
2. Certifique-se de ter Python 3 e Jupyter Notebook instalados
3. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas matplotlib folium

## ✍️ Autor
- [Bruno Ricardo Machado](https://www.instagram.com/brunorm86/)
- [Github](https://github.com/brunorm86)
- [Linkedin](https://www.linkedin.com/in/bruno-ricardo-machado/)
- [E-Mail](mailto:brunorm869@gmail.com)

## Repositório do projeto
- [Link do repositório](https://github.com/brunorm86/challenge1-data-science.git)