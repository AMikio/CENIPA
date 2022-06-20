# Desafio Técnico A3DATA
========================

Este repositório contém o desfio técnico desenlvolvido para a vaga de Cientista de Dados da A3DATA, contendo um Jupyter Notebook onde é feito o desenvolvimento de uma análise exploratória do conjunto de dados de Ocorrências Aeronáuticas na Aviação Civil Brasileira da CENIPA (Centro de Investigação e Prevenção de Acidentes Aeronáuticos).

Foi feita uma análise de diferentes aspectos dos dados, sem um direcionamento específico buscando encontrar algumas possíveis relações entre as diferentes features disponíveis.

## Dependências

Junto ao Jupyter notebook, é fornecido o arquivo dependencias.yml que contém o ambiente de desenvolvimento utilizado, conforme configurado pelo gerenciador de pacotes Conda.

Para configurar o abiente, basta utilizar:
```
conda env create --name <nome_do_ambiente> --file dependencias.yml
```
e 
```
conda activate <nome_do_ambiente>
```

## Jupyter Notebook

Para visualizar o Jupyter Notebook, recomenda-se a utilização do Jupyter Lab. Para utilizá-lo, basta acessar o diretório principal deste repositório e executar, com o ambiente apropriado ativado, o comando:
```
jupyter lab
```
Uma página deve abrir no navegador padrão do sistema. Basta então acessar o _notebook_ `CENIPA.ipynb` através do explorador de arquivos na página.

O _notebook_ contém as análises feitas, com comentários em Markdown, assim como todo o código utilizado para desenvolver a análise.
