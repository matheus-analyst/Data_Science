# Análise de Dados com Pandas 📊

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Projeto de análise de dados com Python e Pandas, focado em tratamento de base, cálculo de métricas, criação de relatórios e automação de envio por e-mail.

## Visão geral

Este projeto utiliza uma base de vendas para organizar os dados, calcular indicadores importantes e gerar um resumo em HTML para acompanhamento dos resultados de forma rápida e prática.

## Funcionalidades

- Leitura e tratamento da base de vendas.
- Criação de colunas calculadas como faturamento.
- Agrupamento por loja e análise de desempenho.
- Geração de tabelas organizadas em HTML.
- Envio automático de relatório por e-mail com `smtplib`.
- Criação de visualizações com `Plotly`.

## Tecnologias utilizadas

- Python
- Pandas
- Plotly
- OpenPyXL
- `smtplib`
- `MIMEText` e `MIMEMultipart`
- Jupyter Notebook

## Bibliotecas instaladas

Algumas das bibliotecas presentes no ambiente incluem:

- scipy
- statsmodels
- urllib3
- tornado
- traitlets
- typing_extensions
- tzdata
- widgetsnbextension
- websocket-client
- soupsieve
- stack-data
- terminado
- tinycss2
- Send2Trash
- setuptools
- six
- wcwidth

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
assets/banner.gif