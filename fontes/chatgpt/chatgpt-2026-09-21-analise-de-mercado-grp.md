---
type: source
title: "Análise de mercado GRP"
slug: chatgpt-2026-09-21-analise-de-mercado-grp
origem: ChatGPT (export 2026-11)
criado: 2026-09-21
atualizado: 2026-11-02
mensagens: 21
---

# Análise de mercado GRP

Conversa do ChatGPT de 2026-09-21 (última atividade 2026-11-02). Transcrição bruta: **fonte, não verdade curada**. Fatos relevantes devem ser promovidos para as páginas de pessoas, organizações, áreas e decisões.

**Anexos citados:** ativo-2026-09-21T00_09_28.171.csv, ativo-2026-09-21T00_41_54.987.csv


## Giuliano

Peço que você analise esta planilha aonde constam todos os municípios que possuem algum faturamento com a Betha. Não necessariamente temos todos os produtos nestes municípios mas já é possível ter uma ideia de em quantos municípios estamos presentes no brasil com faturamento.

Com base nesta informação, aja como um especialista em análise de dados de mercado de software GRP para gestão pública municipal e avalie o potencial de crescimento da Betha levando em consideração que a atuação em Santa Catarina seria somente através de venda direta, ou seja, contratos diretos com a Betha, e o restante dos estados queremos atuar somente com a venda indireta, ou seja, através de canais.

No cenário atual da planilha temos um recorrente de aproximadamente R$16.731.437,27.

Como especialista conto com seu expertise para fazer uma busca nos principais portais públicos que disponibilizam de forma gratuita principalmente dos contratos cadastrados de softwares concorrentes de empresas concorrentes da Betha como por exemplo Pública Tecnologia, IPM Sistemas, Elotech, E&L, SmarAPD, Fiorilli, Aspec, Grupo S&S, Multi24, Tecnosistemas, Thema, e tantas outros concorrentes que competem diretamente com a Betha no sistemas do core como sistemas orçamentário, compras contratos e licitações, pessoal, arrecadação e sistemas para o cidadão. O principal portal a ser consultado é o PNCP mas não quero limitá-lo a busca somente neste portal. Explore o máximo do seu potencial.


## ChatGPT

Vou estruturar a análise em duas frentes: primeiro, dimensionar com precisão a presença e o recorrente atual da Betha por município, estado e região; depois, cruzar essa base com o mercado endereçável municipal e com evidências públicas de contratos dos principais concorrentes — priorizando PNCP, mas também portais de transparência, tribunais de contas e bases oficiais.

Como o objetivo é apoiar uma decisão estratégica de expansão por canais, vou usar a metodologia de análise de planilhas para garantir consistência da base e deixar explícitas as premissas, limitações e oportunidades. Também distinguirei “município com algum faturamento” de “município plenamente penetrado”, pois essa diferença é central para não subestimar o potencial de expansão dentro da própria base.


## ChatGPT

A primeira leitura já revela um ponto estratégico importante: a base tem 29.333 registros, mas apenas 581 combinações únicas de município/UF, distribuídas por 17 estados. Isso confirma que cada linha não representa um município novo; os registros repetidos parecem refletir múltiplos itens, contratos, produtos ou ocorrências de faturamento.

Portanto, não vou usar a quantidade de linhas como proxy de penetração. A presença territorial será calculada pelos 581 municípios únicos, enquanto a recorrência de R$ 16,73 milhões será tratada como receita consolidada da carteira — porque o arquivo não contém valor por município nem identificação de produto. A ausência desses campos limita, por enquanto, a análise de ticket, share of wallet e espaço de cross-sell por cliente.


## ChatGPT

A pesquisa aberta confirma que o PNCP oferece consultas públicas por API, mas a pesquisa textual comum não indexa adequadamente fornecedor, objeto e valor dos contratos. Para obter evidência útil — e evitar conclusões baseadas apenas em páginas comerciais dos concorrentes — vou consultar a camada pública estruturada do portal e complementar com fontes municipais e tribunais de contas quando houver lacunas. Isso também permitirá separar contrato vigente, licitação, aditivo e simples menção ao fornecedor.


## ChatGPT

Analisei a [planilha de municípios com faturamento](sandbox:/workspace/scratch/cc61b485ce2c/upload/ativo-2026-09-21T00_09_28.171.csv) e fiz o cruzamento com o mercado municipal brasileiro e com evidências públicas dos principais concorrentes.

## Conclusão executiva

A Betha já possui uma presença nacional relevante, mas ainda está longe da saturação:

- 581 municípios com algum faturamento.
- Presença em 17 estados.
- Aproximadamente 10,4% dos municípios brasileiros.
- Recorrência mensal informada: R$ 16,73 milhões.
- Recorrência anualizada: R$ 200,78 milhões.
- Receita mensal média por município presente: aproximadamente R$ 28,8 mil.
- 61,7% dos municípios de Santa Catarina já possuem algum faturamento.
- Fora de Santa Catarina, a cobertura é de apenas 7,6%.

Minha leitura principal é que a Betha tem duas oportunidades simultâneas:

1. Expandir o portfólio nos 581 municípios onde já existe algum relacionamento.
2. Conquistar novos municípios, principalmente por meio de canais fora de Santa Catarina.

A primeira oportunidade pode ser tão ou mais relevante que a segunda, porque a planilha registra apenas a existência de algum faturamento. Ela não permite saber quantos produtos cada município utiliza.

## Qualidade da base

A planilha possui:

| Indicador | Resultado |
|---|---:|
| Registros totais | 29.333 |
| Municípios/UF únicos | 581 |
| Registros repetidos | 28.752 |
| Estados com presença | 17 |
| Estados sem presença | 9 |

Cada linha não representa um novo município. As repetições podem representar produtos, contratos, órgãos, estabelecimentos ou diferentes ocorrências de faturamento.

Por isso, a quantidade de linhas não deve ser usada para medir participação de mercado, densidade de produtos ou receita. Para isso seriam necessários, pelo menos:

- Município e UF.
- Produto.
- Órgão ou entidade contratante.
- Modelo comercial.
- Canal responsável.
- Receita recorrente mensal.
- Receita de serviços e implantação.
- Data de início e término do contrato.

## Presença territorial

