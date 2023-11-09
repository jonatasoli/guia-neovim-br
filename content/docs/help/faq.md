+++
title = "FAQ"
description = "Perguntas Frequentes."
date = 2023-11-09T19:30:00+00:00
updated = 2023-11-09T19:30:00+00:00
draft = false
weight = 30
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Perguntas Frequentes."
toc = true
top = false
+++

## O que é NeoVim??

Extensível

    API de primeira classe: descobrível, versionada, documentada.
    Comunicação estruturada com MessagePack permite extensões em qualquer linguagem.
    Plugins remotos funcionam como co-processos, de forma segura e assíncrona.
    GUIs, IDEs, navegadores web podem incorporar o Neovim como editor ou host de script.
    Plugins Lua são fáceis de criar, assim como os plugins Vimscript. Sua configuração pode viver em init.lua!
    Motor de análise que produz AST permite destaque de sintaxe mais rápido e preciso, navegação de código, refatoração, objetos de texto e movimentos.

Utilizável

    Cliente LSP integrado para inspeção e refatoração de código semântico (ir para a definição, "encontrar referências", formatar, …)
    Padrões sólidos
    Funciona da mesma forma em todos os lugares: um tipo de compilação, um comando
    Recursos modernos de terminal, como estilo de cursor, eventos de foco, colagem entre colchetes
    Emulador de terminal integrado

Substituição para o Vim

    Totalmente compatível com o modelo de edição do Vim e Vimscript v1.
    Comece com :help nvim-from-vim se você já usa o Vim.

Qual é o status do projeto?

    A versão estável atual é a 0.9 (RSS). Consulte o roteiro para acompanhar o progresso e os planos.
    Neovim está tentando transformar o Vim em uma IDE?
    Com 30% menos código-fonte do que o Vim, a visão do Neovim é possibilitar novas aplicações sem comprometer os papéis tradicionais do Vim.
Neovim irá depreciar o Vimscript?

    Não. Lua está integrado, mas o Vimscript é suportado com o mecanismo de Vimscript mais avançado do mundo.

Quais plugins o Neovim suporta?

    Plugins Vim 8.x e muito mais.
