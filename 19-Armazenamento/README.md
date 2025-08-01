<div align="center">
  <h3>AWS Backup</h3>
  <img src="../assets/armazenamento/Backup.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/backup/)

AWS Backup lets you centrally manage and automate backups across AWS services and third-party applications.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de backup – Centraliza e automatiza backup de serviços AWS
- **Shared Model:**
  -  🔹 AWS gerencia execução e armazenamento dos backups
  -  🔹 Você configura políticas e restaurações
- **Características:** Automação, backup centralizado, compliance
- **Palavras-chave:** Backup, automação, recuperação
- **Exemplo:** É como uma caixa onde você guarda cópias de segurança para não perder nada importante.
- 📝 **Como cai na prova:**
  -  🔹 “Quer automatizar backup na AWS...”
  -  🔹 “Qual serviço centraliza backups?”
- 💰 **Como é cobrado:**
  -  🔹 Por volume de dados armazenados e transferidos

---

<div align="center">
  <h3>Amazon Elastic Block Store (Amazon EBS)</h3>
  <img src="../assets/armazenamento/Elastic Block Store.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/ebs/)

Amazon Elastic Block Store (EBS) is an easy to use, high-performance cloud Storage Area Network (SAN).

- **Modelo:** IaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌
- **Escopo:** Zonal (AZ)
- **Opera:** Nível de armazenamento – Blocos de armazenamento para instâncias EC2
- **Shared Model:**
  -  🔹 AWS gerencia hardware e rede
  -  🔹 Você gerencia volumes e snapshots
- **Características:** Persistente, baixa latência, attach/detach em EC2
- **Palavras-chave:** Storage em bloco, EC2, persistência
- **Exemplo:** É como um HD que você conecta no computador na nuvem.
- 📝 **Como cai na prova:**
  -  🔹 “Quer armazenamento rápido para EC2...”
  -  🔹 “Qual serviço é storage em bloco?”
- 💰 **Como é cobrado:**
  -  🔹 Por GB provisionado e IOPS (em alguns tipos)

---

<div align="center">
  <h3>Amazon Elastic File System (Amazon EFS)</h3>
  <img src="../assets/armazenamento/EFS.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/efs/)

Amazon EFS is a simple, serverless, elastic, set-and-forget file system that automatically grows and shrinks as you add and remove files with no need for management or provisioning. You can use Amazon EFS with Amazon EC2, AWS Lambda, Amazon ECS, Amazon EKS and other AWS compute instances, or with on-premises servers.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Sistema de arquivos compartilhado e escalável
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura e escalabilidade
  -  🔹 Você monta e gerencia permissões
- **Características:** Multi-AZ, escalável, compatível NFS
- **Palavras-chave:** Sistema de arquivos, compartilhado, escalável
- **Exemplo:** É como uma pasta gigante que vários computadores podem usar ao mesmo tempo.
- 📝 **Como cai na prova:**
  -  🔹 “Quer storage compartilhado para múltiplas instâncias...”
  -  🔹 “Qual serviço oferece sistema de arquivos gerenciado?”
- 💰 **Como é cobrado:**
  -  🔹 Por GB consumido

---

<div align="center">
  <h3>AWS Elastic Disaster Recovery</h3>
  <img src="../assets/armazenamento/Elastic Disaster Recovery.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/disaster-recovery/)

AWS Elastic Disaster Recovery (AWS DRS) minimizes downtime and data loss with fast, reliable recovery of on-premises and cloud-based applications.

- **Modelo:** SaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de recuperação – Recuperação de desastres para servidores on-premises e cloud
- **Shared Model:**
  -  🔹 AWS gerencia orquestração e replicação
  -  🔹 Você configura planos e recupera servidores
- **Características:** Replicação contínua, failover rápido
- **Palavras-chave:** Disaster recovery, replicação, failover
- **Exemplo:** É como um plano B que liga o backup rápido se algo der errado com seu servidor.
- 📝 **Como cai na prova:**
  -  🔹 “Quer plano de recuperação de desastre...”
  -  🔹 “Qual serviço faz replicação para failover?”
- 💰 **Como é cobrado:**
  -  🔹 Por número de servidores protegidos e uso

---

