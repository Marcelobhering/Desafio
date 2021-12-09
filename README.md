# Desafio Machine Learning

Parte 2 - Projeto de aprendizagem de máquina para quantificar a variação morfológica das flores de íris de três espécies relacionadas.

 -> Iris dataset analysis - Problema de classificação
  
Informação do conjunto de dados:
O conjunto de dados contem três tipos de flores de íris, são 150 registros com cinco atributos - comprimento da sépala, largura da sépala, comprimento da pétala, largura da pétala e espécies
   
  
Informação do Atributos: 

1. comprimento sépala em cm
2. largura sépala em cm
3. comprimento da pétala em cm
4. largura da pétala em cm
5. espécies: - Iris Setosa - Iris Versicolour - Iris Virginica
  
Temos 3 espécies da flor íris para fazer sua classificação. Baseado nas medidas das flores, será possível classificá-las.
Com o auxílio das classes Pandas e NumPy foi realizada a análise exploratória dos dados. A plotagem do gráfico demostrou os 4 atributos os quais foram analisados em pares. Através do gráfico de dispersão, foram exibidas as medidas em cm das pétalas e sépalas. O gráfico de histogramas que está na diagonal principal, analisou a distribuição de frequências de cada característica. Nos gráficos de barra, relacionou-se individualmente cada espécie com as medidas dos seus atributos. Com o auxílio da matriz de correlação, foi possível analisar os coeficientes de correlação entres as varáveis. A coluna espécie do conjunto de dados foi convertida para valores numéricos para poderem ser selecionadas com entradas e foram definidas as amostras de treino e teste, sendo que o tamanho dos dados selecionados para teste foi de 70%.
O próximo passo consistiu em aplicar os modelos de avaliação com o auxílio das funcionalidade das classes do Scikit-Learn. Os modelos usados foram de Regressão logística, K-vizinhos mais próximos e modelo árvore de decisão. Foi determinada a matriz de confusão de cada modelo e se observou que na diagonal principal os valores de verdadeiro positivo estavam mais acertados. Adotou-se a acurácia para calcular a performance de cada modelo e o que obteve o melhor resultado foi o de Árvore de decisão com 94,29% de predições corretas.

  
  # Algoritmos 

<li> Regressão Logística
<li> k-vizinhos mais próximos 
<li> Árvore de Decisão 

  
 # Bibliotecas 

<li> pandas 1.3.4
<li> matplotlib 3.4.3
<li> seaborn 0.11.2
<li> scikit-learn 1.0.1
<li> numpy 1.21.4
<li> matplotlib 3.5
 
 
 
 # Bibliografias 
 
<li>  https://www.freecodecamp.org/news/end-to-end-machine-learning-project-turorial/
<li>  https://pt.wikipedia.org/wiki/Conjunto_de_dados_flor_Iris
<li>  https://awari.com.br/algoritmos-de-classificacao-uma-introducao/
<li>  https://dadosaocubo.com/classificacao-com-scikit-learn/
<li>  http://www.sakurai.dev.br/classificacao-iris/
<li>  https://blog.geekhunter.com.br/aprendizado-de-maquina-e-seus-algoritmos/
<li>  https://medium.com/@pedrofullstack/introdu%C3%A7%C3%A3o-ao-jupyter-notebook-para-python-b2cf79cea31d
<li>  https://kenzie.com.br/blog/google-colab/
<li>  https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
<li>  https://seaborn.pydata.org/examples/scatterplot_matrix.html
<li>  https://pt.stackoverflow.com/
