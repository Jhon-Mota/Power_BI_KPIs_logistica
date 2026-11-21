📦 Dashboard de Análise Logística | Power BI

Dashboard interativo desenvolvido em Power BI para acompanhar e analisar a operação logística de uma empresa que atende grandes varejistas. A partir de um arquivo CSV com informações logísticas, o painel consolida em uma única tela indicadores de faturamento, volume de itens, pontualidade das entregas, desempenho dos motoristas, devoluções e evolução das compras ao longo do tempo.

📖 Sobre o projeto

Em operações logísticas, acompanhar apenas o faturamento não é suficiente: é preciso entender quem são os clientes mais relevantes, quantos itens estão sendo movimentados, se as entregas estão chegando no prazo, como cada motorista está performando e por que os produtos estão sendo devolvidos.

Este projeto nasceu da necessidade de reunir essas informações em um painel visual, claro e de fácil leitura, permitindo que gestores e analistas tomem decisões baseadas em dados e identifiquem rapidamente gargalos na operação.

O dashboard foi construído inteiramente no Power BI, utilizando como base um arquivo CSV com os registros logísticos, que passou por tratamento e modelagem antes da criação dos visuais.

🎯 Objetivos
Consolidar os principais indicadores da operação logística em uma única visão.
Identificar os clientes com maior contribuição em faturamento e volume de itens.
Monitorar o índice de entregas realizadas no prazo versus atrasadas.
Comparar o desempenho dos motoristas em relação à pontualidade.
Entender os motivos das devoluções para apoiar ações corretivas.
Acompanhar a evolução das compras ao longo do tempo e identificar sazonalidades e picos de demanda.
🗂️ Fonte de dados
Formato: arquivo .csv
Conteúdo: informações logísticas contendo dados de clientes, itens, pedidos, entregas, motoristas, devoluções e datas de compra.
Tratamento: os dados foram importados e tratados no Power Query (tipagem de colunas, limpeza e padronização) antes de serem utilizados nos visuais.
📊 Visualizações do dashboard
1. Faturamento por cliente

Gráfico de colunas que apresenta o faturamento total de cada cliente. Permite identificar rapidamente quais contas geram mais receita para a operação.

Clientes analisados: Walmart, Casas Bahia, Magazine Luiza, Americanas, Casa e Vídeo e Ricardo Eletro.
2. Total de itens por cliente

Gráfico de barras horizontais com o volume total de itens movimentados por cliente. Complementa a análise de faturamento, mostrando se o volume de itens acompanha a receita gerada.

3. Status das entregas

Gráfico de pizza que mostra a proporção entre entregas no prazo e atrasadas, sendo o principal indicador de nível de serviço (SLA) da operação.

4. Status dos pedidos por motorista

Gráfico de colunas empilhadas que detalha, para cada motorista, a quantidade de pedidos entregues no prazo e com atraso. Possibilita comparar o desempenho individual e identificar onde há maior concentração de atrasos.

Motoristas analisados: Marcos Leroy, Luiz Pardal, Valdir Espinosa, Túlio Silveira, João Gomes e Felipe Silva.
5. Motivos de devoluções

Gráfico de rosca com a distribuição das devoluções por motivo, exibindo quantidade e percentual de cada categoria, além do total de devoluções no centro do gráfico.

Categorias: Produto errado, Danificado, S/ Devolu. e Arrependimento.
6. Compras por mês

Gráfico de área que mostra a evolução mensal das compras entre janeiro de 2019 e o final de 2021, ajudando a visualizar tendências, picos e quedas de demanda.

🔎 Principais insights

Com base nos dados apresentados no dashboard, destacam-se os seguintes pontos:

Walmart e Casas Bahia lideram o faturamento, com aproximadamente R$ 393 mil e R$ 348 mil, respectivamente. O Walmart também é o cliente com maior volume de itens (cerca de 12,2 mil).
Alto índice de atrasos: cerca de 73,21% das entregas foram realizadas com atraso, contra apenas 26,79% no prazo. Esse é o ponto mais crítico da operação e merece atenção prioritária.
O problema de atrasos é generalizado: todos os motoristas apresentam mais pedidos atrasados do que entregues no prazo, o que sugere que a causa pode estar em processos, rotas ou prazos acordados, e não em um indivíduo específico.
Principais causas de devolução: Produto errado (36,48%) e Danificado (31,27%) somam mais de 67% das devoluções, indicando oportunidades de melhoria em separação/conferência de pedidos e em embalagem e transporte.
Pico de compras em 2020: observa-se um crescimento expressivo a partir de meados de 2020, com picos próximos a 480 compras mensais, seguido de queda acentuada a partir do fim do ano e tendência de redução ao longo de 2021.

🛠️ Tecnologias utilizadas
Tecnologia	Finalidade
Power BI Desktop	Criação e design do dashboard
Power Query	Importação, limpeza e transformação dos dados
DAX	Criação de medidas e cálculos (totais, percentuais e indicadores)
CSV	Fonte de dados logísticos

