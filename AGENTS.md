# AGENTS.md

Este repositório apresenta um guia de dados geoespaciais para cientistas de dados, composto por três notebooks principais e um conjunto de dados de apoio.

## Estrutura
- `2geo_data_types.ipynb` – Introdução a formatos vetoriais e raster.
- `3Processing.ipynb` – Exemplos de processamento e pré-processamento geoespacial.
- `4Vis_v.ipynb` – Técnicas de visualização de dados geoespaciais.
- `datasets/` – Arquivos utilizados nos notebooks (shapefiles, GeoJSON, rasters etc).

## Instruções para contribuidores
1. Certifique-se de que cada notebook executa de ponta a ponta antes de submeter mudanças. Para validar:
   ```
   jupyter nbconvert --execute 2geo_data_types.ipynb
   jupyter nbconvert --execute 3Processing.ipynb
   jupyter nbconvert --execute 4Vis_v.ipynb
   ```
2. Novos arquivos de dados devem ficar em `datasets/` e ser citados no README quando relevante.
3. Evite inserir arquivos muito grandes (acima de ~50 MB) no histórico Git; utilize links externos quando necessário.
