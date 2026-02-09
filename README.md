# ETL com Google Cloud Storage e BigQuery

Notebook de estudo demonstrando um fluxo completo de **Extract, Transform, Load (ETL)** integrado com Google Cloud Platform.

## 🚀 Início Rápido

1. Abra no [Google Colab](https://colab.research.google.com/github/seu-usuario/seu-repo/blob/main/etl-analise-atrasos-logistica.ipynb)
2. Configure seus **Colab Secrets** (ícone 🔑):
   - `GCP_PROJECT_ID`
   - `GCS_BUCKET_NAME`
3. Execute o notebook

## Datasets

- **GCS Bucket**: Arquivo JSON com dados de feriados brasileiros
- **BigQuery**: Tabela `olist_dataset.orders` com dados de pedidos (origem: [Dataset Olist no Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce))
- **Resultado**: Nova tabela `pedido_atrasos` com análise de atrasos nas entregas
