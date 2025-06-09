# Forward-From

## Introdução

O conceito de *forward-from* está relacionado à rastreabilidade para frente (*forward traceability*), que permite a ligação dos requisitos a artefatos desenvolvidos nas fases posteriores do ciclo de vida do software. De acordo com Sayão e Leite (2005), “no primeiro tipo temos a rastreabilidade *forward-to* (para frente), que liga documentos obtidos no processo de elicitação a requisitos relevantes” <a id="anchor_1" href="#FRM1"> [1]</a> </q>, e mais adiante, os autores descrevem que “no segundo tipo temos rastreabilidade *forward-from*, que liga requisitos a artefatos de desenho e implementação”<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Essa capacidade de ligação é essencial para garantir que os requisitos definidos estejam refletidos adequadamente nos artefatos de implementação, assegurando consistência e completude entre o que foi requisitado e o que está sendo construído. Segundo os autores, essa rastreabilidade permite acompanhar a “vida” do requisito ao longo do processo de desenvolvimento, sendo o *forward-from* uma das direções em que esse acompanhamento pode ocorrer.

Essa abordagem favorece o controle de mudanças e facilita a verificação do atendimento aos requisitos ao longo do desenvolvimento. A rastreabilidade *forward-from*, portanto, é uma ferramenta valiosa para garantir a qualidade e a conformidade do produto final.


## Metodologia

Com base no meta-modelo de Toranzo, adaptado por Sayão e Leite, esta metodologia propõe um modelo de rastreabilidade voltado à organização, identificação e manutenção de elos entre os artefatos produzidos no processo de desenvolvimento de software. Foi utilizado o modelo apresentado na **Tabela 3**, composto por *item* e *descrição*. Para facilitar a compreensão das tabelas, também foram incluídas as **Tabelas 1 e 2**, que apresentam as legendas dos artefatos e das técnicas de elicitação, respectivamente. Também é mostrado na **Tabela 4** o cartão de rastreabilidade que cada um desenvolveu.

## Classificação das Informações

Inicialmente, as informações a serem rastreadas são categorizadas em quatro níveis distintos <a id="anchor_2" href="#FRM2"> [2]</a> </q>:

- **Ambiental**: informações externas à organização, como normas regulatórias, fatores políticos ou tendências de mercado.
- **Organizacional**: informações relacionadas à missão, objetivos estratégicos e políticas internas da organização.
- **Gerencial**: dados utilizados na condução e gerenciamento de projetos.
- **Desenvolvimento**: artefatos diretamente relacionados ao processo de desenvolvimento, como requisitos, modelos, código, casos de teste e outros.

No contexto da disciplina, será adotado o nível de desenvolvimento, que abrange os artefatos explorados ao longo das entregas e aplicados no projeto.

## Tipos de Elos de Rastreabilidade

A metodologia considera os seguintes tipos de elos <a id="anchor_2" href="#FRM2"> [2]</a> </q>:

- **Satisfação**: a origem depende da realização do destino (ex.: requisito satisfeito por caso de uso).
- **Recurso**: a origem depende de um recurso fornecido pelo destino (ex.: Sprint depende do backlog do produto).
- **Responsabilidade**: relaciona atores humanos aos artefatos nos quais atuam (ex.: desenvolvedor responsável por requisito).
- **Representação**: o destino representa ou modela o conteúdo da origem (ex.: diagrama que representa requisitos).
- **Alocado**: a origem está alocada a um módulo ou subsistema.
- **Agregação**: o destino é uma composição de elementos da origem.

## Identificação e Categorização dos Artefatos

A tabela abaixo apresenta a legenda com a sigla e o significado dos principais artefatos referenciados nos cartões de rastreabilidade.

<p align="center"><b>Tabela 1</b> — Legenda do mapeamento dos artefatos.</p>

| Sigla | Artefato                  |
|-------|---------------------------|
| UCxx    | Casos de Uso              |
| CENxx    | Cenários                  |
| USxx    | Histórias de Usuário      |
| LEX  | Léxicos                   |
| ES    | Especificação Suplementar |
| NFR   | NFR Framework             |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

## Identificação e Categorização das Técnicas de Elicitação

A tabela abaixo apresenta a legenda com a sigla e as Técnicas de Elicitação referenciados nos cartões de rastreabilidade.

<p align="center"><b>Tabela 2</b> — Legenda do mapeamento das técnicas de elicitação.</p>

| Sigla    | Técnicas               |
| -------- | ------------------------- |
| ADxx       | Análise de Documentos     |
| ENxx       | Entrevista                |
| INTxx      | Introspecção              |
| BRxx       | Brainstorming             |
| RFxx       | Requisitos Funcionais     |
| RNFxx      | Requisitos Não Funcionais |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

## Registro dos Elos

Cada elo deve conter os seguintes elementos:

