# Elos

## Introdução
Os elos de rastreabilidade são conexões essenciais que estabelecem vínculos entre diferentes artefatos e atividades ao longo do ciclo de vida de um projeto ou sistema. Esses elos permitem rastrear a origem e a evolução de funcionalidades, decisões de projeto e mudanças, garantindo um gerenciamento eficaz e uma qualidade consistente. Utilizando a rastreabilidade, é possível identificar a proveniência de cada funcionalidade do sistema, assegurar que todos os requisitos foram devidamente testados e validados, registrar decisões críticas para o projeto e gerenciar os riscos de maneira eficiente. Além disso, a rastreabilidade facilita o controle de mudanças ao indicar quais artefatos são impactados por alterações específicas, promovendo uma gestão integrada e transparente do desenvolvimento e manutenção de sistemas.<a id="RP1" href="#TEC1">[1]</a> 

### Backward-from

A rastreabilidade backward-from é um processo crítico na engenharia de requisitos, que permite a ligação dos requisitos às suas fontes originais. Esse tipo de rastreabilidade é essencial para garantir que todos os requisitos identificados tenham uma origem bem definida, facilitando a validação e verificação durante o ciclo de vida do desenvolvimento do software. Além disso, a rastreabilidade backward-from ajuda a gerenciar mudanças ao rastrear de volta cada requisito até suas bases, assegurando que qualquer modificação no sistema possa ser rapidamente associada à sua origem, permitindo uma resposta eficaz a alterações e garantindo a conformidade com os requisitos iniciais do projeto.<a id="RP1" href="#TEC1">[1]</a> 

### Forward-from

A rastreabilidade forward-from é um componente essencial na engenharia de requisitos, que possibilita a ligação dos requisitos aos artefatos subsequentes, como design, código, testes e documentação. Esse tipo de rastreabilidade é crucial para assegurar que todos os requisitos sejam devidamente implementados e testados ao longo do ciclo de vida do desenvolvimento do software. Além disso, a rastreabilidade forward-to facilita a gestão de mudanças, permitindo que qualquer alteração nos requisitos seja refletida de maneira consistente em todos os artefatos afetados. Isso garante que as modificações sejam corretamente incorporadas e verificadas, mantendo a integridade e a conformidade do sistema em relação aos requisitos definidos inicialmente. <a id="RP2" href="#TEC2">[2]</a>

## Metodologia
Utilizamos um cartão baseado nos cartões presentes nos slides dos Professores Milene Serrano e Maurício Serrano na página 22 à 27<a id="RP3" href="#TEC3">[3]</a>, as categorias e tipos de elos derivam do Meta-modelo de Toranzo. Os cartões que fizemos utilizam o mesmo formato, porém fizemos baseados nos requisitos onde cada cartão possui todos os tipos de Elos daquele requisito citado.

### Cartões de Relacionamento dos Elos

<div align="center">
  <strong>Tabela 1 -</strong> Exemplo de cartão
</div>

<div align="center">
  <table>
    <tr>
      <td><strong>Categoria:</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos:</strong></td>
      <td>RE01, UC01, CE01, ENT01</td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from:</strong></td>
      <td>Agregação: RE01 - ENT01: O requisito originou-se da entrevista.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from:</strong></td>
      <td>
        Satisfação: RE01 - CS01: O requisito deu origem ao caso de uso.<br>
        Satisfação: RE01 - CE01: O requisito deu origem ao cenário.
      </td>
    </tr>
  </table>
</div>

<font size="3"><p style="text-align: center">Autores: [Gabriel Lopes](https://github.com/BrzGab).</p></font>

Legenda:

- **Categoria**: Devem ser classificadas em quatro níveis
    - **Ambiental**: Congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido.
    - **Organizacional**: Reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema.
    - **Gerencial**: Agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto.
    - **Desenvolvimento**: Abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...).
- **Elementos**: Lista de identificadores que representam [requisitos](../../elicitacao/requisitosElicitados) (RE01), [casos de uso](../../modelagem/useCase) (US01), [cenários](../../modelagem/cenarios) (CEN01) e [técnicas de elicitação de requisitos](../../elicitacao/brainStorm) (ENT01).
- **Elos Backward-from**: Primeiro, mostra-se o tipo de elo e depois a origem do requisito. Por exemplo, o requisito REQ01 originou-se da entrevista ENT01.
- **Elos Forward-from**: Primeiro, mostra-se o tipo de elo e como o requisito é satisfeito ou relacionado a outros elementos. Por exemplo, o requisito RE01 deu origem ao caso de uso CS01 e ao cenário CE01.
- **Tipos de Elos**:
    - **Satisfação**: Indica que a classe de origem tem dependência de satisfação com a classe de destino.
    - **Recurso**: Indica que a classe de origem tem dependência de recurso com a classe de destino.
    - **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre artefatos.
    - **Representação**: Captura a representação ou modelagem dos requisitos em outras linguagens.
    - **Alocado**: Classe de origem está relacionada à classe de destino, que representa um subsistema.
    - **Agregação**: Indica composição de elementos.

## Cartões de Requisitos Funcionais

### RF01

