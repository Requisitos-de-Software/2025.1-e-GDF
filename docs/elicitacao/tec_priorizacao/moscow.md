# MoSCoW

## Introdução

A técnica MoSCoW é uma abordagem de priorização usada para identificar a importância relativa de diferentes requisitos em um projeto.

 Segundo o **IIBA (2009)**, "as quatro letras maiúsculas no esquema de priorização MoSCoW representam quatro possíveis classificações de prioridade para os requisitos em um conjunto: **Must (Deve)**, **Should (Deveria)**, **Could (Poderia)** e **Won’t (Não será)**". No contexto do projeto do aplicativo **e-GDF**, essa técnica foi utilizada para definir quais funcionalidades e requisitos são essenciais, desejáveis, opcionais ou fora do escopo neste momento. Logo abaixo, será apresentada uma explicação mais detalhada sobre cada um desses níveis de prioridade, a fim de aprofundar o entendimento da técnica.

### [Must Have](#must-have) - Essencial
O requisito **deve ser atendido** para que a solução seja considerada um sucesso.

### [Should Have](#should-have) - Importante, mas não Essencial
O requisito é **importante** e **deveria ser incluído** na solução, se possível, mas **não é essencial** para o sucesso imediato.

### [Could Have](#could-have) - Bom ter, mas não essencial
É um recurso **desejável**, mas que pode ser **adiado ou até eliminado**, sendo implementado apenas se houver tempo e recursos suficientes.

### [Won’t Have](#wont-have) - Pode ser implementado no futuro
Indica um requisito **não implementado no momento**, mas **possível no futuro**. Essa categoria pode gerar **ambiguidade**, pois pode ser interpretada como "não agora" ou "nunca". A técnica MoSCoW, apesar de clara, **não define critérios objetivos** para classificar os requisitos, o que pode levar a disputas por classificações mais prioritárias, como “Must”. Quando mal aplicada, pode **comprometer a efetividade da priorização**.

## Metodologia

A técnica MoSCoW foi aplicada durante uma reunião realizada via **Microsoft Teams** com 3  membros da equipe do **eGDF**, que desempenharam o papel de **mediadores** e um usuário do aplicativo, que desempenhou o papel de **cliente**. A reunião envolveu uma discussão aprofundada sobre os **requisitos elicitados**, que foram então classificados com base em critérios como **impacto para o usuário**, **viabilidade técnica**, **alinhamento com os objetivos do governo** e **disponibilidade de recursos**. Embora a técnica seja simples, foi necessário um cuidado especial para garantir que as classificações fossem coerentes e refletissem fielmente o valor e a urgência de cada requisito.


## Participantes

