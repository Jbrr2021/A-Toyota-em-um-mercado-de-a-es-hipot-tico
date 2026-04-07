# Análise Temporal da Toyota em um Mercado de Ações Hipotético

Este projeto apresenta uma análise exploratória e temporal de dados financeiros da Toyota em um mercado de ações hipotético, utilizando **Python**, **Pandas**, **Matplotlib** e **Google Colab**.

O objetivo é estudar o comportamento do ativo ao longo do tempo, observando preço, volume, retornos, volatilidade e indicadores técnicos como **RSI**, **MACD** e **médias móveis**.

---

## Objetivos do projeto

Neste estudo, foram analisados os seguintes pontos:

- estrutura e qualidade do dataset
- comportamento do preço de fechamento ao longo do tempo
- evolução do volume negociado
- distribuição dos retornos diários
- comparação entre volatilidade de 10 e 30 períodos
- análise do RSI
- análise do MACD e da linha de sinal
- médias móveis de 20 e 50 períodos
- correlação entre variáveis
- retorno acumulado
- identificação da maior alta e da maior queda diária

---

## Dataset

O conjunto de dados utilizado foi:

**Toyota in a Hypothetical Stock Market**

Variáveis presentes no dataset:

- `Date`
- `Close`
- `High`
- `Low`
- `Open`
- `Volume`
- `Return`
- `Volatility_10`
- `Volatility_30`
- `RSI`
- `MACD`
- `MACD_Signal`

---

## Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- KaggleHub
- Google Colab
- GitHub

---

## Etapas da análise

O projeto foi desenvolvido seguindo esta sequência:

1. carregamento do dataset no Colab  
2. leitura do arquivo CSV com Pandas  
3. inspeção inicial dos dados  
4. conversão da coluna de data  
5. ordenação cronológica da série  
6. análise gráfica do preço e do volume  
7. análise dos retornos  
8. estudo da volatilidade  
9. interpretação de indicadores técnicos  
10. construção de médias móveis  
11. análise de correlação  
12. cálculo do retorno acumulado  
13. identificação de eventos extremos da série  

---

## Principais insights

Durante a análise, foi possível observar que:

- o preço de fechamento apresentou tendência de alta no longo prazo
- o volume negociado mostrou picos relevantes em alguns períodos
- os retornos diários ficaram concentrados próximos de zero, mas com eventos extremos
- a volatilidade de 10 períodos reagiu mais rapidamente que a de 30 períodos
- o RSI oscilou frequentemente entre regiões de sobrecompra e sobrevenda
- o MACD e sua linha de sinal acompanharam as mudanças de tendência do ativo
- as médias móveis ajudaram a visualizar melhor a direção principal da série
- o retorno acumulado mostrou forte valorização no longo prazo

---

## Estrutura do projeto

```bash
.
├── README.md
├── toyota_mercado_hipotetico.ipynb
