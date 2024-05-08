<h1>Plano de Colheita Automatizado 🌲 </h1>

<h2>Descrição</h2>
<p>Este repositório contém um script Python desenvolvido para automatizar a criação do plano de colheita baseado em dados de inventário florestal e capacidade de produção. O script realiza a importação de dados, processamento de sequenciamentos, cálculos de volumes e distâncias, e gera visualizações geográficas e gráficas dos dados processados.</p>

<h2>Bibliotecas Utilizadas</h2>
<ul>
  <li><strong>Pandas</strong> para manipulação de dados e operações com DataFrames.</li>
  <li><strong>NumPy</strong> para cálculos numéricos.</li>
  <li><strong>Folium</strong> para visualizações geográficas em mapas.</li>
  <li><strong>Matplotlib</strong> para a criação de gráficos.</li>
  <li><strong>OpenPyXL</strong> para a leitura e escrita de arquivos Excel.</li>
  <li><strong>GeoPandas</strong> e <strong>Shapely</strong> para manipulação de dados geográficos.</li>
  <li><strong>os</strong> e <strong>math</strong> para funcionalidades de sistema e cálculos matemáticos.</li>
</ul>

<h2>Estrutura do Código</h2>
<ol>
  <li><strong>Importação de Módulos</strong>: Inicialmente, o script importa todas as bibliotecas necessárias.</li>
  <li><strong>Carregamento de Dados</strong>: Utiliza Pandas para carregar os dados de inventário e capacidades de produção de arquivos Excel.</li>
  <li><strong>Preparação de Dados</strong>: Limpeza e transformação dos dados, incluindo remoção de linhas vazias e conversão de tipos de dados.</li>
  <li><strong>Processamento Geográfico</strong>: Uso de GeoPandas para enriquecer os dados do inventário com informações geográficas, realizando um spatial join com um shapefile de municípios brasileiros.</li>
  <li><strong>Cálculos de Volumes e Distâncias</strong>: Cálculo de volumes de colheita baseados no inventário e cálculo de distâncias usando a fórmula de Haversine.</li>
  <li><strong>Visualização de Dados</strong>: Criação de gráficos de barras para representar movimentações e distâncias acumuladas e uso de Folium para mapear as localizações dos talhões.</li>
  <li><strong>Exportação de Resultados</strong>: Os resultados são exportados para um novo arquivo Excel, com imagens dos gráficos integradas.</li>
  <li><strong>Mapa Interativo</strong>: Geração de um mapa interativo com marcadores para cada talhão processado.</li>
</ol>

<h2>Execução do Script</h2>
<p>Para executar este script, assegure-se de que todas as bibliotecas necessárias estão instaladas e que os arquivos Excel de entrada estão no diretório especificado pelo script. Execute o script através de um ambiente Python que suporte estas bibliotecas, como Anaconda ou um ambiente virtual Python padrão.</p>

<h2>Contribuições</h2>
<p>Contribuições para este projeto são bem-vindas. Por favor, envie sugestões de melhorias ou correções através de pull requests ou issues no GitHub.</p>

<h2>Licença</h2>
<p>Este projeto é distribuído sob a licença MIT.</p>
