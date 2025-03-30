# Stock Price Prediction 📊  

<div align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>  
</div>

<p align='justify'>  
This project uses a recurrent neural network (LSTM) to predict stock prices, with data obtained from the Yahoo Finance API. The model is implemented using the PyTorch library.  

## Index  

- [Description](#description)  
- [Dataset](#dataset)  
- [Results](#results)  
- [Contact](#contact)  

## Description

This project aims to predict Tesla's (TSLA) stock prices based on historical data. We use an LSTM neural network due to its ability to capture long-term dependencies in sequential data.  

The main steps of the project are:  

1. **Importing Libraries**: Importing necessary libraries, including `pandas`, `numpy`, `torch`, `scikit-learn`, and `yahoo_fin`.  
2. **Data Preparation**: Collecting and preprocessing stock price data.  
3. **Model Construction**: Defining the architecture of the LSTM neural network.  
4. **Model Training**: Training the model with historical data.  
5. **Model Evaluation**: Evaluating model performance and visualizing results.  

To run this project, you need to have Python installed on your system, along with the following libraries:  

- numpy  
- pandas  
- scikit-learn  
- matplotlib  
- torch  
- yahoo_fin  

## Dataset

<p align='center'>  
<img src="https://github.com/ViniciusSilveiraCampos/Acoes_Previsao/assets/108243297/e49854ae-0b8f-4896-a001-7910522cc3e3" width=70%>  

> The dataset was extracted using the <code>yahoo_fin</code> library, which allows retrieving financial data such as stock market prices. This enables us to extract data to determine stock closing values.  

## Results

The following graph shows a comparison between the actual Tesla stock prices and the model’s predictions:  

<p align='center'>  
<img src="https://github.com/ViniciusSilveiraCampos/Acoes_Previsao/assets/108243297/13301825-6efb-4a89-b720-425c2c6af6f5" width=50%> </p>  

The red line represents actual prices, while the blue line represents the model’s predictions.  

## Contributions  

Contributions are welcome! If you want to contribute to this project, follow these steps:  

1. Fork the project.  
2. Create a new branch with your modifications: `git checkout -b my-feature`  
3. Commit your changes: `git commit -m 'Added a new feature'`  
4. Push to the branch: `git push origin my-feature`  
5. Open a Pull Request  
