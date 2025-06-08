# Forward-From

## Introdução

O conceito de *forward-from* está relacionado à rastreabilidade para frente (*forward traceability*), que permite a ligação dos requisitos a artefatos desenvolvidos nas fases posteriores do ciclo de vida do software. De acordo com Sayão e Leite (2005), “no primeiro tipo temos a rastreabilidade *forward-to* (para frente), que liga documentos obtidos no processo de elicitação a requisitos relevantes” <a id="anchor_1" href="#FRM1"> [1]</a> </q>, e mais adiante, os autores descrevem que “no segundo tipo temos rastreabilidade *forward-from*, que liga requisitos a artefatos de desenho e implementação”<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Essa capacidade de ligação é essencial para garantir que os requisitos definidos estejam refletidos adequadamente nos artefatos de implementação, assegurando consistência e completude entre o que foi requisitado e o que está sendo construído. Segundo os autores, essa rastreabilidade permite acompanhar a “vida” do requisito ao longo do processo de desenvolvimento, sendo o *forward-from* uma das direções em que esse acompanhamento pode ocorrer.

Essa abordagem favorece o controle de mudanças e facilita a verificação do atendimento aos requisitos ao longo do desenvolvimento. A rastreabilidade *forward-from*, portanto, é uma ferramenta valiosa para garantir a qualidade e a conformidade do produto final.


## Metodologia

Com base no meta-modelo de Toranzo, adaptado por Sayão e Leite, esta metodologia propõe um modelo de rastreabilidade voltado à organização, identificação e manutenção de elos entre os artefatos produzidos no processo de desenvolvimento de software.

## Classificação das Informações

Inicialmente, as informações a serem rastreadas são categorizadas em quatro níveis distintos:

- **Ambiental**: informações externas à organização, como normas regulatórias, fatores políticos ou tendências de mercado.
- **Organizacional**: informações relacionadas à missão, objetivos estratégicos e políticas internas da organização.
- **Gerencial**: dados utilizados na condução e gerenciamento de projetos.
- **Desenvolvimento**: artefatos diretamente relacionados ao processo de desenvolvimento, como requisitos, modelos, código, casos de teste e outros.

No contexto da disciplina, será adotado o nível de desenvolvimento, que abrange os artefatos explorados ao longo das entregas e aplicados no projeto.

## Tipos de Elos de Rastreabilidade

A metodologia considera os seguintes tipos de elos:

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

<font size="3"><p style="text-align: center">Tabela 3: Modelo de Cartão de Rastreabilidade</p></font>


| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | [Inserir descrição do requisito funcional ou não funcional]               |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | [Inserir links para artefatos relacionados, como requisitos, casos de uso, cenários, léxicos, etc.]<br>Exemplo: [RFXX](#), [ISXX](#), [CEN XX](#), [UCXX](#), [LEX](#) |
| Elos Forward-from   | [Inserir os elos de rastreabilidade com tipo e destino] <br> Exemplo: <br> Satisfação – [Destino]<br> Recurso – [Destino]<br>  Responsabilidade – [Destino] <br> Agregação – [Destino] <br>|
| Status              | Implementado / Não implementado                                           |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

## Cartões de Requisitos Funcionais

### ELO 01

<font size="3"><p style="text-align: center">Tabela 4: Cartão do Requisito Funcional 01 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve conseguir realizar login de forma simples e rápida             |
| Categoria           | Desenvolvimento                                                          |
| Elementos  Rastreáveis         |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR01</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD01</a>, RF01, [UC01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US29](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us29), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito ao descrever o processo de login.<br>**Recurso**: O cenário detalha os recursos necessários para login simples e rápido.<br>**Satisfação**: A história de usuário satisfaz o requisito ao especificar a necessidade de login simplificado.<br>**Representação**: O léxico representa os termos e conceitos relacionados ao login.<br>**Agregação**:  O requisito é classificado no Épico 01.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito.|
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### ELO 02

<font size="3"><p style="text-align: center">Tabela 5: Cartão do Requisito Funcional 02 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia        |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR02</a> , RF02, [UC02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US30](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us30), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito ao descrever funcionalidades acessíveis.<br>**Recurso**: O cenário detalha recursos para usuários com pouca familiaridade tecnológica.<br>**Satisfação**:  A história de usuário satisfaz o requisito ao especificar interface intuitiva.<br>**Representação**: O léxico representa termos simplificados para acessibilidade.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### ELO 03

<font size="3"><p style="text-align: center">Tabela 6: Cartão do Requisito Funcional 03 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder receber notificações personalizadas com base em sua localização           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR03</a>, RF03, [UC03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US31](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us31), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Agregação**: O requisito originou-se do brainstorming.<br> **Satisfação**: O caso de uso satisfaz o requisito ao descrever notificações por localização.<br>**Recurso**: O cenário detalha recursos de geolocalização e notificações.<br>**Satisfação**: A história de usuário satisfaz o requisito de notificações personalizadas.<br>**Representação**: O léxico representa conceitos de localização e notificações.<br>**Agregação**: O requisito está relacionado ao Épico 07.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou  responsável pela elaboração e validação do requisito.|
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 04

<font size="3"><p style="text-align: center">Tabela 7: Cartão do Requisito Funcional 04 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder consultar agendamentos e serviços em um único local centralizado          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR04</a> , RF04, [UC04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US36](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us36), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de centralização de serviços.<br>**Recurso**: O cenário detalha recursos para consulta centralizada.<br>**Satisfação**: A história de usuário satisfaz o requisito de acesso unificado.<br>**Representação**: O léxico representa conceitos de agendamento e centralização.<br>**Agregação**: O requisito está relacionado ao Épico 04.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 05

<font size="3"><p style="text-align: center">Tabela 8: Cartão do Requisito Funcional 05 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve ter acesso a um assistente virtual com acessibilidade por voz         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR05</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD05</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT13</a>, RF05, [UC05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US37](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us37), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de assistente virtual.<br>**Recurso**: O cenário detalha recursos de voz e assistência virtual.<br>**Satisfação**: A história de usuário satisfaz o requisito de acessibilidade por voz.<br>**Representação**: O léxico representa conceitos de assistente virtual e comandos de voz.<br>**Agregação**: O requisito está relacionado ao Épico 03.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 06

<font size="3"><p style="text-align: center">Tabela 9: Cartão do Requisito Funcional 06 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR06</a> , RF06, [UC06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US38](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us38), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de tutoriais.<br>**Recurso**:  O cenário detalha recursos educacionais do app.<br>**Satisfação**:  A história de usuário satisfaz o requisito de guias passo a passo.<br>**Representação**: O léxico representa conceitos de tutorial e ajuda.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 07

<font size="3"><p style="text-align: center">Tabela 10: Cartão do Requisito Funcional 07 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder alterar o tamanho da fonte e o contraste de cores             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR07</a>, <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD08</a>, RF07, [UC07](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN07](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us15), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de personalização visual.<br>**Recurso**:  O cenário detalha recursos de acessibilidade visual.<br>**Satisfação**:  A história de usuário satisfaz o requisito de ajustes visuais.<br>**Representação**: O léxico representa conceitos de fonte e contraste.<br>**Agregação**: O requisito está relacionado ao Épico 03.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab) 2025)</p></font>


### ELO 08

<font size="3"><p style="text-align: center">Tabela 11: Cartão do Requisito Funcional 08 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |O aplicativo deve permitir modo escuro          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR08</a>, RF08, [UC08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us16), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |**Satisfação**: O caso de uso satisfaz o requisito de modo escuro.<br>**Recurso**:  O cenário detalha recursos de tema escuro.<br>**Satisfação**:  A história de usuário satisfaz o requisito de personalização de tema.<br>**Representação**:  O léxico representa conceitos de modo escuro.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab) 2025)</p></font>


### ELO 09

<font size="3"><p style="text-align: center">Tabela 12: Cartão do Requisito Funcional 09 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |	O usuário deve poder acessar e visualizar notícias relevantes            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR10</a>, RF09, [US32](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us32) e  [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de informações relevantes.<br>**Agregação**: O requisito está relacionado ao Épico  05.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito.|
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 10

<font size="3"><p style="text-align: center">Tabela 13: Cartão do Requisito Funcional 10 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentosr realizar login de forma simples e rápida             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |   <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR11</a> , RF10, [UC09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us17), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de geração de relatórios.<br>**Recurso**: O cenário detalha recursos de comprovantes.<br>**Satisfação**: A história de usuário satisfaz o requisito de documentação.<br>**Representação**: O léxico representa conceitos de relatório e comprovante.<br>**Agregação**: O requisito está relacionado ao Épico  08. <br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab) 2025)</p></font>


### ELO 11

<font size="3"><p style="text-align: center">Tabela 14: Cartão do Requisito Funcional 11 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR12</a> , RF11,  [US39](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us39) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de serviços integrados.<br>**Agregação**: O requisito está relacionado ao Eṕico 04.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              |Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 12

<font size="3"><p style="text-align: center">Tabela 15: Cartão do Requisito Funcional 12 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder alterar o idioma do aplicativo          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR13</a>, RF12, [UC10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us08), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |  **Satisfação**: O caso de uso satisfaz o requisito de mudança de idioma.<br>**Recurso**:  O cenário detalha recursos de internacionalização.<br>**Satisfação**:  A história de usuário satisfaz o requisito de múltiplos idiomas.<br>**Representação**:  O léxico representa conceitos de idioma e tradução.<br>**Agregação**: O requisito está relacionado ao Épico 02. <br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 13

