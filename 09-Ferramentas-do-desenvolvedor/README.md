<div align="center">
  <h3>AWS CLI (Command Line Interface)</h3>
  <img src="../assets/ferramentas-do-desenvolvedor/Command Line Interface.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/cli/)

The AWS Command Line Interface (AWS CLI) is a unified tool that provides a consistent interface for interacting with all parts of Amazon Web Services.

- **Modelo:** Ferramenta (Client-side)
- **Híbrido:** ✅ (acessa recursos locais e AWS)
- **Totalmente gerenciado pela AWS:** ❌ (cliente instalado na máquina do usuário)
- **Sem servidor:** N/A (ferramenta local)
- **Escopo:** Global (acessa qualquer região da AWS)
- **Opera:** Interface de linha de comando para gerenciar recursos AWS
- **Shared Model:**
  -  🔹 AWS gerencia APIs e infraestrutura
  -  🔹 Você gerencia comandos e credenciais
- **Características:** Automação, scripting, acesso via terminal
- **Palavras-chave:** CLI, linha de comando, automação, SDK
- **Exemplo:** É como um controle remoto para mandar comandos para sua nuvem AWS.
- 📝 **Como cai na prova:**
  -  🔹 “Quer automatizar tarefas na AWS via terminal...”
  -  🔹 “Qual ferramenta é usada para gerenciar AWS via linha de comando?”
- 💰 **Como é cobrado:**
  -  🔹 Gratuito

---

<div align="center">
  <h3>AWS CodeBuild</h3>
  <img src="../assets/ferramentas-do-desenvolvedor/CodeBuild.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/codebuild/)

Build and test code with automatic scaling, and pay only for the build minutes you use.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de build – Serviço de build contínuo e integração contínua (CI)
- **Shared Model:**
  -  🔹 AWS gerencia infraestrutura de build
  -  🔹 Você gerencia projetos, código e configurações
- **Características:** Build automático, escalável, integração com CodePipeline
- **Palavras-chave:** Build, CI, integração contínua, compilação automática
- **Exemplo:** É como uma fábrica que transforma seu código em programas prontos para usar, sem você se preocupar com máquinas.
- 📝 **Como cai na prova:**
  -  🔹 “Você precisa compilar código automaticamente na nuvem...”
  -  🔹 “Qual serviço executa build CI/CD gerenciado?”
- 💰 **Como é cobrado:**
  -  🔹 Por minutos de build e tipo de ambiente

---

<div align="center">
  <h3>AWS CodePipeline</h3>
  <img src="../assets/ferramentas-do-desenvolvedor/CodePipeline.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/codepipeline/)

AWS CodePipeline automates the build, test, and deploy phases of your release process each time a code change occurs.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de orquestração – Pipeline de entrega contínua (CD)
- **Shared Model:**
  -  🔹 AWS gerencia a infraestrutura e execução do pipeline
  -  🔹 Você configura etapas e integrações
- **Características:** Automatiza build, teste e deploy
- **Palavras-chave:** Pipeline, CI/CD, automação, entrega contínua
- **Exemplo:** É como uma linha de montagem automática que leva seu código do desenvolvimento até a produção.
- 📝 **Como cai na prova:**
  -  🔹 “Quer automatizar deploys e testes...”
  -  🔹 “Qual serviço cria pipeline CI/CD na AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Por número de execuções de pipeline

---

<div align="center">
  <h3>AWS X-Ray</h3>
  <img src="../assets/ferramentas-do-desenvolvedor/X Ray.png" alt="img" width="100"><br>
</div><br>

[Documentação](https://aws.amazon.com/pt/xray/)

AWS X-Ray helps you debug and analyze your microservices applications with request tracing so you can find the root cause of issues and performance bottlenecks.

- **Modelo:** PaaS
- **Híbrido:** ✅
- **Totalmente gerenciado pela AWS:** ✅
- **Sem servidor:** ✅
- **Escopo:** Regional
- **Opera:** Nível de aplicação – Análise e rastreamento de aplicações distribuídas
- **Shared Model:**
  -  🔹 AWS gerencia coleta e processamento de dados
  -  🔹 Você integra SDKs e monitora traces
- **Características:** Debug, performance, visualização de requisições
- **Palavras-chave:** Tracing, monitoramento, performance, debugging
- **Exemplo:** É como um raio-X que vê dentro do funcionamento das suas aplicações para achar problemas.
- 📝 **Como cai na prova:**
  -  🔹 “Quer monitorar e debugar aplicações distribuídas...”
  -  🔹 “Qual serviço ajuda a rastrear requisições na AWS?”
- 💰 **Como é cobrado:**
  -  🔹 Por número de traces coletados e dados analisados
