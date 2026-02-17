# 🤖 Assistente de RH e Legislação - Varginha & CLT 🍦📊

## 📋 Sobre o Projeto
Este repositório foi desenvolvido para o desafio de projeto **"Criando um Chatbot Baseado em Conteúdo de PDFs 🍦📊"** da **Digital Innovation One (DIO)**. O objetivo principal foi aplicar conceitos de **RAG (Retrieval-Augmented Generation)** utilizando o **Azure AI Foundry** para transformar documentos estáticos em uma base de conhecimento interativa e consultiva.

O assistente foi configurado para atuar como um especialista em **Recursos Humanos e Legislação**, integrando dados da legislação federal (**CLT**) com o **Estatuto do Servidor de Varginha** e diversas **Normas Regulamentadoras (NRs)**.

## 📂 Estrutura do Repositório
* **`/inputs`**: Contém os 11 arquivos PDF utilizados como base de conhecimento (CLT, Estatuto de Varginha e NRs principais).
* **`/screenshots`**: Registros visuais das etapas de configuração, indexação e testes do chatbot.

## 🛠️ Tecnologias Utilizadas
* **Azure AI Foundry**: Plataforma utilizada para a orquestração da solução de IA.
* **GPT-4o**: Modelo de linguagem de última geração para processamento de respostas.
* **Azure AI Search (Plano Gratuito F)**: Motor de busca e indexação de documentos.
* **Busca Híbrida**: Combinação de vetores e palavras-chave para garantir máxima precisão nas respostas.

## 📈 Processo e Desafios Superados
O projeto processou um volume total de **14,5 MB** de conteúdo jurídico, resultando em um índice de **1.351 documentos fragmentados** para facilitar a busca semântica.

### 🚧 Insights Técnicos:
1.  **Ingestão de Dados**: Foi necessário utilizar o **modo anônimo** do navegador para superar instabilidades de cache na interface do Azure e concluir com sucesso as etapas de indexação.
2.  **Segurança e Identidade**: Durante o provisionamento do Web App, foram identificadas restrições de **Managed Identity** (Código 400), optando-se pela validação funcional via Playground para assegurar a integridade do projeto.
3.  **Controle de Custos**: Monitoramento ativo da assinatura Azure para garantir que o projeto operasse dentro do nível **Gratuito (F)**.

## 🚀 Resultados
O chatbot demonstrou alta precisão técnica, conseguindo diferenciar normas de esferas distintas e responder sobre temas complexos, como o adicional de insalubridade da **NR-15**, citando corretamente que o cálculo é baseado no salário mínimo da região.

---

### 📸 Galeria de Evidências (Screenshots)

| Descrição | Arquivo |
| :--- | :--- |
| **Configuração do Assistente** | `screenshots/Arquitetura e Configuração.jpg` |
| **Status da Ingestão** | `screenshots/Gestão de Ingestão (RAG).png` |
| **Índice de Pesquisa Concluído** | `Validação do Banco de Dados.png` |
| **Validação Técnica (Chat)** | `O Bot em Ação.png` |

---
