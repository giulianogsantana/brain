# Regras do brain

Este arquivo é o contrato entre o Giuliano e qualquer IA (Claude, ChatGPT, gbrain) que leia ou escreva aqui.

## 1. Brain primeiro
Antes de responder sobre pessoas, parceiros, contratos, projetos ou decisões, **consulte o brain**. Só depois busque em e-mail, Drive, tl;dv ou web. Se o brain e a fonte externa divergirem, mostre a divergência; não sobrescreva em silêncio.

## 2. Uma página por assunto
- Pessoa → `pessoas/<nome-sobrenome>.md`
- Empresa ou órgão → `organizacoes/<nome>.md`
- Frente de trabalho → `areas/<nome>.md`
- Conceito ou framework → `conhecimento/<nome>.md`
- Decisão → linha em `decisoes/<ano>.md` (e link na área)
- Reunião → `reunioes/AAAA-MM-DD-<assunto>.md`

Fato sobre X vai na página de X. Ligue páginas com `[[slug]]`.

## 3. Proveniência
- Todo fato relevante tem **data** (mesmo aproximada) e, quando possível, **fonte** (`[[chatgpt-...]]`, link do Drive, reunião).
- Marque o que é dedução com **(inferido)**. Sem marca = dito pelo Giuliano ou documentado.
- Nunca invente. Se não sabe, escreva "não confirmado".
- Fatos mudam: atualize com histórico ("Diretora Comercial interina desde ago/2026; antes: Luciano Torres"), não apague o passado.

## 4. Formato da página
```
---
type: person | company | project | concept | decision | meeting | note | source
title: Nome legível
aliases: [apelidos, siglas]
tags: [betha, revenda, ...]
status: ativo | pausado | encerrado   (áreas)
atualizado: AAAA-MM-DD
---
# Título
Resumo em 1–3 linhas (o que é e por que importa).

## Situação atual
## Histórico (mais recente primeiro)
## Relações
## Fontes
```

## 5. O que NÃO entra (ou vai para `privado/`)
- Senhas, CPF, dados bancários, documentos pessoais: nunca.
- Vida pessoal, saúde, família, jurídico pessoal: só em `privado/` (fora do git).
- Dados de clientes da Betha: o mínimo necessário. Nada de planilhas inteiras; resuma e aponte o link do Drive.

## 6. Rituais
- **Captura** (diária, 2 min): ver [[captura]].
- **Revisão semanal** (sexta, 30 min): ver [[revisao-semanal]].
- **Consolidação mensal**: fundir duplicatas, atualizar status das áreas, arquivar o que encerrou.

## 7. Para IAs que escrevem aqui
- Leia a página antes de editar; acrescente, não reescreva o que outra pessoa ou IA escreveu.
- Ao final de um trabalho relevante (reunião, contrato analisado, decisão), proponha a atualização das páginas afetadas e diga quais mudou.
- Prefira editar a criar: procure aliases antes de criar página nova.
