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
Código que gera os relatórios contidos em nulos_consolidados.

-- ols_reg_ridge
Contém o código para rodar a regressão.

-- base_2001_2008
Base na forma final, ajustada para a regressão.

-- Diálogos com o robozinho
Conversas com o GPT para chegar a toda essa parafernalha.

*** TODO ***
Montar base 2009 até 2016 \n
Montar base 2017 até 2024 \n
Realizar análises visuais \n
Realizar análises não supervisionadas: clusterizações por perfil financeiro (k_means, GMM, hdbsscan), análise de latentes (PCA e análise fatorial) \n
Incluir rótulos para análises supervisionadas: risco_de_encerramento (logit, ridge e lasso, XGBoost), previsão_de_indicadores (Ridge, GBM, Arimax) \n 
Corrirgir bug de decimais nas coluna (DADOS_CONTAB_AUSENTES e qualquer outro rótulo que não for possível manipular sabe-se lá por quê) e ajustar a precisão para 5 casas \n
Incluir aqui todas as informações que faltam para ficar suficiente claro. \n
