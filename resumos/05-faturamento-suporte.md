# Tópico 05: Faturamento, Precificação e Suporte

## 1. Precificação da AWS
Existem três pilares fundamentais de custo na AWS:
1.  **Computação:** Cobrado por segundo ou hora.
2.  **Armazenamento:** Cobrado por GB por mês.
3.  **Transferência de Dados:** Cobrado por dados que **SAEM** da AWS (Dados que entram geralmente são grátis).

## 2. Ferramentas de Gerenciamento de Custos
*   **AWS Budgets:** Permite criar orçamentos personalizados que alertam quando seus custos ou uso excedem o esperado.
*   **AWS Cost Explorer:** Ferramenta visual que permite visualizar, entender e gerenciar seus custos e uso da AWS ao longo do tempo.
*   **Calculadora de Preços da AWS:** Estima o custo de seus casos de uso e serviços antes de provisioná-los.

## 3. Estratégias de Economia (EC2)
*   **Instâncias On-Demand:** Pague pelo que usar sem compromisso (Mais caros).
*   **Savings Plans:** Compromisso de uso de computação (em $/hora) por 1 ou 3 anos para até 72% de economia.
*   **Instâncias Reservadas (Reserved Instances):** Compromisso de uso de instâncias específicas por 1 ou 3 anos.
*   **Instâncias Spot:** Utilize a capacidade sobressalente da AWS com até 90% de desconto (Pode ser interrompida). Ideal para cargas de trabalho flexíveis.

## 4. Planos de Suporte AWS
1.  **Basic (Grátis):** Sucesso ao cliente e suporte de serviço 24x7, documentação, whitepapers. Sem suporte técnico.
2.  **Developer ($29+/mês):** Recomendado para ambientes de teste e desenvolvimento. Resposta < 24h para problemas gerais.
3.  **Business ($100+/mês):** Recomendado para cargas de trabalho de produção. Acesso 24x7 via chat/telefone. Resposta < 1h para sistemas fora do ar.
4.  **Enterprise ($15.000+/mês):** Recomendado para cargas de trabalho críticas. Inclui **TAM (Technical Account Manager)** dedicado e resposta < 15 min para missão crítica.

## 5. AWS Organizations
Permite consolidar e gerenciar centralizadamente múltiplas contas AWS.
*   **Faturamento Consolidado:** Uma única conta paga por todas as outras, permitindo maiores descontos por volume.
*   **SCPs (Service Control Policies):** Define permissões e limites para todas as contas da organização.
