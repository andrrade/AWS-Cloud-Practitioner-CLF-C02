### **AWS Backup**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de backup – Centraliza e automatiza backup de serviços AWS
- 
- **Shared Model:**
-  🔹 AWS gerencia execução e armazenamento dos backups
-   🔹 Você configura políticas e restaurações
- 
- **Características:** Automação, backup centralizado, compliance
- 
- **Palavras-chave:** Backup, automação, recuperação
- 
- **Exemplo:** É como uma caixa onde você guarda cópias de segurança para não perder nada importante.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer automatizar backup na AWS...”
-  🔹 “Qual serviço centraliza backups?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por volume de dados armazenados e transferidos

---

### **Amazon Elastic Block Store (Amazon EBS)**

- **Modelo:** IaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌
- **Escopo:** Zonal (AZ)
- **Opera:** Nível de armazenamento – Blocos de armazenamento para instâncias EC2
- 
- **Shared Model:**
-  🔹 AWS gerencia hardware e rede
-   🔹 Você gerencia volumes e snapshots
- 
- **Características:** Persistente, baixa latência, attach/detach em EC2
- 
- **Palavras-chave:** Storage em bloco, EC2, persistência
- 
- **Exemplo:** É como um HD que você conecta no computador na nuvem.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer armazenamento rápido para EC2...”
-   🔹 “Qual serviço é storage em bloco?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por GB provisionado e IOPS (em alguns tipos)

---

### **Amazon Elastic File System (Amazon EFS)**

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Sistema de arquivos compartilhado e escalável
- 
- **Shared Model:**
-  🔹 AWS gerencia infraestrutura e escalabilidade
-   🔹 Você monta e gerencia permissões
- 
- **Características:** Multi-AZ, escalável, compatível NFS
- 
- **Palavras-chave:** Sistema de arquivos, compartilhado, escalável
- 
- **Exemplo:** É como uma pasta gigante que vários computadores podem usar ao mesmo tempo.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer storage compartilhado para múltiplas instâncias...”
-   🔹 “Qual serviço oferece sistema de arquivos gerenciado?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por GB consumido

---

### **AWS Elastic Disaster Recovery**

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de recuperação – Recuperação de desastres para servidores on-premises e cloud
- 
- **Shared Model:**
-  🔹 AWS gerencia orquestração e replicação
-   🔹 Você configura planos e recupera servidores
- 
- **Características:** Replicação contínua, failover rápido
- 
- **Palavras-chave:** Disaster recovery, replicação, failover
- 
- **Exemplo:** É como um plano B que liga o backup rápido se algo der errado com seu servidor.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer plano de recuperação de desastre...”
-   🔹 “Qual serviço faz replicação para failover?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por número de servidores protegidos e uso

---

### **Amazon FSx**

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Sistemas de arquivos otimizados (Windows, Lustre)
- 
- **Shared Model:**
-  🔹 AWS gerencia hardware e software
-   🔹 Você usa e configura acesso
- 
- **Características:** Performance alta, compatível SMB/NFS, especializado
- 
- **Palavras-chave:** Sistema de arquivos, Windows, Lustre
- 
- **Exemplo:** É como um drive de rede rápido e especializado para tipos diferentes de dados.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer sistema de arquivos gerenciado para Windows ou HPC...”
-   🔹 “Qual serviço oferece FSx?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por GB provisionado e throughput

---

### **Amazon S3**

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Armazenamento de objetos escalável e durável
- 
- **Shared Model:**
-  🔹 AWS gerencia infraestrutura e durabilidade
-   🔹 Você gerencia dados e permissões
- 
- **Características:** Alta durabilidade, escalabilidade, acesso via API
- 
- **Palavras-chave:** Storage de objetos, escalável, durável
- 
- **Exemplo:** É como um baú gigante onde você guarda fotos, vídeos e arquivos na nuvem.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer armazenamento simples e escalável...”
-   🔹 “Qual serviço é storage de objetos?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por GB armazenado, requests e transferência

---

### **Amazon S3 Glacier**

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Arquivamento e backup de dados com baixo custo
- 
- **Shared Model:**
-  🔹 AWS gerencia armazenamento e segurança
-   🔹 Você gerencia políticas de recuperação
- 
- **Características:** Baixo custo, latência alta para recuperação, arquivamento
- 
- **Palavras-chave:** Arquivamento, baixo custo, backup
- 
- **Exemplo:** É como um porão onde você guarda arquivos antigos que quase nunca usa.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer arquivamento barato para dados antigos...”
-   🔹 “Qual serviço é para arquivar dados a longo prazo?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por GB armazenado e custo de recuperação

---

### **AWS Storage Gateway**

- **Modelo:** Híbrido (on-premises + nuvem)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Integra armazenamento local com AWS cloud
- 
- **Shared Model:**
-  🔹 AWS gerencia serviço na nuvem
-   🔹 Você instala appliance local e configura
- 
- **Características:** Cache local, backup, armazenamento híbrido
- 
- **Palavras-chave:** Gateway, híbrido, armazenamento local + nuvem
- 
- **Exemplo:** É como uma ponte que conecta seu armazenamento local ao baú gigante na nuvem.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer integrar storage local com AWS...”
-   🔹 “Qual serviço conecta armazenamento on-premises e cloud?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por uso de armazenamento na nuvem e tráfego
