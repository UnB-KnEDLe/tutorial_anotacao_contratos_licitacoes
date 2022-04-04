# Ato de "Aviso de Licitação"

Os atos de "Aviso de Licitação" podem aparecer também da seguinte forma: "Aviso de Abertura", "Aviso de Abertura de Licitação Exclusiva", "Aviso de Pregão Eletrônico" e "Aviso de Abertura de Licitação Retificação".

## Como encontrar um ato de "Aviso de Licitação"?

Primeiro é necessário procurar pelos atos de aviso de licitação bastando pressionar CTRL+F e pesquisar pelos termos "aviso" e procurar se essa palavra é acompanhada de:

- Aviso de Abertura
- Aviso de Abertura de Licitação Exclusiva
- Aviso do Pregão Eletrônico
- Aviso de Abertura de Licitação Retificação

Após encontrar uma ou mais publicaçes associadas, deve-se fazer a correspondência de cada bloco de texto em relação a um dos padrões definidos a seguir. Anote as entidades conforme os labels descritos na tabela a seguir.

## Tabela de entidades e padrões

As entidades que deverão ser identificadas são:

ID | Label | Entidade (descrição)  | Observação
------- | ------- | ------- | ------- 
(1) | numero_licitacao | Número da Licitação | anotar todo o código alfanumérico. Por exemplo, "11/2021" ou "01/2020-CEB"
(2) | modalidade_licitacao | Modalidade da Licitação | Anotar conforme os tipos: "Concorrência", "Tomada de Preços", "Pregão Eletrônico", "Pregão Presencial", "Credenciamento", "RDC" etc
(3) | orgao_licitante | Nome do Órgão Licitante | consulte a lista [aqui](../listagem_orgaos.md)
(4) | tipo_objeto | Tipo de Objeto | Aparece dentro da label (5), Objeto da Licitação. Podem ser: "Alienação de Bens", "Aquisições", "Prestação de Serviços", "Concessão", "Permissão", "Locação", "Obras e serviços de engenharia"
(5) | objeto_licitacao | Objeto da Licitação | anotar toda a sentença até o ponto final "." ou ponto e vírgula ";"
(6) | processo_gdf | Número do Processo do GDF | anotar somente o código numérico
(7) | valor_estimado_contratacao | Valor Estimado da Contratação | anotar somente números
(8) | data_abertura_licitacao | Data de Abertura da Licitação | em caso de existirem mais de uma data, dar preferência para "Data de Abertura" (não anotar a hora)
(9) | sistema_compras | Sistema de Compras Utilizado | Caso apareça na publicação, marcar o nome completo, como: "ComprasNet", "Licitações-e (Banco do Brasil)", "ComprasDF", "e-ComprasDF". Se aparecer o site, também marcar a URL completa.
(10) | codigo_licitacao_sistema_compras | Código da Licitação no Sistema de Compras Utilizada | Marcar somente os números após a palavra "UASG"
(11) | nome_responsavel | Nome do Responsável pela Publicação do Ato |	Não é nome de nenhum dos signatários das partes (órgão e entidade)
(12) | AVISO_LICITACAO | Publicação completa | anotar toda a publicação referente ao ato, envolvendo também as suas entidades

## Exemplos


AVISO DE ABERTURA DE LICITACAO<br>
**PREGAO ELETRONICO[2]** No **34/2019[1]**.<br>
Processo: **001-001334/2019[6]**. Objeto: **Registro de precos para eventual {contratacao}[4] de servicos de organizacao de eventos e correlatos, a serem realizados nas dependencias internas e externas da Camara Legislativa do Distrito Federal, sob demanda, abrangendo o planejamento operacional, apoio logistico, organizacao, execucao, montagem de infraestrutura,  fornecimento de bens e  mao-de-obra, independentemente da prestacao de servicos concomitantes, utilizando mobiliario necessario e adequado, fornecimento de layouts para estandes e exposicoes, compreendendo a montagem, desmontagem, limpeza, manutencao, sonorizacao, iluminacao, instalacoes eletrica e equipamentos, conforme os requisitos e condicoes estabelecidos no Termo de Referencia - Anexo I, do Edital[5]**. Valor estimado: R$ **6.014.928,12[7]**. Data/hora da Sessao Publica: **25/10/2019[8]**. Local: Internet, no endereco **www.comprasnet.gov.br[9]**. Tipo: menor preco global. O edital encontra-se nos enderecos: **www.comprasnet.gov.br[9]** (UASG **974004[10]**) e www.cl.df.gov.br, no link transparencia. Maiores informacoes (61) 3348-8650.<br>
Brasilia/DF, 14 de outubro de 2019.<br>
**DOUGLAS BRUNO GONCALVES DE LAET[11]**.<br><br><br>



