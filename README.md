# Previsão de Satisfação do Cliente na InStyle
Este repositório contém um projeto dedicado à análise da satisfação do cliente da empresa InStyle, uma conceituada loja de roupas sediada nos Estados Unidos. O objetivo central deste projeto é otimizar a experiência do cliente e elevar os níveis de satisfação enquanto a empresa expande suas operações. Para atingir essa meta, desenvolvemos um modelo de aprendizado de máquina que tem a capacidade de prever se um cliente está satisfeito, ou por outro lado, neutro/insatisfeito. Essa previsão proporcionará à empresa insights valiosos, permitindo a tomada proativa de medidas para aprimorar a experiência do cliente.
  <p align="center"><strong><a href="https://www.kaggle.com/competitions/instyle-nps">Mais detalhes </a></strong></p>

## Preparação de Dados e Modelagem
O projeto de previsão da satisfação do cliente envolveu as seguintes etapas:

### Preparação de Dados
* Carregamento dos dados de treinamento a partir do arquivo train.csv.
* Análise exploratória detalhada para compreensão da distribuição e qualidade dos dados.
* Conversão de variáveis categóricas em formatos numéricos.
* Tratamento de valores ausentes considerando seu impacto.
### Identificação de Outliers e Relações
* Detecção e tratamento de outliers usando gráficos boxplot.
* Utilização da biblioteca Sweetviz para visualizar relações entre variáveis e satisfação do cliente.
### Seleção de Características
* Aplicação do algoritmo Boruta com um modelo Random Forest para destacar características relevantes.
* Eliminação de características menos impactantes para simplificar o modelo.
### Modelagem de Dados
* Configuração de modelos de classificação como XGBoost, SVC, Gradient Boosting e LightGBM.
* Utilização da biblioteca PyCaret para simplificar configuração e otimização de hiperparâmetros.
### Avaliação do Modelo
* Avaliação por meio de validação cruzada para calcular métricas de desempenho.
* Uso dos dados de teste para avaliar o modelo em um conjunto independente.
### Geração de Previsões e Submissões
* Utilização do modelo LightGBM para gerar previsões nos dados de teste.
* Criação de arquivo de submissão para avaliação em ambiente de produção.
* O resultado foi um modelo robusto de previsão da satisfação do cliente com base em dados devidamente tratados e avaliados.

## Resultados e Conquistas
Com a finalização das fases de modelagem e avaliação, analisamos os resultados com um nível substancial de detalhe. O modelo que apresentou a pontuação F1-score mais elevada(96,5%) foi selecionado como nosso modelo final. Essa seleção capacita a equipe a tomar decisões informadas sobre a satisfação dos clientes, contribuindo para a adaptação das estratégias operacionais e financeiras. Através da oferta de previsões mais precisas, almejamos reduzir os impactos adversos das situações em questão e aprimorar a eficiência das operações.
