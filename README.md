
# MVP - Engenharia de Dados com dados de acidentes da PRF

## Contexto de Negócio e Perguntas

Os acidentes de trânsito em rodovias federais representam um problema relevante de segurança viária, podendo resultar em vítimas feridas, vítimas fatais e impactos sociais e econômicos.

Neste projeto será desenvolvido um pipeline de Engenharia de Dados utilizando dados abertos da Polícia Rodoviária Federal (PRF), com registros de acidentes ocorridos em rodovias federais brasileiras entre 2021 e 2025.

O objetivo é estruturar, tratar, modelar e analisar os dados de forma a identificar padrões temporais, geográficos e circunstanciais associados à ocorrência e à gravidade dos acidentes.

### Perguntas de negócio

1. Como o número de acidentes, feridos e mortos evoluiu entre 2021 e 2025?
2. Quais estados, municípios e rodovias concentram mais acidentes e vítimas fatais?
3. Como a gravidade dos acidentes varia por dia da semana, horário e fase do dia?
4. Como condições meteorológicas, tipo de pista e traçado da via estão associados à gravidade dos acidentes?
5. Quais causas e tipos de acidente apresentam maior proporção de ocorrências com vítimas fatais?

## Fonte dos Dados

Os dados utilizados neste projeto são provenientes do Portal de Dados Abertos da Polícia Rodoviária Federal (PRF), mais especificamente da base BAT - Boletim de Acidente de Trânsito.

Foram utilizados os arquivos anuais de acidentes agrupados por ocorrência referentes aos anos de 2021, 2022, 2023, 2024 e 2025.

A escolha da base agrupada por ocorrência foi feita porque sua granularidade é adequada ao objetivo deste projeto: cada registro representa uma ocorrência de acidente, permitindo realizar análises sobre quantidade de acidentes, localização, características da via, condições meteorológicas, gravidade, mortos e feridos sem duplicar ocorrências em função do número de pessoas envolvidas.

O período de 2021 a 2025 foi selecionado por representar cinco anos completos e consecutivos, permitindo comparações temporais sem incluir o ano corrente, que ainda possui dados parciais.

### Formato dos dados

Os dados são disponibilizados pela PRF em arquivos CSV compactados em formato ZIP.

Neste projeto serão utilizados cinco arquivos, um para cada ano analisado:

- datatran2021.csv
- datatran2022.csv
- datatran2023.csv
- datatran2024.csv
- datatran2025.csv

### Licença e uso dos dados

Os dados fazem parte da política de Dados Abertos da Polícia Rodoviária Federal.

Segundo a PRF, dados abertos são disponibilizados em formato legível por máquina e sem restrições de licenças, patentes ou mecanismos de controle, podendo ser livremente utilizados, reutilizados e redistribuídos.

### Dicionário de dados

A PRF disponibiliza também um dicionário oficial das variáveis da base de acidentes, contendo a descrição dos campos utilizados nos registros agrupados por ocorrência.

### Referências

- [Portal de Dados Abertos da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)
- [Dicionário de dados de acidentes da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dicionario-acidentes)

## Carga dos Dados

Esta seção será preenchida após a ingestão dos arquivos no Databricks.

## Modelagem e Catálogo de Dados

Esta seção será preenchida após a definição da modelagem.

## Pipeline de Dados

Esta seção será preenchida durante a construção do pipeline ETL.

## Qualidade de Dados

Esta seção será preenchida após a análise de qualidade dos dados.

## Análise de Dados

Esta seção será preenchida com as respostas às perguntas de negócio.

## Autoavaliação

Esta seção será preenchida ao final do projeto.
