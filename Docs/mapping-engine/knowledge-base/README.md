
# Knowledge Base

A **Knowledge Base** reúne todo o conhecimento especializado utilizado pela Mapping Engine do LYS.

Ela representa a formalização do processo de tomada de decisão de uma lash designer experiente, transformando conhecimento prático em regras estruturadas e interpretáveis pela engine.

---

# Objetivo

A base de conhecimento define **o que a engine sabe**.

Ela não toma decisões diretamente.

Seu papel é fornecer informações estruturadas para que o motor de decisão avalie cada caso de forma consistente e justificável.

---

# Filosofia

Todo conhecimento armazenado deve responder a pelo menos uma das seguintes perguntas:

- O que é possível fazer?
- O que deve ser evitado?
- O que influencia uma decisão?
- Como justificar uma recomendação?

---

# Organização

```
Knowledge Base

├── Anatomia
│
├── Cílios Naturais
│
├── Intenção Estética
│
├── Regras Técnicas
│
└── Modelo de Score
```

---

# Componentes

## Anatomia

Modela todas as características anatômicas relevantes para a tomada de decisão.

Exemplos:

- formato ocular
- inclinação
- profundidade
- espaço palpebral
- cobertura palpebral

---

## Cílios Naturais

Modela as características estruturais dos fios naturais.

Exemplos:

- espessura
- direção
- densidade
- resistência
- suporte estrutural

---

## Intenção Estética

Responsável por transformar o desejo da cliente em uma representação técnica.

Inclui:

- atributos visuais
- linguagem da cliente
- preferências
- restrições
- intensidade dos atributos

---

## Regras Técnicas

Conjunto de regras que relaciona anatomia, intenção estética e limitações técnicas.

Exemplos:

- incompatibilidades
- recomendações
- compensações
- exceções

---

## Modelo de Score

Modelos utilizados para comparar diferentes estratégias possíveis.

Exemplos:

- pesos
- prioridades
- critérios de avaliação
- ranking das soluções

---

# Fluxo dentro da Engine

```text
Conhecimento Estruturado

        │

        ▼

Filtro de Viabilidade Técnica

        │

        ▼

Motor de Decisão

        │

        ▼

Estratégia Recomendada
```

---

# Evolução

A Knowledge Base é incremental.

Novas observações, regras e relações podem ser adicionadas conforme a evolução do projeto e a validação prática da engine.

O objetivo é expandir continuamente a capacidade de decisão sem alterar a arquitetura principal da Mapping Engine.
