<h1> Plano de Colheita Automatizado 🌲</h1> 
<p></p>
<h2> Descrição do Projeto </h2>
<p></p>
Este repositório contém um script Python desenvolvido para automatizar a criação do plano de colheita baseado em dados de inventário florestal e capacidade de produção. O script realiza a importação de dados, processamento de sequenciamentos, cálculos de volumes e distâncias, e gera visualizações geográficas e gráficas dos dados processados.
<p></p>

<h2> Bibliotecas Utilizadas </h2>
Pandas para manipulação de dados e operações com DataFrames.
NumPy para cálculos numéricos.
Folium para visualizações geográficas em mapas.
Matplotlib para a criação de gráficos.
OpenPyXL para a leitura e escrita de arquivos Excel.
GeoPandas e Shapely para manipulação de dados geográficos.
os e math para funcionalidades de sistema e cálculos matemáticos.
<p></p>

<h2> Estrutura do Código </h2>
Preparação e Limpeza de Dados: Inicialmente, o script carrega os dados das planilhas Excel, limpa dados ausentes e converte tipos de dados conforme necessário para análise.
Cálculo de Capacidades e Sequenciamento: Calcula a capacidade de produção e realiza o sequenciamento de colheita baseado em capacidades pré-definidas e inventário atual.
Análise Espacial: Realiza junções espaciais para enriquecer o dataset com informações geográficas dos municípios e estados a partir de um shapefile dos municípios do Brasil.
Visualizações: Gera gráficos para visualizar o número de mudanças de blocos por data e a distância total percorrida por período.
Exportação de Resultados: Os resultados das análises são exportados de volta para o Excel, com a inclusão de gráficos e imagens onde aplicável.

<h2> Como Usar </h2>
Para utilizar este script, você precisará das seguintes dependências instaladas:

matplotlib: 3.8.4
pandas    : 2.2.2
geopandas : 0.14.4
openpyxl  : 3.1.2
numpy     : 1.26.4
folium    : 0.16.0
