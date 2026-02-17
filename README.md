# 🤖 Assistente de RH e Legislação - Varginha & CLT 🍦📊

## 📋 Sobre o Projeto
Este repositório foi desenvolvido para o desafio de projeto **"Criando um Chatbot Baseado em Conteúdo de PDFs 🍦📊"** da **Digital Innovation One (DIO)**. O objetivo principal foi aplicar conceitos de **RAG (Retrieval-Augmented Generation)** utilizando o **Azure AI Foundry** para transformar documentos estáticos em uma base de conhecimento interativa e consultiva.

O assistente atua como um especialista em **Recursos Humanos e Legislação**, integrando dados da legislação federal (**CLT**) com o **Estatuto do Servidor de Varginha** e diversas **Normas Regulamentadoras (NRs)**.

## 📂 Estrutura do Repositório
* **`/inputs`**: Arquivos PDF utilizados como base de conhecimento (CLT, Estatuto de Varginha e NRs).
* **`/screenshots`**: Registros visuais das etapas de configuração e validação do chatbot.

## 🛠️ Tecnologias Utilizadas
* **Azure AI Foundry**: Orquestração da solução de IA.
* **GPT-4o**: Modelo de linguagem para processamento de respostas.
* **Azure AI Search (Plano Gratuito F)**: Motor de busca e indexação.
* **Busca Híbrida**: Combinação de vetores e palavras-chave para alta precisão.

## 📈 Processo e Desafios Superados
O projeto processou um volume total de **14,5 MB** de conteúdo jurídico, resultando em um índice de **1.351 documentos fragmentados** para facilitar a busca semântica.

### 🚧 Insights Técnicos:
1.  **Ingestão de Dados**: Uso de **modo anônimo** para superar instabilidades de cache na interface do Azure e concluir a indexação.
2.  **Segurança e Identidade**: Diagnóstico de restrições de **Managed Identity** no provisionamento de Web Apps, validando a solução via Playground.
3.  **Controle de Custos**: Monitoramento da assinatura para garantir operação dentro do nível **Gratuito (F)**.

## 🚀 Resultados e Evidências
O chatbot demonstrou alta precisão técnica ao responder sobre temas como o adicional de insalubridade da **NR-15**, baseando-se no salário mínimo regional.

---

### 📸 Galeria de Execução

#### 1. Arquitetura e Configuração
Configuração do modelo GPT-4o e definição das instruções de sistema para o assistente de RH.
![Arquitetura e Configuração](screenshots/Arquitetura%20e%20Configuração.png)

#### 2. Gestão de Ingestão (RAG)
Acompanhamento do processo de quebra, agrupamento e indexação dos documentos no Azure.
![Gestão de Ingestão](screenshots/Gestão%20de%20Ingestão%20(RAG).png)

#### 3. Validação do Banco de Dados
Visualização do índice concluído com os 1.351 fragmentos de dados prontos para busca.
![Validação do Banco de Dados](screenshots/Validação%20do%20Banco%20de%20Dados.png)

#### 4. O Bot em Ação
Exemplo de resposta consultiva do chatbot utilizando a base de dados de NRs.
![O Bot em Ação](screenshots/O%20Bot%20em%20Ação.png)

---
