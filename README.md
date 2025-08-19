-- faltantes_por_ops
Contém os relatórios que segregam, por operadora, os dados faltantes, por dois grupos: contábeis e indicadores.

-- dados_isolados
São os dados manipulados, contém somente os indicadores, sem lógica de cálculo, apenas valores hardcoded.

-- nulos_consolidados
Relatórios de dados faltantes, porém, dessa vez, agregados por grupos de contas e indicadores.

-- saidas_reg
Saídas do modelos gerado, é um modelo sem poder preditivido nem ajuste relevante, porém, já é um começo.
A primeira melhoria, acredito, está na redução de dimensionalidade e um proxy mais adequado para a variável dependentes, pois o usado tende a valores muito repetidos.

-- dados_faltantes_por_ops
Contém os códigos rodados, para reproduzir as análises que geram os relatórios contidos na pasta faltantes_por_ops.

-- testa_continuidade_prestador_de_saude
Cógido que gera os relatórios contidos em nulos_consolidados.

-- ols_reg_ridge
Contém o código para rodar a regressão.

-- base_2001_2008
Base na forma final, ajustada para a regressão.


