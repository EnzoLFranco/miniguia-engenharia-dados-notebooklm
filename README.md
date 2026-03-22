# 📊 Miniguia de Estudos: Engenharia de Dados com NotebookLM

## 📖 Contexto e Objetivos
Este repositório apresenta o resultado de um desafio prático da **DIO**, onde utilizei o **NotebookLM** como uma ferramenta de aprendizagem ativa. O tema escolhido foi **Engenharia de Dados**, com o objetivo de consolidar conceitos fundamentais sobre a estruturação de fluxos de dados modernos, arquitetura de medalhões e boas práticas de documentação técnica.

**Objetivos de Estudo:**
* Compreender os pilares da Engenharia de Dados moderna.
* Explorar a implementação de camadas de dados (Medallion Architecture).
* Definir padrões de documentação e governança para pipelines.

---

## 🔍 Curadoria de Fontes
Para alimentar o NotebookLM e gerar o conhecimento deste guia, selecionei as seguintes fontes de referência:

1. [Fundamentos de Engenharia de Dados](https://pt.scribd.com/document/916804425/Fundamentos-de-Engenharia-de-Dados) - Visão geral sobre a profissão e fluxos básicos.
2. [O Livro Completo da Engenharia de Dados](https://pt.slideshare.net/slideshow/o-livro-completo-da-engenharia-de-dadospdf/257268748) - Um guia abrangente sobre ferramentas e ecossistema.
3. [Modern Data Engineering Playbook (Thoughtworks)](https://www.thoughtworks.com/content/dam/thoughtworks/documents/whitepaper/tw_modern_data_engineering_playbook_PT-BR.pdf) - Estratégias avançadas e práticas de mercado para engenharia moderna.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"
Documentar o processo de extração de informação é essencial para mostrar a maturidade técnica no uso de IAs.

### Prompts Estratégicos Testados:
* **Prompt 1 (Documentação):** *"Quais são as boas práticas para documentar uma pipeline?"*
    * **Resultado:** A IA destacou a importância de diagramas de linhagem (lineage), dicionários de dados e versionamento de esquemas.
* **Prompt 2 (Implementação):** *"Como implementar as camadas Bronze, Silver e Gold no Python?"*
    * **Resultado:** O retorno focou no uso de bibliotecas como PySpark e Delta Lake para garantir a transição de dados brutos para dados prontos para negócio.

### 🛠️ Troubleshooting (Desafios):
* **Dificuldade:** Ao perguntar sobre as camadas no Python, a resposta inicial foi muito teórica.
* **Solução:** Refinei o prompt pedindo exemplos práticos de bibliotecas específicas (como Pandas ou Spark) para que o código gerado fosse aplicável à realidade técnica.

---

## 🚀 Miniguia de Estudo (Entrega Final)

### 📝 Resumo Estruturado: Arquitetura de Medalhão
* **Camada Bronze (Raw):** Armazenamento dos dados em seu estado original, sem transformações. Foco em fidelidade à fonte.
* **Camada Silver (Trusted):** Dados limpos, filtrados e padronizados. Aqui ocorre a validação de tipos e a remoção de duplicatas.
* **Camada Gold (Refined):** Dados agregados e modelados para o consumo final (BI, Machine Learning ou relatórios executivos).

### 📕 Glossário de Conceitos
* **Pipeline de Dados:** Sequência de processos que movem e transformam dados de um sistema para outro.
* **Medallion Architecture:** Design de camadas para organizar logicamente os dados dentro de um Data Lakehouse.
* **Linhagem de Dados:** O rastreamento da origem do dado e de todas as transformações pelas quais ele passou.

### 📑 Prompts Reutilizáveis para Revisão
> Utilize estes prompts no seu NotebookLM para revisar o conteúdo futuramente:
1. "Crie um quiz de 5 perguntas de múltipla escolha sobre os conceitos de ETL e camadas de dados explicados nos documentos."
2. "Gere um resumo em tópicos sobre as vantagens do uso de Cloud Computing para Big Data conforme as fontes fornecidas."

---

## 🛠️ Tecnologias Utilizadas
* [NotebookLM](https://notebooklm.google.com/)
* [GitHub](https://github.com/)
