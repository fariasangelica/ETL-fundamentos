# Fundamentos de ETL

> ### História do ETL e do ELT
> - Existe desde a década de 1970.
> - Popularização com o surgimento dos data warehouses. No entanto, os data warehouses tradicionais exigiam processos ETL personalizados para cada fonte de dados.
> - O ELT se tornou o método moderno de integração de dados para análises eficientes.

> ### O que é ETL?
> - Extract, Transform e Load (Extrair, Transformar e Carregar).
>
> - O ETL combina dados de vários sistemas em um único banco de dados, repositório de dados, armazenamento de dados ou data lake. Pode ser usado para armazenar dados legados, ou, o que é mais comum, agregar dados para analisar e impulsionar as decisões de negócios.
>
> - Extração: É o processo de recuperação de dados de uma ou mais origens, sejam elas on-lines, locais, legadas, SaaS ou outras. Após a conclusão da recuperação ou extração, os dados são carregados em uma área de preparo.
> - Transformação: Envolve pegar esses dados, limpá-los e colocá-los em um formato comum, para que possam ser armazenados em um banco de dados, repositórios de dados, armazenamento de dados ou data lakes de destino. A limpeza normalmente envolve extrair registros duplicados, incompletos ou obvimanete incorretos.
> - Carregamento: É o processo de inserir os dados formatados no banco de dados, repositório de dados, armazenamento de dados ou data lake de destino.

> ### O que é ELT - Extract, Load e Transformação
>
> ### Como os processos ELT e ETL diferem entre si?
> Processo ETL
>   1. Extrai dados brutos de várias fontes.
>   2. Você usa um servidor de processamento secundário para transformar esses dados.
>   3. CarregaR esses dados em um banco de dados de destino.

![image](https://github.com/user-attachments/assets/3998b2a8-d9a2-4484-b5af-db51e74d654e)

> Processo ELT
> 1. Extrai dados brutos de várias fontes.
> 2. Você o carrega em seu estado natural em um data warehouse ou data lake.
> 3. Transformar conforme necessário enquanto está no sistema de destino.

> ### 








Referências:

https://cloud.google.com/learn/what-is-etl?hl=pt-BR

https://aws.amazon.com/pt/what-is/etl/
