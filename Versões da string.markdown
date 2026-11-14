**Evolução da string de busca — três últimas versões**

Este registro apresenta as três últimas versões da string de busca, em ordem cronológica. A versão final corresponde à string apresentada na Tabela 3 do artigo.

**Antepenúltima versão**

```text
("human experiment*" OR "human evaluation" OR "human-in-the-loop" OR "RLHF" OR "reinforcement learning from human feedback")
AND
("generative AI" OR "large language model*" OR LLM* OR "foundation model*")
AND
("alignment" OR "value alignment" OR "human alignment" OR "human expectation*")
```

**Penúltima versão**

```text
("Evaluation" OR "Alignment" OR "Metrics" OR "Human Feedback" OR "Preference Optimization" OR "Instruction Following")
AND
("Large Language Models" OR "LLMs" OR "Generative Chatbots" OR "Language Models")
AND
("Domain-Specific" OR "Natural Language")
AND
("Human Values" OR "Human Instructions")
```

**Principais alterações em relação à antepenúltima versão:**

1. Reformulação do primeiro bloco, substituindo os termos relacionados à experimentação humana, avaliação humana e RLHF por termos de avaliação, alinhamento, métricas, feedback humano, otimização de preferências e seguimento de instruções.
2. Reformulação do bloco de tecnologias, com a adoção de expressões relacionadas a modelos de linguagem e chatbots generativos.
3. Introdução de um bloco obrigatório composto por "Domain-Specific" ou "Natural Language".
4. Substituição do bloco obrigatório de alinhamento e expectativas humanas pelo bloco de valores ou instruções humanas. "Alignment" passou a ser uma alternativa no primeiro bloco, deixando de constituir uma exigência temática separada.
5. Alteração da estrutura de três para quatro blocos unidos por AND.

**Versão final**

```text
("Evaluation" OR "Alignment" OR "Metrics" OR "Human Feedback" OR "Instruction Following")
AND
("Large Language Models" OR "LLMs" OR "Generative Chatbots" OR "Language Models" OR "Natural Language")
AND
("Human Values" OR "Human Instructions")
```

**Principais alterações em relação à penúltima versão:**

1. Retirada de "Preference Optimization" do primeiro bloco.
2. Retirada de "Domain-Specific".
3. Transferência de "Natural Language" para o bloco de modelos de linguagem e chatbots, como alternativa ligada por OR.
4. Eliminação do bloco obrigatório separado de domínio/linguagem.
5. Manutenção do bloco "Human Values" OR "Human Instructions".
6. Alteração da estrutura de quatro para três blocos unidos por AND.
