---
type: source
title: "Escrever resposta sobre chamado"
slug: chatgpt-2026-08-25-escrever-resposta-sobre-chamado
origem: ChatGPT (export 2026-11)
criado: 2026-08-25
atualizado: 2026-08-25
mensagens: 3
---

# Escrever resposta sobre chamado

Conversa do ChatGPT de 2026-08-25 (última atividade 2026-08-25). Transcrição bruta: **fonte, não verdade curada**. Fatos relevantes devem ser promovidos para as páginas de pessoas, organizações, áreas e decisões.

**Anexos citados:** 08425210-69dd-496c-8663-3180805af410.png, 1ef2519a-eaa3-4915-9ce3-c33e0f1c20ac.png, 2a4be239-37a1-4e07-94f4-7f1a49bd7ad1.png, 2a686c2c-c076-4389-bc69-a418d10ba1a2.png, 2b9ce460-c32f-4d94-9dba-bd1350f9cf30.png, 8b92f28b-42a7-425a-83ac-4d4945a4f58a.png


## Giuliano

Fui questionado pela nossa revenda chamada Delta sobre um chamado. Os prints que seguem anexo são do chamado em questão.
Diante do questionamento fui atrás do gerente que cuida deste produto e o mesmo trouxe o seguinte relato através de áudio aonde segue abaixo a transcrição:

Opa, bom dia, Gil. Eh, deixa eu te explicar. Nós fechamos uma um lote de chamados do Cidadão Web, eh, porque nós não iremos mais evoluir o Cidadão Web, só por por alguma necessidade de algum cliente, até que a gente possa migrar completamente todos os clientes para utilizarem o portal. Até final de setembro, a expectativa é que a gente já tenha todos os serviços que hoje rodam no cidadão web rodando nativamente dentro do portal. Estamos bem adiantados, inclusive Florianópolis deve começar a utilizar na próxima semana já a grande maioria dos serviços, então a gente não vai evoluir mais o cidadão e e o portal de serviços ele deve substituir o cidadão. Dito isso, eh deixa eu mandar esse áudio aqui para nós quebrar em partes aqui. Pera aí.  

Dito isso, temos essa exigência do BAC em relação à forma de integração feita hoje eh com os convênios por parte aí da da dos fornecedores de de software, que exige um nível mais eh sofisticado aí de autenticação, que depende de um certificado para poder fazer a comunicação com as APIs deles. Ah, esse em especial nós nós temos algumas melhorias, nós tínhamos algumas melhorias que nós atendemos pontualmente a pedido de alguns clientes para alguns convênios eh dentro dentro entre estes, dentre eles, es este que eu te passei, Secred, Banriçu e Santander. Até tô averiguando se tem algum outro aqui que a gente suporta que não entrou nessa leva de implementações aí. Eh, estes a gente acabou atendendo porque, eh, já eram pedido um nós nós começamos a implementação disso ainda no momento que a gente não tinha ainda todos os serviços já bem adiantados ali no portal. Então, a gente deu o seguimento nesses itens aqui, eh, pra gente poder fechar esses esses acordos aqui. Eh, com a abordagem do portal, o portal assumindo o papel eh do cidadão web, o portal ele não tem mais isso implementado dentro dele, assim como o cidadão web tinha. O cidadão web hoje são é o sistema apartado ali do tributos, aonde tem toda uma integração e aí tem toda essa implementação de integração diretamente no cidadão web. No portal isso não acontece mais. O portal ele consome nativamente isso do tributos. Ele depende eh do tributos para o tributos resolver essa questão de emissão de bol. de de de PX. Eh, e a gente não vai mais tratar isso no portal. Eh, considerando essa estratégia, não sei te dizer hoje como é que o Tributos trata está tratando isso, como é que se o Tributos já resolveu isso, se o Tributos ainda vai resolver, porque essa é uma determinação do bassen, eu não sei exatamente passado, retrasado, mas é esse ano realmente vai ser mais eh o pessoal vai vai fechar mais o cerco em relação a isso, em relação o bas em relação aos bancos, né? Então, os bancos devem pressionar mais os os clientes aqui. Eh, e consequentemente os fornecedores para mudarem essa estratégia para poder fazer uso, né, de de uma versão mais nova, né, da da das APIs de integração que eles têm. Então, da, né, tá tendo uma pressão um pouco maior. Eu não sei se isso já chegou pro Márcio, como é que o Márcio tá tá tratando isso. Por isso que seria interessante eh envolver o Márcio nisso. 

Diante do exposto, preciso responder para a revenda e gostaria que você me ajudasse a compilar o texto de resposta com base nas informações que me foram passadas.


## ChatGPT

Vou estruturar a resposta de modo a explicar a decisão sobre o Cidadão Web, reconhecer a urgência regulatória e, principalmente, deixar claro que o encerramento do chamado não significa que a necessidade será ignorada — ela precisa ser tratada no produto Tributos, que sustentará a emissão no novo Portal de Serviços. Para apresentar o texto já pronto para envio, usarei o recurso de bloco de escrita.


## ChatGPT

A resposta deve reconhecer que o encerramento genérico do chamado não esclareceu adequadamente o tratamento da exigência. Também é importante não prometer uma solução antes da validação com o responsável pelo Tributos.

:::writing{variant="standard" id="46281"}
Olá, Max. Bom dia!

Busquei internamente mais informações sobre o chamado DSI-34363 e gostaria de complementar o retorno anteriormente apresentado.

A Betha está promovendo uma transição dos serviços atualmente disponibilizados pelo Cidadão Web para o novo Portal de Serviços. A expectativa da equipe é que, até o final de setembro, todos os serviços atualmente executados pelo Cidadão Web estejam disponíveis de forma nativa no novo portal.

Em razão dessa estratégia, o Cidadão Web não receberá novas evoluções, salvo alguma necessidade excepcional de cliente durante o período de transição. Por esse motivo, o chamado foi encerrado enquanto solicitação de melhoria específica nesse sistema.

Entretanto, isso não significa que a necessidade relacionada à utilização de certificado mTLS nas APIs Pix tenha sido desconsiderada. Temos ciência do movimento dos bancos para adequação das integrações às exigências de segurança aplicáveis. Inclusive, algumas adequações pontuais já vinham sendo trabalhadas para convênios como Sicredi, Banrisul e Santander, em razão de solicitações anteriormente recebidas.

No novo Portal de Serviços, a arquitetura será diferente da utilizada atualmente no Cidadão Web. O portal não realizará diretamente essa integração bancária, pois consumirá nativamente os serviços disponibilizados pelo sistema Tributos. Dessa forma, a emissão das guias com Pix e o atendimento aos novos requisitos de autenticação deverão ser tratados na camada do Tributos.

Diante disso, o próximo encaminhamento será envolver a gestão responsável pelo produto Tributos para confirmar:

- como a exigência de autenticação por certificado mTLS será atendida na nova arquitetura;
- quais instituições financeiras já estão contempladas;
- se haverá alguma ação necessária durante a transição do Cidadão Web para o Portal de Serviços; e
- qual é a previsão para atendimento dos convênios ainda não adequados.

Assim que essa validação for concluída, retornaremos à Delta com um posicionamento mais preciso sobre o tratamento da demanda. Reconhecemos a relevância e a urgência do tema, especialmente diante dos prazos informados pelo Banrisul e da exigência já praticada pelo Sicredi.

Agradecemos por terem trazido antecipadamente essa necessidade e pelas informações compartilhadas no chamado.
:::
