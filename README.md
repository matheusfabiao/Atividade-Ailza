# Análise de Regressão - README

Este repositório contém um script Python que realiza uma análise de regressão utilizando dados de emissão de CO2 e tamanho do motor. O objetivo é explorar a relação entre essas variáveis e criar visualizações informativas para melhor compreensão do modelo.

## Pré-requisitos
Certifique-se de ter o módulo wget instalado. Caso contrário, instale-o executando o seguinte comando:
```
pip3 install wget
```

## Obtendo os Dados
O script utiliza o módulo wget para baixar um arquivo CSV contendo os dados necessários. Execute o seguinte comando para baixar o arquivo:
```
wget https://raw.githubusercontent.com/matheusfabiao/Atividade-Ailza/main/FuelConsumptionCo2.csv
```
## Bibliotecas Utilizadas
* pandas
* numpy
* matplotlib
* seaborn
* statsmodels
* plotly
* plotly.graph_objects

Certifique-se de ter essas bibliotecas instaladas antes de executar o script.

## Executando o Script
Execute o script em um ambiente Python compatível. Recomenda-se o uso de ambientes virtuais para evitar conflitos de dependências.
```
python nome_do_script.py
```
## Visão Geral do Script
* Carrega os dados do arquivo CSV em um DataFrame usando a biblioteca pandas.
* Realiza uma análise exploratória inicial, exibindo as primeiras linhas do DataFrame e estatísticas descritivas.
* Estima um modelo de regressão linear utilizando o método dos mínimos quadrados ordinários (OLS) da biblioteca statsmodels.
* Adiciona os valores ajustados (fitted values) ao DataFrame e gera um gráfico de dispersão usando a biblioteca Plotly.
* Apresenta o coeficiente de ajuste (R²) como medida de correlação ao quadrado.
* Explora um modelo auxiliar para fins didáticos, demonstrando um ajuste perfeito (R² igual a 100%).
* Gera visualizações adicionais para ilustrar o conceito de R².

## Resultados e Conclusões
O script fornece visualizações e estatísticas que auxiliam na compreensão da relação entre emissão de CO2 e tamanho do motor, destacando a utilidade da análise de regressão na modelagem dessas relações.

Para obter mais detalhes sobre o modelo estimado e seus parâmetros, consulte a seção de resultados ao executar o script.

Este é um projeto didático e pode ser adaptado para análises específicas ou expandido para incluir mais funcionalidades conforme necessário.
