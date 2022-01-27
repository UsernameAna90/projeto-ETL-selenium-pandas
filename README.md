# projeto-ETL-selenium-pandas

Pequeno projeto pessoal buscando aliar o aprendizado de automação web com Selenium e transformação de dados com Pandas para praticar a realização do processo de ETL - Importação, Tratamento e Exportação de dados.

A base de dados escolhida contempla informações sobre a importação de produtos do exterior para o Brasil. O objetivo é encontrar o valor que o país desembolsaria pelos mesmos produtos atualmente, considerando as constantes mudanças na cotação das moedas internacionais e o câmbio da moeda.

Nesse contexto, o Selenium foi usado para fazer buscas automatizadas na web trazendo os valores atualizados da cotação de cada diferente moeda presente na base de dados. E o Pandas foi usado para fazer análises exploratórias afim de encontrar inconsistências entre os dados, e tratar tais inconsistências.

Por fim, novos dados foram inseridos demonstrando a cotação atual, preço dos produtos atualmente em relação a diferente cotação, parcela acrescida ou diminuída entre o preço original e o preço atual, e ainda despesas totais referentes aos dois períodos, visando atingir o objetivo estabelecido para os dados.

Demais detalhes do processo estão explicados em comentários no notebook!
