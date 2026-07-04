# Mapping Engine (LYS)

A **Mapping Engine** é o núcleo de decisão do LYS.

Sua responsabilidade é transformar informações anatômicas, características dos fios naturais e a intenção estética da cliente em uma estratégia técnica personalizada de mapping.

---

## Objetivo

O propósito da engine não é apenas recomendar um mapping, mas reproduzir o processo de tomada de decisão de uma lash designer experiente de forma estruturada, consistente e justificável.

---

## Filosofia

A engine é construída sobre quatro pilares fundamentais:

- Base de conhecimento técnico
- Modelagem da intenção estética
- Regras de decisão
- Sistema de validação

Cada recomendação gerada deve possuir fundamentação técnica, respeitar as restrições anatômicas da cliente e atender ao resultado visual desejado.

---

# Arquitetura Geral

<p align="center">
    <img src="./architecture/engine-overview.png" width="900">
</p>

---

# Fluxo de decisão

```text
Cliente
      │
      ▼
Intenção Estética
      │
      ▼
Interpretação da Linguagem
      │
      ▼
Base de Conhecimento
      │
      ▼
Aplicação das Regras
      │
      ▼
Sistema de Score
      │
      ▼
Validação Técnica
      │
      ▼
Sugestão de Mapping
```

---

# Componentes

| Componente | Objetivo | Status |
|------------|----------|--------|
| Anatomia | Modelar características do olho | ✅ |
| Fios Naturais | Modelar limitações estruturais | ✅ |
| Assimetrias | Compensações visuais | ✅ |
| Intenção Estética | Traduzir desejo em atributos técnicos | 🚧 |
| Sistema de Score | Priorizar soluções | 🚧 |
| Resolução de Conflitos | Resolver regras concorrentes | ⏳ |

---


# Evolução da Engine

A documentação acompanha a evolução da arquitetura do projeto.

O objetivo é registrar não apenas o resultado final, mas também o processo de construção da lógica responsável pelas decisões da engine.

---

# Roadmap

- ✅ Modelagem Anatômica
- ✅ Base de Fios Naturais
- ✅ Regras de Assimetria
- 🚧 Intenção Estética
- ⏳ Sistema de Score
- ⏳ Resolução de Conflitos
- ⏳ Motor de Inferência
- ⏳ Estratégia Final de Mapping

---

> "O objetivo do LYS não é substituir o julgamento profissional da lash designer, mas estruturar esse conhecimento para que decisões técnicas sejam consistentes, explicáveis e personalizadas."