<div align="center">
  <strong>Tabela 2 -</strong> Cartão do Requisito RF01
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF01, [BR01](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US29](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve conseguir realizar login de forma simples e rápida |
| **Elos Backward-from:**  | **Agregação**: RF01 - [BR01](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se do brainstorming e da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF01 - UC: O caso de uso satisfaz o requisito ao descrever o processo de login.<br>**Recurso**: RF01 - C: O cenário detalha os recursos necessários para login simples e rápido.<br>**Satisfação**: RF01 - [US29](./historia-de-usuario.md): A história de usuário satisfaz o requisito ao especificar a necessidade de login simplificado.<br>**Representação**: RF01 - L: O léxico representa os termos e conceitos relacionados ao login.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF01: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/navicg">Ana Victória</a>, 2025.</p>

### RF02

<div align="center">
  <strong>Tabela 3 -</strong> Cartão do Requisito RF02
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF02, [BR02](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US30](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia |
| **Elos Backward-from:**  | **Agregação**: RF02 - [BR02](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF02 - UC: O caso de uso satisfaz o requisito ao descrever funcionalidades acessíveis.<br>**Recurso**: RF02 - C: O cenário detalha recursos para usuários com pouca familiaridade tecnológica.<br>**Satisfação**: RF02 - [US30](./historia-de-usuario.md): A história de usuário satisfaz o requisito ao especificar interface intuitiva.<br>**Representação**: RF02 - L: O léxico representa termos simplificados para acessibilidade.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF02: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/navicg">Ana Victória</a>, 2025.</p>

### RF03

<div align="center">
  <strong>Tabela 4 -</strong> Cartão do Requisito RF03
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF03, [BR03](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US31](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder receber notificações personalizadas com base em sua localização |
| **Elos Backward-from:**  | **Agregação**: RF03 - [BR03](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF03 - UC: O caso de uso satisfaz o requisito ao descrever notificações por localização.<br>**Recurso**: RF03 - C: O cenário detalha recursos de geolocalização e notificações.<br>**Satisfação**: RF03 - [US31](./historia-de-usuario.md): A história de usuário satisfaz o requisito de notificações personalizadas.<br>**Representação**: RF03 - L: O léxico representa conceitos de localização e notificações.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF03: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/navicg">Ana Victória</a>, 2025.</p>

### RF04

<div align="center">
  <strong>Tabela 5 -</strong> Cartão do Requisito RF04
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF04, [BR04](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US36](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder consultar agendamentos e serviços em um único local centralizado |
| **Elos Backward-from:**  | **Agregação**: RF04 - [BR04](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF04 - UC: O caso de uso satisfaz o requisito de centralização de serviços.<br>**Recurso**: RF04 - C: O cenário detalha recursos para consulta centralizada.<br>**Satisfação**: RF04 - [US36](./historia-de-usuario.md): A história de usuário satisfaz o requisito de acesso unificado.<br>**Representação**: RF04 - L: O léxico representa conceitos de agendamento e centralização.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) - RF04: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF05

<div align="center">
  <strong>Tabela 6 -</strong> Cartão do Requisito RF05
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF05, [BR05](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US37](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve ter acesso a um assistente virtual com acessibilidade por voz |
| **Elos Backward-from:**  | **Agregação**: RF05 - [BR05](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se do brainstorming, análise de documentos e introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF05 - UC: O caso de uso satisfaz o requisito de assistente virtual.<br>**Recurso**: RF05 - C: O cenário detalha recursos de voz e assistência virtual.<br>**Satisfação**: RF05 - [US37](./historia-de-usuario.md): A história de usuário satisfaz o requisito de acessibilidade por voz.<br>**Representação**: RF05 - L: O léxico representa conceitos de assistente virtual e comandos de voz.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) - RF05: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF06

<div align="center">
  <strong>Tabela 7 -</strong> Cartão do Requisito RF06
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF06, [BR06](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US38](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app |
| **Elos Backward-from:**  | **Agregação**: RF06 - [BR06](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF06 - UC: O caso de uso satisfaz o requisito de tutoriais.<br>**Recurso**: RF06 - C: O cenário detalha recursos educacionais do app.<br>**Satisfação**: RF06 - [US38](./historia-de-usuario.md): A história de usuário satisfaz o requisito de guias passo a passo.<br>**Representação**: RF06 - L: O léxico representa conceitos de tutorial e ajuda.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) - RF06: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF07

<div align="center">
  <strong>Tabela 8 -</strong> Cartão do Requisito RF07
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF07, [BR07](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US15](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder alterar o tamanho da fonte e o contraste de cores |
| **Elos Backward-from:**  | **Agregação**: RF07 - [BR07](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se do brainstorming, entrevista e análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF07 - UC: O caso de uso satisfaz o requisito de personalização visual.<br>**Recurso**: RF07 - C: O cenário detalha recursos de acessibilidade visual.<br>**Satisfação**: RF07 - [US15](./historia-de-usuario.md): A história de usuário satisfaz o requisito de ajustes visuais.<br>**Representação**: RF07 - L: O léxico representa conceitos de fonte e contraste.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) - RF07: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF08

<div align="center">
  <strong>Tabela 9 -</strong> Cartão do Requisito RF08
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF08, [BR08](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US16](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve permitir modo escuro |
| **Elos Backward-from:**  | **Agregação**: RF08 - [BR08](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF08 - UC: O caso de uso satisfaz o requisito de modo escuro.<br>**Recurso**: RF08 - C: O cenário detalha recursos de tema escuro.<br>**Satisfação**: RF08 - [US16](./historia-de-usuario.md): A história de usuário satisfaz o requisito de personalização de tema.<br>**Representação**: RF08 - L: O léxico representa conceitos de modo escuro.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) - RF08: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF09

<div align="center">
  <strong>Tabela 10 -</strong> Cartão do Requisito RF09
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF09, [BR10](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US32](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder acessar e visualizar notícias relevantes |
| **Elos Backward-from:**  | **Agregação**: RF09 - [BR10](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF09 - UC: O caso de uso satisfaz o requisito de acesso a notícias.<br>**Recurso**: RF09 - C: O cenário detalha recursos de feed de notícias.<br>**Satisfação**: RF09 - [US32](./historia-de-usuario.md): A história de usuário satisfaz o requisito de informações relevantes.<br>**Representação**: RF09 - L: O léxico representa conceitos de notícias e feed.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF09: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/navicg">Ana Victória</a>, 2025.</p>

### RF10

<div align="center">
  <strong>Tabela 11 -</strong> Cartão do Requisito RF10
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF10, [BR11](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US17](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos |
| **Elos Backward-from:**  | **Agregação**: RF10 - [BR11](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF10 - UC: O caso de uso satisfaz o requisito de geração de relatórios.<br>**Recurso**: RF10 - C: O cenário detalha recursos de comprovantes.<br>**Satisfação**: RF10 - [US17](./historia-de-usuario.md): A história de usuário satisfaz o requisito de documentação.<br>**Representação**: RF10 - L: O léxico representa conceitos de relatório e comprovante.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) - RF10: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF11

<div align="center">
  <strong>Tabela 12 -</strong> Cartão do Requisito RF11
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF11, [BR12](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US39](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade |
| **Elos Backward-from:**  | **Agregação**: RF11 - [BR12](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF11 - UC: O caso de uso satisfaz o requisito de integração de serviços.<br>**Recurso**: RF11 - C: O cenário detalha recursos de integração.<br>**Satisfação**: RF11 - [US39](./historia-de-usuario.md): A história de usuário satisfaz o requisito de serviços integrados.<br>**Representação**: RF11 - L: O léxico representa conceitos de integração e serviços públicos.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) - RF11: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF12

<div align="center">
  <strong>Tabela 13 -</strong> Cartão do Requisito RF12
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF12, [BR13](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US08](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder alterar o idioma do aplicativo |
| **Elos Backward-from:**  | **Agregação**: RF12 - [BR13](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF12 - UC: O caso de uso satisfaz o requisito de mudança de idioma.<br>**Recurso**: RF12 - C: O cenário detalha recursos de internacionalização.<br>**Satisfação**: RF12 - [US08](./historia-de-usuario.md): A história de usuário satisfaz o requisito de múltiplos idiomas.<br>**Representação**: RF12 - L: O léxico representa conceitos de idioma e tradução.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RF12: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF13

<div align="center">
  <strong>Tabela 14 -</strong> Cartão do Requisito RF13
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF13, [BR14](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US09](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços |
| **Elos Backward-from:**  | **Agregação**: RF13 - [BR14](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF13 - UC: O caso de uso satisfaz o requisito de personalização de perfil.<br>**Recurso**: RF13 - C: O cenário detalha recursos de preferências personalizadas.<br>**Satisfação**: RF13 - [US09](./historia-de-usuario.md): A história de usuário satisfaz o requisito de recomendações.<br>**Representação**: RF13 - L: O léxico representa conceitos de perfil e preferências.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RF13: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF14

<div align="center">
  <strong>Tabela 15 -</strong> Cartão do Requisito RF14
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF14, [BR15](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US10](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes |
| **Elos Backward-from:**  | **Agregação**: RF14 - [BR15](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF14 - UC: O caso de uso satisfaz o requisito de lembretes.<br>**Recurso**: RF14 - C: O cenário detalha recursos de notificações de vencimento.<br>**Satisfação**: RF14 - [US10](./historia-de-usuario.md): A história de usuário satisfaz o requisito de alertas.<br>**Representação**: RF14 - L: O léxico representa conceitos de lembrete e notificação.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RF14: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF15

<div align="center">
  <strong>Tabela 16 -</strong> Cartão do Requisito RF15
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF15, [BR16](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US33](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder acessar um menu com as principais funções logo na tela inicial |
| **Elos Backward-from:**  | **Agregação**: RF15 - [BR16](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF15 - UC: O caso de uso satisfaz o requisito de menu principal.<br>**Recurso**: RF15 - C: O cenário detalha recursos da tela inicial.<br>**Satisfação**: RF15 - [US33](./historia-de-usuario.md): A história de usuário satisfaz o requisito de acesso rápido.<br>**Representação**: RF15 - L: O léxico representa conceitos de menu e navegação.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF15: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/navicg">Ana Victória</a>, 2025.</p>

### RF16

<div align="center">
  <strong>Tabela 17 -</strong> Cartão do Requisito RF16
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF16, [BR17](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US22](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada |
| **Elos Backward-from:**  | **Agregação**: RF16 - [BR17](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF16 - UC: O caso de uso satisfaz o requisito de gestão de agendamentos.<br>**Recurso**: RF16 - C: O cenário detalha recursos de reagendamento.<br>**Satisfação**: RF16 - [US22](./historia-de-usuario.md): A história de usuário satisfaz o requisito de centralização.<br>**Representação**: RF16 - L: O léxico representa conceitos de agendamento.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) - RF16: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF17

<div align="center">
  <strong>Tabela 18 -</strong> Cartão do Requisito RF17
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF17, [BR19](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US48](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte |
| **Elos Backward-from:**  | **Agregação**: RF17 - [BR19](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF17 - UC: O caso de uso satisfaz o requisito de categorização.<br>**Recurso**: RF17 - C: O cenário detalha recursos de notificações categorizadas.<br>**Satisfação**: RF17 - [US48](./historia-de-usuario.md): A história de usuário satisfaz o requisito de filtros.<br>**Representação**: RF17 - L: O léxico representa conceitos de categorias.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) - RF17: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF18

<div align="center">
  <strong>Tabela 19 -</strong> Cartão do Requisito RF18
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF18, [BR20](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US02](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes) |
| **Elos Backward-from:**  | **Agregação**: RF18 - [BR20](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF18 - UC: O caso de uso satisfaz o requisito de compartilhamento.<br>**Recurso**: RF18 - C: O cenário detalha recursos de salvamento e compartilhamento.<br>**Satisfação**: RF18 - [US02](./historia-de-usuario.md): A história de usuário satisfaz o requisito de exportação.<br>**Representação**: RF18 - L: O léxico representa conceitos de protocolo e compartilhamento.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RF18: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF19

<div align="center">
  <strong>Tabela 20 -</strong> Cartão do Requisito RF19
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF19, [EN01](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US18](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa |
| **Elos Backward-from:**  | **Agregação**: RF19 - [EN01](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF19 - UC: O caso de uso satisfaz o requisito de rastreamento em tempo real.<br>**Recurso**: RF19 - C: O cenário detalha recursos de localização e mapas.<br>**Satisfação**: RF19 - [US18](./historia-de-usuario.md): A história de usuário satisfaz o requisito de transporte público.<br>**Representação**: RF19 - L: O léxico representa conceitos de transporte e GPS.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) - RF19: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF20

<div align="center">
  <strong>Tabela 21 -</strong> Cartão do Requisito RF20
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF20, [EN02](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US34](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo fornece links para serviços externos com explicações claras |
| **Elos Backward-from:**  | **Agregação**: RF20 - [EN02](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF20 - UC: O caso de uso satisfaz o requisito de links externos.<br>**Recurso**: RF20 - C: O cenário detalha recursos de redirecionamento.<br>**Satisfação**: RF20 - [US34](./historia-de-usuario.md): A história de usuário satisfaz o requisito de clareza nas explicações.<br>**Representação**: RF20 - L: O léxico representa conceitos de links e serviços externos.<br>**Responsabilidade**: [Ana Victória](https://github.com/navicg) - RF20: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/navicg">Ana Victória</a>, 2025.</p>

### RF21

<div align="center">
  <strong>Tabela 22 -</strong> Cartão do Requisito RF21
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF21, [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT07](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US40](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL |
| **Elos Backward-from:**  | **Agregação**: RF21 - [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT07](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da entrevista e introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF21 - UC: O caso de uso satisfaz parcialmente o requisito educacional.<br>**Recurso**: RF21 - C: O cenário detalha recursos educacionais.<br>**Satisfação**: RF21 - [US40](./historia-de-usuario.md): A história de usuário satisfaz parcialmente o requisito de informações educacionais.<br>**Representação**: RF21 - L: O léxico representa conceitos de educação e calendário.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) - RF21: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Parcial |

</center>

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF22

<div align="center">
  <strong>Tabela 23 -</strong> Cartão do Requisito RF22
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF22, [EN04](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US01](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial |
| **Elos Backward-from:**  | **Agregação**: RF22 - [EN04](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF22 - UC: O caso de uso satisfaz o requisito de autenticação segura.<br>**Recurso**: RF22 - C: O cenário detalha recursos de autenticação gov.br.<br>**Satisfação**: RF22 - [US01](./historia-de-usuario.md): A história de usuário satisfaz o requisito de login seguro.<br>**Representação**: RF22 - L: O léxico representa conceitos de autenticação e segurança.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RF22: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF23

<div align="center">
  <strong>Tabela 24 -</strong> Cartão do Requisito RF23
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF23, [EN05](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US19](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras |
| **Elos Backward-from:**  | **Agregação**: RF23 - [EN05](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF23 - UC: O caso de uso satisfaz o requisito de serviços fiscais.<br>**Recurso**: RF23 - C: O cenário detalha recursos de pagamento de impostos.<br>**Satisfação**: RF23 - [US19](./historia-de-usuario.md): A história de usuário satisfaz o requisito de clareza fiscal.<br>**Representação**: RF23 - L: O léxico representa conceitos de impostos e boletos.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) - RF23: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF24

<div align="center">
  <strong>Tabela 25 -</strong> Cartão do Requisito RF24
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF24, [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US46](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos |
| **Elos Backward-from:**  | **Agregação**: RF24 - [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF24 - UC: O caso de uso satisfaz o requisito de acompanhamento educacional.<br>**Recurso**: RF24 - C: O cenário detalha recursos de pendências escolares.<br>**Satisfação**: RF24 - [US46](./historia-de-usuario.md): A história de usuário satisfaz o requisito de gestão educacional.<br>**Representação**: RF24 - L: O léxico representa conceitos de educação e pendências.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) - RF24: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF25

<div align="center">
  <strong>Tabela 26 -</strong> Cartão do Requisito RF25
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF25, [EN09](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US23](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve permitir que usuários reportem problemas da cidade através de um mapa interativo |
| **Elos Backward-from:**  | **Agregação**: RF25 - [EN09](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF25 - UC: O caso de uso satisfaz o requisito de reporte interativo.<br>**Recurso**: RF25 - C: O cenário detalha recursos de mapa interativo.<br>**Satisfação**: RF25 - [US23](./historia-de-usuario.md): A história de usuário satisfaz o requisito de reporte geolocalizado.<br>**Representação**: RF25 - L: O léxico representa conceitos de mapa e reporte.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) - RF25: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF26

<div align="center">
  <strong>Tabela 27 -</strong> Cartão do Requisito RF26
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF26, [EN10](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT05](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US24](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve fornecer acesso a números de serviços de emergência da polícia |
| **Elos Backward-from:**  | **Agregação**: RF26 - [EN10](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT05](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da entrevista e introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF26 - UC: O caso de uso satisfaz o requisito de acesso a emergências.<br>**Recurso**: RF26 - C: O cenário detalha recursos de contatos de emergência.<br>**Satisfação**: RF26 - [US24](./historia-de-usuario.md): A história de usuário satisfaz o requisito de segurança pública.<br>**Representação**: RF26 - L: O léxico representa conceitos de emergência e segurança.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) - RF26: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF27

<div align="center">
  <strong>Tabela 28 -</strong> Cartão do Requisito RF27
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF27, [EN11](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), UC, C, [US03](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso |
| **Elos Backward-from:**  | **Agregação**: RF27 - [EN11](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN): O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RF27 - UC: O caso de uso satisfaz o requisito de suporte.<br>**Recurso**: RF27 - C: O cenário detalha recursos de ajuda.<br>**Satisfação**: RF27 - [US03](./historia-de-usuario.md): A história de usuário satisfaz o requisito de instruções.<br>**Representação**: RF27 - L: O léxico representa conceitos de suporte e ajuda.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RF27: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF28

<div align="center">
  <strong>Tabela 29 -</strong> Cartão do Requisito RF28
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF28, [AD02](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US25](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos |
| **Elos Backward-from:**  | **Agregação**: RF28 - [AD02](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF28 - UC: O caso de uso satisfaz o requisito de solicitação de serviços.<br>**Recurso**: RF28 - C: O cenário detalha recursos de serviços públicos.<br>**Satisfação**: RF28 - [US25](./historia-de-usuario.md): A história de usuário satisfaz o requisito de solicitações.<br>**Representação**: RF28 - L: O léxico representa conceitos de serviços públicos.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) - RF28: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF29

<div align="center">
  <strong>Tabela 30 -</strong> Cartão do Requisito RF29
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF29, [AD03](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US26](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço |
| **Elos Backward-from:**  | **Agregação**: RF29 - [AD03](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF29 - UC: O caso de uso satisfaz o requisito de localização no mapa.<br>**Recurso**: RF29 - C: O cenário detalha recursos de geolocalização.<br>**Satisfação**: RF29 - [US26](./historia-de-usuario.md): A história de usuário satisfaz o requisito de visualização espacial.<br>**Representação**: RF29 - L: O léxico representa conceitos de mapa e localização.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) - RF29: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF30

<div align="center">
  <strong>Tabela 31 -</strong> Cartão do Requisito RF30
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF30, [AD04](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US04](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações |
| **Elos Backward-from:**  | **Agregação**: RF30 - [AD04](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF30 - UC: O caso de uso satisfaz o requisito de acompanhamento.<br>**Recurso**: RF30 - C: O cenário detalha recursos de status.<br>**Satisfação**: RF30 - [US04](./historia-de-usuario.md): A história de usuário satisfaz o requisito de monitoramento.<br>**Representação**: RF30 - L: O léxico representa conceitos de status e acompanhamento.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RF30: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF31

<div align="center">
  <strong>Tabela 32 -</strong> Cartão do Requisito RF31
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF31, [AD06](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US05](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O sistema deve permitir que o usuário confirme a resolução de problemas relatados |
| **Elos Backward-from:**  | **Agregação**: RF31 - [AD06](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF31 - UC: O caso de uso satisfaz o requisito de confirmação.<br>**Recurso**: RF31 - C: O cenário detalha recursos de validação.<br>**Satisfação**: RF31 - [US05](./historia-de-usuario.md): A história de usuário satisfaz o requisito de feedback.<br>**Representação**: RF31 - L: O léxico representa conceitos de confirmação e resolução.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RF31: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF32

<div align="center">
  <strong>Tabela 33 -</strong> Cartão do Requisito RF32
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF32, [AD07](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), UC, C, [US06](./historia-de-usuario.md), L |
| **Descrição do Requisito** | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo |
| **Elos Backward-from:**  | **Agregação**: RF32 - [AD07](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RF32 - UC: O caso de uso satisfaz o requisito de exclusão de conta.<br>**Recurso**: RF32 - C: O cenário detalha recursos de privacidade.<br>**Satisfação**: RF32 - [US06](./historia-de-usuario.md): A história de usuário satisfaz o requisito de controle de dados.<br>**Representação**: RF32 - L: O léxico representa conceitos de exclusão e privacidade.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RF32: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RF33

<div align="center">
  <strong>Tabela 34 -</strong> Cartão do Requisito RF33
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF33, [INT01](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US41](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação |
| **Elos Backward-from:**  | **Agregação**: RF33 - [INT01](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF33 - UC: O caso de uso satisfaz o requisito de registro de ocorrências.<br>**Recurso**: RF33 - C: O cenário detalha recursos de infraestrutura.<br>**Satisfação**: RF33 - [US41](./historia-de-usuario.md): A história de usuário satisfaz o requisito de reporte urbano.<br>**Representação**: RF33 - L: O léxico representa conceitos de infraestrutura e ocorrências.<br>**Responsabilidade**: [Artur Mendonça](https://github.com/ArtyMend07) - RF33: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025.</p>

### RF34

<div align="center">
  <strong>Tabela 35 -</strong> Cartão do Requisito RF34
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF34, [INT02](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US20](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes |
| **Elos Backward-from:**  | **Agregação**: RF34 - [INT02](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF34 - UC: O caso de uso satisfaz o requisito de categorização.<br>**Recurso**: RF34 - C: O cenário detalha recursos de triagem.<br>**Satisfação**: RF34 - [US20](./historia-de-usuario.md): A história de usuário satisfaz o requisito de organização.<br>**Representação**: RF34 - L: O léxico representa conceitos de categorias e triagem.<br>**Responsabilidade**: [Gabriel Lopes](https://github.com/BrzGab) - RF34: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RF35

<div align="center">
  <strong>Tabela 36 -</strong> Cartão do Requisito RF35
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF35, [INT03](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US11](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo) |
| **Elos Backward-from:**  | **Agregação**: RF35 - [INT03](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF35 - UC: O caso de uso satisfaz o requisito de seleção de serviços.<br>**Recurso**: RF35 - C: O cenário detalha recursos de tipos de serviço.<br>**Satisfação**: RF35 - [US11](./historia-de-usuario.md): A história de usuário satisfaz o requisito de escolha.<br>**Representação**: RF35 - L: O léxico representa conceitos de serviços e seleção.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RF35: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF36

<div align="center">
  <strong>Tabela 37 -</strong> Cartão do Requisito RF36
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF36, [INT04](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US12](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência |
| **Elos Backward-from:**  | **Agregação**: RF36 - [INT04](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF36 - UC: O caso de uso satisfaz o requisito de documentação detalhada.<br>**Recurso**: RF36 - C: O cenário detalha recursos multimídia.<br>**Satisfação**: RF36 - [US12](./historia-de-usuario.md): A história de usuário satisfaz o requisito de registro completo.<br>**Representação**: RF36 - L: O léxico representa conceitos de mídia e localização.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RF36: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF37

<div align="center">
  <strong>Tabela 38 -</strong> Cartão do Requisito RF37
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF37, [INT06](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US45](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue |
| **Elos Backward-from:**  | **Agregação**: RF37 - [INT06](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF37 - UC: O caso de uso satisfaz o requisito de agendamento de saúde.<br>**Recurso**: RF37 - C: O cenário detalha recursos de saúde pública.<br>**Satisfação**: RF37 - [US45](./historia-de-usuario.md): A história de usuário satisfaz o requisito de serviços médicos.<br>**Representação**: RF37 - L: O léxico representa conceitos de saúde e agendamento.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) - RF37: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF38

<div align="center">
  <strong>Tabela 39 -</strong> Cartão do Requisito RF38
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF38, [INT08](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US13](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade |
| **Elos Backward-from:**  | **Agregação**: RF38 - [INT08](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF38 - UC: O caso de uso satisfaz o requisito de transporte.<br>**Recurso**: RF38 - C: O cenário detalha recursos de mobilidade.<br>**Satisfação**: RF38 - [US13](./historia-de-usuario.md): A história de usuário satisfaz o requisito de cartão mobilidade.<br>**Representação**: RF38 - L: O léxico representa conceitos de transporte público.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RF38: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF39

<div align="center">
  <strong>Tabela 40 -</strong> Cartão do Requisito RF39
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF39, [INT09](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US43](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Permitir agendamentos em serviços sociais, como centros de assistência social e habitação |
| **Elos Backward-from:**  | **Agregação**: RF39 - [INT09](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF39 - UC: O caso de uso satisfaz o requisito de serviços sociais.<br>**Recurso**: RF39 - C: O cenário detalha recursos de assistência social.<br>**Satisfação**: RF39 - [US43](./historia-de-usuario.md): A história de usuário satisfaz o requisito de agendamentos sociais.<br>**Representação**: RF39 - L: O léxico representa conceitos de assistência e habitação.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) - RF39: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF40

<div align="center">
  <strong>Tabela 41 -</strong> Cartão do Requisito RF40
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF40, [INT10](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, US, L |
| **Descrição do Requisito** | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais |
| **Elos Backward-from:**  | **Agregação**: RF40 - [INT10](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF40 - UC: O caso de uso satisfaz o requisito de documentos fiscais.<br>**Recurso**: RF40 - C: O cenário detalha recursos tributários.<br>**Satisfação**: RF40 - US: A história de usuário satisfaz o requisito de emissão de documentos.<br>**Representação**: RF40 - L: O léxico representa conceitos fiscais e tributários. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RF41

<div align="center">
  <strong>Tabela 42 -</strong> Cartão do Requisito RF41
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF41, [INT11](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US47](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos |
| **Elos Backward-from:**  | **Agregação**: RF41 - [INT11](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF41 - UC: O caso de uso satisfaz o requisito de histórico.<br>**Recurso**: RF41 - C: O cenário detalha recursos de registro de atividades.<br>**Satisfação**: RF41 - [US47](./historia-de-usuario.md): A história de usuário satisfaz o requisito de rastreamento.<br>**Representação**: RF41 - L: O léxico representa conceitos de histórico e registro.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) - RF41: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF42

<div align="center">
  <strong>Tabela 43 -</strong> Cartão do Requisito RF42
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF42, [INT12](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, [US44](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal |
| **Elos Backward-from:**  | **Agregação**: RF42 - [INT12](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF42 - UC: O caso de uso satisfaz o requisito de feed informativo.<br>**Recurso**: RF42 - C: O cenário detalha recursos de notícias.<br>**Satisfação**: RF42 - [US44](./historia-de-usuario.md): A história de usuário satisfaz o requisito de informações governamentais.<br>**Representação**: RF42 - L: O léxico representa conceitos de notícias e comunicação.<br>**Responsabilidade**: [Lucas Mendonça](https://github.com/lucasarruda9) - RF42: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025.</p>

### RF43

<div align="center">
  <strong>Tabela 44 -</strong> Cartão do Requisito RF43
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF43, [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [BR18](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), UC, C, [US27](./historia-de-usuario.md), L |
| **Descrição do Requisito** | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes dos usuários |
| **Elos Backward-from:**  | **Agregação**: RF43 - [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [BR18](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS): O requisito originou-se da introspecção e brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RF43 - UC: O caso de uso satisfaz o requisito de assistente virtual.<br>**Recurso**: RF43 - C: O cenário detalha recursos de chatbot.<br>**Satisfação**: RF43 - [US27](./historia-de-usuario.md): A história de usuário satisfaz o requisito de suporte automatizado.<br>**Representação**: RF43 - L: O léxico representa conceitos de assistente e automação.<br>**Responsabilidade**: [Karoline Luz](https://github.com/KarolineLuz) - RF43: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025.</p>

### RF44

<div align="center">
  <strong>Tabela 45 -</strong> Cartão do Requisito RF44
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RF44, [INT14](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), UC, C, US, L |
| **Descrição do Requisito** | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas |
| **Elos Backward-from:**  | **Agregação**: RF44 - [INT14](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT): O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RF44 - UC: O caso de uso satisfaz o requisito de mapa de serviços.<br>**Recurso**: RF44 - C: O cenário detalha recursos de localização espacial.<br>**Satisfação**: RF44 - US: A história de usuário satisfaz o requisito de visualização geográfica.<br>**Representação**: RF44 - L: O léxico representa conceitos de mapa e localização. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

## Cartões de Requisitos Não Funcionais

### RNF01

<div align="center">
  <strong>Tabela 46 -</strong> Cartão do Requisito RNF01
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF01, [AD09](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), ES, NFR, [US14](./historia-de-usuario.md) |
| **Descrição do Requisito** | O sistema deve ser compatível com vários dispositivos como Android e iOS |
| **Elos Backward-from:**  | **Agregação**: RNF01 - [AD09](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RNF01 - ES: A especificação suplementar satisfaz o requisito de compatibilidade.<br>**Representação**: RNF01 - NFR: O NFR Framework representa as metas de portabilidade.<br>**Satisfação**: RNF01 - [US14](./historia-de-usuario.md): A história de usuário satisfaz o requisito de compatibilidade multiplataforma.<br>**Responsabilidade**: [João Marcos](https://github.com/JJOAOMARCOSS) - RNF01: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/JJOAOMARCOSS">João Marcos</a>, 2025.</p>

### RNF02

<div align="center">
  <strong>Tabela 47 -</strong> Cartão do Requisito RNF02
</div>

<center>

| **Categoria:**           | Organizacional                                   |
|:--|:--|
| **Elementos:**           | RNF02, [AD10](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), ES, NFR, [US07](./historia-de-usuario.md) |
| **Descrição do Requisito** | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD) |
| **Elos Backward-from:**  | **Agregação**: RNF02 - [AD10](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD): O requisito originou-se da análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RNF02 - ES: A especificação suplementar satisfaz o requisito legal.<br>**Representação**: RNF02 - NFR: O NFR Framework representa as metas de conformidade legal.<br>**Satisfação**: RNF02 - [US07](./historia-de-usuario.md): A história de usuário satisfaz o requisito de conformidade LGPD.<br>**Responsabilidade**: [Luiza Silva](https://github.com/Luizaxx) - RNF02: Responsável pela elaboração e validação do requisito. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025.</p>

### RNF03

<div align="center">
  <strong>Tabela 48 -</strong> Cartão do Requisito RNF03
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF03, [BRN01](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN), ES, NFR |
| **Descrição do Requisito** | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos |
| **Elos Backward-from:**  | **Agregação**: RNF03 - [BRN01](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN): O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF03 - ES: A especificação suplementar satisfaz o requisito de usabilidade.<br>**Representação**: RNF03 - NFR: O NFR Framework representa as metas de interface. |
| **Implementação:**       | Sim |

</center>


### RNF04

<div align="center">
  <strong>Tabela 49 -</strong> Cartão do Requisito RNF04
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF04, [BRN02](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BRN), ES, NFR |
| **Descrição do Requisito** | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual |
| **Elos Backward-from:**  | **Agregação**: RNF04 - BRN02: O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF04 - ES: A especificação suplementar satisfaz o requisito de acessibilidade.<br>**Representação**: RNF04 - NFR: O NFR Framework representa as metas de inclusão. |
| **Implementação:**       | Não |

</center>



### RNF05

<div align="center">
  <strong>Tabela 50 -</strong> Cartão do Requisito RNF05
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF05, BRN04, ES, NFR |
| **Descrição do Requisito** | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware |
| **Elos Backward-from:**  | **Agregação**: RNF05 - BRN04: O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF05 - ES: A especificação suplementar satisfaz o requisito de performance.<br>**Representação**: RNF05 - NFR: O NFR Framework representa as metas de eficiência. |
| **Implementação:**       | Sim |

</center>



### RNF06

<div align="center">
  <strong>Tabela 51 -</strong> Cartão do Requisito RNF06
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF06, BRN05, ES, NFR |
| **Descrição do Requisito** | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos |
| **Elos Backward-from:**  | **Agregação**: RNF06 - BRN05: O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF06 - ES: A especificação suplementar satisfaz o requisito de navegabilidade.<br>**Representação**: RNF06 - NFR: O NFR Framework representa as metas de fluidez. |
| **Implementação:**       | Não |

</center>



### RNF07

<div align="center">
  <strong>Tabela 52 -</strong> Cartão do Requisito RNF07
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF07, BRN06, ES, NFR |
| **Descrição do Requisito** | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta |
| **Elos Backward-from:**  | **Agregação**: RNF07 - BRN06: O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF07 - ES: A especificação suplementar satisfaz o requisito de otimização.<br>**Representação**: RNF07 - NFR: O NFR Framework representa as metas de desempenho. |
| **Implementação:**       | Sim |

</center>



### RNF08

<div align="center">
  <strong>Tabela 53 -</strong> Cartão do Requisito RNF08
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF08, BRN07, INT22, ES, NFR |
| **Descrição do Requisito** | O layout deve ser responsivo para diferentes tamanhos de tela |
| **Elos Backward-from:**  | **Agregação**: RNF08 - BRN07, INT22: O requisito originou-se do brainstorming e introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF08 - ES: A especificação suplementar satisfaz o requisito de responsividade.<br>**Representação**: RNF08 - NFR: O NFR Framework representa as metas de adaptabilidade. |
| **Implementação:**       | Sim |

</center>



### RNF09

<div align="center">
  <strong>Tabela 54 -</strong> Cartão do Requisito RNF09
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF09, BRN08, ES, NFR |
| **Descrição do Requisito** | O sistema deve ter compatibilidade com leitores de tela |
| **Elos Backward-from:**  | **Agregação**: RNF09 - BRN08: O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF09 - ES: A especificação suplementar satisfaz o requisito de acessibilidade técnica.<br>**Representação**: RNF09 - NFR: O NFR Framework representa as metas de compatibilidade assistiva. |
| **Implementação:**       | Sim |

</center>



### RNF10

<div align="center">
  <strong>Tabela 55 -</strong> Cartão do Requisito RNF10
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF10, BRN09, ES, NFR |
| **Descrição do Requisito** | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade |
| **Elos Backward-from:**  | **Agregação**: RNF10 - BRN09: O requisito originou-se do brainstorming |
| **Elos Forward-from:**   | **Satisfação**: RNF10 - ES: A especificação suplementar satisfaz o requisito de comunicação clara.<br>**Representação**: RNF10 - NFR: O NFR Framework representa as metas de legibilidade. |
| **Implementação:**       | Não |

</center>



### RNF11

<div align="center">
  <strong>Tabela 56 -</strong> Cartão do Requisito RNF11
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF11, EN01, AD11, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos |
| **Elos Backward-from:**  | **Agregação**: RNF11 - EN01, AD11: O requisito originou-se da entrevista e análise de documentos |
| **Elos Forward-from:**   | **Satisfação**: RNF11 - ES: A especificação suplementar satisfaz o requisito de intuitividade.<br>**Representação**: RNF11 - NFR: O NFR Framework representa as metas de autonomia do aplicativo. |
| **Implementação:**       | Não |

</center>



### RNF12

<div align="center">
  <strong>Tabela 57 -</strong> Cartão do Requisito RNF12
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF12, EN02, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação |
| **Elos Backward-from:**  | **Agregação**: RNF12 - EN02: O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RNF12 - ES: A especificação suplementar satisfaz o requisito de confiabilidade.<br>**Representação**: RNF12 - NFR: O NFR Framework representa as metas de precisão da informação. |
| **Implementação:**       | Sim |

</center>



### RNF13

<div align="center">
  <strong>Tabela 58 -</strong> Cartão do Requisito RNF13
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF13, EN03, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis |
| **Elos Backward-from:**  | **Agregação**: RNF13 - EN03: O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RNF13 - ES: A especificação suplementar satisfaz o requisito de estabilidade.<br>**Representação**: RNF13 - NFR: O NFR Framework representa as metas de robustez. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/">Ana Victória</a>, 2025.</p>

### RNF14

<div align="center">
  <strong>Tabela 59 -</strong> Cartão do Requisito RNF14
</div>

<center>

| **Categoria:**           | Organizacional                                   |
|:--|:--|
| **Elementos:**           | RNF14, EN04, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança |
| **Elos Backward-from:**  | **Agregação**: RNF14 - EN04: O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RNF14 - ES: A especificação suplementar satisfaz o requisito de segurança.<br>**Representação**: RNF14 - NFR: O NFR Framework representa as metas de privacidade. |
| **Implementação:**       | Sim |

</center>



### RNF15

<div align="center">
  <strong>Tabela 60 -</strong> Cartão do Requisito RNF15
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF15, EN05, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida |
| **Elos Backward-from:**  | **Agregação**: RNF15 - EN05: O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RNF15 - ES: A especificação suplementar satisfaz o requisito de performance de autenticação.<br>**Representação**: RNF15 - NFR: O NFR Framework representa as metas de velocidade de login. |
| **Implementação:**       | Não |

</center>



### RNF16

<div align="center">
  <strong>Tabela 61 -</strong> Cartão do Requisito RNF16
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF16, EN06, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis |
| **Elos Backward-from:**  | **Agregação**: RNF16 - EN06: O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RNF16 - ES: A especificação suplementar satisfaz o requisito de usabilidade para idosos.<br>**Representação**: RNF16 - NFR: O NFR Framework representa as metas de design inclusivo. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/">Karoline Luz</a>, 2025.</p>

### RNF17

<div align="center">
  <strong>Tabela 62 -</strong> Cartão do Requisito RNF17
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF17, EN07, INT19, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais |
| **Elos Backward-from:**  | **Agregação**: RNF17 - EN07, INT19: O requisito originou-se da entrevista e introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF17 - ES: A especificação suplementar satisfaz o requisito de acessibilidade visual.<br>**Representação**: RNF17 - NFR: O NFR Framework representa as metas de inclusão visual. |
| **Implementação:**       | Não |

</center>



### RNF18

<div align="center">
  <strong>Tabela 63 -</strong> Cartão do Requisito RNF18
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF18, EN08, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários |
| **Elos Backward-from:**  | **Agregação**: RNF18 - EN08: O requisito originou-se da entrevista |
| **Elos Forward-from:**   | **Satisfação**: RNF18 - ES: A especificação suplementar satisfaz o requisito de aparência.<br>**Representação**: RNF18 - NFR: O NFR Framework representa as metas de design profissional. |
| **Implementação:**       | Não |

</center>



### RNF19

<div align="center">
  <strong>Tabela 64 -</strong> Cartão do Requisito RNF19
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF19, INT15, ES, NFR |
| **Descrição do Requisito** | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS |
| **Elos Backward-from:**  | **Agregação**: RNF19 - INT15: O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF19 - ES: A especificação suplementar satisfaz o requisito de compatibilidade atual.<br>**Representação**: RNF19 - NFR: O NFR Framework representa as metas de atualização tecnológica. |
| **Implementação:**       | Sim |

</center>



### RNF20

<div align="center">
  <strong>Tabela 65 -</strong> Cartão do Requisito RNF20
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF20, INT16, ES, NFR |
| **Descrição do Requisito** | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência |
| **Elos Backward-from:**  | **Agregação**: RNF20 - INT16: O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF20 - ES: A especificação suplementar satisfaz o requisito de tempo de resposta.<br>**Representação**: RNF20 - NFR: O NFR Framework representa as metas de latência. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/">Artur Mendonça</a>, 2025.</p>

### RNF21

<div align="center">
  <strong>Tabela 66 -</strong> Cartão do Requisito RNF21
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF21, INT17, ES, NFR |
| **Descrição do Requisito** | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade |
| **Elos Backward-from:**  | **Agregação**: RNF21 - INT17: O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF21 - ES: A especificação suplementar satisfaz o requisito de simplicidade.<br>**Representação**: RNF21 - NFR: O NFR Framework representa as metas de clareza comunicativa. |
| **Implementação:**       | Sim |

</center>



### RNF22

<div align="center">
  <strong>Tabela 67 -</strong> Cartão do Requisito RNF22
</div>

<center>

| **Categoria:**           | Organizacional                                   |
|:--|:--|
| **Elementos:**           | RNF22, INT18, ES, NFR |
| **Descrição do Requisito** | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura |
| **Elos Backward-from:**  | **Agregação**: RNF22 - INT18: O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF22 - ES: A especificação suplementar satisfaz o requisito de criptografia.<br>**Representação**: RNF22 - NFR: O NFR Framework representa as metas de segurança técnica. |
| **Implementação:**       | Sim |

</center>

<p align="center">Autor: <a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025.</p>

### RNF23

<div align="center">
  <strong>Tabela 68 -</strong> Cartão do Requisito RNF23
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF23, INT20, ES, NFR |
| **Descrição do Requisito** | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas |
| **Elos Backward-from:**  | **Agregação**: RNF23 - INT20: O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF23 - ES: A especificação suplementar satisfaz o requisito de funcionalidade offline.<br>**Representação**: RNF23 - NFR: O NFR Framework representa as metas de disponibilidade. |
| **Implementação:**       | Não |

</center>

<p align="center">Autor: <a href="https://github.com/">Lucas Mendonça</a>, 2025.</p>

### RNF24

<div align="center">
  <strong>Tabela 69 -</strong> Cartão do Requisito RNF24
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RNF24, INT21, ES, NFR |
| **Descrição do Requisito** | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis |
| **Elos Backward-from:**  | **Agregação**: RNF24 - INT21: O requisito originou-se da introspecção |
| **Elos Forward-from:**   | **Satisfação**: RNF24 - ES: A especificação suplementar satisfaz o requisito de otimização de mídia.<br>**Representação**: RNF24 - NFR: O NFR Framework representa as metas de eficiência de upload. |
| **Implementação:**       | Sim |

</center>



## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 07 jun. 2025.

> <a id="RP2" href="#TEC2">2.</a> Kotonya, Gerald, and Ian Sommerville. "Requirements Engineering: Processes and Techniques." John Wiley & Sons, 1998. Disponível em: (https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf).Acesso em: 07 jun. 2025.

> <a id="RP3" href="#TEC3">3.</a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. disponível em: [https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/doimagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 07 jun. 2025.

## Bibliografia
> <a id="RP1" href="#TEC1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 07 jun. 2025.

> <a id="RP2" href="#TEC2">2.</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf). Acesso em: 07 jun. 2025.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 21/06/2024  | Criação da página | [Gabriel Lopes](https://github.com/BrzGab) e [Artur Mendonça](https://github.com/ArtyMend07) | 22/06/2024 |  [Lucas Mendonça](https://github.com/lucasarruda9) |