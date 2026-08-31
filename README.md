# Titanic EDA: Fatores Associados à Sobrevivência

Análise exploratória do dataset Titanic (Seaborn) investigando quais fatores 
socioeconômicos e demográficos influenciaram a sobrevivência dos passageiros.

## Principais achados

- **Sexo**: mulheres tiveram taxa de sobrevivência 3,9x maior que homens (74,2% vs 18,9%)
- **Classe**: 75,8% dos passageiros da 3ª classe morreram, contra 37% na 1ª classe
- **Tarifa**: sobreviventes pagaram, em média, 2,2x mais que falecidos (£32,99 vs £15,03)
- **Família a bordo**: número de irmãos/cônjuges explica 51% da variação na taxa de 
  mortalidade (R² = 0,51, r de Pearson = 0,71)

## Metodologia

- Limpeza de dados: remoção de colunas redundantes, tratamento seletivo de valores ausentes
- Estatística descritiva: média, mediana, quartis, desvio padrão, coeficiente de variação
- Estatística inferencial: correlação de Pearson, coeficiente de determinação (R²)
- Visualização: boxplots, regplot (Matplotlib/Seaborn)

## Ferramentas

Python 3 · Pandas · NumPy · Matplotlib · Seaborn · Google Colab

## Estrutura

- `notebooks/` — análise completa com código
- `docs/` — relatório formal com discussão detalhada

## Autores

Caio de Moraes — [LinkedIn](https://linkedin.com/in/moraes-caio)
