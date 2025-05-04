# MoSCoW

## Introdução

A técnica MoSCoW é uma abordagem de priorização usada para identificar a importância relativa de diferentes requisitos em um projeto. Seu nome é um acrônimo para quatro categorias de prioridade: **Must Have**, **Should Have**, **Could Have** e **Won’t Have**.

No contexto do projeto do aplicativo **e-GDF**, essa técnica foi utilizada para definir quais funcionalidades e requisitos são essenciais, desejáveis, opcionais ou fora do escopo neste momento.

Contudo, apesar de sua popularidade, a técnica MoSCoW possui limitações importantes. De acordo com o *International Institute of Business Analysis* (IIBA, 2009):

### **[Must Have](#must-have) - Essencial **
O requisito **deve ser atendido** para que a solução seja considerada um sucesso.

### **[Should Have](#should-have) - Importante, mas não Essencial ** 
O requisito é **importante** e **deveria ser incluído** na solução, se possível, mas **não é essencial** para o sucesso imediato.

### **[Could Have](#could-have) Bom ter, mas não Essencial ** 
É um recurso **desejável**, mas que pode ser **adiado ou até eliminado**, sendo implementado apenas se houver tempo e recursos suficientes.

### **[Won’t Have](#wont-have) Não será implementado no momento **  
Indica um requisito **não implementado no momento**, mas **possível no futuro**. Essa categoria pode gerar **ambiguidade**, pois pode ser interpretada como "não agora" ou "nunca". A técnica MoSCoW, apesar de clara, **não define critérios objetivos** para classificar os requisitos, o que pode levar a disputas por classificações mais prioritárias, como “Must”. Quando mal aplicada, pode **comprometer a efetividade da priorização**.

## Metodologia

A técnica MoSCoW foi aplicada por meio de reuniões com os participantes do projeto, que discutiram e classificaram os requisitos com base em critérios como impacto no usuário, viabilidade técnica, alinhamento com os objetivos do governo e disponibilidade de recursos. Apesar de sua simplicidade, foi necessário cuidado para que as classificações fossem coerentes e refletissem verdadeiramente o valor e a urgência dos requisitos.


A tabela 1 apresenta os requisitos funcionais e não funcionais, sendo que cada linha contém um ID, sua respectiva descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisito em questão e se ele foi implementado ou não.

A legenda para cada sigla é a seguinte:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- INTx: Requisito nºx elicitado pela Introspecção
- BRx: Requisito nºx elicitado pelo Brainstorming
- ADx: Requisito nºx elicitado pelo Analise de Documentos
- ENx: Requisito nºx elicitado pela Entevista


## Participantes

