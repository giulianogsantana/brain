---
type: meeting
title: Datalake, barramento de dados e IA
data: 2026-11-11
participantes: [Giuliano, Klaus Boeing, Patrick Cardoso, Adler Cachuba]
link: https://tldv.io/app/meetings/6af44a69f93560001399e7cf
atualizado: 2026-11-13
---
# Datalake, barramento de dados e IA (2026-11-11)

## Contexto
Arquitetura de dados (data lake, barramento) e governança de acesso de parceiros às APIs. Fonte: notas do tl;dv.

## Pontos discutidos
- Consultas degradam o banco transacional (ex.: cálculo de saldos); objetivo é reduzir leituras diretas. Camada bronze com versionamento e auditoria; conector direto para parceiros consumirem o data lake sem réplicas.
- Especialista de produto definirá requisitos; grupo transversal às verticais será criado. Projeto de lei de IA pode trazer multas sobre uso de dados.
- **Governança de parceiros**: pedidos de acesso eram aprovados sem verificar o produto; não há critérios claros. Sugestões: premissas para automatizar, justificativa obrigatória para novas conexões, modelo de licença e cobrança.
- Risco: revendas podem plugar sistemas de concorrentes no Estúdio.

## Decisões
- [[talita-frederico]] não liberará a credencial de teste pedida (via Patrick) até a empresa solicitante ser verificada.

## Pendências (quem / até quando)
- Klaus: apresentação detalhada da iniciativa de dados.
- Adler: enviar print do site "Radar do Gestor".
- Giuliano: investigar a empresa solicitante antes de liberar acesso.

## Páginas atualizadas
- [[consumo-plataforma-apis]], [[parceiros-de-produto]]
