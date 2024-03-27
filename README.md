# Previsão de Score de Crédito
Este projeto consiste em desenvolver um modelo de machine learning para prever o score de crédito de clientes com base em suas características. O objetivo é utilizar diferentes algoritmos de classificação para prever o score de crédito de novos clientes, a fim de tomar decisões mais informadas em relação a concessão de crédito.

## Visão Geral do Projeto
O processo de previsão do score de crédito é realizado utilizando a biblioteca scikit-learn em Python. O fluxo de trabalho inclui os seguintes passos:

1 - Importação da base de dados de clientes. <br>
2 - Transformação das informações categóricas em números para que possam ser processadas pelo modelo. <br>
3 - Escolha das colunas relevantes para treinar o modelo. <br>
4 - Divisão dos dados em conjuntos de treinamento e teste. <br>
5 - Treinamento de dois modelos de machine learning: Árvore de Decisão e KNN (K-Vizinhos Mais Próximos). <br>
6 - Avaliação da acurácia dos modelos treinados. <br>
7 - Previsão do score de crédito para novos clientes com base no modelo treinado. <br>

## Funcionalidades Principais
- Tratamento de Dados: O projeto realiza o tratamento de dados, transformando informações categóricas em números para serem processadas pelo modelo de machine learning.
- Treinamento de Modelos: Utiliza dois modelos de machine learning: Árvore de Decisão e KNN, para prever o score de crédito dos clientes.
- Avaliação da Acurácia: Avalia a acurácia dos modelos treinados utilizando a métrica de acurácia.
- Previsão de Score de Crédito: Realiza a previsão do score de crédito para novos clientes com base nos modelos treinados.

## Como Utilizar
- Clone este repositório em sua máquina local.
- Certifique-se de ter Python instalado em seu ambiente.
- Instale as bibliotecas necessárias executando pip install pandas scikit-learn.
- Coloque seus arquivos de dados (clientes.csv e novos_clientes.csv) na pasta do projeto.
- Execute o script Python para iniciar o processo de previsão de score de crédito.
- Verifique os resultados das previsões no console ou em qualquer outra saída que você tenha configurado.


## Aviso
Este projeto foi desenvolvido para fins de estudo e demonstração. Certifique-se de entender os princípios por trás dos modelos de machine learning antes de utilizá-los em aplicações de produção.
A acurácia dos modelos pode variar dependendo dos dados e das características dos clientes. Recomenda-se ajustar os modelos e os dados conforme necessário para obter melhores resultados.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request com melhorias ou correções.
