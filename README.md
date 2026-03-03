# echo-state-network-from-scratch
Implementação de uma Echo State Network (ESN) do zero em Python para previsão de séries temporais caóticas (Mackey-Glass).

# Classical Reservoir Computing (ESN)

Este repositório contém uma implementação detalhada de uma **Echo State Network (ESN)**, a arquitetura clássica de **Reservoir Computing**. 

O objetivo é demonstrar como um sistema dinâmico de pesos fixos e aleatórios (o reservatório) pode ser usado para processar informações sequenciais complexas, treinando apenas a camada de saída (*readout*).

## Destaques do Projeto
- **Implementação "From Scratch":** Construída do zero utilizando apenas `NumPy` para a dinâmica do reservatório.
- **Eficiência:** Demonstração de como o treinamento via Regressão Ridge rápido.
- **Benchmark Caótico:** Aplicação na série temporal de **Mackey-Glass**, um sistema dinâmico não-linear clássico.
- **Visualização:** Gráficos detalhados de estados do reservatório, erros de predição e previsões autoregressivas.

## Tecnologias Utilizadas
* Python 3
* NumPy (Álgebra Linear e Dinâmica)
* Scikit-Learn (Readout Training via Ridge Regression)
* Matplotlib (Visualização de Dados)

## Resultados
O modelo alcançou um **NRMSE (Normalized Root Mean Square Error)** baixo, mostrando a eficácia das ESNs em capturar a estrutura de sistemas caóticos com custo computacional mínimo.

---
*Este estudo faz parte do meu portfólio de Machine Learning e Processamento de Sinais.*
