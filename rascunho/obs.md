dashboard = graficos interativos de linha e pizza
movimentações = cadastro de entradas, saidas e de categorias
planejamento = criação de cofrinhos e associação de metas ( à revisar )
investimentos = visualição da carteira, cadastros de ações, fii, etf, tesouro direto etc ( conectar a bolsa para ver a mudança de valorização dos ativos investidos)
relatorios = relatorios estáticos em pdf trazendo relações (tabelas) dos registros assim como graficos estáticos. O relatorio permite filtrar por periodo palavras-chaves, valores etc (diversas consultas de sql)


                         CARTEIRA
                            │
             ┌──────────────┴──────────────┐
             │                             │
         FRONTEND                       BACKEND
             │                             │
       HTML + CSS + JS                  Django
                                           │
                              ┌────────────┴────────────┐
                              │                         │
                           Django ORM              Lógica Python
                              │                         │
                              └────────────┬────────────┘
                                           │
                                      PostgreSQL

======
PANDAS
======
PostgreSQL
      ↓
   Django
      ↓
 registros financeiros
      ↓
    pandas
      ↓
 agrupamento/análise
      ↓
 resultado                                    

======
NUMPY
======
API da bolsa
     ↓
   Django
     ↓
PostgreSQL
     ↓
   Python
     ↓
   NumPy
     ↓
indicadores

======
MATPLOTLIB
======
Python
   ↓
dados
   ↓
análise
   ↓
gráfico estático