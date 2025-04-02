# **Análise de Inundações - Google Earth Engine & GeoJSON**

Nome: Lucas Barbaroto Miotto            RA: 22.01388-0
Nome: Victor Hugo Reiter Gonzalez       RA: 22.01452-7

##  **Estrutura do Projeto**

-  `dados/` → Contém o arquivo GeoJSON com os dados de inundação
-  `notebooks/` → Contém os notebooks usados para análise
-  `README.md` → Este documento com as informações do projeto

## **Dataset**

- O dataset foi obtido pela ferramenta do Google Earth Engine, no formado GeoJson
- Link para o Google Earth Engine: https://developers.google.com/earth-engine/datasets/catalog/GLOBAL_FLOOD_DB_MODIS_EVENTS_V1?hl=pt-br

### **Como Rodar**

1. Instalar todas as bibliotecas:
   ```bash
   pip install geopandas pandas folium matplotlib
   ```
2. No notebook, no segundo bloco, alterar o caminho do dataseet:
    ```bash
   geojson_path = "/content/dataset_projetoGeo.geojson" # Trocar o caminho para essa váriavel
   # OBS: Esse caminho que está agora, é por conta que o projeto foi feito no google colab 
   ```
3. Execute o notebook:
    ```bash
   jupyter notebook notebooks/analise_inundacoes.ipynb
   ```