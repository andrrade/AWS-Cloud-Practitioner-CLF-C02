<div align="center">
  <h3>AWS Auto Scaling</h3>
  <img src="../assets/gerenciamento-e-governanca/EC2 Auto Scaling.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/ec2/autoscaling/)

Amazon EC2 Auto Scaling helps you maintain application availability and define how to scale Amazon EC2 capacity to meet the demands of your application.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de infraestrutura – Ajuste automático da capacidade de recursos
- **Shared Model:**
  -  🔹 AWS gerencia monitoramento e execução do scaling
  -  🔹 Você define políticas e limites
- **Características:** Escala recursos automaticamente, otimiza custos e performance
- **Palavras-chave:** Auto Scaling, ajuste automático, elasticidade
- **Exemplo:** É como um termostato que liga ou desliga o ar condicionado para deixar a temperatura ideal.
- 📝 **Como cai na prova:**
  -  🔹 “Quer ajustar automaticamente capacidade de servidores...”
  -  🔹 “Qual serviço escala recursos conforme demanda?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito; paga pelos recursos escalados

---

<div align="center">
  <h3>AWS CloudFormation</h3>
  <img src="../assets/gerenciamento-e-governanca/CloudFormation.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/cloudformation/)

AWS CloudFormation is an infrastructure as code (IaC) service that allows you to easily model, provision, and manage AWS and third-party resources.

- **Modelo:** IaaS/PaaS (infra como código)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de infraestrutura – Provisionamento automatizado via templates
- **Shared Model:**
  -  🔹 AWS executa criação e gerenciamento dos recursos
  -  🔹 Você cria templates e configurações
- **Características:** Infraestrutura como código, repetibilidade, automação
- **Palavras-chave:** IaC, templates, automação, infraestrutura
- **Exemplo:** É como um roteiro que diz para a AWS quais recursos criar, sem fazer manualmente.
- 📝 **Como cai na prova:**
  -  🔹 “Quer automatizar criação de recursos AWS...”
  -  🔹 “Qual serviço usa templates para infraestrutura?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito; paga pelos recursos provisionados

---

<div align="center">
  <h3>AWS CloudTrail</h3>
  <img src="../assets/gerenciamento-e-governanca/CloudTrail.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/cloudtrail/)

AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional (logs) / Global (controle)
- **Opera:** Nível de segurança – Registro e auditoria de ações na conta AWS
- **Shared Model:**
  -  🔹 AWS coleta e armazena logs
  -  🔹 Você analisa e responde a eventos
- **Características:** Auditoria, compliance, monitoramento de API calls
- **Palavras-chave:** Logs, auditoria, segurança, compliance
- **Exemplo:** É como uma câmera de segurança que grava tudo que acontece na sua conta AWS.
- 📝 **Como cai na prova:**
  -  🔹 “Quer monitorar ações e mudanças na conta AWS...”
  -  🔹 “Qual serviço registra chamadas de API e atividades?”
- 💰 **Como é cobrado:**
  -  🔹 Primeiro 90 dias gratuitos; depois por volume de logs

---

<div align="center">
  <h3>Amazon CloudWatch</h3>
  <img src="../assets/gerenciamento-e-governanca/CloudWatch.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/cloudwatch/)

Amazon CloudWatch is a monitoring service built for DevOps engineers, developers, site reliability engineers (SREs), IT managers, and product owners.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de monitoramento – Métricas, logs e alarmes para recursos e aplicações
- **Shared Model:**
  -  🔹 AWS coleta métricas e logs
  -  🔹 Você configura alarmes e dashboards
- **Características:** Monitoramento em tempo real, alertas, dashboards
- **Palavras-chave:** Métricas, logs, monitoramento, alarmes
- **Exemplo:** É como um painel que mostra a saúde e funcionamento da sua nuvem.
- 📝 **Como cai na prova:**
  -  🔹 “Quer monitorar desempenho e receber alertas...”
  -  🔹 “Qual serviço monitora recursos AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Por métricas, logs e alarmes usados

---

