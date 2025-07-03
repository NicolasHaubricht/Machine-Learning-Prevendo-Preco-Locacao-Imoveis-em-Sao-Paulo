
# Machine Learning para Previsão de Preços de Locação em São Paulo

O projeto tem como objetivo de desenvolver modelos de machine learning para prever preços de locação de imóveis em São Paulo com base em dados reais do mercado. Foram aplicados e comparados algoritmos como Linear Regression, Decision Tree e Random Forest.


## Comparação dos Modelos

![image](https://github.com/user-attachments/assets/d70723be-f3e6-41cb-9094-e6b8ebedb04c)


Esse projeto pode ser útil para os seguintes públicos:

- Corretoras de imóveis: para estimar valores de locação de forma rápida e embasada, facilitando a definição de preços e a negociação com clientes.

- Locatários: para avaliar se o valor de aluguel de um imóvel está dentro do padrão esperado para a região e características do imóvel.

- Proprietários: para ter uma referência de preço de locação ao anunciar um imóvel, garantindo maior competitividade no mercado.

- Plataformas de anúncios imobiliários: como base para integração em sistemas que automatizam a sugestão de preços.

- Pesquisadores e analistas de mercado imobiliário: como ferramenta para estudos sobre preços de locação e tendências do setor.



## Tecnologias Utilizadas

**Desenvolvido em:** Python e Bibliotecas Externas

**Bibliotecas e módulos importados**: 
- gdown 
- pandas 
- numpy 
- plotly.express 
- plotly.graph_objects 
- matplotlib.pyplot
- seaborn

**Machine Learning**:
- sklearn.cluster.KMeans 
- sklearn.linear_model.LinearRegression
- sklearn.tree.DecisionTreeRegressor
- sklearn.ensemble.RandomForestRegressor
- sklearn.model_selection.cross_val_score
- sklearn.model_selection.GridSearchCV
- sklearn.model_selection.train_test_split 
- sklearn.metrics.mean_squared_error
- sklearn.metrics.r2_score
## Melhorias

O próximo passo do projeto é criar uma plataforma web onde qualquer pessoa possa usar o modelo de machine learning de forma simples. A ideia é que o usuário preencha os dados do imóvel, como área, número de quartos, banheiros, vagas, localização entre outras informações complementares. Com esses dados o sistema devolverá a previsão do preço de locação. Isso vai transformar o modelo de machine learning em uma ferramenta prática, que pode ajudar tanto proprietários quanto interessados em alugar um imóvel, deixando o projeto mais útil e aplicável no mundo real.


## Autor

- Feito por [Nicolas Haubricht](https://github.com/NicolasHaubricht)

- Projeto desenvolvido após conclusão do curso Fundamentos de AI e Machine Learning [Asimov](https://asimov.academy/)

