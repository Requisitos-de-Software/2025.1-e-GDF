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

<a href="https://ibb.co/Ndm9236c"><img src="https://i.ibb.co/v6W1Qfjz/Diagrama-de-Casos-de-Uso-drawio.png" alt="Diagrama-de-Casos-de-Uso-drawio" border="0" /></a>


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


<font size="3"><p style="text-align: center"> Disponível de forma online em PDF:  [Clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Diagrama%20de%20Casos%20de%20Uso.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22P%C3%A1gina-1%22%20id%3D%2234NzMq-ass0gtIXJ2DlH%22%3E7V1rc9q6Fv01%2BZiOLb8%2FUpI%2BZtpzMqGnp71f7jggwL0GcWyTJufXX8lPvC0SYZCwiTvTFgtjhNfa23svbUlXxnj19DHyN8uvZIbDK6TNnq6MmyuEDMvy6H%2Bs5Tlr0S3DzVoWUTDL26qGSfAvzhu1vHUbzHBcOzEhJEyCTb1xStZrPE1qbX4Ukd%2F10%2BYkrH%2Frxl%2FgRsNk6ofN1r%2BDWbLMWl3kVO2fcLBYFt%2Bs2%2FkvXvnFyfkviZf%2BjPzeaTJur4xxREiSvVo9jXHI7l5xX7LPfdjzbtmxCK8TkQ%2Fc6Ukyjn7cbL79s%2F386ZP99BR%2FuUbZVR79cJv%2F4Ctkh%2FR672fBI325YC%2BLpjmh30R%2FSAGS%2Fc%2BWdf69Ub2EH3mIYAvtYHadRjPnG4dODJ0YOjF0YuhE3zvBvWKP%2Bj90YujE0ImhE0Mnhk4MnRg6MXRi6MTQiaETQyeGTrzJTrye0Keid%2FJcKOkR2a5nmInRGn379zJI8GTjT9m7vyN%2FQ9uWySqkR3r56V1xO9e7H3GU4Kedplzs%2FojJCifRMz0lf%2Fdat3PlPR97MNz8%2BHcl5HvFOMNyR8RHjpO3%2BvnowaK8eiWw0xe5xn6A3m7s1dsLUMsbVkDJ3rjOsB7RE3R385TddAD1PfbD4F%2BfwqJ9IYtgTf%2BfBKtNGMyDqT8je3EHMNEfEWxirAYi16ohZGlWAyHd4iDkysLHlonPFD9gBs8fJElBuRobVyOH%2FfvewjG7mSRDb5oiWb09MroJn67VLUx39aaJ6Y5KAB15AI7JOt6GSWphowVez%2FwVvXeEATemL6IUtBk77iRUdVOzOUghTSVSrjyk%2FkqCwhWO4jiIE3rjMD34HkTJ1g9LS%2FtO%2Fu0kWMAt6rp3brPy5IHVDChGUxzHKXrftgmJAj9gNnbnxzFhv616LRzbnNXy9LqTdHiWxwtDpIFZfJkiNH9t48xpfvNX%2FnrJMJwxa%2FxAMqtkf6lvpQ40Zse9ANWrY%2BoijoG6SjHVlWKaBI8ppF8Jiyy123i6jfpikAA7j4edpxQ7tBe75q08Gs2POEqhu8ehn6TBpxEFaRSTGeJqE5FHn5pm3E88de3soY0uMc3jGGOY5JB%2BngVkxZ6PqVGOaO439aml9sUwG2GPdu6wRzdVAnmHo5isyyz%2BLsJzmi%2By%2FG%2B0ngZ%2BXDw46XnzIOwLqMA6EUeFKZUaNaBaKkGt0v6veB37NG9kOMbkIUozEkyRLdLIXuAJE0lqkBx3aygFVKJq81J28nk9J9GqKeOkRrqjENAfdY%2F93eN%2BIG0ApA2nKc8ZhTUta1XQ0qCWqO80YaFZyTxYbLOH6yuq3dhP8IIlq701ZJtnyGoTU4maEA%2FdFb2DSRAuGb4fJn74%2BKJZf15RpJM%2BRca6jt4BkC0eyGqzHaVa0q5oO%2FZD6oNTXHWa8tCWLzgLj9PU57u%2F6K3xVnHx2RQItD%2BLlfIUZta7XmaRcgFrGSffzrZTfxrQaDrVDruJIRAGKzs8WySF9ieuEpSIe5w61CzXIQ8hXqXYPQYshf3qb%2FzUGbPkNrfSvTCebpT6rONnSLPObsVKM94qlp5sGReYG%2FYZ0n%2FF210%2F3U37heiZPCVRqV6BlKa2ExIG0yAz4AmOHoMsZEq1xLs0cBo90DN6m9oii6dVqAVUaWpbVB5AQNlhjnWqLK5J6aB7CazuGWd%2F0ipNZGvR0iTxk22qU6SP2wJZmO%2F0BFnggx2bg6xS8R8pTmLX84BmqwzYexyTcAvKhnLJuIqv%2Bomr6xrnxlVp3nr7NA23AUP1JqspKofJ%2B%2Bp0kcd5mqqF0JA4SD4OZv7swGK9eOlv2MvtKhxNExLRc9gNDuhT%2BIv%2FgMM7EgcJTWLpKQ8kSchq54RRGCzYGwkB2JFtEgZrPC4XxNBOBKjp1G1SN3maAw%2FQcjj99IjuFx0eyjCVFYClw6L4%2BuPNhx1wHvYiQ%2B9JUr%2Btfn6%2Fp6yWLOIAsQpms3CfbdWLnxkp8qVOaL51EnR016yBY4hqCbY0aCTmIqMtK%2Bmjd585yEwv%2BEge3zGPqNFQJ30WTsl6ifPBNdrwwZ8GfthFT2nCKmhe%2FYKp1E%2FKzTr8FbuJYfMoWOcPvbyx%2FoGDHnU7EEFDLV1pyHzse3%2F6v0VqnmMSMhd8syZrBjxez0ZsASHaQjZ4nbV8CNidTI2YRs%2FL1KL1hn3vJUVMttEUv3Tns%2FNoTr3AiYBx4Vlt%2BaK9HNPe6brh1WhWrP3DG4ePWG1Q8IhrnefRLP%2FCOxKktCj4jupPChPOp8juQ%2F6piqyNC1lAIjUscKHsRjUuRIHzn3dO27ATYv5XFeeQ%2BTzGtauktlPeyyPMSWKu1z6z65QL9ECsyEvj1Aqhhtw07uJ9IJsR8fxj9%2BAnO3hnFYc3T7tv3jwf7TsLSeV15%2Bl02XkacFioLLA51HuWKtfeK%2FXCfRahz6CBHuFhLR14WI3nYZVq26bakvULlUBh9sBVytTWs5tKy58vrZ4dAsov2UFKAZU7rLg3FrplM%2Fdm%2BAKCoacg%2BbHzeicUokdVJMQOikCoDKB0VQGUKZp9FnV63QygTAfVDciFhiEaQJXpZnklqJb1I4BSOoh86DTpjntjOLuIK6wqrZI15Q4dX743PsJD2qIe0u6yh7RNQOqy4WAPqcMrGb30kErH7HdnkCQ4mjP3VVuspS85JXg8cmdBq00p5Y7RX75rbBt0tglwj3DDrqgb1rrshl2gz3mW2c4LIzilvZfDJJZE2aCqASjGiS%2BwQqPclaQYSLY4y2mprc8oGC0X07TEbd%2F8vDcAtG7xFghSjLREjQggTW9IeMwaaf3G2uXNEVGMtUxBgWLpGdEix3TvXIKLBhnZvJkHikGWKDNUBl1N1BOuzeo3suj8RZNF%2BFpDFuaRVQ6RZxU7N4svbuu12N8Af15MBdjBHY4C%2BvtYbeWZCgiK8uDXCwiuxLKKHYh5q5hap0kjrg0o51htKwauYSahm4KpxKmSAJs3KHxqbgoOvADi8Rj9UkrMjiCpjyCnJUhOq1vsdMECQK2lRljNYkH%2FKJuZvPR08JriXlNUElfkNRGsjjIKhA%2BuUgU%2Bs6FvymYmL8kemCnOTNHhbFXMBAvXM262YyaCzITOVzYzeaLAwExxZnrdYqYOV%2FPzrJbMbCwdr6t2mjwN4whqtuSQJEoroKbw2IqqLAhOT7TgULRwFgQiA92A81dkc5MnvQzcPICbere4iQA3kdY21oT1Fo1UXzY1eZUSAzUPoCbqGDWheOS4LanZ8Jqqg01e8cdAzQOo2S3l6LqRvjhGS2rakJqKtaPC%2FQ%2FUbEtNs2PUhInQ4dQ81xPcObHC%2Fva4KDr3XlXiA1NpR2vpJq%2Bhw7UUJ%2BXFzI2Tc%2FOdxu5fbTTHM8%2FD0FOPCwnTtmv6e2PUsm3g2biQ4nTdOfHI0NvzqKIT8s8kwOsOAowSFuDrqzLpbkENVdQ88dDQ26NmxxR4qCRV5YBHKklIc0BvZFNzEOCPo2ZxvzpDTThsqbX2mnD801RMzUF%2FP5KaHVOSDMgoDU7kFk6RQLCJnCJ4UcXNQYA%2Fkptdk5Lg2FCj8LftE90zFVNzEOCPpGbHlKUGNc22hcVwHUdkq6VmoWMN1GxLzY6pR1D0bE4qbyt6GshSzM1BkD%2BSmx2TjxrcbAw3tuamqdpvooGbx3Gza7XFsOrdbJukg6p3w%2FIUU3NQ3Y%2BkZsekzUaSjlq7TRNyU57bTH7e%2F5wbt59D%2F9fSnW2%2Fr57%2FGBdrhkimJo9kh05IazNBrj03deFJbN1K0uF4kNXWacI9P%2FXG0viSmanGafaPmaILu3WMmOBp3pitK%2F4wr1%2FIg%2BVMkmmpZpjygmnZLeUIBod2W7ldR415QoqZqWaUsn%2FM1EV3W%2BiYxzQblZsaiA2FuWk2Kt7lLZbA5eaJhykvZq2EomjjdW52SzmCA%2BiWBS4hLrfDONMTXLn6VNQ88VDQxVCzuA99oybwmsgw2npNDSpQumJqFqYxcHPPRjt9izbhctbIhFKkMDktD5JT3uwMPjlVrOXRR3IawvFmt0Yq4UIHJkKtPacF4wPV5FSxnEcfyWmKau4dIydcU8vw4Ni3uLAJyenIm%2F7LJ%2BeZ1n6%2FmA0bT2iNEjd5FN2jqGBfN5d%2BN6G1NJYYEX8qwKxRdLWSs63%2Bzh8y40Xlg%2FlK329VrWqIRHduKJ6o3TRfkA0bZtviM9t77Ur9MF6kIDDkhXiHz7xV%2BrQSrsXolthz3VidzXbdlo8nQHDRLYhPxsyhSujICZBdK2CDaxTYVktqovrjQrcUJyxI7q6qb2NfaxNOUbA522OUZRKn3oSMj6vS7TYvdl9rqMSW5rkbz7lKgT3x1Ls%2Byl8vMr538hecMec6reUvOKrlCG6EebKniZrJd2cmmnD9aLeI5qJ9T6nj5R4HLsEsu4JUb%2FKK3uVJfkiiZEkWbD%2Bf26oVkKs65wthG%2FGk%2FPuFk%2BR5kj4Cb%2FxtQursLJxl5SB%2F7rxzhEwhzLMXT3yVZ8IEEn1CPV8vN5P%2F3N0%2FXv%2B9cv4c%2FRe9%2F%2FM7t%2B580NA6rKEB3rQU1YTZar8YcqnV0OBa8s0NXYSLlx3rlSt1TUTjGq%2FE7U%2FfhPH2xQitLhkhzLJaV2rbCBihDefI9MIIeeU3b2Ej%2BEZizrGCvZyFG8F7KjeC58IoV1p7A%2FvAF%2BG2dGf6khUK7vPQEV%2FqADXBa7vTHZw907jQmT0pPYwIs4nqdOpVll%2FJDLMz%2Fg8%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E) </p></font>

