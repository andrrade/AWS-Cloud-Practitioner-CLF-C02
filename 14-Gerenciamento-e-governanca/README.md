### **AWS Auto Scaling**

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de infraestrutura – Ajuste automático da capacidade de recursos
- **Shared Model:**
-  🔹 AWS gerencia monitoramento e execução do scaling
-  🔹 Você define políticas e limites
- 
- **Características:** Escala recursos automaticamente, otimiza custos e performance
- 
- **Palavras-chave:** Auto Scaling, ajuste automático, elasticidade
- 
- **Exemplo:** É como um termostato que liga ou desliga o ar condicionado para deixar a temperatura ideal.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer ajustar automaticamente capacidade de servidores...”
-  🔹 “Qual serviço escala recursos conforme demanda?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito; paga pelos recursos escalados

---

### **AWS CloudFormation**

- **Modelo:** IaaS/PaaS (infra como código)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de infraestrutura – Provisionamento automatizado via templates
- 
- **Shared Model:**
-  🔹 AWS executa criação e gerenciamento dos recursos
-  🔹 Você cria templates e configurações
- 
- **Características:** Infraestrutura como código, repetibilidade, automação
- 
- **Palavras-chave:** IaC, templates, automação, infraestrutura
- 
- **Exemplo:** É como um roteiro que diz para a AWS quais recursos criar, sem fazer manualmente.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer automatizar criação de recursos AWS...”
-  🔹 “Qual serviço usa templates para infraestrutura?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito; paga pelos recursos provisionados

---

### **AWS CloudTrail**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional (logs) / Global (controle)
- **Opera:** Nível de segurança – Registro e auditoria de ações na conta AWS
- 
- **Shared Model:**
-  🔹 AWS coleta e armazena logs
-  🔹 Você analisa e responde a eventos
- 
- **Características:** Auditoria, compliance, monitoramento de API calls
- 
- **Palavras-chave:** Logs, auditoria, segurança, compliance
- 
- **Exemplo:** É como uma câmera de segurança que grava tudo que acontece na sua conta AWS.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer monitorar ações e mudanças na conta AWS...”
-  🔹 “Qual serviço registra chamadas de API e atividades?”
- 
- 💰 **Como é cobrado:**
-  🔹 Primeiro 90 dias gratuitos; depois por volume de logs

---

### **Amazon CloudWatch**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de monitoramento – Métricas, logs e alarmes para recursos e aplicações
- 
- **Shared Model:**
-  🔹 AWS coleta métricas e logs
-  🔹 Você configura alarmes e dashboards
- 
- **Características:** Monitoramento em tempo real, alertas, dashboards
- 
- **Palavras-chave:** Métricas, logs, monitoramento, alarmes
- 
- **Exemplo:** É como um painel que mostra a saúde e funcionamento da sua nuvem.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer monitorar desempenho e receber alertas...”
-  🔹 “Qual serviço monitora recursos AWS?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por métricas, logs e alarmes usados

---

### **AWS Compute Optimizer**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de recomendação – Sugestões para otimização de recursos computacionais
- 
- **Shared Model:**
-  🔹 AWS analisa uso e sugere melhorias
-  🔹 Você aplica recomendações
- 
- **Características:** Otimização de custos e performance
- 
- **Palavras-chave:** Otimização, recomendação, custos, performance
- 
- **Exemplo:** É como um consultor que sugere a máquina ideal para seu uso, economizando dinheiro.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer recomendações para otimizar uso de servidores...”
-  🔹 “Qual serviço sugere ajustes para reduzir custos?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **AWS Config**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de compliance – Monitoramento e auditoria da configuração dos recursos
- 
- **Shared Model:**
-  🔹 AWS coleta histórico e estado atual
-  🔹 Você define regras e avalia conformidade
- 
- **Características:** Auditoria de configuração, compliance, histórico
- 
- **Palavras-chave:** Compliance, auditoria, configuração, governança
- 
- **Exemplo:** É como um inspetor que verifica se tudo na sua nuvem está configurado direitinho.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer monitorar mudanças e compliance dos recursos...”
-  🔹 “Qual serviço verifica conformidade de configuração?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por recursos avaliados e regras usadas

---

### **AWS Control Tower**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global (contas AWS)
- **Opera:** Nível de governança – Configuração automática de multi-contas com melhores práticas
- 
- **Shared Model:**
-  🔹 AWS configura contas, políticas e governança
-  🔹 Você gerencia usuários e workloads
- 
- **Características:** Multi-contas, governança automática, segurança
- 
- **Palavras-chave:** Governança, multi-conta, automação, segurança
- 
- **Exemplo:** É como uma torre de controle que organiza e protege várias contas AWS da sua empresa.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer governar várias contas AWS facilmente...”
-  🔹 “Qual serviço ajuda na gestão multi-contas com segurança?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito (paga-se pelos recursos usados nas contas)

