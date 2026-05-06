# 🤖 Ippo — Seu Copiloto Inteligente

![dio/me](https://img.shields.io/badge/dio-me-ff2d55)
![IA](https://img.shields.io/badge/IA-Assistente%20Inteligente-blue)
![Prompt](https://img.shields.io/badge/Prompt-engineering-yellow)

O **Ippo** é um copiloto inteligente projetado para auxiliar desenvolvedores em diferentes níveis, oferecendo suporte desde dúvidas simples até execução de tarefas complexas no código.

Ele funciona através de **modos de operação**, permitindo que você escolha exatamente **como quer interagir com a IA** — com mais controle, clareza e produtividade.

---

# 🧩 Modos do Ippo

O Ippo possui 5 modos principais de interação:

- ❓ Ask → entender  
- ✏️ Edit → modificar código  
- 🧭 Plan → planejar soluções  
- 🤖 Agent → executar tarefas completas  
- 📚 Study → aprender de verdade  

---

# ❓ Ask — Entendimento sem alteração

O modo **Ask** é ideal para quando você quer **entender algo sem alterar o código**.

Ele funciona como um **mentor técnico**, analisando o contexto do projeto e explicando:

- erros  
- funções  
- trechos de código  
- stack traces  
- conceitos gerais  

💡 *Perfeito para debugging e aprendizado rápido.*

📄 **Prompt:** `prompts/prompt-ask.md`

---

# ✏️ Edit — Modificação direta

No modo **Edit**, o foco é **transformar código existente**.

Você seleciona um trecho e descreve a mudança — o Ippo faz o resto.

Ideal para:
- refatoração  
- melhorias de performance  
- ajustes de lógica  
- padronização de código  
- tratamento de erros  
- conversão de linguagem  

💡 *Aqui a ideia é: “pegue isso e melhore”*

📄 **Prompt:** `prompts/prompt-edit.md`

---

# 🧭 Plan — Pensar antes de executar

O modo **Plan** é usado para problemas mais complexos, onde é importante **definir uma estratégia antes de sair codando**.

Ele:
- quebra o problema em etapas  
- explica a abordagem  
- organiza a solução  

💡 *Ideal para features novas ou mudanças grandes.*

📄 **Prompt:** `prompts/prompt-plan.md`

---

# 🤖 Agent — Execução autônoma

O modo **Agent** é o mais poderoso.

Aqui, o Ippo atua quase como um **dev júnior**, podendo:

- navegar pelo projeto  
- criar arquivos  
- modificar múltiplos pontos  
- manter contexto entre ações  

Você só define o objetivo, por exemplo:

```bash
implemente autenticação com JWT
