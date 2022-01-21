# Universidade Federal de Minas Gerais
# Projeto final: Predizendo a área do conhecimento de teses e dissertações dos programas de pós-graduação do Brasil - 2021/1
**Resumo**: objetivo é criar um modelo Sequence-to-Sequence usando uma rede LSTM, o qual que preveja a grande área de concentração de teses e dissertações por meio do resumo informado pelo autor. O corpus está disponível em https://dadosabertos.capes.gov.br/dataset/2018-catalogo-de-teses-e-dissertacoes-da-capes. 

**Sobre o Dataset**: "Os dados contêm informações sobre as Teses e Dissertações da Pós-Graduação de 2017 a 2019 consolidados a partir do COLETA CAPES, os nomes dos autores, a data de defesa, a localização da IES a qual o autor está vinculado, a área de conhecimento da tese ou dissertação. No ano de 2017 temos 83.281 registros com 83.262 autores distintos dos 3.954 Programas de Pós-Graduação de 415 IES. No ano de 2018 temos 88.120 registros com 88.093 autores distintos dos 4.151 Programas de Pós-Graduação de 434 IES. No ano de 2019 temos 93.692 registros com 93.656 autores distintos dos 4.250 Programas de Pós-Graduação de 451 IES." [SIC]

**Baixar do GitHub**: https://github.com/EwertonDCSilv/ml_project

**Executar no colab**: https://drive.google.com/drive/folders/1ICIJ_xPF-vBWPcNce7o4J3PZdaWzjTPM?usp=sharing


**Pastas**:
```
.
+-- data
|   +-- data.zip // Conjunto de teste
|   +-- data_full.zip // Conjunto completo de dados
+-- model // Pasta para exportar modelo 
|   +-- saved_model.pb
|   +-- _variables
|   |   +-- variables.data-00000-of-00001
|   |   +-- variables.index
+-- README.md
+-- tpFinal.ipynb // Codigo
```