<div align="center">
  <h3>Amazon FSx</h3>
  <img src="../assets/armazenamento/FSx.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/fsx/)

Amazon FSx makes it easy and cost effective to launch, run, and scale feature-rich, high-performance file systems in the cloud. It supports a wide range of workloads with its reliability, security, scalability, and broad set of capabilities. Amazon FSx is built on the latest AWS compute, networking, and disk technologies to provide high performance and lower TCO. And as a fully managed service, it handles hardware provisioning, patching, and backups -- freeing you up to focus on your applications, your end users, and your business.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Sistemas de arquivos otimizados (Windows, Lustre)
- **Shared Model:**
  -  🔹 AWS gerencia hardware e software
  -  🔹 Você usa e configura acesso
- **Características:** Performance alta, compatível SMB/NFS, especializado
- **Palavras-chave:** Sistema de arquivos, Windows, Lustre
- **Exemplo:** É como um drive de rede rápido e especializado para tipos diferentes de dados.
- 📝 **Como cai na prova:**
  -  🔹 “Quer sistema de arquivos gerenciado para Windows ou HPC...”
  -  🔹 “Qual serviço oferece FSx?”
- 💰 **Como é cobrado:**
  -  🔹 Por GB provisionado e throughput

---

<div align="center">
  <h3>Amazon S3</h3>
  <img src="../assets/armazenamento/Simple Storage Service.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/s3/)

Amazon Simple Storage Service (Amazon S3) is storage for the internet. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere on the web.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Armazenamento de objetos escalável e durável
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura e durabilidade
  -  🔹 Você gerencia dados e permissões
- **Características:** Alta durabilidade, escalabilidade, acesso via API
- **Palavras-chave:** Storage de objetos, escalável, durável
- **Exemplo:** É como um baú gigante onde você guarda fotos, vídeos e arquivos na nuvem.
- 📝 **Como cai na prova:**
  -  🔹 “Quer armazenamento simples e escalável...”
  -  🔹 “Qual serviço é storage de objetos?”
- 💰 **Como é cobrado:**
  -  🔹 Por GB armazenado, requests e transferência

---

<div align="center">
  <h3>Amazon S3 Glacier</h3>
  <img src="../assets/armazenamento/Simple Storage Service Glacier.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/s3/storage-classes/glacier/)

Long-term, secure, durable Amazon S3 object storage classes for data archiving, starting at $1 per terabyte per month.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Arquivamento e backup de dados com baixo custo
- **Shared Model:**
  -  🔹 AWS gerencia armazenamento e segurança
  -  🔹 Você gerencia políticas de recuperação
- **Características:** Baixo custo, latência alta para recuperação, arquivamento
- **Palavras-chave:** Arquivamento, baixo custo, backup
- **Exemplo:** É como um porão onde você guarda arquivos antigos que quase nunca usa.
- 📝 **Como cai na prova:**
  -  🔹 “Quer arquivamento barato para dados antigos...”
  -  🔹 “Qual serviço é para arquivar dados a longo prazo?”
- 💰 **Como é cobrado:**
  -  🔹 Por GB armazenado e custo de recuperação

---

<div align="center">
  <h3>AWS Storage Gateway</h3>
  <img src="../assets/armazenamento/Storage Gateway.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/storagegateway/)

AWS Storage Gateway is a service that connects an on-premises software appliance with cloud-based storage to provide seamless and secure integration between your on-premises IT environment and the AWS storage infrastructure in the AWS Cloud.

- **Modelo:** Híbrido (on-premises + nuvem)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Integra armazenamento local com AWS cloud
- **Shared Model:**
  -  🔹 AWS gerencia serviço na nuvem
  -  🔹 Você instala appliance local e configura
- **Características:** Cache local, backup, armazenamento híbrido
- **Palavras-chave:** Gateway, híbrido, armazenamento local + nuvem
- **Exemplo:** É como uma ponte que conecta seu armazenamento local ao baú gigante na nuvem.
- 📝 **Como cai na prova:**
  -  🔹 “Quer integrar storage local com AWS...”
  -  🔹 “Qual serviço conecta armazenamento on-premises e cloud?”
- 💰 **Como é cobrado:**
  -  🔹 Por uso de armazenamento na nuvem e tráfego
