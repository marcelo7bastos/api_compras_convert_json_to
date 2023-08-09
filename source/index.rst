.. api_compras_convert_json_to documentation master file, created by
   sphinx-quickstart on Wed Aug  9 17:37:32 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Aplicação Streamlit para Conversão de JSON
==========================================

.. contents::
   :local:
   :depth: 2

Esta aplicação foi criada usando Streamlit e permite a visualização e exportação de dados da `API Compras Governamentais <https://api-comprasv2.dth.nuvem.gov.br/swagger-ui/index.html#/>`_ do governo brasileiro para formatos Excel e CSV.

Bibliotecas Usadas
------------------

- json
- requests
- pandas
- streamlit

Funcionalidades
---------------

1. **Ler JSON**: Uma função que faz uma requisição GET para uma URL fornecida e retorna o conteúdo JSON.
2. **Visualizar DataFrame**: Após ler o JSON, os dados são convertidos em um DataFrame do pandas para visualização.
3. **Exportar para Excel e CSV**: Funções para exportar os dados visualizados para formatos Excel e CSV.

Layout Streamlit
----------------

O layout do Streamlit inclui um campo de entrada para a URL da API, um botão para visualizar uma prévia dos dados e botões para download dos dados em formatos Excel e CSV.

Como Usar
---------

1. Insira a URL da API no campo fornecido.
2. Clique no botão de visualização.
3. Se os dados forem carregados com sucesso, você verá uma prévia do DataFrame e terá a opção de baixar os dados em Excel ou CSV.
