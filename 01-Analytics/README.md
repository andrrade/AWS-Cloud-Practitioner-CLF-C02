<div align="center">
  <h3>Amazon Athena</h3>
  <img src="../assets/analytics/Athenaa.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/athena/)

Amazon Athena is a serverless, interactive analytics service that provides a simplified and flexible way to analyze petabytes of data where it lives. 

Amazon Athena é um serviço de análise interativa e sem servidor (serverless) que oferece uma forma simplificada e flexível de analisar petabytes de dados onde eles estão armazenados.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Opera:** Layer 7 – Consulta de dados no S3 com SQL
- **Escopo:** Regional
- **Shared Model:**
  -  🔹 AWS cuida da infra e da escalabilidade
  -  🔹 Você cuida dos dados e permissões
- **Características:** Consulta SQL direto no S3, sem ETL, sem infraestrutura
- **Palavras-chave:** SQL no S3, análise rápida, sem servidor
- **Exemplo:** Você faz perguntas em SQL direto para arquivos guardados no S3, como se conversasse com uma planilha gigante.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa consultar dados armazenados no S3 usando SQL...”
  -  🔹 “Qual serviço permite consultar dados no S3 sem infraestrutura?”
- 💰 **Como é cobrado:**
  - 🔹 Por volume de dados lido na consulta

---

<div align="center">
  <h3>Amazon EMR</h3>
  <img src="../assets/analytics/EMR.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/emr/)

Amazon EMR is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications using open-source analytics frameworks such as Apache Spark, Apache Hive, and Presto.

O Amazon EMR é uma plataforma de big data na nuvem para executar tarefas de processamento de dados distribuídos em larga escala, consultas SQL interativas e aplicações de machine learning, utilizando frameworks de análise open-source como Apache Spark, Apache Hive e Presto.

- **Modelo:** PaaS
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌ (mas tem opção com serverless)
- **Escopo:** Regional
- **Opera:** Nível de cluster (processamento de big data)
- **Shared Model:**
  -  🔹 AWS cuida da infraestrutura básica
  -  🔹 Você gerencia clusters, jobs, segurança
- **Características:** Processa grandes volumes com frameworks como Hadoop, Spark
- **Palavras-chave:** Big Data, Hadoop, Spark, clusters
- **Exemplo:** Como uma fábrica que transforma dados brutos em relatórios, usando várias esteiras (nós).
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa processar grandes volumes com Hadoop ou Spark...”
  -  🔹 “Qual serviço usa clusters para big data?”
- 💰 **Como é cobrado:**
  -  🔹 Por hora e por tipo de instância usada nos clusters

---

<div align="center">
  <h3>AWS Glue</h3>
  <img src="../assets/analytics/Gluee.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/glue/)

AWS Glue is a serverless data integration service that makes it easy to discover, prepare, integrate, and modernize the extract, transform, and load (ETL) process.

O AWS Glue é um serviço de integração de dados serverless que facilita a descoberta, preparação, integração e modernização do processo de extração, transformação e carga (ETL).

- **Modelo:** PaaS
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de dados (ETL – Extract, Transform, Load)
- **Shared Model:**
  -  🔹 AWS cuida da infra e do motor de execução
  -  🔹 Você gerencia os scripts e dados
- **Características:** ETL serverless, catálogo de dados, integração com S3, Redshift, etc.
- **Palavras-chave:** ETL, Catálogo, transformação de dados, serverless
- **Exemplo:** Como um robô que limpa, organiza e entrega os dados já prontos para uso.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa transformar dados de forma automática...”
  -  🔹 “Qual serviço é ideal para ETL serverless?”
- 💰 **Como é cobrado:**
  -  🔹 Por DPU-hora (Data Processing Unit por tempo usado)

---

<div align="center">
  <h3>Amazon Kinesis</h3>
  <img src="../assets/analytics/Kinesiss.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/kinesis/)

Collect streaming data, create a real-time data pipeline, and analyze real-time video and data streams, log analytics, event analytics, and IoT analytics.

Coleta dados em streaming, cria um pipeline de dados em tempo real e permite analisar transmissões de vídeo e dados em tempo real, além de análises de logs, eventos e dados de IoT.

- **Modelo:** PaaS
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌ (Kinesis Data Firehose é serverless)
- **Escopo:** Regional
- **Opera:** Nível de dados em tempo real (streaming)
- **Shared Model:**
  -  🔹 AWS cuida da infra e alta disponibilidade
  -  🔹 Você define streams, consumo, retenção