- [Ana Vitória](https://github.com/navicg) – Participante da priorização
- [Gabriel Lopes](https://github.com/BrzGab) – Participante da priorização
- [Karoline Luz](https://github.com/KarolineLuz) – Participante da priorização

## Requisitos Priorizados

**Legenda:**

- **RF**: Requisito Funcional  
- **RNF**: Requisito Não Funcional

## Requisitos Priorizados

**Legenda:**
- RF: Requisito Funcional
- RNF: Requisito Não Funcional

| ID      | Descrição                                                                                                                                                    | Rastreabilidade               | Implementação | Prioridade (MoSCoW) |
|---------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|---------------|--------------------|
| RF01     | O usuário deve conseguir realizar login de forma simples e rápida                                                                                             | BR01, AD01                    | Não           | WH                 |
| RF02     | O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia                                                                  | BR02                          | Não           | MH                 |
| RF03     | O usuário deve poder receber notificações personalizadas com base em sua localização                                                                          | BR03                          | Não           | CH                 |
| RF04     | O usuário deve poder consultar agendamentos e serviços em um único local centralizado                                                                        | BR04                          | Não           | MH                 |
| RF05     | O usuário deve ter acesso a um assistente virtual com acessibilidade por voz                                                                                 | BR05, AD05, INT13             | Não           | MH                 |
| RF06     | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app                                                                                   | BR06                          | Não           | SH                 |
| RF07     | O usuário deve poder alterar o tamanho da fonte e o contraste de cores                                                                                        | BR07, EN08, AD08              | Não           | SH                 |
| RF08     | O aplicativo deve permitir modo escuro                                                                                                                       | BR08                          | Não           | CH                 |
| RF09     | O usuário deve poder acessar e visualizar notícias relevantes                                                                                                 | BR10                          | Sim           | SH                 |
| RF10     | O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos                                                                              | BR11                          | Não           | CH                 |
| RF11     | O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade                                                                         | BR12                          | Sim           | MH                 |
| RF12     | O usuário deve poder alterar o idioma do aplicativo                                                                                                          | BR13                          | Não           | SH                 |
| RF13     | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços                                                                  | BR14                          | Não           | SH                 |
| RF14     | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes                                                             | BR15                          | Não           | MH                 |
| RF15     | O usuário deve poder acessar um menu com as principais funções logo na tela inicial                                                                           | BR16                          | Sim           | SH                 |
| RF16     | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada                                                                | BR17                          | Não           | MH                 |
| RF17     | O usuário deve poder utilizar chatbot para tirar dúvidas                                                                                                     | BR18                          | Sim           | WH                 |
| RF18     | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte                                                                      | BR19                          | Não           | SH                 |
| RF19     | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)                                                     | BR20                          | Não           | SH                 |
| RF20     | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa                                     | EN01                          | Sim           | MH                 |
| RF21     | O aplicativo fornece links para serviços externos (como Secretaria da Fazenda) de forma eficiente, com explicações claras sobre o que o usuário encontrará    | EN02                          | Sim           | CH                 |
| RF22     | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL                              | EN03, INT07                   | Parcial       | MH                 |
| RF23     | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial                                                  | EN04                          | Não           | SH                 |
| RF24     | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras                                              | EN05                          | Sim           | SH                 |
| RF25     | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos                          | EN06                          | Não           | MH                 |
| RF26     | O aplicativo deve permitir que usuários reportem problemas da cidade através de um mapa interativo                                                           | EN09                          | Não           | MH                 |
| RF27     | O aplicativo deve fornecer acesso a números de serviços de emergência da polícia                                                                             | EN10, INT05                   | Sim           | MH                 |
| RF28     | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso                                                                             | EN11                          | Não           | CH                 |
| RF29     | O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos                                             | AD02                          | Não           | MH                 |
| RF30     | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço                                                              | AD03                          | Não           | MH                 |
| RF31     | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações                                                                   | AD04                          | Não           | MH                 |
| RF32     | O sistema deve permitir que o usuário confirme a resolução de problemas relatados                                                                            | AD06                          | Não           | MH                 |
| RF33     | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo                                                                               | AD07                          | Não           | MH                 |
| RF34     | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação                                    | INT01                         | Sim           | MH                 |
| RF35     | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes                                            | INT02                         | Sim           | MH                 |
| RF36     | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo)                                                                   | INT03                         | Sim           | MH                 |
| RF37     | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência                                                                           | INT04                         | Sim           | MH                 |
| RF38     | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue                                                                  | INT06                         | Sim           | MH                 |
| RF39     | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade                                                                | INT08                         | Sim           | MH                 |
| RF40     | Permitir agendamentos em serviços sociais, como centros de assistência social e habitação                                                                    | INT09                         | Sim           | MH                 |
| RF41     | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais                                                                                  | INT10                         | Sim           | MH                 |
| RF42     | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos                                                       | INT11                         | Sim           | MH                 |
| RF43     | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal                                                              | INT12                         | Sim           | SH                 |
| RF44     | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes                                                                  | INT13                         | Sim           | CH                 |
| RF45     | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas                                                                       | INT14                         | Sim           | MH                 |
| RNF01    | O sistema deve ser compatível com vários dispositivos como Android e iOS                                                                                     | AD09                          | Não           | MH                 |
| RNF02    | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD)                                                                            | AD10                          | Não           | MH                 |
| RNF03    | O sistema deve ter uma interface intuitiva                                                                                                                  | AD11                          | Não           | MH                 |
| RNF04    | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos                                                                               | BRN01                         | Sim           | MH                 |
| RNF05    | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                                                                      | BRN02                         | Não           | MH                 |
| RNF06    | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                                                                              | BRN04                         | Sim           | MH                 |
| RNF07    | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos                                                           | BRN05                         | Não           | MH                 |
| RNF08    | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta                                                                       | BRN06                         | Sim           | SH                 |
| RNF09    | O layout deve ser responsivo para diferentes tamanhos de tela                                                                                               | BRN07, INT22                  | Sim           | MH                 |
| RNF10    | O sistema deve ter compatibilidade com leitores de tela                                                                                                     | BRN08                         | Sim           | MH                 |
| RNF11    | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade                                                                  | BRN09                         | Não           | MH                 |
| RNF12    | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos                                   | EN01                          | Não           | MH                 |
| RNF13    | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação       | EN02                          | Sim           | MH                 |
| RNF14    | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis                                     | EN03                          | Não           | MH                 |
| RNF15    | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança                                    | EN04                          | Sim           | MH                 |
| RNF16    | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida                                                        | EN05                          | Não           | CH                 |
| RNF17    | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis   | EN06                          | Não           | MH                 |
| RNF18    | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais                                            | EN07, INT19                   | Não           | MH                 |
| RNF19    | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários                                                          | EN08                          | Não           | MH                 |
| RNF20    | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS                                                                     | INT15                         | Sim           | MH                 |
| RNF21    | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência                                                     | INT16                         | Sim           | MH                 |
| RNF22    | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade                                       | INT17                         | Sim           | MH                 |
| RNF23    | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura                                                              | INT18                         | Sim           | MH                 |
| RNF24    | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas                                                               | INT20                         | Não           | MH                 |
| RNF25    | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis                                                         | INT21                         | Sim           | MH                 |