<font size="3"><p style="text-align: center">Tabela 16: Cartão do Requisito Funcional 13 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |   <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR14</a>, RF13, [UC11](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN11](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us09), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de personalização de perfil.<br>**Recurso**: O cenário detalha recursos de preferências personalizadas.<br>**Satisfação**:  A história de usuário satisfaz o requisito de recomendações.<br>**Representação**:  O léxico representa conceitos de perfil e preferências.<br>**Agregação**: O requisito está relacionado ao Épico 02. <br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 14

<font size="3"><p style="text-align: center">Tabela 17: Cartão do Requisito Funcional 14 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR15</a>, RF14, [UC12](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN12](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us10), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de lembretes.<br>**Recurso**:  O cenário detalha recursos de notificações de vencimento.<br>**Satisfação**:  A história de usuário satisfaz o requisito de alertas.<br>**Representação**: O léxico representa conceitos de lembrete e notificação.<br>**Agregação**: O requisito está relacionado ao Épico 07.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>


### ELO 15

<font size="3"><p style="text-align: center">Tabela 18: Cartão do Requisito Funcional 16 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar um menu com as principais funções logo na tela inicial           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR16</a>, RF15, [US33](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us33) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: RF15 - [US33](./historia-de-usuario.md): A história de usuário satisfaz o requisito de acesso rápido.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF15: Responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 16

<font size="3"><p style="text-align: center">Tabela 19: Cartão do Requisito Funcional 16 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR17</a> , RF16, [UC15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US22](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us22), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de gestão de agendamentos.<br>**Recurso**:  O cenário detalha recursos de reagendamento.<br>**Satisfação**: A história de usuário satisfaz o requisito de centralização.<br>**Representação**: O léxico representa conceitos de agendamento.<br>**Agregação**: O requisito está relacionado ao Épico 06.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 17

<font size="3"><p style="text-align: center">Tabela 20: Cartão do Requisito Funcional 17 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte        |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR19</a>, RF07, [UC14](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN14](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US48](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us48), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |  **Satisfação**: O caso de uso satisfaz o requisito de categorização.<br>**Recurso**: O cenário detalha recursos de notificações categorizadas.<br>**Satisfação**: A história de usuário satisfaz o requisito de filtros.<br>**Representação**: O léxico representa conceitos de categorias.<br>**Agregação**: O requisito está relacionado ao Épico 07. <br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 18

<font size="3"><p style="text-align: center">Tabela 21: Cartão do Requisito Funcional 18 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR20</a>, RF18, [UC18](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN18](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us02), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de compartilhamento.<br>**Recurso**: O cenário detalha recursos de salvamento e compartilhamento.<br>**Satisfação**: A história de usuário satisfaz o requisito de exportação.<br>**Representação**: O léxico representa conceitos de protocolo e compartilhamento.<br>**Agregação**: O requisito está relacionado ao Épico 08.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 19

<font size="3"><p style="text-align: center">Tabela 22: Cartão do Requisito Funcional 19 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN01</a>, RF19, [US18](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us18) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de rastreamento em tempo real.<br>**Recurso**: O cenário detalha recursos de localização e mapas.<br>**Satisfação**: A história de usuário satisfaz o requisito de transporte público.<br>**Representação**: O léxico representa conceitos de transporte e GPS.<br>**Agregação**: O requisito está relacionado ao Épico 10.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 20

<font size="3"><p style="text-align: center">Tabela 23: Cartão do Requisito Funcional 20 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo fornece links para serviços externos (como Secretaria da Fazenda) de forma eficiente, com explicações claras sobre o que o usuário encontrará após clicar.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN02</a>, RF20,[US34](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us34) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de clareza nas explicações.<br>**Agregação**: O requisito está relacionado ao Épico 04.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### ELO 21

<font size="3"><p style="text-align: center">Tabela 24: Cartão do Requisito Funcional 21 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN03</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT07</a>, RF21,[US40](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us40) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz parcialmente o requisito de informações educacionais.<br>**Agregação**: O requisito está relacionado ao Épico 05.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 22

<font size="3"><p style="text-align: center">Tabela 25: Cartão do Requisito Funcional 22 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial.           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a> , RF22, [UC17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us01), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | ***Satisfação**: O caso de uso satisfaz o requisito de autenticação segura.<br>**Recurso**: O cenário detalha recursos de autenticação gov.br.<br>**Satisfação**: A história de usuário satisfaz o requisito de login seguro.<br>**Representação**: O léxico representa conceitos de autenticação e segurança.<br>**Agregação**: O requisito está relacionado ao Épico 01.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 23

