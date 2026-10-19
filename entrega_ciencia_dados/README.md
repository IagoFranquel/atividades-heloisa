# Revisão — Limpeza e Preparação de Dados

Esta pasta contém os cinco notebooks da atividade, o arquivo de dependências e este guia. Todos os arquivos ficam no mesmo nível para facilitar o envio ao repositório.

## Arquivos de dados necessários

Coloque nesta mesma pasta os seguintes arquivos antes de executar os notebooks:

- `melb_data.csv`
- `KPMG_VI_New_raw_data_update_final.xlsx`
- `adult.data`
- pelo menos dois CSVs do dataset Dirty E-Commerce Data — SHEIN

O notebook de Diamonds carrega o conjunto diretamente com Seaborn. Os datasets do Kaggle precisam ser baixados manualmente pela página indicada no enunciado.

## Instalação

```bash
pip install -r requirements.txt
```

Abra os notebooks no Jupyter ou no VS Code e execute as células na ordem. Os notebooks preservam os DataFrames originais, mostram os diagnósticos, aplicam os tratamentos pedidos e incluem as respostas reflexivas.

Os resultados numéricos dependem dos arquivos baixados. Execute as células com os dados reais e confira os gráficos e as tabelas antes de enviar a atividade.
