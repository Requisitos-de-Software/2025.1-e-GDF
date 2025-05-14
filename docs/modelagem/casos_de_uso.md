# O que são Casos de Uso

Casos de uso são uma técnica de modelagem usada para descrever os **requisitos funcionais** de um sistema, focando nas **interações entre usuários (atores) e o sistema** para atingir determinados objetivos.

## Definição
Um **caso de uso** representa uma sequência de interações entre um ator e o sistema que resulta em um **resultado observável e de valor** para o ator.

## Objetivo
O principal objetivo dos casos de uso é **documentar como o sistema deve se comportar** em resposta às ações dos usuários, servindo como ponte entre analistas, desenvolvedores e clientes.

## Características
- São representados por **diagramas de casos de uso**, utilizando a notação UML (Unified Modeling Language).
- Os **atores** podem ser pessoas, sistemas externos ou dispositivos que interagem com o sistema.
- Cada caso de uso descreve um **fluxo de eventos**, podendo incluir:
  - **Fluxo principal** 
  - **Fluxos alternativos**
  - **Fluxos de exceção**

## Notação
- Usar **verbos no infinitivo** para nomear os casos de uso, pois eles representam **ações**.
- Casos de uso são representados por **elipses**, e os atores por **figuras humanas** (para pessoas).

## Tipos de Relacionamento
- `include`: Indica que um caso de uso **sempre inclui** outro.
- `extend`: Indica que um caso de uso **pode opcionalmente estender** outro.
- `generalization`: Herança entre casos de uso ou entre atores.

# Componentes e Símbolos de um Diagrama de Casos de Uso

