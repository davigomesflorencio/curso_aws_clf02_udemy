# Tópico 01: Conceitos da Nuvem

## 1. O que é Computação em Nuvem?
Computação em nuvem é a entrega sob demanda de poder computacional, banco de dados, armazenamento, aplicações e outros recursos de TI por meio de uma plataforma de serviços de nuvem via Internet, com precificação de **pagamento conforme o uso (Pay-as-you-go)**.

## 2. Vantagens da Nuvem AWS
1.  **Troca de despesas de capital (CapEx) por despesas variáveis (OpEx):** Em vez de investir muito em data centers e servidores antes de saber como você os usará, pague apenas pelo que consumir.
2.  **Economias de escala massivas:** A AWS consegue preços mais baixos de fornecedores devido ao volume de clientes, repassando a economia.
3.  **Pare de adivinhar a capacidade:** Elimine o desperdício de recursos ociosos ou a falta de capacidade.
4.  **Aumento de velocidade e agilidade:** Recursos de TI estão a apenas alguns cliques de distância.
5.  **Pare de gastar dinheiro com manutenção de Data Centers:** Foque nos seus clientes e no código, não no hardware.
6.  **Expansão global em minutos:** Implemente aplicações em várias regiões do mundo rapidamente.

## 3. Modelos de Serviço de Nuvem
*   **IaaS (Infrastructure as a Service):** Contém os blocos fundamentais para o TI na nuvem. Oferece o maior nível de flexibilidade e controle (ex: EC2).
*   **PaaS (Platform as a Service):** Remove a necessidade de gerenciar a infraestrutura subjacente (hardware e SO). Foco na implementação e gerenciamento de aplicações (ex: Elastic Beanstalk).
*   **SaaS (Software as a Service):** Produto completo, executado e gerenciado pelo provedor (ex: AWS QuickSight, Dropbox, Gmail).

## 4. Modelos de Implantação de Nuvem
*   **Nuvem (Cloud):** Aplicação totalmente implantada na nuvem.
*   **Híbrida (Hybrid):** Conecta a infraestrutura local (on-premises) com a nuvem AWS.
*   **On-premises (Private Cloud):** Implantação de recursos localmente usando ferramentas de gerenciamento de virtualização.

## 5. Infraestrutura Global da AWS
*   **Regiões (Regions):** Áreas geográficas físicas ao redor do mundo que contêm 3 ou mais Zonas de Disponibilidade.
*   **Zonas de Disponibilidade (Availability Zones - AZs):** Um ou mais data centers discretos com energia, rede e conectividade redundantes em uma Região AWS. Oferecem alta disponibilidade e tolerância a falhas.
*   **Pontos de Presença (Edge Locations):** Locais onde o conteúdo é armazenado em cache para reduzir a latência para os usuários finais (usado pelo CloudFront).

## 6. AWS Well-Architected Framework
O framework ajuda arquitetos de nuvem a construir a infraestrutura mais segura, eficiente, resiliente e de alto desempenho possível para suas aplicações. Ele é baseado em **6 pilares**:

1.  **Excelência Operacional:** Executar e monitorar sistemas para entregar valor de negócio e melhorar continuamente processos e procedimentos.
2.  **Segurança:** Proteger informações, sistemas e ativos enquanto entrega valor de negócio através de avaliações de risco e estratégias de mitigação.
3.  **Confiabilidade:** Garantir que uma carga de trabalho execute sua função pretendida de forma correta e consistente quando esperado (foco em recuperação de falhas).
4.  **Eficiência de Performance:** Usar recursos de computação de forma eficiente para atender aos requisitos do sistema e manter essa eficiência à medida que a tecnologia muda.
5.  **Otimização de Custos:** Evitar gastos desnecessários. Entender onde o dinheiro está sendo gasto e selecionar os tipos de recursos com o tamanho e número corretos.
6.  **Sustentabilidade:** Foco em minimizar os impactos ambientais da execução de cargas de trabalho na nuvem.
