# O que é Inteligência Artificial (IA)?

Capacidade de máquinas de executarem tarefas que normalmente exigem inteligência humana, como aprender, reconhecer padrões ou tomar decisões.

- Termo cunhado em 1960;
- Termo guarda-chuva que engloba vários assuntos;
- Conceito chave: imitar o comportamento humano.

## Como funciona?

- Utiliza Redes Neurais para identificar padrões complexos;
- Redes Neurais são pequenos nós funcionais interligados que funcionam como neurônios artificiais.
- Artificial Neural Network - ANN;
- Condicionais encadeadas;
- Processo de implementação e execução muito caro e extenso.

## Machine Learning - Aprendizado de Máquina

- Processo de ensinar máquinas;
- Máquinas identificam padrões;

### Tipos de aprendizados

- Supervised Learning: é fornecido um conjunto de dados e instruído do que se trata (imagens, texto);
- Unsupervised Learning: apenas um conjunto de dados é fornecido, a máquina identifica padrões e os classifica;
- Reinforcement Learning: a cada identificação a máquina é informada se está correta ou não.

## Deep Learning - Aprendizado profundo

- Processo de aprendizado aplicado a uma rede neural mais complexa;
- Exige um grande poder computacional;
- Processo extremamente caro para manter;
- Resulta nos modelos (LLM, SLM, visão computacional, ...).

## Generative AI

- Baseado no processamento de linguagem natural (Natural Language Processing);
  - Conversa natural entre humano e máquina, "oi, tudo bem?"
  - A mensagem é enviada ao modelo (LLM), o modelo converte em instruções para a máquina, resultado é devolvido ao modelo, que converte em linguagem natural. É um processo custoso
- Trabalha com janelas de contextos (memória)

## Transformers

- Preveem a próxima palavra (token)
  - Generative Pre-trained Transformer (GPT)
  - Sonnet
  - Gemini...
- Cada palavra é quebrada em tokens e passa pela rede neural com base na janela de contexto (chat)
- Modelos treinados com base em todo o conteúdo de domínio público na internet, o que pode não estar atualizado

## Retrieval Augmented Generator (RAG)

- Modelos não compreendem o que está dizendo, quando não tem informação tende a alucinar, inventar
- Serve para aumentar a capacidade do modelo
- Um conjunto de dados passam por um processo de **Embedding**, transformando-os em vetores de probabilidades

## Model Context Protocol (MCP)

- Definição de como IA consegue interagir com outras IAs, modelos, aplicações
- Possuem **Tools** que permitem essas interações
- Toda IA é **Estocástica**, um prompt pode gerar diferentes resultados

## Agents

- Programa autônomo que sabe onde está e sabe o que pode fazer
- Podem ser criados através de prompts
- Em um fluxo podem haver vários agentes que interagem entre si
- Precisam de contexto para operar corretamente

## Skills

- Habilidades que Agents podem exercer
- Independentes de Agents
- São passivas
- Podem ser específicas ou globais
- Prompts bem escritos

## Commands

- Análogo a um **Skill**
- Podem ser invocados a partir de um prompt
- Reativo, necessitam ser invocados
