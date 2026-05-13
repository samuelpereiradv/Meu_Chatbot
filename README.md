# 📚 Chatbot Inteligente – Especialista em Disney

## 🧠 Visão Geral
Chatbot baseado em IA desenvolvido com **LangChain** e **Groq (LLaMA 3.3)**, projetado para atuar como um pesquisador especializado na The Walt Disney Company.  
O sistema responde exclusivamente dentro de um escopo definido, garantindo consistência e controle nas respostas.

---

## ⚙️ Tecnologias Utilizadas
- Python  
- LangChain  
- Groq API (LLaMA 3.3)  
- Processamento de Linguagem Natural (NLP)

---

## 🎯 Funcionalidades
- Geração de respostas contextuais sobre a Disney  
- Restrição de escopo com validação de perguntas  
- Interação via terminal (CLI)  
- Definição de persona com regras específicas  

---

## 🧩 Arquitetura
- Uso de **SystemMessage** para definir comportamento e regras  
- Uso de **HumanMessage** para entrada do usuário  
- Integração com LLM via Groq para geração de respostas  

---

## ▶️ Como Executar

```bash
pip install langchain langchain-groq
python chatbot.py