---

### **AWS Health Dashboard**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global
- **Opera:** Nível de serviço – Informações personalizadas sobre status da AWS
- 
- **Shared Model:**
-  🔹 AWS fornece status e notificações
-   🔹 Você monitora alertas e eventos
- 
- **Características:** Status da AWS, notificações de eventos e manutenções
- 
- **Palavras-chave:** Status, incidentes, notificações
- 
- **Exemplo:** É como um painel que avisa se algo na AWS está com problema e pode afetar seus serviços.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer saber status e incidentes da AWS que afetam seus recursos...”
-  🔹 “Qual serviço oferece alertas personalizados da AWS?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **AWS License Manager**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de governança – Gerenciamento de licenças de software
- 
- **Shared Model:**
-  🔹 AWS gerencia controle de licenças
-   🔹 Você controla uso e compliance
- 
- **Características:** Controle de licenças, compliance, redução de custos
- 
- **Palavras-chave:** Licença, compliance, software
- 
- **Exemplo:** É como um gerente que controla quantas licenças de software sua empresa está usando.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer gerenciar licenças de software na nuvem...”
-  🔹 “Qual serviço ajuda no controle de licenças?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **Console de Gerenciamento da AWS**

- **Modelo:** SaaS (interface web)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** N/A
- **Escopo:** Global
- **Opera:** Nível de interface – Painel web para gerenciar todos os serviços AWS
- 
- **Shared Model:**
-  🔹 AWS oferece interface e APIs
-   🔹 Você usa para controlar e configurar recursos
- 
- **Características:** Interface gráfica, controle completo, dashboards
- 
- **Palavras-chave:** Console, web, gerenciamento
- 
- **Exemplo:** É como o painel de controle do carro, onde você vê e mexe em tudo da AWS.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer gerenciar serviços AWS via web...”
-  🔹 “Qual ferramenta é o console AWS?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **AWS Organizations**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global
- **Opera:** Nível de gestão – Gerenciamento centralizado de múltiplas contas AWS
- 
- **Shared Model:**
-  🔹 AWS gerencia organização e políticas
-   🔹 Você cria unidades e gerencia contas
- 
- **Características:** Multi-conta, consolidação financeira, políticas de segurança
- 
- **Palavras-chave:** Multi-conta, organização, governança
- 
- **Exemplo:** É como um chefe que organiza várias contas da AWS da sua empresa em um lugar só.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer gerenciar várias contas AWS e políticas...”
-  🔹 “Qual serviço organiza multi-contas?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **AWS Service Catalog**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de governança – Catálogo de produtos aprovados para uso na AWS
- 
- **Shared Model:**
-  🔹 AWS gerencia infraestrutura do catálogo
-   🔹 Você cria e controla produtos aprovados
- 
- **Características:** Padronização, governança, automação
- 
- **Palavras-chave:** Catálogo, governança, padronização
- 
- **Exemplo:** É como um menu onde só aparecem os pratos aprovados para pedir na AWS.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer padronizar recursos usados na empresa...”
-  🔹 “Qual serviço cria catálogo de produtos aprovados?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **Service Quotas**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Global
- **Opera:** Nível de controle – Gerenciamento de limites (quotas) dos serviços AWS
- 
- **Shared Model:**
-  🔹 AWS monitora limites padrão
-   🔹 Você solicita aumentos e monitora uso
- 
- **Características:** Controle de quotas, monitoramento, solicitações
- 
- **Palavras-chave:** Limites, quotas, gerenciamento
- 
- **Exemplo:** É como um fiscal que controla quantos recursos você pode usar na AWS.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer gerenciar limites de uso dos serviços...”
-  🔹 “Qual serviço controla quotas AWS?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito

---

### **AWS Systems Manager**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de gerenciamento – Administração e automação de recursos AWS
- 
- **Shared Model:**
-  🔹 AWS gerencia infraestrutura e ferramentas
-   🔹 Você gerencia comandos e políticas
- 
- **Características:** Gerenciamento centralizado, automação, patches, inventário
- 
- **Palavras-chave:** Gerenciamento, automação, inventário
- 
- **Exemplo:** É como um painel que ajuda a cuidar e organizar seus servidores e aplicativos.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer gerenciar e automatizar recursos AWS...”
-  🔹 “Qual serviço centraliza gerenciamento de infraestrutura?”
- 
- 💰 **Como é cobrado:**
-  🔹 Gratuito; paga pelos recursos usados
