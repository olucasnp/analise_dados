# Crescimento populacional 2010 → 2022 (IBGE, Censo 2022)

Notebook `analise_populacao.ipynb` (pandas + numpy) que lê a tabela `CD2022_Populacao_2010_Compatibilizada_20231222.xlsx` e gera:

| Arquivo | Conteúdo |
|---|---|
| `populacao_estados.csv` | População agregada por UF, ordenada pelo maior crescimento absoluto 2010–2022 |
| `populacao_municipios.csv` | População por município, ordenada pelo maior crescimento absoluto 2010–2022 |

O crescimento usa a população 2010 compatibilizada com os limites territoriais de 2022, conforme a nota do IBGE.
CSV separado por `;`, decimal `,` (abre direto no Excel em português).