O Brasil possui 5.571 localidades consideradas nas estimativas populacionais, incluindo Brasília e Fernando de Noronha. Para o mercado efetivamente formado por governos municipais, utilizei 5.569 municípios como universo operacional. As estimativas mais recentes do IBGE já incorporam Boa Esperança do Norte/MT. [Referência sobre a base territorial mais recente](https://www1.folha.uol.com.br/cotidiano/2026/08/veja-a-populacao-da-sua-cidade-em-2026-segundo-o-ibge.shtml).

### Estados com maior penetração

| UF | Municípios Betha | Total do estado | Penetração | Municípios disponíveis |
|---|---:|---:|---:|---:|
| AC | 21 | 22 | 95,5% | 1 |
| SC | 182 | 295 | 61,7% | 113 |
| AM | 19 | 62 | 30,6% | 43 |
| MS | 18 | 79 | 22,8% | 61 |
| RJ | 18 | 92 | 19,6% | 74 |
| RO | 10 | 52 | 19,2% | 42 |
| PR | 70 | 399 | 17,5% | 329 |
| RS | 67 | 497 | 13,5% | 430 |
| MT | 18 | 142 | 12,7% | 124 |
| SP | 66 | 645 | 10,2% | 579 |

O Acre está praticamente saturado territorialmente. Sua oportunidade principal é ampliar produtos e receita por município, e não conquistar novas prefeituras.

Santa Catarina permanece como o maior ativo territorial da Betha, mas ainda existem 113 municípios sem faturamento. Como a atuação será direta, esse espaço deve ser tratado por uma estratégia própria de cobertura comercial, distinta da expansão nacional por canais.

### Maiores espaços disponíveis

| UF | Presença Betha | Mercado disponível |
|---|---:|---:|
| MG | 61 | 792 |
| SP | 66 | 579 |
| RS | 67 | 430 |
| BA | 14 | 403 |
| PR | 70 | 329 |
| GO | 0 | 246 |
| PI | 0 | 224 |
| PB | 0 | 223 |
| MA | 0 | 217 |
| PE | 0 | 184 |
| CE | 1 | 183 |
| RN | 1 | 166 |
| TO | 0 | 139 |
| PA | 7 | 137 |
| MT | 18 | 124 |

Os estados sem faturamento são AP, RR, TO, MA, PI, PB, PE, SE e GO.

## Potencial financeiro indicativo

A média atual de R$ 28,8 mil mensais por município pode ser usada como referência inicial. Entretanto, ela mistura diferentes portes, produtos e modelos comerciais.

| Captura dos municípios ainda disponíveis | Novos municípios | MRR incremental estimado | Receita anual incremental |
|---|---:|---:|---:|
| 2% | 100 | R$ 2,88 milhões | R$ 34,56 milhões |
| 5% | 249 | R$ 7,17 milhões | R$ 86,05 milhões |
| 10% | 499 | R$ 14,37 milhões | R$ 172,44 milhões |
| 15% | 748 | R$ 21,54 milhões | R$ 258,49 milhões |
| 20% | 998 | R$ 28,74 milhões | R$ 344,88 milhões |

Esses valores representam uma ordem de grandeza equivalente ao ticket atual. Não são projeções líquidas para a Betha, porque a expansão nacional ocorrerá por canais e ainda precisamos considerar:

- Repasse ao canal.
- Tributação.
- Serviços de implantação.
- Suporte e atendimento local.
- Investimento em capacitação.
- Custo de localização para os respectivos tribunais de contas.
- Ticket diferente por porte municipal.
- Número efetivo de produtos contratados.

Mesmo no cenário conservador de captura de apenas 5% do espaço territorial, a recorrência mensal poderia passar de R$ 16,73 milhões para aproximadamente R$ 23,90 milhões, antes do efeito econômico dos repasses aos canais.

## Onde a Betha deveria concentrar esforços

### 1. Santa Catarina: crescimento direto e share of wallet

Prioridades:

- Conquistar gradualmente os 113 municípios sem faturamento.
- Mapear produtos não contratados nos 182 municípios atuais.
- Defender a base contra IPM e outros concorrentes regionais.
- Separar municípios por porte, ticket atual e quantidade de produtos.
- Criar metas específicas de expansão de portfólio por conta.

Em Santa Catarina, a oportunidade de cross-sell provavelmente é maior do que a simples leitura dos 113 municípios ainda disponíveis.

### 2. Primeira onda de expansão por canais

Eu priorizaria:

| Prioridade | Estados | Justificativa |
|---|---|---|
| Muito alta | MG, RS, PR | Grande quantidade de municípios disponíveis e presença Betha já estabelecida |
| Muito alta | SP | Maior mercado municipal relevante, embora altamente competitivo |
| Alta | BA, CE, PA | Mercados grandes, baixa penetração e possibilidade de expansão com parceiros regionais |
| Alta | MS, MT, RJ | Presença proporcionalmente relevante, permitindo expansão por adjacência |
| Seletiva | AM, RO, ES | Mercados menores, mas com base existente que reduz o custo de entrada |

MG, RS e PR são os melhores territórios para expansão acelerada porque combinam base instalada, conhecimento regulatório e espaço disponível.

SP deve ser atacado com maior seletividade. O estado tem 579 municípios disponíveis, mas também apresenta elevada concorrência de empresas como Fiorilli, SmarAPD, Pública e fornecedores locais.

### 3. Segunda onda: construção de novos canais

GO, PE, PB, MA, PI e TO somam mais de 1.200 municípios sem presença Betha.

Porém, entrar simultaneamente nesses mercados produziria dispersão. A recomendação é escolher dois estados-piloto com base em:

- Força e cobertura do parceiro.
- Capacidade de implantação e suporte.
- Experiência com o TCE estadual.
- Carteira prévia de municípios.
- Capacidade financeira.
- Ausência de conflito com outros canais.
- Número de contratos concorrentes próximos do vencimento.

A Betha não deveria escolher o próximo estado apenas pelo número de municípios disponíveis. O ativo decisivo será o canal capaz de converter e sustentar esses municípios.

## Leitura competitiva

A pesquisa pública confirma que o mercado é altamente regionalizado:

- IPM apresenta contratos e presença principalmente no Sul, inclusive em Santa Catarina, como no contrato publicado pelo município de Garuva. [Contrato IPM–Garuva no PNCP](https://pncp.gov.br/).
- Elotech apresenta forte presença no Paraná, com contratos de sistemas web e gestão pública. [Contrato do CISPAR com a Elotech](https://www.cispar.pr.gov.br/).
- E&L aparece com frequência em municípios de Minas Gerais e Espírito Santo. [Contrato de Governador Valadares com a E&L](https://transparencia.valadares.mg.gov.br/).
- SmarAPD possui presença histórica em municípios médios e grandes de São Paulo. [Contrato da Câmara de Sertãozinho](https://www.camarasertaozinho.sp.gov.br/imprensa/transparencia/0/6/0/885).
- Fiorilli tem alta disseminação em municípios pequenos e estruturas municipais do interior paulista. [Contrato de Paulistânia](https://www.cmpaulistania.sp.gov.br/noticia/100/fiorilli-software-ltda/).

O PNCP é uma fonte fundamental e oferece consultas públicas e APIs, mas ainda não pode ser tratado isoladamente como um censo completo do mercado. A cobertura depende da publicação pelos órgãos e da vigência da Lei nº 14.133/2021. Contratos antigos, aditivos, empenhos e contratações cadastradas apenas em portais locais podem não aparecer de forma uniforme. O próprio PNCP mantém documentação específica de integração e dados abertos. [Manuais oficiais do PNCP](https://www.gov.br/pncp/pt-br/pncp/manuais).

Portanto, uma inteligência competitiva confiável deve combinar:

1. PNCP.
2. Portais de transparência municipais.
3. Diários oficiais.
4. Tribunais de Contas.
5. Portais de compras públicas.
6. Sites e portais disponibilizados pelos próprios fornecedores.
7. Datas de vencimento dos contratos.
8. Valores de aditivos e renovações.

## Estratégia recomendada

A expansão deve operar em três movimentos.

### Defender e expandir a base

Criar uma matriz produto × município para os 581 municípios atuais. Essa matriz indicará:

- Produtos contratados.
- Produtos ausentes.
- Ticket atual.
- Potencial adicional.
- Grau de relacionamento.
- Risco competitivo.
- Data de vencimento.
- Canal responsável.

Esse trabalho provavelmente revelará uma oportunidade de receita mais rápida e barata que a aquisição de novos municípios.

### Escalar canais onde já existe presença

O programa de canais deve estabelecer metas por território:

- Municípios conquistados.
- MRR novo.
- Produtos adicionados à base.
- Pipeline ponderado.
- Taxa de conversão.
- Tempo de implantação.
- Satisfação e retenção.
- Capacidade técnica do parceiro.
- Rentabilidade líquida para a Betha.

### Construir inteligência de contratos concorrentes

A Betha deve manter uma base contínua contendo:

- Município.
- Concorrente.
- CNPJ do fornecedor.
- Objeto.
- Produtos envolvidos.
- Valor mensal e total.
- Data de assinatura.
- Vigência.
- Data provável da nova licitação.
- Modalidade.
- Portal de origem.
- Canal Betha potencial.
- Probabilidade de conversão.

O melhor indicador de oportunidade não é apenas “município sem Betha”. É “município sem Betha, com contrato concorrente próximo do vencimento, canal habilitado e aderência ao portfólio”.

## Minha recomendação final

A Betha não deve tentar cobrir o Brasil inteiro imediatamente. A melhor sequência é:

1. Maximizar o portfólio nos 581 municípios atuais.
2. Buscar os 113 municípios restantes de Santa Catarina por venda direta.
3. Escalar canais em MG, RS, PR, SP, BA e CE.
4. Consolidar MS, MT, RJ, PA, AM e RO por adjacência.
5. Escolher dois estados hoje sem presença para pilotos estruturados.
6. Manter monitoramento permanente dos contratos concorrentes e seus vencimentos.

O potencial é expressivo: conquistar apenas 5% do espaço territorial disponível, no ticket médio atual, representa aproximadamente R$ 86 milhões de receita recorrente anual adicional. Mas a verdadeira oportunidade tende a ser ainda maior quando consideramos o cross-sell dentro dos 581 municípios já atendidos.

Se for útil, posso configurar “Monitorar contratos GRP dos concorrentes” para identificar periodicamente novas contratações, aditivos e vencimentos relevantes.

genui{"suggest_automation":{"label":"Monitorar contratos GRP dos concorrentes"}}


## ChatGPT

Vou configurar o monitoramento para buscar novas contratações, aditivos e vencimentos de contratos de GRP municipal envolvendo os concorrentes já mapeados. Falta apenas definir a frequência.


## Giuliano

Para uma análise sua mais completa do entendimento do atual cenário da Betha, compartilho com você a planilha com mais dados, informando as entidades que são clientes da Betha nos municípios e estados, valores para cada um dos produtos. Assim como você analisou a outra planilha, esta deve ser analisada da mesma forma e não se deve considerar cada linha como se fosse um cliente mas analisar cada município, cada entidade e cada produto que consta nesta entidade para basear sua análise.


## ChatGPT

Perfeito. Vou refazer a leitura em três níveis distintos — município, entidade e produto — e reconciliar os valores sem contar linhas repetidas como clientes. Também vou comparar os novos totais com os 581 municípios e os R$ 16,73 milhões do levantamento anterior, identificando concentração de receita, cobertura de portfólio, oportunidades de cross-sell e diferenças entre venda direta em Santa Catarina e canais nos demais estados.

Como esta análise continua o trabalho anterior e envolve uma nova planilha mais completa, vou usar o contexto já construído e a metodologia específica de análise de planilhas para preservar os mesmos critérios de comparação.


## ChatGPT

A nova base fecha a mesma presença territorial do levantamento anterior: 581 municípios em 17 estados. Agora, porém, ela permite enxergar 2.118 entidades e 112 produtos.

Há uma divergência financeira relevante que estou reconciliando: a soma da coluna “Valor” é R$ 24,75 milhões, acima dos R$ 16,73 milhões informados anteriormente. Como só existem duas duplicidades exatas, essa diferença não é explicada por repetição simples de linhas. Vou separar o que é faturamento efetivamente atribuído, produtos com valor zero, possíveis componentes de pacote e concentração por entidade antes de interpretar esse total como MRR consolidado.


## ChatGPT

A nova planilha muda significativamente a leitura financeira da carteira Betha. Ela confirma os 581 municípios do levantamento anterior, mas revela uma operação composta por 2.118 entidades, 112 produtos e R$ 24,75 milhões na coluna “Valor”.

Analisei a base respeitando a hierarquia correta:

**município → entidade → produto → valor**, sem tratar cada uma das 29.333 linhas como cliente.

[Planilha detalhada analisada](sandbox:/workspace/scratch/cc61b485ce2c/upload/ativo-2026-09-21T00_41_54.987.csv)

## 1. Visão consolidada

| Indicador | Resultado |
|---|---:|
| Linhas da base | 29.333 |
| Municípios/UF | 581 |
| Municípios com valor positivo | 579 |
| Entidades identificadas | 2.118 |
| Entidades com valor positivo | 2.094 |
| Produtos diferentes | 112 |
| Soma bruta da coluna Valor | R$ 24.753.484,43 |
| Total após retirar 2 duplicidades exatas | R$ 24.753.233,03 |
| Valor anualizado, se a coluna representar MRR | R$ 297,04 milhões |
| Produtos médios por município | 22,7 |
| Produtos com valor positivo por município | 19,5 |
| Entidades médias por município | 3,6 |

Foram encontradas apenas duas duplicidades exatas, ambas em Passos Maia/SC, somando R$ 251,40. Portanto, a diferença financeira em relação ao valor informado anteriormente não decorre de linhas duplicadas.

Taió/SC e Rolante/RS aparecem na base, mas todas as suas linhas possuem valor zero. São municípios com registro de produto, mas sem recorrência monetária identificada nesta extração.

## 2. Reconciliação com os R$ 16,73 milhões anteriores

A principal descoberta da nova base está nesta separação:

| Mercado | Municípios | Entidades | Valor |
|---|---:|---:|---:|
| Santa Catarina | 182 | 795 | R$ 7.913.108,09 |
| Demais estados | 399 | 1.323 | R$ 16.840.376,34 |
| Total | 581 | 2.118 | R$ 24.753.484,43 |

O valor fora de Santa Catarina, R$ 16,84 milhões, está apenas R$ 108,9 mil ou 0,65% acima dos R$ 16,73 milhões informados anteriormente.

Isso indica uma hipótese bastante consistente: os R$ 16,73 milhões podem representar o recorrente da operação indireta ou da carteira fora de Santa Catarina. A diferença residual pode decorrer da data da extração, novas ativações, reajustes ou critérios de contabilização.

Antes de utilizar R$ 24,75 milhões como MRR oficial da Betha, recomendo confirmar:

- Se “Valor” representa MRR faturado, valor contratado ou valor comercial cadastrado.
- Se Santa Catarina estava excluída do total anterior.
- Se produtos com preço zero são componentes de pacotes.
- Se serviços, implantações e projetos específicos estão misturados ao recorrente.
- Se o valor de R$ 164,8 mil da SEDUC/AM é mensal ou corresponde a outra modalidade de cobrança.

## 3. Receita por região

| Região | Municípios | Entidades | Valor | Participação |
|---|---:|---:|---:|---:|
| Sul | 319 | 1.138 | R$ 13.060.181 | 52,8% |
| Sudeste | 152 | 409 | R$ 8.396.307 | 33,9% |
| Norte | 57 | 259 | R$ 2.279.943 | 9,2% |
| Centro-Oeste | 36 | 272 | R$ 658.116 | 2,7% |
| Nordeste | 17 | 40 | R$ 358.937 | 1,5% |

Sul e Sudeste concentram 86,7% do valor da carteira. Essa concentração está alinhada com a presença histórica da Betha, mas também evidencia a baixa monetização atual do Nordeste e Centro-Oeste.

## 4. Receita por estado

| UF | Municípios | Entidades | Valor | Participação | Média por município |
|---|---:|---:|---:|---:|---:|
| SC | 182 | 795 | R$ 7.913.108 | 32,0% | R$ 43,5 mil |
| MG | 61 | 169 | R$ 4.211.932 | 17,0% | R$ 69,0 mil |
| PR | 70 | 186 | R$ 3.054.912 | 12,3% | R$ 43,6 mil |
| SP | 66 | 130 | R$ 2.939.228 | 11,9% | R$ 44,5 mil |
| RS | 67 | 157 | R$ 2.092.161 | 8,5% | R$ 31,2 mil |
| RJ | 18 | 100 | R$ 1.153.585 | 4,7% | R$ 64,1 mil |
| AC | 21 | 63 | R$ 835.762 | 3,4% | R$ 39,8 mil |
| AM | 19 | 83 | R$ 713.112 | 2,9% | R$ 37,5 mil |
| RO | 10 | 50 | R$ 485.859 | 2,0% | R$ 48,6 mil |
| MS | 18 | 231 | R$ 458.829 | 1,9% | R$ 25,5 mil |
| BA | 14 | 33 | R$ 256.935 | 1,0% | R$ 18,4 mil |
| PA | 7 | 63 | R$ 245.210 | 1,0% | R$ 35,0 mil |
| MT | 18 | 41 | R$ 199.287 | 0,8% | R$ 11,1 mil |

SC, MG, PR, SP e RS concentram 81,7% do valor total.

### Leitura estratégica

- **MG é o estado mais monetizado fora de SC:** R$ 69 mil por município. A base demonstra boa capacidade de expansão de receita quando há presença estabelecida.
- **RJ também apresenta ticket elevado:** R$ 64 mil por município, embora esteja presente em apenas 18 cidades.
- **RS tem presença territorial relevante, mas ticket menor:** oportunidade de ampliar portfólio com Delta e Alpha.
- **MS possui 231 entidades em apenas 18 municípios**, mas média de apenas R$ 1,99 mil por entidade. Isso sugere grande fragmentação de faturamento entre fundos, câmaras e outras estruturas.
- **MT possui 18 municípios, mas somente R$ 11,1 mil por município**, sinalizando baixa profundidade de portfólio ou contratos de menor porte.
- **BA apresenta 14 municípios, mas somente R$ 18,4 mil por município:** há espaço tanto para expansão territorial quanto para aumento de ticket.
- **CE está concentrado em Maracanaú**, com R$ 90 mil e apenas duas entidades.

## 5. Maiores municípios por valor

| Município | UF | Valor | Entidades | Produtos |
|---|---|---:|---:|---:|
| Atibaia | SP | R$ 562.893 | 3 | 41 |
| Criciúma | SC | R$ 507.297 | 17 | 49 |
| Varginha | MG | R$ 397.479 | 7 | 37 |
| Araras | SP | R$ 372.154 | 5 | 30 |
| Divinópolis | MG | R$ 359.260 | 4 | 44 |
| Resende | RJ | R$ 327.442 | 18 | 27 |
| Francisco Morato | SP | R$ 309.750 | 4 | 36 |
| Ribeirão das Neves | MG | R$ 244.120 | 2 | 25 |
| Fazenda Rio Grande | PR | R$ 234.512 | 4 | 36 |
| Florianópolis | SC | R$ 227.407 | 4 | 22 |

A receita não está excessivamente dependente de poucos municípios:

- Maior município: 2,3% do total.
- Dez maiores: 14,3%.
- Vinte maiores: 21,7%.
- Cem maiores: 50,6%.

Isso é positivo para o risco da carteira: mesmo a perda de um grande município isolado não comprometeria de forma crítica o recorrente total.

## 6. Receita por tipo de entidade

Classificação indicativa baseada no nome da conta:

| Tipo de entidade | Entidades | Valor | Participação |
|---|---:|---:|---:|
| Prefeituras e municípios | 522 | R$ 18.443.356 | 74,5% |
| Câmaras municipais | 471 | R$ 2.521.515 | 10,2% |
| Fundos municipais/estaduais | 730 | R$ 1.754.086 | 7,1% |
| Institutos e fundações | 166 | R$ 679.933 | 2,7% |
| Saneamento e autarquias de água | 56 | R$ 342.040 | 1,4% |
| Consórcios públicos | 72 | R$ 311.817 | 1,3% |
| Demais entidades | 101 | R$ 700.290 | 2,8% |

A prefeitura é a principal âncora econômica do município, mas 25,5% do valor vem de outras entidades. Isso demonstra que o potencial comercial deve ser medido por ecossistema municipal, não apenas por prefeitura.

Um município pode já ser cliente Betha e ainda apresentar oportunidades em:

- Câmara.
- Fundo de saúde.
- Fundo de educação.
- Instituto de previdência.
- Autarquia de água e saneamento.
- Fundação.
- Consórcio público.

## 7. Produtos com maior recorrência

| Produto | Valor | Participação | Municípios |
|---|---:|---:|---:|
| Contabilidade Cloud | R$ 3.009.079 | 12,2% | 500 |
| Tributos Cloud | R$ 2.214.601 | 8,9% | 429 |
| Folha Cloud | R$ 2.084.793 | 8,4% | 501 |
| Compras Cloud | R$ 1.706.568 | 6,9% | 485 |
| Transparência Cloud | R$ 1.063.460 | 4,3% | 481 |
| Educação | R$ 1.001.129 | 4,0% | 207 |
| e-Nota Cloud | R$ 869.611 | 3,5% | 240 |
| Recursos Humanos Cloud | R$ 786.831 | 3,2% | 479 |
| Saúde | R$ 770.527 | 3,1% | 161 |
| Livro Eletrônico | R$ 682.672 | 2,8% | 361 |

Os cinco maiores produtos representam 40,7% do valor. Os dez maiores representam 57,3%.

A carteira está ancorada nos sistemas do core municipal, especialmente contabilidade, tributação, folha, compras e transparência. Isso confirma que esses produtos continuam sendo a principal porta de entrada e sustentação da relação com os municípios.

## 8. Cobertura do portfólio core

| Produto | Municípios com o produto | Espaço dentro da base atual |
|---|---:|---:|
| eSocial | 508 | 73 |
| Folha Cloud | 501 | 80 |
| Contabilidade Cloud | 500 | 81 |
| Tesouraria Cloud | 499 | 82 |
| Planejamento Cloud | 499 | 82 |
| Compras Cloud | 485 | 96 |
| Transparência Cloud | 481 | 100 |
| Recursos Humanos Cloud | 479 | 102 |
| Patrimônio Cloud | 476 | 105 |
| Tributos Cloud | 429 | 152 |
| Cidadão Web Tributos | 396 | 185 |
| Procuradoria Cloud | 390 | 191 |

Esses espaços não devem ser convertidos automaticamente em oportunidades comerciais. É necessário validar:

- Se outra entidade do município é responsável pelo processo.
- Se o produto está incluído em pacote.
- Se há concorrente no módulo.
- Se o município tem porte e estrutura para utilizar o produto.
- Se existem impedimentos contratuais ou técnicos.

Ainda assim, a base mostra uma oportunidade clara: a expansão do portfólio dentro dos municípios atuais pode ser mais rápida que a entrada em novos municípios.

## 9. Produtos com valor zero

A base possui 5.998 linhas com valor zero, equivalentes a 20,4% dos registros.

Alguns exemplos:

| Produto | Registros totais | Registros com valor zero |
|---|---:|---:|
| Contratos Cloud | 1.788 | 1.722 |
| Prestação de Contas | 1.789 | 1.687 |
| Convênios | 1.313 | 1.261 |
| Controladoria | 816 | 803 |
| Minha Cidade App | 198 | 174 |
| Studio Aplicações | 153 | 151 |

A interpretação mais provável é que esses produtos estejam:

- Incluídos em pacotes.
- Liberados sem preço individual.
- Precificados em outro item.
- Disponíveis tecnicamente, mas sem cobrança.
- Associados a contratos legados.

Por isso, produto com valor zero não deve ser classificado automaticamente como produto não utilizado ou oportunidade de venda. Antes disso, é preciso distinguir:

- Produto contratado e incluído no pacote.
- Produto liberado sem utilização.
- Produto gratuito.
- Produto com preço alocado em outro módulo.
- Produto cadastrado incorretamente.

## 10. Profundidade de portfólio

| Produtos com valor positivo no município | Municípios | Valor total |
|---|---:|---:|
| 1 a 5 | 63 | R$ 488 mil |
| 6 a 10 | 54 | R$ 658 mil |
| 11 a 20 | 135 | R$ 5,12 milhões |
| 21 a 30 | 290 | R$ 13,20 milhões |
| 31 ou mais | 39 | R$ 5,29 milhões |

A maior parte da receita está nos municípios com 21 ou mais produtos. Isso reforça que amplitude de portfólio e receita caminham juntas.

Entretanto, alguns municípios de alto valor apresentam contratos concentrados em verticais específicas:

- Manaus: R$ 165,8 mil concentrados principalmente no projeto SADI.
- Santa Cruz do Sul: R$ 90,1 mil concentrados na Saúde.
- Maracanaú: R$ 90,0 mil concentrados em Folha, RH e Ponto.
- Votuporanga, Ubá, São Bento do Sul, Timbó e Pomerode: concentração em Educação.

Esses municípios não devem ser tratados como clientes GRP completos apenas porque possuem faturamento elevado.

## 11. Oportunidades iniciais de expansão

A análise indica três tipos diferentes de oportunidade.

### Completar o core

Municípios com contratos relevantes, mas lacunas específicas no portfólio central:

- Francisco Morato/SP: Procuradoria.
- Itapema/SC: Tributos, Procuradoria e Cidadão Web Tributos.
- Itaguaí/RJ: Tributos, Procuradoria e Cidadão Web Tributos.
- Tubarão/SC: Tributos, Procuradoria e Cidadão Web Tributos.
- Içara/SC: Tributos, Procuradoria e Cidadão Web Tributos.
- Sapucaia/RJ: Cidadão Web Tributos.
- Curitiba/PR: Tributos, Procuradoria e Cidadão Web Tributos.
- Iranduba/AM: Procuradoria.

Essas lacunas precisam ser validadas comercialmente porque a ausência pode decorrer do escopo da entidade atendida.

### Expandir uma vertical para o restante do município

Exemplos:

- Maracanaú possui presença forte em Gestão de Pessoas, mas não apresenta o conjunto administrativo-financeiro.
- Santa Cruz do Sul possui presença forte em Saúde, mas não no core GRP.
- Municípios atendidos apenas em Educação podem ser trabalhados para RH, arrecadação, contabilidade ou serviços ao cidadão.
- Municípios com apenas Tributos podem evoluir para e-Nota, Livro Eletrônico, Procuradoria e serviços digitais.

### Ampliar entidades no mesmo município

O município pode possuir a prefeitura como cliente, mas ainda não ter:

- Câmara.
- Previdência.
- Fundo de saúde.
- Fundo de educação.
- Autarquia de saneamento.
- Fundação ou consórcio.

Essa oportunidade não aparece em uma análise limitada apenas ao número de municípios.

## 12. Implicações para o modelo direto e indireto

### Santa Catarina — venda direta

- 182 municípios.
- 795 entidades.
- R$ 7,91 milhões.
- Média de R$ 43,5 mil por município.
- 32% do valor total da base.

A estratégia direta deve combinar:

1. Defesa da carteira.
2. Expansão de portfólio por entidade.
3. Conquista dos 113 municípios catarinenses ainda sem faturamento.
4. Identificação de produtos sem preço individual.
5. Padronização de pacotes e eliminação de distorções de cadastro.

### Demais estados — canais

- 399 municípios.
- 1.323 entidades.
- R$ 16,84 milhões.
- Média de R$ 42,2 mil por município.
- 68% do valor total.

A carteira indireta já é maior que Santa Catarina em valor absoluto. Isso demonstra que os canais não são apenas uma alternativa de expansão: eles sustentam a maior parcela territorial e financeira da presença nacional da Betha.

As prioridades mais claras são:

- MG: maior receita e ticket fora de SC.
- PR e SP: grande base e valor relevante.
- RS: ampliar ticket e portfólio nos municípios existentes.
- RJ: ticket elevado, com espaço para expansão territorial.
- BA, CE e PA: transformar presenças pontuais em clusters regionais.
- MS e MT: revisar profundidade, preço e composição dos contratos.

## Conclusão

A leitura anterior mostrava uma Betha presente em 581 municípios. A nova base revela algo mais importante: a Betha está presente em 2.118 relações com entidades públicas, com uma carteira ampla de produtos e forte capacidade de expansão dentro dos próprios municípios atendidos.

O crescimento não deve ser medido apenas por “novos municípios”. Os indicadores estratégicos precisam considerar:

- Novos municípios.
- Novas entidades dentro de municípios atuais.
- Novos produtos por entidade.
- Crescimento do ticket municipal.
- Participação do core no município.
- Expansão de verticais.
- Receita líquida após repasse ao canal.
- Dependência de produtos incluídos em pacotes sem preço individual.

A prioridade imediata é reconciliar oficialmente os R$ 16,73 milhões com os R$ 24,75 milhões da coluna “Valor”. A proximidade entre os R$ 16,73 milhões e os R$ 16,84 milhões fora de Santa Catarina indica que o número anterior provavelmente representa a carteira indireta, enquanto a nova base inclui também os R$ 7,91 milhões da operação direta catarinense.


## Giuliano

Leve em consideração o valor total de R$16.731.437,27 pois nesta planilha não fica especificado para você o que é valor de contratos direto Betha, o que é valor obtido do repasse das revendas e o que é referente ao valor obtido através dos contratos fechados pelos parceiros de negócio. Pois os valores obtidos pelas revendas tem um percentual de repasse que vem para a Betha referente a royalts e IaaS e os valores dos contratos fechados pelos parceiros de negócios são 100% da Betha e a Betha repassa um percentual de comissão para eles dependendo do parto do município.


## ChatGPT

Entendido. Essa distinção altera a interpretação financeira da análise: os R$ 24,75 milhões da coluna “Valor” representam uma base comercial heterogênea e não a receita recorrente efetivamente apropriada pela Betha. Vou considerar R$ 16.731.437,27 como o recorrente oficial e tratar os valores da planilha somente como referência de composição contratual, cobertura e presença de produtos.


## ChatGPT

Perfeito. A partir de agora, considerarei **R$ 16.731.437,27 como o recorrente mensal oficial da Betha**.

Os R$ 24,75 milhões somados na planilha não devem ser tratados como receita Betha, porque misturam bases econômicas diferentes:

| Modelo | Relação financeira |
|---|---|
| Venda direta | Contrato direto com a Betha; receita integral da Betha antes de tributos e custos |
| Revenda | A revenda contrata e fatura o cliente; a Betha recebe royalties e IaaS |
| Parceiro de negócios | A Betha contrata e fatura 100% do cliente; depois repassa comissão ao parceiro conforme o porte do município |

## Indicadores financeiros corrigidos

| Indicador | Resultado |
|---|---:|
| Recorrente mensal oficial | R$ 16.731.437,27 |
| Recorrente anualizado | R$ 200.777.247,24 |
| Municípios presentes | 581 |
| Entidades identificadas | 2.118 |
| Média mensal por município | R$ 28.797,65 |
| Média mensal por entidade | R$ 7.899,64 |

As médias são apenas referências gerais, pois os modelos comerciais produzem resultados econômicos diferentes para a Betha.

## O que permanece válido na análise

A planilha continua sendo plenamente útil para analisar:

- Presença nos 581 municípios.
- Quantidade e tipos de entidades atendidas.
- Distribuição territorial.
- Produtos existentes em cada entidade.
- Profundidade do portfólio por município.
- Produtos ausentes.
- Possibilidades de cross-sell.
- Concentração operacional.
- Cobertura por estado e região.
- Municípios atendidos somente por uma vertical.
- Potencial de expansão para outras entidades do mesmo município.

## O que precisa ser corrigido

As tabelas anteriores intituladas “receita por estado”, “receita por produto” e “receita por município” devem ser interpretadas como:

> **Valor cadastrado ou valor comercial presente na base, sem equivalência direta com a receita reconhecida pela Betha.**

Não é seguro utilizar a coluna “Valor” para afirmar que:

- Santa Catarina gera R$ 7,91 milhões para a Betha.
- Os demais estados geram R$ 16,84 milhões.
- Determinado produto representa um percentual da receita Betha.
- Um estado possui maior rentabilidade que outro.
- Uma revenda gera o valor integral exibido na planilha.

Essas conclusões dependeriam da identificação do modelo comercial e da aplicação das respectivas regras de repasse.

## Modelo correto para a análise financeira

A receita Betha deve ser calculada de maneira diferente em cada modelo.

### Venda direta

\[
\text{Receita Betha} = \text{valor faturado ao cliente}
\]

Para chegar à contribuição econômica:

\[
\text{Margem} = \text{receita} - \text{tributos} - \text{custos de implantação, suporte e atendimento}
\]

### Revenda

\[
\text{Receita Betha} = \text{royalties} + \text{IaaS}
\]

O valor total pago pelo município à revenda não representa receita da Betha.

### Parceiro de negócios

\[
\text{Receita bruta Betha} = 100\% \text{ do contrato}
\]

\[
\text{Receita após comissão} =
\text{valor recebido} - \text{comissão do parceiro}
\]

A comissão deve ser aplicada conforme a regra e o porte do município.

## Consequência estratégica

A análise de crescimento precisa separar duas dimensões:

1. **Potencial comercial:** valor total dos contratos e produtos existentes no município.
2. **Potencial econômico para a Betha:** quanto efetivamente permanece com a Betha após royalties, IaaS, comissões, tributos e custos.

Um município pode apresentar grande valor contratual na planilha, mas gerar pouca receita para a Betha se estiver no modelo de revenda. Outro pode apresentar valor semelhante e produzir uma contribuição muito maior por ser venda direta ou parceiro de negócios.

## Estrutura necessária para a análise definitiva

Para calcular receita, margem e potencial por canal, a base ideal deve conter:

- Município e UF.
- Entidade.
- Produto.
- Porte do município.
- Modelo comercial: direto, revenda ou parceiro de negócios.
- Revenda ou parceiro responsável.
- Valor total contratado.
- Valor faturado pela Betha.
- Percentual de royalties.
- Valor de IaaS.
- Percentual ou valor da comissão.
- Receita recorrente Betha.
- Receita líquida após repasse.
- Tributos.
- Custos de implantação e atendimento.
- Vigência e vencimento do contrato.

Com esses campos, será possível comparar corretamente:

- Receita e margem por estado.
- Rentabilidade de cada modelo comercial.
- Desempenho de cada revenda e parceiro.
- Ticket Betha por porte municipal.
- Custo de atendimento.
- Potencial de cross-sell líquido.
- Retorno econômico da expansão territorial.

Portanto, a conclusão financeira correta é: **a Betha possui R$ 16,73 milhões de recorrência mensal em 581 municípios**. A planilha detalhada deve apoiar a leitura de presença, entidades e portfólio, mas não a distribuição financeira desse recorrente enquanto os modelos comerciais e os repasses não estiverem identificados.


## Giuliano

Agora preciso que você conecte esta sua análise na apresentação que você criou no chat Estruturar Plano Estratégico. Como podemos encaixar estas informações nesta apresentação? Você consegue encaixar a sua análise direto no documento que você criou?


## ChatGPT

Consigo, sim. Vou incorporar a análise diretamente na versão atual da apresentação do Planejamento Estratégico 2027, preservando o padrão visual e o raciocínio executivo já construído.

A inclusão precisa reforçar a tese de crescimento por canais sem confundir “valor cadastrado nos contratos” com receita Betha. Vou usar três recursos: o contexto do trabalho anterior para manter a narrativa, a metodologia de apresentações para encaixar os dados sem sobrecarregar os slides e o acesso ao arquivo atual para editar a versão correta.


## ChatGPT

Vou abrir a versão atual da apresentação e mapear a narrativa existente antes de inserir os dados. A integração será feita no próprio arquivo, preservando o estilo e usando R$ 16.731.437,27 como MRR oficial — sem tratar a soma bruta da planilha como receita Betha.


## ChatGPT

A apresentação tem 18 slides e a melhor conexão é inserir a análise logo após o diagnóstico atual. Também vou corrigir a ambiguidade do slide existente: os “173 municípios/14 estados” representam o recorte do ecossistema de canais, enquanto a nova base representa a presença total faturada da Betha.


## ChatGPT

A conexão ficou estruturada em quatro novos slides: dimensão da presença faturada, três alavancas de crescimento, cobertura do portfólio core e estratégia territorial direta/indireta. Estou na revisão visual final, ajustando legibilidade e consistência dos indicadores financeiros.


## ChatGPT

Consegui integrar a análise diretamente na apresentação. O documento foi atualizado de 18 para 22 slides, mantendo o padrão visual original.

Principais inclusões:

- Presença faturada: 581 municípios, 17 UFs, 2.118 entidades e 112 produtos.
- MRR oficial de R$ 16.731.437,27 e ARR equivalente de R$ 200,78 milhões.
- Crescimento estruturado em três dimensões: novos municípios, novas entidades e novos produtos.
- Cobertura dos principais produtos do core e oportunidades de cross-sell.
- Estratégia territorial diferenciada:
  - Santa Catarina: venda direta, 182 de 295 municípios.
  - Demais estados: expansão exclusivamente por canais.
- Esclarecimento entre o recorte de Canais — 173 municípios — e a presença faturada total da Betha.
- Nota metodológica impedindo que os valores brutos da planilha sejam interpretados como receita Betha.

A apresentação completa foi renderizada e validada, sem problemas de overflow ou integridade.

[Baixar a apresentação atualizada](sandbox:/workspace/scratch/cc61b485ce2c/output/Planejamento_Estrategico_2027_Gerencia_de_Canais_v4_atualizado.pptx)


## ChatGPT

## Monitoramento de contratos GRP — atualização executiva

Este é o primeiro levantamento consolidado disponível nesta rotina; portanto, os registros abaixo formam a linha de base para as próximas comparações.

Foram identificados três movimentos de alta relevância comercial: uma ata de R$ 958,6 mil em Mossoró/RN, uma licitação estimada em R$ 5,17 milhões em Porto Feliz/SP e um contrato vencido, sem renovação localizada, na Câmara de Tombos/MG.

### Novidades e mudanças relevantes

| Município/UF | Evento e concorrente | Objeto e módulos | Valores | Vigência/situação | Avaliação para a Betha |
|---|---|---|---|---|---|
| Mossoró/RN | Ata de Registro de Preços 02/2026 — Sistemas Integrados Aplicado ao Setor Público Ltda., CNPJ 18.603.971/0001-91 | Licença de software integrado: execução contábil-orçamentária, administração financeira e controle | Total máximo: **R$ 958.600,00**; média equivalente: **R$ 79.883,33/mês** | Assinada em 10/04/2026; vigente até 10/04/2027 | **Muito alta.** Contrato amplo de core, com potencial para adesões e contratações derivadas. Atuação via canal no RN; mapear entidades participantes e quantitativos efetivamente consumidos. genui{"citation":{"ref":"turn12view3"}} |
| Mossoró/RN — PREVI | Contrato com Sistemas Integrados Aplicado ao Setor Público Ltda., mesmo CNPJ | Execução contábil-orçamentária, administração financeira e controle | Total: **R$ 154.000,00**; aproximadamente **R$ 12.833,33/mês** | Vigência até 19/05/2027; contrato ativo | **Alta.** Entidade previdenciária com core financeiro isolado; oportunidade para canal especializado em RPPS e integração com folha/previdenciário. genui{"citation":{"ref":"turn7search0"}} |
| Porto Feliz/SP | Pregão Eletrônico 58/2026; fornecedor ainda não confirmado | Plataforma GRP para Prefeitura, Câmara, SAAE e PortoPrev. Inclui contabilidade, orçamento, tesouraria, planejamento, compras, licitações, contratos, controle interno, almoxarifado e outros módulos | Estimado: **R$ 5.166.791,51** por 12 meses; média contratual equivalente de **R$ 430.565,96/mês**, incluindo implantação e demais serviços | Propostas encerradas em 17/09/2026; PNCP ainda exibia homologação em R$ 0,00 no registro consultado | **Crítica.** É a maior oportunidade localizada. Monitorar homologação, recursos e contrato. Atuação Betha necessariamente via canal em SP. genui{"citation":{"ref":"turn8search4"}} |
| Câmara de Coxim/MS | Pregão Presencial 1/2026; vencedor não localizado | Locação de sistema integrado de gestão pública | Estimado: **R$ 87.633,00**; média equivalente de **R$ 7.302,75/mês** | Sessão em 17/07/2026; resultado/contrato não localizado | **Alta.** Verificar vencedor e módulos contratados; oportunidade de cobertura por canal em MS e referência para outras câmaras da região. genui{"citation":{"ref":"turn12view1"}} |
| Diamantina/MG — FUMPREV | Adesão 1/2026 — Memory Projetos e Desenvolvimento de Sistemas Ltda., CNPJ 71.000.731/0001-85 | Sistema administrativo estruturante web; implantação, migração, datacenter, planejamento e orçamento, suporte e reserva técnica | **R$ 160.722,00**; composição mistura implantação, recorrência e horas técnicas | Homologada; data final da vigência contratual não disponível no registro consultado | **Alta.** Confirma avanço da Memory em RPPS mineiros. Recomenda-se canal com especialização em previdência municipal. genui{"citation":{"ref":"turn7search6"}} |
| Câmara de Tombos/MG | Primeiro aditivo — Memory Projetos, CNPJ 71.000.731/0001-85 | GRP web/SIAFIC, migração, treinamento, manutenção e suporte | Total: **R$ 22.403,88**; **R$ 1.866,99/mês** | Vigência terminou em **12/09/2026**; não foi localizada nova prorrogação | **Oportunidade imediata.** Confirmar se houve renovação não publicada ou contratação emergencial. Abordagem via canal em MG. genui{"citation":{"ref":"turn12view2"}} |
| Câmara de Águas Formosas/MG | Aviso de contratação direta 003/2026 — fornecedor não definido | Contabilidade, orçamento, tesouraria, EFD-Reinf, RH/folha, eSocial, compras, licitações, contratos, obras e editais, em nuvem | Valor sigiloso | Processo **suspenso**; propostas previstas para agosto de 2026 | **Alta se reaberto.** Escopo fortemente aderente ao core Betha; acompanhar republicação e motivos da suspensão com canal mineiro. genui{"citation":{"ref":"turn7search1"}} |
| Mossoró/RN | Aditivo do Contrato 03/2022 — Sistemas Integrados Aplicado ao Setor Público | Renovação transitória do sistema anterior | **R$ 106.939,14** por três meses; **R$ 35.646,38/mês** | Vigência encerrada em 08/04/2026 | **Mudança relevante:** o aditivo curto foi sucedido pela nova ARP de R$ 958,6 mil, indicando consolidação/expansão do fornecedor. genui{"citation":{"ref":"turn12view4"}} |

### Contratos e oportunidades priorizados por vencimento

1. **Câmara de Tombos/MG — vencido em 12/09/2026**  
   Prioridade imediata. Confirmar renovação, dispensa emergencial ou preparação de novo processo.

2. **ARP Mossoró/RN — vence em 10/04/2027**  
   Iniciar inteligência comercial até dezembro de 2026. Avaliar consumo da ata, entidades aderentes e satisfação operacional.

3. **PREVI-Mossoró/RN — vence em 19/05/2027**  
   Trabalhar diagnóstico de RPPS, integrações e módulos ausentes entre novembro de 2026 e janeiro de 2027.

4. **Diamantina/MG — vencimento não publicado**  
   A adesão foi estruturada para itens anuais, mas a data contratual precisa ser confirmada antes de classificar o mês de renovação.

5. **Porto Feliz/SP — contratação em definição**  
   Ainda não é vencimento: é oportunidade competitiva corrente. A prioridade é identificar homologação, vencedor e eventual fase recursal.

### Leitura estratégica

- O movimento mais importante é a concentração de **contabilidade, orçamento, financeiro e controle** em contratações integradas, geralmente acompanhadas de nuvem, migração, suporte e adequação ao SIAFIC.
- MG apresenta oportunidades de menor ticket, porém replicáveis em câmaras e RPPS. Recomenda-se um canal especializado e playbook padronizado para esses entes.
- Porto Feliz/SP exige acompanhamento executivo: envolve quatro entidades municipais e pode gerar referência regional relevante.
- Não foi localizada, neste ciclo, nova oportunidade GRP de alta confiança em Santa Catarina que justifique acionamento imediato da venda direta.
- Não foram verificadas rescisões de contratos GRP entre os registros selecionados.
- Atenção metodológica: no PNCP, o campo **“Fonte/Plataforma”** pode indicar o software utilizado pelo órgão para publicar a contratação — IPM, Elotech, Fiorilli ou Pública, por exemplo — e não a empresa contratada. A classificação como concorrente somente foi feita quando o fornecedor foi confirmado no contrato, ata ou diário oficial.


## ChatGPT

## Relatório executivo — monitoramento GRP municipal

**Data de corte: 2 de novembro de 2026.** Foram consideradas somente ocorrências novas, recém-publicadas ou com mudança relevante em relação ao levantamento anterior.

### Principais sinais de mercado

- **Santa Catarina:** Brusque contratou emergencialmente a IPM por **R$ 2,53 milhões**, com vigência até outubro de 2027. É o evento comercial mais importante do período para venda direta: o caráter emergencial indica necessidade de acompanhar desde já o processo definitivo.
- **Oportunidade imediata:** Bodoquena/MS está recebendo propostas para um GRP completo, estimado em **R$ 1,14 milhão**, até **13/11/2026**.
- **Fortalecimento competitivo:** IPM ganhou contratos relevantes em Juatuba/MG e Brusque/SC; SMARAPD venceu Ourinhos/SP e iniciou contrato de cinco anos em Ipatinga/MG; Elotech venceu Quatiguá/PR.
- **Janela de substituição:** Fronteira/MG possui contrato emergencial que vence em **09/01/2027**. Flórida/PR e Cruzmaltina/PR também entram em janela comercial no primeiro trimestre de 2027.
- **Alerta metodológico:** “Fonte/Plataforma” no PNCP — por exemplo, Pública Tecnologia, IPM, Fiorilli ou CECAM — **não significa que essa empresa seja a contratada**. Somente classifiquei concorrente quando havia fornecedor/arrematante ou contrato identificado.

## Novos contratos e mudanças relevantes

| Município/UF | Concorrente | Objeto e módulos | Valores | Assinatura e vigência | Modalidade / situação | Avaliação para a Betha |
|---|---|---|---|---|---|---|
| **Brusque/SC** | **IPM Sistemas** — 01.258.027/0001-41 | Continuidade do GRP integrado. Entre os 132 itens constam planejamento e orçamento, contabilidade/financeiro, controle interno, pessoal, folha, ponto e outros módulos | Total **R$ 2.525.053,76**; equivalente médio **R$ 210.421,15/mês** | 28/10/26 a 28/10/27 | Dispensa emergencial; vigente | **Prioridade máxima – venda direta.** Mapear imediatamente o processo definitivo, requisitos técnicos, transição e satisfação do município. O contrato emergencial pode ser encerrado antes se houver solução substitutiva, conforme o futuro processo. genui{"citation":{"ref":"turn17view0"}} |
| **Ourinhos/SP** | **SMARAPD** — 50.735.505/0001-72 | GRP integrado para Prefeitura, Câmara e Instituto de Previdência; licenças, hospedagem, segurança, implantação, manutenção e treinamento | **R$ 230.783,33/mês**; **R$ 2.769.400,00/ano e total** | 15/10/26 a 14/10/27 | Pregão eletrônico 11/2026; contrato vigente | Alta relevância pelo porte, abrangência institucional e receita. Atuação por **canal em SP**; iniciar inteligência de satisfação e implantação no 1º semestre de 2027. genui{"citation":{"refs":["turn20search0","turn20search1"]}} |
| **Juatuba/MG** | **IPM Sistemas** — 01.258.027/0001-41 | GRP web nativo, usuários ilimitados, implantação, migração, parametrização, treinamento, suporte, manutenção e datacenter | Total **R$ 3.089.128,00/60 meses**; média calculada **R$ 51.485,47/mês** e **R$ 617.825,60/ano** | 14/09/26 a 13/09/31; publicado em 29/10/26 | Pregão eletrônico 90039/2026; contratado | Alta relevância competitiva, mas baixa oportunidade de substituição no curto prazo. Canal mineiro deve acompanhar implantação e eventuais falhas de entrega. genui{"citation":{"refs":["turn21search2","turn21search5"]}} |
| **Ipatinga/MG** | **SMARAPD** — 50.735.505/0001-72 | GRP integrado aderente a SIAFIC, PCASP/NBCASP, SICOM/TCE-MG, SIOPS, SIOPE, SICONFI, transparência e demais integrações | PNCP informa **R$ 0,00**, mas isso representa dado financeiro não publicado, e não contrato sem valor. Mensal, anual e total: **indisponíveis** | 09/10/26 a 08/10/31 | Contrato 112/2026; modalidade não identificada no registro consultado | Movimento defensivo importante da SMARAPD em município de grande porte. Desenvolver presença por **canal em MG**, focada inicialmente em entidades e módulos periféricos. genui{"citation":{"ref":"turn14search0"}} |
| **Quatiguá/PR** | **Elotech** — 80.896.194/0001-94 | Sistema integrado para finanças, tributos, gestão de pessoas e administração, com usuários ilimitados | **R$ 1.987.000,00 total**; equivalente médio, se distribuído pelos 12 meses, **R$ 165.583,33/mês** | 13/10/26 a 13/10/27 | Pregão eletrônico 21/2026; contratado | Alta relevância e contrato substancial para município pequeno. Canal no Paraná deve acompanhar implantação, preço efetivo por módulo e satisfação. genui{"citation":{"refs":["turn21search1","turn21search6"]}} |
| **São Mateus/ES** | **E&L Produções de Software** — 39.781.752/0001-72 | Licença de uso, implantação, customização, treinamento e suporte técnico | **R$ 183 mil total**; média calculada **R$ 15.250/mês** | 09/10/26 a 09/10/27 | Inexigibilidade; vigente | Relevância média. O modelo de contratação direta merece análise jurídica e técnica para eventual contestação comercial ou abordagem por canal no ES. Módulos específicos não detalhados na publicação recuperada. genui{"citation":{"ref":"turn19search3"}} |
| **Mossoró/RN** | **Sistemas Integrados Aplicado ao Setor Público – ASPEC** — 18.603.971/0001-91 | Execução contábil-orçamentária, administração financeira, controle e suporte presencial | **R$ 414.600,00/ano**; média **R$ 34.550/mês** | 30/04/26 a 30/04/27; extrato republicado em 27/10/26 | Pregão 01/2026; vigente | Complementa a ARP já monitorada e aumenta a exposição da ASPEC no município. Canal no RN deve trabalhar a janela de abril de 2027 de maneira coordenada entre Prefeitura e PREVI. genui{"citation":{"refs":["turn19search5","turn19search9"]}} |
| **Fronteira/MG** | **Paulista Tecnologia e Serviços** — 00.562.341/0001-50 | Licença temporária de GRP integrado, suporte e atualizações legais/corretivas para Executivo e Legislativo | **R$ 134.998,20/4 meses**; média **R$ 33.749,55/mês** | 10/09/26 a 09/01/27 | Dispensa emergencial; vigente | **Prioridade máxima por canal em MG.** Contrato curto sugere processo definitivo, nova emergência ou migração iminente. genui{"citation":{"ref":"turn13search4"}} |

## Licitações e oportunidades em andamento

| Município/UF | Escopo | Valor e prazo | Situação | Recomendação |
|---|---|---|---|---|
| **Bodoquena/MS** | GRP em nuvem para administração municipal: contabilidade, tesouraria, planejamento, compras/contratos, folha, eSocial, tributos, NFS-e, atendimento ao contribuinte, controladoria, educação e outros | Estimado em **R$ 1.144.525,46**; propostas até **13/11/26, 8h59** | Pregão eletrônico 16/2026, disputa aberta, sem SRP; fornecedor ainda não definido | **Ação imediata via canal em MS.** O edital possui 114 itens e inclui implantação, datacenter e suporte presencial, permitindo modelagem por módulos e serviços. genui{"citation":{"refs":["turn15search0","turn15search3"]}} |
| **Campinápolis/MT** | GRP web em nuvem para Executivo, Legislativo e Fundo de Previdência; implantação, manutenção, suporte, treinamento e segurança | Estimativa **sigilosa**; propostas encerradas em 23/10/26 | Pregão eletrônico 17/2026/SRP; ainda sem homologação ou fornecedor divulgado | Canal em MT deve monitorar diariamente homologação, ata e contrato. Grande relevância pela cobertura de três entidades. genui{"citation":{"ref":"turn15search1"}} |
| **Valparaíso/SP** | GRP integrado/SIAFIC para Prefeitura, Câmara e Departamento de Água e Esgoto; conversão, implantação, treinamento, suporte e evolução | Valor não publicado; cotação encerrada em 23/10/26 | Pesquisa/cotação; nenhum resultado ou contrato cadastrado | Indício de contratação futura. Canal paulista deve buscar o termo de referência e influenciar requisitos antes da licitação. genui{"citation":{"ref":"turn19search8"}} |
| **Paraibuna/SP** | GRP nativamente web para Prefeitura, Câmara, Fundação Cultural e Instituto de Previdência | Estimado em **R$ 1.419.738,22** | Pregão eletrônico 50/2026; propostas encerradas, mas homologação, fornecedor e contrato ainda não publicados | Alta prioridade de monitoramento por canal. A plataforma indicada é **CECAM**, mas isso não comprova que a CECAM seja a vencedora. genui{"citation":{"refs":["turn15search4","turn15search5"]}} |

## Vencimentos priorizados

| Prioridade | Município/UF | Fornecedor | Vencimento provável | Motivo e ação |
|---:|---|---|---|---|
| **1** | Fronteira/MG | Paulista Tecnologia | **09/01/2027** | Emergencial de quatro meses. Identificar imediatamente o processo substitutivo e ativar canal mineiro. |
| **2** | Flórida/PR | Elotech | **10/01/2027** | Contrato temporário de cinco meses para GRP completo. Janela curta e clara para canal no Paraná. genui{"citation":{"ref":"turn16search1"}} |
| **3** | Cruzmaltina/PR | Elotech | **07/02/2027** | Quarto aditivo do Contrato 007/2022. Verificar se haverá nova prorrogação ou licitação substitutiva. Valor atualizado não localizado. genui{"citation":{"ref":"turn14search5"}} |
| **4** | Mossoró/RN | ASPEC | **10/04/2027** | Vencimento da ARP 02/2026 já monitorada; preparar canal e diagnóstico competitivo até janeiro. |
| **5** | Mossoró/RN | ASPEC | **30/04/2027** | Contrato contábil-financeiro da Secretaria de Administração; oportunidade de abordagem conjunta com a ARP. |
| **6** | PREVI-Mossoró/RN | ASPEC | **19/05/2027** | Entidade previdenciária com ciclo próximo ao da Prefeitura; estratégia municipal integrada. |
| **7** | Quatiguá/PR | Elotech | **13/10/2027** | Não é oportunidade imediata, mas a implantação recente permite iniciar acompanhamento de satisfação no segundo trimestre de 2027. |
| **8** | Ourinhos/SP | SMARAPD | **14/10/2027** | Contrato anual de alto valor; preparar inteligência competitiva e canal com antecedência. |
| **9** | Brusque/SC | IPM | **28/10/2027 ou antes** | Apesar da data formal, a natureza emergencial torna possível um processo definitivo anterior. Deve permanecer no radar contínuo de venda direta. |

## Casos anteriores sem mudança material

- **Porto Feliz/SP:** continua sem homologação ou vencedor publicado; valor estimado permanece em **R$ 5.166.791,51**.
- **Campinápolis/MT, Paraibuna/SP e Porto Feliz/SP:** “R$ 0,00 homologado” significa ausência de resultado financeiro publicado, não contratação gratuita.
- Não foi localizada, nesta rodada, nova contratação substitutiva conclusiva para **Tombos/MG** nem retomada confirmada do procedimento suspenso de **Águas Formosas/MG**.

### Direcionamento comercial

A prioridade da Betha deve ser:

1. **Venda direta em SC:** Brusque, com atuação imediata sobre o processo definitivo. Camboriú apareceu em contratação de controle físico-financeiro de projetos, mas não como GRP core; portanto é oportunidade complementar, não prioritária.
2. **Canais com oportunidade aberta:** Bodoquena/MS, Campinápolis/MT, Paraibuna/SP e Valparaíso/SP.
3. **Canais para substituição próxima:** Fronteira/MG, Flórida/PR, Cruzmaltina/PR e Mossoró/RN.
4. **Inteligência competitiva:** acompanhar implantação e qualidade de entrega da IPM em Juatuba e Brusque, da SMARAPD em Ourinhos e Ipatinga, e da Elotech em Quatiguá.
