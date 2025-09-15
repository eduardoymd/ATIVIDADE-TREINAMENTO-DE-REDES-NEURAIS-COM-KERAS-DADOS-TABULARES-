# ATIVIDADE-TREINAMENTO-DE-REDES-NEURAIS-COM-KERAS-DADOS-TABULARES-
### EXERCÍCIO 1 – CLASSIFICAÇÃO MULTICLASSE
Dataset: Wine Dataset (UCI)
1. Treinar uma rede neural em Keras para classificar vinhos em 3 classes.
- Configuração mínima: 2 camadas ocultas com 32 neurônios cada, função de ativação ReLU.
- Camada de saída com 3 neurônios, função de ativação Softmax.
- Função de perda: categorical_crossentropy.
- Otimizador: Adam.
2. Comparar os resultados com um modelo do scikit-learn (RandomForestClassifier ou
LogisticRegression).
3. Registrar métricas de acurácia e discutir qual modelo teve melhor desempenho

---

### EXERCÍCIO 2 – REGRESSÃO
Dataset: California Housing Dataset (Scikit-learn)
1. Treinar uma rede neural em Keras para prever o valor médio das casas.
- Configuração mínima: 3 camadas ocultas com 64, 32 e 16 neurônios, função de ativação ReLU.
- Camada de saída com 1 neurônio, função de ativação Linear.
- Função de perda: mse.
- Otimizador: Adam.
2. Comparar os resultados com um modelo do scikit-learn (LinearRegression ou
RandomForestRegressor).
3. Registrar métricas de erro (RMSE ou MAE) e discutir qual modelo teve melhor desempenho.

# Respostas
# ExERCÍCIO 1 – CLASSIFICAÇÃO MULTICLASSE
### 2. Comparar os resultados com um modelo do scikit-learn:
- Tanto o RandomForest quanto a LogisticRegression conseguem classificar todas as amostras corretamente no conjunto de teste, então a acurácia é 1.000 (100%).
### 3. Registrar métricas de acurácia e discutir qual modelo teve melhor desempenho.
- Todos os modelos alcançaram desempenho perfeito neste dataset.
Para esse dataset específico, não há diferença de desempenho entre os modelos, todos foram igualmente eficazes.

# EXERCÍCIO 2 – REGRESSÃO
### 2. Comparar os resultados com um modelo do scikit-learn (LinearRegression ou RandomForestRegressor).
| Modelo              | RMSE   | MAE    |
| ------------------- | ------ | ------ |
| Linear Regression   | 0.7456 | 0.5332 |
| Random Forest       | 0.5055 | 0.3276 |
| Rede Neural (Keras) | 0.5291 | 0.3504 |

- O Random Forest Regressor teve o melhor desempenho no conjunto de teste, seguido de perto pela rede neural. O Linear Regression foi o menos preciso.
### 3. Registrar métricas de erro (RMSE ou MAE) e discutir qual modelo teve melhor desempenho.

O Random Forest Regressor foi o modelo mais eficaz para prever o valor médio das casas no conjunto de teste. A rede neural também foi eficiente, enquanto o Linear Regression teve desempenho limitado.

#INTEGRANTES
- Eduardo Eiki - RM 554921
- Nicollas Frei - RM 557647
- Heitor Duarte - RM 558208