| **Componente** | **Descrição** | **Representação** | **Observações** |
|----------------|---------------|--------------------|------------------|
| **Ator** | Representa um usuário ou sistema externo que interage com o sistema. |  <p> boneco de palito </p>   <img src="https://uploaddeimagens.com.br/images/004/898/880/original/Captura_de_tela_2025-05-14_172431.png?1747254282" style="height:100px;width:100px"/>| Pode ser uma pessoa, sistema, dispositivo, etc. |
| **Sistema** | Define o escopo do sistema e contém os casos de uso. | <p> Retângulo </p>   <img src="https://uploaddeimagens.com.br/images/004/898/872/original/Captura_de_tela_2025-05-14_171350.png?1747253666" style="height:100px;width:100px"/> | Casos de uso fora do retângulo estão fora do escopo. |
| **Caso de Uso** | Representa uma funcionalidade ou ação do sistema. | <p> Elipse </p>   <img src="https://uploaddeimagens.com.br/images/004/898/873/original/Captura_de_tela_2025-05-14_171524.png?1747253734" style="height:100px;width:100px"/> | Ex: `Realizar login` |
| **Comunicação** | Relação entre ator e caso de uso. | <p> Linha sólida </p>   <img src="https://uploaddeimagens.com.br/images/004/898/875/original/Captura_de_tela_2025-05-14_171817.png?1747253905" style="height:100px;width:100px"/> | Indica que o ator executa ou interage com a funcionalidade. |
| **Inclusão** (`<<include>>`) | Um caso de uso inclui outro obrigatoriamente. | <p> Linha tracejada com seta e nome `<<include>>`. </p>   <img src="https://uploaddeimagens.com.br/images/004/898/877/original/Captura_de_tela_2025-05-14_172102.png?1747254078" style="height:100px;width:100px"/>  | O caso incluído **sempre** será executado. |
| **Extensão** (`<<extend>>`) | Um caso de uso pode adicionar comportamento opcional a outro. | <p> Linha tracejada com seta apontada para o caso base e nome `<<extend>>`. </p>   <img src="https://uploaddeimagens.com.br/images/004/898/878/original/Captura_de_tela_2025-05-14_172153.png?1747254126" style="height:100px;width:100px"/>  | O caso estendido **pode ou não** ser executado. |

 <font size="3"><p style="text-align: center">Figuras Elaboradas por: [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

## Metodologia

Para o levantamento e modelagem dos requisitos do sistema, foi adotada uma abordagem baseada na **Engenharia de Requisitos**, com foco na identificação e documentação dos **requisitos funcionais** por meio de **Casos de Uso**.

A modelagem seguiu os princípios da UML (Unified Modeling Language), utilizando o **Diagrama de Casos de Uso** como ferramenta principal para representar as interações entre os usuários (atores) e o sistema.
A ferramenta utilizada para a criação do diagrama foi o **[Drawio](https://www.drawio.com/)**

## Diagrama de Casos de Uso 


<img src="https://uploaddeimagens.com.br/images/004/898/881/original/Casos_de_Uso_-_e-GDF.drawio_%281%29.png?1747254726" />

<font size="3"><p style="text-align: center">Elaborado por: [Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

<font size="3"><p style="text-align: center"> Disponível de forma online em PDF:  [Clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Casos%20de%20Uso%20-%20e-GDF&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D10GdaECkUznH_nYY121uDyYmGvFr_6X8Y%26export%3Ddownload) </p></font>

## Especialização de caso de uso 

# Casos de Uso – Sistema e-GDF

| Código | Caso de Uso                         | Atores envolvidos              | Pré-condição                          | Pós-condição                                 | Requisitos Funcionais               |
|--------|-------------------------------------|--------------------------------|---------------------------------------|----------------------------------------------|-------------------------------------|
| UC01   | Fazer Login                         | Cidadão                        | Acesso ao sistema                     | Usuário autenticado                          | Autenticação                        |
| UC02   | Registrar Ocorrência                | Cidadão, Sistema de Governo    | Login realizado                       | Ocorrência registrada                        | Formulário, upload, localização     |
| UC03   | Acessar Contato de Emergência       | Cidadão                        | Nenhuma                               | Informações exibidas                         | Consulta de dados                   |
| UC04   | Realizar Chamada de Emergência      | Cidadão                        | Nenhuma                               | Ligação efetuada                             | Integração com discagem do sistema |
| UC05   | Agendar Doação de Sangue            | Cidadão, Sistema de Saúde      | Login realizado                       | Agendamento confirmado                       | Sistema de agendamento             |
| UC06   | Acessar Serviços Meu SUS            | Cidadão, Sistema de Saúde      | Login realizado                       | Visualização de serviços                     | Integração com sistema do SUS       |
| UC07   | Consultar Calendário Escolar        | Cidadão, Sistema Educacional   | Nenhuma                               | Informações exibidas                         | Acesso a dados                      |
| UC08   | Cadastrar Cartão Mobilidade         | Cidadão, Sistema de Transporte | Login realizado                       | Cartão cadastrado                            | Cadastro e validação de dados       |
| UC09   | Realizar Matrícula em Creches       | Cidadão, Sistema Educacional   | Login realizado                       | Matrícula registrada                         | Formulário, integração escolar      |
| UC10   | Consultar DF no Ponto               | Cidadão, Sistema de Transporte | Nenhuma                               | Informações exibidas                         | Consulta em tempo real              |
| UC11   | Agendar na CODHAB                   | Cidadão                        | Login realizado                       | Agendamento efetuado                         | Sistema de agendamento             |
| UC12   | Inscrever-se no Morar Bem           | Cidadão                        | Login realizado                       | Inscrição registrada                         | Formulário, validação               |
| UC13   | Agendar no CRAS                     | Cidadão, Sistema de Assistência| Login realizado                       | Agendamento realizado                        | Integração com CRAS                |
| UC14   | Emitir Documentos Fiscais           | Cidadão, Sistema Tributário    | Login realizado                       | Documento gerado                             | Geração de PDF/relatório            |
| UC15   | Consultar Atividades                | Cidadão                        | Nenhuma                               | Lista de atividades exibida                  | Listagem                           |
| UC16   | Visualizar Notícias                 | Cidadão                        | Nenhuma                               | Notícias exibidas                            | Integração com feed/notícias        |
| UC17   | Interagir com ChatBot               | Cidadão                        | Nenhuma                               | Respostas automáticas fornecidas             | Integração com IA ou script        |
| UC18   | Visualizar Mapa                     | Cidadão                        | Nenhuma                               | Mapa exibido                                 | Integração com sistema de mapas     |
| UC19   | Localizar Ocorrência                | Cidadão                        | Ocorrência registrada                 | Localização exibida                          | Mapa, busca                        |
| UC20   | Localizar Serviços                  | Cidadão                        | Nenhuma                               | Lista de serviços exibida                    | Busca por tipo/localização         |
| UC21   | Gerenciar Conta                     | Cidadão                        | Login realizado                       | Ações de conta realizadas                    | CRUD de usuário                    |
| UC22   | Cadastrar Usuário                   | Cidadão                        | Nenhuma                               | Cadastro realizado                           | Validação e persistência de dados  |
| UC23   | Editar Perfil                       | Cidadão                        | Login realizado                       | Perfil atualizado                            | Edição de dados pessoais           |
| UC24   | Autenticar Usuário                  | Cidadão                        | Dados de login informados            | Usuário autenticado                          | Autenticação                       |
| UC25   | Emitir IPVA                         | Cidadão, Sistema Tributário    | Login realizado                       | Documento gerado                             | Integração com base tributária     |
| UC26   | Emitir IPTU                         | Cidadão, Sistema Tributário    | Login realizado                       | Documento gerado                             | Geração de boleto/dados            |
| UC27   | Emitir DAR                          | Cidadão, Sistema Tributário    | Login realizado                       | Documento gerado                             | Emissão de DAR eletrônico          |
| UC28   | Emitir Certidão Negativa            | Cidadão, Sistema Tributário    | Login realizado                       | Certidão emitida                             | Integração e validação de pendências |

<font size="3"><p style="text-align: center">Elaborado por: [Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

## Referências Bibliograficas

[1] DevMedia. *O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML*. 2012.  
Disponível em: [https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408](https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408).  
Acessado em: 13 de Maio. de 2025.

[2] SERRANO M., SERRANO M. *Requisitos - Aula 13*.  
Disponível na plataforma Aprender3: [https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf).  
Acessado em: 13 de Maio. de 2025.


# Histórico de Versões

| Versão | Descrição                                           | Autor(es)                                                                 | Data       | Revisor(es)                                         | Data de revisão |
|--------|----------------------------------------------------|---------------------------------------------------------------------------|------------|----------------------------------------------------|-----------------|
| 1.0    | Criação da documentação do Casos de Uso          |  [Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 14/05/2025 | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)       | 17/05/2025      |
