<div align="center">
  <img src="../assets/conteineres/Elastic Container Registry.png" alt="img" width="100"><br>
  <h3>Amazon Elastic Container Registry (Amazon ECR)</h3>
</div><br>

Amazon Elastic Container Registry (ECR) is a fully managed Docker container registry that makes it easy to store, share, and deploy container images.

[Documentação](https://aws.amazon.com/pt/ecr/)

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de armazenamento – Repositório de imagens de contêiner
- **Shared Model:**
  -  🔹 AWS gerencia armazenamento, segurança e disponibilidade
  -  🔹 Você gerencia imagens e permissões de acesso
- **Características:** Repositório privado, integração com ECS, EKS, controle de versão
- **Palavras-chave:** Registro, imagens, contêiner, Docker
- **Exemplo:** É como um armário seguro onde você guarda as figurinhas (imagens) dos seus contêineres.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa armazenar e versionar imagens de contêiner...”
  -  🔹 “Qual serviço gerencia imagens para ECS e EKS?”
- 💰 **Como é cobrado:**
  -  🔹 Por armazenamento usado e transferência de dados

---

<div align="center">
  <img src="../assets/conteineres/Elastic Container Service.png" alt="img" width="100"><br>
  <h3>Amazon Elastic Container Service (Amazon ECS)</h3>
</div><br>

Amazon Elastic Container Service (Amazon ECS) provides a fully managed container service solution that’s easy to use, scalable, secure, and reliable.

[Documentação](https://aws.amazon.com/pt/ecs/)

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌ (tem integração com Fargate para serverless)
- **Escopo:** Regional
- **Opera:** Nível de orquestração – Gerenciamento de contêineres Docker
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura, balanceamento e escalabilidade
  -  🔹 Você gerencia tarefas, definições e clusters
- **Características:** Orquestração, integração com AWS, escalabilidade
- **Palavras-chave:** Orquestração, contêiner, Docker, clusters
- **Exemplo:** É como um maestro que coordena várias caixas (contêineres) para tocar juntas.
- 📝 **Como cai na prova:**
  -  🔹 “Quer orquestrar contêineres Docker...”
  -  🔹 “Qual serviço gerencia execução de contêineres?”
- 💰 **Como é cobrado:**
  -  🔹 Pelo uso dos recursos subjacentes (EC2 ou Fargate)

---

<div align="center">
  <img src="../assets/conteineres/Elastic Kubernetes Service.png" alt="img" width="100"><br>
  <h3>Amazon Elastic Kubernetes Service (Amazon EKS)</h3>
</div><br>

Amazon Elastic Kubernetes Service (EKS) is a managed service and certified Kubernetes conformant to run Kubernetes on AWS and on-premises.

[Documentação](https://aws.amazon.com/pt/eks/)

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ❌ (com suporte para Fargate também)
- **Escopo:** Regional
- **Opera:** Nível de orquestração – Kubernetes gerenciado para contêineres
- **Shared Model:**
  -  🔹 AWS gerencia o plano de controle Kubernetes
  -  🔹 Você gerencia os nós, pods e configurações
- **Características:** Kubernetes gerenciado, escalabilidade, alta disponibilidade
- **Palavras-chave:** Kubernetes, orquestração, contêineres, clusters
- **Exemplo:** É como um time de treinadores especializados que cuida dos contêineres para você.
- 📝 **Como cai na prova:**
  -  🔹 “Quer usar Kubernetes sem gerenciar o plano de controle...”
  -  🔹 “Qual serviço oferece Kubernetes gerenciado?”
- 💰 **Como é cobrado:**
  -  🔹 Por hora do plano de controle + recursos usados nos nós
