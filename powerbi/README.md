# PowerBI - Dashboard

Abaixo um exemplo de desenvolvimento de um dashboard em PowerBI com recursos básicos e intermediários de análise e manuseio.

<video controls>
  <source src="https://raw.githubusercontent.com/joseadelmarjr/data_engineering_tools/add-power-bi-project/powerbi/video/Dashboard_demo.mp4" type="video/mp4">
</video>

## - Como fazer

A construção do dashboard acima foi feita durante palestra que se tornaram em 3 vídeos, sendo eles:


### - 1 - Fundamentos e primeiros passos

[![Watch the video](https://img.youtube.com/vi/Y8cfSVygQFY/hqdefault.jpg)](https://www.youtube.com/embed/Y8cfSVygQFY)


No primeiro vídeo temos:

- [x]  Power BI e seus concorrentes
- [x]  Módulos para o funcionamento da ferramenta
- [x]  Principais recursos
- [x]  Relacionamento
- [x]  Filtros (todas as páginas, página e visual)
- [x]  Importação de bases (csv, excel e PostgreSQL)
- [x]  Visuais básicos
- [x]  Drill-down/up


### - 2 - Drill-through, medidas e RLS
[![Watch the video](https://img.youtube.com/vi/KO01TEnKbLA/hqdefault.jpg)](https://www.youtube.com/embed/KO01TEnKbLA)

No segundo temos:
- [x]  Drill-through
- [x]  Adicionar imagem dinâmica (Sample Image)
- [x]  Relatório cruzado
- [x]  Dax / Criação de tabelas
- [x]  Dax / Criação de medidas
- [x]  Dax / AllSelected
- [x]  Visual de mapa
- [x]  Colorir mapa com gradiente
- [x]  Colorir mapa com subgrupo
- [x]  RLS (Row level security)


### - 3 - Gráficos avançados, publicação e exportações
[![Watch the video](https://img.youtube.com/vi/AWvHQ2Hj65Y/hqdefault.jpg)](https://www.youtube.com/embed/AWvHQ2Hj65Y)


No terceiro temos:
- [x]  Tacômetro
- [x]  Gráfico com 2 eixos
- [x]  Gráfico de dispersão
- [x]  Filtro na tela e chiclet slicer
- [x]  Configuração do Gateway
- [x]  Workspaces
- [x]  Aplicativos
- [x]  Exportações


## - Para replicar

Os dados utilizados nesse exemplo são os mesmos disponibilizados nos exemplos de SQL e PySpark e podem ser encontrados [nesse link](../docker/jupyter_spark/workspace/bases_teste/).
O Postgres mencionado nos vídeos não ficará ativo, porém seus dados estão contidos no arquivo [vendas.csv](../docker/jupyter_spark/workspace/bases_teste/vendas.csv).