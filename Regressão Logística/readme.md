## Análise e Predição de Cliques em Anúncios: Construindo um Modelo Inteligente para Publicidade Online

<p align="center">
  <img src="https://esoft.inf.br/images/desenvolvimento-web-aplicativo.png" alt=" " />
</p>

Este projeto tem como objetivo analisar um conjunto de dados fictício de publicidade online e desenvolver um modelo preditivo utilizando regressão logística para identificar se um usuário da internet clicará ou não em um anúncio. Serão aplicadas técnicas de análise exploratória de dados, visualização de padrões e pré-processamento para otimizar o desempenho do modelo. A avaliação do modelo será feita por meio de métricas adequadas, garantindo sua precisão e eficiência. Por fim, os resultados serão analisados e discutidos, destacando suas possíveis aplicações na publicidade online.

## Justificativa

Este projeto se justifica pela necessidade de identificar qual plataforma – aplicativo ou site – gera maior engajamento e conversão de vendas. Com base na análise do comportamento dos clientes, a empresa poderá direcionar seus investimentos de forma estratégica, otimizando a experiência do usuário e aumentando a lucratividade.


## Desenvolvedores

- Isabel Cristina Martins [https://github.com/IsaCristinaMartins]

## Metodologia

O projeto será desenvolvido utilizando a metodologia CRISP-DM, seguindo os seguintes passos:

<div align = " ">

- Entendimento de negócio
- Entendimento de dados
- Preparação dos dados
- Modelagem

</div>

O projeto também é dividido em duas entregas, a saber:

<div align = " ">

- Análise Exploratória de Dados (EDA): entendimento das variáveis que influenciam o MPG e identificação de padrões nos dados através de hipóteses, visualizações e insights.
- Análise comparativa de modelos: construção de modelos de aprendizado de máquina para previsão de consumo, com métricas de desempenho para avaliação da performance.

</div>

## Resultados Esperados

Os resultados esperados deste projeto incluem a criação de um modelo de regressão logística eficaz para prever a probabilidade de um usuário clicar ou não em um anúncio com base em suas características. Espera-se que o modelo seja capaz de identificar padrões e variáveis significativas que influenciem a decisão de clicar, proporcionando previsões precisas. Além disso, espera-se que a avaliação do modelo mostre um bom desempenho, com métricas de precisão, recall e F1-score indicando que o modelo está apto a realizar previsões relevantes. Os resultados também poderão fornecer insights valiosos sobre os fatores que impactam o comportamento dos usuários em relação à publicidade online.

## Dicionário de dados

| Nome da Coluna             | Nome em Português        | Tipo de Dado    |            Descrição                               | Valores Possíveis                              |
|----------------------------|--------------------------|-----------------|----------------------------------------------------|------------------------------------------------|
| Daily Time Spent on Site   | Tempo Diário no Site     | float (quanti)  | Tempo médio que o consumidor passa no site (min)   | 0.0 – 60.0+ minutos                            |
| Age                        | Idade                    | int (quanti)    | Idade do consumidor (anos).                        | Valores inteiros (anos)                        |
| Area Income                | Renda da Área            | float (quanti)  | Renda média da área geográfica do consumidor (USD) | $0.00 – $100,000.00+                           |
| Daily Internet Usage       | Uso Diário de Internet   | float (quanti)  | Tempo médio/dia consumidor demora na rede(min)     | 0.0 – 24.0+ horas                              |
| Ad Topic Line              | Título do Anúncio        | string (qualit) | Título do anúncio exibido ao consumidor.           | Texto                                          |
| City                       | Cidade                   | string (qualit) | Cidade do consumidor.                              | Texto                                          |
| Male                       | Sexo Masculino           | int (quanti)    | Indica se o consumidor é masculino (1) ou não (0). | 0 ou 1                                         |
| Country                    | País                     | string (qualit) | País do consumidor.                                | Texto                                          |
| Timestamp                  | Timestamp                | datetime (qualit)| Hora do clique ou fechou a janela.                | Data e hora                                    |
| Clicked on Ad              | Clicou no Anúncio        | int (quanti)    | Indica se o consumidor clicou (1) ou não clicou (0)| 0 ou 1                                         |
