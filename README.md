# Intraday Correlation Analysis

## First Task: Aplicando Correlação

- Considerar somente os 11 index temáticos
- Calcular o retorno - usando OPEN/CLOSE dos index
- Calcular a correlação (janela de 500) desses index dois-a-dois
- Para cada combinação, calcular o 90%, 10% e mediana

## Second Task: Aplicando PCA

- Considerar o mesmo conjunto de index
- Calcular o retorno - usando OPEN/CLOSE dos index
- Calcula-se a matrix de covariância com uma janela de tamanho 500
- Aplica-se o PCA em cada um dessa matrix
- Considera-se a explicação dos 3 primeiros autovalores
