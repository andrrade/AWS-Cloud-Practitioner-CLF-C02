### **AWS Batch**

<p align="center">
  <br>
  <img src="../assets/computacao/batch.png" alt="img">
</p>

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de job batch (execução de jobs em lote)
- **Shared Model:**
-  🔹 AWS gerencia a infraestrutura e escalabilidade
-  🔹 Você define jobs e gerencia scripts
- 
- **Características:** Processamento em lote, escalável, automatizado
- 
- **Palavras-chave:** Batch, processamento em lote, jobs, escalabilidade
- 
- **Exemplo:** É como uma fábrica que processa várias tarefas de uma vez, quando você manda a lista.
- 
- 📝 **Como cai na prova:**
-  🔹 “Você precisa executar jobs batch automaticamente e em escala...”
-  🔹 “Qual serviço automatiza processamento em lote na AWS?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por recursos computacionais usados (vCPU, memória) e tempo de execução

---

### **Amazon EC2**

<p align="center">
  <br>
  <img src="../assets/computacao/EC2.png" alt="img">
</p>

- **Modelo:** IaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ❌ (você gerencia instâncias)
- **Sem servidor:** ❌
- **Escopo:** Zonal (AZ)
- **Opera:** Nível de instância – máquinas virtuais configuráveis
- **Shared Model:**
-  🔹 AWS cuida da infraestrutura física e rede
-  🔹 Você gerencia sistema operacional, software e segurança
- 
- **Características:** Instâncias flexíveis, controle total, escalável
- 
- **Palavras-chave:** VM, instância, IaaS, computação flexível
- 
- **Exemplo:** É como alugar um computador na nuvem para você usar como quiser.
- 
- 📝 **Como cai na prova:**
-  🔹 “Você quer servidores virtuais configuráveis...”
-  🔹 “Qual serviço oferece máquinas virtuais?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por hora, segundo uso de CPU, memória, e tipo da instância

---

### **AWS Elastic Beanstalk**

<p align="center">
  <br>
  <img src="../assets/computacao/ElasticBeanstalk.png" alt="img">
</p>

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌
- **Escopo:** Regional
- **Opera:** Nível de aplicação – Plataforma para deploy automático
- **Shared Model:**
-  🔹 AWS gerencia infraestrutura, escalabilidade e balanceamento
-  🔹 Você cuida do código e configuração
- 
- **Características:** Deploy fácil, gerência automática de infraestrutura
- 
- **Palavras-chave:** Deploy, aplicação, plataforma gerenciada
- 
- **Exemplo:** É como um ajudante que coloca seu site no ar sem você precisar configurar servidores.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer implantar apps sem se preocupar com infraestrutura...”
-  🔹 “Qual serviço facilita deploy e gerenciamento?”
- 
- 💰 **Como é cobrado:**
-  🔹 Pelo uso dos recursos subjacentes (EC2, storage, etc.)

---

### **Amazon Lightsail**

<p align="center">
  <br>
  <img src="../assets/computacao/Lightsail.png" alt="img">
</p>

- **Modelo:** IaaS (mais simplificado)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅ (infraestrutura simplificada)
- **Sem servidor:** ❌
- **Escopo:** Zonal
- **Opera:** Nível de instância – VPS fácil para projetos simples
- **Shared Model:**
-  🔹 AWS gerencia a infraestrutura e rede
-  🔹 Você gerencia instância e software
- 
- **Características:** VPS simples, pacote fixo, fácil de usar
- 
- **Palavras-chave:** VPS, servidor simples, pacote fixo
- 
- **Exemplo:** É como um computador na nuvem fácil de ligar e usar, sem complicação.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer VPS simples para projetos pequenos...”
-  🔹 “Qual serviço oferece servidores fáceis de usar?”
- 
- 💰 **Como é cobrado:**
-  🔹 Mensalidade fixa pelo pacote escolhido

---

### **AWS Outposts**

<p align="center">
  <br>
  <img src="../assets/computacao/outpots.png" alt="img">
</p>

- **Modelo:** IaaS + PaaS (hardware no local)
- **Híbrido:** ✅ (essencialmente híbrido)
- **Totalmente gerenciado pela AWS:** ✅ (infraestrutura AWS no local)
- **Sem servidor:** ❌
- **Escopo:** Local + Regional AWS
- **Opera:** Infraestrutura física local com integração à nuvem AWS
- **Shared Model:**
-  🔹 AWS gerencia hardware e atualizações
-  🔹 Você gerencia software e segurança local
- 
- **Características:** Infra local com experiência AWS, baixa latência, integração
- 
- **Palavras-chave:** Híbrido, on-premises, infraestrutura local
- 
- **Exemplo:** É como ter a AWS dentro da sua empresa, perto dos seus equipamentos.
- 
- 📝 **Como cai na prova:**
-  🔹 “Quer rodar serviços AWS localmente com gestão da AWS...”
-  🔹 “Qual solução traz AWS on-premises?”
- 
- 💰 **Como é cobrado:**
-  🔹 Por uso do hardware e serviços provisionados localmente
