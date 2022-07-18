## ANÁLISE DE SENTIMENTOS - Reviews do Parque da Disney
Este projeto tem como foco fazer a análise de sentimento das reviews das diferentes filiais dos parques das Disney, classificando se uma review é positiva, negativa ou neutra.

## Técnicas e modelos utilizados
### VADER - MODELO PRÉ TREINADO
VADER é um modelo provido da biblioteca NLTK. Por meio dele é possível realizar análise de sentimento dos textos, conseguindo através de scores, dizer se uma parte do discurso tem teor positivo ou negativo. Utilizei este modelo pré treinado para fazer comparações com os modelos que treinei ao longo do notebook.

### COUNTVECTORIZER
Provido do scikit-learn, CountVectorizer é uma técnica de pré processamento antes dos modelos serem treinados. Essa técnica consiste em converter os textos em uma contagem de termos.

### NAIVE BAYES
O modeloo de Naive Bayes é um classificador probabilístico que é baseado na aplicação do teorema de Bayes, pressupondo do princípio que todas as variáveis são independentes entre si. Para esse modelo, utilizei a biblioteca scikit-learn.
### SUPORT VECTOR MACHINES (SVM)
O modelo de Suport Vector Machines tem como objetivo achar um hiperplano que consiga dividir melhor os dados. Para a implementação desse modelo, também utilizei a biblioteca scikit-learn.

## Bibliotecas utilizadas
* [NLTK](https://www.nltk.org/)
* [SEABORN](https://seaborn.pydata.org/)
* [SCIKIT-LEARN](https://scikit-learn.org/stable/)
* [MATPLOTLIB](https://matplotlib.org/)



