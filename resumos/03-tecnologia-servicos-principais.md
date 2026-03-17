# Tópico 03: Tecnologia e Serviços Principais

## 1. Computação (Compute)
*   **Amazon EC2 (Elastic Compute Cloud):** Servidores virtuais na nuvem (Instâncias). Oferece controle total do SO.
    *   **Tipos de Instâncias:**
        *   **General Purpose (T, M):** Equilíbrio entre computação, memória e rede.
        *   **Compute Optimized (C):** Ideal para aplicações que exigem processadores de alta performance (batch processing, media transcoding).
        *   **Memory Optimized (R, X, Z):** Para cargas de trabalho que processam grandes conjuntos de dados na memória (bancos de dados open-source, cache in-memory).
        *   **Storage Optimized (I, D, H):** Para tarefas que exigem alto acesso sequencial de leitura/escrita em grandes conjuntos de dados no armazenamento local (NoSQL, Data Warehousing).
        *   **Accelerated Computing (P, G, F):** Usam coprocessadores de hardware para funções como processamento gráfico ou cálculo de dados (Machine Learning, Renderização 3D).
*   **AWS Lambda:** Computação **Serverless**. Executa código sem gerenciar servidores. Você paga apenas pelo tempo de execução.
*   **AWS Fargate:** Mecanismo de computação sem servidor para contêineres (ECS/EKS).
*   **AWS Elastic Beanstalk:** PaaS para implantar e escalar aplicações web rapidamente (Java, .NET, PHP, Node.js, Python, Ruby, Go e Docker).

## 2. Armazenamento (Storage)
*   **Amazon S3 (Simple Storage Service):** Armazenamento de objetos organizado em **Buckets**.
    *   **S3 Storage Classes:**
        *   **S3 Standard:** Alta durabilidade, disponibilidade e performance para dados acessados frequentemente.
        *   **S3 Intelligent-Tiering:** Move dados automaticamente para a classe mais econômica com base no padrão de acesso.
        *   **S3 Standard-IA (Infrequent Access):** Para dados acessados com menos frequência, mas que precisam de acesso rápido quando necessário. Custo de armazenamento menor, mas custo de recuperação maior.
        *   **S3 One Zone-IA:** Igual ao Standard-IA, mas os dados são armazenados em uma única AZ (menos resiliente, mais barato).
        *   **S3 Glacier Instant Retrieval:** Para arquivos de longa duração acessados raramente (milisegundos).
        *   **S3 Glacier Flexible Retrieval:** Arquivamento barato, recuperação de minutos a horas.
        *   **S3 Glacier Deep Archive:** Classe mais barata para retenção de 7-10 anos (recuperação em até 12 horas).
*   **Amazon EBS (Elastic Block Store):** Blocos de armazenamento de alto desempenho para uso com instâncias EC2 (equivalente a um HD/SSD virtual).
*   **Amazon EFS (Elastic File System):** Sistema de arquivos NFS totalmente gerenciado e elástico. Pode ser montado em centenas de instâncias EC2 simultaneamente.
*   **S3 Glacier:** Armazenamento de baixo custo para arquivamento de dados a longo prazo.

## 3. Bancos de Dados (Databases)
*   **Amazon RDS (Relational Database Service):** Serviço gerenciado para bancos de dados relacionais (MySQL, PostgreSQL, Oracle, SQL Server, MariaDB e Amazon Aurora).
*   **Amazon Aurora:** Banco de dados relacional compatível com MySQL e PostgreSQL, criado para a nuvem.
*   **Amazon DynamoDB:** Banco de dados **NoSQL** (Chave-Valor) totalmente gerenciado, com latência de milissegundos em qualquer escala.
*   **Amazon ElastiCache:** Serviço de cache na memória (Redis ou Memcached) para melhorar a performance de aplicações.
*   **Amazon Redshift:** Data warehouse em escala de petabytes.

## 4. Integração de Aplicações
*   **Amazon SQS (Simple Queue Service):** Serviço de filas de mensagens desacopladas.
*   **Amazon SNS (Simple Notification Service):** Serviço de mensagens Pub/Sub (Email, SMS, Lambda).
*   **AWS Step Functions:** Orquestração visual de workflows para aplicações distribuídas.
