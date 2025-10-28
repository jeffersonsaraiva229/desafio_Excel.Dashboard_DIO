# Dashboard de Vendas - [venda de planos de jogos online!]

## Objetivo
Criar um dashboard em Excel para analisar desempenho de vendas (KPIs, comparativos por mês, produto, região, etc).

## Estrutura do repositório
- `data/base.xlsx` — base de dados usada
- `dashboard.xlsx` — arquivo Excel com o dashboard final
- `screenshots/` — imagens do dashboard (visualização)
- `README.md` — instruções e detalhes

## Dados utilizados
- Fonte: (fonte de dados forncida pela DIO)
- Colunas importantes: `Data`, `Produto`, `Região`, `Vendas`, `Quantidade`, `Custo`, etc.
- Observações sobre limpeza/transformação (ex.: removi linhas nulas, formatei datas, agrupei categorias X)

## Como reproduzir / instruções
1. Abra `dashboard.xlsx`.
2. Se necessário, habilite as conexões/external links: `Dados > Atualizar tudo`.
3. Para atualizar com outra base:
   - Substitua `data/base.xlsx` mantendo o mesmo layout de colunas.
   - Abra `dashboard.xlsx` e atualize as tabelas/pivôs: clique em cada Tabela Dinâmica → `Atualizar`.
4. Ferramentas usadas: Tabelas, Tabela Dinâmica, Segmentação (Slicers), Gráficos, Formatação condicional.

## Recursos e notas técnicas
- Planilhas internas:
  - `Raw` — dados originais
  - `Model` — tabela preparada (colunas, fórmulas)
  - `Dashboard` — visual
- Fórmulas importantes: (listar fórmulas/colunas calculadas, e.g. `=SOMASES(...)`, `=ÍNDICE/CORRESP`, `POWER QUERY` se usado)
- Limitações: (ex.: dados apenas até 2024, dados fictícios, etc.)

## Contato
- Autor: Jefferson Teixeira Saraiva 
- E-mail: jeffersonsaraiva229@gmail.com