<div align="center">
  <h3>AWS Compute Optimizer</h3>
  <img src="../assets/gerenciamento-e-governanca/Compute Optimizer.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/compute-optimizer/)

AWS Compute Optimizer recommends more efficient AWS compute resources for your workloads to reduce costs and improve performance.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de recomendação – Sugestões para otimização de recursos computacionais
- **Shared Model:**
  -  🔹 AWS analisa uso e sugere melhorias
  -  🔹 Você aplica recomendações
- **Características:** Otimização de custos e performance
- **Palavras-chave:** Otimização, recomendação, custos, performance
- **Exemplo:** É como um consultor que sugere a máquina ideal para seu uso, economizando dinheiro.
- 📝 **Como cai na prova:**
  -  🔹 “Quer recomendações para otimizar uso de servidores...”
  -  🔹 “Qual serviço sugere ajustes para reduzir custos?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>AWS Config</h3>
  <img src="../assets/gerenciamento-e-governanca/Config.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/config/)

AWS Config is a config tool that helps you assess, audit, and evaluate the configurations and relationships of your resources.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de compliance – Monitoramento e auditoria da configuração dos recursos
- **Shared Model:**
  -  🔹 AWS coleta histórico e estado atual
  -  🔹 Você define regras e avalia conformidade
- **Características:** Auditoria de configuração, compliance, histórico
- **Palavras-chave:** Compliance, auditoria, configuração, governança
- **Exemplo:** É como um inspetor que verifica se tudo na sua nuvem está configurado direitinho.
- 📝 **Como cai na prova:**
  -  🔹 “Quer monitorar mudanças e compliance dos recursos...”
  -  🔹 “Qual serviço verifica conformidade de configuração?”
- 💰 **Como é cobrado:**
  -  🔹 Por recursos avaliados e regras usadas

---

<div align="center">
  <h3>AWS Control Tower</h3>
  <img src="../assets/gerenciamento-e-governanca/Control Tower.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/controltower/)

AWS Control Tower provides a single location to set up a well-architected, multi-account environment to govern your AWS workloads with rules for security, operations, and compliance.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global (contas AWS)
- **Opera:** Nível de governança – Configuração automática de multi-contas com melhores práticas
- **Shared Model:**
  -  🔹 AWS configura contas, políticas e governança
  -  🔹 Você gerencia usuários e workloads
- **Características:** Multi-contas, governança automática, segurança
- **Palavras-chave:** Governança, multi-conta, automação, segurança
- **Exemplo:** É como uma torre de controle que organiza e protege várias contas AWS da sua empresa.
- 📝 **Como cai na prova:**
  -  🔹 “Quer governar várias contas AWS facilmente...”
  -  🔹 “Qual serviço ajuda na gestão multi-contas com segurança?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito (paga-se pelos recursos usados nas contas)

---

<div align="center">
  <h3>AWS Health Dashboard</h3>
  <img src="../assets/gerenciamento-e-governanca/Personal Health Dashboard.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/premiumsupport/technology/aws-health/)

View important events and changes affecting your AWS environment

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global
- **Opera:** Nível de serviço – Informações personalizadas sobre status da AWS
- **Shared Model:**
  -  🔹 AWS fornece status e notificações
  -   🔹 Você monitora alertas e eventos
- **Características:** Status da AWS, notificações de eventos e manutenções
- **Palavras-chave:** Status, incidentes, notificações
- **Exemplo:** É como um painel que avisa se algo na AWS está com problema e pode afetar seus serviços.
- 📝 **Como cai na prova:**
  -  🔹 “Quer saber status e incidentes da AWS que afetam seus recursos...”
  -  🔹 “Qual serviço oferece alertas personalizados da AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>AWS License Manager</h3>
  <img src="../assets/gerenciamento-e-governanca/License Manager.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/license-manager/)

AWS License Manager makes it easier for you to manage your software licenses from vendors, such as Microsoft, SAP, Oracle, and IBM, across AWS and on-premises environments.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de governança – Gerenciamento de licenças de software
- **Shared Model:**
  -  🔹 AWS gerencia controle de licenças
  -   🔹 Você controla uso e compliance
