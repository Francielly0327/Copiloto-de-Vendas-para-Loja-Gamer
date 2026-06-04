# 🎮 GameHub IA - Copiloto de Vendas para Loja Gamer

## 📌 Sobre o Projeto

O **GameHub IA** é um Copiloto de Vendas desenvolvido para auxiliar vendedores de uma loja gamer no atendimento ao cliente. A solução utiliza Inteligência Artificial para identificar necessidades, sugerir produtos adequados, responder dúvidas frequentes e apoiar o processo de vendas de forma personalizada.

O objetivo não é substituir o vendedor, mas fornecer suporte durante o atendimento, tornando as interações mais rápidas, eficientes e alinhadas ao perfil de cada cliente.

---

## 🎯 Problema que o Projeto Resolve

Durante o atendimento, muitos vendedores precisam lidar com diferentes perfis de clientes, dúvidas técnicas sobre produtos e objeções relacionadas à compra.

O GameHub IA foi criado para:

* Compreender as necessidades do cliente;
* Recomendar produtos compatíveis com seu perfil;
* Responder perguntas frequentes;
* Auxiliar na argumentação de vendas;
* Sugerir próximos passos para conduzir o atendimento.

Dessa forma, o vendedor consegue oferecer um atendimento mais consultivo e aumentar as chances de conversão.

---

## 🛠️ Abordagem Utilizada

Este projeto foi desenvolvido no formato de **Copiloto de Vendas com IA**, utilizando:

* Prompt principal para definição do comportamento da IA;
* Base de conhecimento estruturada em arquivos Markdown;
* Regras de atendimento para personalização das respostas;
* Simulação de cenários reais de vendas em uma loja gamer.

---

## 📚 Base de Conhecimento

A IA utiliza informações armazenadas na pasta `knowledge/`, composta pelos seguintes arquivos:

### produtos.md

Contém informações sobre os produtos comercializados pela loja, incluindo características e diferenciais.

### perguntas-frequentes.md

Reúne respostas para as dúvidas mais comuns dos clientes.

### objecoes.md

Apresenta exemplos de objeções de venda e sugestões de respostas para auxiliar o vendedor durante a negociação.

---

## 📁 Estrutura do Projeto

```text
copiloto-vendas-ia/
│
├── README.md
│
├── prompts/
│   └── prompt-principal.md
│
└── knowledge/
    ├── produtos.md
    ├── perguntas-frequentes.md
    └── objecoes.md
```

## 💬 Exemplo de Atendimento

**Cliente:** Estou procurando um mouse para jogos de FPS.

**Copiloto:** Você joga de forma casual ou competitiva?

**Cliente:** Competitiva.

**Copiloto:** Nesse caso, recomendo o Mouse Gamer Falcon X. Ele possui 7200 DPI, 7 botões programáveis e alta precisão, características importantes para jogadores que buscam desempenho competitivo.

---

## 🚀 Possíveis Melhorias Futuras

* Integração com banco de dados de produtos;
* Recomendação automática baseada no histórico do cliente;
* Integração com WhatsApp e plataformas de e-commerce;
* Sistema de análise de intenção de compra;
* Dashboard para acompanhamento de atendimentos;
* Suporte a múltiplos segmentos além do mercado gamer.

---

## 👨‍💻 Tecnologias e Conceitos Aplicados

* Engenharia de Prompt
* Inteligência Artificial Generativa
* Estruturação de Base de Conhecimento
* Atendimento Assistido por IA
* Copilotos e Agentes Inteligentes

---

## 📖 Conclusão

O GameHub IA demonstra como a Inteligência Artificial pode ser utilizada para apoiar equipes de vendas, proporcionando respostas mais rápidas, recomendações personalizadas e uma melhor experiência para o cliente.

Este projeto foi desenvolvido como parte do desafio proposto pela DIO (Digital Innovation One), aplicando conceitos de IA Generativa em um cenário prático de atendimento e vendas.
