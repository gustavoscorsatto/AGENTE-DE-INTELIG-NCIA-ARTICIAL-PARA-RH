# 🤖 Agente de Inteligência Artificial para área de Recursos Humanos (RH)

Este repositório apresenta o desenvolvimento de um **Agente de Inteligência Artificial aplicado à área de Recursos Humanos**, capaz de **analisar respostas textuais abertas**, realizar **pré-processamento dos dados**, gerar **resumos automáticos** e **classificar perfis profissionais** em áreas organizacionais específicas.

O projeto utiliza técnicas de **Processamento de Linguagem Natural (PLN)** aliadas a **Large Language Models (LLMs)**, integrados via **LangChain** e **Llama (Meta)**, com foco em **apoio à tomada de decisão em contextos corporativos e acadêmicos**.


## 📌 Contexto do Projeto

Em processos seletivos e avaliações internas, é comum a utilização de **perguntas discursivas** para identificar o perfil comportamental e profissional dos respondentes. Contudo, a análise manual dessas respostas é:

- Demorada;
- Subjetiva;
- Pouco escalável;
- Difícil de padronizar.

Este projeto propõe uma solução automatizada que **estrutura, resume e interpreta respostas textuais**, oferecendo ao RH um **insight inicial sobre a área organizacional mais compatível com o perfil analisado**.

---

## 🎯 Objetivos

- Automatizar a análise de respostas abertas em processos de RH;
- Aplicar pré-processamento textual para melhoria da qualidade dos dados;
- Utilizar LLMs para **sumarização e interpretação semântica**;
- Classificar perfis com base em **palavras-chave e viés linguístico**;
- Reduzir o esforço manual e a subjetividade inicial das análises.

---

## 🧠 Funcionamento do Agente

O agente foi estruturado em **etapas bem definidas**, refletidas diretamente no notebook do projeto.

### 1️⃣ Pré-processamento dos Dados
- Importação de dados via **CSV**;
- Limpeza e normalização textual;
- Preparação das respostas para análise semântica.

### 2️⃣ Integração com LLM (Llama – Meta)
- Configuração da API do **Llama**;
- Uso de modelos de linguagem para interpretação contextual;
- Integração via **LangChain**, permitindo maior modularidade e controle do fluxo.

### 3️⃣ Análise Semântica e Sumarização
- Extração das ideias centrais das respostas;
- Geração de resumos objetivos;
- Redução de ruído textual mantendo o significado original.

### 4️⃣ Classificação por Área Organizacional
A partir do conteúdo textual, o agente sugere a área com maior aderência ao perfil identificado.


## 🏢 Áreas Avaliadas pelo Modelo

O agente classifica os perfis nas seguintes áreas:

- **📊 Projetos**  
  Foco em planejamento, organização, execução, metas e prazos.

- **📣 Marketing**  
  Linguagem associada à criatividade, comunicação, estratégias e público-alvo.

- **👥 Recursos Humanos**  
  Ênfase em pessoas, empatia, trabalho em equipe, gestão e clima organizacional.

- **🎓 Capacitação**  
  Orientação para aprendizado contínuo, desenvolvimento profissional e formação.


## 🧩 Tecnologias Utilizadas

- **Python**
- **Jupyter Notebook**
- **LangChain**
- **Llama (Meta AI)**
- **Processamento de Linguagem Natural (PLN)**
- **CSV para entrada de dados**
- **APIs de modelos de linguagem**


## ⚠️ Considerações Éticas e LGPD

- O agente **não substitui decisões humanas**;
- Atua exclusivamente como **ferramenta de apoio**;
- Não realiza inferência de dados sensíveis;
- Deve ser utilizado em conformidade com a **LGPD**;
- Recomenda-se validação humana em todas as etapas decisórias.


## 🚧 Limitações do Projeto

- Dependência da qualidade das respostas textuais;
- Possível viés linguístico do modelo;
- Classificação baseada em padrões semânticos, não em competências técnicas diretas;
- Resultados são **indicativos**, não determinísticos.


## 🚀 Possíveis Extensões Futuras

- Inclusão de novas áreas organizacionais;
- Treinamento com dados reais anonimizados;
- Análise de sentimento integrada;
- Interface gráfica ou dashboard para RH;
- Integração com sistemas de recrutamento (ATS);
- Exportação automática de relatórios.


## 👨‍💻 Autores

Projeto desenvolvido em contexto **acadêmico e experimental**, com foco na aplicação prática de **Inteligência Artificial no ambiente corporativo**, especialmente em **Recursos Humanos**.


