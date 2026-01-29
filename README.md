# Análise de Preços de Maçã e Regressão Linear

Este notebook Jupyter (executado no Google Colab) realiza uma análise exploratória de dados de preços de maçã de várias cidades e aplica regressão linear para modelar a tendência de preços.

## Conteúdo

1.  **Carregamento e Inspeção Inicial dos Dados**: Carrega dados de preços de maçã de um arquivo CSV e realiza verificações básicas de estrutura com NumPy.
2.  **Preparação dos Dados**: Transpõe o conjunto de dados para facilitar a manipulação e extrai dados específicos para datas e preços por cidade.
3.  **Tratamento de Valores Ausentes**: Identifica e preenche valores `NaN` (Not a Number) nos dados de preço usando uma média simples.
4.  **Visualização Básica**: Plota séries temporais de preços para entender tendências iniciais usando Matplotlib.
5.  **Análise de Regressão Linear**: 
    *   Calcula os coeficientes (inclinação 'a' e intercepto 'b') de uma linha de regressão linear para os dados de preço de Moscou usando o método dos mínimos quadrados.
    *   Avalia o ajuste do modelo de regressão linear calculando a norma euclidiana (distância L2) entre os dados reais e a linha de regressão.
    *   Visualiza a linha de regressão e faz previsões/extrapolações.
6.  **Geração e Avaliação de Múltiplos Modelos Lineares**: 
    *   Gera vários modelos lineares com diferentes inclinações aleatórias.
    *   Calcula a norma euclidiana para cada um desses modelos para comparar seu ajuste aos dados.
7.  **Salvamento dos Dados**: Salva os resultados das normas e coeficientes angulares em um arquivo CSV.

## Bibliotecas Utilizadas

*   `numpy`: Para operações numéricas e manipulação de arrays.
*   `matplotlib.pyplot`: Para criação de gráficos e visualizações.

## Como Usar

Para executar este notebook:

1.  Abra-o no Google Colab ou em qualquer ambiente Jupyter.
2.  Execute as células sequencialmente para carregar, processar, analisar e visualizar os dados.

## Resultados Principais

O notebook demonstra como:

*   Carregar e preparar dados de séries temporais usando NumPy.
*   Identificar e tratar valores ausentes.
*   Aplicar regressão linear para modelar tendências de dados.
*   Avaliar a qualidade do ajuste de um modelo linear usando a norma euclidiana.
*   Comparar diferentes modelos lineares gerados aleatoriamente.
