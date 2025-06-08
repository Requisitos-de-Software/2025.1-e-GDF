# Backward-from

## Introdução
Os elos de rastreabilidade são conexões essenciais que estabelecem vínculos entre diferentes artefatos e atividades ao longo do ciclo de vida de um projeto ou sistema. Esses elos permitem rastrear a origem e a evolução de funcionalidades, decisões de projeto e mudanças, garantindo um gerenciamento eficaz e uma qualidade consistente. Utilizando a rastreabilidade, é possível identificar a proveniência de cada funcionalidade do sistema, assegurar que todos os requisitos foram devidamente testados e validados, registrar decisões críticas para o projeto e gerenciar os riscos de maneira eficiente. Além disso, a rastreabilidade facilita o controle de mudanças ao indicar quais artefatos são impactados por alterações específicas, promovendo uma gestão integrada e transparente do desenvolvimento e manutenção de sistemas.<a id="RP1" href="#citacao-elo1"><sup>[1]</sup></a>

### Backward-from

A rastreabilidade backward-from é um processo crítico na engenharia de requisitos, que permite a ligação dos requisitos às suas fontes originais. Esse tipo de rastreabilidade é essencial para garantir que todos os requisitos identificados tenham uma origem bem definida, facilitando a validação e verificação durante o ciclo de vida do desenvolvimento do software. Além disso, a rastreabilidade backward-from ajuda a gerenciar mudanças ao rastrear de volta cada requisito até suas bases, assegurando que qualquer modificação no sistema possa ser rapidamente associada à sua origem, permitindo uma resposta eficaz a alterações e garantindo a conformidade com os requisitos iniciais do projeto.<a id="RP2" href="#citacao-elo2"><sup>[2]</sup></a>

## Participantes

**Tabela 1 -** Participantes da Rastreabilidade Backward-from

