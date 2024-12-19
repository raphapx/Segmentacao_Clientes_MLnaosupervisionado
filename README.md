# Segmentação de cliente utilizando tecnicas de machine learning

Este projeto tem como objetivo separar os clientes em 3 perfis usando modelos de machine learning não-supervisionados

## Estrutura do Projeto

Analise exploratória: notebook-eda.ipynb
Predição: notebook-prediction.ipynb
Clusterização: notebook-segmentation.ipynb

## Pré-requisitos

Certifique-se de ter o Python 3.11.9 instalado. Você pode especificar a versão do Python usando o arquivo `.python-version`.

### Importação das Bibliotecas
As bibliotecas necessárias incluem:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`

### Carregamento dos Dados
Os dados são carregados do arquivo `customer-segmentation-analysis.csv` e armazenados em um DataFrame do pandas.

### Estudo dos Atributos
Análise dos atributos do dataset para entender suas características e identificar potenciais preditores.

### Visualização dos Dados
Gráficos de barras e mapas de calor são utilizados para visualizar a distribuição dos dados e correlações entre variáveis.

### Engenharia de Atributos
Transformações como One-Hot Encoding são realizadas para preparar os dados para a modelagem.

### Experimentação Inicial de Modelos
Não-supervisionado:
 - Redimensionamento com PCA
 - K-means
 - Clusterização Hierarquica (HCA)
   
Supervisionado:
- Regressão Logística
- K-Nearest Neighbors
- Random Forest
- Gradient Boosting

## Resultados
Foi dividos os clientes em 3 perfis distintos para campanha direcionada.
