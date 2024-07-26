Previsão de Quantidade em Estoque

Este projeto utiliza um modelo de Machine Learning para prever a quantidade de produtos em estoque com base em dados históricos.
Descrição do Projeto

O objetivo deste projeto é prever a quantidade de produtos em estoque utilizando um conjunto de dados que inclui informações sobre promoções e datas. O modelo treinado é uma regressão linear simples.
Dados

O conjunto de dados contém as seguintes colunas:

    ID_PRODUTO: Identificador do produto.
    DIA: Data da observação.
    FLAG_PROMOCAO: Indica se o produto está em promoção (0 ou 1).
    QUANTIDADE_ESTOQUE: Quantidade do produto em estoque.

Preparação dos Dados

    A coluna DIA foi convertida para o formato datetime.
    Foram extraídas características adicionais da coluna DIA, como o dia da semana e o mês.

Modelo

O SageMaker Canvas selecionou automaticamente o melhor modelo de machine learning para prever a QUANTIDADE_ESTOQUE.
Avaliação do Modelo

O modelo foi avaliado utilizando as seguintes métricas:

    Erro quadrático médio (MSE): 644.74
    Coeficiente de determinação (R²): 0.21
