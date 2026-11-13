---
type: project
title: Modelo de receita por consumo da plataforma (APIs e Estúdio)
aliases: [consumo da plataforma, cobrança de APIs, Estúdio de Aplicações, data lake]
tags: [produto, receita, parceiros]
status: ativo
atualizado: 2026-11-13
---
# Consumo da plataforma: APIs, Estúdio e governança de parceiros
Definir como cobrar pelo consumo de APIs/Estúdio e como governar o acesso de parceiros aos dados.

## Situação atual (nov/2026)
- Proposta inicial: planos por cotas (hits mensais e simultâneos), Starter só de consulta, escrita cobrada à parte, valor por domínio. Concorrentes não cobram. [[2026-11-09-modelo-receita-consumo-plataforma]]
- Governança: hoje não há critérios para aprovar acessos de parceiros; propostas de premissas, justificativa obrigatória e licença/cobrança. [[2026-11-11-datalake-barramento-ia]]
- Caso concreto: parceiro de BI **Sistemática** com alto volume de requisições (4 municípios, 3 projetos), alerta do [[fabio-canabarro]] em 10/11. Tratativa: não confirmada.
- Data lake (Klaus Boeing): reduzir leitura no banco transacional; conector para parceiros.

## Próximos passos
- [ ] Klaus: dados de consumo por município e apresentação do data lake
- [ ] Remarcar "Consumo da Plataforma - Modelos de Cobrança" (20/11 é feriado, segundo Samanta)
- [ ] Definir critérios de liberação de acesso de parceiros (inferido)

## Relações
- [[integracao-banco-do-brasil]], [[parceiros-de-produto]]