<font size="3"><p style="text-align: center">Tabela 26: Cartão do Requisito Funcional 23 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN05</a>, RF23,  [US19](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us19) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de clareza fiscal.<br>**Agregação**:O requisito está relacionado ao Épico 04. <br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### ELO 24

<font size="3"><p style="text-align: center">Tabela 27: Cartão do Requisito Funcional 24 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos.            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN06</a>, RF24, [UC13](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN13](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US46](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us46), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |**Satisfação**:  O caso de uso satisfaz o requisito de acompanhamento educacional.<br>**Recurso**: O cenário detalha recursos de pendências escolares.<br>**Satisfação**: A história de usuário satisfaz o requisito de gestão educacional.<br>**Agregação**: O requisito está relacionado ao Épico 04. <br>**Representação**: O léxico representa conceitos de educação e pendências.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


### ELO 25

<font size="3"><p style="text-align: center">Tabela 28: Cartão do Requisito Funcional 25 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve permitir que usuários reportem problemas da cidade através de um mapa interativo.             |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN09</a>, RF25, [UC16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US23](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us23), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de reporte interativo.<br>**Recurso**: O cenário detalha recursos de mapa interativo.<br>**Satisfação**: A história de usuário satisfaz o requisito de reporte geolocalizado.<br>**Representação**: O léxico representa conceitos de mapa e reporte.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 26

<font size="3"><p style="text-align: center">Tabela 29: Cartão do Requisito Funcional 26 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve fornecer acesso a números de serviços de emergência da polícia.            |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN10</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT05</a> , RF26, [US24](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us24) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de segurança pública.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito.  |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 27

<font size="3"><p style="text-align: center">Tabela 30: Cartão do Requisito Funcional 27 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso.        |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |   <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN11</a>, RF27, [UC19](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN19](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us03), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de suporte.<br>**Recurso**: O cenário detalha recursos de ajuda.<br>**Satisfação**: A história de usuário satisfaz o requisito de instruções.<br>**Representação**: O léxico representa conceitos de suporte e ajuda.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 28

<font size="3"><p style="text-align: center">Tabela 31: Cartão do Requisito Funcional 28 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos.         |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD02</a>, RF28, [US01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us01) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de solicitações.<br>**Agregação**: O requisito está relacionado ao Épico 09.  <br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 29

<font size="3"><p style="text-align: center">Tabela 32: Cartão do Requisito Funcional 29 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacaotec_elicitacao/analise_documentos/#anchor_AD">AD03</a>, RF29,[US26](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us26) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de visualização espacial.<br>**Agregação**: O requisito está relacionado ao Epico 09. <br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### ELO 30

<font size="3"><p style="text-align: center">Tabela 33: Cartão do Requisito Funcional 30 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.           |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD04</a>, RF30, [US04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us04) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de monitoramento.<br>**Agregação**: O requisito está relacionado ao Épico 06.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 31

<font size="3"><p style="text-align: center">Tabela 34: Cartão do Requisito Funcional 31 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O sistema deve permitir que o usuário confirme a resolução de problemas relatados.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD06</a>, RF31, [US05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us05) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de feedback.<br>**Agregação**: O requisito está relacionado ao Épico 06.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 32

<font size="3"><p style="text-align: center">Tabela 35: Cartão do Requisito Funcional 32 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |    <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD07</a> , RF32, [US06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us06) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de controle de dados.<br>**Agregação**: O requisito está relacionado ao Épico  11.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) ficou responsável pela elaboração e validação do requisito. |
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Luiza Silva](https://github.com/Luizaxx), 2025)</p></font>


### ELO 33

<font size="3"><p style="text-align: center">Tabela 36: Cartão do Requisito Funcional 33 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação.          |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT01</a>, RF33, [US41](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us41) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: A história de usuário satisfaz o requisito de reporte urbano.<br>**Agregação**: O requisito está relacionado ao Épico  09.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito.|
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>


### ELO 34

<font size="3"><p style="text-align: center">Tabela 37: Cartão do Requisito Funcional 34 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes.       |
| Categoria           | Desenvolvimento                                                          |
| Elementos Rastreáveis           |  <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT02</a>, RF34, [US20](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us20) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/)                                      |
Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de organização.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              |Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

# Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação n° 20/05. Departamento de Informática, PUC-Rio, 2005.


# Histórico de Versões

| Versão | Descrição                                                                                          | Autor(es)                                             | Data       | Revisor(es)                                        | Data de revisão |
| ------ | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ---------- | -------------------------------------------------- | --------------- 
| 1.0    | Adicionando introdução e metologia do forward-from | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |
| 1.1   | Adição das tabelas 2 até 35, referentes aos cartões do forward-from dos requisitos 1 ao 34 | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |
| 1.2   | Ajustando autores das tabelas | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |