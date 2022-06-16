## Recursos Especiais baixados interpostos pelo MPSP
### 16/06/2022
O presente notebook buscou obter os resultados dos recursos especiais interpostos pelo MPSP.

A análise foi feita a partir de dataset gerado pelo STJ, filtrando-se 1000 processos que tinham o MPSP como parte ou interessado, já baixados (pois a intenção era a de conhecer o desfecho), em ordem cronológica descendente da data da última movimentação. O arquivo "csv" foi gerado pelo STJ no dia 16 jun. 2022.

O codigo foi escrito em Python. Foram utilizadas as bibliotecas pandas (para as operações com o dataframe), matplotlib (para os gráficos), requests (para as requisições http ao site do STJ) e beautifulsoup (para a extração dos dados dos documentos html recuperados).
