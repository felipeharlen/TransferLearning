# Treinamento de Redes Neurais com Transfer Learning

Este projeto faz parte das atividades do curso de Machine Learning Specialist da Digital Innovation One (DIO). Neste projeto, foi aplicada a técnica de transfer learning para a classificação de imagens de cães e gatos usando um conjunto de dados do Kaggle e pesos pré-treinados da rede neural InceptionV3 no ImageNet. Todo o desenvolvimento foi realizado no Jupyter Notebook.

## Objetivo

O objetivo deste projeto é explorar e demonstrar como é possível tirar proveito de modelos de aprendizado profundo já treinados em tarefas amplas, como o ImageNet, e adaptá-los para uma tarefa específica, como a classificação de imagens de cães e gatos. A aplicação desta técnica economiza tempo e recursos na construção de um modelo eficaz para essa tarefa.

## Passos Principais

- Preparação dos dados: Os conjuntos de dados de cães e gatos do Kaggle foram pré-processados e divididos em conjuntos de treinamento, validação e teste.

- Transfer Learning: Foi utilizada a arquitetura InceptionV3 pré-treinada no ImageNet como base do modelo.

- Treinamento: A última camada da rede foi ajustada para classificar entre cães e gatos, e o modelo foi treinado com os dados de treinamento.

- Avaliação: O desempenho do modelo foi avaliado usando os dados de validação e teste.

## Ambiente de Desenvolvimento

- Jupyter Notebook
- Python 3
- Bibliotecas de Machine Learning, como TensorFlow e Keras

## Resultados

O modelo de classificação treinado alcançou uma precisão significativa (superior a 92%) na tarefa de distinguir entre cães e gatos, demonstrando a eficácia da técnica de transfer learning para essa tarefa específica.

Este projeto é uma oportunidade de aprendizado e prática de técnicas avançadas de Machine Learning e Deep Learning.

**Data:** 22 de Outubro de 2023

*Este projeto faz parte do curso Machine Learning Specialist da Digital Innovation One (DIO).*
