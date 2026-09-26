⚡ PLD Forecasting (Prismatech) - LSTM & Data Engineering
Previsão Horária do Preço de Liquidação das Diferenças (PLD) no Mercado Livre de Energia Brasileiro.

Este repositório contém o código-fonte, os pipelines de dados e a modelagem preditiva desenvolvidos como parte do Trabalho de Conclusão de Curso (MBA em Data Science & Analytics) da Universidade de São Paulo (USP/ESALQ).

🚀 Sobre o Projeto
O modelo utiliza uma rede neural profunda Long Short-Term Memory (LSTM) conteinerizada em ambiente Serverless (Databricks) para prever a alta volatilidade e a não-linearidade do PLD.

O grande diferencial desta arquitetura é a sua abordagem híbrida: a Inteligência Artificial é encapsulada por uma regra de negócio determinística oficial do setor elétrico (a Banda de Saturação), travando as predições matemáticas ao piso regulatório definido pela Agência Nacional de Energia Elétrica (ANEEL).

🛠️ Tecnologias Utilizadas
Ambiente em Nuvem: Databricks (Serverless)

Linguagem: Python

Machine Learning / Deep Learning: TensorFlow, Keras, Scikit-Learn

Data Wrangling: Pandas, NumPy

Visualização: Matplotlib

📊 Desempenho do Modelo
Em testes de validação sobre cenários de 2025 (extrema volatilidade hídrica), o algoritmo apresentou aderência tática comercial para mesas de operação de Trading:

MAE: R$ 19,91 / MWh

RMSE: R$ 42,16 / MWh

Desenvolvido por Felipe Costa Medina para o portfólio de soluções preditivas da Prismatech.