## Especialização de caso de uso 

# Casos de Uso – Sistema e-GDF

| UC01 | Realizar Login Simplificado |
| ----- | ---------- |
| Descrição | O usuário realiza login de forma simples e rápida no aplicativo |
| Ator | Cidadão |
| Pré-condições | Possuir cadastro no sistema |
| Ação | O usuário efetua login no aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário insere suas credenciais </br> <li> O usuário seleciona "Entrar" </br> <li> O sistema valida as credenciais </br> <li> O sistema redireciona para a página inicial </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O sistema redireciona para a plataforma gov.br </br> <li> O usuário realiza autenticação </br> <li> O sistema redireciona para a página inicial </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário insere credenciais inválidas </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema solicita que o usuário insira novamente as credenciais </br> </ul> |
| Pós-condições | Usuário autenticado no sistema |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR01, AD01](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg) , 2025).</p></font>

| UC02 | Acessar Interface Simplificada |
| ----- | ---------- |
| Descrição | O usuário acessa funcionalidades do aplicativo mesmo com pouca familiaridade com tecnologia |
| Ator | Cidadão, Usuário com Necessidades de Acessibilidade |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário navega pela interface simplificada |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema exibe interface simplificada com ícones grandes e descritivos </br> <li> O usuário seleciona a funcionalidade desejada </br> <li> O sistema exibe instruções claras de uso </br> <li> O usuário realiza a ação desejada com facilidade </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo pela primeira vez </br> <li> O sistema detecta que é o primeiro acesso </br> <li> O sistema oferece tutorial inicial de navegação </br> <li> O usuário segue o tutorial </br> <li> O sistema exibe interface simplificada </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário não consegue localizar a funcionalidade desejada </br> <li> O sistema oferece opção de ajuda contextual </br> <li> O usuário seleciona ajuda </br> <li> O sistema exibe instruções específicas </br> </ul> |
| Pós-condições | Usuário consegue navegar e utilizar o aplicativo facilmente |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR02](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg) , 2025).</p></font>

