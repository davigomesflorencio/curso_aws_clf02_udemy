# Tópico 02: Segurança e Conformidade

## 1. Modelo de Responsabilidade Compartilhada
A segurança e a conformidade são uma responsabilidade compartilhada entre a AWS e o cliente.

*   **AWS: Segurança DA Nuvem (Security OF the Cloud).**
    *   A AWS é responsável por proteger a infraestrutura que executa todos os serviços oferecidos na Nuvem AWS (Hardware, Software, Redes, Instalações).
*   **Cliente: Segurança NA Nuvem (Security IN the Cloud).**
    *   O cliente é responsável pela configuração dos serviços, gerenciamento de dados, sistemas operacionais (em IaaS), firewalls, criptografia e gerenciamento de identidade (IAM).

## 2. AWS IAM (Identity and Access Management)
Permite gerenciar o acesso aos serviços e recursos da AWS de forma segura.

*   **Usuários (Users):** Pessoas ou aplicações que acessam a AWS.
*   **Grupos (Groups):** Coleção de usuários para facilitar a atribuição de permissões.
*   **Funções/Roles (Roles):** Identidades que podem ser assumidas por serviços ou usuários externos (sem senhas de longo prazo).
*   **Políticas (Policies):** Documentos JSON que definem as permissões (Allow/Deny).
*   **MFA (Multi-Factor Authentication):** Camada extra de proteção além da senha.

## 3. Serviços de Segurança Principais
*   **AWS Shield:** Proteção gerenciada contra ataques DDoS (Standard é gratuito).
*   **AWS WAF (Web Application Firewall):** Protege contra explorações comuns da web (SQL Injection, Cross-site scripting).
*   **AWS KMS (Key Management Service):** Criação e gerenciamento de chaves de criptografia.
*   **Amazon Inspector:** Serviço automatizado de avaliação de segurança para instâncias EC2.
*   **AWS CloudTrail:** Registra todas as chamadas de API (Quem fez o quê, quando e onde).
*   **AWS Artifact:** Portal para acessar documentos de conformidade e relatórios de auditoria da AWS.
*   **AWS GuardDuty:** Serviço inteligente de detecção de ameaças.

## 4. Princípios de Design de Segurança
*   Privilégio Mínimo (Least Privilege): Conceda apenas as permissões necessárias.
*   Segurança em todas as camadas.
*   Automação de práticas recomendadas de segurança.
*   Proteção de dados em trânsito e em repouso.
