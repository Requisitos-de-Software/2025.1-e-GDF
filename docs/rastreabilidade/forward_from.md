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

## Identificação e Categorização dos Artefatos

Os artefatos envolvidos no processo de desenvolvimento devem ser previamente identificados e documentados. Exemplos incluem:

* **Casos de Uso**  
* **Cenários**
* **Histórias de Usuário**
* **Léxicos**
* **Especificação Suplementar**
* **NFR Framework**

A rastreabilidade será estabelecida entre pares de artefatos por meio de elos classificados conforme o tipo de relação.

## Tipos de Elos de Rastreabilidade

A metodologia considera os seguintes tipos de elos:

- **Satisfação**: a origem depende da realização do destino (ex.: requisito satisfeito por caso de uso).
- **Recurso**: a origem depende de um recurso fornecido pelo destino (ex.: Sprint depende do backlog do produto).
- **Responsabilidade**: relaciona atores humanos aos artefatos nos quais atuam (ex.: desenvolvedor responsável por requisito).
- **Representação**: o destino representa ou modela o conteúdo da origem (ex.: diagrama que representa requisitos).
- **Alocado**: a origem está alocada a um módulo ou subsistema.
- **Agregação**: o destino é uma composição de elementos da origem.

## Registro dos Elos

Cada elo deve conter os seguintes elementos:

<font size="3"><p style="text-align: center">Tabela X: Modelo de Cartão de Rastreabilidade (Forward-from)</p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | [Inserir descrição do requisito funcional ou não funcional]               |
| Categoria           | Desenvolvimento                                                          |
| Elementos           | [Inserir links para artefatos relacionados, como requisitos, casos de uso, cenários, léxicos, etc.]<br>Exemplo: [RFXX](#), [ISXX](#), [Cenário XX](#), [UCXX](#), [LXX](#) |
| Elos Forward-from   | [Inserir os elos de rastreabilidade com tipo e destino] <br> Exemplo: <br> Satisfação – [Destino]<br> Recurso – [Destino]<br>  Responsabilidade – [Destino] <br> Agregação – [Destino] <br>|
| Status              | Implementado / Não implementado                                           |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

# Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação n° 20/05. Departamento de Informática, PUC-Rio, 2005.

## Cartões de Requisitos Funcionais

### RF01

<font size="3"><p style="text-align: center">Tabela 2: Cartão do Requisito Funcional 01 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve conseguir realizar login de forma simples e rápida             |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR01</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD01</a>, RF01, [UC01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN01](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US29](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us29), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito ao descrever o processo de login.<br>**Recurso**: O cenário detalha os recursos necessários para login simples e rápido.<br>**Satisfação**: A história de usuário satisfaz o requisito ao especificar a necessidade de login simplificado.<br>**Representação**: O léxico representa os termos e conceitos relacionados ao login.<br>**Agregação**:  O requisito é classificado no Épico 01.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito.|
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### RF02

<font size="3"><p style="text-align: center">Tabela 3: Cartão do Requisito Funcional 02 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia        |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR02</a> , RF02, [UC02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN02](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US30](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us30), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito ao descrever funcionalidades acessíveis.<br>**Recurso**: O cenário detalha recursos para usuários com pouca familiaridade tecnológica.<br>**Satisfação**:  A história de usuário satisfaz o requisito ao especificar interface intuitiva.<br>**Representação**: O léxico representa termos simplificados para acessibilidade.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### RF03

<font size="3"><p style="text-align: center">Tabela 4: Cartão do Requisito Funcional 03 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder receber notificações personalizadas com base em sua localização           |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR03</a>, RF03, [UC03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN03](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US31](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us31), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Agregação**: O requisito originou-se do brainstorming.<br> **Satisfação**: O caso de uso satisfaz o requisito ao descrever notificações por localização.<br>**Recurso**: O cenário detalha recursos de geolocalização e notificações.<br>**Satisfação**: A história de usuário satisfaz o requisito de notificações personalizadas.<br>**Representação**: O léxico representa conceitos de localização e notificações.<br>**Agregação**: O requisito está relacionado ao Épico 07.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou  responsável pela elaboração e validação do requisito.|
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF04

<font size="3"><p style="text-align: center">Tabela 5: Cartão do Requisito Funcional 04 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder consultar agendamentos e serviços em um único local centralizado          |
| Categoria           | Desenvolvimento                                                          |
| Elementos           | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR04</a> , RF04, [UC04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN04](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US36](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us36), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de centralização de serviços.<br>**Recurso**: O cenário detalha recursos para consulta centralizada.<br>**Satisfação**: A história de usuário satisfaz o requisito de acesso unificado.<br>**Representação**: O léxico representa conceitos de agendamento e centralização.<br>**Agregação**: O requisito está relacionado ao Épico 04.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF05

<font size="3"><p style="text-align: center">Tabela 6: Cartão do Requisito Funcional 05 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve ter acesso a um assistente virtual com acessibilidade por voz         |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR05</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD05</a>, <a href="../../elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT13</a>, RF05, [UC05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN05](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US37](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us37), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de assistente virtual.<br>**Recurso**: O cenário detalha recursos de voz e assistência virtual.<br>**Satisfação**: A história de usuário satisfaz o requisito de acessibilidade por voz.<br>**Representação**: O léxico representa conceitos de assistente virtual e comandos de voz.<br>**Agregação**: O requisito está relacionado ao Épico 03.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF06

<font size="3"><p style="text-align: center">Tabela 7: Cartão do Requisito Funcional 06 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app         |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR06</a> , RF06, [UC06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN06](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US38](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us38), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de tutoriais.<br>**Recurso**:  O cenário detalha recursos educacionais do app.<br>**Satisfação**:  A história de usuário satisfaz o requisito de guias passo a passo.<br>**Representação**: O léxico representa conceitos de tutorial e ajuda.<br>**Agregação**: O requisito está relacionado ao Épico 09.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF07

<font size="3"><p style="text-align: center">Tabela 8: Cartão do Requisito Funcional 07 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder alterar o tamanho da fonte e o contraste de cores             |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR07</a>, <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>, <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD08</a>, RF07, [UC07](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN07](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US15](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us15), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  O caso de uso satisfaz o requisito de personalização visual.<br>**Recurso**:  O cenário detalha recursos de acessibilidade visual.<br>**Satisfação**:  A história de usuário satisfaz o requisito de ajustes visuais.<br>**Representação**: O léxico representa conceitos de fonte e contraste.<br>**Agregação**: O requisito está relacionado ao Épico 03.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF08

<font size="3"><p style="text-align: center">Tabela 9: Cartão do Requisito Funcional 08 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |O aplicativo deve permitir modo escuro          |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR08</a>, RF08, [UC08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US16](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us16), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |**Satisfação**: O caso de uso satisfaz o requisito de modo escuro.<br>**Recurso**:  O cenário detalha recursos de tema escuro.<br>**Satisfação**:  A história de usuário satisfaz o requisito de personalização de tema.<br>**Representação**:  O léxico representa conceitos de modo escuro.<br>**Agregação**: O requisito está relacionado ao Épico 02.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF09

<font size="3"><p style="text-align: center">Tabela 10: Cartão do Requisito Funcional 09 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |	O usuário deve poder acessar e visualizar notícias relevantes            |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR10</a>, RF09, [US32](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us32) e  [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de informações relevantes.<br>**Agregação**: O requisito está relacionado ao Épico  05.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) ficou responsável pela elaboração e validação do requisito.|
| Status              | Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF10

<font size="3"><p style="text-align: center">Tabela 11: Cartão do Requisito Funcional 10 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | 	O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentosr realizar login de forma simples e rápida             |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |   <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR11</a> , RF10, [UC09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US17](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us17), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de geração de relatórios.<br>**Recurso**: O cenário detalha recursos de comprovantes.<br>**Satisfação**: A história de usuário satisfaz o requisito de documentação.<br>**Representação**: O léxico representa conceitos de relatório e comprovante.<br>**Agregação**: O requisito está relacionado ao Épico  08. <br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF11

<font size="3"><p style="text-align: center">Tabela 12: Cartão do Requisito Funcional 11 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito |O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade         |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR12</a> , RF11,  [US39](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us39) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**:  A história de usuário satisfaz o requisito de serviços integrados.<br>**Agregação**: O requisito está relacionado ao Eṕico 04.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) ficou responsável pela elaboração e validação do requisito. |
| Status              |Implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF12