- **Características:** Captura, processa e analisa dados em tempo real
- **Palavras-chave:** Streaming, tempo real, ingestão de dados
- **Exemplo:** Como um rio de dados fluindo continuamente e você decide onde colocar as redes de pesca.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa capturar dados em tempo real de sensores...”
  -  🔹 “Qual serviço lida com ingestão de streaming?”
- 💰 **Como é cobrado:**
  -  🔹 Por volume de dados processado e shards usados

---

<div align="center">
  <h3>Amazon OpenSearch Service</h3>
  <img src="../assets/analytics/OpenSearch Service.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/opensearch-service/)

Unlock fast and scalable search, monitoring, and analysis for log analytics and website search by deploying and running OpenSearch and ALv2 Elasticsearch.

Desbloqueie buscas rápidas e escaláveis, monitoramento e análise para logs e buscas em sites ao implantar e executar o OpenSearch e o Elasticsearch com licença ALv2.

- **Modelo:** PaaS
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌
- **Escopo:** Regional
- **Opera:** Layer 7 – Pesquisa e análise de dados textuais/logs
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura
  -  🔹 Você define os índices, consultas e segurança
- **Características:** Busca rápida, análise de logs, visualizações
- **Palavras-chave:** Elasticsearch, logs, busca, Kibana
- **Exemplo:** Como um Google interno da sua empresa para buscar em registros e logs.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa pesquisar grandes volumes de logs...”
  -  🔹 “Qual serviço oferece análise e visualização com Kibana?”
- 💰 **Como é cobrado:**
  -  🔹 Por tipo e número de instâncias + armazenamento

---

<div align="center">
  <h3>Amazon QuickSight</h3>
  <img src="../assets/analytics/QuickSight.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/quicksight/)

Amazon QuickSight is a cloud-native, serverless, business intelligence with native ML integrations and usage-based pricing, allowing insights for all users.

O Amazon QuickSight é um serviço de business intelligence nativo da nuvem e serverless, com integrações nativas de machine learning e precificação baseada no uso, permitindo gerar insights para todos os usuários.

- **Modelo:** SaaS
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de aplicação (dashboard/BI)
- **Shared Model:**
  -  🔹 AWS cuida de tudo
  -  🔹 Você define os dados e painéis
- **Características:** Business Intelligence, painéis interativos, integração com outros serviços
- **Palavras-chave:** Dashboard, BI, visualização, insights
- **Exemplo:** Como criar gráficos coloridos e bonitos com apenas alguns cliques nos dados.
- 📝 **Como cai na prova:**
  -  🔹 “Você quer criar dashboards a partir dos dados...”
  -  🔹 “Qual serviço fornece BI interativo?”
- 💰 **Como é cobrado:**
  -  🔹 Por usuário (Standard ou Enterprise) ou por uso (SPICE)

---

<div align="center">
  <h3>Amazon Redshift</h3>
  <img src="../assets/analytics/Redshiftt.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/redshift/)

Amazon Redshift uses SQL to analyze structured and semi-structured data across data warehouses, operational databases, and data lakes, using AWS-designed hardware and machine learning to deliver the best price performance at any scale.

O Amazon Redshift utiliza SQL para analisar dados estruturados e semiestruturados em data warehouses, bancos de dados operacionais e data lakes, usando hardware desenvolvido pela AWS e machine learning para oferecer o melhor custo-benefício em qualquer escala.

- **Modelo:** PaaS
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌ (modo serverless existe, mas não é padrão)
- **Escopo:** Regional
- **Opera:** Layer 7 – Data warehouse (consultas SQL pesadas)
- **Shared Model:**
  -  🔹 AWS cuida da infra
  -  🔹 Você gerencia o uso e as permissões
- **Características:** Consultas rápidas, grande volume de dados, BI-friendly
- **Palavras-chave:** Data warehouse, analytics, SQL, performance
- **Exemplo:** Um armário gigante e superorganizado onde tudo é fácil de achar
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa de um data warehouse altamente performático...”
  -  🔹 “Qual serviço armazena e analisa grandes volumes com SQL?”
- 💰 **Como é cobrado:**
  -  🔹 Por tipo e tamanho de nó + tempo de uso (ou por consulta no modo serverless)
