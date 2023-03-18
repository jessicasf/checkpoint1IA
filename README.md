# checkpoint1IA
# Template para desenvolvimento e entrega do Checkpoint 1

Esse é um guia simples do README e deve ser customizado pelo estudante

**Nome: (Jessica Souza Felix)** 

**Turma: (2TDSPI)**

**Ano: 2023**

## Objetivo

Avaliar conceitos sobre Modelagem de dados e aprendizado de máquina (ML)

## Descrição do desafio
O desafio foi dado com dados de diversos tipos de carro, para realizar levantamento de tabelas, graficos com tuso que foi dado em sala de aula, como desafio verificar o melhor preco de carro para o usuario.Qual o preço de venda de um veículo Volkswagen Sedan 2.0 a gasolina, ano 2005, com cerca de 172095 km rodados? Esse e o desafio.

## Desenvolvimento do projeto
   - Como foi desenvolvido o projeto?
   foi desenvolvido atravez do colab com update do checkpoint, e o arquivo dos dados do carro, com isso usamos o dataset
   e fizemos importacoes como panda por exemplo.

## Como executar o projeto
   - Quais são os passos a serem realizados para executar o projeto?
   primero passo ter cadastro no colaab
   segundo passo fazer update do checkpoint
   terceiro passo baixar o arquivo carros e arrastar para colab
  import pandas as pd
  from sklearn.datasets import fetch_openml
  import matplotlib.pyplot as plt
   import seaborn as sns
   dados=dados.drop("Mileage/1000", axis=1)
   dados.head()
   correlacao = dados.corr()
   sns.heatmap(correlacao, annot=True )
   plt.show()
   dados = dados.dropna(axis=0)
   from sklearn.model_selection import train_test_split
   len(dados)
   from sklearn.tree import DecisionTreeRegressor
   from sklearn.metrics import r2_score, mean_absolute_error
   from sklearn.linear_model import LinearRegression
   from sklearn.metrics import r2_score, mean_absolute_error
   from sklearn.linear_model import LinearRegression
   from sklearn.metrics import r2_score, mean_absolute_error
   print("Erro Médio Absoluto (MAE): %.2f" % mean_absolute_error(w_test, w_predicoes))
   r2_score(w_test,w_predicoes)
   print("R2-score: %.2f" % r2_score(w_test,w_predicoes))   



   
## Pré-requisitos
   - Quais são as dependências do projeto?  
   Quais são os passos a serem realizados para executar o projeto?
   primero passo ter cadastro no colaab
   segundo passo fazer update do checkpoint
   terceiro passo baixar o arquivo carros e arrastar para colab
   quarto passo importar import pandas as pd #Pandas = Biblioteca para trabalhar com tabelas seria o 1 exercicio
   dados = pd.read_csv('carros.csv', sep=',') #carregando dataset, carrecamos os dados do carro,
   depois usamos o dados.head(15) para mostrar as quantidades de linhas.dados.info() para informacoes, 
 

## Video Explicativo
   - Coloque aqui o link para o seu video explicando como o projeto foi desenvolvido, quais as dificuldades encontradas e qual a solução adotada.
   https://youtu.be/sIXXXotA_ZE
