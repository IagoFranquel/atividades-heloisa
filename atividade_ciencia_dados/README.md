# Revisão — Limpeza e Preparação de Dados

## Estrutura

- `01_valores_ausentes.ipynb`
- `02_duplicatas.ipynb`
- `03_padronizacao_escalonamento.ipynb`
- `04_outliers.ipynb`
- `05_pipeline_integrado.ipynb`
- `dados/` para os arquivos baixados

## Dependências

Crie um ambiente virtual e instale:

```bash
pip install -r requirements.txt
```

Os arquivos do Kaggle devem ser baixados manualmente e colocados em `dados/` com os nomes indicados no enunciado. Para o exercício 3, coloque `adult.data` em `dados/`. O exercício 4 baixa o conjunto `diamonds` pelo Seaborn.

## Execução

Abra os notebooks com Jupyter ou VS Code e execute as células na ordem. Os notebooks preservam os DataFrames originais e mostram os efeitos dos tratamentos.

## Observação

As respostas reflexivas foram redigidas para acompanhar os resultados esperados do enunciado. Depois de executar os notebooks, confira os números exibidos e ajuste qualquer frase que dependa de uma particularidade dos arquivos baixados.
