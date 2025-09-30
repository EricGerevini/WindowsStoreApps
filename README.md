# Estudo sobre a estatísticas dos aplicativos do windowns store
Neste estudo, levarei em consideração os seguintes dados de cada aplicativo:

- Data de lançamento
- Classificação
- Número de avaliações
- Preço
- Categoria 

Obs: Também foi o processo seletivo do meu atual emprego =)

No python, utilizei as seguintes bibliotecas:

- Pandas
- Matplotlib
- Numpy

# Objetivos
Neste projeto tenho como objetivo procurar correlações entre alguns dados:

1 - Existe relação entre a avaliação dos aplicativos e a quantidade de avaliações? 

2 - E entre a data de publicação e as avaliações?

3 - Os aplicativos pagos são melhor avaliados?

# Pré Requisitos
Necessário importar os pacotes; pandas para trabalhar com o dataframe, numpy para trabalhar com os vetores(array's) e o matplotlib para plotar o gráfico.

```
import pandas as pd

import numpy as np

import matplotlib.pyplot as plt
```

# Fonte de Dados

A 3 tabelas de dados estão disponíveis para download.

# Resultados

Os resultados foram bastante satisfatórios:

1 - Encontrei uma forte correlação (0.88 utilizando o método de Pearson) entre a avaliação dos aplicativos e a quantidade de avialiações.
Evidenciando que os aplicativos mais avaliações tendem a ser melhor avaliados.

2 - No segundo problema, a correlação encontrada foi baixa (-0.27 utilizando o método de Perason) entre a data de publicação e as avaliações.
Evidenciando que os não existe (ou muito baixa) correlação.

3 - Neste problema, a análise feita mostrou que a médias das notas dos aplicativos pagos foram menores que os aplicativos de graça.

Os resultados podem ser vários motivos, algumas conclusÕes(pessoais) foram:

1 - Os aplicativos que são melhores avaliados, tendem a ter mais downloads e um maior número de clientes satisfeitos, e os aplicativos com menor nota o oposto.

2 - No segundo não houve correlação, portanto nõa cabe uma análise qualitative do resultado.

3 - Neste resultado, esse resultado pode acontecer devido uma maior rigorosidade dos clientes por pagarem pelo seus produtos.

# Referências 

https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp

Obrigado e espero que gostem do meu segundo projeto/estudo em dataframe em python.

Abraços o/
