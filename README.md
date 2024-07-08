# 📊 (Entrega do Desafio) Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Repositório de entrega do desafio de projeto do Bootcamp Nexa - Machine Learning para Iniciantes na AWS.

Objetivos do Desafio: 



## 🚀 Passo a Passo

### 1. Selecionar Dataset

Para o meu modelo de predição eu utilizei um dataset próprio (utilizei o próprio ChatGPT para criar um modelo de 500 linhas), que está neste repositório como: "**dataset-previsao-estoque**". Criei um modelo com o nome de "**previsao-estoque**" e fiz o upload do arquivo do dataset. 

### 2. Construir/Treinar

Para o treinamento do modelo, configurei da seguinte forma: 

- "*target column*" para usar a coluna "quantidade_estoque";
- "*item ID column*" para "id_produto";
- "*Time stamp column*" para "dia";

### 3. Analisar

Nas métricas de análise meu modelo teve os seguintes resultados:

- Avg. wQL = 0.346;
- MAPE = 0.971;
- WAPE = 0.581;
- RMSE = 36.006;
- MASE = 0.852;

De acordo com uma pesquisa e com ajuda do ChatGPT pude saber qual seria o nível de eficiência do meu modelo.

**Pontos Positivos:** O Avg. wQL e o MASE indicam que o modelo tem um desempenho razoável em termos de precisão e é melhor do que o modelo de referência simples.
**Pontos Negativos:** O MAPE e o WAPE são altos, sugerindo que as previsões têm uma alta porcentagem de erro. O RMSE também é alto, indicando que os erros absolutos das previsões são significativos.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.
