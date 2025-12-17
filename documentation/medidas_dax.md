1. Métricas de faturamento e volume
   **Faturamento total:** soma da receita bruta de todas as vendas
   EVALUATE
      SUMMARIZECOLUMNS(
        "Total de vendas (R$)", [Total de vendas (R$)]
    )

   **Quantidade de pedidos:** Contagem distinta de produtos vendidos
   EVALUATE
      SUMMARIZECOLUMNS(
        "Quantidade vendida", [Quantidade vendida]
    )

2. Indicadores de eficiência (KPI)
   **Ticket médio:** Valor médio de cada venda
   EVALUATE
    SUMMARIZECOLUMNS(
        "Ticket médio", [Ticket médio]
    )

   **Vendas por loja:** Contagem de unidades vendidadas por loja para análise de rentabilidade
   EVALUATE
      SUMMARIZECOLUMNS(
        "Vendas por loja", [Vendas por loja]
    )
