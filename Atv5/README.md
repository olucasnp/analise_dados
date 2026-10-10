# IDHM por Unidade da Federação (1991–2024)

Notebook `analise_idh.ipynb` (pandas + numpy + matplotlib) sobre a `Tabela4.csv`:

- leitura de CSV com `;`, vírgula decimal e codificação latin-1
- limpeza de colunas vazias
- ranking dos estados pelo IDH de 2024
- maior melhora entre 1991 e 2024 e estados em que o IDH piorou
- conversão do formato largo para o longo com `melt`
- gráficos de linha: só Minas Gerais (`idh_minas_gerais.png`), todos os estados (`idh_todos_estados.png`) e MG em destaque (`idh_destaque_mg.png`)
