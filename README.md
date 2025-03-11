## Desafios de Machine Learning: Análises e Modelos

<p align="center">
  <img src="https://assets.dio.me/qc5KPp_XDOP596YsVKMAe8vmSDkponJewj0TdKp-XUk/f:webp/q:80/L2FydGljbGVzL2NvdmVyL2Y3NmY4YWU3LWY1NzYtNDA4ZC1hZjNiLThlNDM4YmQ4OGY1ZS5wbmc" alt=" " />
</p>

Este repositório contém uma série de desafios de Machine Learning, com o objetivo de aplicar técnicas e algoritmos para resolver problemas reais de análise de dados. A pasta reúne projetos que envolvem análise exploratória de dados, construção de modelos preditivos e avaliação de desempenho, utilizando abordagens como regressão, classificação e clustering. Cada desafio inclui uma análise detalhada das variáveis do problema, seleção de características relevantes e comparação de diferentes algoritmos, com o intuito de identificar as melhores soluções para cada cenário. O foco é aprimorar as habilidades em machine learning, entender as nuances dos dados e explorar métodos para otimizar os resultados, buscando sempre as melhores práticas para análise e implementação de modelos.

## Justificativa

Este projeto se justifica pela necessidade de identificar qual plataforma – aplicativo ou site – gera maior engajamento e conversão de vendas. Com base na análise do comportamento dos clientes, a empresa poderá direcionar seus investimentos de forma estratégica, otimizando a experiência do usuário e aumentando a lucratividade.

Neste projeto, vamos abordar as seguintes questões:

<div align=" ">

- 2.1: Análise da relação entre preço, corte, cor e clareza do diamante.
- 2.2: A influência entre peso (carat), preço e corte do diamante.
- 2.3: A influência das proporções (depth e table) no preço.


</div>

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

Espera-se que a análise revele padrões de uso distintos entre o aplicativo móvel e o site, como diferenças na taxa de conversão, no tempo médio de navegação e na frequência de compras. Além disso, os dados podem indicar qual canal oferece maior retorno para a empresa, auxiliando na decisão sobre onde concentrar investimentos. Também é possível identificar oportunidades de melhoria na experiência do usuário, como ajustes na interface, personalização de recomendações e estratégias para aumentar a fidelização dos clientes.

## Dicionário de dados

| Nome da Coluna          | Nome em Português      | Tipo de Dado    |                    Descrição                            | Valores Possíveis                    |
|-------------------------|------------------------|-----------------|---------------------------------------------------------|--------------------------------------|
| Email                   | E-mail                 | string (qualit) | Endereço de e-mail do cliente.                          | Texto                                |
| Address                 | Endereço               | string (qualit) | Endereço residencial do cliente.                        | Texto                                |
| Avatar                  | Avatar                 | string (qualit) | Imagem de perfil do cliente.                            | URL ou caminho de imagem             |
| Avg. Session Length     | Duração Média   Sessão | float (quanti)  | Duração média  sessões  de  navegação do cliente (min). | 0.0 – 60.0+ min                      |
| Time on App             | Tempo no Aplicativo    | float (quanti)  | Tempo total gasto no aplicativo móvel (min).            | 0.0 – 60.0+ min                      |
| Time on Website         | Tempo no Site          | float (quanti)  | Tempo total gasto no site (min).                        | 0.0 – 60.0+ min                      |
| Length of Membership    | Tempo de Associação    | float (quanti)  | Tempo de associação do cliente com a empresa (anos).    | 0.0 – 10.0+ anos                     |
| Yearly Amount Spent     | Valor Gasto Anualmente | float (quanti)  | Quantia gasta anualmente pelo cliente (USD).            | $0.00 – $10,000.00+                  |


