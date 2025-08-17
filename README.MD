================Projeto de Análise de Desempenho e Tendências do Sistema Fotovoltaico no Brasil===============

Este projeto tem como objetivo analisar as tendências de crescimento e queda da energia solar no Brasil, considerando o período de 2009 a 2025. A análise busca identificar padrões de sazonalidade, variações anuais e fatores que influenciam o desempenho do sistema fotovoltaico no país. Serão utilizadas técnicas de visualização de dados e estatística para compreender o comportamento da geração de energia solar ao longo dos anos e apoiar tomadas de decisão para o setor. os dados utilizados serão obtidos através de dados da ANEEL, que fornece informações detalhadas sobre a geração de energ#ia solar no Brasil. Esse projeto visa contribuir para o entendimento do crescimento da energia solar no país e auxiliar na formulação de políticas públicas e estratégias de investimento no setor, tambem ver como sistemas fotovoltaicos esta ficando saturado no Brasil, e como isso pode afetar o mercado de energia.

# Requisitos do Projeto
- Python 3.11
- Bibliotecas: pandas, numpy, matplotlib, seaborn, requests entre outras.
- Jupyter Notebook ou ambiente de desenvolvimento Python.
# Estrutura do Projeto
- `README.md`: Documentação do projeto.
- `projeto-energia-solar.ipynb`: Notebook Jupyter contendo o código e as análises.
- `16/08/205`: Pasta para armazenar os dados utilizados no projeto.
- `16/08/2025`: Arquivo CSV contendo os dados de geração de energia solar no Brasil.
# Introdução
A energia solar tem se destacado como uma fonte renovável de energia no Brasil, especialmente nos últimos
    anos. Este projeto visa analisar o desempenho do sistema fotovoltaico no país, identificando tendências de crescimento e sazonalidade na geração de energia solar. Utilizando dados da ANEEL, serão explorados padrões anuais e mensais, além de fatores que influenciam a geração de energia solar.
# Objetivos do Projeto
- Analisar o crescimento da energia solar no Brasil entre 2009 e 2025.
- Identificar padrões de sazonalidade e variações anuais na geração de energia solar.
- Explorar fatores que influenciam o desempenho do sistema fotovoltaico.
- Contribuir para a formulação de políticas públicas e estratégias de investimento no setor de energia solar.   

# Importação de Bibliotecas
Para iniciar o projeto, vamos importar as bibliotecas necessárias para manipulação de dados, visualização e análise estatística. As principais bibliotecas utilizadas serão `pandas` para manipulação de dados, `numpy` para operações numéricas, `matplotlib` e `seaborn` para visualização de dados, e `requests` para obter os dados da ANEEL.

```python   
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import requests
```
# Leitura dos Dados
Neste projeto, utilizaremos dados da ANEEL (Agência Nacional de Energia Elétrica) que fornece informações detalhadas sobre a geração de energia solar no Brasil. Os dados serão lidos a partir de um arquivo CSV que contém informações sobre a geração de energia solar no país, incluindo dados mensais e anuais.

# Tratamento de Dados
Após a leitura dos dados, é importante realizar um tratamento para garantir que as informações estejam limpas e prontas para análise. Isso inclui a remoção de valores ausentes, conversão de tipos de dados e formatação de colunas e outros.