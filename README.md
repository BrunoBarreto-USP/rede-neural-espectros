# Rede Neural para Classificação de Espectros Astronômicos

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)

## Descrição
Este repositório contém Jupyter notebooks que implementam um pipeline completo de classificação de espectros astronômicos (galáxias, estrelas e quasares) usando uma rede neural em Python com TensorFlow/Keras. O objetivo é demonstrar desde o pré-processamento dos dados brutos até a avaliação do modelo.

## Dados necessários
- `specObj-dr17.fits (6.7 Gb)` pelo link:
> https://www.sdss4.org/dr17/spectro/spectro_access/

## ATENÇÃO:
Modificar os diretórios nos arquivos .ipynb para os seus locais utilizados para o download dos dados

## Conteúdo do Repositório
- `rede_neural_espectros1.1.ipynb`: Código principal em Jupyter Notebook.  
- `programa01_gerador_de_amostras.ipynb`: Scripts para extrair dados do catálogo do SDSS.  
- `requirements.txt`: Dependências necessárias para reproduzir o ambiente.  
- `README.md`: Este arquivo de apresentação.

## Pré-requisitos
- Python 3.8 ou superior  
- Jupyter Notebook  

## Instalação
1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/rede-neural-espectros.git
   cd rede-neural-espectros
