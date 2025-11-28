Projeto desenvolvido durante o curso Estatística para Geoquímica Ambiental, na 1ª Semana Acadêmica da Pós-Graduação em Geociências.
O objetivo é aplicar técnicas estatísticas a 30 amostras ambientais para identificar diferenças entre:

Áreas: Controle × Impactada

Locais: Rio, Lago e Solo

Os parâmetros analisados incluem:

- pH
- Condutividade
- Matéria Orgânica (%)
- Metais Pesados (mg/kg)

Objetivo

1. Avaliar padrões geoquímicos, testar diferenças entre grupos e investigar relações entre variáveis, respondendo perguntas como:
2. Há diferença de pH entre áreas?
3. Locais (Rio/Lago/Solo) apresentam teores distintos de matéria orgânica?
4. Existem outliers relevantes?
5. Quais variáveis possuem comportamento normal?
6. Há correlação entre metais pesados e condutividade?

Estrutura do Conjunto de Dados

30 amostras distribuídas entre:

- 2 áreas: Controle e Impactada
- 3 tipos de local: Rio, Lago e Solo

Variáveis:

-pH
-Condutividade
-Matéria Orgânica (%)
-Metais Pesados (mg/kg)

Metodologia

1. Limpeza e organização

- Importação via readxl
- Padronização de colunas e criação de fatores

2. Estatística descritiva

- Média, mediana, desvio padrão
- Identificação de outliers (boxplot)

3. Testes de normalidade

- Shapiro-Wilk
- pH → normal
- Matéria Orgânica → normal
- Condutividade e Metais → não normal

4. Testes comparativos

- pH (Controle × Impactada): t-test → sem diferença significativa
- Condutividade (Controle × Impactada): Wilcoxon → sem diferença significativa
- Matéria Orgânica (Rio/Lago/Solo): ANOVA → não significativo
- Metais Pesados (Rio/Lago/Solo): Kruskal-Wallis → não significativo

5. Correlações

- pH × Matéria Orgânica → fraca, não significativa
- Condutividade × Metais Pesados → fraca, não significativa

6. Visualizações

- Média de matéria orgânica por local
- Boxplot de metais por local
- Série de condutividade por tipo de local

 Conclusão

1. Os parâmetros avaliados não apresentaram diferenças significativas entre áreas ou tipos de local, indicando que:
2. Os ambientes possuem condições físico-químicas semelhantes
3. Não há evidências de impacto localizado na área “Impactada”
4. As variações observadas são compatíveis com variabilidade natural

O projeto demonstra domínio de estatística inferencial aplicada ao diagnóstico ambiental.

🛠️ Ferramentas Utilizadas

- R
- tidyverse
- ggplot2
- dplyr
- stats

Autora
Camila Mariana – Graduação em Oceanografia (UERJ)