<font size="3"><p style="text-align: center">Tabela 3: Modelo de Cartão de Rastreabilidade <a id="anchor_2" href="#FRM2"> [2]</a> </q> </p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | [Inserir descrição do requisito funcional ou não funcional]               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | [Inserir links para artefatos relacionados, como requisitos, casos de uso, cenários, léxicos, etc.]<br>Exemplo: [RFXX](#), [ISXX](#), [CEN XX](#), [UCXX](#), [LEX](#) |
| Elos Forward-from   | [Inserir os elos de rastreabilidade com tipo e destino] <br> Exemplo: <br> Satisfação – [Destino]<br> Recurso – [Destino]<br>  Responsabilidade – [Destino] <br> Agregação – [Destino] <br>|
| Status              | Implementado / Não implementado                                           |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

## Registro do que cada participante desenvolveu

<font size="3"><p style="text-align: center">Tabela 4: Elo que cada um participou</p></font>

| Cartão de Rastreabilidade |                         Autor(a) |
|---------------------------|----------------------------------|
| [ELO 01](#elo01), [ELO 02](#elo02), [ELO 03](#elo03), [ELO 09](#elo09), [ELO 15](#elo15), [ELO 20](#elo20),[ELO 57](#elo57),[ELO 61](#elo61)         |  [Ana Victória Guedes da Costa](https://github.com/navicg)   |
| [ELO 04](#elo04), [ELO 05](#elo05),  [ELO 06](#elo06), [ELO 11](#elo11), [ELO 21](#elo21), [ELO 33](#elo33),[ELO 49](#elo49),[ELO 50](#elo50),[ELO 51](#elo51),[ELO 52](#elo52),[ELO 59](#elo59),[ELO 64](#elo64)        |    [Artur Mendonça Arruda](https://github.com/ArtyMend07)      |
|  [ELO 07](#elo07), [ELO 08](#elo08), [ELO 10](#elo10), [ELO 19](#elo19), [ELO 23](#elo23), [ELO 34](#elo34),[ELO 44](#elo44),[ELO 56](#elo56),[ELO 62](#elo62),[ELO 65](#elo65),[ELO 66](#elo66),[ELO 68](#elo68)   |   [Gabriel Lopes](https://github.com/BrzGab)       |
| [ELO 12](#elo12), [ELO 13](#elo13), [ELO 14](#elo14),[ELO 35](#elo35),[ELO 36](#elo36),[ELO 38](#elo38),[ELO 45](#elo45)        |    [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)      |
| [ELO 16](#elo16),  [ELO 25](#elo25), [ELO 26](#elo26) , [ELO 28](#elo28), [ELO 29](#elo29),[ELO 43](#elo43),[ELO 53](#elo53),[ELO 60](#elo60),[ELO 63](#elo63)        |     [Karoline Luz da Conceição](https://github.com/KarolineLuz)    |
| [ELO 17](#elo17), [ELO 24](#elo24),[ELO 37](#elo37),[ELO 39](#elo39),[ELO 40](#elo40),[ELO 41](#elo41),[ELO 42](#elo42),[ELO 47](#elo47),[ELO 48](#elo48),[ELO 54](#elo54),[ELO 55](#elo55),[ELO 67](#elo67)          |     [Lucas Mendonça Arruda](https://github.com/lucasarruda9)     |
| [ELO 18](#elo18), [ELO 22](#elo22), [ELO 27](#elo27), [ELO 30](#elo30), [ELO 31](#elo31), [ELO 32](#elo32),[ELO 46](#elo46),[ELO 58](#elo58)         |     [Luiza da Silva Pugas](https://github.com/Luizaxx)     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

## Cartões de Requisitos Funcionais

### ELO 01 {#elo01}

<font size="3"><p style="text-align: center">Tabela 4: Cartão do Requisito Funcional 01 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve conseguir realizar login de forma simples e rápida             |
| Categoria           | Desenvolvimento                                                          |
| Elementos  Rastreáveis         |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR01</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD01</a>, RF01, [UC01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US29](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us29), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito ao descrever o processo de login.<br>**Recurso**: O cenário detalha os recursos necessários para login simples e rápido.<br>**Satisfação**: A história de usuário satisfaz o requisito ao especificar a necessidade de login simplificado.<br>**Representação**: O léxico representa os termos e conceitos relacionados ao login.<br>**Agregação**:  O requisito é classificado no Épico 01.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito.|
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### ELO 02 {#elo02}

<font size="3"><p style="text-align: center">Tabela 5: Cartão do Requisito Funcional 02 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia        |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR02</a> , RF02, [UC02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US30](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us30), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito ao descrever funcionalidades acessíveis.<br>**Recurso**: O cenário detalha recursos para usuários com pouca familiaridade tecnológica.<br>**Satisfação**:  A história de usuário satisfaz o requisito ao especificar interface intuitiva.<br>**Representação**: O léxico representa termos simplificados para acessibilidade.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### ELO 03 {#elo03}

<font size="3"><p style="text-align: center">Tabela 6: Cartão do Requisito Funcional 03 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder receber notificações personalizadas com base em sua localização           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR03</a>, RF03, [UC03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US31](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us31), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Agregação**: O requisito originou-se do brainstorming.<br> **Satisfação**: O caso de uso satisfaz o requisito ao descrever notificações por localização.<br>**Recurso**: O cenário detalha recursos de geolocalização e notificações.<br>**Satisfação**: A história de usuário satisfaz o requisito de notificações personalizadas.<br>**Representação**: O léxico representa conceitos de localização e notificações.<br>**Agregação**: O requisito está relacionado ao Épico 07.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou  responsável pela elaboração e validação do requisito.|
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 04 {#elo04}

<font size="3"><p style="text-align: center">Tabela 7: Cartão do Requisito Funcional 04 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder consultar agendamentos e serviços em um único local centralizado          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR04</a> , RF04, [UC04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US36](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us36), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de centralização de serviços.<br>**Recurso**: O cenário detalha recursos para consulta centralizada.<br>**Satisfação**: A história de usuário satisfaz o requisito de acesso unificado.<br>**Representação**: O léxico representa conceitos de agendamento e centralização.<br>**Agregação**: O requisito está relacionado ao Épico 04.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 05 {#elo05}

<font size="3"><p style="text-align: center">Tabela 8: Cartão do Requisito Funcional 05 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve ter acesso a um assistente virtual com acessibilidade por voz         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR05</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD05</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT13</a>, RF05, [UC05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US37](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us37), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de assistente virtual.<br>**Recurso**: O cenário detalha recursos de voz e assistência virtual.<br>**Satisfação**: A história de usuário satisfaz o requisito de acessibilidade por voz.<br>**Representação**: O léxico representa conceitos de assistente virtual e comandos de voz.<br>**Agregação**: O requisito está relacionado ao Épico 03.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 06 {#elo06}

<font size="3"><p style="text-align: center">Tabela 9: Cartão do Requisito Funcional 06 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR06</a> , RF06, [UC06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US38](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us38), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de tutoriais.<br>**Recurso**:  O cenário detalha recursos educacionais do app.<br>**Satisfação**:  A história de usuário satisfaz o requisito de guias passo a passo.<br>**Representação**: O léxico representa conceitos de tutorial e ajuda.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 07 {#elo07}

<font size="3"><p style="text-align: center">Tabela 10: Cartão do Requisito Funcional 07 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder alterar o tamanho da fonte e o contraste de cores             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR07</a>, <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD08</a>, RF07, [UC07](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN07](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us15), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de personalização visual.<br>**Recurso**:  O cenário detalha recursos de acessibilidade visual.<br>**Satisfação**:  A história de usuário satisfaz o requisito de ajustes visuais.<br>**Representação**: O léxico representa conceitos de fonte e contraste.<br>**Agregação**: O requisito está relacionado ao Épico 03.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab) 2025)</p></font>


### ELO 08 {#elo08}

<font size="3"><p style="text-align: center">Tabela 11: Cartão do Requisito Funcional 08 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |O aplicativo deve permitir modo escuro          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR08</a>, RF08, [UC08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us16), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |**Satisfação**: O caso de uso satisfaz o requisito de modo escuro.<br>**Recurso**:  O cenário detalha recursos de tema escuro.<br>**Satisfação**:  A história de usuário satisfaz o requisito de personalização de tema.<br>**Representação**:  O léxico representa conceitos de modo escuro.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab) 2025)</p></font>


### ELO 09 {#elo09}

<font size="3"><p style="text-align: center">Tabela 12: Cartão do Requisito Funcional 09 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |	O usuário deve poder acessar e visualizar notícias relevantes            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR10</a>, RF09, [US32](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us32) e  [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de informações relevantes.<br>**Agregação**: O requisito está relacionado ao Épico  05.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito.|
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 10 {#elo10}

<font size="3"><p style="text-align: center">Tabela 13: Cartão do Requisito Funcional 10 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentosr realizar login de forma simples e rápida             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |   <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR11</a> , RF10, [UC09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us17), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de geração de relatórios.<br>**Recurso**: O cenário detalha recursos de comprovantes.<br>**Satisfação**: A história de usuário satisfaz o requisito de documentação.<br>**Representação**: O léxico representa conceitos de relatório e comprovante.<br>**Agregação**: O requisito está relacionado ao Épico  08. <br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab) 2025)</p></font>


### ELO 11 {#elo11}

<font size="3"><p style="text-align: center">Tabela 14: Cartão do Requisito Funcional 11 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR12</a> , RF11,  [US39](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us39) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de serviços integrados.<br>**Agregação**: O requisito está relacionado ao Eṕico 04.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              |Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 12 {#elo12}

<font size="3"><p style="text-align: center">Tabela 15: Cartão do Requisito Funcional 12 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder alterar o idioma do aplicativo          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR13</a>, RF12, [UC10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us08), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |  **Satisfação**: O caso de uso satisfaz o requisito de mudança de idioma.<br>**Recurso**:  O cenário detalha recursos de internacionalização.<br>**Satisfação**:  A história de usuário satisfaz o requisito de múltiplos idiomas.<br>**Representação**:  O léxico representa conceitos de idioma e tradução.<br>**Agregação**: O requisito está relacionado ao Épico 02. <br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 13 {#elo13}

<font size="3"><p style="text-align: center">Tabela 16: Cartão do Requisito Funcional 13 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |   <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR14</a>, RF13, [UC11](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN11](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us09), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de personalização de perfil.<br>**Recurso**: O cenário detalha recursos de preferências personalizadas.<br>**Satisfação**:  A história de usuário satisfaz o requisito de recomendações.<br>**Representação**:  O léxico representa conceitos de perfil e preferências.<br>**Agregação**: O requisito está relacionado ao Épico 02. <br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 14 {#elo14}

<font size="3"><p style="text-align: center">Tabela 17: Cartão do Requisito Funcional 14 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR15</a>, RF14, [UC12](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN12](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us10), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de lembretes.<br>**Recurso**:  O cenário detalha recursos de notificações de vencimento.<br>**Satisfação**:  A história de usuário satisfaz o requisito de alertas.<br>**Representação**: O léxico representa conceitos de lembrete e notificação.<br>**Agregação**: O requisito está relacionado ao Épico 07.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 15 {#elo15}

<font size="3"><p style="text-align: center">Tabela 18: Cartão do Requisito Funcional 16 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar um menu com as principais funções logo na tela inicial           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR16</a>, RF15, [US33](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us33) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: RF15 - [US33](./historia-de-usuario.md): A história de usuário satisfaz o requisito de acesso rápido.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF15: Responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 16 {#elo16}

<font size="3"><p style="text-align: center">Tabela 19: Cartão do Requisito Funcional 16 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR17</a> , RF16, [UC15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US22](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us22), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de gestão de agendamentos.<br>**Recurso**:  O cenário detalha recursos de reagendamento.<br>**Satisfação**: A história de usuário satisfaz o requisito de centralização.<br>**Representação**: O léxico representa conceitos de agendamento.<br>**Agregação**: O requisito está relacionado ao Épico 06.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 17 {#elo17}

<font size="3"><p style="text-align: center">Tabela 20: Cartão do Requisito Funcional 17 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte        |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR19</a>, RF07, [UC14](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN14](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US48](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us48), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |  **Satisfação**: O caso de uso satisfaz o requisito de categorização.<br>**Recurso**: O cenário detalha recursos de notificações categorizadas.<br>**Satisfação**: A história de usuário satisfaz o requisito de filtros.<br>**Representação**: O léxico representa conceitos de categorias.<br>**Agregação**: O requisito está relacionado ao Épico 07. <br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 18 {#elo18}

<font size="3"><p style="text-align: center">Tabela 21: Cartão do Requisito Funcional 18 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR20</a>, RF18, [UC18](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN18](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us02), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de compartilhamento.<br>**Recurso**: O cenário detalha recursos de salvamento e compartilhamento.<br>**Satisfação**: A história de usuário satisfaz o requisito de exportação.<br>**Representação**: O léxico representa conceitos de protocolo e compartilhamento.<br>**Agregação**: O requisito está relacionado ao Épico 08.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 19 {#elo19}

<font size="3"><p style="text-align: center">Tabela 22: Cartão do Requisito Funcional 19 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN01</a>, RF19, [US18](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us18) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de rastreamento em tempo real.<br>**Recurso**: O cenário detalha recursos de localização e mapas.<br>**Satisfação**: A história de usuário satisfaz o requisito de transporte público.<br>**Representação**: O léxico representa conceitos de transporte e GPS.<br>**Agregação**: O requisito está relacionado ao Épico 10.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 20 {#elo20}

<font size="3"><p style="text-align: center">Tabela 23: Cartão do Requisito Funcional 20 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo fornece links para serviços externos (como Secretaria da Fazenda) de forma eficiente, com explicações claras sobre o que o usuário encontrará após clicar.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN02</a>, RF20,[US34](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us34) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de clareza nas explicações.<br>**Agregação**: O requisito está relacionado ao Épico 04.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 21 {#elo21}

<font size="3"><p style="text-align: center">Tabela 24: Cartão do Requisito Funcional 21 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN03</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT07</a>, RF21,[US40](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us40) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz parcialmente o requisito de informações educacionais.<br>**Agregação**: O requisito está relacionado ao Épico 05.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 22 {#elo22}

<font size="3"><p style="text-align: center">Tabela 25: Cartão do Requisito Funcional 22 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial.           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a> , RF22, [UC17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us01), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | ***Satisfação**: O caso de uso satisfaz o requisito de autenticação segura.<br>**Recurso**: O cenário detalha recursos de autenticação gov.br.<br>**Satisfação**: A história de usuário satisfaz o requisito de login seguro.<br>**Representação**: O léxico representa conceitos de autenticação e segurança.<br>**Agregação**: O requisito está relacionado ao Épico 01.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 23 {#elo23}

<font size="3"><p style="text-align: center">Tabela 26: Cartão do Requisito Funcional 23 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN05</a>, RF23,  [US19](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us19) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de clareza fiscal.<br>**Agregação**:O requisito está relacionado ao Épico 04. <br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 24 {#elo24}

<font size="3"><p style="text-align: center">Tabela 27: Cartão do Requisito Funcional 24 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos.            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN06</a>, RF24, [UC13](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN13](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US46](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us46), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |**Satisfação**:  O caso de uso satisfaz o requisito de acompanhamento educacional.<br>**Recurso**: O cenário detalha recursos de pendências escolares.<br>**Satisfação**: A história de usuário satisfaz o requisito de gestão educacional.<br>**Agregação**: O requisito está relacionado ao Épico 04. <br>**Representação**: O léxico representa conceitos de educação e pendências.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 25 {#elo25}

<font size="3"><p style="text-align: center">Tabela 28: Cartão do Requisito Funcional 25 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir que usuários reportem problemas da cidade através de um mapa interativo.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN09</a>, RF25, [UC16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US23](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us23), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de reporte interativo.<br>**Recurso**: O cenário detalha recursos de mapa interativo.<br>**Satisfação**: A história de usuário satisfaz o requisito de reporte geolocalizado.<br>**Representação**: O léxico representa conceitos de mapa e reporte.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 26 {#elo26}

<font size="3"><p style="text-align: center">Tabela 29: Cartão do Requisito Funcional 26 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve fornecer acesso a números de serviços de emergência da polícia.            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN10</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT05</a> , RF26, [US24](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us24) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de segurança pública.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito.  |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 27 {#elo27}

<font size="3"><p style="text-align: center">Tabela 30: Cartão do Requisito Funcional 27 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso.        |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |   <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN11</a>, RF27, [UC19](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN19](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us03), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de suporte.<br>**Recurso**: O cenário detalha recursos de ajuda.<br>**Satisfação**: A história de usuário satisfaz o requisito de instruções.<br>**Representação**: O léxico representa conceitos de suporte e ajuda.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 28 {#elo28}

<font size="3"><p style="text-align: center">Tabela 31: Cartão do Requisito Funcional 28 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos.         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD02</a>, RF28, [US01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us01) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de solicitações.<br>**Agregação**: O requisito está relacionado ao Épico 09.  <br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 29 {#elo29}

<font size="3"><p style="text-align: center">Tabela 32: Cartão do Requisito Funcional 29 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacaotec_elicitacao/analise_documentos/#anchor_AD">AD03</a>, RF29,[US26](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us26) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de visualização espacial.<br>**Agregação**: O requisito está relacionado ao Epico 09. <br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 30 {#elo30}

<font size="3"><p style="text-align: center">Tabela 33: Cartão do Requisito Funcional 30 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD04</a>, RF30, [US04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us04) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de monitoramento.<br>**Agregação**: O requisito está relacionado ao Épico 06.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 31 {#elo31}

<font size="3"><p style="text-align: center">Tabela 34: Cartão do Requisito Funcional 31 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O sistema deve permitir que o usuário confirme a resolução de problemas relatados.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD06</a>, RF31, [US05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us05) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de feedback.<br>**Agregação**: O requisito está relacionado ao Épico 06.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 32 {#elo32}

<font size="3"><p style="text-align: center">Tabela 35: Cartão do Requisito Funcional 32 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |    <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD07</a> , RF32, [US06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us06) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de controle de dados.<br>**Agregação**: O requisito está relacionado ao Épico  11.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 33 {#elo33}

<font size="3"><p style="text-align: center">Tabela 36: Cartão do Requisito Funcional 33 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT01</a>, RF33, [US41](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us41) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de reporte urbano.<br>**Agregação**: O requisito está relacionado ao Épico  09.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito.|
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 34 {#elo34}

<font size="3"><p style="text-align: center">Tabela 37: Cartão do Requisito Funcional 34 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes.       |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT02</a>, RF34, [US20](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us20) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/)                                      |
Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de organização.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              |Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 35 {#elo35}

<font size="3"><p style="text-align: center">Tabela 36: Cartão do Requisito Funcional 35 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo)               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF35,[INT03](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [US11](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md#anchor_US),[LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Agregação – O requisito originou-se da introspecção.<br> Satisfação – O caso de uso satisfaz o requisito de seleção de serviços.<br> Recurso – O cenário detalha recursos de tipos de serviço.<br> Satisfação – A história de usuário satisfaz o requisito de escolha.<br> Representação – O léxico representa conceitos de serviços e seleção.<br> Agregação – O requisito está relacionado ao Épico correspondente.<br> Responsabilidade – [João Marcos](https://github.com/JJOAOMARCOSS) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |




<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### ELO 36 {#elo36}

<font size="3"><p style="text-align: center">Tabela 37: Cartão do Requisito Funcional 36 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF36, [INT04](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação –O caso de uso satisfaz o requisito de documentação detalhada.<br> Recurso – O cenário detalha recursos multimídia.<br> Satisfação – A história de usuário satisfaz o requisito de registro completo.<br> Representação –  O léxico representa conceitos de mídia e localização.<br> Responsabilidade – [João Marcos](https://github.com/JJOAOMARCOSS) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 37 {#elo37}

<font size="3"><p style="text-align: center">Tabela 38: Cartão do Requisito Funcional 37 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF37, [INT06](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [US45](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de agendamento de saúde.<br> Recurso – O cenário detalha recursos de saúde pública.<br> Satisfação – A história de usuário satisfaz o requisito de serviços médicos.<br> Representação – O léxico representa conceitos de saúde e agendamento.<br> Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 38 {#elo38}

<font size="3"><p style="text-align: center">Tabela 39: Cartão do Requisito Funcional 38 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF38, [INT08](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [US13](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de transporte.<br> Recurso – O cenário detalha recursos de mobilidade.<br> Satisfação – A história de usuário satisfaz o requisito de cartão mobilidade.<br> Representação – O léxico representa conceitos de transporte público.<br> Responsabilidade – [João Marcos](https://github.com/JJOAOMARCOSS) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 39 {#elo39}

<font size="3"><p style="text-align: center">Tabela 40: Cartão do Requisito Funcional 39 </p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Permitir agendamentos em serviços sociais, como centros de assistência social e habitação               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF39, [INT09](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [US43](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de serviços sociais.<br> Recurso – O cenário detalha recursos de assistência social.<br> Satisfação – A história de usuário satisfaz o requisito de agendamentos sociais.<br> Representação – O léxico representa conceitos de assistência e habitação.<br> Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 40 {#elo40}

<font size="3"><p style="text-align: center">Tabela 41: Cartão do Requisito Funcional 40 </p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  RF40, [INT10](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [US47](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de documentos fiscais.<br> Recurso – O cenário detalha recursos tributários.<br> Satisfação – A história de usuário satisfaz o requisito de emissão de documentos.<br> Representação – O léxico representa conceitos fiscais e tributários..<br> Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. | |
| Status              | Implementado                                                           |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 41 {#elo41}

<font size="3"><p style="text-align: center">Tabela 42: Cartão do Requisito Funcional 41</p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  RF41, [INT11](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [US44](./historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de histórico.<br> Recurso – O cenário detalha recursos de registro de atividades.<br> Satisfação – A história de usuário satisfaz o requisito de rastreamento.<br> Representação – O léxico representa conceitos de histórico e registro.<br> Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 42 {#elo42}

<font size="3"><p style="text-align: center">Tabela 43: Cartão do Requisito Funcional 42 </p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF42, [INT12](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [US45](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de feed informativo.<br> Recurso – O cenário detalha recursos de notícias.<br> Satisfação – A história de usuário satisfaz o requisito de informações governamentais.<br> Representação – O léxico representa conceitos de notícias e comunicação.<br> Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 43 {#elo43}

<font size="3"><p style="text-align: center">Tabela 44: Cartão do Requisito Funcional 43 </p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes dos usuários               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF43, [INT13](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [BR18](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [UC](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/docs/elo-backward/docs/modelagem/casos_de_uso.md), [US27](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de assistente virtual.<br> Recurso – O cenário detalha recursos de chatbot.<br> Satisfação – A história de usuário satisfaz o requisito de suporte automatizado.<br> Representação – O léxico representa conceitos de assistente e automação.<br> Responsabilidade – [Karoline Luz](https://github.com/KarolineLuz) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 44 {#elo44}

<font size="3"><p style="text-align: center">Tabela 45: Cartão do Requisito Funcional 44</p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RF44, [INT14](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de mapa de serviços.<br> Recurso – O cenário detalha recursos de localização espacial.<br> Satisfação – A história de usuário satisfaz o requisito de visualização geográfica.<br> Representação – O léxico representa conceitos de mapa e localização.<br> Responsabilidade – [Gabriel Lopes](https://github.com/BrzGab) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


## Cartões de Requisitos Não Funcionais

### ELO 45 {#elo45}

<font size="3"><p style="text-align: center">Tabela 46: Cartão do Requisito Não Funcional 01 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve ser compatível com vários dispositivos como Android e iOS               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RNF01, [AD09](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/analise_documentos.md), [US14](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de compatibilidade.<br> Representação – O NFR Framework representa as metas de portabilidade.<br> Satisfação – A história de usuário satisfaz o requisito de compatibilidade multiplataforma.<br> Responsabilidade – [João Marcos](https://github.com/JJOAOMARCOSS) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 46 {#elo46}

<font size="3"><p style="text-align: center">Tabela 47: Cartão do Requisito Não Funcional 02 </p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD)               |
| Categoria           | Organizacional                                                          |
| Elementos Rastreáveis           | RNF02, [AD10](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/analise_documentos.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/docs/elo-backward/docs/modelagem/agil/nfrframework.md), [US07](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito legal.<br> Representação – O NFR Framework representa as metas de conformidade legal.<br> Satisfação – A história de usuário satisfaz o requisito de conformidade LGPD.<br> Responsabilidade – [Luiza Silva](https://github.com/Luizaxx) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>



### ELO 47 {#elo47}

<font size="3"><p style="text-align: center">Tabela 48: Cartão do Requisito Não Funcional 03 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve possuir uma inteELO ace simples, limpa e com ícones ilustrativos |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | RNF03, [BRN01](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de usabilidade.<br> Representação – O NFR Framework representa as metas de inteELO ace.<br> Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>



### ELO 48 {#elo48}

<font size="3"><p style="text-align: center">Tabela 49: Cartão do Requisito Não Funcional 04 </p></font>

| Item                   | Descrição                                                                                                         |
|------------------------|-----------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                          |
| Categoria              | Desenvolvimento                                                                                                  |
| Elementos Rastreáveis  | RNF04, [BRN02](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de acessibilidade.<br>Recurso – O cenário detalha recursos de acessibilidade.<br>Satisfação – A história de usuário satisfaz o requisito de inclusão digital.<br>Representação – O léxico representa conceitos de acessibilidade e usabilidade.<br>Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status                 | Não implementado                                                                                                 |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 49 {#elo49}

<font size="3"><p style="text-align: center">Tabela 50: Cartão do Requisito Não Funcional 05 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis | RNF05, [BRN04](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de performance.<br> Representação – O NFR Framework representa as metas de eficiência.<br> Responsabilidade – [Artur Mendonça](https://github.com/ArtyMend07) pela elaboração e validação do requisito. |
| Status              | Implementado                                                             |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 50 {#elo50}

<font size="3"><p style="text-align: center">Tabela 51: Cartão do Requisito Não Funcional 06 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis | RNF07, [BRN06](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de otimização.<br> Recurso – O cenário detalha recursos de carregamento otimizado.<br> Satisfação – A história de usuário satisfaz o requisito de desempenho.<br> Representação – O NFR Framework representa as metas de desempenho.<br> Responsabilidade – [Artur Mendonça](https://github.com/ArtyMend07) pela elaboração e validação do requisito. |
| Status              | Implementado                                                             |




<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 51 {#elo51}

<font size="3"><p style="text-align: center">Tabela 52: Cartão do Requisito Não Funcional 07 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis | RNF07, [BRN06](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de otimização.<br> Representação – O NFR Framework representa as metas de desempenho.<br> Responsabilidade – [Artur Mendonça](https://github.com/ArtyMend07) pela elaboração e validação do requisito.
| Status              | Implementado                                                             |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

### ELO 52 {#elo52}

<font size="3"><p style="text-align: center">Tabela 53: Cartão do Requisito Não Funcional 08 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O layout deve ser responsivo para diferentes tamanhos de tela            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis | RNF08, [BRN07](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [INT22](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de responsividade.<br> Recurso – O cenário detalha recursos para responsividade.<br> Representação – O NFR Framework representa as metas de adaptabilidade.<br> Responsabilidade – [Artur Mendonça](https://github.com/ArtyMend07) pela elaboração e validação do requisito. |
| Status              | Implementado                                                             |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 53 {#elo53}

<font size="3"><p style="text-align: center">Tabela 54: Cartão do Requisito Não Funcional 09 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve ter compatibilidade com leitores de tela                  |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis | RNF09, [BRN08](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de acessibilidade.<br> Recurso – O cenário detalha recursos para acessibilidade.<br> Representação – O NFR Framework representa as metas de acessibilidade.<br> Responsabilidade – [Karoline Luz](https://github.com/KarolineLuz) pela elaboração e validação do requisito. |
| Status              | Implementado                                                             |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 54 {#elo54}

<font size="3"><p style="text-align: center">Tabela 55: Cartão do Requisito Não Funcional 10 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis| RNF10, [BRN09](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de comunicação clara.<br>Representação – O NFR Framework representa as metas de legibilidade.<br>Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Não implementado                                                         |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 55 {#elo55}

<font size="3"><p style="text-align: center">Tabela 56: Cartão do Requisito Não Funcional 11 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis| RNF11, [EN01](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [AD11](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/analise_documentos.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md) |
| Elos Forward-from   | Satisfação – A especificação suplementar satisfaz o requisito de intuitividade.<br>Representação – O NFR Framework representa as metas de autonomia do aplicativo.<br>Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status              | Não implementado                                                         |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 56 {#elo56}

<font size="3"><p style="text-align: center">Tabela 57: Cartão do Requisito Não Funcional 12 </p></font>


| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação |
| Categoria              | Desenvolvimento                                                                                                                               |
| Elementos Rastreáveis  | RNF12, [EN02](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de confiabilidade.<br>Representação – O NFR Framework representa as metas de precisão da informação.<br>Responsabilidade – [Gabriel Lopes](https://github.com/BrzGab) pela elaboração e validação do requisito. |
| Status                 | Implementado                                                                                                                                   |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 57 {#elo57}

<font size="3"><p style="text-align: center">Tabela 58: Cartão do Requisito Não Funcional 13 </p></font>

| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis                      |
| Categoria              | Desenvolvimento                                                                                                                               |
| Elementos Rastreáveis  | RNF13, [EN03](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md), [US35](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de estabilidade.<br>Representação – O NFR Framework representa as metas de robustez.<br>Responsabilidade – [Ana Victória Guedes da Costa](https://github.com/navicg) pela elaboração e validação do requisito. |
| Status                 | Não implementado                                                                                                                               |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025)</p></font>


### ELO 58 {#elo58}

<font size="3"><p style="text-align: center">Tabela 59: Cartão do Requisito Não Funcional 14 </p></font>

| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança                    |
| Categoria              | Organizacional                                                                                                                                |
| Elementos Rastreáveis  | RNF14, [EN04](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de segurança de dados.<br>Representação – O NFR Framework representa as metas de privacidade e proteção.<br>Responsabilidade – [Luiza da Silva Pugas](https://github.com/Luizaxx) pela elaboração e validação do requisito. |
| Status                 | Implementado                                                                                                                                  |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>


### ELO 59 {#elo59}

<font size="3"><p style="text-align: center">Tabela 60: Cartão do Requisito Não Funcional 15 </p></font>


| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida                                          |
| Categoria              | Desenvolvimento                                                                                                                               |
| Elementos Rastreáveis  | RNF15, [EN05](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de performance de autenticação.<br>Representação – O NFR Framework representa as metas de velocidade de login.<br>Responsabilidade – [Arthur Mendonça](https://github.com/ArtyMend07) pela elaboração e validação do requisito. |
| Status                 | Não Implementado                                                                                                                              |


<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Arthur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 60 {#elo60}

<font size="3"><p style="text-align: center">Tabela 61: Cartão do Requisito Não Funcional 16 </p></font>

| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis |
| Categoria              | Desenvolvimento                                                                                                                               |
| Elementos Rastreáveis  | RNF16, [EN06](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [US28](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de usabilidade para idosos.<br>Representação – O NFR Framework representa as metas de design inclusivo.<br>Responsabilidade – [Karoline Luz da Conceição](https://github.com/KarolineLuz) pela elaboração e validação do requisito. |
| Status                 | Não Implementado                                                                                                                              |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 61 {#elo61}

<font size="3"><p style="text-align: center">Tabela 62: Cartão do Requisito Não Funcional 17 </p></font>

| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais                              |
| Categoria              | Desenvolvimento                                                                                                                               |
| Elementos Rastreáveis  | RNF17, [EN07](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [INT19](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de acessibilidade visual.<br>Representação – O NFR Framework representa as metas de inclusão visual.<br>Responsabilidade – [Ana Victória Guedes da Costa](https://github.com/navicg) pela elaboração e validação do requisito. |
| Status                 | Não Implementado                                                                                                                              |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025)</p></font>


### ELO 62 {#elo62}

<font size="3"><p style="text-align: center">Tabela 63: Cartão do Requisito Não Funcional 18 </p></font>

| Item                   | Descrição                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários                                            |
| Categoria              | Desenvolvimento                                                                                                                               |
| Elementos              | RNF18, [EN08](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/entrevista.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – A especificação suplementar satisfaz o requisito de aparência.<br>Representação – O NFR Framework representa as metas de design profissional.<br>Responsabilidade – [Gabriel Lopes](https://github.com/BrzGab) pela elaboração e validação do requisito. |
| Status                 | Não implementado                                                                                                                              |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 63 {#elo63}

<font size="3"><p style="text-align: center">Tabela 64: Cartão do Requisito Não Funcional 19 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes dos usuários               |
| Categoria           | Desenvolvimento                                                          |
| Elementos           | RF43, [INT13](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [BR18](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/brainstorming.md),[UC](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/docs/elo-backward/docs/modelagem/casos_de_uso.md), [US27](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md) |
| Elos Forward-from   | Satisfação – O caso de uso satisfaz o requisito de assistente virtual.<br> Recurso – O cenário detalha recursos de chatbot.<br> Satisfação – A história de usuário satisfaz o requisito de suporte automatizado.<br> Representação – O léxico representa conceitos de assistente e automação.<br> Responsabilidade – [Karoline Luz](https://github.com/KarolineLuz) pela elaboração e validação do requisito. |
| Status              | Implementado                                                           |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 64 {#elo64}
<font size="3"><p style="text-align: center">Tabela 65: Cartão do Requisito Não Funcional 20 </p></font>



| Item                   | Descrição                                                                                                         |
|------------------------|-------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito  | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência          |
| Categoria              | Desenvolvimento                                                                                                   |
| Elementos Rastreáveis   | RNF20, [INT16](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md), [US42](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from       | Satisfação – A especificação suplementar satisfaz o requisito de tempo de resposta.<br>Representação – O NFR Framework representa as metas de latência.<br>Responsabilidade – [Artur Mendonça](https://github.com/ArtyMend07) pela elaboração e validação do requisito. |
| Status                 | Implementado                                                                         

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

### ELO 65 {#elo65}

<font size="3"><p style="text-align: center">Tabela 66: Cartão do Requisito Não Funcional 21 </p></font>

| Item                   | Descrição                                                                                                          |
|------------------------|--------------------------------------------------------------------------------------------------------------------|
| Descrição do requisito  | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade |
| Categoria              | Desenvolvimento                                                                                                    |
| Elementos Rastreáveis   | RNF21, [INT17](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from       | Satisfação – A especificação suplementar satisfaz o requisito de simplicidade.<br>Representação – O NFR Framework representa as metas de clareza comunicativa.<br>Responsabilidade – [Gabriel Lopes](https://github.com/BrzGab) pela elaboração e validação do requisito. |
| Status                 | Implementado                                                                                                                |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 66 {#elo66}

<font size="3"><p style="text-align: center">Tabela 67: Cartão do Requisito Não Funcional 22 </p></font>

| Item                   | Descrição                                                                                                    |
|------------------------|--------------------------------------------------------------------------------------------------------------|
| Descrição do requisito  | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura               |
| Categoria              | Organizacional                                                                                                |
| Elementos Rastreáveis   | RNF22, [INT18](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [Backlog](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/backlog.md), [US21](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md) |
| Elos Forward-from       | Satisfação – A especificação suplementar satisfaz o requisito de criptografia.<br>Representação – O NFR Framework representa as metas de segurança técnica.<br>Responsabilidade – [Gabriel Lopes](https://github.com/BrzGab) pela elaboração e validação do requisito. |
| Status                 | Implementado                                                                                                         |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>




### ELO 67 {#elo67}

<font size="3"><p style="text-align: center">Tabela 68: Cartão do Requisito Não Funcional 23 </p></font>

| Item                 | Descrição                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------|
| Descrição do requisito | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas |
| Categoria            | Desenvolvimento                                                                               |
| Elementos Rastreáveis | RNF23, [INT20](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [US49](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/historia-de-usuario.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from    | Satisfação – A especificação suplementar satisfaz o requisito de funcionalidade offline.<br>Representação – O NFR Framework representa as metas de disponibilidade.<br>Responsabilidade – [Lucas Mendonça](https://github.com/lucasarruda9) pela elaboração e validação do requisito. |
| Status               | Não    Implementado                                                                                        |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>



### ELO 68 {#elo68}
<font size="3"><p style="text-align: center">Tabela 69: Cartão do Requisito Não Funcional 24 </p></font>

| Item                   | Descrição                                                                                                         |
|------------------------|-----------------------------------------------------------------------------------------------------------------|
| Descrição do requisito | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis              |
| Categoria              | Desenvolvimento                                                                                                  |
| Elementos Rastreáveis  | RNF24, [INT21](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/elicitacao/tec_elicitacao/introspeccao.md), [NFR](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/agil/nfrframework.md), [LEX](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/main/docs/modelagem/lexico.md) |
| Elos Forward-from      | Satisfação – RNF24 - ES: A especificação suplementar satisfaz o requisito de otimização de mídia.<br>Representação – RNF24 - NFR: O NFR Framework representa as metas de eficiência de upload.<br>Responsabilidade – [Gabriel Lopes](https://github.com/BrzGab) pela elaboração e validação do requisito. |
| Status                 | Implementado                                                                                                             |



<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>



# Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação n° 20/05. Departamento de Informática, PUC-Rio, 2005.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/elo-forward/docs/assets/rastreabilidade/forward_from/referencia_1.png" >
</div>

> <a id="FRM2" href="#anchor_2">2.</a> SERRANO, Milene; SERRANO, Maurício. *Requisitos – Aula 26*. 2025. Disponível em: [Apresentação de slides](https://aprender3.unb.br/pluginfile.php/3096178/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 8 jun. 2025.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/elo-forward/docs/assets/rastreabilidade/forward_from/refrencia_2.1.png" >
</div>

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/elo-forward/docs/assets/rastreabilidade/forward_from/referencia_2.png" >
</div>

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/elo-forward/docs/assets/rastreabilidade/forward_from/referencia_2.2.png" >
</div>

# Histórico de Versões

| Versão | Descrição                                                                                          | Autor(es)                                             | Data       | Revisor(es)                                        | Data de revisão |
| ------ | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ---------- | -------------------------------------------------- | --------------- 
| 1.0    | Adicionando introdução e metologia do forward-from | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 08/06/2025  |
| 1.2   | Ajustando autores das tabelas | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Luiza Silva](https://github.com/Luizaxx) | 08/06/2025  |
| 1.3   | Adicionando imgs das referências bibliográficas | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |
| 1.4   |  Adicionando cartão de rastreabilidade relacionado ao ELO 16, ELO 25, ELO 26 , ELO 28, ELO 29,ELO 43,ELO 53,ELO 60,ELO 63 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 08/06/2025  |
| 1.4   | Adicionando cartão de rastreabilidade relacionado ao  ELO 04, ELO 05, ELO 06, ELO 11, ELO 21, ELO 33,ELO 49,ELO 50,ELO 51,ELO 52,ELO 59 e ELO 64 | [Artur Mendonça](https://github.com/ArtyMend07)| 08/06/2025 | [Luiza Silva](https://github.com/Luizaxx) | 08/06/2025  |
| 1.5   | Adicionando cartão de rastreabilidade relacionado ao  ELO 17, ELO 24,ELO 37,ELO 39,ELO 40,ELO 41,ELO 42,ELO 47,ELO 48,ELO 54,ELO 55,ELO 67  |  [Lucas Mendonça](https://github.com/lucasarruda9) | 08/06/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 08/06/2025  |
| 1.6   | Adicionando cartão de rastreabilidade relacionado ao  ELO 18, ELO 22, ELO 27, ELO 30, ELO 31, ELO 32,ELO 46,ELO 58  |  [Luiza Silva](https://github.com/Luizaxx) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |
| 1.7   | Adicionando cartão de rastreabilidade relacionado ao  ELO 07, ELO 08, ELO 10, ELO 19, ELO 23, ELO 34,ELO 44,ELO 56,ELO 62,ELO 65,ELO 66,ELO 68 | [Gabriel Lopes](https://github.com/BrzGab) | 08/06/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 08/06/2025  |
| 1.8   | Adicionando cartão de rastreabilidade relacionado ao  ELO 12, ELO 13, ELO 14,ELO 35,ELO 36,ELO 38,ELO 45  |[João Marcos Moraes](https://github.com/JJOAOMARCOSS)| 08/06/2025 |  [Lucas Mendonça](https://github.com/lucasarruda9) | 08/06/2025  |
| 1.9    | Adicionando cartão de rastreabilidade relacionado ao ELO 01, ELO 02, ELO 03, ELO 09, ELO 15, ELO 20,ELO 57 e ELO 61 | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 08/06/2025  |