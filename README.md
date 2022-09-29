# Projeto Prático



#  Etapa 1 - Entendendo o Problema

---

- Problema - Você foi contratado pela Quinto Andar para ser Analista de Dados. A sua primeira tarefa é analisar um conjunto de dados sobre preço de aluguel casas e responder as seguintes perguntas:

- [x]  Em quais cidades se concentram a maior quantidade de casas?
- [x]  Em quais cidades estão os imóveis com maior preço de aluguel?
- [x]  Ter animais impacta no preço do aluguel?
- [x]  As casas mobiliadas possuem um preço de aluguel mais alto?

- Ferramentas usadas: Python e Google Colab
    
    [Google Colaboratory](https://colab.research.google.com/drive/1mZnWqkTU7ZtHfcXTVj9qgOfyR_jDVgdt?usp=sharing)
    

#  Etapa 2 - Coletando os Dados

---

- A equipe realizou a extração dos dados diretamente do Banco e forneceu a você um conjunto de dados no formato Excel contendo variáveis importantes e que podem ser úteis para responder essas perguntas.
    - Cidade que as casas se localizam;
    - Área em metros quadrados da casa
    - Quantidade de quartos;
    - Quantidade de banheiros;
    - Quantidade de vagas de Estacionamento;
    - Andar da casa;
    - Se aceita animais;
    - Preço da taxa de condomínio;
    - Preço do aluguel;
    - Preço da Taxa de IPTU;
    - Preço da Taxa de Incêndio;
    - Preço total do aluguel.
    
    [Loading Google Sheets](https://docs.google.com/spreadsheets/d/1ivNOCdU_qmQdiNOxQABHhYpVSNEsQ55K/edit?usp=sharing&ouid=104413768616625233151&rtpof=true&sd=true)
    

#  Etapa 3 - Análise Exploratória dos Dados

---

- Na maioria dos casos a gente entra nessa etapa sem saber o que tem nas mãos.
    - Seu trabalho é mergulhar nos dados que coletou visando extrair informação
        - Dados → Informação → Insights
    - Dar sentido aos dados.
- Quando bem feita é certeza de um projeto de sucesso!
- Foco nas perguntas que preciso responder:
    - [x]  Em quais cidades se concentram a maior quantidade de casas?
    - [x]  Em quais cidades estão os imóveis com maior preço de aluguel?
    - [x]  Ter animais impacta no preço do aluguel?
    - [x]  As casas mobiliadas possuem um preço de aluguel mais alto?
- Use sua caixa de ferramentas
    - Criatividade
    - Bibliotecas e Ferramentas
    - Regra de Negócio
- Bibliotecas úteis para Análise e Visualização de Dadas
    - Pandas
    
    [pandas](https://pandas.pydata.org/)
    
    - Matplotlib
    
    [Tutorials - Matplotlib 3.5.1 documentation](https://matplotlib.org/stable/tutorials/index.html)
    
    - NumPy
    
    [NumPy](https://numpy.org/)
    
    - Seaborn
    
    [seaborn: statistical data visualization - seaborn 0.11.2 documentation](https://seaborn.pydata.org/)
    
- Sabia que existe uma forma automatizada?
    - SweetViz
        
        [sweetviz](https://pypi.org/project/sweetviz/)
        

# **📊** Etapa 4 - Apresentação

---

- [x]  Em quais cidades se concentram a maior quantidade de casas?

0 Conjunto de dados possui 13 colunas e 10.692 registros de casas

São Paulo         5887
Rio de Janeiro    1501
Belo Horizonte    1258
Porto Alegre      1193
Campinas           853

![Grafico_qtd_casas_por_cidade.png](Projeto%20Pra%CC%81tico%20186cf9ceac9747aca439118c55731eb0/Grafico_qtd_casas_por_cidade.png)

- [x]  Em quais cidades estão os imóveis com maior preço de aluguel?

Belo Horizonte    3040.0
Campinas          2140.0
Porto Alegre      2211.0
Rio de Janeiro    3253.0
São Paulo         4596.0

![Grafico_cidade_preco_aluguel.png](Projeto%20Pra%CC%81tico%20186cf9ceac9747aca439118c55731eb0/Grafico_cidade_preco_aluguel.png)

- [x]  Ter animais impacta no preço do aluguel?

![grafico_qtd_residencia_aceita_animal.png](Projeto%20Pra%CC%81tico%20186cf9ceac9747aca439118c55731eb0/grafico_qtd_residencia_aceita_animal.png)

![grafico_relação_entre_cidade_aluguel_animais.png](Projeto%20Pra%CC%81tico%20186cf9ceac9747aca439118c55731eb0/grafico_relao_entre_cidade_aluguel_animais.png)

- [x]  As casas mobiliadas possuem um preço de aluguel mais alto?

nao    3170.0
sim    4855.5

![grafico_relacao_aluguel_casasmobiliada.png](Projeto%20Pra%CC%81tico%20186cf9ceac9747aca439118c55731eb0/grafico_
