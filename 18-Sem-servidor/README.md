<div align="center">
  <h3>AWS Fargate</h3>
  <img src="../assets/sem-servidor/Fargate.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/fargate/)

AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes (EKS).

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de computação – Execução de containers sem gerenciar servidores
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura, servidores e escala
  -  🔹 Você gerencia containers e aplicações
- **Características:** Serverless para containers, escalável, integra com ECS/EKS
- **Palavras-chave:** Containers, serverless, escalabilidade
- **Exemplo:** É como um restaurante que cuida da cozinha inteira para você só se preocupar com o prato.
- 📝 **Como cai na prova:**
  -  🔹 “Quer rodar containers sem gerenciar servidores...”
  -  🔹 “Qual serviço executa containers serverless?”
- 💰 **Como é cobrado:**
  -  🔹 Por CPU, memória e tempo de execução do container

---

<div align="center">
  <img src="../assets/sem-servidor/Lambda.png" alt="img" width="100"><br>
  <h3>AWS Lambda</h3>
</div><br>

[Documentação](https://aws.amazon.com/pt/lambda/)

AWS Lambda is a serverless compute service for running code without having to provision or manage servers. You pay only for the compute time you consume.

- **Modelo:** FaaS (Function as a Service)
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de computação – Execução de funções (código) em resposta a eventos
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura, execução e escala
  -  🔹 Você escreve funções e define triggers
- **Características:** Serverless, baseado em eventos, escalável automaticamente
- **Palavras-chave:** Funções, serverless, eventos
- **Exemplo:** É como um ajudante que só aparece quando você precisa fazer uma tarefa rápida.
- 📝 **Como cai na prova:**
  -  🔹 “Quer executar código sem servidor e pagar só pelo uso...”
  -  🔹 “Qual serviço AWS é função serverless?”
- 💰 **Como é cobrado:**
  - 🔹 Por número de invocações e tempo de execução
