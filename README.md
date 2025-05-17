# 🔧 JSTechBot — Seu Técnico Digital de Bolso

Bem-vindo ao **JSTechBot**, um chatbot técnico inteligente desenvolvido com a **API Gemini** do Google. Ele é capaz de ajudar técnicos e usuários com dúvidas sobre computadores, notebooks, impressoras e celulares, de um jeito direto, prático e inteligente. 👨‍🔧💬

---

## 🎯 Objetivo

Criar um **assistente técnico automatizado** que responda dúvidas comuns de manutenção, configuração e problemas técnicos, com linguagem clara, rápida e contextual.

---

## 🚀 Tecnologias Utilizadas

- 🐍 **Python**
- 📘 **Google Colab**
- 🤖 **Google Generative AI (Gemini Pro)**
- 🌐 API via `google-generativeai`
- 💬 Armazenamento de contexto da conversa

---

## 🧠 Prompt de Identidade

> “Você é um técnico especializado em manutenção de computadores, notebooks, impressoras e celulares. Responda sempre de forma clara e objetiva.”

Esse prompt define a personalidade do JSTechBot: técnico, direto, prestativo.

---

## 🧩 Funcionalidades

✅ Respostas técnicas detalhadas  
✅ Histórico de conversa com contexto  
✅ Diagnóstico de erros (ex: códigos de impressora, tela, BIOS)  
✅ Sugestões de procedimentos e ferramentas  
✅ Expansível para interfaces web ou mobile  

---

## 💬 Exemplo de Conversa

```plaintext
🧑 Você: Erro E0 HP 2774  
🔧 JSTechBot: Esse erro está relacionado a cartuchos. Aqui estão as possíveis causas:
- Cartucho ausente, incompatível ou vazio
- Contatos sujos
- Falha interna da impressora
(Soluções passo a passo incluídas)

🧑 Você: Qual o modelo de cartucho dessa impressora?  
🔧 JSTechBot: HP 667 Preto e HP 667 Tricolor
 ```
---

📌 Estrutura do Código

conversa: lista que armazena o histórico (pergunta e resposta)

perguntar_ao_bot(pergunta): função que envia o prompt com histórico pro Gemini

generate_content(): método principal da API Gemini para gerar respostas

---

🔮 Próximos Passos

Criar uma interface web responsiva

Armazenar as conversas em banco de dados

Integrar com Telegram/WhatsApp

Adicionar imagens e vídeos nos retornos do bot

---

🙌 Contribuições

Contribuições são super bem-vindas! Se você é da área de manutenção ou IA, bora evoluir esse projeto juntas(os).

---

🧑‍💻 Feito por
Laís Máximo💻✨
Aluna de Análise e Desenvolvimento de Sistemas | Criadora do JSTechBot
