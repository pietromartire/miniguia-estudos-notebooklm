<div align="center">
  <img src="header.png.png" alt="Banner: Estudos de Segurança Cibernética com IA - Projeto DIO" />
</div>
<br>

# Miniguia de Estudos: Inteligência Artificial na Prevenção a Fraudes e Segurança da Informação

> **Projeto prático focado na criação de um Caderno Temático no NotebookLM, unindo curadoria de conhecimento, pensamento crítico e Inteligência Artificial.**

---

## 🎯 Contexto e Objetivos

O cenário corporativo atual exige uma visão holística sobre a **Prevenção a Fraudes e a mitigação de riscos em Segurança da Informação**. Para endereçar esse desafio, o objetivo da criação deste projeto foi explorar como a Inteligência Artificial pode atuar como um assistente de estudo ativo na consolidação de disciplinas estratégicas. 

O material utiliza a **Zero Trust** e **Normas Globais** como pilares fundamentais para blindar ambientes, proteger dados e apoiar o dia a dia de operações de defesa e governança.

**Objetivos de Estudo:**
1. Compreender o panorama geral de riscos em Segurança da Informação e as principais metodologias de detecção de fraudes.
2. Aprofundar o estudo no ciclo de vida de identidades como controle técnico e mitigador primário contra ameaças internas e externas.
3. Testar a capacidade do NotebookLM de cruzar informações entre frameworks de mercado (NIST, COSO/ACFE) e guias focados em lógicas práticas de segurança.

---

## 📚 Curadoria de Fontes

Para garantir que a IA gerasse respostas com alta precisão técnica e sem alucinações, os seguintes documentos base (além de outras 42 fontes) foram enviados para o NotebookLM:

1. **[NIST Cybersecurity Framework 2.0 (PDF)](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf)**: Documentação oficial sobre as funções de governar, identificar, proteger, detectar, responder e recuperar em incidentes de segurança.
2. **[Cloudflare: Fundamentos de IAM e Zero Trust](https://www.cloudflare.com/learning/access-management/what-is-identity-and-access-management/)**: Artigo técnico detalhando o controle de acesso e o ciclo de vida de credenciais para redução da superfície de ataque.
3. **[CISA: Cybersecurity Risk Metrics Guide (PDF)](https://www.cisa.gov/sites/default/files/publications/Cyber_Risk_Economics_Guide_1.pdf)**: Material prático focado na mensuração e economia do risco cibernético geral.
4. **[Guide to Fraud Detection Rules (SEON)](https://seon.io/resources/guides/guide-to-fraud-detection-rules/)**: Guia sobre a estruturação de lógicas de detecção de fraudes, detalhando verificações de velocidade, regras estáticas e modelos de *scoring*.
5. **[Fraud Risk Management Guide (ACFE/COSO)](https://www.acfe.com/fraud-resources/fraud-risk-tools---coso/fraud-risk-management-guide)**: Diretrizes oficiais para o estabelecimento de um programa abrangente de gestão de risco de fraude corporativa.

---

## 🛠️ Engenharia de Prompts

Durante a exploração do NotebookLM, apliquei diferentes técnicas de *prompt engineering* para refinar os resultados. Abaixo estão documentados os testes, as falhas e as estratégias bem-sucedidas:

### Teste 1: Cenário Geral
* **Prompt Inicial:** *"Como evitar fraudes e riscos de segurança da informação?"*
* **Dificuldade:** A resposta gerada foi muito ampla e superficial, sem focar nas medidas técnicas e preventivas esperadas para uma operação de segurança.
* **Prompt Refinado:** *"Aja como um Especialista com visão ampla às áreas de segurança. Com base EXCLUSIVAMENTE nos documentos do NIST e da ACFE, explique de forma extremamente resumdia: como a implementação de controles e regras rígidas atuam diretamente na prevenção de fraudes internas e externas, listando 3 exemplos práticos."*
* **Resultado:** A IA cruzou os dados de governança geral com a aplicação técnica, trazendo conceitos claros e coerentes, resposta abaixo:

*Como especialista, afirmo que regras e controles rígidos previnem fraudes ao analisar dados em tempo real para aprovar, revisar ou bloquear ações suspeitas. Exemplos práticos incluem: bloqueio de IPs em listas de restrição, pontuação de risco para telefones descartáveis e limitação de tentativas de login simultâneas.*

### Teste 2: Criação de Cenários e Lógicas de Detecção
* **Prompt:** *"Com base no guia da SEON, crie um cenário onde a falta de regras de velocidade (velocity checks) no login gerou um incidente de Account Takeover crítico, e como você mitigaria esse risco utilizando um sistema de scoring."*
* **Resultado:** A IA simulou um ataque automatizado de preenchimento de credenciais e formulou uma resposta analítica e executiva baseada na documentação estudada.

---

## 📖 Miniguia de Estudo

### Resumo 
O estudo exige o domínio de frameworks complexos e cenários práticos. Este projeto demonstrou que a Inteligência Artificial atua como um verdadeiro motor de aprendizagem ativa, facilitando a compreensão de grandes normas e que os maiores incidentes não vem apenas de ataques puramente técnicos. Ao integrar a IA na rotina de estudos, torna-se possível cruzar dinamicamente lógicas de segurança, transformando a teoria em simulações interativas que aceleram o desenvolvimento analítico e preparam o profissional para lidar proativamente com ameaças reais.

### 🧠 Glossário de Conceitos

* **Segurança da Informação:** Prática de proteger dados e sistemas contra acesso, uso, divulgação, interrupção, modificação ou destruição não autorizados.
* **Prevenção a Fraudes (Governança COSO):** Estruturação de um ambiente com avaliações preventivas e detectivas para mitigar riscos de perdas financeiras ou de dados por ações intencionais (internas ou externas).
* **Tríade CIA (Confidencialidade, Integridade e Disponibilidade):** Os três pilares fundamentais da Segurança da Informação. Eles garantem que os dados estejam protegidos contra acessos indevidos, não sejam alterados por pessoas não autorizadas e estejam sempre acessíveis para o uso legítimo.
* **Gestão de Riscos:** Processo estratégico e contínuo de identificação, avaliação e mitigação de ameaças e vulnerabilidades (tanto internas quanto externas). O objetivo é equilibrar a proteção dos ativos com as necessidades operacionais e financeiras do negócio.
* **Defesa em Profundidade (Defense in Depth):** Abordagem arquitetônica que aplica múltiplas camadas sobrepostas de controles de segurança (tecnológicos, administrativos e físicos). Dessa forma, se um controle falhar ou for burlado por um fraudador, outras camadas ainda protegerão a informação.

### 🔄 Prompts Reutilizáveis para Revisão

Para futuras sessões de estudo com este Notebook, utilize os seguintes prompts no NotebookLM:

1. *"Atue como um especialista em segurança. Crie uma tabela explicando como a quebra de cada pilar da Tríade CIA (Confidencialidade, Integridade e Disponibilidade) pode resultar em diferentes tipos de fraude corporativa, usando os materiais fornecidos como base."*
2. *"Elabore um cenário prático onde uma organização falhou na sua Gestão de Riscos Cibernéticos e sofreu um incidente. Em seguida, me faça perguntas sobre como eu estruturaria uma solução aplicando o conceito de Defesa em Profundidade (Defense in Depth)."*
3. *"Gere 5 perguntas de múltipla escolha de nível intermediário focadas na integração entre os princípios básicos de Segurança da Informação e as diretrizes de prevenção a fraudes do framework COSO, para testar meu conhecimento."*

---
*Projeto desenvolvido para o desafio de aprendizagem ativa com IA da DIO, consolidando fundamentos aplicados à rotina de segurança cibernética corporativa.*

🔗 **Acesse o caderno original:** [Meu Caderno no NotebookLM](https://notebooklm.google.com/notebook/b4090d7e-7add-4a30-8266-2f6bc4144aa1)
