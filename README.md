# 🤖 Desafio DIO: Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

Este repositório faz parte da minha jornada de aprendizado na [Digital Innovation One (DIO)](https://www.dio.me/), onde estou estudando os fundamentos da Inteligência Artificial aplicada em ferramentas da Microsoft.

Neste desafio, utilizei o **Microsoft Copilot Studio** para criar um **Copiloto com Fluxo de Conversa Personalizado**, ajustando respostas com GenAI e aprendendo a lidar com tópicos e mensagens de erro.

---

## 🎯 Objetivo

> Criar um **Copiloto com Fluxo de Conversa Personalizado** no **Microsoft Copilot Studio**, contendo:
>
> - Um copiloto criado do zero (em branco);
> - Um tópico customizado com gatilhos e respostas;
> - Mensagem de erro personalizada para o tópico;
> - Ajuste de qualidade das respostas com uso de GenAI.

---

## 🛠️ Passo a Passo Realizado

### 1. Criar um Copiloto em Branco
- Acesse o [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/).
- Clique em **"Criar Copiloto"**.
- Escolha a opção **"Começar do zero"** (em branco), sem fluxos pré-definidos.

### 2. Criar e Configurar um Tópico
- No menu lateral, vá até **"Tópicos"** e clique em **"Novo Tópico"**.
- Dê um nome ao tópico (ex: `Dicas de Python`).
- Adicione frases de gatilho que ativam esse tópico (ex: "Como posso estudar Python?", "Dicas de materiais de graça.").
- No editor de fluxo, adicione uma **mensagem com a resposta padrão** para esse tema.

### 3. Personalizar Mensagem de Erro
- Ainda no fluxo do tópico, configure uma mensagem de erro (fallback).
- Essa mensagem será exibida caso o copiloto não entenda a entrada do usuário.

  **Exemplo de mensagem:**
  > "Desculpe, não entendi sua pergunta. Poderia reformular ou perguntar de outra forma?"

### 4. Ajustar a Qualidade da Resposta com GenAI
- No bloco de resposta, ative a opção para utilizar **GenAI (GPT)**.
- Escolha o estilo da resposta: curta, padrão ou mais elaborada.
- Teste variações para entender o comportamento do copiloto com diferentes níveis de resposta.

### 5. Testar o Copiloto
- Use a área de **teste do Copilot Studio** para interagir com o copiloto.
- Verifique se os gatilhos ativam o tópico correto, se a resposta está adequada e se a mensagem de erro aparece quando necessário.

---

## 📚 Aprendizados

- Como criar um fluxo de conversa funcional e amigável.
- A importância de prever erros e fornecer mensagens claras ao usuário.
- Como usar o GenAI para refinar e adaptar respostas.
- Como estruturar tópicos de forma lógica e intuitiva.

---

## ✅ Próximos Passos

- Criar múltiplos tópicos com fluxos ramificados.
- Integrar o copiloto com serviços externos via API.
- Publicar o copiloto em canais como Microsoft Teams, sites ou apps.

---

## 💡 Contribua

Se você também está aprendendo ou já tem experiência com o Microsoft Copilot Studio, fique à vontade para contribuir com sugestões, melhorias ou abrir issues!

Vamos evoluir juntos! 🚀