| Nome                 | Função        |
| -------------------- | ------------- |
| [Ana Victória](https://github.com/navicg)| Mediador|
| [Gabriel Lopes](https://github.com/BrzGab) | Mediador |
| [Karoline Luz](https://github.com/KarolineLuz)   | Mediador |
| **João Vitor** | Cliente       |

<font size="3"><p style="text-align: center">Fonte: [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz).</p></font>


## Reunião da aplicação da técnica

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube/embed/t8xXrzlBbdM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=rZacw2V8qPA" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Requisitos Priorizados

A **Tabela 1** e **2** apresenta os requisitos funcionais e não funcionais, respectivamente, sendo que cada linha contém um **ID**, sua respectiva descrição, um **hyperlink de rastreabilidade** que direciona à página da(s) **técnica(s)** que elicitou o requisito em questão e se ele foi **implementado** ou não, e também o nível de **prioridade**.

A **legenda** para cada sigla é a seguinte:

- **RFx**: Requisito Funcional nºx
- **INTx***: Requisito nºx elicitado pela Introspecção
- **BRx**: Requisito nºx elicitado pelo Brainstorming
- **ADx**: Requisito nºx elicitado pelo Analise de Documentos
- **ENx**: Requisito nºx elicitado pela Entevista
- **MH**: Prioridade: **Must Have**
- **SH**: Prioridade: **Should Have**
- **CH**: Prioridade: **Could Have**
- **WH**: Prioridade: **Won't Have**

### Tabela 1: Requisitos Funcionais
| ID   | Descrição                                                                                                                                                               | Rastreabilidade                                                  | Implementação | Prioridade (MoSCoW) |
 | ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ------------- | ------------------ |
 |      |                                                                                                                                                                         |                                                                  |               |                    |
 | RF01   | O usuário deve conseguir realizar login de forma simples e rápida                                                                                                       | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR01</a>, <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD01</a>                                              | Não           | WH
 | RF02   | O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia                                                                           | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR02</a>                                                                                                                  | Não           | MH
 | RF03   | O usuário deve poder receber notificações personalizadas com base em sua localização                                                                                    | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR03</a>                                                                                                                  | Não           | CH
 | RF04   | O usuário deve poder consultar agendamentos e serviços em um único local centralizado                                                                                   | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR04</a>                                                                                                                  | Não           | MH
 | RF05   | O usuário deve ter acesso a um assistente virtual com acessibilidade por voz                                                                                            | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR05</a>, <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD05</a>, <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT13</a> | Não           | MH
 | RF06   | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app                                                                                              | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR06</a>                                                                                                                  | Não           |SH
 | RF07   | O usuário deve poder alterar o tamanho da fonte e o contraste de cores                                                                                                  | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR07</a>, <a href="../tec_elicitacao/entrevista/#anchor_EN">EN08</a>, <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD08</a> | Não           | SH
 | RF08   | O aplicativo deve permitir modo escuro                                                                                                                                  | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR08</a>                                                                                                                  | Não           | CH
 | RF09   | O usuário deve poder acessar e visualizar notícias relevantes                                                                                                           | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR10</a>                                                                                                                  | Sim           | SH
 | RF10   | O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos                                                                                         | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR11</a>                                                                                                                  | Não           | CH
 | RF11   | O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade                                                                                    | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR12</a>                                                                                                                  | Sim           | MH
 | RF12   | O usuário deve poder alterar o idioma do aplicativo                                                                                                                     | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR13</a>                                                                                                                  | Não           | SH
 | RF13   | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços                                                                             | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR14</a>                                                                                                                  | Não           | SH
 | RF14   | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes                                                                        | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR15</a>                                                                                                                  | Não           | MH
 | RF15   | O usuário deve poder acessar um menu com as principais funções logo na tela inicial                                                                                     | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR16</a>                                                                                                                  | Sim           | SH
 | RF16   | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada                                                                           | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR17</a>                                                                                                                  | Não           | MH
 | RF17   | O usuário deve poder utilizar chatbot para tirar dúvidas                                                                                                                | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR18</a>                                                                                                                  | Sim           | WH
 | RF18   | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte                                                                                 | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR19</a>                                                                                                                  | Não           | SH
 | RF19   | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)                                                               | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR20</a>                                                                                                                  | Não           | SH
 | RF20   | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa.                                              | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN01</a>                                                                                                                     | Sim           | MH
 | RF21   | O aplicativo fornece links para serviços externos (como Secretaria da Fazenda) de forma eficiente, com explicações claras sobre o que o usuário encontrará após clicar. | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN02</a>                                                                                                                     | Sim           | CH
 | RF22   | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL.                                        | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN03</a>, <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT07</a>                                                   | Parcial       | MH
 | RF23   | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial.                                                           | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN04</a>                                                                                                                     | Não           | SH
 | RF24   | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras.                                                         | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN05</a>                                                                                                                     | Sim           | SH
 | RF25   | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos.                                    | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN06</a>                                                                                                                     | Não           | MH
 | RF26   | O aplicativo deve permitir que usuários reportem problemas da cidade através de um mapa interativo.                                                                     | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN09</a>                                                                                                                     | Não           | MH
 | RF27   | O aplicativo deve fornecer acesso a números de serviços de emergência da polícia.                                                                                       | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN10</a>, <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT05</a>                                                   | Sim           | MH
 | RF28   | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso.                                                                                       | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN11</a>                                                                                                                     | Não           | CH
 | RF29   | O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos.                                                        | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD02</a>                                                                                                                 | Não           | MH
 | RF30   | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço                                                                          | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD03</a>                                                                                                                 | Não           | MH
 | RF31   | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.                                                                              | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD04</a>                                                                                                                 | Não           | MH
 | RF32   | O sistema deve permitir que o usuário confirme a resolução de problemas relatados.                                                                                       | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD06</a>                                                                                                                 | Não           | MH
 | RF33   | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo.                                                                                           | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD07</a>                                                                                                                 | Não           | MH
 | RF34   | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação.                                              | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT01</a>                                                                                                                  | Sim           | MH
 | RF35   | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes.                                                     | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT02</a>                                                                                                                  | Sim           | MH
 | RF36   | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo).                                                                               | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT03</a>                                                                                                                  | Sim           |MH
 | RF37   | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência.                                                                                      | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT04</a>                                                                                                                  | Sim           |MH
 | RF38   | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue.                                                                              | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT06</a>                                                                                                                  | Sim           |MH
 | RF39   | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade.                                                                            | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT08</a>                                                                                                                  | Sim           |MH
 | RF40   | Permitir agendamentos em serviços sociais, como centros de assistência social e habitação.                                                                                | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT09</a>                                                                                                                  | Sim           |MH
 | RF41   | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais.                                                                                            | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT10</a>                                                                                                                  | Sim           |MH
 | RF42   | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos.                                                                  | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT11</a>                                                                                                                  | Sim           |MH
 | RF43   | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal.                                                                         | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT12</a>                                                                                                                  | Sim           |SH
 | RF44   | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes.                                                                             | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT13</a>                                                                                                                  | Sim           |CH
 | RF45   | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas.                                                                                  | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT14</a>                                                                                                                  | Sim           |MH

<font size="3"><p style="text-align: center">Fonte: [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz).</p></font>

### Tabela 2: Requisitos Não funcionais

**Legenda**:

- **RNFx**: Requisito Não-Funcional nºx
- **INTx***: Requisito nºx elicitado pela Introspecção
- **BRx**: Requisito nºx elicitado pelo Brainstorming
- **ADx**: Requisito nºx elicitado pelo Analise de Documentos
- **ENx**: Requisito nºx elicitado pela Entevista
- **MH**: Prioridade: **Must Have**
- **SH**: Prioridade: **Should Have**
- **CH**: Prioridade: **Could Have**
- **WH**: Prioridade: **Won't Have**

 | ID   | Descrição                                                                                                                                                               | Rastreabilidade                                                  | Implementação | Prioridade (MoSCoW) |
 | ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ------------- | ------------------ |
 |      |                                                                                                                                                                         |                                                                  |               |                    |
 | RNF01  | O sistema deve ser compatível com vários dispositivos como Android e iOS.                                                                                              | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD09</a>                                                                                                                 | Não           |MH
 | RNF02  | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).                                                                                        | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD10</a>                                                                                                                 | Não           |MH
 | RNF03  | O sistema deve ter uma interface intuitiva.                                                                                                                             | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD11</a>                                                                                                                 | Não           |MH
 | RNF04  | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos                                                                                           | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN01</a>                                                                                                                  | Sim           |MH
 | RNF05  | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                                                                                 | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a>                                                                                                                  | Não           |MH
 | RNF06  | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                                                                                         | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a>                                                                                                                  | Sim           |CH
 | RNF07  | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos                                                                       | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN05</a>                                                                                                                  | Não           |MH
 | RNF08  | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta                                                                                  | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a>                                                                                                                  | Sim           |MH
 | RNF09  | O layout deve ser responsivo para diferentes tamanhos de tela                                                                                                          | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN07</a>, <a href="../tec_elicitacao/integracao/#anchor_INTT">INT22</a>                                                 | Sim           |MH
 | RNF10  | O sistema deve ter compatibilidade com leitores de tela                                                                                                                 | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a>                                                                                                                  | Sim           |MH
 | RNF11  | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade                                                                             | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN09</a>                                                                                                                  | Não           |MH
 | RNF12  | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos.                                              | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN01</a>                                                                                                                       | Não           |MH
 | RNF13  | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação.                 | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN02</a>                                                                                                                       | Sim           |MH
 | RNF14  | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis.                                              | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN03</a>                                                                                                                       | Não           |MH
 | RNF15  | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.                                             | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN04</a>                                                                                                                       | Sim           |MH
 | RNF16  | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida.                                                                  | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN05</a>                                                                                                                       | Não           |MH
 | RNF17  | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis.             | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN06</a>                                                                                                                       | Não           |MH
 | RNF18  | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais.                                                      | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN07</a>, <a href="../tec_elicitacao/integracao/#anchor_INTT">INT19</a>                                                                                                                       | Não           |MH
 | RNF19  | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários.                                                                     | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN08</a>                                                                                                                       | Não           |MH
 | RNF20  | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.                                                                               | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT15</a>                                                                                                                   | Sim           |MH
 | RNF21  | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.                                                               | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT16</a>                                                                                                                   | Sim           |MH
 | RNF22  | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade.                                                 | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT17</a>                                                                                                                   | Sim           |MH
 | RNF23  | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura.                                                                        | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT18</a>                                                                                                                   | Sim           |MH
 | RNF24  | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.                                                                         | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT20</a>                                                                                                                   | Não           |MH
 | RNF25  | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis.                                                                    | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT21</a>                                                                                                                   | Sim           | MH               |


