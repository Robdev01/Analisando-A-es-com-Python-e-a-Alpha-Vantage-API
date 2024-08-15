# Análise de Ações com Python

Este projeto utiliza a API da Alpha Vantage para obter dados históricos de preços de ações mensais e realizar uma avaliação simples para determinar se uma ação deve ser comprada com base em critérios específicos.

## Funcionalidades

- **Obter Dados Históricos**: Acesse dados de preços mensais de ações usando a Alpha Vantage API.
- **Avaliação de Ações**: Avalie ações com base na taxa de crescimento e preço médio dos últimos 10 anos.
- **Visualização de Dados**: Gere um gráfico dos preços de fechamento das ações para uma análise visual.

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Requests

## Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina. Você pode baixar o Python [aqui](https://www.python.org/downloads/).

Instale as bibliotecas necessárias utilizando o `pip`:


## Configuração

- Substitua a variável API_KEY no código pelo seu próprio API Key da Alpha Vantage. Você pode obter uma chave gratuita aqui.

- Chame a função obter_dados_historicos(symbol) passando o símbolo da ação que você deseja analisar, e em seguida, utilize a função avaliar_acao(symbol, data) para obter a recomendação e o gráfico.

```bash
pip install pandas matplotlib requests
symbol = 'AAPL'  # Exemplo: Apple Inc.
dados = obter_dados_historicos(symbol)
recomendacao, plot_url = avaliar_acao(symbol, dados)

print(recomendacao)


Sinta-se à vontade para ajustar as seções conforme necessário e adicionar mais detalhes que você achar relevantes!

