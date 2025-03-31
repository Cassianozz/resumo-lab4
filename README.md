# resumo-lab4
Resumo
1. Regiões e Geografias
Regiões: Áreas geográficas com múltiplos datacenters (ex.: Leste dos EUA, Sul do Brasil).

Geografias: Agrupamentos de regiões para compliance de dados (ex.: Europa, Ásia).

Pares de Regiões: Regiões emparelhadas para recuperação de desastre (DR).

2. Zonas de Disponibilidade (Availability Zones)
Datacenters fisicamente isolados dentro de uma região.

Oferecem alta disponibilidade e tolerância a falhas.

Baixa latência (< 2ms) entre zonas para replicação síncrona.

3. Conjuntos de Disponibilidade (Availability Sets)
Agrupam VMs em domínios de falha (FDs) e domínios de atualização (UDs).

FDs: Evitam falhas simultâneas (racks diferentes).

UDs: Garantem atualizações sem downtime total.

4. Grupos de Recursos (Resource Groups)
Contêineres lógicos para organizar recursos (VMs, redes, bancos de dados).

Gerenciam ciclo de vida (deploy, exclusão) e controle de acesso (RBAC).

Podem conter recursos de regiões diferentes.

5. Redes Virtuais (VNets) e Sub-redes
Isolamento lógico de recursos na nuvem.

Sub-redes: Segmentação para segurança (ex.: front-end, back-end).

Conectividade: VPN Gateway, ExpressRoute (conexão dedicada).

6. Balanceadores de Carga e Application Gateway
Azure Load Balancer: Distribui tráfego entre VMs (camada 4 - TCP/UDP).

Application Gateway: Balanceamento em camada 7 (HTTP/HTTPS) com WAF integrado.

7. Armazenamento
Blob Storage: Armazenamento de objetos (imagens, backups).

Azure Files: Sistemas de arquivos compartilhados (SMB/NFS).

Managed Disks: Discos persistentes para VMs.

8. Serviços de Banco de Dados
Azure SQL Database: Banco de dados gerenciado em PaaS.

Cosmos DB: Banco NoSQL globalmente distribuído.

Azure Database for MySQL/PostgreSQL: Opções open-source gerenciadas.

9. Azure Kubernetes Service (AKS)
Orquestração de contêineres Kubernetes gerenciada.

Escalabilidade automática e integração com CI/CD.

10. Azure Active Directory (Azure AD)
Gerenciamento de identidade e acesso (IAM).

SSO (Single Sign-On), MFA e governança de acesso.

11. Monitoramento e Segurança
Azure Monitor: Coleta logs e métricas (Application Insights, Log Analytics).

Azure Security Center: Proteção contra ameaças e compliance.

Backup e Site Recovery: Recuperação de desastres (DR).

12. Modelos de Implantação
Infraestrutura como Código (IaC): ARM Templates, Terraform, Bicep.

Azure DevOps: Pipelines para CI/CD.

Benefícios da Arquitetura do Azure
Escalabilidade: Ajuste dinâmico de recursos (vertical/horizontal).

Resiliência: Zonas de disponibilidade e conjuntos de failover.

Segurança: Isolamento de rede, criptografia e conformidade (GDPR, ISO 27001).

Gerenciamento Simplificado: Painel único (Azure Portal) e automação.

