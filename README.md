# 🏬 Análise de Dados E-commerce Olist (Python + SQL)

> **Análise completa de dados de uma das maiores plataformas de e-commerce do Brasil — Olist.**  
> SQL foi utilizado para manipulação e exploração dos dados, enquanto Python cuidou da visualização e geração de insights.  
> Base de dados pública disponível no [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data).

---

## Visão Geral

Este projeto analisa mais de **100 mil pedidos reais** da **Olist**, um marketplace brasileiro que conecta pequenos lojistas a grandes varejistas online.  
O objetivo é **extrair insights estratégicos** sobre comportamento do consumidor, desempenho logístico e valor do cliente.

Combinando **consultas SQL avançadas** e **visualizações em Python**, o projeto mostra como decisões baseadas em dados podem otimizar processos, melhorar a experiência do cliente e identificar oportunidades de crescimento.

---

## Objetivos

- 🧾 Entender o comportamento de vendas e as categorias mais lucrativas  
- 🚚 Analisar tempos de entrega e eficiência logística por região  
- ⭐ Avaliar a satisfação dos clientes por meio das avaliações  
- 💰 Calcular o **Valor do Tempo de Vida do Cliente (LTV)** no Brasil  
- 📈 Identificar tendências de vendas e sazonalidade  
- 🧮 Demonstrar raciocínio analítico ponta a ponta com SQL + Python  

---

## Ferramentas e Tecnologias

| Tecnologia | Finalidade |
|-------------|-------------|
| 🐍 **Python** | Análise e visualização de dados |
| 🗄️ **SQLite + SQL** | Consultas e manipulação de dados |
| 📘 **Jupyter Notebook** | Documentação e storytelling analítico |
| 📊 **Pandas / Matplotlib / Seaborn** | Limpeza e visualização de dados |
| 🗺️ **Folium** | Mapas geográficos interativos |
| 📈 **NumPy / Squarify** | Estatísticas e gráficos avançados |

---

## 📂 Estrutura do Repositório

📂 olist-ecommerce-sql-analysis/

├── 📜 README.md ← Versão em português (PT-BR)
├── 📜 README_EN.md ← Versão em inglês
├── 📔 olist_analysis.ipynb ← Notebook completo (Jupyter)
├── 🐍 sql_olist_e_commerce_data_analysis.py ← Código em Python

├── 📊 data/ ← Base de dados original do Kaggle
│ ├── olist_customers_dataset.csv
│ ├── olist_orders_dataset.csv
│ ├── olist_products_dataset.csv
│ └── ... (outros arquivos CSV)

├── 📈 images/ ← Gráficos e visualizações geradas
│ ├── all_images.png
│ ├── image1.png
│ ├── image2.png
│ └── ... (outras imagens)

---

## Principais Insights

### 💸 **Análise de Vendas**
- Categorias líderes: **Beleza e Saúde** e **Eletrônicos**  
- Valor médio do pedido ≈ **R$160**, com grande variação  
- Vendas concentradas em **São Paulo** e **Rio de Janeiro**  

### 🚚 **Logística e Entregas**
- Tempo médio de entrega: **5 a 12 dias**, variando por cidade  
- Picos de atraso em **dezembro (Natal)** e **fevereiro (Carnaval)**  
- Região Sudeste apresenta o melhor desempenho logístico  

### ⭐ **Avaliações de Clientes**
- Maioria das avaliações são **positivas (4–5 estrelas)**  
- Reclamações negativas estão ligadas a **atrasos na entrega**, não à qualidade do produto  

### 💰 **Valor do Tempo de Vida do Cliente (LTV)**
- Maior concentração de clientes de alto valor no **Sudeste e Sul do Brasil**  
- Mapa interativo destaca áreas de maior rentabilidade, especialmente **SP e RJ**  
- Tempo médio de vida do cliente (**TMVC**) entre **8 e 12 semanas**  

### 🛍️ **Vendedores**
- **85%** dos vendedores são pequenos (menos de 100 pedidos)  
- Apenas **2%** possuem mais de 1000 pedidos  
- Grandes vendedores tendem a ter **entregas mais lentas**  

---

## Meu Foco Analítico

Este projeto mostra como **SQL e Python se complementam** na análise de dados:  
- SQL é responsável pela **extração e transformação**;  
- Python, pela **visualização e interpretação** dos resultados.

Foram utilizadas consultas complexas com **CTEs, funções de janela e subqueries**, realizando análises avançadas diretamente no banco.  
Em seguida, o Python foi usado para **validar e comunicar visualmente** os insights, transformando dados brutos em valor de negócio.

---

## 💼 Conclusão

Durante a exploração do dataset da Olist, foi possível identificar:

- Crescimento das vendas impulsionado por sazonalidade e concentração regional  
- Forte impacto da logística na satisfação dos clientes  
- Concentração do LTV nas regiões mais urbanizadas  
- Predominância de pequenos vendedores na plataforma  

---

## 🔗 Referência

📊 [Olist E-commerce Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

---

## 👤 Autor

**Matheus Lourenço**   
📧 matheus.mot12@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/matlourenco) • [GitHub](https://github.com/matheusl2016)

---
