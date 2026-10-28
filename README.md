# Rafael Santos, "Rafa, o Pato" 🦆

Construo **agentes de IA e automações** que rodam em produção: do protótipo ao sistema no ar, com acesso por perfil, aprovação humana nas ações sensíveis e backup.

Desenvolvedor Full Stack em São Paulo. Hoje na BNC Realty (construtora), onde desenvolvi o sistema de gestão e os agentes que a operação usa no dia a dia. Cursando Ciência de Dados e Inteligência Artificial (Dom Bosco).

## O que já coloquei no ar

O código de produção é da empresa e não é público. Os repositórios abaixo são **versões reconstruídas, com dados fictícios**, que mostram como cada peça foi pensada e funciona. Cada um traz README com passos para rodar, testes e o que ficou de fora.

| Projeto | O que faz | Stack |
|---|---|---|
| **[Sistema de gestão de obras](https://github.com/RafaOPato/gestao-obras-case)** | Estudo de caso do sistema que substituiu o antigo: obras, pedidos de compra, cronograma, agenda, planilhas, painel do dono e versão para celular | React, Node.js, PostgreSQL, Docker, MCP |
| **[Assistente de compras no WhatsApp](https://github.com/RafaOPato/agente-compras-whatsapp)** | Lê o pedido de insumos, dispara cotações aos fornecedores, consolida as respostas em mapa de concorrência e só fecha com o OK do engenheiro | n8n, Waha, Claude, Python, PostgreSQL |
| **[Servidor MCP com permissão por agente](https://github.com/RafaOPato/mcp-obras)** | Cada agente só enxerga as obras e ferramentas liberadas para ele; a regra é checada em código, não no prompt | Node.js, MCP |
| **[Transcrição de áudio do WhatsApp](https://github.com/RafaOPato/transcricao-audio-whatsapp)** | Áudios viram texto e alimentam o acompanhamento da obra | n8n, Whisper (Groq), Node.js |
| **[Leitor de cartões](https://github.com/RafaOPato/Leitor-de-cart-o)** | Foto de cartão de visita vira linha de planilha | Python, Gemini Vision |

Resultados: [preencher: horas por semana economizadas em compras] · [preencher: tempo de cotação antes e depois] · [preencher: quantidade de usuários ativos].

## Estudos e laboratórios

| Projeto | O que mostra |
|---|---|
| **[Análise de dados com IA](https://github.com/RafaOPato/analise-dados-ia)** | Um erro de junção que passa batido quando a IA analisa dados sem conferência, reproduzido com dados sintéticos, e o método que o corrige |
| **[RAG mini (estudo)](https://github.com/RafaOPato/rag-mini)** | Busca por similaridade com pgvector e avaliação (recall@3, MRR). Projeto de estudo: não usei RAG em produção |

## Como eu trabalho com IA

- Agentes com **permissão por ferramenta**, checada em código e não só no prompt.
- Nada vai para produção sem validar antes no ambiente local.
- Estudando: RAG, orquestração com LangChain e fine-tuning. Ainda não usei em produção, e os repositórios de estudo estão marcados como tal.

## Stack

`Node.js` `React` `Python` `Java` `PostgreSQL` `MySQL` `Docker` `n8n` `MCP` `HTML/CSS/JS` `Figma`

## Contato

[LinkedIn](https://www.linkedin.com/in/rafael-santos) · rafael.moises2k@gmail.com · [Site](https://pato.bncrealty.com.br)
