# Regressão Logística: uma aplicação na detecção de pacientes de alto risco da Covid-19

Link do artigo associado do Medium: https://medium.com/@samir.silva12342/implementa%C3%A7%C3%A3o-do-zero-regress%C3%A3o-log%C3%ADstica-3e0f4dff9c32
 
Há dois notebooks neste repositório:

- 01_logreg_feature_engineering_and_application_sklearn.ipynb: nele, realizei a aplicação passo-a-passo das boas práticas de feature engineering no dataset 'Covid Data', disponível no Kaggle e apliquei um modelo de regressão logística aos dados para prever pacientes de alto risco de óbito devido à Covid-19, utilizando a biblioteca 'scikit-learn', do Python.

- 02_logreg_implementation.ipynb: neste notebook, realizei, passo-a-passo, a formulação matemática e a implementação em Python de um modelo de regressão logística utilizando regularização L1.

A regressão logística é um dos modelos de Machine Learning mais conhecidos e é aplicada quando queremos prever classificações através de probabilidades. Seu princípio envolve a utilização da função de ativação sigmoide na soma ponderada dos valores das features para obtenção de probabilidades que indicarão, ao serem comparadas com um threshold (limiar), qual a classificação final do target naquela situação.

Neste repositório, encontram-se os notebooks "01_logreg_feature_engineering_and_application_sklearn.ipynb" e "02_logreg_implementation.ipynb" que desenvolvem passo-a-passo o modelo de regressão logística seguindo uma lógica para aprendizado de sua aplicação e implementação, seguindo as boas práticas utilizadas no aprendizado de máquina.

## Tecnologias e Bibliotecas Utilizadas

- Jupyter Notebook
- Python
- Pandas
- Sklearn
- Numpy
- Matplotlib
