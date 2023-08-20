# Modelo-de-regressao-para-fenotipagem-de-tomateiro
Modelo de regressão para predição da doença Requeima em plantas de tomate (para estudo)

Nesta atividade temos a disposição um banco de dados de fenotipagem de tomateiro.

Foram desenvolvidos modelos de regressão para predição da severidade da doença 'Requeima' em plantas de tomate a partir de informações retiradas de imagens aéreas das plantas.

Foram treinados os seguintes modelos:
- Máquina de vetor de suporte (Support Vector Regressor);
- K-vizinhos mais próximos (K-Neighbors Regressor);
- Árvore de regressão (Random Forest Regressor);
- Gradiente descendente estocástico (Stochastic Gradient Descent)

Técnicas de otimização utilizadas:
- Redução de features por eliminação recursiva;
- Redução de features por testes estatísticos (correlação cruzada);
- Otimização de hiperparâmetros através da redução da pontuação em teste de validação cruzada do modelo.

O melhor resultado obtido foi o modelo que utilizou a técnica K-vizinhos mais próximos.
Esse modelo obteve a métrica r2 = 0.9101809113157263 para os dados de teste.