| Nome | Data |
|:--|:--|
| [Ana Victória ](https://github.com/navicg) | 07/06/2025 |
| [Artur Mendonça](https://github.com/ArtyMend07) | 07/06/2025 |
| [Gabriel Lopes](https://github.com/BrzGab) | 07/06/2025 |
| [João Marcos](https://github.com/JJOAOMARCOSS) | 07/06/2025 |
| [Karoline Luz](https://github.com/KarolineLuz) | 07/06/2025 |
| [Lucas Mendonça](https://github.com/lucasarruda9) | 07/06/2025 |
| [Luiza Silva](https://github.com/Luizaxx) | 07/06/2025 |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab), 2025.*

## Metodologia
Utilizamos um cartão baseado nos cartões presentes nos slides dos Professores Milene Serrano e Maurício Serrano na página 22 à 27<a id="RP3" href="#citacao-elo3"><sup>[3]</sup></a>, as categorias e tipos de elos derivam do Meta-modelo de Toranzo. Os cartões que fizemos utilizam o mesmo formato, porém fizemos baseados nos requisitos onde cada cartão possui todos os tipos de Elos daquele requisito citado.

### Cartões de Relacionamento dos Elos

**Tabela 2 -** Exemplo de cartão

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | RE01, UC01, CE01, ENT01 |
| **Descrição do Requisito** | Descrição do que se trata o requisito |
| **Elos Backward-from:** | Agregação: RE01 - ENT01: O requisito originou-se da entrevista. |
| **Implementação:** | Sim/Não |

*Autores: [Artur Mendonça](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab).*

**Legenda: <a id="RP4" href="#citacao-elo4"><sup>[4]</sup></a>**

- **Categoria**: Devem ser classificadas em quatro níveis
    - **Ambiental**: Congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido.
    - **Organizacional**: Reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema.
    - **Gerencial**: Agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto.
    - **Desenvolvimento**: Abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...).
- **Elementos**: Lista de identificadores que representam [requisitos](../elicitacao/req_elicitados.md) (RE01), [casos de uso](../modelagem/casos_de_uso.md) (US01), [cenários](../modelagem/cenario.md) (CEN01) e [técnicas de elicitação de requisitos](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) (ENT01).
- **Elos Backward-from**: Primeiro, mostra-se o tipo de elo e depois a origem do requisito. Por exemplo, o requisito REQ01 originou-se da entrevista ENT01.
- **Tipos de Elos <a id="RP5" href="#citacao-elo5"><sup>[5]</sup></a>**:
    - **Satisfação**: Indica que a classe de origem tem dependência de satisfação com a classe de destino.
    - **Recurso**: Indica que a classe de origem tem dependência de recurso com a classe de destino.
    - **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre artefatos.
    - **Representação**: Captura a representação ou modelagem dos requisitos em outras linguagens.
    - **Alocado**: Classe de origem está relacionada à classe de destino, que representa um subsistema.
    - **Agregação**: Indica composição de elementos.

## Cartões de Requisitos Funcionais

### RF01

**Tabela 3 -** Cartão do Requisito RF01

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF01](../elicitacao/req_elicitados.md#anchor_RF), [BR01](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O usuário deve conseguir realizar login de forma simples e rápida |
| **Elos Backward-from:** | **Agregação**: RF01 - [BR01](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se do brainstorming e da análise de documentos |
| **Implementação:** | Não |

*Autor: [Ana Victória](https://github.com/navicg), 2025.*

### RF02

**Tabela 4 -** Cartão do Requisito RF02

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF02](../elicitacao/req_elicitados.md#anchor_RF), [BR02](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia |
| **Elos Backward-from:** | **Agregação**: RF02 - [BR02](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Ana Victória](https://github.com/navicg), 2025.*

### RF03

**Tabela 5 -** Cartão do Requisito RF03

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF03](../elicitacao/req_elicitados.md#anchor_RF), [BR03](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder receber notificações personalizadas com base em sua localização |
| **Elos Backward-from:** | **Agregação**: RF03 - [BR03](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Ana Victória](https://github.com/navicg), 2025.*

### RF04

**Tabela 6 -** Cartão do Requisito RF04

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF04](../elicitacao/req_elicitados.md#anchor_RF), [BR04](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder consultar agendamentos e serviços em um único local centralizado |
| **Elos Backward-from:** | **Agregação**: RF04 - [BR04](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07), 2025.*

### RF05

**Tabela 7 -** Cartão do Requisito RF05

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF05](../elicitacao/req_elicitados.md#anchor_RF), [BR05](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O usuário deve ter acesso a um assistente virtual com acessibilidade por voz |
| **Elos Backward-from:** | **Agregação**: RF05 - [BR05](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se do brainstorming, análise de documentos e introspecção |
| **Implementação:** | Não |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07), 2025.*

### RF06

**Tabela 8 -** Cartão do Requisito RF06

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF06](../elicitacao/req_elicitados.md#anchor_RF), [BR06](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app |
| **Elos Backward-from:** | **Agregação**: RF06 - [BR06](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07), 2025.*

### RF07

**Tabela 9 -** Cartão do Requisito RF07

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF07](../elicitacao/req_elicitados.md#anchor_RF), [BR07](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O usuário deve poder alterar o tamanho da fonte e o contraste de cores |
| **Elos Backward-from:** | **Agregação**: RF07 - [BR07](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se do brainstorming, entrevista e análise de documentos |
| **Implementação:** | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RF08

**Tabela 10 -** Cartão do Requisito RF08

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF08](../elicitacao/req_elicitados.md#anchor_RF), [BR08](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O aplicativo deve permitir modo escuro |
| **Elos Backward-from:** | **Agregação**: RF08- [BR08](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RF09

**Tabela 11 -** Cartão do Requisito RF09

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF09](../elicitacao/req_elicitados.md#anchor_RF), [BR10](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder acessar e visualizar notícias relevantes |
| **Elos Backward-from:** | **Agregação**: RF09 - [BR10](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Sim |

*Autor: [Ana Victória](https://github.com/navicg), 2025.*

### RF10

**Tabela 12 -** Cartão do Requisito RF10

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF10](../elicitacao/req_elicitados.md#anchor_RF), [BR11](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos |
| **Elos Backward-from:** | **Agregação**: RF10 - [BR11](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RF11

**Tabela 13 -** Cartão do Requisito RF11

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF11](../elicitacao/req_elicitados.md#anchor_RF), [BR12](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade |
| **Elos Backward-from:** | **Agregação**: RF11- [BR12](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Sim |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07), 2025.*

### RF12

**Tabela 14 -** Cartão do Requisito RF12

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF12](../elicitacao/req_elicitados.md#anchor_RF), [BR13](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder alterar o idioma do aplicativo |
| **Elos Backward-from:** | **Agregação**: RF12 - [BR13](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [João Marcos](https://github.com/JJOAOMARCOSS), 2025.*

### RF13

**Tabela 15 -** Cartão do Requisito RF13

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF13](../elicitacao/req_elicitados.md#anchor_RF), [BR14](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços |
| **Elos Backward-from:** | **Agregação**: RF13 - [BR14](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [João Marcos](https://github.com/JJOAOMARCOSS), 2025.*

### RF14

**Tabela 16 -** Cartão do Requisito RF14

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF14](../elicitacao/req_elicitados.md#anchor_RF), [BR15](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes |
| **Elos Backward-from:** | **Agregação**: RF14 - [BR15](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [João Marcos](https://github.com/JJOAOMARCOSS), 2025.*

### RF15

**Tabela 17 -** Cartão do Requisito RF15

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF15](../elicitacao/req_elicitados.md#anchor_RF), [BR16](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder acessar um menu com as principais funções logo na tela inicial |
| **Elos Backward-from:** | **Agregação**: RF15 - [BR16](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Sim |

*Autor: [Ana Victória](https://github.com/navicg), 2025.*

### RF16

**Tabela 18 -** Cartão do Requisito RF16

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF16](../elicitacao/req_elicitados.md#anchor_RF), [BR17](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada |
| **Elos Backward-from:** | **Agregação**: RF16 - [BR17](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Karoline Luz](https://github.com/KarolineLuz), 2025.*

### RF17

**Tabela 19 -** Cartão do Requisito RF17

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF17](../elicitacao/req_elicitados.md#anchor_RF), [BR19](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte |
| **Elos Backward-from:** | **Agregação**: RF17 - [BR19](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Lucas Mendonça](https://github.com/lucasarruda9), 2025.*

### RF18

**Tabela 20 -** Cartão do Requisito RF18

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF18](../elicitacao/req_elicitados.md#anchor_RF), [BR20](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes) |
| **Elos Backward-from:** | **Agregação**: RF18 - [BR20](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Implementação:** | Não |

*Autor: [Luiza Silva](https://github.com/Luizaxx), 2025.*

### RF19

**Tabela 21 -** Cartão do Requisito RF19

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF19](../elicitacao/req_elicitados.md#anchor_RF), [EN01](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa |
| **Elos Backward-from:** | **Agregação**: RF19 - [EN01](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RF20

**Tabela 22 -** Cartão do Requisito RF20

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF20](../elicitacao/req_elicitados.md#anchor_RF), [EN02](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo fornece links para serviços externos com explicações claras |
| **Elos Backward-from:** | **Agregação**: RF20 - [EN02](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Sim |

*Autor: [Ana Victória](https://github.com/navicg), 2025.*

### RF21

**Tabela 23 -** Cartão do Requisito RF21

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF21](../elicitacao/req_elicitados.md#anchor_RF), [EN03](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT07](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL |
| **Elos Backward-from:** | **Agregação**: RF21 - [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT07](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da entrevista e introspecção |
| **Implementação:** | Parcial |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07), 2025.*

### RF22

**Tabela 24 -** Cartão do Requisito RF22

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF22](../elicitacao/req_elicitados.md#anchor_RF), [EN04](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial |
| **Elos Backward-from:** | **Agregação**: RF22 - [EN04](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Não |

*Autor: [Luiza Silva](https://github.com/Luizaxx), 2025.*

### RF23

**Tabela 25 -** Cartão do Requisito RF23

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF23](../elicitacao/req_elicitados.md#anchor_RF), [EN05](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras |
| **Elos Backward-from:** | **Agregação**: RF23 - [EN05](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RF24

**Tabela 26 -** Cartão do Requisito RF24

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF24](../elicitacao/req_elicitados.md#anchor_RF), [EN06](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos |
| **Elos Backward-from:** | **Agregação**: RF24 - [EN06](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Não |

*Autor: [Lucas Mendonça](https://github.com/lucasarruda9), 2025.*

### RF25

**Tabela 27 -** Cartão do Requisito RF25

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF25](../elicitacao/req_elicitados.md#anchor_RF), [EN09](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve permitir que usuários reportem problemas da cidade através de um mapa interativo |
| **Elos Backward-from:** | **Agregação**: RF25 - [EN09](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Não |

*Autor: [Karoline Luz](https://github.com/KarolineLuz), 2025.*

### RF26

**Tabela 28 -** Cartão do Requisito RF26

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF26](../elicitacao/req_elicitados.md#anchor_RF), [EN10](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT05](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O aplicativo deve fornecer acesso a números de serviços de emergência da polícia |
| **Elos Backward-from:** | **Agregação**: RF26 - [EN10](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT05](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da entrevista e introspecção |
| **Implementação:** | Sim |

*Autor: [Karoline Luz](https://github.com/KarolineLuz), 2025.*

### RF27

**Tabela 29 -** Cartão do Requisito RF27

| Campo | Valor |
|:--|:--|
| **Categoria:** | Desenvolvimento |
| **Elementos:** | [RF27](../elicitacao/req_elicitados.md#anchor_RF), [EN11](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso |
| **Elos Backward-from:** | **Agregação**: RF27 - [EN11](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:** | Não |

*Autor: [Luiza Silva](https://github.com/Luizaxx), 2025.*

### RF28

<div align="center">
  <strong>Tabela 30 -</strong> Cartão do Requisito RF28
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF28](../elicitacao/req_elicitados.md#anchor_RF), [AD02](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos |
| **Elos Backward-from:** | **Agregação**: RF28 - [AD02](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF29

<div align="center">
  <strong>Tabela 31 -</strong> Cartão do Requisito RF29
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF29](../elicitacao/req_elicitados.md#anchor_RF), [AD03](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço |
| **Elos Backward-from:** | **Agregação**: RF29 - [AD03](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF30

<div align="center">
  <strong>Tabela 32 -</strong> Cartão do Requisito RF30
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF30](../elicitacao/req_elicitados.md#anchor_RF), [AD04](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações |
| **Elos Backward-from:** | **Agregação**: RF30 - [AD04](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF31

<div align="center">
  <strong>Tabela 33 -</strong> Cartão do Requisito RF31
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF31](../elicitacao/req_elicitados.md#anchor_RF), [AD06](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve permitir que o usuário confirme a resolução de problemas relatados |
| **Elos Backward-from:** | **Agregação**: RF31 - [AD06](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF32

<div align="center">
  <strong>Tabela 34 -</strong> Cartão do Requisito RF32
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF32](../elicitacao/req_elicitados.md#anchor_RF), [AD07](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo |
| **Elos Backward-from:** | **Agregação**: RF32 - [AD07](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF33

<div align="center">
  <strong>Tabela 35 -</strong> Cartão do Requisito RF33
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF33](../elicitacao/req_elicitados.md#anchor_RF), [INT01](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação |
| **Elos Backward-from:** | **Agregação**: RF33 - [INT01](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF34

<div align="center">
  <strong>Tabela 36 -</strong> Cartão do Requisito RF34
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF34](../elicitacao/req_elicitados.md#anchor_RF), [INT02](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes |
| **Elos Backward-from:** | **Agregação**: RF34 - [INT02](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF35

<div align="center">
  <strong>Tabela 37 -</strong> Cartão do Requisito RF35
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF35](../elicitacao/req_elicitados.md#anchor_RF), [INT03](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo) |
| **Elos Backward-from:** | **Agregação**: RF35 - [INT03](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF36

<div align="center">
  <strong>Tabela 38 -</strong> Cartão do Requisito RF36
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF36](../elicitacao/req_elicitados.md#anchor_RF), [INT04](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência |
| **Elos Backward-from:** | **Agregação**: RF36 - [INT04](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF37

<div align="center">
  <strong>Tabela 39 -</strong> Cartão do Requisito RF37
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF37](../elicitacao/req_elicitados.md#anchor_RF), [INT06](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue |
| **Elos Backward-from:** | **Agregação**: RF37 - [INT06](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF38

<div align="center">
  <strong>Tabela 40 -</strong> Cartão do Requisito RF38
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF38](../elicitacao/req_elicitados.md#anchor_RF), [INT08](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade |
| **Elos Backward-from:** | **Agregação**: RF38 - [INT08](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF39

<div align="center">
  <strong>Tabela 41 -</strong> Cartão do Requisito RF39
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF39](../elicitacao/req_elicitados.md#anchor_RF), [INT09](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Permitir agendamentos em serviços sociais, como centros de assistência social e habitação |
| **Elos Backward-from:** | **Agregação**: RF39 - [INT09](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF40

<div align="center">
  <strong>Tabela 42 -</strong> Cartão do Requisito RF40
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF40](../elicitacao/req_elicitados.md#anchor_RF), [INT10](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais |
| **Elos Backward-from:** | **Agregação**: RF40 - [INT10](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF41

<div align="center">
  <strong>Tabela 43 -</strong> Cartão do Requisito RF41
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF41](../elicitacao/req_elicitados.md#anchor_RF), [INT11](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos |
| **Elos Backward-from:** | **Agregação**: RF41 - [INT11](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF42

<div align="center">
  <strong>Tabela 44 -</strong> Cartão do Requisito RF42
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF42](../elicitacao/req_elicitados.md#anchor_RF), [INT12](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal |
| **Elos Backward-from:** | **Agregação**: RF42 - [INT12](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF43

<div align="center">
  <strong>Tabela 45 -</strong> Cartão do Requisito RF43
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF43](../elicitacao/req_elicitados.md#anchor_RF), [INT13](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [BR18](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Descrição do Requisito** | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes dos usuários |
| **Elos Backward-from:** | **Agregação**: RF43 - [INT13](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [BR18](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se da introspecção e brainstorming |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF44

<div align="center">
  <strong>Tabela 46 -</strong> Cartão do Requisito RF44
</div>

| **Categoria:** | Desenvolvimento |
|:---------------|:----------------|
| **Elementos:** | [RF44](../elicitacao/req_elicitados.md#anchor_RF), [INT14](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas |
| **Elos Backward-from:** | **Agregação**: RF44 - [INT14](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:** | Sim |

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

## Cartões de Requisitos Não Funcionais

### RNF01

**Tabela 47 -** Cartão do Requisito RNF01

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF01](../elicitacao/req_elicitados.md#anchor_RNF), [AD09](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve ser compatível com vários dispositivos como Android e iOS |
| **Elos Backward-from:**  | **Agregação**: RNF01 - [AD09](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:**       | Sim |

*Autor: [João Marcos](https://github.com/JJOAOMARCOSS), 2025.*

### RNF02

**Tabela 48 -** Cartão do Requisito RNF02

| **Categoria:**           | Organizacional                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF02](../elicitacao/req_elicitados.md#anchor_RNF), [AD10](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD) |
| **Elos Backward-from:**  | **Agregação**: RNF02 - [AD10](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Implementação:**       | Sim |

*Autor: [Luiza Silva](https://github.com/Luizaxx), 2025.*

### RNF03

**Tabela 49 -** Cartão do Requisito RNF03

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF03](../elicitacao/req_elicitados.md#anchor_RNF), [BRN01](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos |
| **Elos Backward-from:**  | **Agregação**: RNF03 - [BRN01](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF04

**Tabela 50 -** Cartão do Requisito RNF04

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF04](../elicitacao/req_elicitados.md#anchor_RNF), [BRN02](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual |
| **Elos Backward-from:**  | **Agregação**: RNF04 - [BRN02](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF05

**Tabela 51 -** Cartão do Requisito RNF05

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF05](../elicitacao/req_elicitados.md#anchor_RNF), [BRN04](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware |
| **Elos Backward-from:**  | **Agregação**: RNF05 - [BRN04](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF06

**Tabela 52 -** Cartão do Requisito RNF06

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF06](../elicitacao/req_elicitados.md#anchor_RNF), [BRN05](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos |
| **Elos Backward-from:**  | **Agregação**: RNF06 - [BRN05](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF07

**Tabela 53 -** Cartão do Requisito RNF07

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF07](../elicitacao/req_elicitados.md#anchor_RNF), [BRN06](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta |
| **Elos Backward-from:**  | **Agregação**: RNF07 - [BRN06](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF08

**Tabela 54 -** Cartão do Requisito RNF08

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF08](../elicitacao/req_elicitados.md#anchor_RNF), [BRN07](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN), [INT22](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O layout deve ser responsivo para diferentes tamanhos de tela |
| **Elos Backward-from:**  | **Agregação**: RNF08 - [BRN07](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN), [INT22](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se do brainstorming e introspecção |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF09

**Tabela 55 -** Cartão do Requisito RNF09

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF09](../elicitacao/req_elicitados.md#anchor_RNF), [BRN08](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | O sistema deve ter compatibilidade com leitores de tela |
| **Elos Backward-from:**  | **Agregação**: RNF09 - [BRN08](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF10

**Tabela 56 -** Cartão do Requisito RNF10

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF10](../elicitacao/req_elicitados.md#anchor_RNF), [BRN09](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN) |
| **Descrição do Requisito** | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade |
| **Elos Backward-from:**  | **Agregação**: RNF10 - [BRN09](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF11

**Tabela 57 -** Cartão do Requisito RNF11

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF11](../elicitacao/req_elicitados.md#anchor_RNF), [EN01](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD11](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Descrição do Requisito** | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos |
| **Elos Backward-from:**  | **Agregação**: RNF11 - [EN01](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD11](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da entrevista e análise de documentos |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF12

**Tabela 58 -** Cartão do Requisito RNF12

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF12](../elicitacao/req_elicitados.md#anchor_RNF), [EN02](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação |
| **Elos Backward-from:**  | **Agregação**: RNF12 - [EN02](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF13

**Tabela 59 -** Cartão do Requisito RNF13

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF13](../elicitacao/req_elicitados.md#anchor_RNF), [EN03](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis |
| **Elos Backward-from:**  | **Agregação**: RNF13 - [EN03](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:**       | Não |

*Autor: [Ana Victória](https://github.com/anavicg), 2025.*

### RNF14

**Tabela 60 -** Cartão do Requisito RNF14

| **Categoria:**           | Organizacional                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF14](../elicitacao/req_elicitados.md#anchor_RNF), [EN04](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança |
| **Elos Backward-from:**  | **Agregação**: RNF14 - [EN04](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF15

**Tabela 61 -** Cartão do Requisito RNF15

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF15](../elicitacao/req_elicitados.md#anchor_RNF), [EN05](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida |
| **Elos Backward-from:**  | **Agregação**: RNF15 - [EN05](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF16

**Tabela 62 -** Cartão do Requisito RNF16

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF16](../elicitacao/req_elicitados.md#anchor_RNF), [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis |
| **Elos Backward-from:**  | **Agregação**: RNF16 - [EN06](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:**       | Não |

*Autor: [Karoline Luz](https://github.com/KarolineLuz), 2025.*

### RNF17

**Tabela 63 -** Cartão do Requisito RNF17

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF17](../elicitacao/req_elicitados.md#anchor_RNF), [EN07](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT19](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais |
| **Elos Backward-from:**  | **Agregação**: RNF17 - [EN07](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT19](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da entrevista e introspecção |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF18

**Tabela 64 -** Cartão do Requisito RNF18

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF18](../elicitacao/req_elicitados.md#anchor_RNF), [EN08](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| **Descrição do Requisito** | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários |
| **Elos Backward-from:**  | **Agregação**: RNF18 - [EN08](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Implementação:**       | Não |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF19

**Tabela 65 -** Cartão do Requisito RNF19

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF19](../elicitacao/req_elicitados.md#anchor_RNF), [INT15](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS |
| **Elos Backward-from:**  | **Agregação**: RNF19 - [INT15](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF20

**Tabela 66 -** Cartão do Requisito RNF20

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF20](../elicitacao/req_elicitados.md#anchor_RNF), [INT16](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência |
| **Elos Backward-from:**  | **Agregação**: RNF20 - [INT16](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:**       | Sim |

*Autor: [Artur Mendonça](https://github.com/ArtyMend07), 2025.*

### RNF21

**Tabela 67 -** Cartão do Requisito RNF21

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF21](../elicitacao/req_elicitados.md#anchor_RNF), [INT17](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade |
| **Elos Backward-from:**  | **Agregação**: RNF21 - [INT17](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF22

**Tabela 68 -** Cartão do Requisito RNF22

| **Categoria:**           | Organizacional                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF22](../elicitacao/req_elicitados.md#anchor_RNF), [INT18](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura |
| **Elos Backward-from:**  | **Agregação**: RNF22 - [INT18](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

### RNF23

**Tabela 69 -** Cartão do Requisito RNF23

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF23](../elicitacao/req_elicitados.md#anchor_RNF), [INT20](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas |
| **Elos Backward-from:**  | **Agregação**: RNF23 - [INT20](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:**       | Não |

*Autor: [Lucas Mendonça](https://github.com/lucasarruda9), 2025.*

### RNF24

**Tabela 70 -** Cartão do Requisito RNF24

| **Categoria:**           | Desenvolvimento                                   |
|:-------------------------|:--------------------------------------------------|
| **Elementos:**           | [RNF24](../elicitacao/req_elicitados.md#anchor_RNF), [INT21](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Descrição do Requisito** | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis |
| **Elos Backward-from:**  | **Agregação**: RNF24 - [INT21](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Implementação:**       | Sim |

*Autor: [Gabriel Lopes](https://github.com/BrzGab), 2025.*

## Referências Bibliográficas

> <a id="citacao-elo1" href="#RP1">[1]</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 07 jun. 2025.

> <a id="citacao-elo2" href="#RP2">[2]</a> SERRANO, Milene, SERRANO, Maurício. Requisitos - Aula sobre Rastreabilidade. UnB Gama, Brasília, 2023.
<div align="center"><img src="../assets/fonte-elo2.png" alt="Fonte Elo 2 - Backward-from"></div>

> <a id="citacao-elo3" href="#RP3">[3]</a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: [link](https://aprender3.unb.br/pluginfile.php/3096178/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 07 jun. 2025.


> <a id="citacao-elo4" href="#RP4">[4]</a> SERRANO, Milene, SERRANO, Maurício. Requisitos - Tipos de Elos. UnB Gama, Brasília, 2023.
<div align="center"><img src="../assets/fonte-elo4.png" alt="Fonte Elo 4 - Tipos de Elos"></div>

> <a id="citacao-elo5" href="#RP5">[5]</a> SERRANO, Milene, SERRANO, Maurício. Requisitos - Tipos de Elos. UnB Gama, Brasília, 2023.
<div align="center"><img src="../assets/fonte-elo5.png" alt="Fonte Elo 5 - Tipos de Elos"></div>

## Bibliografia

> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 07 jun. 2025.

> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. Disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf). Acesso em: 07 jun. 2025.

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 07/06/2025 | Criação da página e adicionando os cartões dos requisitos |  [Artur Mendonça](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab) | 07/06/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) |
| `1.1` | 08/06/2025 | Adição de novas referências bibliográficas e correção de hyperlinks | [Artur Mendonça](https://github.com/ArtyMend07) [Gabriel Lopes](https://github.com/BrzGab) | 08/06/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) |