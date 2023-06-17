# Teste de Hipótese: Comparação de Ações NVIDIA e AMD

Este repositório contém um código Python para realizar um teste de hipótese comparando as ações da NVIDIA e AMD durante a pandemia. O teste de hipótese é baseado na média das ações dessas duas empresas.

## Descrição do Projeto

O objetivo deste projeto é comparar as médias dos preços de fechamento ajustados das ações da NVIDIA e AMD durante a pandemia e determinar se há diferença significativa entre elas. O teste de hipótese é realizado utilizando o teste t de Student.

O código lê os dados das ações da NVIDIA e AMD de arquivos CSV, faz a imputação de dados faltantes, mescla os dados em um único DataFrame e realiza o teste de hipótese. Além disso, ele também cria gráficos para visualizar os dados e a distribuição normal com o valor da estatística t.

## Como executar o código

1. Certifique-se de ter o Python instalado (versão 3.6 ou superior).

2. Clone este repositório:

```
git clone https://github.com/FilipeSCampos/T-Test-Student.git
```

3. Instale as dependências necessárias:

```
import pandas as pd
import scipy 
from statistics import stdev 
from math import sqrt
from scipy import stats
import matplotlib.pyplot as plt
import numpy as np
from scipy.stats import t
```

5. Coloque os arquivos CSV contendo os dados das ações da NVIDIA e AMD na raiz do diretório do projeto. Certifique-se de nomear os arquivos corretamente como `NVIDIA (1999-2023).csv` e `AMD (1980-2023).csv`.

6. Execute o código Python:

```
python Teste T.ipynb

```


7. O código exibirá a estatística t, os graus de liberdade, o valor crítico de t e o valor p obtidos no teste de hipótese. Além disso, ele plotará gráficos para visualizar os dados e a distribuição normal com o valor da estatística t marcado.

## Resultados

![image](https://github.com/FilipeSCampos/T-Test-Student/assets/113521439/8299266e-67e9-40f0-8c21-efb558cb052b)

Os resultados do teste de hipótese indicarão se há diferença significativa entre as médias das ações da NVIDIA e AMD durante a pandemia.

T-statistc: 33.12634819243399

Degrees of freedom: 1648

T-critical value: 1.645778767293261

P-value: 0.0

T-statistic: 33.12634819243399

P-value: 7.239358972768469e-185

Como podemos ver, devemos descartar a Hipotese 0 

![image](https://github.com/FilipeSCampos/T-Test-Student/assets/113521439/f4d71215-4f98-4f60-8608-6e4d3bce7237)


## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias para o código ou outras análises relacionadas, sinta-se à vontade para abrir uma issue ou enviar um pull request.







