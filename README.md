

# Análise de Dados com Pandas 📊

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

<p align="center">
  <img src="https://media.giphy.com/media/HWgB6Bf9sK8qK/giphy.gif" alt="Banner" width="100%" />
</p>
Projeto de **análise de dados com Python e Pandas**, focado em tratamento de base, cálculo de métricas, criação de relatórios e automação de envio por e-mail.

## Visão geral

Este notebook pega uma base de vendas, organiza os dados, calcula indicadores importantes e monta um e-mail em HTML com o resumo para o responsável acompanhar os resultados de forma rápida.

## Funcionalidades

- Leitura e tratamento da base de vendas.
- Criação de colunas calculadas como faturamento e ticket médio.
- Agrupamento por loja e análise de desempenho.
- Geração de tabelas organizadas em HTML.
- Envio automático de relatório por e-mail com `smtplib`.
- Uso de `Plotly` para visualização de dados.

## Tecnologias utilizadas

- Python
- Pandas
- Plotly
- OpenPyXL
- Smtplib
- MIMEText e MIMEMultipart
- Jupyter Notebook

## Bibliotecas instaladas

As principais bibliotecas presentes no ambiente incluem:

- scipy
- statsmodels
- urllib3
- tornado
- traitlets
- typing_extensions
- tzdata
- widgetsnbextension
- webcolors
- websocket-client
- soupsieve
- stack-data
- terminado
- tinycss2
- rpds-py
- Send2Trash
- setuptools
- six
- wcwidth
- webencodings
- uri-template

## Como funciona

1. Importa as bibliotecas.
2. Lê a base de vendas.
3. Calcula faturamento e ticket médio.
4. Agrupa os dados por loja.
5. Formata o resumo em HTML.
6. Envia o e-mail com o relatório.

## Estrutura do projeto

```text
Projeto.ipynb
README.md
vendas.xlsx
output/
```

## Exemplo de resultado

O relatório final traz uma tabela com:

- Loja.
- Faturamento total.
- Quantidade vendida.
- Ticket médio.

## Objetivo

O objetivo do projeto é transformar dados brutos em informação útil para análise de desempenho comercial e apoio à tomada de decisão.

## Próximos passos

- Adicionar gráficos mais completos.
- Inserir filtros por produto e período.
- Salvar relatórios em PDF ou Excel.
- Criar dashboard interativo.

## Autor

Matheus dos Santos

