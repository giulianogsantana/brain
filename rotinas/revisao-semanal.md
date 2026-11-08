---
type: note
title: Revisão semanal
atualizado: 2026-11-07
---
# Revisão semanal (sexta, 30 min)

**Automatizada desde 2026-11-07**: tarefa agendada no Claude, toda sexta às 16h38 (horário de Brasília). Fontes: inbox, tl;dv, Google Agenda, Gmail e Drive da conta profissional, todos em modo somente leitura. Resultado: commit "Revisão semanal AAAA-MM-DD" e resumo por notificação. Ela não envia e-mails, não mexe na agenda nem no Drive e não escreve em `privado/`.

Para rodar manualmente, use o prompt abaixo:

Prompt para o Claude ou ChatGPT com acesso ao brain:

> Faça a revisão semanal do meu brain:
> 1. Trie tudo em `inbox/` para as páginas certas (pessoas, organizações, áreas, decisões) e apague os itens triados.
> 2. Busque no tl;dv as reuniões da semana e registre as relevantes em `reunioes/`.
> 3. Atualize o `status` e "Situação atual" das áreas que se moveram; liste as que estão paradas há mais de 30 dias.
> 4. Aponte contradições entre páginas e pessoas citadas sem página.
> 5. Me entregue um resumo de 10 linhas: o que avançou, o que travou, o que preciso decidir.
