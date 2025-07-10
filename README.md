# Projeto de Aprendizado Descritivo - 2025/1

Este repositório reúne os arquivos e códigos desenvolvidos para o projeto prático da disciplina **Aprendizado Descritivo** (1º semestre de 2025), ministrada pelo professor Renato Vimieiro.

## Objetivo

Explorar, de forma prática, os conceitos de aprendizado descritivo apresentados em aula. O projeto engloba todo o fluxo de análise de dados reais: desde a obtenção e limpeza dos dados até a aplicação de técnicas descritivas.

## Informações Principais do Projeto

### Dados

- **Dataset utilizado:** [Credit Card Dataset for Clustering][Dataset_url]
- **Fonte:** Kaggle
- **Descrição:** Dados anonimizados de transações de cartões de crédito, que resume o comportamento de uso de cerca de 9.000 titulares ativos de cartão de crédito num período de 6 meses.

### Técnicas de Aprendizado Descritivo

- **Técnica aplicada:** Busca de subgrupos com _Beam Search_.
- **Bibliotecas e ferramentas utilizadas:**
  - `kagglehub`: para carregar datasets diretamente do Kaggle.
  - `kagglehub.KaggleDatasetAdapter`: para carregar datasets diretamente como DataFrame do pandas.
  - `numpy`: operações matemáticas e manipulação de arrays.
  - `pandas`: manipulação e análise de dados tabulares.
  - `seaborn`: visualização estatística dos dados.
  - `matplotlib.pyplot`: criação de gráficos e visualizações personalizadas.
  - `pysubgroup`: biblioteca especializada para descoberta de subgrupos descritivos.
  - `math`: funções matemáticas auxiliares, como `ceil`.

## Integrantes do Grupo

- Amanda Mendes Pinho
- Gabriel Tonioni Duarte
- João Vítor Fernandes Dias
- Larissa Duarte Santana

[Dataset_url]: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata/data
