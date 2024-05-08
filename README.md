##  Inovação em Gestão Florestal: Automatização do Sequenciamento de Colheita 🌲

Descrição do Projeto
Este repositório contém um script Python projetado para facilitar o planejamento e a execução do plano de colheita florestal. O script utiliza uma combinação de bibliotecas Python para manipular dados, realizar análises geoespaciais, visualizar dados e automatizar a geração de relatórios. O objetivo é otimizar o sequenciamento de operações, a logística de colheita e o monitoramento das atividades através de dados extraídos e processados de planilhas Excel e shapefiles.

Funcionalidades
Importação e Manipulação de Dados: Utiliza Pandas para carregar e manipular dados de planilhas Excel.
Análise Geoespacial: Emprega GeoPandas e Shapely para manipular e realizar operações espaciais com dados geográficos.
Visualização de Dados: Gera visualizações usando Matplotlib para analisar as mudanças e distribuições de operações.
Relatórios Automatizados: Cria relatórios dinâmicos e exporta resultados para Excel com a biblioteca OpenPyXL.
Mapeamento Interativo: Utiliza Folium para criar mapas interativos que facilitam a visualização da distribuição geográfica das operações de colheita.

Estrutura do Código
Preparação e Limpeza de Dados: Inicialmente, o script carrega os dados das planilhas Excel, limpa dados ausentes e converte tipos de dados conforme necessário para análise.
Cálculo de Capacidades e Sequenciamento: Calcula a capacidade de produção e realiza o sequenciamento de colheita baseado em capacidades pré-definidas e inventário atual.
Análise Espacial: Realiza junções espaciais para enriquecer o dataset com informações geográficas dos municípios e estados a partir de um shapefile dos municípios do Brasil.
Visualizações: Gera gráficos para visualizar o número de mudanças de blocos por data e a distância total percorrida por período.
Exportação de Resultados: Os resultados das análises são exportados de volta para o Excel, com a inclusão de gráficos e imagens onde aplicável.

Como Usar
Para utilizar este script, você precisará das seguintes dependências instaladas:

matplotlib: 3.8.4
pandas    : 2.2.2
geopandas : 0.14.4
openpyxl  : 3.1.2
numpy     : 1.26.4
folium    : 0.16.0
