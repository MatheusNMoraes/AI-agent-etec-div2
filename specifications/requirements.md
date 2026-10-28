# Requisitos — Layout responsivo

## Identificação

- **Fase:** 2 — Layout responsivo
- **ID no roadmap:** 2
- **Data:** 2026-10-27
- **Branch:** `feature/2026-10-27-layout-responsivo`

## Contexto

O site institucional deve apresentar a escola, cursos, matrizes curriculares e notícias com uma experiência adequada em dispositivos móveis e navegadores modernos. A missão do projeto também pede uma interface atraente e confiável. A stack de referência define React e Vite para o frontend, Node.js com TypeScript para a API e SQLite como armazenamento inicial de notícias.

O repositório ainda não contém código de aplicação. Esta fase deve estabelecer a base necessária para construir as páginas responsivas e preparar a stack, sem antecipar a implementação dos recursos das fases seguintes.

## Escopo

- Tornar responsivas todas as páginas do site, existentes ou criadas durante as fases seguintes.
- Definir uma estrutura compartilhada de layout que comporte navegação e conteúdo em telas móveis, intermediárias e desktop.
- Preparar a aplicação frontend com React, TypeScript e Vite.
- Preparar a base Node.js com TypeScript e incluir SQLite na stack planejada para persistência.
- Manter a arquitetura simples e coerente com `specifications/mission.md` e `specifications/tech-stack.md`.

## Decisões

- **Cobertura:** todas as páginas devem ser responsivas; não limitar o trabalho à página inicial.
- **Prioridade:** suportar primeiro a leitura e navegação em telas pequenas, preservando uma apresentação confortável em telas maiores.
- **Tecnologias:** React no frontend e Node.js com TypeScript na API. SQLite permanece como banco inicial conforme a stack do projeto.
- **Dependências:** selecionar e registrar as dependências necessárias ao inicializar a aplicação, respeitando o gerenciador de pacotes que vier a ser adotado. A escolha de um driver SQLite deve ser compatível com a versão de Node.js e a estratégia de execução definidas para o projeto.
- **Breakpoints:** não foram fornecidos valores fixos; defini-los a partir do conteúdo e verificar os layouts em larguras representativas de celular, tablet e desktop.
- **Escopo de dados:** instalar/preparar a stack não implica implementar nesta fase autenticação, API de notícias, persistência de notícias, catálogo ou matrizes; esses recursos pertencem às fases correspondentes do roadmap.

## Fora de escopo

- Implementar cadastro/login de equipe ou operações de notícias.
- Construir ou popular o catálogo, matrizes curriculares e descrições de disciplinas.
- Definir conteúdo final ou produzir a identidade visual da fase 1.
- Adicionar uma biblioteca de componentes ou CSS sem necessidade validada.

## Referências

- `specifications/mission.md`
- `specifications/tech-stack.md`
- `specifications/roadmap.md` — Fase 2, ID 2
