# Projeto de Análise de Dados - Previsão de Doenças Cardíacas

Este projeto de análise de dados tem como objetivo explorar o conjunto de dados sobre doenças cardíacas de 1988, que contém informações de quatro regiões: Cleveland, Hungria, Suíça e Long Beach V. O conjunto de dados possui 76 atributos, com o atributo alvo indicando a presença de doença cardíaca, representado como 0 para ausência e 1 para presença.

## Descrição dos Atributos

O conjunto de dados contém as seguintes características:

1. **Idade (age)**
2. **Sexo (sex)**
3. **Tipo de Dor no Peito (chest pain type)** - Com 4 valores distintos
4. **Pressão Arterial em Repouso (resting blood pressure)**
5. **Colesterol Sérico em mg/dl (serum cholestoral)**
6. **Açúcar no Sangue em Jejum > 120 mg/dl (fasting blood sugar)**
7. **Resultados Eletrocardiográficos em Repouso (resting electrocardiographic results)** - Com valores 0, 1, e 2
8. **Frequência Cardíaca Máxima Atigida (maximum heart rate achieved)**
9. **Angina Induzida por Exercício (exercise induced angina)**
10. **Depressão do Segmento ST Induzida por Exercício em Relação ao Repouso (oldpeak)**
11. **Inclinação do Segmento ST no Pico do Exercício (the slope of the peak exercise ST segment)**
12. **Número de Grandes Vasos Coloridos por Fluoroscopia (number of major vessels)**
13. **Thal: 0 = Normal, 1 = Defeito Fixo, 2 = Defeito Reversível (thal)**

Os nomes e informações pessoais dos pacientes foram removidos e substituídos por valores fictícios, preservando a privacidade.

## Análise de Dados

### Mapa de Calor Principal

Abaixo está o mapa de calor que representa a correlação entre as variáveis. Esse mapa ajuda a identificar quais atributos têm maior impacto na presença de doença cardíaca.

![Mapa de Calor Principal](img/1_heatmap_hd_corr.png)


### Variáveis Categóricas

Aqui estão os gráficos ou tabelas que representam as variáveis categóricas. Eles fornecem informações sobre a distribuição de dados nessas categorias.

<table>
  <tr>
    <td><img src="img/3_coluna_avaliada_sex.png" alt="Imagem 1" width="300"></td>
    <td><img src="img/4_coluna_avaliada_cp.png" alt="Imagem 2" width="300"></td>
    <td><img src="img/7_coluna_avaliada_fbs.png" alt="Imagem 2" width="300"></td>
  </tr>
  <tr>
    <td><img src="img/8_coluna_avaliada_restecg.png" alt="Imagem 1" width="300"></td>
    <td><img src="img/10_coluna_avaliada_exang.png" alt="Imagem 2" width="300"></td>
    <td><img src="img/12_coluna_avaliada_slope.png" alt="Imagem 2" width="300"></td>
  </tr>
  <tr>
    <td><img src="img/13_coluna_avaliada_ca.png" alt="Imagem 1" width="300"></td>
    <td><img src="img/14_coluna_avaliada_thal.png" alt="Imagem 1" width="300"></td>
  </tr>
</table>

### Variáveis numéricas

As representações gráficas ou tabelas das variáveis numéricas estão a seguir:

<table>
  <tr>
    <td><img src="img/2_coluna_avaliada_age.png" alt="Imagem 1" width="300"></td>
    <td><img src="img/5_coluna_avaliada_trestbps.png" alt="Imagem 2" width="300"></td>
    <td><img src="img/6_coluna_avaliada_chol.png" alt="Imagem 2" width="300"></td>
  </tr>
  <tr>
    <td><img src="img/9_coluna_avaliada_thalach.png" alt="Imagem 1" width="300"></td>
    <td><img src="img/11_coluna_avaliada_oldpeak.png" alt="Imagem 2" width="300"></td>
  </tr>
</table>

## Diferença de Outliers mostradas em Plots

<table>
  <tr>
    <td><img src="img/16_boxplot_01.png" alt="Imagem 2" width="900"></td>
  </tr>
  <tr>
    <td><img src="img/18_boxplot_04.png" alt="Imagem 2" width="900"></td>
  </tr>
</table>

## Resultados Finais das Métricas

Aqui estão os resultados finais das métricas do modelo de previsão de doenças cardíacas:

### Logistic Regression
![Gráfico de Variável Categórica 1](img/19_heatmap_confusion_matrix.png)

### Ada Boost Classifier
![Gráfico de Variável Categórica 1](img/21_ada_boost_classifier_heatmap.png)

### Decision Tree Classifier
![Gráfico de Variável Categórica 1](img/20_decision_tree_classifier_heatmap.png)

### KNeighbors Classifier
![Gráfico de Variável Categórica 1](img/22_knn_heatmap.png)

### Random Forest Classifier
![Gráfico de Variável Categórica 1](img/24_random_forest_classifier_heatmap.png)

## Resultados Finais das Métricas - Com Escalonamento

Os resultados finais das métricas após aplicar escalonamento estão disponíveis a seguir:

### Logistic Regression - Scaler
![Gráfico de Variável Categórica 1](img/25_logistic_regression_scaler_heatmap.png)

### Ada Boost Classifier - Scaler
![Gráfico de Variável Categórica 1](img/27_ada_boost_classifier_scaler_heatmap.png)

### Decision Tree Classifier - Scaler
![Gráfico de Variável Categórica 1](img/26_decision_tree_classifier_scaler_heatmap.png)

### KNeighbors Classifier - Scaler
![Gráfico de Variável Categórica 1](img/28_knn_scaler_heatmap.png)

### Random Forest Classifier - Scaler
![Gráfico de Variável Categórica 1](img/29_random_forest_scaler_heatmap.png)

## Conclusão

Este projeto de análise de dados fornece insights valiosos sobre a previsão de doenças cardíacas com base em um conjunto de dados detalhado. Os resultados e visualizações apresentados aqui podem ser úteis para profissionais da área de ciência de dados que desejam criar modelos de previsão de doenças cardíacas. O conjunto de dados e as análises aqui apresentadas são uma adição valiosa ao seu portfólio de ciência de dados.

### Random Forest Classifier - Scaler
![Gráfico de conclusão](img/30_conclusao.png)