AVISO DE **TOMADA DE PREÇOS[2]** Nº **01/2021[1]**<br>
Processo **00220-00000503/2021-51[6]**<br>
O DISTRITO FEDERAL, por meio da **SECRETARIA DE ESTADO DE ESPORTE E LAZER DO DISTRITO FEDERAL[3]**, autorizada pelo Decreto Distrital nº 41.497/2020, por meio da Comissão Permanente de Licitação, doravante denominada CPL/SEL/GDF, mediante a Portaria nº 186, de 27 de novembro de 2020, publicada no DODF nº 225, de 01 de dezembro de 2020, torna público, para conhecimento dos interessados, que fará licitação, cujo objeto é: **“{CONTRATAÇÃO}[4] DE EMPRESA ESPECIALIZADA EM LIMPEZA, NIVELAMENTO E EXECUÇÃO DE PISO EM CONCRETO ARMADO dos terrenos onde serão implantados os módulos esportivos, objeto do processo {00220-00000398/2021-50}[6]"[5]**, sob a modalidade de **TOMADA DE PREÇOS[2]**, Tipo MENOR PREÇO GLOBAL POR LOTE, Adjudicação POR LOTE. VALOR TOTAL ESTIMADO: R$ **1.348.175,68[7]** (um milhão, trezentos e quarenta e oito mil, cento e setenta e cinco reais e sessenta e oito centavos), em SESSÃO PÚBLICA: no dia 03 de agosto de 2021, às 13h00min, DATA LIMITE DE RECEBIMENTO DOS DOCUMENTOS DE HABILITAÇÃO E PROPOSTA DE PREÇOS: até às 13:00 horas do dia **03 de agosto de 2021[8]**, conforme especificações e quantitativos constantes no Edital. O Edital encontra-se disponibilizado, sem ônus, no setor de Comissão Permanente de Licitação, doravante denominada CPL/SEL/GDF no endereço SCS, Quadra 4, Edifício Luiz Carlos Botelho, 7º andar - Bairro Asa Sul – Brasília/DF; CEP: 70.304-000, e na página da Secretaria de Estado de Esporte e Lazer do Distrito Federal – SEL/GDF, www.esporte.df.gov.br (clicar em “Publicações”).<br>
**THIAGO MOREIRA CARVALHO DOS SANTOS[11]**<br>
Presidente da Comissão<br><br><br>



AVISO DE ABERTURA<br>
**PREGÃO ELETRÔNICO[2]** POR SRP Nº **33/2022[1]** - UASG **926119[10]**<br>
Objeto: **{Aquisição}[4] de material médico hospitalar CATETER INTRAVENOSO PERIFÉRICO 14G e outros, para atender a demanda da Secretaria de Saúde – DF, conforme especificações e quantitativos constantes no Anexo I do Edital[5]**. Processo **00060-00437454/2021-51[6]**. Total de 37 itens (Ampla concorrência e cotas destinadas às ME/EPPs). Valor Estimado: R$ **7.833.355,042[7]**. Cadastro das Propostas: a partir de 31/01/2022. Abertura das Propostas **10/02/2022[8]**, às 9h, horário de Brasília, no site **www.
net.gov.br[9]**. O Edital encontra-se disponibilizado, sem ônus, no site, ou, com ônus, no endereço: SRTVN, Quadra 701, Conjunto C, Edifício PO 700, 2º andar, sala: Central de Compras/DAQ/SUAG, CEP: 70.723-040 – Brasília/DF.<br>
**PEDRO PAULO B.D.C. FLEURY[11]**<br>
Pregoeiro<br><br><br>



AVISO DE LICITAÇÃO<br>
**PREGÃO ELETRÔNICO[2]** Nº **18/2022[1]** - UASG **974002[10]**<br>
A Pregoeira comunica aos interessados que a fim de atender a demanda do **Jardim Botânico e Brasília - JBB[3]**, a Subsecretaria de Compras Governamentais - SCG/SPLAN/SEEC operacionalizará licitação do PE nº **18/2022[2]** no sistema **Comprasnet[9]**, cujo objeto é a **{aquisição}[4] de bomba com vazão, bomba hidráulica, motobomba, bloco de cimento, cimento, relê, disjuntor, mini contactor, etc, conforme especificações e condições estabelecidas no termo de referência constante do Anexo I do Edital[5]**. Valor total estimado: R$ **46.237,77[7]**. Tipo de Licitação: Menor Preço. Unidade Orçamentária: 150106; Programa de Trabalho: 18.122.8210.8517.9658. Elemento de despesa: 33.90.30 e 44.90.52. Fonte: 100 e 120. Abertura das propostas dia **21/02/2022[8]**, às 9h30min. Processo **00195-00000275/2021-73[6]**. O edital poderá ser retirado no endereço eletrônico: **www.comprasgovernamentais.gov.br[9]**. Informações pelo e-mail: pregoeirosulog08@economia.df.gov.br.<br>
Brasília/DF, 04 de fevereiro de 2022<br>
**RITA DE CÁSSIA GODINHO DE CAMPOS[11]**<br><br><br>



AVISO DE LICITAÇÃO<br>
**PREGÃO ELETRÔNICO[2]** Nº **06/2022[1]**<br>
Objeto: **{Contratação}[4] de empresa especializada para fornecimento de 13 (treze) notebooks de alta performance e prestação de garantia on site de 12 (doze) meses, para atendimento das demandas internas do {Tribunal de Contas do Distrito Federal}[3] [5]**. Processo: **00600-00000249/2021-80-TCDF[6]**. Valor estimado: R$ **155.654,46[7]**; enquadramento: natureza 4.4.90.52.35 – Equipamentos e Material Permanente; classificação funcional e programática 01.126.8231.1471.0005 - Modernização de Sistema de Informação do TCDF; fonte de Recursos 100. Data limite de recebimento das propostas: **17/02/2022[8]**, às 14h30min. Cópia do Edital encontra-se à disposição no Serviço de Licitação, localizado no 2º Andar do Ed. Anexo do TCDF, telefone (61) 3314- 2742 ou pelos sítios: www.tc.df.gov.br e **www.comprasnet.gov.br[9]** (UASG: **974003[10]**). A Sessão Pública será processada no sítio do **ComprasNet[9]**, nos termos do Edital. Em atendimento à Lei Distrital nº 5.453/2015, as informações referentes ao certame também estão disponíveis no sítio www.tc.df.gov.br, link: Consulta Processo do TCDF.<br>
Brasília/DF, 02 de fevereiro de 2022<br>
**ALESSANDRA RIBEIRO ASTUTI[11]**<br>
Pregoeira
