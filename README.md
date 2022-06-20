# PREVIS-O-DE-VENDAS

**Projeto Previsão de Vendas**

O projeto foi desenvolvido utilizando linguagem **Python** no Jupyter Notebook. O python possui um série de bibliotecas que nos auxiliam na construção das análises e modelagem dos dados. Neste projeto, foram utilizadas as seguintes:

   - Pandas
   - Numpy
   - Seaborn
   - Matplotlib
   - Plotly
   - Scikit-learn

**Objetivo**

O objetivo deste projeto é **criar um modelo de previsão de vendas** a partir do histórico de investimentos em marketing em diferentes canais: **TV, Jornal e Rádio**.

**Dados**

A base de dados possui informações sobre:

   - **TV**: Valores investidos no meio de comunicação TV (em milhares de reais)
   - **Radio**: Valores investidos no meio de comunicação Rádio (em milhares de reais)
   - **Jornal**: Valores investidos no meio de comunicação Jornal (em milhares de reais)
   - **Vendas**: Valores realizados em vendas (em milhões de reais)


**Conclusões**


Após o pré-processamento dos dados, foram criados 2 modelos de machine learning com a biblioteca Scikit Learn: Regressão Linear e Árvore de decisão. Esses modelos foram treinados e avaliados utilizando métricas de avaliação matemáticas e gráficas, para a escolha do melhor modelo, Foi então escolhida a **Árvore de decisão** por ter melhores métricas.

Por fim, percebemos que o investimento em **TV** era o que possuía maior correlação com as vendas.
Podemos perceber que em termos de importância para o modelo via Árvore de Decisão:
- **O investimento em TV é ~85% relevante;**
- **O Rádio que também avaliamos anteriormente, pouco mais de 10%;**
- **Jornal não chegando a mais de 5% de relevância**
