
# Previsão do Preço das Ações 📊

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/> 

<p align='justify'>
Este projeto utiliza uma rede neural recorrente (LSTM) para prever os preços das ações, com dados obtidos da API do Yahoo Finance. O modelo é implementado utilizando a biblioteca PyTorch.


## Índice

- [Descrição](#descrição-📝)

- [Base de Dados](#base-de-dados-💾)

- [Resultados](#resultados-📶)

- [Contato](#contato)

## Descrição 📝

Este projeto busca prever os preços das ações da Tesla (TSLA) com base em dados históricos. Utilizamos uma rede neural LSTM devido à sua capacidade de capturar dependências de longo prazo nos dados sequenciais.

As principais etapas do projeto são:

1. **Importação das Bibliotecas**: Importação das bibliotecas necessárias, incluindo `pandas`, `numpy`, `torch`, `scikit-learn` e `yahoo_fin`.
2. **Preparação dos Dados**: Coleta e pré-processamento dos dados de preços das ações.
3. **Construção do Modelo**: Definição da arquitetura da rede neural LSTM.
4. **Treinamento do Modelo**: Treinamento do modelo com os dados históricos.
5. **Avaliação do Modelo**: Avaliação da performance do modelo e visualização dos resultados.

Para executar este projeto, você precisará ter o Python instalado em seu sistema, juntamente com as seguintes bibliotecas: 

- numpy 
- pandas
- scikit-learn
- matplotlib
- torch
- yahoo_fin

## Base de dados 💾 

<p align='center'>
<img src="https://github.com/ViniciusSilveiraCampos/Acoes_Previsao/assets/108243297/e49854ae-0b8f-4896-a001-7910522cc3e3" width=70%>

> A base de dados foi extraida através da <code>yahoo_fin</code>, uma biblioteca capaz de extrair dados financeiros, como a bolsa de valores. Assim podemos extrair os dados para descobrir o valor de fechamento das ações.


## Resultados 📶

O gráfico a seguir mostra a comparação entre os preços reais das ações da Tesla e as previsões feitas pelo modelo:

<p align='center'>
<img src="https://github.com/ViniciusSilveiraCampos/Acoes_Previsao/assets/108243297/13301825-6efb-4a89-b720-425c2c6af6f5" width=50%> </p>


A linha vermelha representa os preços reais, enquanto a linha azul representa as previsões do modelo.

## Contribuições

Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma nova branch com suas modificações: `git checkout -b minha-feature`
3. Faça commit das suas alterações: `git commit -m 'Adicionei uma nova feature'`
4. Faça push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

## Contato

Email: vivico2005@gmail.com

Link do Codigo: https://github.com/ViniciusSilveiraCampos/Acoes_Previsao/blob/main/Previsão_Preço_Das_Ações.ipynb

---
