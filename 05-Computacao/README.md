<div align="center">
  <h3>AWS Batch</h3>
  <img src="../assets/computacao/Batchh.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/batch/)

AWS Batch allows developers, scientists, and engineers to efficiently process hundreds of thousands of batch and machine learning computing jobs on AWS.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de job batch (execução de jobs em lote)
- **Shared Model:**
  -  🔹 AWS gerencia a infraestrutura e escalabilidade
  -  🔹 Você define jobs e gerencia scripts
- **Características:** Processamento em lote, escalável, automatizado
- **Palavras-chave:** Batch, processamento em lote, jobs, escalabilidade
- **Exemplo:** É como uma fábrica que processa várias tarefas de uma vez, quando você manda a lista.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa executar jobs batch automaticamente e em escala...”
  -  🔹 “Qual serviço automatiza processamento em lote na AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Por recursos computacionais usados (vCPU, memória) e tempo de execução

---

<div align="center">
  <h3>Amazon EC2</h3>
  <img src="../assets/computacao/EC2.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/ec2/)

Amazon EC2 provides secure, resizable compute in the cloud, offering the broadest choice of processor, storage, networking, OS, and purchase model.

- **Modelo:** IaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ❌ (você gerencia instâncias)
- **Sem servidor:** ❌
- **Escopo:** Zonal (AZ)
- **Opera:** Nível de instância – máquinas virtuais configuráveis
- **Shared Model:**
  -  🔹 AWS cuida da infraestrutura física e rede
  -  🔹 Você gerencia sistema operacional, software e segurança
- **Características:** Instâncias flexíveis, controle total, escalável
- **Palavras-chave:** VM, instância, IaaS, computação flexível
- **Exemplo:** É como alugar um computador na nuvem para você usar como quiser.
- 📝 **Como cai na prova:**
  -  🔹 “Você quer servidores virtuais configuráveis...”
  -  🔹 “Qual serviço oferece máquinas virtuais?”
- 💰 **Como é cobrado:**
  -  🔹 Por hora, segundo uso de CPU, memória, e tipo da instância

---

<div align="center">
  <h3>AWS Elastic Beanstalk</h3>
  <img src="../assets/computacao/Elastic Beanstalk.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/elasticbeanstalk/)

AWS Elastic Beanstalk helps you deploy and manage web applications with capacity provisioning, app health monitoring, and more.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌
- **Escopo:** Regional
- **Opera:** Nível de aplicação – Plataforma para deploy automático
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura, escalabilidade e balanceamento
  -  🔹 Você cuida do código e configuração
- **Características:** Deploy fácil, gerência automática de infraestrutura
- **Palavras-chave:** Deploy, aplicação, plataforma gerenciada
- **Exemplo:** É como um ajudante que coloca seu site no ar sem você precisar configurar servidores.
- 📝 **Como cai na prova:**
  -  🔹 “Quer implantar apps sem se preocupar com infraestrutura...”
  -  🔹 “Qual serviço facilita deploy e gerenciamento?”
- 💰 **Como é cobrado:**
  -  🔹 Pelo uso dos recursos subjacentes (EC2, storage, etc.)

---

<div align="center">
  <h3>Amazon Lightsail</h3>
  <img src="../assets/computacao/Lightsail.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/lightsail/)

Amazon Lightsail is an easy-to-use virtual private server (VPS) that offers simple management of cloud resources such as containers, at low, predictable prices.

- **Modelo:** IaaS (mais simplificado)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅ (infraestrutura simplificada)
- **Sem servidor:** ❌
- **Escopo:** Zonal
- **Opera:** Nível de instância – VPS fácil para projetos simples
- **Shared Model:**
  -  🔹 AWS gerencia a infraestrutura e rede
  -  🔹 Você gerencia instância e software
- **Características:** VPS simples, pacote fixo, fácil de usar
- **Palavras-chave:** VPS, servidor simples, pacote fixo
- **Exemplo:** É como um computador na nuvem fácil de ligar e usar, sem complicação.
- 📝 **Como cai na prova:**
  -  🔹 “Quer VPS simples para projetos pequenos...”
  -  🔹 “Qual serviço oferece servidores fáceis de usar?”
- 💰 **Como é cobrado:**
  -  🔹 Mensalidade fixa pelo pacote escolhido

---

<div align="center">
  <h3>AWS Outposts</h3>
  <img src="../assets/computacao/Outposts family.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/outposts/)

Run AWS infrastructure and services on premises for a truly consistent hybrid experience.

- **Modelo:** IaaS + PaaS (hardware no local)
- **Híbrido:** ✅ (essencialmente híbrido)
- **Totalmente gerenciado pela AWS:** ✅ (infraestrutura AWS no local)
- **Sem servidor:** ❌
- **Escopo:** Local + Regional AWS
- **Opera:** Infraestrutura física local com integração à nuvem AWS
- **Shared Model:**
  -  🔹 AWS gerencia hardware e atualizações
  -  🔹 Você gerencia software e segurança local
- **Características:** Infra local com experiência AWS, baixa latência, integração
- **Palavras-chave:** Híbrido, on-premises, infraestrutura local
- **Exemplo:** É como ter a AWS dentro da sua empresa, perto dos seus equipamentos.
- 📝 **Como cai na prova:**
  -  🔹 “Quer rodar serviços AWS localmente com gestão da AWS...”
  -  🔹 “Qual solução traz AWS on-premises?”
- 💰 **Como é cobrado:**
  -  🔹 Por uso do hardware e serviços provisionados localmente
