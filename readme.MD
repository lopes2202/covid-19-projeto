# COVID-19 Data Analytics com Pandas & Plotly
Este projeto realiza uma análise exploratória de dados (EDA) sobre os impactos da COVID-19 globalmente. O foco principal é a transformação de dados brutos em insights visuais, calculando métricas críticas como a Taxa de Letalidade por país e continente.

# Funcionalidades
Limpeza e Tratamento de Dados: Conversão de tipos de dados (strings para datetime/float) para manipulação precisa de séries temporais e métricas.

Cálculo de Letalidade: Implementação de lógica para extrair a porcentagem real de óbitos em relação aos casos confirmados.

Gráficos de Pizza para representação de mortes por continente.

Gráficos de Barras Ordenados para comparação de letalidade entre países.

# Tecnologias Utilizadas
Python 3.12

Pandas: Manipulação e tratamento de DataFrames.

Plotly Express: Biblioteca para geração de gráficos interativos e modernos.

Jupyter Notebook: Ambiente de desenvolvimento.

# Estrutura do Dataset
O projeto consome dados que incluem:

continent: Localização geográfica.

country: Nome do país analisado.

cases.total: Total de casos confirmados.

deaths.total: Total de óbitos registrados.

population(k): População total para normalização de dados.

letalidade: Letalidade dos casos para comparação.