<font size="3"><p style="text-align: center">Fonte: [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz).</p></font>


## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a> International Institute of Business Analysis (IIBA). *A Guide to the Business Analysis Body of Knowledge (BABOK Guide)*. 2009. Priorização de Requisitos – UnB-FCTE. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096091/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf](https://aprender3.unb.br/pluginfile.php/3096091/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em: maio 2025.

> <a id="FRM1" href="#anchor_2">2.</a>Técnica MoSCoW – Trecho do material de Priorização de Requisitos – UnB-FCTE. Disponível em: [https://drive.google.com/file/d/1P-nfa2q3aiHsXSLgVBxa65OvOc0iSW58/view](https://drive.google.com/file/d/1P-nfa2q3aiHsXSLgVBxa65OvOc0iSW58/view). Acesso em: 04 mai.2025.

> <a id="FRM1" href="#anchor_3">3.</a>Aula 07 – Requisitos – UnB-FCTE. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096092/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf](https://aprender3.unb.br/pluginfile.php/3096092/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em: 04 mai.2025.

## Bibliografias

> <a id="FRM1" href="#anchor_4">4.</a>Portal do GDF. Disponível em: [https://www.df.gov.br/](https://www.df.gov.br/). Acesso em: 04 mai.2025.

> <a id="FRM1" href="#anchor_5">5.</a>Aplicativo e-GDF. Disponível em: [https://play.google.com/store/apps/details?id=br.gov.df.eGDF&hl=pt_BR](https://play.google.com/store/apps/details?id=br.gov.df.eGDF&hl=pt_BR). Acesso em: 04 mai.2025.



## Histórico de Versões

| Versão | Data       | Descrição                                | Autor(es)             | Revisor(es) | Data de Revisão |
|--------|------------|------------------------------------------|----------------------|-------------|----------------|
| 1.0    | 24/04/2025 | Criação do documento com requisitos MoSCoW | [Ana Vitória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz) |[João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS) | 04/05/2025 |
| 1.1    | 24/04/2025 | Correção e adição de melhorias no artefato | [Ana Vitória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz) | [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS) | 04/05/2025 |
| 1.2    | 04/05/2025 | Adicionando requisitos priorizados na reunião realizada| [Ana Vitória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz) |[João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)| 04/05/2025 

