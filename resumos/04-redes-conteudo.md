# Tópico 04: Redes e Entrega de Conteúdo

## 1. Amazon VPC (Virtual Private Cloud)
Permite provisionar uma seção logicamente isolada da Nuvem AWS, onde você pode lançar recursos em uma rede virtual definida por você.

*   **Sub-redes (Subnets):** Divisão lógica da VPC em intervalos de endereços IP (Pública ou Privada).
*   **Gateways da Internet (Internet Gateways):** Permite que sua VPC se comunique com a Internet.
*   **Grupos de Segurança (Security Groups):** Firewall virtual em nível de **Instância** (Stateful).
*   **ACLs de Rede (NACLs):** Firewall virtual em nível de **Sub-rede** (Stateless).
*   **AWS Direct Connect:** Conexão de rede dedicada entre suas instalações e a AWS (Ignora a Internet).
*   **VPC Peering:** Conexão de rede entre duas VPCs diferentes.
*   **VPC Endpoints (PrivateLink):** Conecta de forma privada sua VPC aos serviços da AWS e serviços de endpoint compatíveis.

## 2. Roteamento e Distribuição de Conteúdo
*   **Amazon Route 53:** Serviço de DNS altamente disponível e escalável. Oferece políticas de roteamento (Simple, Failover, Geolocation, Latency, Weighted).
*   **Amazon CloudFront:** Rede de entrega de conteúdo (CDN) que acelera a distribuição de seus conteúdos estáticos e dinâmicos para usuários finais em todo o mundo. Reduz latência através de **Edge Locations**.
*   **AWS Global Accelerator:** Serviço que usa a infraestrutura de rede global da AWS para melhorar a performance e disponibilidade das aplicações dos usuários. Fornece IPs estáticos fixos.

## 3. Balanceamento de Carga
*   **AWS ELB (Elastic Load Balancing):** Distribui automaticamente o tráfego de entrada em múltiplos destinos (Instâncias EC2, Contêineres, IPs, Lambdas).
    *   **Application Load Balancer (ALB):** Nível 7 (HTTP/HTTPS). Ideal para aplicações micro-serviços.
    *   **Network Load Balancer (NLB):** Nível 4 (TCP/UDP/TLS). Ideal para altíssima performance e tráfego TCP.
    *   **Gateway Load Balancer (GWLB):** Ideal para appliance de terceiros.
