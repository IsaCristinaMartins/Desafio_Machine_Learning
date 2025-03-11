## Análise dos preços de mais de 50.000 diamantes de lapidação redonda

<p align="center">
  <img src="https://esoft.inf.br/images/desenvolvimento-web-aplicativo.png" alt=" " />
</p>

Este projeto tem como objetivo analisar o comportamento dos clientes de uma empresa de e-commerce de moda com sede em Nova York, que vende roupas online e oferece consultoria de estilo presencial. A análise exploratória dos dados investigará o engajamento dos usuários nas plataformas disponíveis – aplicativo móvel e site – considerando métricas como frequência de acesso, taxa de conversão, tempo médio de navegação e preferências de compra. Além disso, será realizada uma comparação de desempenho entre os dois canais, buscando identificar qual proporciona maior retorno para a empresa e onde deve ser focado o investimento para otimizar a experiência do cliente.

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


