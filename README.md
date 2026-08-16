# Coleta de Dados de Múltiplas Fontes (Web Scraping, APIs, Google Sheets)

## Objetivo
Praticar diferentes formas de obter dados para análise além de arquivos CSV estáticos: tabelas HTML, APIs REST e planilhas do Google Sheets.

## O que foi feito
- Leitura direta de **tabelas HTML** de uma página web (dados de qualidade do ar — GIOS) usando `pandas.read_html`
- Consumo de dados via **API REST** pública (JSON) com `requests` / `pandas.read_json`
- Normalização de JSON aninhado com `pandas.json_normalize`
- Integração com **Google Sheets** como fonte de dados
- Agregações com `groupby` sobre os dados coletados

## Tecnologias
`Python` `pandas` `requests`

## Como executar
```bash
pip install pandas requests
jupyter notebook "pobieranie danych z rożnych źródeł, praca z bazą i groupby.ipynb"
```
