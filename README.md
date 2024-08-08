# Fundamentos de ETL

> ### História do ETL e do ELT
> - Existe desde a década de 1970.
> - Popularização com o surgimento dos data warehouses. No entanto, os data warehouses tradicionais exigiam processos ETL personalizados para cada fonte de dados.
> - O ELT se tornou o método moderno de integração de dados para análises eficientes.

> ### Como o processo de ETL evoluiu?
> - Originou-se com o surgimento de banco de dados relacionais que armazenavam dados na forma de tabelas para análises.
> 
> Tradicional:
> - Dados armazenados em banco de dados transacionais, os quais ofereciam suporte para muitas solicitações de leitura e gravação, mas não ofereciam boas análises.
>   
> Moderno:
> - Tecnologia de nuvem surgiu possibilitando a criação de vastos bancos de dados (também chamados de coletores de dados). Esses coletores de dados podem receber dados de várias fontes e ter recursos de hardware subjacentes, os quais podem ser dimensionados com o passar do tempo.
> - Mais sofisticação e podem funcionar junto com os coletores de dados modernos. Convertem formatos de dados herdados para dados modernos.
>
> Data warehouses: é um repositório central que pode armazenar vários bancos de dados. Em cada banco de dados, você pode organizar seus dados em tabelas e colunas, as quais descrevem os tipos de dados presentes na tabela.
> 
> Data lakes: armazenar seus dados estruturados e não estruturados em um repositório centralizado e em qualquer escala. Pode armazenar dados como eles estão, sem a necessidade de estrutura-los. Pode realizar vários tipos de análises, como consultas SQL, análises de big data, pesquisas de texto completo, análise em tempo real e machine learning para orientar melhores decisões.

> ### O que é ETL?
> - Extract, Transform e Load (Extrair, Transformar e Carregar).
>
> - O ETL combina dados de vários sistemas em um único banco de dados, repositório de dados, armazenamento de dados ou data lake. Pode ser usado para armazenar dados legados, ou, o que é mais comum, agregar dados para analisar e impulsionar as decisões de negócios.
>
> - Extração: É o processo de recuperação de dados de uma ou mais origens, sejam elas on-lines, locais, legadas, SaaS ou outras. Após a conclusão da recuperação ou extração, os dados são carregados em uma área de preparo.
> - Transformação: Envolve pegar esses dados, limpá-los e colocá-los em um formato comum, para que possam ser armazenados em um banco de dados, repositórios de dados, armazenamento de dados ou data lakes de destino. A limpeza normalmente envolve extrair registros duplicados, incompletos ou obvimanete incorretos.
> - Carregamento: É o processo de inserir os dados formatados no banco de dados, repositório de dados, armazenamento de dados ou data lake de destino.


> ### Por que o ETL é importante?
> 
> Organização com dados estruturados e não estruturados, incluindo:
> - Dados de clientes de sistemas de pagamento on-lines e gerenciamento de relacionamento com o cliente (CRM).
>   
> - Dados de estoque e oprações dos sistemas do fornecedor.
>   
> - Dados de sensores de dispositivos de Internet das Coisas (IoT).
>   
> - Dados de marketing das mídias sociais e comentários do cliente.
>   
> - Dados de funcionários de sistemas internos de recursos humanos.
>
> Com a aplicação do processo de ETL, conjuntos de dados brutos individuais podem ser preparados em um formato e uma estrutura mais consumíveis para fins de análise, resultando em informações mais significativas.


> ### Como o processo de ETL beneficia o business intelligence?
> - Aprimora o BI e a análise, tornando o processo mais confiável, preciso, detalhado e eficiente.
>   
> - Contexto histórico aos dados: Um empresa pode combinar dados herdados com dados de novas plataformas.
> - Visualização de dados consolidada: Combinação de bancos de dados e várias formas de dados em uma visualização única.
> - Análise de dados precisa: Para atender aos padrões regulatórios e de conformidade.
> - Automação de tarefas: Automatizam o processo de migração de dados e você pode configura-las para integrar alterações de dados periodicamente ou até mesmo durante uma execução.


> ### O que é ELT - Extract, Load e Transformação
> - É uma extenção de extração, transformação e carregamento (ETL) que inverte a ordem das operações.
> - Carregamento de dados diretamente no sistema de destino antes de processá-los.
>
> ETL em comparação com o ELT
> - ELT funciona bem para conjuntos de dados não estruturados e de alto volume que exigem carregamento frequente.
> - Ideal para big data, pois o planejamento de análise pode ser realizado após a extração e armazemaneto dos dados.
> - O processo de ETL requer maior definição no início.


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

> ### Diferenças entre ETL e ELT
> São abordagens de processamento de análise.
> ETL usa conjunto de regras de negócios para processar dados de várias fontes antes da integração centralziada
> ELT carrega os dads como estão e os transforma em um estágio posterior, dependendo do caso de uso e dos requisitos de análise.










Referências:

https://cloud.google.com/learn/what-is-etl?hl=pt-BR

https://aws.amazon.com/pt/what-is/etl/
