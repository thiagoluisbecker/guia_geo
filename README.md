# Guia Geo – Introdução a Dados Geoespaciais

Este repositório contém um conjunto de notebooks voltados para quem deseja aprender a manipular, processar e visualizar informações geoespaciais com Python.

## Como rodar no Binder

1. Clique no badge abaixo ou acesse `[https://mybinder.org/v2/gh/<usuario>/<repositorio>/HEAD](https://mybinder.org/v2/gh/thiagoluisbecker/guia_geo/HEAD)`.
2. Aguarde a construção da imagem. Esse processo pode levar alguns minutos na primeira execução.
3. Quando o Jupyter Notebook abrir, navegue até o notebook desejado.
4. Execute as células normalmente para reproduzir os exemplos.

## Como rodar localmente

1. Crie um ambiente Python (virtualenv ou conda).
2. Instale as dependências listadas em `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```
3. Inicie o Jupyter Notebook ou JupyterLab:

   ```bash
   jupyter notebook
   ```
4. Abra os arquivos na ordem indicada e execute cada célula.

## Notebooks
1. **Tipos de Dados Geoespaciais – `2geo_data_types.ipynb`**
   Introdução aos formatos vetoriais e raster, exemplos com `geopandas`, `shapely` e `rasterio`.
2. **Processamento de Dados Geoespaciais – `3Processing.ipynb`**
   Demonstra técnicas de geocodificação, projeções cartográficas e interseções.
3. **Visualizações – `4Vis_v.ipynb`**
   Apresenta diferentes abordagens para criar mapas e gráficos usando `folium` e `matplotlib`.

Os notebooks utilizam dados disponíveis em `datasets/`, que incluem shapefiles, GeoJSON e rasters de exemplo.

## Estrutura

```
datasets/
2geo_data_types.ipynb     # Introdução a dados geoespaciais
3Processing.ipynb         # Processamento e pré-processamento
4Vis_v.ipynb              # Visualizações geoespaciais
```