- **Características:** Controle de licenças, compliance, redução de custos
- **Palavras-chave:** Licença, compliance, software
- **Exemplo:** É como um gerente que controla quantas licenças de software sua empresa está usando.
- 📝 **Como cai na prova:**
  -  🔹 “Quer gerenciar licenças de software na nuvem...”
  -  🔹 “Qual serviço ajuda no controle de licenças?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>Console de Gerenciamento da AWS (Management Console)</h3>
  <img src="../assets/gerenciamento-e-governanca/Management Console.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/console/)

The AWS Management Console is a web application that comprises and refers to a broad collection of service consoles for managing AWS resources.

- **Modelo:** SaaS (interface web)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** N/A
- **Escopo:** Global
- **Opera:** Nível de interface – Painel web para gerenciar todos os serviços AWS
- **Shared Model:**
  -  🔹 AWS oferece interface e APIs
  -   🔹 Você usa para controlar e configurar recursos
- **Características:** Interface gráfica, controle completo, dashboards
- **Palavras-chave:** Console, web, gerenciamento
- **Exemplo:** É como o painel de controle do carro, onde você vê e mexe em tudo da AWS.
- 📝 **Como cai na prova:**
  -  🔹 “Quer gerenciar serviços AWS via web...”
  -  🔹 “Qual ferramenta é o console AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>AWS Organizations</h3>
  <img src="../assets/gerenciamento-e-governanca/Organizations.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/organizations/)

AWS Organizations enables centralized cloud account management as you grow and scale your AWS resources.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global
- **Opera:** Nível de gestão – Gerenciamento centralizado de múltiplas contas AWS
- **Shared Model:**
  -  🔹 AWS gerencia organização e políticas
  -   🔹 Você cria unidades e gerencia contas
- **Características:** Multi-conta, consolidação financeira, políticas de segurança
- **Palavras-chave:** Multi-conta, organização, governança
- **Exemplo:** É como um chefe que organiza várias contas da AWS da sua empresa em um lugar só.
- 📝 **Como cai na prova:**
  -  🔹 “Quer gerenciar várias contas AWS e políticas...”
  -  🔹 “Qual serviço organiza multi-contas?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>Service Catalog</h3>
  <img src="../assets/gerenciamento-e-governanca/Service Catalog.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/servicecatalog/)

AWS Service Catalog helps you create and manage IaC templates approved for use on AWS so anyone can discover approved, self-service cloud resources.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de governança – Catálogo de produtos aprovados para uso na AWS
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura do catálogo
  -   🔹 Você cria e controla produtos aprovados
- **Características:** Padronização, governança, automação
- **Palavras-chave:** Catálogo, governança, padronização
- **Exemplo:** É como um menu onde só aparecem os pratos aprovados para pedir na AWS.
- 📝 **Como cai na prova:**
  -  🔹 “Quer padronizar recursos usados na empresa...”
  -  🔹 “Qual serviço cria catálogo de produtos aprovados?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>Service Quotas</h3>
  <img src="../assets/gerenciamento-e-governanca/AWS-logo.png" alt="img" width="100"><br>
</div><br>

With Service Quotas, you can view and manage your quotas for AWS services from a central location. Quotas, also referred to as limits in AWS services, are the maximum values for the resources, actions, and items in your AWS account.