| UC03 | Receber Notificações por Localização |
| ----- | ---------- |
| Descrição | O usuário recebe notificações personalizadas com base em sua localização |
| Ator | Cidadão, Sistema de Notificações, Sistema de Geolocalização |
| Pré-condições | Ter o aplicativo instalado e permissões de localização ativadas |
| Ação | O usuário recebe notificações relevantes baseadas em sua localização |
| Fluxo principal | <ul><li> O usuário ativa os serviços de localização </br> <li> O sistema detecta a localização do usuário </br> <li> O sistema identifica serviços/informações relevantes para a região </br> <li> O sistema envia notificações personalizadas </br> <li> O usuário visualiza as notificações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa as configurações do aplicativo </br> <li> O usuário configura áreas de interesse para notificações </br> <li> O sistema envia notificações quando houver atualizações nas áreas selecionadas </br> <li> O usuário visualiza as notificações </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tem serviços de localização desativados </br> <li> O sistema detecta a ausência de permissão </br> <li> O sistema solicita acesso à localização </br> <li> O usuário nega a permissão </br> <li> O sistema informa que as notificações por localização não estarão disponíveis </br> </ul> |
| Pós-condições | Usuário recebe notificações relevantes baseadas em sua localização |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR03](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg) , 2025).</p></font>

