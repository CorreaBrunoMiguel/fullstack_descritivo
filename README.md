# Projeto FullStack Interativo – Repositório Descritivo

## Visão Geral

Este repositório faz parte do projeto **FullStack Interativo**, criado para formar desenvolvedores FullStack completos (React + Node.js) de forma prática, progressiva e avaliativa.

O conteúdo será totalmente **modular**, organizado em:

- **Módulos** → grandes blocos temáticos
- **Fases** → subdivisões de cada módulo
- **Aulas** → unidade mínima de estudo, com:
  - Teoria (lessonXX.html)
  - Quiz (quizXX.html)
  - Exercícios (practiceXX.html)
  - Desafios (challengeXX.html)

> Todas as avaliações bloqueiam o avanço até atingir a pontuação mínima.

---

## Estrutura do Monorepo

---

fullstack_descritivo/
├── .editorconfig
├── .eslintrc.json
├── prettier.config.js
├── README.md
├── mXX/ # Módulo XX
│ ├── fXX/ # Fase XX
│ │ ├── aXX/ # Aula XX
│ │ │ ├── lessonXX.html # Teoria interativa
│ │ │ ├── quizXX.html # Quiz avaliativo
│ │ │ ├── practiceXX.html # Exercícios práticos
│ │ │ └── challengeXX.html # Desafio integrador
│ │ └── ... # Próximas aulas
│ └── README.md # Detalhes do módulo
├── mYY/ # Próximo módulo
└── docs/ # Documentação, referências, arquivos md (gitignore)

---

## Roadmap Inicial – Módulo 01: Fundamentos de Programação e Lógica

- **Fase 01 – Lógica de Programação com JavaScript**
  1. Aula 01 – Introdução à lógica e ambiente JS
  2. Aula 02 – Variáveis (let, const, var) e tipos primitivos
  3. Aula 03 – Conversão de tipos e coerção
  4. Aula 04 – Operadores aritméticos, lógicos e relacionais
  5. Aula 05 – Estruturas de controle (if, else, switch)
  6. Aula 06 – Laços de repetição (for, while, do...while)
  7. Aula 07 – Funções e escopo
  8. Aula 08 – Funções modernas (arrow, anônimas, parâmetros padrão, callbacks)
  9. Aula 09 – Exercícios integradores e revisão

> Cada aula terá arquivos interativos seguindo a organização **módulo → fase → aula**.

---

## Progresso do Repositório

- Estrutura inicial criada: ✅
- Pastas `docs/` e raiz configuradas: ✅
- Módulos e fases pendentes: ⬜
- Conteúdo das aulas pendente: ⬜

---

## Diretrizes de Trabalho

1. **Checklists:** Toda inclusão de conteúdo ou pasta seguirá checklist detalhado antes do commit.
2. **Avaliação contínua:** Usuário só avança após pontuação mínima em quiz, exercícios e desafios.
3. **Atualização constante:** Teoria será sempre super completa, atualizada e com exemplos guiados.
4. **Estrutura modular:** Seguir padrão **módulo → fase → aula** com README.md em cada nível.
5. **Controle de versão:** Branch principal `develop`; branches por módulo, fase e aula conforme avançamos.

---

## Próximos Passos

1. Finalizar configuração inicial do repositório (package.json, .gitignore, ESLint/Prettier).
2. Criar pastas iniciais do **Módulo 01 – Fase 01**.
3. Iniciar produção de conteúdo interativo (HTML/CSS/JS) das aulas.