[Documentação](https://docs.aws.amazon.com/servicequotas/latest/userguide/intro.html)

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global
- **Opera:** Nível de controle – Gerenciamento de limites (quotas) dos serviços AWS
- **Shared Model:**
  -  🔹 AWS monitora limites padrão
  -   🔹 Você solicita aumentos e monitora uso
- **Características:** Controle de quotas, monitoramento, solicitações
- **Palavras-chave:** Limites, quotas, gerenciamento
- **Exemplo:** É como um fiscal que controla quantos recursos você pode usar na AWS.
- 📝 **Como cai na prova:**
  -  🔹 “Quer gerenciar limites de uso dos serviços...”
  -  🔹 “Qual serviço controla quotas AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>AWS Systems Manager</h3>
  <img src="../assets/gerenciamento-e-governanca/Systems Manager.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/systems-manager/)

AWS Systems Manager provides an operations console and APIs for centralized application and resource management in hybrid environments.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de gerenciamento – Administração e automação de recursos AWS
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura e ferramentas
  -   🔹 Você gerencia comandos e políticas 
- **Características:** Gerenciamento centralizado, automação, patches, inventário
- **Palavras-chave:** Gerenciamento, automação, inventário
- **Exemplo:** É como um painel que ajuda a cuidar e organizar seus servidores e aplicativos.
- 📝 **Como cai na prova:**
  -  🔹 “Quer gerenciar e automatizar recursos AWS...”
  -  🔹 “Qual serviço centraliza gerenciamento de infraestrutura?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito; paga pelos recursos usados

---

<div align="center">
  <h3>AWS Trusted Advisor</h3>
  <img src="../assets/gerenciamento-e-governanca/Trusted Advisor.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/premiumsupport/technology/trusted-advisor/)

AWS Support provides support for users of Amazon Web Services.

- **Modelo:** SaaS  
- **Híbrido:** ✅  
- **Totalmente gerenciado pela AWS:** ✅  
- **Sem servidor:** ✅  
- **Escopo:** Regional (a depender da verificação feita)  
- **Opera:** Nível de gerenciamento – Análise de boas práticas operacionais  
- **Shared Model:**  
  - 🔹 AWS fornece as recomendações e infraestrutura  
  - 🔹 Você aplica ou não as sugestões  
- **Características:**  
  - Recomendações de segurança  
  - Performance  
  - Economia  
  - Tolerância a falhas  
  - Limites de serviço  
- **Palavras-chave:**  
  - Otimização  
  - Recomendações  
  - Boas práticas  
  - Segurança  
  - Custos  
- **Exemplo:**  
  - É como um consultor virtual que revisa sua conta AWS e dá dicas do que melhorar.  
- 📝 **Como cai na prova:**  
  - 🔹 “Quer ajuda para seguir boas práticas de segurança e reduzir custos...”  
  - 🔹 “Ferramenta que analisa sua conta e recomenda melhorias...”  
- 💰 **Como é cobrado:**  
  - 🔹 Algumas verificações são gratuitas  
  - 🔹 Verificações adicionais com plano de suporte Business ou Enterprise

---

<div align="center">
  <h3>AWS Well-Architected Tool</h3>
  <img src="../assets/gerenciamento-e-governanca/Well Architected Tool.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/well-architected-tool/)

Learn architectural best practices, improve your workloads, and track progress over time with the AWS Well-Architected Tool

- **Modelo:** SaaS  
- **Híbrido:** ✅  
- **Totalmente gerenciado pela AWS:** ✅  
- **Sem servidor:** ✅  
- **Escopo:** Regional  
- **Opera:** Nível de arquitetura – Planejamento e avaliação de workloads  
- **Shared Model:**  
  - 🔹 AWS oferece o framework e a ferramenta  
  - 🔹 Você avalia e ajusta sua arquitetura  
- **Características:**  
  - Avaliação estruturada de workloads  
  - Recomendações por pilar  
  - Insights para melhoria contínua  
- **Palavras-chave:**  
  - Arquitetura  
  - Avaliação  
  - Melhoria contínua  
  - Pilares  
- **Pilares do Framework:**  
  - **Operações:** Automação, monitoramento  
  - **Segurança:** Proteção de dados, controle de acesso  
  - **Confiabilidade:** Recuperação, escalabilidade  
  - **Performance:** Eficiência, otimização  
  - **Otimização de custos:** Uso eficiente de recursos  
  - **Sustentabilidade:** Redução de impacto ambiental  
- **Exemplo:**  
  - É como uma checklist que mostra se sua aplicação segue boas práticas arquitetônicas e onde pode melhorar.  
- 📝 **Como cai na prova:**  
  - 🔹 “Quer verificar se sua arquitetura está bem planejada...”  
  - 🔹 “Ferramenta para avaliar workloads com base em pilares...”  
- 💰 **Como é cobrado:**  
  - 🔹 Gratuito
  