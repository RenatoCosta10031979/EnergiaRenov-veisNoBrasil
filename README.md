# **Projeto Final**
Bem-vindo ao repositório do projeto de análise de dados "PANORAMA NACIONAL DE ENERGIAS RENOVÁVEIS NO BRASIL: RISCOS E OPORTUNIDADES".

Este repositório contém alguns dos recursos utilizados para realizar análises de dados sobre tema proposto no projeto de conclusão do BOOTCAMP MARTECH SOULCODE ACADEMY - ANALISTA DE DADOS - AD2.

Foram utilizadas tecnologias e ferramentas como o Google Colab, Google Cloud Storage, BigQuery, Looker Studio, Power BI, MongoDB, Python Pandas e PySpark para realizar análises avançadas.

## **Contexto**
A energia produzida em território nacional tem como principal fonte de geração as usinas hidrelétricas.

Entretanto, nos últimos anos, mais precisamente a partir de 2017, observa-se um crescimento acentuado de energias renováveis. Segundo as consultas realizadas no projeto, em bases de dados públicas, sejam governamentais ou particulares, parte da evolução da energia pode ser explicada pela grande expansão de geração e oferta de energia solar, que a partir de 2017 cresceu em ritmo acelerado, acompanhado também pela energia eólica, de forma mais discreta.

O Brasil é um país de dimensões continentais e possui extensas áreas tem cobertura de radiação solar por longos meses, como parte do Sudeste e Centro-Oeste e principalmente a região Nordeste, onde concentra-se maior quantidade de usinas e fazendas para geração centralizada de energia solar. Contudo essa não é a única fonte de geração de energia solar. A longa exposição solar em todo o país, somada a incentivos e regulamentações inovadoras, favorecendo a utilização de energias renováveis, em especial, a energia solar fotovoltaica, permitiu a instalação das mini e micro geradoras de energia solar, denominada de geração distribuída.

A geração distribuída, principalmente resultante do excedente de energia produzida e da geração compartilhada tem aumentado consideravelmente ano a ano a disponibilidade de energia no sistema de distribuição, barateando a médio prazo os custos de geração, já que os investimentos necessários são diluídos ao longo do tempo.

Destaca-se, aqui, além do alívio à sobrecarga da matriz energética nacional, a utilização de novas tecnologias que demandem uso de energia elétrica, como o abastecimento de pontos de recarga para carros híbridos e elétricos, instalados em diversas localidades. Servindo como complemento de fonte de fornecimento, esses pontos ajudam a ampliar a oferta de local, próxima a pontos de recarga e/ou alta demanda consumidora, consequentemente, a aumentando a utilização de equipamentos e veículos a base de energia limpa.

## **Recursos Utilizados**

Neste projeto, utilizamos as seguintes ferramentas e tecnologias:

- [Google Colab](https://colab.research.google.com/): Uma plataforma de notebooks interativos que permite escrever e executar código Python em um ambiente baseado na nuvem.

- [Google Cloud Storage](https://cloud.google.com/storage): Um serviço de armazenamento na nuvem altamente escalável e durável oferecido pelo Google.

- [BigQuery](https://cloud.google.com/bigquery): Um serviço de análise de dados que permite executar consultas SQL em conjuntos de dados extremamente grandes.

- [Looker Studio](https://looker.com): Uma plataforma de análise e visualização de dados que facilita a exploração de informações.

- [Power BI](https://powerbi.microsoft.com/): Uma ferramenta de análise de negócios da Microsoft que permite visualizar dados e compartilhar insights.

- [MongoDB](https://www.mongodb.com/): Um banco de dados NoSQL orientado a documentos, adequado para armazenar e gerenciar grandes volumes de dados não estruturados.

- [Python Pandas](https://pandas.pydata.org/): Uma biblioteca popular para análise de dados em Python.

- [PySpark](https://spark.apache.org/docs/latest/api/python/index.html): A biblioteca Python para Spark, uma estrutura de processamento de dados em grande escala.


## **Notebooks e Scripts**

Neste repositório, você encontrará os seguintes notebooks e scripts:

- [Notebook de Análise de Dados](https://colab.research.google.com/github/squadOito/soulcodead2/blob/main/notebooks/fator_capacidade_mwh_2015_2023.ipynb): Notebook Colab com processo ETL e análise de dados com Pandas.

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_2_1_cap_instalada_por_regiao_e_uf_tratado.ipynb): Notebook Colab com processo ETL e análise de dados com Pandas.

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/2_2_cap_instalada_de_geracao_eletrica_por_fonte_mw.ipynb): Notebook Colab com processo ETL e análise de dados com Pandas.

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_2_3_geracao_eletrica_por_fonte_gwh_tratado.ipynb): Notebook Colab com processo ETL e análise de dados com Pandas.

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_geracao_distribuida_pyspark_tratado.ipynb): Consultas com PySpark.

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_global_horizontal_means_tratad.ipynb): Notebook Colab com processo ETL usando Pandas.

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_iea_ponto_recarga_pyspark_bruto.ipynb): Notebook Colab com processo ETL usando Pyspark (ponto de recarga).

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_iea_ponto_veiculos_pyspark_bruto.ipynb): Notebook Colab com processo ETL usando Pyspark (ponto veículo).

- [Notebook de Análise de Dados](https://colab.research.google.com/github/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/notebooks/notebook_mongoDB_carregamento_parquet.ipynb): Notebook Colab com comandos para realização de backup no MongoDB (arquivo parquet).

## **Dasboards**

- [Looker Studio Dashboard](https://github.com/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/dashboards/LookerStudio.pdf): Acesse o dashboard criado com Looker Studio para visualização  detalhada de dados relacionados a Energias Renováveis no Brasil.
- - [Power BI Dashboard](https://github.com/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/dashboards/PowerBI.pdf): Explore o dashboard desenvolvido no Power BI para análise visual de dados sobre Energias Renováveis no Brasil.
- [Notebook de Dashboards](https://github.com/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/dashboards/dashboards.ipynb): Acesse o notebook que contém a implementação dos dashboards para visualização interativa de dados sobre Energias Renováveis no Brasil.

## **Slide Apresentação Projeto Final**
- [Apresentação do Projeto Final](https://github.com/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/blob/main/dashboards/Slides.pdf): Confira a apresentação em slides do projeto final sobre Energias Renováveis no Brasil.




## **Dicionário e Conjuntos de Dados**
Para auxiliar no entendimento do projeto, seguem o dicionário e amostragem do conjunto de dados utilizado:



[Dicionários](https://github.com/RenatoCosta10031979/EnergiaRenovaveisNoBrasil/tree/main/documentation): Acesso aos dicionários utilizados no processamento de dados já tratados.

conjuntos de dados: Amostragem dos conjuntos de dados trabalhados no projeto em formato parquet.


