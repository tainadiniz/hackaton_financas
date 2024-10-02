**UNIVERSIDADE FEDERAL DA PARAÍBA** \
**CENTRO DE CIÊNCIAS SOCIAIS APLICADAS**\
**CIÊNCIA DE DADOS PARA NEGÓCIOS** \
**ALUNOS: Nercino Neto e Tainá Diniz**

# **Hackathon Finanças**
## **1. Descrição**
- Neste projeto, visando a construção de uma carteira de investimentos, aplicamos o método de Markowitz para otimizar a alocação de ativos, priorizando a maximização do Índice de Sharpe, um indicador crucial que leva em conta o desempenho ajustado ao risco. Através desta simulação, buscamos criar uma carteira de investimentos na Bolsa Brasileira B3, iniciando com os portfólios de maior volume de acordo com o Índice Brasil 100 (IBrX 100 B3). No exemplo apresentado, distribuímos pesos por meio do modelo de otimização de Markowitz, conduzindo uma análise de cinco anos para avaliar o desempenho.
## **2. Importando Bibliotecas**

## **3. Obtendo Dados de Tickets B3**

- 3.1 Estabelecendo um período de cinco anos

- 3.2 Definindo Tickers de Ativos com Base no Índice Brasil 100

- 3.3 Obtendo infomações sobre os Tickets

## **4. Aplicando Método de Markowitz**

- 4.1 Criando DataFrame de Variação

- 4.2 Instanciando Class Portfolio

- 4.3 Definindo Métodos de Retornos Históricos

- 4.4 Calculando Método de Otimização

- 4.5 Configurações para Modelo Clássico de Markowitz

- 4.6 Criando a Carteira de Investimentos

## **5. Rebalanceamento de Carteira**

- 5.1 Selecionando Os Cinco Principais Tickers

- 5.2 Criando o DataFrame de Variação Com os Cinco Principais Tickers

- 5.3 Atualizando a Instância De Portfolio

- 5.4 Recalculando o Método de Otimização

- 5.5 Atualizando a Carteira de Investimentos

- 5.6 Calculando a Eficiência da Fronteira

## **6. Gráficos**

- 6.1 Composição Da Carteira de Investimento

- 6.2 Eficiência Da Fronteira

- 6.3 Medidas de Risco

## **7. Backtesting**

- 7.1 Normalizando Os Dados

- 7.2  Comprando As Ações

- 7.3 Colunas De Valores Diarios

- 7.4 ROI Da Carteira

- 7.5 Retorno Médio Diario