<font size="3"><p style="text-align: center">Tabela 13: Cartão do Requisito Funcional 12 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder alterar o idioma do aplicativo          |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |  <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR13</a>, RF12, [UC10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN10](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US08](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us08), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   |  **Satisfação**: O caso de uso satisfaz o requisito de mudança de idioma.<br>**Recurso**:  O cenário detalha recursos de internacionalização.<br>**Satisfação**:  A história de usuário satisfaz o requisito de múltiplos idiomas.<br>**Representação**:  O léxico representa conceitos de idioma e tradução.<br>**Agregação**: O requisito está relacionado ao Épico 02. <br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>


### RF13

<font size="3"><p style="text-align: center">Tabela 14: Cartão do Requisito Funcional 13 </p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços          |
| Categoria           | Desenvolvimento                                                          |
| Elementos           |   <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR14</a>, RF13, [UC11](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/casos_de_uso/), [CEN11](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/cenario/), [US09](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/historia-de-usuario/#us09), [LEX](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/lexico/) e [Backlog](https://requisitos-de-software.github.io/2025.1-e-GDF/modelagem/agil/backlog/) |
| Elos Forward-from   | **Satisfação**: O caso de uso satisfaz o requisito de personalização de perfil.<br>**Recurso**: O cenário detalha recursos de preferências personalizadas.<br>**Satisfação**:  A história de usuário satisfaz o requisito de recomendações.<br>**Representação**:  O léxico representa conceitos de perfil e preferências.<br>**Agregação**: O requisito está relacionado ao Épico 02. <br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) ficou responsável pela elaboração e validação do requisito. |
| Status              | Não implementado                                           |

<font size="3"><p style="text-align: center"> Elaborado pelo(a) autor(a): ([Ana Victória](https://github.com/navicg), 2025)</p></font>

# Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação n° 20/05. Departamento de Informática, PUC-Rio, 2005.


# Histórico de Versões

| Versão | Descrição                                                                                          | Autor(es)                                             | Data       | Revisor(es)                                        | Data de revisão |
| ------ | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ---------- | -------------------------------------------------- | --------------- 
| 1.0    | Adicionando introdução e metologia do forward-from | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |