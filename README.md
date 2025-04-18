# Projeto de Engenharia de Dados — Montadora de Veículos (Fictícia)

Este projeto prático simula o cenário de uma montadora de veículos fictícia, com foco na construção de um **Data Warehouse moderno**, utilizando tecnologias amplamente adotadas no mercado de dados.

##  Tecnologias Utilizadas

- **PostgreSQL**: banco de dados transacional
- **Airflow**: orquestração e automação de pipelines de dados
- **Snowflake**: Data Warehouse em nuvem
- **dbt (data build tool)**: transformação e modelagem de dados
- **Looker Studio**: visualização e criação de dashboards

> ⚠️ Algumas ferramentas utilizadas, como o Snowflake e o Looker Studio, possuem planos pagos e recursos que demandam infraestrutura. Portanto, **não estão ativas em produção para evitar custos contínuos**.  
> No entanto, **o Airflow foi configurado em uma instância EC2 da AWS** para simular um ambiente de orquestração real.

##  Pipeline de Dados

1. **Extração** de dados transacionais em tempo real (simulados)
2. **Carga** dos dados para o Snowflake via Airflow
3. **Transformação** com dbt: modelagem dimensional (modelo estrela)
4. **Visualização** no Looker Studio com dashboards interativos

##  Aprendizados-Chave

- Criação e orquestração de pipelines com Airflow
- Transformações com dbt seguindo boas práticas de engenharia de dados
- Integração entre PostgreSQL, Snowflake e ferramentas de visualização
- Construção de dashboards dinâmicos para suporte à decisão

##  Resultado

Dashboards que demonstram métricas relevantes para a operação da montadora, como:
- Vendas por modelo e região
- Análise de desempenho por concessionária
- Indicadores de produção e estoque

##  Próximos Passos

- Integração com Kafka para ingestão em tempo real
- Testes e monitoramento de qualidade de dados
- Automatização completa via CI/CD

---

**#EngenhariaDeDados #Airflow #dbt #Snowflake #DataWarehouse #PostgreSQL #LookerStudio #DataPipeline #DataEngineering**
