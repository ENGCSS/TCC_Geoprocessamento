# TCC Geoprocessamento
## Mapa Interativo

Este repositório apresenta um mapa interativo desenvolvido como parte do Trabalho de Conclusão de Curso (TCC), com foco em **Geoprocessamento aplicado à Saúde Pública na Bahia**. O objetivo principal é a **visualização geoespacial de unidades de atenção oncológica (UNACONs e CACONs)**, com ênfase em serviços de alta complexidade.

---

## 🌍 Mapa Interativo

O resultado é um mapa online que exibe:
- Localização dos hospitais habilitados em alta complexidade oncológica na Bahia
- Informações descritivas e imagens ilustrativas de cada unidade
- Classificação visual por região, com base em critérios definidos no estudo

📌 **Acesse o mapa interativo aqui:**

👉 [Visualizar Mapa Interativo](https://engcss.github.io/TCC_Geoprocessamento/)

---

## 🗂️ Fonte dos Dados

Os dados utilizados foram obtidos das seguintes fontes:

- **Malha Municipal Digital (MMD), Fonte: IBGE, 2022**: shapefile contendo os limites municipais atualizados, utilizados para contextualização espacial.
- **Cadastro Nacional de Estabelecimentos de Saúde (CNES)**: informações sobre unidades de saúde oncológica habilitadas (UNACONs e CACONs), extraídas da plataforma **DATASUS**.
- **Imagens ilustrativas das unidades de saúde**: incorporadas diretamente no arquivo HTML final por meio de codificação **base64**, garantindo portabilidade e visualização offline.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Folium** – geração de mapas interativos
- **Pandas** – manipulação tabular
- **GeoPandas** – análise espacial com shapefiles
- **Jupyter Notebook**
- **Leaflet.js** – via Folium para renderização interativa
- **GitHub Pages** – para publicação online do mapa

---

## 📁 Estrutura de Pastas

```text
TCC_Geoprocessamento/
├── DADOS/                  # Arquivos de entrada utilizados nas análises
├── Saidas/                 # Arquivos de saída (mantido para controle)
├── Mapa Interativo.ipynb   # Notebook responsável pela geração do mapa
├── MAPA.html               # Mapa interativo final (página inicial)
├── README.md               # Este arquivo de descrição
```

