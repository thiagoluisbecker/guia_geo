# Guia Geo – Introdução a Dados Geoespaciais

Este repositório contém um conjunto de notebooks voltados para cientistas de dados que desejam aprender a manipular, processar e visualizar informações geoespaciais com Python.

## Notebooks
1. **Tipos de Dados Geoespaciais – `2geo_data_types.ipynb`**
   Introdução aos formatos vetoriais e raster, exemplos com `geopandas`, `shapely` e `rasterio`.
2. **Processamento de Dados Geoespaciais – `3Processing.ipynb`**
   Demonstra técnicas de geocodificação, projeções cartográficas e interseções.
3. **Visualizações – `4Vis_v.ipynb`**
   Apresenta diferentes abordagens para criar mapas e gráficos usando `folium` e `matplotlib`.

Os notebooks utilizam dados disponíveis em `datasets/`, que incluem shapefiles, GeoJSON e rasters de exemplo.

## Instalação
Crie um ambiente Python e instale as dependências principais:

```bash
pip install geopandas shapely folium rasterio pandas matplotlib
```

## Como usar
Abra os notebooks na ordem indicada e execute cada célula para reproduzir os exemplos.

## Estrutura

```
datasets/                 # Dados de apoio
2geo_data_types.ipynb     # Introdução a formatos geoespaciais
3Processing.ipynb         # Processamento e pré-processamento
4Vis_v.ipynb              # Visualizações geoespaciais
```

Contribuições são bem-vindas! Abra uma issue ou envie um pull request para sugerir melhorias.