| UC04 | Consultar Agendamentos Centralizados |
| ----- | ---------- |
| Descrição | O usuário consulta agendamentos e serviços em um único local centralizado |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário acessa e visualiza todos seus agendamentos em um local único |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O sistema exibe lista de todos os agendamentos ativos </br> <li> O usuário visualiza detalhes de data, hora e local </br> <li> O usuário seleciona um agendamento específico para mais detalhes </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O usuário utiliza filtros para refinar a busca (por tipo de serviço, por data, etc) </br> <li> O sistema exibe agendamentos filtrados </br> <li> O usuário seleciona o agendamento desejado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O usuário não possui agendamentos ativos </br> <li> O sistema exibe mensagem informativa </br> <li> O sistema oferece opção para realizar novos agendamentos </br> </ul> |
| Pós-condições | Usuário visualiza todos seus agendamentos em um local centralizado |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

| UC05 | Utilizar Assistente Virtual por Voz |
| ----- | ---------- |
| Descrição | O usuário interage com assistente virtual utilizando comandos de voz |
| Ator | Cidadão, Usuário com Necessidades de Acessibilidade |
| Pré-condições | Ter o aplicativo instalado e permissões de microfone ativadas |
| Ação | O usuário utiliza comandos de voz para interagir com o aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário ativa o assistente virtual (ícone de microfone) </br> <li> O sistema aguarda comando de voz </br> <li> O usuário fornece comando por voz </br> <li> O assistente processa e executa a solicitação </br> <li> O sistema fornece resposta por áudio e texto </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário configura o assistente virtual como método padrão de interação </br> <li> O aplicativo inicia com assistente ativo </br> <li> O usuário fornece comandos por voz </br> <li> O assistente executa as ações solicitadas </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário ativa o assistente virtual </br> <li> O usuário fornece comando por voz </br> <li> O sistema não reconhece o comando </br> <li> O sistema solicita que o usuário repita o comando </br> <li> O sistema oferece sugestões de comandos válidos </br> </ul> |
| Pós-condições | Solicitação do usuário processada via comando de voz |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR05, AD05, INT13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

| UC06 | Acessar Tutoriais Passo a Passo |
| ----- | ---------- |
| Descrição | O usuário acessa tutoriais detalhados sobre como usar o aplicativo |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário visualiza tutoriais sobre funcionalidades do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Ajuda" ou "Tutoriais" </br> <li> O sistema exibe lista de tutoriais disponíveis </br> <li> O usuário seleciona um tutorial específico </br> <li> O sistema apresenta instruções passo a passo com imagens </br> <li> O usuário segue as instruções </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa uma funcionalidade pela primeira vez </br> <li> O sistema detecta o primeiro acesso </br> <li> O sistema oferece tutorial contextual </br> <li> O usuário seleciona "Mostrar tutorial" </br> <li> O sistema apresenta instruções específicas daquela funcionalidade </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Ajuda" ou "Tutoriais" </br> <li> O sistema não consegue carregar os tutoriais </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema oferece opção para tentar novamente </br> </ul> |
| Pós-condições | Usuário visualiza e aprende a utilizar as funcionalidades do aplicativo |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

| UC07 | Ajustar Tamanho de Fonte e Contraste |
| ----- | ---------- |
| Descrição | O usuário altera o tamanho da fonte e o contraste de cores do aplicativo |
| Ator | Cidadão, Usuário com Necessidades de Acessibilidade |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário personaliza configurações visuais do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário seleciona "Acessibilidade" </br> <li> O usuário ajusta o tamanho da fonte usando controle deslizante </br> <li> O usuário ajusta o contraste de cores </br> <li> O sistema aplica as configurações imediatamente </br> <li> O usuário confirma as alterações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário utiliza gestos de acessibilidade (ex: pinça para aumentar fonte) </br> <li> O sistema detecta o gesto </br> <li> O sistema ajusta o tamanho da fonte temporariamente </br> <li> O sistema oferece opção para salvar a configuração </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário faz ajustes extremos que prejudicam a visualização </br> <li> O sistema detecta configuração problemática </br> <li> O sistema oferece opção para restaurar configurações padrão </br> </ul> |
| Pós-condições | Aplicativo exibido com o tamanho de fonte e contraste personalizados |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR07, EN08, AD08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

| UC08 | Ativar Modo Escuro |
| ----- | ---------- |
| Descrição | O usuário ativa o modo escuro (dark mode) no aplicativo |
| Ator | Cidadão, Usuário com Necessidades de Acessibilidade |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário alterna entre modo claro e escuro |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário seleciona "Aparência" </br> <li> O usuário alterna o botão para "Modo Escuro" </br> <li> O sistema aplica o tema escuro imediatamente </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário usa gesto rápido/atalho para alternar modo </br> <li> O sistema detecta o gesto/atalho </br> <li> O sistema alterna entre modo claro e escuro </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> Ocorre erro ao carregar preferências de aparência </br> <li> O sistema mantém o modo atual </br> <li> O sistema exibe mensagem de erro </br> </ul> |
| Pós-condições | Aplicativo exibido no modo escuro |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

