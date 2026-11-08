---
type: source
title: "Varredura de emails Gmail"
slug: chatgpt-2026-08-18-varredura-de-emails-gmail
origem: ChatGPT (export 2026-11)
criado: 2026-08-18
atualizado: 2026-08-18
mensagens: 4
---

# Varredura de emails Gmail

Conversa do ChatGPT de 2026-08-18 (última atividade 2026-08-18). Transcrição bruta: **fonte, não verdade curada**. Fatos relevantes devem ser promovidos para as páginas de pessoas, organizações, áreas e decisões.


## Giuliano

@Gmail gostaria que você fizesse uma varredura nos meus e-mails e encontre todos os e-mails que foram enviados pela custom que trate de problemas envolvendo o nosso produto de gestão fiscal.


## ChatGPT

Vou cruzar remetentes/domínios ligados à Custom com termos de Gestão Fiscal e, depois, ler as conversas encontradas para separar problema real de simples menção ao produto.


## ChatGPT

A primeira varredura já trouxe um núcleo forte em **Resende/RJ**, com ofício formal da Custom sobre riscos na implantação do Gestão Fiscal e chamados de correção. Vou ampliar agora para mensagens mais recentes e para outros municípios/casos que possam não usar “Gestão Fiscal” no assunto.


## ChatGPT

Fiz a varredura no seu Gmail, considerando mensagens originadas pela **Custom** e também mensagens da Custom que chegaram até você por encaminhamentos internos. Depois filtrei o que realmente trata de **problemas, limitações, instabilidades ou dificuldades operacionais ligadas ao Gestão Fiscal**, excluindo temas puramente comerciais, contratuais e problemas de outros produtos, como Folha/Pessoal.

O que aparece é bastante consistente: há **três grandes núcleos de problemas**, além de um caso operacional menor.

### 1. Resende/RJ — implantação do Gestão Fiscal e problemas de performance — 2021

A primeira ocorrência forte é uma longa thread iniciada pela Yviê/Custom em **26/03/2021**, com o assunto **“Ofício Custom | Gestão Fiscal - Resende”**.

A Custom formalizou por ofício os **riscos da implantação do Gestão Fiscal em Resende**, dizendo que o produto estava sendo testado antes de ser demonstrado ao município e que havia preocupação suficiente para envolver a direção da Betha.

Os principais e-mails da Custom nessa conversa foram:

- **26/03/2021 — Ofício Custom | Gestão Fiscal - Resende**: comunicação formal dos riscos da implantação, com o arquivo *022 Ofício Betha_Resende_Gestão Fiscal.pdf*. [Abrir no Gmail](https://mail.google.com/mail/#all/1786e30dff002ff7)
- **26/03/2021 — complemento da Custom**: esclarece que o produto ainda estava sendo testado internamente e registra o **CI-89884** para formalizar a ocorrência.
- **29/03/2021 — acompanhamento**: a Custom informa que houve melhora significativa no **tempo de importação**, mas que continuaria monitorando para avaliar se a performance seria suficiente para atender Resende.
- **14/04/2021 — retorno formal da Custom**: informa que ainda havia pendência no **CI-89994** e que testaria uma atualização recém-liberada.
- **14/04/2021 — novo problema após a entrega**: a Custom comunica que os testes da solução do CI-89994 **não funcionaram** e abre o **CI-90408**.
- A Betha, nessa mesma thread, reconheceu que havia um incidente envolvendo o processo de importação e que ainda trabalhava em infraestrutura e escalabilidade.

Portanto, aqui existe um histórico formal bastante importante: **o Gestão Fiscal já apresentava problemas de performance/importação durante a própria implantação em Resende em 2021**, com reincidência mesmo após uma tentativa de correção.

### 2. Arrecadação/Fiscalização — problemas com GRERJ/TJ — 2021

Outra thread relevante começou em **03/03/2021**, com o assunto **“Ofício Custom | Chamados URGENTE - GRERJs”**. A própria Custom classificou a demanda como urgente em razão da **“grande insatisfação” dos clientes** com questões da vertical de Arrecadação e Fiscalização.

Os registros mais relevantes são:

- **03/03/2021 — Ofício Custom | Chamados URGENTE - GRERJs**: formalização da situação com o arquivo *Ofício GRERJ.pdf*. [Abrir no Gmail](https://mail.google.com/mail/#all/177f9a33c373f6ac)
- **04/03/2021 — complemento**: inclusão do **CI-88392**, relacionado a **erro na transmissão das custas ao Tribunal de Justiça**.
- **08/03/2021 — CI-78886**: a Custom explica que o usuário recebia a mensagem **“data do vencimento inválida”**, que dava a entender que havia um erro no sistema Tributos. A causa, segundo a análise, era uma limitação do serviço do TJ. A Custom solicita melhoria da mensagem para orientar corretamente o usuário.
- A Betha respondeu que **três funcionalidades seriam desenvolvidas em 30 dias**, embora tenha diferenciado o CI-78886 por depender de limitação externa do Tribunal.

Esse grupo deve entrar no levantamento porque está diretamente associado ao ecossistema do **Tributos/Arrecadação e Fiscalização** e demonstra problemas de integração, comportamento do produto e experiência operacional.

### 3. Resende e Sapucaia/RJ — protestos, CDAs, performance e estabilidade — 2026

Este é, de longe, o conjunto **mais atual e mais crítico**.

A cadeia começa com um e-mail da Custom de **25/05/2026**, posteriormente encaminhado internamente para você, sob o assunto **“Preocupação Operacional – Execução de Protestos no Módulo Tributos”**. [Abrir a conversa no Gmail](https://mail.google.com/mail/#all/19e694a657338834)

Em Resende, a Custom relata que o **Secretário de Fazenda manifestou insatisfação especificamente com o Tributos**, apesar de considerar os demais módulos adequados. Os problemas apresentados foram:

- impossibilidade prática de executar **protestos em lote** em grande volume;
- necessidade de abrir as CDAs individualmente;
- remoção manual de débitos já quitados;
- atualização manual de multa e juros;
- dificuldade de manter o valor da guia exatamente compatível com o valor consolidado das CDAs;
- risco direto sobre as campanhas de **REFIS e arrecadação municipal**.

Chamados associados: **CI-98660 e CI-98680**.

No mesmo e-mail, a Custom usa **Sapucaia/RJ como evidência adicional**, relatando:

- demora excessiva na execução das rotinas de protesto;
- comportamento divergente das parametrizações;
- instabilidades recorrentes;
- problemas praticamente diários.

Chamados citados: **SGS-1971, CI-99080, CI-99013, CI-99022, CI-99028 e CI-99048**.

A sequência da conversa é especialmente relevante:

- **03/06/2026:** a Custom registra que acompanharia as correções de CI-98660 e CI-98680, então previstas para 18/06.
- **19/06/2026:** depois de reunião com Sapucaia, cobra nova agenda e alerta que os dois chamados previstos para 18/06 ainda apareciam como **“aguardando avaliação”**.
- **24/06/2026:** confirma novo alinhamento técnico.
- **06/08/2026:** há uma escalada importante. Eliel informa que um usuário da Prefeitura de Sapucaia abriu **processo administrativo formal reclamando que o sistema não funciona para protestos**. A Custom afirma que os erros persistiam apesar das reuniões anteriores e que o contrato com o município estava sob risco.

Nesse último agravamento são citados os chamados **SGS-1971, CI-99211, SGS-1983 e CI-99473**. A Custom também faz uma associação direta com Resende: se a operação apresenta problemas em um município menor como Sapucaia, existe preocupação concreta com a capacidade de atender Resende, cujo volume de movimentação é muito superior. [Abrir o encaminhamento mais recente](https://mail.google.com/mail/#all/19fdc537e2d34d7d)

### 4. Resende — DES-IF / Nota Avulsa — problema de acesso em 2021

Encontrei ainda uma cadeia menor, também relacionada ao ambiente tributário, iniciada em **27/04/2021**, com o assunto **“Liberação Desif | PM Resende”**.

A Custom solicitou a liberação de **DES-IF e Nota Avulsa no Cloud** para Resende. No dia seguinte informou que os técnicos **não estavam conseguindo acessar**, apesar de a Betha indicar que o produto já estava liberado. [Abrir no Gmail](https://mail.google.com/mail/#all/17913993f18ad4f5)

Eu classificaria esse caso separadamente dos anteriores porque parece ter sido predominantemente um **problema de liberação/acesso**, e não necessariamente uma deficiência funcional do Gestão Fiscal.

---

### O quadro que emerge

O mais interessante da varredura não é apenas a existência de chamados isolados. Existe uma **recorrência histórica**:

**2021:** performance/importação do Gestão Fiscal em Resende → problemas de GRERJ/integracão com TJ → correções que precisaram ser refeitas.

**2026:** dificuldades operacionais do Tributos voltam a aparecer em uma função crítica — **protesto de dívida ativa** — agora acompanhadas de problemas de performance, estabilidade e escalabilidade em Sapucaia e Resende.

E a situação atual é mais séria porque deixou de ser exclusivamente técnica: há registro de **insatisfação do Secretário de Fazenda de Resende**, impacto potencial na arrecadação/REFIS e **processo administrativo formal em Sapucaia**, com risco contratual apontado pela própria Custom.

Também encontrei mensagens recentes da Custom sobre Resende referentes a **Folha/Pessoal, auditoria e integridade de dados**, mas deliberadamente **não as incluí**, porque são problemas de outro produto e contaminariam a análise de Gestão Fiscal.

Se o objetivo for levar isso ao responsável pelo suporte/desenvolvimento, eu consigo transformar agora essa varredura em uma **matriz consolidada por município → problema → chamado → histórico → resposta dada pela Betha → situação conhecida → risco**, o que deixaria muito claro especialmente o encadeamento de **Resende e Sapucaia**. memcite