<font size="3"><p style="text-align: center">Fonte: [Ana Vitória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz).</p></font>


## Referências Bibliográficas

- International Institute of Business Analysis (IIBA). *A Guide to the Business Analysis Body of Knowledge (BABOK Guide)*. 2009.
- Priorização de Requisitos – UnB-FCTE. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096091/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf](https://aprender3.unb.br/pluginfile.php/3096091/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em: maio 2025.
- Técnica MoSCoW – Trecho do material de Priorização de Requisitos – UnB-FCTE. Disponível em: [https://drive.google.com/file/d/1P-nfa2q3aiHsXSLgVBxa65OvOc0iSW58/view](https://drive.google.com/file/d/1P-nfa2q3aiHsXSLgVBxa65OvOc0iSW58/view). Acesso em: maio 2025.
- Aula 07 – Requisitos – UnB-FCTE. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096092/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf](https://aprender3.unb.br/pluginfile.php/3096092/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em: maio 2025.
- Portal do GDF. Disponível em: [https://www.df.gov.br/](https://www.df.gov.br/). Acesso em: maio 2025.
- Aplicativo e-GDF. Disponível em: [https://play.google.com/store/apps/details?id=br.gov.df.eGDF&hl=pt_BR](https://play.google.com/store/apps/details?id=br.gov.df.eGDF&hl=pt_BR). Acesso em: maio 2025.
- GOV.BR - Portal Oficial. Disponível em: [https://www.gov.br/pt-br](https://www.gov.br/pt-br). Acesso em: 03/05/2025.

## Histórico de Versões

| Versão | Data       | Descrição                                | Autor(es)             | Revisor(es) | Data de Revisão |
|--------|------------|------------------------------------------|----------------------|-------------|----------------|
| 1.0    | 24/04/2025 | Criação do documento com requisitos MoSCoW | [Ana Vitória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz) | — |
| 1.1    | 24/04/2025 | Correção e adição de melhorias no artefato | [Ana Vitória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz) | — |
