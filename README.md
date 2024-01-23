# WebScraping_BeautifulSoup

 # Projeto de Extração de Dados de Criptomoedas

Neste projeto, utilizamos a biblioteca BeautifulSoup para realizar a extração de informações sobre a cotação atual de diversas criptomoedas no site [Investing.com - Criptomoedas](https://br.investing.com/crypto/). A seguir, detalhamos as etapas do projeto:

## Etapas do Projeto

1. **Acesso ao Site e Extração de Dados:**
   - Utilizamos o BeautifulSoup para acessar o conteúdo do [site de Criptomoedas](https://br.investing.com/crypto/) e navegamos até a tabela que continha as informações desejadas.

2. **Loop de Coleta de Dados:**
   - Implementamos um loop para percorrer as linhas da tabela, extraindo os valores referentes às criptomoedas.

3. **Criação do Arquivo CSV:**
   - Com os dados coletados, criamos um arquivo CSV denominado "criptomoedas.csv".

4. **Importação e Apresentação dos Resultados com Pandas:**
   - Utilizamos a biblioteca Pandas para importar o arquivo CSV e apresentar os resultados de forma tabular.

## Resultados Finais

O resultado final foi um DataFrame que exibiu as criptomoedas e suas cotações atuais:

```plaintext
 Moeda     Valor
0    BTC  39.000,7
1    ETH  2.234,68
2   USDT    0,9999
3    BNB     297,2
4    SOL     80,12
5    XRP    0,5083
6   USDC    1,0008
7  stETH  2.224,49
8    ADA    0,4598
9   DOGE  0,077209
