# Plano — Layout responsivo

## 1. Preparação da aplicação

1.1. Confirmar o gerenciador de pacotes e as versões de Node.js/TypeScript usadas pelo projeto; registrar a decisão nos arquivos de configuração.

1.2. Inicializar o frontend com React, React DOM, TypeScript e Vite, incluindo as dependências de desenvolvimento e scripts necessários.

1.3. Preparar a base da API em Node.js com TypeScript e incluir as dependências necessárias para SQLite, sem implementar ainda os endpoints de notícias.

1.4. Validar que frontend e API iniciam em ambiente local e que as dependências e lockfile estão consistentes.

## 2. Estrutura e comportamento responsivo

2.1. Definir a estrutura compartilhada de página e navegação para acomodar os conteúdos institucionais previstos no roadmap.

2.2. Definir regras CSS responsivas e breakpoints com base no conteúdo, evitando dimensões e transbordamentos que prejudiquem telas pequenas.

2.3. Implementar a adaptação da navegação e dos elementos de layout entre celular, tablet e desktop, preservando acesso às mesmas páginas e ações.

2.4. Aplicar e verificar o padrão responsivo em todas as páginas já implementadas; estabelecer o padrão para que as páginas das próximas fases também o sigam.

2.5. Garantir legibilidade, foco visível, ordem de leitura coerente e controles utilizáveis por toque e teclado.

## 3. Validação e entrega

3.1. Executar build e verificações disponíveis para frontend e API.

3.2. Validar as páginas em larguras representativas de celular, tablet e desktop e em navegadores modernos definidos para o projeto.

3.3. Corrigir problemas de navegação, conteúdo cortado, rolagem horizontal indesejada e controles inacessíveis identificados na validação.

3.4. Registrar resultados, limitações e evidências em `validation.md`; considerar a fase pronta para merge somente após cumprir os critérios definidos.
