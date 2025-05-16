# Casos de Uso

## O que são Casos de Uso

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

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

## Metodologia

Para o levantamento e modelagem dos requisitos do sistema, foi adotada uma abordagem baseada na **Engenharia de Requisitos**, com foco na identificação e documentação dos **requisitos funcionais** por meio de **Casos de Uso**.

A modelagem seguiu os princípios da UML (Unified Modeling Language), utilizando o **Diagrama de Casos de Uso** como ferramenta principal para representar as interações entre os usuários (atores) e o sistema.
A ferramenta utilizada para a criação do diagrama foi o **[Drawio](https://www.drawio.com/)**

## Diagrama de Casos de Uso 


<a href="https://ibb.co/LXgStbGs"><img src="https://i.ibb.co/8LxM5ThQ/Casos-de-Uso-e-GDF-drawio.png" alt="Casos-de-Uso-e-GDF-drawio" border="0" /></a>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


<font size="3"><p style="text-align: center"> Disponível de forma online em PDF:  [Clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Casos%20de%20Uso%20-%20e-GDF&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D10GdaECkUznH_nYY121uDyYmGvFr_6X8Y%26export%3Ddownload) </p></font>

## Especialização de caso de uso 

# Casos de Uso – Sistema e-GDF


| UC01 | Fazer Login |
| ----- | ---------- |
| Descrição | O usuário é capaz de realizar o login no sistema através de credenciais seguras |
| Ator | Cidadão |
| Pré-condições | Acesso à internet, cadastro no sistema |
| Ação | O usuário autentica-se no sistema |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona a opção "Login" </br> <li> O usuário insere seu CPF e senha </br> <li> O usuário clica em "Entrar" </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona a opção "Login" </br> <li> O usuário escolhe login com gov.br </br> <li> O sistema redireciona para a plataforma gov.br </br> <li> O usuário completa a autenticação </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona a opção "Login" </br> <li> O usuário insere credenciais inválidas </br> <li> O sistema exibe mensagem de erro </br> <li> O usuário seleciona "Esqueci minha senha" </br> </ul> |
| Pós-condições | O usuário está autenticado e tem acesso às funcionalidades que requerem login |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF01](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC02 | Registrar Ocorrência |
| ----- | ---------- |
| Descrição | O usuário é capaz de registrar ocorrências relacionadas a problemas de infraestrutura urbana |
| Ator | Cidadão, Sistema de Governo |
| Pré-condições | Login realizado |
| Ação | O usuário registra uma ocorrência no sistema |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Registrar Ocorrência" </br> <li> O usuário seleciona a categoria da ocorrência </br> <li> O usuário adiciona descrição do problema </br> <li> O usuário captura e anexa uma foto </br> <li> O usuário confirma localização via GPS </br> <li> O usuário envia a ocorrência </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Registrar Ocorrência" </br> <li> O usuário escolhe localização manual no mapa </br> <li> O usuário preenche os demais dados </br> <li> O usuário envia a ocorrência </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Registrar Ocorrência" </br> <li> O usuário preenche dados incompletos </br> <li> O sistema exibe mensagem de erro </br> <li> O usuário completa as informações necessárias </br> </ul> |
| Pós-condições | Ocorrência registrada no sistema e encaminhada para o órgão responsável |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF29](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF34](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF35](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF36](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF37](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC03 | Acessar Contato de Emergência |
| ----- | ---------- |
| Descrição | O usuário acessa informações de contatos de emergência |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário visualiza contatos de emergência |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Emergência" na tela inicial </br> <li> O sistema exibe lista de contatos de emergência </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca por "emergência" ou "contatos" </br> <li> O sistema exibe os contatos de emergência </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Emergência" na tela inicial </br> <li> O sistema apresenta erro de conexão </br> <li> O sistema exibe contatos salvos offline </br> </ul> |
| Pós-condições | O usuário visualiza a lista de contatos de emergência |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF27](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC04 | Realizar Chamada de Emergência |
| ----- | ---------- |
| Descrição | O usuário realiza chamada direta para serviços de emergência |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário efetua ligação para serviço de emergência |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Emergência" na tela inicial </br> <li> O usuário seleciona o serviço desejado (polícia, bombeiros, SAMU) </br> <li> O usuário confirma a chamada </br> <li> O sistema redireciona para o discador com o número preenchido </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário usa o assistente virtual </br> <li> O usuário solicita "ligar para emergência" </br> <li> O sistema oferece opções de serviços emergenciais </br> <li> O usuário seleciona o serviço desejado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Emergência" na tela inicial </br> <li> O usuário seleciona o serviço desejado </br> <li> O dispositivo não tem permissão para realizar chamadas </br> <li> O sistema exibe mensagem de erro e orientação </br> </ul> |
| Pós-condições | Ligação efetuada para o serviço de emergência escolhido |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF27](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC05 | Agendar Doação de Sangue |
| ----- | ---------- |
| Descrição | O usuário agenda doação de sangue em hemocentros do DF |
| Ator | Cidadão, Sistema de Saúde |
| Pré-condições | Login realizado |
| Ação | O usuário agenda horário para doação de sangue |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços de Saúde" </br> <li> O usuário seleciona "Doação de Sangue" </br> <li> O usuário escolhe o hemocentro desejado </br> <li> O usuário seleciona data e horário disponíveis </br> <li> O usuário preenche questionário de pré-triagem </br> <li> O usuário confirma agendamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca "doação de sangue" </br> <li> O sistema exibe a opção de agendamento </br> <li> O usuário segue o fluxo de agendamento </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços de Saúde" </br> <li> O usuário seleciona "Doação de Sangue" </br> <li> O sistema verifica que o usuário não está elegível </br> <li> O sistema exibe os motivos e orientações </br> </ul> |
| Pós-condições | Agendamento de doação confirmado e registrado no sistema |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF38](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC06 | Acessar Serviços Meu SUS |
| ----- | ---------- |
| Descrição | O usuário acessa serviços integrados com o sistema SUS |
| Ator | Cidadão, Sistema de Saúde |
| Pré-condições | Login realizado |
| Ação | O usuário acessa serviços relacionados ao SUS |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços de Saúde" </br> <li> O usuário seleciona "Meu SUS" </br> <li> O sistema exibe opções de serviços disponíveis </br> <li> O usuário seleciona o serviço desejado </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza o assistente virtual </br> <li> O usuário solicita acesso aos serviços do SUS </br> <li> O sistema direciona para a área de serviços do SUS </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços de Saúde" </br> <li> O usuário seleciona "Meu SUS" </br> <li> O sistema detecta dados incompletos no cadastro </br> <li> O sistema solicita complementação de informações </br> </ul> |
| Pós-condições | O usuário visualiza e acessa os serviços do SUS disponíveis |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF11](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC07 | Consultar Calendário Escolar |
| ----- | ---------- |
| Descrição | O usuário consulta o calendário escolar da rede pública de ensino do DF |
| Ator | Cidadão, Sistema Educacional |
| Pré-condições | Nenhuma |
| Ação | O usuário visualiza informações do calendário escolar |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Educação" </br> <li> O usuário seleciona "Calendário Escolar" </br> <li> O sistema exibe o calendário escolar vigente </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca "calendário escolar" </br> <li> O sistema exibe o calendário escolar </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Educação" </br> <li> O usuário seleciona "Calendário Escolar" </br> <li> O sistema enfrenta falha de conexão </br> <li> O sistema exibe versão em cache ou mensagem de erro </br> </ul> |
| Pós-condições | O usuário visualiza o calendário escolar atualizado |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF22](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC08 | Cadastrar Cartão Mobilidade |
| ----- | ---------- |
| Descrição | O usuário realiza o pré-cadastro do Cartão Mobilidade para transporte público |
| Ator | Cidadão, Sistema de Transporte |
| Pré-condições | Login realizado |
| Ação | O usuário cadastra dados para emissão de Cartão Mobilidade |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Transporte" </br> <li> O usuário seleciona "Cartão Mobilidade" </br> <li> O usuário seleciona "Novo Cadastro" </br> <li> O usuário preenche formulário com dados pessoais </br> <li> O usuário anexa documentos solicitados </br> <li> O usuário confirma o cadastro </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca "cartão mobilidade" </br> <li> O sistema exibe a opção de cadastro </br> <li> O usuário segue o fluxo de cadastro </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Transporte" </br> <li> O usuário seleciona "Cartão Mobilidade" </br> <li> O sistema detecta cadastro já existente </br> <li> O sistema exibe informações do cadastro atual </br> </ul> |
| Pós-condições | Cartão Mobilidade cadastrado e aguardando aprovação |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF39](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC09 | Realizar Matrícula em Creches |
| ----- | ---------- |
| Descrição | O usuário realiza matrícula de crianças em creches da rede pública |
| Ator | Cidadão, Sistema Educacional |
| Pré-condições | Login realizado |
| Ação | O usuário efetua matrícula em creche |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Educação" </br> <li> O usuário seleciona "Matrícula em Creches" </br> <li> O usuário preenche dados do responsável e da criança </br> <li> O usuário seleciona creches por ordem de preferência </br> <li> O usuário anexa documentos solicitados </br> <li> O usuário confirma a matrícula </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca "matrícula creche" </br> <li> O sistema exibe a opção de matrícula </br> <li> O usuário segue o fluxo de matrícula </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Educação" </br> <li> O usuário seleciona "Matrícula em Creches" </br> <li> O sistema verifica que o período de matrícula está encerrado </br> <li> O sistema exibe informações sobre próximo período </br> </ul> |
| Pós-condições | Matrícula registrada e aguardando confirmação de vaga |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF11](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF22](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC10 | Consultar DF no Ponto |
| ----- | ---------- |
| Descrição | O usuário consulta informações sobre transporte público em tempo real |
| Ator | Cidadão, Sistema de Transporte |
| Pré-condições | Nenhuma |
| Ação | O usuário visualiza informações sobre ônibus e itinerários |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Transporte" </br> <li> O usuário seleciona "DF no Ponto" </br> <li> O sistema exibe mapa com localização de ônibus </br> <li> O usuário seleciona linha de interesse </br> <li> O sistema exibe informações da linha e previsão de chegada </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Transporte" </br> <li> O usuário seleciona "DF no Ponto" </br> <li> O usuário busca pelo número da linha desejada </br> <li> O sistema exibe informações da linha </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Transporte" </br> <li> O usuário seleciona "DF no Ponto" </br> <li> O sistema não consegue obter dados em tempo real </br> <li> O sistema exibe informações estáticas dos horários programados </br> </ul> |
| Pós-condições | O usuário visualiza informações atualizadas sobre o transporte público |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF20](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC11 | Agendar na CODHAB |
| ----- | ---------- |
| Descrição | O usuário agenda atendimento na Companhia de Desenvolvimento Habitacional |
| Ator | Cidadão |
| Pré-condições | Login realizado |
| Ação | O usuário agenda horário na CODHAB |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Habitação" </br> <li> O usuário seleciona "Agendar CODHAB" </br> <li> O usuário seleciona unidade de atendimento </br> <li> O usuário seleciona tipo de serviço </br> <li> O usuário escolhe data e horário disponíveis </br> <li> O usuário confirma o agendamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca "CODHAB" </br> <li> O sistema exibe opções de serviços </br> <li> O usuário seleciona "Agendar Atendimento" </br> <li> O usuário segue o fluxo de agendamento </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Habitação" </br> <li> O usuário seleciona "Agendar CODHAB" </br> <li> O sistema verifica que não há horários disponíveis </br> <li> O sistema exibe mensagem e opção para notificação </br> </ul> |
| Pós-condições | Agendamento efetuado e confirmado |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF40](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC12 | Inscrever-se no Morar Bem |
| ----- | ---------- |
| Descrição | O usuário se inscreve no programa habitacional Morar Bem |
| Ator | Cidadão |
| Pré-condições | Login realizado |
| Ação | O usuário realiza inscrição no programa Morar Bem |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Habitação" </br> <li> O usuário seleciona "Morar Bem" </br> <li> O usuário preenche formulário socioeconômico </br> <li> O usuário anexa documentos comprobatórios </br> <li> O usuário confirma a inscrição </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca "Morar Bem" </br> <li> O sistema exibe a opção de inscrição </br> <li> O usuário segue o fluxo de inscrição </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Habitação" </br> <li> O usuário seleciona "Morar Bem" </br> <li> O sistema detecta inscrição já existente </br> <li> O sistema exibe status da inscrição atual </br> </ul> |
| Pós-condições | Inscrição registrada no programa Morar Bem |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF40](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC13 | Agendar no CRAS |
| ----- | ---------- |
| Descrição | O usuário agenda atendimento no Centro de Referência de Assistência Social |
| Ator | Cidadão, Sistema de Assistência |
| Pré-condições | Login realizado |
| Ação | O usuário agenda horário no CRAS |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Assistência Social" </br> <li> O usuário seleciona "Agendar CRAS" </br> <li> O usuário seleciona unidade mais próxima </br> <li> O usuário seleciona tipo de atendimento </br> <li> O usuário escolhe data e horário disponíveis </br> <li> O usuário confirma o agendamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza o mapa de serviços </br> <li> O usuário localiza um CRAS próximo </br> <li> O usuário seleciona "Agendar Atendimento" </br> <li> O usuário segue o fluxo de agendamento </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Assistência Social" </br> <li> O usuário seleciona "Agendar CRAS" </br> <li> O sistema verifica que não há unidades disponíveis na região </br> <li> O sistema sugere outras unidades próximas </br> </ul> |
| Pós-condições | Agendamento realizado no CRAS escolhido |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF40](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC14 | Emitir Documentos Fiscais |
| ----- | ---------- |
| Descrição | O usuário emite documentos fiscais como certidões e boletos de pagamento |
| Ator | Cidadão, Sistema Tributário |
| Pré-condições | Login realizado |
| Ação | O usuário emite documentos fiscais |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona o tipo de documento desejado </br> <li> O usuário preenche informações solicitadas </br> <li> O sistema gera o documento </br> <li> O usuário visualiza e baixa o documento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca pelo nome do documento desejado </br> <li> O sistema exibe opções relacionadas </br> <li> O usuário seleciona a opção desejada </br> <li> O usuário segue o fluxo de emissão </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona o tipo de documento desejado </br> <li> O sistema detecta pendências que impedem emissão </br> <li> O sistema exibe mensagem informativa sobre as pendências </br> </ul> |
| Pós-condições | Documento fiscal emitido em formato digital |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF41](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC15 | Consultar Atividades |
| ----- | ---------- |
| Descrição | O usuário consulta histórico de atividades e interações no sistema |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário visualiza lista de atividades realizadas |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Minhas Atividades" </br> <li> O sistema exibe lista cronológica de atividades </br> <li> O usuário pode filtrar por tipo de atividade </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa seu perfil </br> <li> O usuário seleciona "Histórico" </br> <li> O sistema exibe lista de atividades recentes </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Minhas Atividades" </br> <li> O sistema enfrenta erro ao carregar dados </br> <li> O sistema exibe mensagem de erro e opção de atualização </br> </ul> |
| Pós-condições | O usuário visualiza lista de atividades realizadas no sistema |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF42](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC16 | Visualizar Notícias |
| ----- | ---------- |
| Descrição | O usuário visualiza notícias e informações do Governo do DF |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário acessa feed de notícias |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Notícias" </br> <li> O sistema exibe feed de notícias atualizadas </br> <li> O usuário seleciona notícia para visualizar detalhes </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário visualiza notícias destacadas na tela inicial </br> <li> O usuário seleciona notícia para visualizar detalhes </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Notícias" </br> <li> O sistema enfrenta problemas de conexão </br> <li> O sistema exibe notícias em cache ou mensagem de erro </br> </ul> |
| Pós-condições | O usuário visualiza notícias e informações do GDF |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF09](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF43](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC17 | Interagir com ChatBot |
| ----- | ---------- |
| Descrição | O usuário interage com assistente virtual para obter informações e ajuda |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário utiliza chatbot para obter informações |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona ícone do chatbot </br> <li> O usuário digita pergunta ou solicitação </br> <li> O sistema fornece resposta automatizada </br> <li> O usuário pode continuar a conversa ou finalizar </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona ícone do chatbot </br> <li> O usuário utiliza comandos de voz </br> <li> O sistema interpreta o comando e responde </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona ícone do chatbot </br> <li> O usuário digita pergunta complexa ou fora do escopo </br> <li> O chatbot não consegue responder </br> <li> O sistema oferece contato com atendimento humano </br> </ul> |
| Pós-condições | O usuário recebe respostas para suas dúvidas |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF17](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF44](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC18 | Visualizar Mapa |
| ----- | ---------- |
| Descrição | O usuário visualiza mapa com serviços públicos e ocorrências |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário explora mapa interativo |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Mapa" </br> <li> O sistema exibe mapa da região </br> <li> O usuário visualiza pontos de interesse e ocorrências </br> <li> O usuário pode selecionar categorias de exibição </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona serviço específico com mapa </br> <li> O sistema exibe mapa focado no serviço selecionado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Mapa" </br> <li> O sistema não consegue carregar o mapa </br> <li> O sistema exibe mensagem de erro e sugestões alternativas </br> </ul> |
| Pós-condições | O usuário visualiza mapa interativo com informações relevantes |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF45](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC19 | Localizar Ocorrência |
| ----- | ---------- |
| Descrição | O usuário localiza ocorrências em mapa interativo |
| Ator | Cidadão |
| Pré-condições | Ocorrência registrada |
| Ação | O usuário visualiza localização de ocorrências |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Ocorrências" </br> <li> O usuário seleciona filtro de ocorrências </br> <li> O sistema exibe mapa com ocorrências filtradas </br> <li> O usuário seleciona ocorrência específica para detalhes </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa "Minhas Ocorrências" </br> <li> O usuário seleciona ocorrência específica </br> <li> O usuário seleciona "Ver no Mapa" </br> <li> O sistema exibe localização da ocorrência </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Ocorrências" </br> <li> O sistema não encontra ocorrências na região </br> <li> O sistema exibe mensagem informativa </br> </ul> |
| Pós-condições | O usuário visualiza ocorrências no mapa |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF30](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF45](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC20 | Localizar Serviços |
| ----- | ---------- |
| Descrição | O usuário localiza pontos de serviço público no mapa |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O usuário visualiza serviços públicos em mapa |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Mapa" </br> <li> O usuário seleciona categoria de serviço desejada </br> <li> O sistema exibe pontos de serviço no mapa </br> <li> O usuário seleciona ponto específico para detalhes </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário utiliza a barra de pesquisa </br> <li> O usuário busca por tipo de serviço </br> <li> O sistema exibe resultados </br> <li> O usuário seleciona "Ver no Mapa" </br> <li> O sistema exibe serviços no mapa </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Mapa" </br> <li> O usuário seleciona categoria de serviço </br> <li> O sistema não encontra serviços próximos </br> <li> O sistema exibe mensagem e sugestão de ampliar busca </br> </ul> |
| Pós-condições | O usuário visualiza serviços públicos no mapa |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF45](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC21 | Gerenciar Conta |
| ----- | ---------- |
| Descrição | O usuário gerencia configurações e dados da sua conta |
| Ator | Cidadão |
| Pré-condições | Login realizado |
| Ação | O usuário acessa e modifica configurações da conta |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Minha Conta" ou ícone de perfil </br> <li> O sistema exibe opções de gerenciamento </br> <li> O usuário seleciona opção desejada </br> <li> O usuário realiza alterações </br> <li> O usuário confirma as alterações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa área específica (ex: notificações) </br> <li> O usuário seleciona configurações da área </br> <li> O usuário realiza alterações específicas </br> <li> O usuário confirma as alterações </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Minha Conta" </br> <li> O usuário tenta alterar informações protegidas </br> <li> O sistema exibe aviso de restrição </br> </ul> |
| Pós-condições | Alterações realizadas e salvas na conta do usuário |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC22 | Cadastrar Usuário |
| ----- | ---------- |
| Descrição | Novo usuário realiza cadastro no sistema |
| Ator | Cidadão |
| Pré-condições | Nenhuma |
| Ação | O cidadão cria uma nova conta no sistema |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Cadastrar" </br> <li> O usuário preenche dados pessoais </br> <li> O usuário cria senha </br> <li> O usuário aceita termos de uso </br> <li> O sistema valida os dados </br> <li> O sistema confirma cadastro </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Cadastrar com gov.br" </br> <li> O sistema redireciona para autenticação gov.br </br> <li> O usuário autoriza compartilhamento de dados </br> <li> O sistema confirma cadastro </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Cadastrar" </br> <li> O usuário preenche dados com inconsistências </br> <li> O sistema exibe erros de validação </br> <li> O usuário corrige os dados </br> </ul> |
| Pós-condições | Nova conta criada e usuário pode realizar login |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF01](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC23 | Editar Perfil |
| ----- | ---------- |
| Descrição | O usuário edita informações do seu perfil |
| Ator | Cidadão |
| Pré-condições | Login realizado |
| Ação | O usuário atualiza dados do perfil |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Minha Conta" </br> <li> O usuário seleciona "Editar Perfil" </br> <li> O usuário modifica informações desejadas </br> <li> O usuário salva alterações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona ícone de perfil </br> <li> O usuário seleciona opção de edição </br> <li> O usuário atualiza informações </br> <li> O usuário salva alterações </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Minha Conta" </br> <li> O usuário seleciona "Editar Perfil" </br> <li> O usuário insere dados inválidos </br> <li> O sistema exibe mensagens de erro </br> <li> O usuário corrige os dados </br> </ul> |
| Pós-condições | Perfil atualizado com novas informações |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>
| UC24 | Autenticar Usuário |
| ----- | ---------- |
| Descrição | O sistema autentica as credenciais do usuário |
| Ator | Cidadão |
| Pré-condições | Dados de login informados |
| Ação | O sistema valida credenciais e autentica o usuário |
| Fluxo principal | <ul><li> O usuário insere credenciais </br> <li> O sistema valida as informações </br> <li> O sistema autentica o usuário </br> <li> O sistema direciona para área logada </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário seleciona autenticação biométrica </br> <li> O sistema valida biometria </br> <li> O sistema autentica o usuário </br> <li> O sistema direciona para área logada </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário insere credenciais </br> <li> O sistema detecta credenciais inválidas </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema oferece recuperação de senha </br> </ul> |
| Pós-condições | Usuário autenticado no sistema |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF01](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF23](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>
| UC25 | Emitir IPVA |
| ----- | ---------- |
| Descrição | O usuário emite guia de pagamento do IPVA |
| Ator | Cidadão, Sistema Tributário |
| Pré-condições | Login realizado |
| Ação | O usuário gera documento de IPVA |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "IPVA" </br> <li> O usuário informa placa e RENAVAM do veículo </br> <li> O sistema exibe informações do débito </br> <li> O usuário seleciona opção de pagamento </br> <li> O sistema gera guia de pagamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário busca por "IPVA" </br> <li> O usuário seleciona veículo já cadastrado </br> <li> O sistema exibe informações do débito </br> <li> O usuário seleciona opção de pagamento </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "IPVA" </br> <li> O usuário informa dados incorretos </br> <li> O sistema exibe mensagem de erro </br> <li> O usuário corrige os dados </br> </ul> |
| Pós-condições | Guia de pagamento do IPVA gerada |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF24](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF41](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC26 | Emitir IPTU |
| ----- | ---------- |
| Descrição | O usuário emite guia de pagamento do IPTU |
| Ator | Cidadão, Sistema Tributário |
| Pré-condições | Login realizado |
| Ação | O usuário gera documento de IPTU |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "IPTU" </br> <li> O usuário informa inscrição do imóvel </br> <li> O sistema exibe informações do débito </br> <li> O usuário seleciona opção de pagamento </br> <li> O sistema gera guia de pagamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário busca por "IPTU" </br> <li> O usuário seleciona imóvel já cadastrado </br> <li> O sistema exibe informações do débito </br> <li> O usuário seleciona opção de pagamento </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "IPTU" </br> <li> O usuário informa dados incorretos </br> <li> O sistema exibe mensagem de erro </br> <li> O usuário corrige os dados </br> </ul> |
| Pós-condições | Guia de pagamento do IPTU gerada |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF41](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC27 | Emitir DAR |
| ----- | ---------- |
| Descrição | O usuário emite Documento de Arrecadação |
| Ator | Cidadão, Sistema Tributário |
| Pré-condições | Login realizado |
| Ação | O usuário gera DAR para pagamento de taxas e tributos |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "Emitir DAR" </br> <li> O usuário seleciona tipo de receita </br> <li> O usuário preenche informações necessárias </br> <li> O sistema calcula valores </br> <li> O sistema gera DAR para pagamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário busca por "DAR" ou "taxa" </br> <li> O usuário seleciona "Emitir DAR" </br> <li> O usuário segue o fluxo de emissão </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "Emitir DAR" </br> <li> O usuário preenche informações incompletas </br> <li> O sistema exibe mensagem de erro </br> <li> O usuário completa as informações </br> </ul> |
| Pós-condições | DAR emitido para pagamento de taxa ou tributo |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF41](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC28 | Emitir Certidão Negativa |
| ----- | ---------- |
| Descrição | O usuário emite certidão negativa de débitos |
| Ator | Cidadão, Sistema Tributário |
| Pré-condições | Login realizado |
| Ação | O usuário gera certidão negativa |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "Certidão Negativa" </br> <li> O usuário informa CPF/CNPJ para consulta </br> <li> O sistema verifica situação fiscal </br> <li> O sistema gera certidão negativa </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário busca por "certidão" </br> <li> O usuário seleciona "Certidão Negativa" </br> <li> O usuário segue o fluxo de emissão </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Serviços Tributários" </br> <li> O usuário seleciona "Certidão Negativa" </br> <li> O sistema verifica existência de débitos </br> <li> O sistema exibe informações sobre pendências </br> <li> O sistema oferece opções de regularização </br> </ul> |
| Pós-condições | Certidão negativa emitida em formato digital |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [RF41](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


| UC29 | Personalizar Acessibilidade |
| ----- | ---------- |
| Descrição | O usuário personaliza configurações de acessibilidade para melhor experiência de uso |
| Ator | Cidadão |
| Pré-condições | Acesso ao aplicativo |
| Ação | O usuário customiza opções de acessibilidade |
| Fluxo principal | <ul><li> O usuário acessa as configurações do aplicativo </br> <li> O usuário seleciona "Acessibilidade" </br> <li> O usuário ajusta tamanho da fonte </br> <li> O usuário ajusta contraste de cores </br> <li> O usuário ativa modo escuro </br> <li> O sistema salva as preferências </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário busca por "acessibilidade" </br> <li> O usuário seleciona "Configurações de Acessibilidade" </br> <li> O usuário segue o fluxo de personalização </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa as configurações </br> <li> O usuário seleciona "Acessibilidade" </br> <li> O usuário tenta ajustar configurações </br> <li> O sistema não consegue salvar as preferências </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema sugere tentar novamente ou restaurar configurações padrão </br> </ul> |
| Pós-condições | Interface adaptada conforme preferências de acessibilidade do usuário |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF07](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF12](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RNF05](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RNF17](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RNF18](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>



| UC30 | Gerenciar Notificações |
| ----- | ---------- |
| Descrição | O usuário configura e gerencia suas preferências de notificações |
| Ator | Cidadão |
| Pré-condições | Login realizado |
| Ação | O usuário personaliza suas configurações de notificações |
| Fluxo principal | <ul><li> O usuário acessa configurações do perfil </br> <li> O usuário seleciona "Gerenciamento de Notificações" </br> <li> O usuário configura notificações por localização </br> <li> O usuário configura notificações por categoria </br> <li> O usuário configura notificações de vencimentos </br> <li> O sistema salva as preferências </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o menu principal </br> <li> O usuário busca por "notificações" </br> <li> O usuário seleciona "Configurar Notificações" </br> <li> O usuário segue o fluxo de configuração </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa configurações do perfil </br> <li> O usuário seleciona "Gerenciamento de Notificações" </br> <li> O sistema detecta restrições de permissão </br> <li> O sistema solicita autorização para enviar notificações </br> <li> O usuário nega permissão </br> <li> O sistema informa limitações de funcionalidade </br> </ul> |
| Pós-condições | Preferências de notificação configuradas e ativas |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF03](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF14](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF18](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


| UC31 | Utilizar Assistente Virtual |
| ----- | ---------- |
| Descrição | O usuário interage com assistente virtual por comandos de voz |
| Ator | Cidadão |
| Pré-condições | Aplicativo instalado |
| Ação | O usuário utiliza comandos de voz para navegação e operações |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário ativa o assistente virtual (ícone de microfone) </br> <li> O usuário emite comando de voz </br> <li> O sistema processa o comando </br> <li> O sistema executa a ação solicitada </br> <li> O sistema confirma a ação por áudio </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário pressiona e segura o botão de menu </br> <li> O assistente virtual é ativado automaticamente </br> <li> O usuário emite comando de voz </br> <li> O sistema executa a solicitação </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário ativa o assistente virtual </br> <li> O usuário emite comando de voz </br> <li> O sistema não reconhece o comando </br> <li> O sistema solicita que o usuário repita o comando </br> <li> Após três tentativas sem sucesso, o sistema sugere usar a interface visual </br> </ul> |
| Pós-condições | Ação solicitada por voz é executada pelo sistema |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF05](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC32 | Gerenciar Documentos |
| ----- | ---------- |
| Descrição | O usuário gerencia documentos digitais e comprovantes |
| Ator | Cidadão, Sistema de Governo do DF |
| Pré-condições | Login realizado |
| Ação | O usuário acessa, gera e compartilha documentos digitais |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Meus Documentos" </br> <li> O usuário visualiza lista de documentos disponíveis </br> <li> O usuário seleciona um documento </br> <li> O usuário escolhe gerar/visualizar/compartilhar o documento </br> <li> O sistema executa a ação solicitada </br> </ul> |
| Fluxo alternativo | <ul><li> Após realizar um agendamento ou serviço </br> <li> O sistema oferece opção de salvar comprovante </br> <li> O usuário confirma a ação </br> <li> O documento é adicionado à biblioteca de documentos </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa "Meus Documentos" </br> <li> O usuário tenta gerar um relatório/comprovante </br> <li> O sistema identifica falha na geração </br> <li> O sistema informa o erro </br> <li> O sistema oferece alternativas para obtenção do documento </br> </ul> |
| Pós-condições | Documento visualizado, gerado ou compartilhado com sucesso |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF10](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF19](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC33 | Gerenciar Solicitações de Serviços |
| ----- | ---------- |
| Descrição | O usuário solicita e acompanha serviços públicos |
| Ator | Cidadão, Sistema de Governo do DF |
| Pré-condições | Login realizado |
| Ação | O usuário solicita serviços públicos e acompanha sua execução |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Solicitar Serviços" </br> <li> O usuário escolhe categoria de serviço </br> <li> O usuário preenche informações necessárias </br> <li> O usuário seleciona localização no mapa </br> <li> O usuário confirma solicitação </br> <li> O sistema registra e envia a solicitação </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa "Minhas Solicitações" </br> <li> O usuário visualiza lista de solicitações anteriores </br> <li> O usuário seleciona uma solicitação </br> <li> O usuário verifica status ou confirma resolução </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta solicitar um serviço </br> <li> O sistema identifica falta de informações ou erros </br> <li> O sistema sinaliza campos obrigatórios </br> <li> O sistema orienta o preenchimento correto </br> </ul> |
| Pós-condições | Solicitação registrada ou status atualizado |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF29](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF30](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF31](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF32](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC34 | Usar Recursos Educacionais Avançados |
| ----- | ---------- |
| Descrição | O usuário acessa funcionalidades avançadas da área educacional |
| Ator | Cidadão, Sistema Educacional |
| Pré-condições | Login realizado, perfil vinculado ao sistema educacional |
| Ação | O usuário acessa informações e gerencia pendências educacionais |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Educação" </br> <li> O usuário escolhe "Área do Professor" ou "Área do Aluno" </br> <li> O usuário visualiza calendário e pendências acadêmicas </br> <li> O usuário seleciona pendência para mais detalhes </br> <li> O sistema exibe informações detalhadas </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa "Calendário Escolar" </br> <li> O usuário visualiza eventos programados </br> <li> O usuário seleciona data específica </br> <li> O usuário visualiza pendências associadas à data </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta acessar área educacional </br> <li> O sistema identifica perfil não vinculado a sistema educacional </br> <li> O sistema informa necessidade de vínculo </br> <li> O sistema orienta processo de vinculação </br> </ul> |
| Pós-condições | Informações educacionais acessadas e pendências visualizadas |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF25](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC35 | Interagir com Mapas Avançados |
| ----- | ---------- |
| Descrição | O usuário utiliza funcionalidades avançadas de mapas |
| Ator | Cidadão |
| Pré-condições | Acesso ao aplicativo, permissão de localização |
| Ação | O usuário interage com mapas para reportar problemas e localizar serviços |
| Fluxo principal | <ul><li> O usuário acessa o menu principal </br> <li> O usuário seleciona "Mapa Interativo" </br> <li> O usuário visualiza mapa da cidade </br> <li> O usuário seleciona ponto específico no mapa </br> <li> O usuário escolhe "Reportar Problema" </br> <li> O usuário preenche informações sobre o problema </br> <li> O sistema registra a ocorrência </br> </ul> |
| Fluxo alternativo | <ul><li> Durante processo de solicitação de serviço </br> <li> O usuário é direcionado para seleção de local no mapa </br> <li> O usuário seleciona ponto exato da ocorrência </br> <li> O sistema registra coordenadas geográficas </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta acessar mapa interativo </br> <li> O sistema detecta permissão de localização negada </br> <li> O sistema solicita autorização para acesso à localização </br> <li> O sistema informa limitações de funcionalidade sem a permissão </br> </ul> |
| Pós-condições | Problema reportado ou local selecionado no mapa |
| Data de Criação | 15/05/2025 |
| Rastreabilidade | [RF26](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [RF30](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

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
