# Projeto de Análise de Dados Imobiliários de casas de leilão PR - Banco Caixa Economica Federal

Este projeto é destinado à análise de dados imobiliários fornecidos pelo Banco Caixa. O código é reutilizável e pode ser adaptado para análises futuras.

## Utilização no Google Colab

1. Certifique-se de ter acesso aos dados fornecidos pelo Banco Caixa.
2. Faça o upload do conjunto de dados para a pasta `/content/data/` no ambiente do Colab.

```python
# Instale as bibliotecas necessárias
!pip install pandas matplotlib tabulate

# Clone o repositório
!git clone https://github.com/seu_usuario/seu_repositorio.git

# Acesse o diretório do projeto
%cd seu_repositorio

# Execute o script de análise
!python analise_imoveis.p