| UC09 | Gerar Relatórios e Comprovantes |
| ----- | ---------- |
| Descrição | O usuário gera relatórios e visualiza comprovantes de agendamentos |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema e possuir agendamentos realizados |
| Ação | O usuário gera e visualiza documentos comprobatórios |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O usuário seleciona um agendamento específico </br> <li> O usuário seleciona "Gerar Comprovante" </br> <li> O sistema processa a solicitação </br> <li> O sistema exibe o comprovante em formato PDF </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Relatórios" </br> <li> O usuário seleciona o tipo de relatório (por período, por serviço, etc.) </br> <li> O usuário configura os parâmetros do relatório </br> <li> O usuário seleciona "Gerar" </br> <li> O sistema exibe o relatório consolidado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O usuário seleciona "Gerar Comprovante" </br> <li> O sistema não consegue processar a solicitação </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema oferece alternativas para obtenção do comprovante </br> </ul> |
| Pós-condições | Usuário obtém comprovante ou relatório em formato digital |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR11](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>>

| UC10 | Alterar Idioma do Aplicativo |
| ----- | ---------- |
| Descrição | O usuário altera o idioma da interface do aplicativo |
| Ator | Cidadão, Usuário com Necessidades de Acessibilidade |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário seleciona o idioma de preferência |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário seleciona "Idioma" </br> <li> O sistema exibe lista de idiomas disponíveis </br> <li> O usuário seleciona o idioma desejado </br> <li> O sistema aplica o novo idioma imediatamente </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário inicia o aplicativo pela primeira vez </br> <li> O sistema detecta o idioma do dispositivo </br> <li> O sistema pergunta se deve usar o idioma do dispositivo </br> <li> O usuário confirma ou seleciona outro idioma </br> <li> O sistema aplica o idioma selecionado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário seleciona "Idioma" </br> <li> O sistema não consegue carregar a lista de idiomas </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema mantém o idioma atual </br> </ul> |
| Pós-condições | Aplicativo exibido no idioma selecionado pelo usuário |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([João Marcos](https://github.com/JJOAOMARCOSS) , 2025).</p></font>

| UC11 | Personalizar Preferências de Perfil |
| ----- | ---------- |
| Descrição | O usuário personaliza suas preferências e perfil para recomendações de serviços |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário configura preferências para receber recomendações personalizadas |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Perfil" ou "Minha Conta" </br> <li> O usuário seleciona "Preferências" </br> <li> O usuário configura categorias de interesse (saúde, educação, transporte, etc.) </br> <li> O usuário ajusta frequência de recomendações </br> <li> O usuário salva as configurações </br> <li> O sistema confirma as alterações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário conclui um serviço no aplicativo </br> <li> O sistema sugere personalização baseada na atividade recente </br> <li> O usuário aceita sugestões </br> <li> O sistema atualiza preferências automaticamente </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Preferências" </br> <li> O usuário faz alterações </br> <li> O sistema não consegue salvar as configurações </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema mantém configurações anteriores </br> </ul> |
| Pós-condições | Perfil do usuário personalizado para receber recomendações relevantes |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR14](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([João Marcos](https://github.com/JJOAOMARCOSS) , 2025).</p></font>

| UC12 | Receber Mensagens sobre Vencimentos |
| ----- | ---------- |
| Descrição | O usuário recebe mensagens curtas sobre vencimentos e lembretes importantes |
| Ator | Cidadão, Sistema de Notificações |
| Pré-condições | Estar autenticado no sistema e ter notificações ativadas |
| Ação | O usuário recebe alertas sobre prazos e vencimentos |
| Fluxo principal | <ul><li> O sistema identifica prazos próximos (impostos, agendamentos, etc.) </br> <li> O sistema gera notificação com informações essenciais </br> <li> O sistema envia notificação para o dispositivo do usuário </br> <li> O usuário visualiza a notificação </br> <li> O usuário toca na notificação para ver detalhes </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Lembretes" </br> <li> O sistema exibe lista de lembretes ativos </br> <li> O usuário visualiza todos os vencimentos próximos </br> </ul> |
| Fluxo de exceção | <ul><li> O sistema tenta enviar notificação </br> <li> O usuário desativou notificações do aplicativo </br> <li> O sistema registra falha no envio </br> <li> O sistema armazena o lembrete para exibição dentro do aplicativo </br> </ul> |
| Pós-condições | Usuário informado sobre vencimentos e prazos importantes |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR15](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([João Marcos](https://github.com/JJOAOMARCOSS) , 2025).</p></font>

| UC13 | Acessar Informações de Agendamento/Reagendamento |
| ----- | ---------- |
| Descrição | O usuário acessa informações de agendamento e reagendamento de forma centralizada |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário visualiza e gerencia agendamentos em área centralizada |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O sistema exibe lista de agendamentos </br> <li> O usuário seleciona um agendamento específico </br> <li> O sistema exibe detalhes completos </br> <li> O usuário visualiza opções de reagendamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário recebe notificação sobre agendamento </br> <li> O usuário seleciona a notificação </br> <li> O sistema direciona para detalhes do agendamento </br> <li> O usuário visualiza informações e opções disponíveis </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Meus Agendamentos" </br> <li> O usuário tenta reagendar um compromisso </br> <li> O sistema detecta que o prazo para reagendamento expirou </br> <li> O sistema exibe mensagem explicativa </br> <li> O sistema oferece alternativas de contato </br> </ul> |
| Pós-condições | Usuário visualiza ou modifica informações de agendamento |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR17](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

| UC14 | Configurar Notificações por Categorias |
| ----- | ---------- |
| Descrição | O usuário configura a recepção de notificações por categorias específicas como saúde, educação e transporte |
| Ator | Cidadão, Sistema de Notificações |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário personaliza suas preferências de notificações por categoria |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Configurações" </br> <li> O usuário seleciona "Notificações" </br> <li> O sistema exibe as categorias disponíveis </br> <li> O usuário ativa/desativa notificações por categoria </br> <li> O sistema salva as preferências </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário recebe uma notificação </br> <li> O usuário seleciona opção de configurar notificações na própria notificação </br> <li> O sistema direciona para tela de configuração de notificações </br> <li> O usuário ativa/desativa categorias desejadas </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta configurar notificações </br> <li> O sistema detecta falha de conexão </br> <li> O sistema informa ao usuário sobre o problema </br> <li> O sistema sugere tentar novamente quando houver conexão estável </br> </ul> |
| Pós-condições | As preferências de notificação do usuário são atualizadas no sistema |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR19](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

| UC15 | Compartilhar/Salvar Informações Importantes |
| ----- | ---------- |
| Descrição | O usuário compartilha ou salva informações importantes como protocolos ou comprovantes |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema e ter acessado uma informação compartilhável |
| Ação | O usuário compartilha ou salva um documento ou informação relevante |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até documentos/comprovantes </br> <li> O usuário seleciona um item específico </br> <li> O sistema exibe opções de compartilhamento/salvamento </br> <li> O usuário escolhe o método desejado (PDF, compartilhar, salvar) </br> <li> O sistema processa a solicitação </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário recebe confirmação de um serviço </br> <li> O sistema exibe automaticamente opções para salvar/compartilhar </br> <li> O usuário seleciona a opção desejada </br> <li> O sistema finaliza a operação conforme solicitado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta compartilhar/salvar um documento </br> <li> O sistema detecta falta de permissão de armazenamento </br> <li> O sistema solicita permissão de acesso </br> <li> O usuário nega a permissão </br> <li> O sistema informa que não pode prosseguir sem permissão </br> </ul> |
| Pós-condições | O documento/informação é compartilhado ou salvo conforme solicitado |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR20](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

| UC16 | Consultar Calendário Letivo e Vagas |
| ----- | ---------- |
| Descrição | O usuário consulta informações educacionais como calendário letivo e status de vagas no CIL |
| Ator | Cidadão, Aluno/Professor, Sistema Educacional |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário acessa e visualiza informações educacionais centralizadas |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona a área "Educação" </br> <li> O usuário escolhe "Calendário Letivo" ou "Consulta de Vagas" </br> <li> O sistema exibe as informações solicitadas </br> <li> O usuário visualiza os dados detalhados </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário utiliza a barra de pesquisa </br> <li> O usuário digita termos relacionados à educação </br> <li> O sistema exibe resultados relacionados </br> <li> O usuário seleciona o serviço desejado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta consultar vagas no CIL </br> <li> O sistema detecta que o banco de dados educacional está em manutenção </br> <li> O sistema informa o horário previsto para normalização </br> <li> O sistema sugere tentar novamente mais tarde </br> </ul> |
| Pós-condições | O usuário visualiza as informações educacionais solicitadas |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [EN03](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/), [INT07](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Karoline Luz](https://github.com/KarolineLuz), 2025).</p></font>

| UC17 | Autenticar via Gov.br com Reconhecimento Facial |
| ----- | ---------- |
| Descrição | O usuário realiza autenticação segura através da plataforma gov.br, utilizando recursos como reconhecimento facial |
| Ator | Cidadão, Sistema Gov.br |
| Pré-condições | Ter cadastro ativo no gov.br e dispositivo com câmera funcional |
| Ação | O usuário se autentica no sistema utilizando reconhecimento facial via gov.br |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O sistema redireciona para autenticação gov.br </br> <li> O usuário seleciona "Reconhecimento Facial" </br> <li> O sistema ativa a câmera do dispositivo </br> <li> O usuário posiciona o rosto conforme orientação </br> <li> O sistema valida a identidade e autoriza o acesso </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O sistema redireciona para autenticação gov.br </br> <li> O usuário opta por outros métodos de autenticação </br> <li> O sistema processa a autenticação alternativa </br> <li> O usuário é autenticado no sistema </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O usuário tenta usar reconhecimento facial </br> <li> O sistema não consegue validar a identidade após múltiplas tentativas </br> <li> O sistema sugere método alternativo de autenticação </br> <li> O sistema oferece opções de suporte </br> </ul> |
| Pós-condições | O usuário está autenticado com segurança no sistema |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [EN04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Karoline Luz](https://github.com/KarolineLuz), 2025).</p></font>

| UC18 | Acompanhar Pendências Educacionais |
| ----- | ---------- |
| Descrição | O usuário acompanha pendências e atividades relacionadas à área educacional, tanto para professores quanto alunos |
| Ator | Aluno/Professor, Sistema Educacional |
| Pré-condições | Estar autenticado no sistema e ter vínculo com instituição educacional |
| Ação | O usuário visualiza e gerencia pendências educacionais |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona a área "Educação" </br> <li> O usuário escolhe "Minhas Pendências" </br> <li> O sistema exibe lista de pendências classificadas por tipo e prazo </br> <li> O usuário seleciona uma pendência específica </br> <li> O sistema exibe detalhes e possíveis ações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário recebe notificação sobre nova pendência </br> <li> O usuário seleciona a notificação </br> <li> O sistema direciona para detalhes da pendência </br> <li> O usuário visualiza informações e opções disponíveis </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta acessar pendências educacionais </br> <li> O sistema detecta que o perfil educacional não está completamente configurado </br> <li> O sistema solicita informações complementares </br> <li> O sistema orienta sobre como completar o cadastro </br> </ul> |
| Pós-condições | O usuário visualiza e pode interagir com suas pendências educacionais |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [EN06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Karoline Luz](https://github.com/KarolineLuz), 2025).</p></font>

| UC19 | Reportar Problemas via Mapa Interativo |
| ----- | ---------- |
| Descrição | O usuário reporta problemas da cidade através de um mapa interativo |
| Ator | Cidadão, Sistema de Geolocalização, Órgãos Públicos |
| Pré-condições | Estar autenticado no sistema e permitir acesso à localização |
| Ação | O usuário identifica e reporta problemas urbanos utilizando mapa interativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Reportar Problema" </br> <li> O sistema exibe mapa da região atual </br> <li> O usuário seleciona localização do problema no mapa </br> <li> O usuário seleciona categoria do problema </br> <li> O usuário adiciona descrição e/ou foto </br> <li> O usuário confirma o envio </br> <li> O sistema registra e encaminha a solicitação </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário visualiza mapa de problemas já reportados </br> <li> O usuário verifica se o problema já foi reportado </br> <li> O usuário adiciona comentário complementar ao problema existente </br> <li> O sistema atualiza o registro do problema </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta reportar problema via mapa </br> <li> O sistema detecta que o serviço de localização está desativado </br> <li> O sistema solicita permissão de localização </br> <li> O usuário nega a permissão </br> <li> O sistema oferece método alternativo de localização manual </br> </ul> |
| Pós-condições | O problema é registrado no sistema e encaminhado ao órgão responsável |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [EN09](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC20 | Acessar Suporte ao Usuário |
| ----- | ---------- |
| Descrição | O usuário acessa seção de suporte com instruções detalhadas sobre como usar o aplicativo |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário acessa e utiliza recursos de suporte e ajuda |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Ajuda e Suporte" </br> <li> O sistema exibe categorias de suporte disponíveis </br> <li> O usuário seleciona o tópico desejado </br> <li> O sistema exibe instruções detalhadas </br> <li> O usuário navega pelo conteúdo de ajuda </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário utiliza a barra de pesquisa de ajuda </br> <li> O usuário digita sua dúvida ou palavra-chave </br> <li> O sistema exibe resultados relacionados </br> <li> O usuário seleciona o item mais relevante </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta acessar suporte </br> <li> O usuário não encontra resposta para sua dúvida </br> <li> O sistema oferece opção de contato direto com suporte </br> <li> O usuário seleciona método de contato preferido </br> <li> O sistema direciona para canal de atendimento </br> </ul> |
| Pós-condições | O usuário obtém ajuda ou informações sobre como utilizar o aplicativo |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [EN11](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC21 | Solicitar Serviços Públicos |
| ----- | ---------- |
| Descrição | O usuário solicita serviços públicos como coleta de lixo, reparo de vias e outros |
| Ator | Cidadão, Órgãos Públicos |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário solicita serviços públicos através do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Solicitar Serviços" </br> <li> O sistema exibe categorias de serviços disponíveis </br> <li> O usuário seleciona o tipo de serviço desejado </br> <li> O usuário fornece informações necessárias (local, descrição) </br> <li> O usuário confirma a solicitação </br> <li> O sistema registra e encaminha ao órgão responsável </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona serviço recente ou frequente </br> <li> O sistema pré-preenche informações com base em solicitações anteriores </br> <li> O usuário ajusta detalhes conforme necessário </br> <li> O usuário confirma a solicitação </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta solicitar um serviço </br> <li> O sistema detecta que o serviço está temporariamente indisponível </br> <li> O sistema informa motivo e previsão de retorno </br> <li> O sistema sugere serviços alternativos relacionados </br> </ul> |
| Pós-condições | A solicitação é registrada e encaminhada ao órgão responsável |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [AD02](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC22 | Localizar Serviço Solicitado no Mapa |
| ----- | ---------- |
| Descrição | O usuário utiliza mapa para localizar onde foi solicitado o serviço |
| Ator | Cidadão, Sistema de Geolocalização |
| Pré-condições | Estar autenticado no sistema e ter solicitações ativas |
| Ação | O usuário visualiza no mapa as solicitações feitas |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Minhas Solicitações" </br> <li> O sistema exibe lista de solicitações ativas </br> <li> O usuário seleciona "Ver no Mapa" </br> <li> O sistema exibe mapa com localização das solicitações </br> <li> O usuário seleciona um ponto específico para ver detalhes </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Mapa de Serviços" </br> <li> O sistema exibe mapa com todos os serviços na região </br> <li> O usuário utiliza filtros para visualizar apenas suas solicitações </br> <li> O sistema atualiza o mapa conforme filtros aplicados </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta visualizar solicitações no mapa </br> <li> O sistema detecta que não há solicitações ativas </br> <li> O sistema exibe mensagem informativa </br> <li> O sistema oferece opção de fazer nova solicitação </br> </ul> |
| Pós-condições | O usuário visualiza a localização geográfica de suas solicitações |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [AD03](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC23 | Acompanhar Status das Solicitações |
| ----- | ---------- |
| Descrição | O usuário visualiza e acompanha o status das suas solicitações de serviços |
| Ator | Cidadão, Órgãos Públicos |
| Pré-condições | Estar autenticado no sistema e ter solicitações registradas |
| Ação | O usuário acompanha o andamento de suas solicitações |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Minhas Solicitações" </br> <li> O sistema exibe lista de solicitações com status atual </br> <li> O usuário seleciona uma solicitação específica </br> <li> O sistema exibe histórico detalhado e status atual </br> <li> O usuário visualiza previsão de atendimento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário recebe notificação de atualização de status </br> <li> O usuário seleciona a notificação </br> <li> O sistema direciona para detalhes da solicitação atualizada </br> <li> O usuário visualiza novo status e informações </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta acessar detalhes de uma solicitação </br> <li> O sistema detecta problema na recuperação de informações </br> <li> O sistema informa o problema e sugere tentar novamente </br> <li> O sistema oferece canal alternativo de consulta </br> </ul> |
| Pós-condições | O usuário visualiza informações atualizadas sobre suas solicitações |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [AD04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC24 | Confirmar Resolução de Problemas |
| ----- | ---------- |
| Descrição | O usuário confirma a resolução de problemas relatados anteriormente |
| Ator | Cidadão, Órgãos Públicos |
| Pré-condições | Estar autenticado no sistema e ter solicitações em status "Concluído" |
| Ação | O usuário valida se o problema foi efetivamente resolvido |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Minhas Solicitações" </br> <li> O sistema exibe solicitações marcadas como "Concluídas" </br> <li> O usuário seleciona uma solicitação específica </br> <li> O usuário avalia se o problema foi resolvido </br> <li> O usuário confirma a resolução ou reporta pendência </br> <li> O sistema registra a avaliação do usuário </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário recebe notificação solicitando confirmação </br> <li> O usuário seleciona a notificação </br> <li> O sistema direciona para avaliação da solicitação </br> <li> O usuário confirma resolução ou indica pendências </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta confirmar resolução </br> <li> O usuário indica que o problema não foi resolvido </br> <li> O sistema solicita detalhes sobre a pendência </br> <li> O usuário fornece informações complementares </br> <li> O sistema reabre a solicitação com as novas informações </br> </ul> |
| Pós-condições | O status da solicitação é atualizado com o feedback do usuário |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [AD06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

| UC25 | Excluir Dados e Conta |
| ----- | ---------- |
| Descrição | O usuário exclui seus dados pessoais e conta do aplicativo |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário solicita e confirma a exclusão de sua conta e dados pessoais |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Configurações" </br> <li> O usuário seleciona "Privacidade e Dados" </br> <li> O usuário seleciona "Excluir minha conta" </br> <li> O sistema solicita confirmação e senha </br> <li> O usuário confirma a exclusão </br> <li> O sistema processa a exclusão dos dados </br> <li> O sistema confirma a conclusão do processo </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Configurações" </br> <li> O usuário seleciona "Privacidade e Dados" </br> <li> O usuário seleciona "Download dos meus dados" </br> <li> O sistema gera arquivo com dados do usuário </br> <li> O usuário faz download dos dados </br> <li> O usuário prossegue com exclusão da conta </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário tenta excluir sua conta </br> <li> O sistema detecta solicitações em andamento </br> <li> O sistema alerta sobre perda de acompanhamento </br> <li> O sistema oferece opções de cancelar solicitações ou aguardar </br> <li> O usuário decide como proceder </br> </ul> |
| Pós-condições | A conta e dados do usuário são removidos do sistema conforme LGPD |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [AD07](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

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
| 1.0    | Documentação do Diagrama de Casos de Uso          |  [Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 16/05/2025 | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)       | 17/05/2025      |
| 1.1    |  Adicionando tabelas de casos de uso e Bibliografia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 15/05/2025 |
| 1.2    |  Edição de imagem do diagrama e correção de liks| [Ana Victória](https://github.com/navicg)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.3    | Adição de casos de usos não implementados no documento | [Artur Mendonça Arruda](https://github.com/ArtyMend07) |16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.4    | Elaboração e adição de casos de usos não implementados | [Gabriel Lopes](https://github.com/BrzGab)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.5    | Criação e adição de tabela dos casos de uso 10, 11 e 12 no artefato. | [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.6    | Adição do casos de uso 13, 14 no artefato. | [Lucas Mendonça](https://github.com/lucasarruda9)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.7    | Adição do casos de uso 15(solicitação de serviço público) no documento. | [Lucas Mendonça](https://github.com/lucasarruda9)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.8    | Implementando os casos de uso 16, 17 e 18 no artefato. | [Karoline Luz da Conceição](https://github.com/KarolineLuz)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 2.0    | Adicionando os casos de uso 19, 20 e 21.| [Luiza da Silva Pugas](https://github.com/Luizaxx)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
