# 🛍️ AluraStoreBR: Análise de indicadores de uma rede fictícia de quatro Lojas

Este projeto analisa os dados de vendas de quatro lojas da AluraStore, utilizando Python para explorar aspectos como **faturamento**, **avaliações** e **distribuição geográfica** das vendas. A partir dos dados fornecidos, são gerados gráficos estáticos e mapas interativos que revelam insights valiosos sobre o desempenho das lojas. Este projeto responde ao primeiro desafio da turma de DataScience do programa [Oracle Next Education (ONE) G8](https://www.oracle.com/br/education/oracle-next-education/), oferecido através de uma parceria da [Oracle](https://www.oracle.com/br/) com a [Alura](https://www.alura.com.br). 

---

## 📌 Objetivos

- Calcular e comparar o faturamento bruto de cada loja
- Analisar a média de frete e avaliação das compras
- Determinar os produtos e categorias de produtos mais e menos vendidos
- Visualizar a **distribuição geográfica** das vendas por coordenadas
- Identificar regiões com maior volume de vendas
- Explorar padrões de concentração por meio de **gráficos de dispersão** e **heatmaps**

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

## ✅ Conclusões
A partir das análises realizadas, os seguintes insights foram destacados:

- **Loja 1** foi responsável pelo **maior faturamento bruto**, seguida pela Loja 2, enquanto a Loja 4 apresentou o menor desempenho.
- A distribuição geográfica revelou uma forte concentração de vendas na **região sudeste**, sobretudo em SP.
- O valor do frete médio apresentou **pouca variação entre as lojas**, o que faz sentido tendo em vista que a maior parte das vendas se concentrou nas mesmas regiões. Ainda assim, o maior frete médio é o da loja 1 e o menor o da loja 4.
- A avaliação média das lojas foi **regular** (**4.02** de um máximo de 5). A loja com **menor desempenho nas avaliações foi a loja 1** e a com **melhor foi a loja 3**.
- As duas categorias de produtos com maior vendagem na rede foram **móveis e eletrônicos**, totalizando juntas **38,8%** das vendas. Além disso, estas duas categorias foram responsáveis também pela por cerca de 38% das vendas de cada loja individualmente. 
- Já as duas categorias com **menor vendagem** na rede foram **utilidades domésticas e livros**. Juntas, totalizam **apenas 15,6%**. Novamente, algo muito similar acontece também individualmente em cada loja.
- Essas descobertas podem orientar ações estratégicas como expansão de cobertura, promoções regionais e ajustes logísticos, além de um esforço para melhor a experiência do cliente.
- De forma geral, as quatro lojas apresentam desempenho geral muito parecidos. Entretanto, tendo em vista seu menor faturamento bruto e segunda pior avaliação média dos clientes, acreditamos que - caso seja esta a decisão da diretoria - a **loja que deveria ser encerrada é a loja 4**. Vale apontar que apesar desta loja possuir o menor valor médio de frete, isto tem pouco impacto no faturamento líquido da loja.

## ✍️ Autor
- [Bruno Ricardo Machado](https://www.instagram.com/brunorm86/)
- [Github](https://github.com/brunorm86)
- [Linkedin](https://www.linkedin.com/in/bruno-ricardo-machado/)
- [E-Mail](mailto:brunorm869@gmail.com)

## Repositório do projeto
- [Link do repositório](https://github.com/brunorm86/challenge1-data-science.git)