# História de Usuário

## Introdução

A história do usuário é um componente central no desenvolvimento ágil, especialmente na metodologia Extreme Programming (XP). Segundo Pressman (**2011**), “a atividade de ‘Ouvir’ conduz à criação de um conjunto de ‘histórias’ (também denominado histórias de usuários) que descreve o resultado, as características e a funcionalidade requisitados para o software a ser construído”<a id="anchor_1" href="#FRM1"> [1]</a> </q>.Essas histórias são escritas pelo cliente e colocadas em fichas, com prioridade atribuída “baseando-se no valor de negócio global do recurso ou função” (**PRESSMAN, 2011**)<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Além disso, as histórias de usuário são usadas como base para os testes de aceitação: “À medida que um incremento é entregue a um cliente, as histórias de usuários [...] implementados pelo incremento são usados como base para testes de aceitação” (**PRESSMAN, 2011**)<a id="anchor_1" href="#FRM1"> [1]</a> </q>. A XP enfatiza a simplicidade e o foco no que é essencial, seguindo o princípio: “Simplifique sempre que puder, mas tenha ciência de que um ‘retrabalho’ (refabricação, redesenvolvimento) contínuo consegue absorver tempo e recursos significativos” (**PRESSMAN, 2011**)<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Por fim, as histórias de usuários possibilitam um feedback constante entre cliente e equipe, já que “conforme novas necessidades surgem como parte do planejamento iterativo, a equipe dá ao cliente um rápido feedback referente ao impacto nos custos e no cronograma” (**PRESSMAN, 2011**)<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Cada história de usuário é construída de forma a responder três perguntas essenciais:  
- **Quem?** — Quem é o usuário ou persona envolvida na interação.  
- **O que?** — Qual é a ação, necessidade ou funcionalidade desejada.  
- **Por que?** — Qual é o valor, objetivo ou benefício buscado por meio daquela ação.

## Metodologia

A criação das histórias de usuário desenvolvidas nesta disciplina seguiu uma abordagem centrada no usuário, considerando tanto os requisitos funcionais e não funcionais, sendo eles implementados quanto os ainda não implementados, todos identificados por meio de quatro técnicas de elicitação de requisitos aplicadas, que visaram garantir uma compreensão ampla e fiel das necessidades dos usuários e, consequentemente, orientar o desenvolvimento das histórias. 

A priorização das histórias de usuário foi realizada utilizando a [técnica de moscow](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/tec_priorizacao/moscow/), que organizou todas as prioridades dos requisitos elicitados em uma tabela. Posteriormente, essas prioridades foram validadas em uma reunião com um ou mais usuários do **eGDF**.

As técnicas de elicitação aplicadas foram:


- **Entrevista:** Um diálogo aberto com os usuários, guiado por um roteiro previamente elaborado, mas com flexibilidade para adaptar-se conforme necessário, buscando compreender suas demandas, expectativas e desafios ao utilizar os serviços oferecidos pelo eGDF.

- **Introspecção:** Avaliação realizada com base na experiência pessoal dos responsáveis pelo projeto, buscando identificar possíveis falhas e oportunidades de melhoria.

- **Análise de Documentos:** Técnica que consiste na revisão e interpretação de materiais já existentes — como relatórios, manuais, normativas ou registros — para extrair informações relevantes sobre o sistema ou domínio em questão.

- **Brainstorming:** Método colaborativo que reúne um grupo de pessoas para gerar, de forma espontânea e criativa, o maior número possível de ideias e soluções relacionadas ao sistema ou problema que está sendo analisado.

 Cada requisito identificado foi transformado em uma história de usuário, e cada integrante da equipe ficou responsável por elaborar sete histórias, conforme demonstrado na **Tabela 2**. O modelo adotado para a elaboração está apresentado na **Tabela 1**, contendo os elementos utilizados nas histórias, juntamente com suas respectivas definições.

### Tabela 1: Modelo de História de Usuário

| **Elemento**                | **Definição** |
|-----------------------------|---------------|
| **Título**                  | Um resumo claro e direto sobre a funcionalidade ou requisito que será implementado. |
| **Como**                    | Identifica o perfil ou tipo de usuário que necessita da funcionalidade. |
| **Eu quero**                | Descreve a ação ou funcionalidade desejada pelo usuário. |
| **Para que**                | Indica o objetivo ou benefício que o usuário deseja alcançar com a funcionalidade. |
| **Critérios de Aceitação**  | Conjunto de condições que determinam quando a história será considerada concluída e aceita. |
| **Rastreabilidade**         | Referência ao requisito ou artefato relacionado, garantindo o vínculo entre a história de usuário e o requisito formal. |
| **Prioridade**   | Avaliação da complexidade ou prioridade da implementação da funcionalidade. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### Tabela 2: Histórias de Usuário que cada participante desenvolveu

### Legenda

- **História de Usuário:** Identificador e link para a descrição detalhada de cada história de usuário desenvolvida.
- **Autor:** Nome e link para o perfil no GitHub do autor responsável pela elaboração da respectiva história de usuário.
- **Requisito Relacionado:** Código do requisito funcional (RF) ou não funcional (RNF) que motivou a criação da história de usuário.
- **Rastreabilidade do Requisito:** Referência à técnica de elicitação utilizada para identificar o requisito, com link direto para o artefato gerado e seu respectivo identificador:  
  - **EN**: Entrevista  
  - **BR**: Brainstorming  
  - **AD**: Análise de Documentos  
  - **INT**: Introspecção  


| História de Usuário | Autor | Requisito Relacionado | Rastreabilidade do Requisito |
| --- | --- | --- | --- |
| [US01](#us01) | [Luiza da Silva Pugas](https://github.com/Luizaxx) | RF22 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a> |
| [US02](#us02) | [Luiza da Silva Pugas](https://github.com/Luizaxx) | RF18 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR20</a> |
| [US03](#us03) | [Luiza da Silva Pugas](https://github.com/Luizaxx) | RF27 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN11</a> |
| [US04](#us04) | [Luiza da Silva Pugas](https://github.com/Luizaxx) | RF30 | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD04</a> |
| [US05](#us05) | [Luiza da Silva Pugas](https://github.com/Luizaxx) | RF31 | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD06</a> |
| [US06](#us06) | [Luiza da Silva Pugas](https://github.com/Luizaxx) | RF32 | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD07</a> |
| [US07](#us08) | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | RF12 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR13</a> |
| [US08](#us09) | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | RF13 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR14</a> |
| [US09](#us10) | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | RF14 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR15</a> |
| [US10](#us11) | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | RF35 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT03</a> |
| [US11](#us12) | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | RF36 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT04</a> |
| [US12](#us13) | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | RF38 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT08</a> |
| [US13](#us15) | [Gabriel Lopes](https://github.com/BrzGab) | RF07 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR07</a>, <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>, <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD08</a> |
| [US14](#us16) | [Gabriel Lopes](https://github.com/BrzGab) | RF08 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR08</a> |
| [US15](#us17) | [Gabriel Lopes](https://github.com/BrzGab) | RF10 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR11</a> |
| [US16](#us18) | [Gabriel Lopes](https://github.com/BrzGab) | RF19 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN01</a> |
| [US17](#us19) | [Gabriel Lopes](https://github.com/BrzGab) | RF23 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN05</a> |
| [US18](#us20) | [Gabriel Lopes](https://github.com/BrzGab) | RF34 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT02</a> |
| [US19](#us22) | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | RF16 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR17</a> |
| [US20](#us23) | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | RF25 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN09</a> |
| [US21](#us24) | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | RF26 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN10</a>, <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT05</a> |
| [US22](#us25) | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | RF28 | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD02</a> |
| [US23](#us26) | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | RF29 | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD03</a> |
| [US24](#us27) | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | RF43 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT13</a>, <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR18</a> |
| [US25](#us29) | [Ana Victória Guedes da Costa](https://github.com/navicg) | RF01 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR01</a>, <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD01</a> |
| [US26](#us30) | [Ana Victória Guedes da Costa](https://github.com/navicg) | RF02 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR02</a> |
| [US27](#us31) | [Ana Victória Guedes da Costa](https://github.com/navicg) | RF03 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR03</a> |
| [US28](#us32) | [Ana Victória Guedes da Costa](https://github.com/navicg) | RF09 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR10</a> |
| [US29](#us33) | [Ana Victória Guedes da Costa](https://github.com/navicg) | RF15 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR16</a> |
| [US30](#us34) | [Ana Victória Guedes da Costa](https://github.com/navicg) | RF20 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN02</a> |
| [US31](#us36) | [Artur Mendonça](https://github.com/ArtyMend07) | RF04 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR04</a> |
| [US32](#us37) | [Artur Mendonça](https://github.com/ArtyMend07) | RF05 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR05</a>, <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD05</a>, <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT13</a> |
| [US33](#us38) | [Artur Mendonça](https://github.com/ArtyMend07) | RF06 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR06</a> |
| [US34](#us39) | [Artur Mendonça](https://github.com/ArtyMend07) | RF11 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR12</a> |
| [US35](#us40) | [Artur Mendonça](https://github.com/ArtyMend07) | RF21 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN03</a>, <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT07</a> |
| [US36](#us41) | [Artur Mendonça](https://github.com/ArtyMend07) | RF33 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT01</a> |
| [US37](#us43) | [Lucas Mendonça](https://github.com/lucasarruda9) | RF39 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT09</a> |
| [US38](#us44) | [Lucas Mendonça](https://github.com/lucasarruda9) | RF41 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT11</a> |
| [US39](#us45) | [Lucas Mendonça](https://github.com/lucasarruda9) | RF42 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT12</a> |
| [US40](#us46) | [Lucas Mendonça](https://github.com/lucasarruda9) | RF24 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN06</a> |
| [US41](#us47) | [Lucas Mendonça](https://github.com/lucasarruda9) | RF40 | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT10</a> |
| [US42](#us48) | [Lucas Mendonça](https://github.com/lucasarruda9) | RF17 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR19</a> |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

## Histórias de Usuário

As tabelas de 3 a 51 descrevem as histórias de usuário realizadas. Seguindo o modelo disponibilizado na **Tabela 1**.

## US01 - Autenticação Segura via gov.br {#us01}

??? abstract "Tabela 3 -  História de Usuário - Permitir autenticação segura através da plataforma gov.br, com opções como reconhecimento facial."


    #### **Título:** Autenticação Segura via gov.br

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** me autenticar de forma segura utilizando a plataforma gov.br, com suporte a reconhecimento facial,  
    **Para que** eu possa acessar os serviços oferecidos pelo aplicativo sem precisar criar uma nova conta e com total segurança.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve redirecionar o usuário para a tela oficial de login do gov.br.
    - <input type="checkbox"checked> Devem ser aceitas formas de autenticação oferecidas pelo gov.br (ex: senha, reconhecimento facial).
    - <input type="checkbox"checked> Após login bem-sucedido, o sistema deve retornar o usuário ao app com sessão iniciada.
    - <input type="checkbox"checked> Se o login falhar, uma mensagem clara deve ser exibida e o usuário poderá tentar novamente.
    - <input type="checkbox"checked> O sistema deve estar em conformidade com a LGPD no tratamento de dados do usuário.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF22</a>

    ---

    #### Estimativa de Esforço
        
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

## US02 - Compartilhamento e Salvamento de Informações Importantes {#us02}

??? abstract "Tabela 4 - História de Usuário - Conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)."

    #### **Título:** Compartilhamento e Salvamento de Informações Importantes

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** compartilhar ou salvar informações importantes, como protocolos ou comprovantes,  
    **Para que** eu possa manter registros acessíveis e enviar os dados facilmente para outras pessoas ou sistemas.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"checked> O aplicativo deve permitir ao usuário salvar protocolos ou comprovantes em formato PDF ou imagem.
    - <input type="checkbox"checked> O sistema deve oferecer a opção de compartilhamento via e-mail, WhatsApp ou outros aplicativos instalados.
    - <input type="checkbox"checked> As opções de compartilhamento devem estar disponíveis após a conclusão de um serviço ou solicitação.
    - <input type="checkbox"checked> O usuário deve receber uma confirmação visual de que o arquivo foi salvo ou compartilhado com sucesso.
    - <input type="checkbox"checked> O recurso deve estar disponível mesmo em dispositivos com acesso restrito à internet (no caso de salvamento local).

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF18</a>

    ---

    #### Estimativa de Esforço
        
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----
    
    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>
    
## US03 -  Acesso a Suporte com Instruções de Uso {#us03}

??? abstract "Tabela 5 - História de Usuário - Oferecer uma seção de suporte ao usuário com instruções de uso."


    #### **Título:** Acesso a Suporte com Instruções de Uso

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** acessar uma seção de suporte com instruções de uso,  
    **Para que** eu possa entender como utilizar as funcionalidades do aplicativo sem precisar de ajuda externa.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"checked> O aplicativo deve disponibilizar um botão ou aba de "Ajuda" ou "Suporte" visível no menu principal.
    - <input type="checkbox"checked> A seção de suporte deve conter instruções de uso organizadas por temas ou funcionalidades.
    - <input type="checkbox"checked> As instruções devem conter texto claro, com possibilidade de incluir imagens ilustrativas.
    - <input type="checkbox"checked> O suporte deve estar disponível sem necessidade de login no aplicativo.
    - <input type="checkbox"checked> Deve haver um campo de busca para facilitar a localização de tópicos de ajuda.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF27</a>

    ---

    #### Estimativa de Esforço

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

## US04 - Acompanhamento de Status de Solicitações {#us04}

??? abstract "Tabela 6 - História de Usuário - Permitir que o usuário visualize e acompanhe o status das suas solicitações."


    #### **Título:** Acompanhamento de Status de Solicitações

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** visualizar e acompanhar o status das minhas solicitações,  
    **Para que** eu possa saber em que etapa está meu pedido e me planejar de acordo com o andamento.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"checked> O sistema deve exibir uma lista com todas as solicitações realizadas pelo usuário.
    - <input type="checkbox"checked> Cada item da lista deve mostrar claramente o status atual (ex: recebido, em análise, concluído).
    - <input type="checkbox"checked> O sistema deve permitir visualizar os detalhes de cada solicitação individualmente.
    - <input type="checkbox"checked> O status deve ser atualizado automaticamente conforme a movimentação no sistema.
    - <input type="checkbox"checked> O usuário deve ser notificado quando houver mudança no status da solicitação.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF30</a>

    ---

    #### Estimativa de Esforço
        
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

## US05 - Confirmação da Resolução de Problemas {#us05}

??? abstract "Tabela 7 - História de Usuário - Permitir que o usuário confirme a resolução de problemas relatados."


    #### **Título:** Confirmação da Resolução de Problemas

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** confirmar se um problema que relatei foi resolvido,  
    **Para que** a administração do sistema saiba que minha demanda foi atendida corretamente.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"checked> O sistema deve permitir que o usuário visualize os problemas que ele relatou.
    - <input type="checkbox"checked> Cada problema deve ter a opção de “Confirmar resolução” disponível após resposta da equipe.
    - <input type="checkbox"checked> Após a confirmação, o problema deve ser marcado como “Resolvido pelo usuário”.
    - <input type="checkbox"checked> O sistema deve registrar data e hora da confirmação feita pelo usuário.
    - <input type="checkbox"checked> O usuário não deve conseguir modificar a confirmação após enviada.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF31</a>

    ---

    #### Estimativa de Esforço
        
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

## US06 - Exclusão de Conta e Dados Pessoais* {#us06}

??? abstract "Tabela 8 - História de Usuário - Permitir que o usuário exclua seus dados e conta do aplicativo."

    #### **Título:** Exclusão de Conta e Dados Pessoais

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** excluir minha conta e todos os meus dados pessoais do sistema,  
    **Para que** eu tenha controle total sobre minhas informações e possa encerrar meu vínculo com o aplicativo a qualquer momento.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"checked> O sistema deve disponibilizar uma opção clara de exclusão de conta nas configurações do usuário.
    - <input type="checkbox"checked> Antes da exclusão, o sistema deve apresentar uma mensagem de confirmação e consequências da ação.
    - <input type="checkbox"checked> A exclusão deve remover todos os dados pessoais do usuário dos bancos ativos, conforme LGPD.
    - <input type="checkbox"checked> Após a exclusão, o usuário não poderá mais acessar sua conta.
    - <input type="checkbox"checked> O sistema deve registrar a solicitação e data de exclusão para fins de auditoria legal.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF32</a>

    ---

    #### Estimativa de Esforço
        
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked > Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

**Vídeo 1** - Validação e Priorização com usuário por [Luiza da Silva Pugas](https://github.com/Luizaxx)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/lCb6uHoCcfY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/lCb6uHoCcfY" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Luiza da Silva Pugas](https://github.com/Luizaxx) | Elaborador das histórias | 30/05/2025 | 10:30 |
| Wanjo Christopher | Cidadão | 30/05/2025 | 10:30 |


## Termo de consentimento de imagem 
Este documento confirma que o cidadão Wanjo Christopher forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](docs/modelagem/agil/docs/assets/Termo_39954923_tce_81319_assinado_assinado_assinado.pdf)

## US07 - Alteração de Idioma no Aplicativo {#us07}

??? abstract "Tabela 10 - História de Usuário -  Permitir  que o usuário altere o idioma da interface para melhor usabilidade."

    #### **Título:** Alteração de Idioma no Aplicativo

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder alterar o idioma da interface do aplicativo facilmente,  
    **Para que** eu possa utilizar o app no idioma que me for mais confortável ou apropriado.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve disponibilizar uma lista com os idiomas suportados para seleção.
    - <input type="checkbox" checked> A alteração de idioma deve refletir imediatamente na interface do usuário.
    - <input type="checkbox" checked> A preferência de idioma do usuário deve ser salva para futuras sessões.
    - <input type="checkbox" checked> O sistema deve manter a consistência da interface após a mudança de idioma.
    - <input type="checkbox" checked> Caso o idioma selecionado não seja suportado, deve-se exibir mensagem apropriada.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF12</a>

    ---

    #### Estimativa de Esforço
    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## US08 - Personalização de Preferências e Perfil {#us08}

??? abstract "Tabela 11 - História de Usuário - Permitir que o usuário personalize suas preferências e perfil para recomendações mais assertivas."


    #### **Título:** Personalização de Preferências e Perfil para Recomendações

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder personalizar minhas preferências e configurar meu perfil,  
    **Para que** as recomendações de serviços oferecidas pelo aplicativo sejam mais adequadas aos meus interesses e necessidades.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve permitir que o usuário edite informações do seu perfil (ex: interesses, preferências, localização).
    - <input type="checkbox" checked> O usuário deve conseguir selecionar categorias ou tipos de serviços de interesse.
    - <input type="checkbox" checked> As preferências personalizadas devem ser salvas e usadas para ajustar as recomendações.
    - <input type="checkbox" checked> O sistema deve apresentar sugestões baseadas no perfil e preferências configuradas.
    - <input type="checkbox" checked> O usuário deve poder alterar suas preferências a qualquer momento.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF13</a>

    ---

    #### Estimativa de Esforço
    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## US09 - Envio de Mensagens Curtas para Lembretes {#us09}

??? abstract "Tabela 12 - História de Usuário -Permitir o envio de mensagens curtas para alertar sobre vencimentos e lembretes importantes."

    #### **Título:** Envio de Mensagens Curtas sobre Vencimentos e Lembretes

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** receber mensagens curtas com alertas sobre vencimentos e lembretes importantes,  
    **Para que** eu possa ser notificado de forma prática e rápida, evitando perder prazos ou compromissos.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve enviar notificações ou mensagens curtas para alertar sobre vencimentos próximos.
    - <input type="checkbox" checked> O usuário deve poder configurar quais tipos de lembretes deseja receber.
    - <input type="checkbox" checked> As mensagens devem ser claras, objetivas e conter informações relevantes.
    - <input type="checkbox" checked> O sistema deve garantir o envio das mensagens dentro do prazo configurado.
    - <input type="checkbox" checked> O usuário deve poder ativar ou desativar essas notificações a qualquer momento.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF14</a>

    ---

    #### Estimativa de Esforço
    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## US10 - Seleção do Tipo de Serviço {#us10}

??? abstract "Tabela 13 - História de Usuário - Permitir ao usuário selecionar o tipo de serviço desejado, como agendamento, limpeza ou reparo."

    #### **Título:** Seleção do Tipo de Serviço (Agendamento, Limpeza ou Reparo)

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder selecionar o tipo de serviço que desejo contratar, seja agendamento, limpeza ou reparo,  
    **Para que** eu possa receber um atendimento personalizado conforme minha necessidade específica.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve apresentar claramente as opções de serviço (agendamento, limpeza, reparo).
    - <input type="checkbox" checked> O usuário deve conseguir selecionar apenas um tipo de serviço por solicitação.
    - <input type="checkbox" checked> A seleção do tipo de serviço deve influenciar nas opções e recomendações exibidas.
    - <input type="checkbox" checked> O sistema deve confirmar a seleção antes de prosseguir com o atendimento.
    - <input type="checkbox" checked> O usuário pode alterar a seleção antes da confirmação final.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF35</a>

    ---

    #### Estimativa de Esforço
      
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## US11 - Registro Detalhado da Ocorrência {#us11}

??? abstract "Tabela 14 - História de Usuário - Permitir ao usuário adicionar descrição textual, imagem e localização GPS da ocorrência."

    #### **Título:** Adição de Descrição, Imagem e Localização GPS da Ocorrência

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder adicionar uma descrição textual, anexar imagens e registrar a localização GPS da ocorrência,  
    **Para que** eu possa fornecer informações completas e precisas sobre o evento reportado.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve permitir a inserção de texto descritivo livre sobre a ocorrência.
    - <input type="checkbox" checked> O usuário deve conseguir anexar uma ou mais imagens relacionadas à ocorrência.
    - <input type="checkbox" checked> O sistema deve capturar ou permitir o envio da localização GPS do usuário ou da ocorrência.
    - <input type="checkbox" checked> As informações adicionadas devem ser salvas corretamente e associadas à ocorrência.
    - <input type="checkbox" checked> O usuário deve receber confirmação do sucesso no registro dos dados.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF36</a>

    ---

    #### Estimativa de Esforço
    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## US12 - Acesso a Serviços de Transporte e Pré-cadastro do Cartão Mobilidade {#us12}

??? abstract "Tabela 15 - História de Usuário - Oferecer acesso a serviços de transporte público, incluindo o pré-cadastro do Cartão Mobilidade."

    #### **Título:** Acesso a Serviços de Transporte Público e Pré-cadastro do Cartão Mobilidade

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** ter acesso aos serviços de transporte público e poder realizar o pré-cadastro do Cartão Mobilidade,  
    **Para que** eu possa utilizar o transporte público de forma mais prática e rápida, sem precisar fazer todo o cadastro presencialmente.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve disponibilizar informações sobre os serviços de transporte público disponíveis.
    - <input type="checkbox" checked> O usuário deve poder iniciar o pré-cadastro do Cartão Mobilidade pelo aplicativo.
    - <input type="checkbox" checked> O sistema deve validar os dados fornecidos no pré-cadastro.
    - <input type="checkbox" checked> O usuário deve receber confirmação e orientações sobre os próximos passos após o pré-cadastro.
    - <input type="checkbox" checked> O sistema deve garantir a segurança e privacidade dos dados pessoais durante o processo.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF38</a>

    ---

    #### Estimativa de Esforço
      
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

**Vídeo 2** - Validação e Priorização com os usuário por [João Marcos Moraes](https://github.com/JJOAOMARCOSS)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/Ph5jpFJNuxY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/Ph5jpFJNuxY" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Arthur Leite forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](docs/assets/termo-de-imagem-hu/Termo_Consentimento_eGDF_ABNT__JOAO_assinado-Artur.pdf)

**Vídeo 3** - Validação e Priorização com os usuário por [João Marcos Moraes](https://github.com/JJOAOMARCOSS)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/gRrLrG8Su2A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/gRrLrG8Su2A" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Vitor Pereira forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](docs/assets/termo-de-imagem-hu/Termo_Consentimento_eGDF_ABNT_-JOAO_assinado_Victor.pdf)

| **Nome** | **Função** |  **Data**  | **Hora** |
| :------------------------------------------------: | :----------------------: | :--------: | :------: |
| [João Marcos Moraes](https://github.com/JJOAOMARCOSS) |    Elaborador das histórias     | 30/05/2025 |  11:00   |
| Arthur Leite |    Cidadão     | 30/05/2025 |  11:00   |
| Vitor Pereira |    Cidadão     | 30/05/2025 |  15:30   |

## US13 - Ajuste de Tamanho de Fonte e Contraste {#us13}

??? abstract "Tabela 17 - História de Usuário - Poder alterar o tamanho da fonte e o contraste de cores"

    #### **Título:** Ajuste de Tamanho de Fonte e Contraste de Cores

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** poder alterar o tamanho da fonte e o contraste de cores da interface,  
    **Para que** eu possa utilizar o aplicativo de forma mais confortável, especialmente se tiver dificuldades visuais.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve oferecer pelo menos 3 opções de tamanho de fonte (pequena, média, grande).
    - <input type="checkbox"> Deve haver opções de alto contraste para melhor visibilidade.
    - <input type="checkbox"> As alterações devem ser aplicadas imediatamente em toda a interface.
    - <input type="checkbox"> As preferências do usuário devem ser salvas para sessões futuras.
    - <input type="checkbox"> Deve haver um botão de "Restaurar padrão" para voltar às configurações originais.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF07</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

## US14 - Ativação do Modo Escuro {#us14}

??? abstract "Tabela 18 - História de Usuário - Permitir modo escuro"


    #### **Título:** Ativação do Modo Escuro

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** poder ativar o modo escuro na interface,  
    **Para que** eu possa usar o aplicativo com mais conforto em ambientes com pouca luz ou reduzir o cansaço visual.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve ter um botão ou switch claramente identificável para ativar/desativar o modo escuro.
    - <input type="checkbox"> A mudança entre modo claro e escuro deve ser instantânea e suave.
    - <input type="checkbox"> Todos os elementos da interface devem se adaptar corretamente ao tema escuro.
    - <input type="checkbox"> A escolha do usuário deve ser salva e aplicada automaticamente em acessos futuros.
    - <input type="checkbox"> O contraste no modo escuro deve atender aos padrões de acessibilidade.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF08</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média

       
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


## US15 - Geração de Relatórios e Comprovantes {#us15}

??? abstract "Tabela 19 - História de usuário - Gerar relatórios e visualizar comprovantes de agendamentos"


    #### **Título:** Geração de Relatórios e Visualização de Comprovantes de Agendamentos

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** gerar relatórios e visualizar comprovantes dos meus agendamentos,  
    **Para que** eu possa ter registros organizados dos serviços solicitados e apresentá-los quando necessário.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve permitir a geração de relatórios em formato PDF ou digital.
    - <input type="checkbox"> Os comprovantes devem conter todas as informações relevantes do agendamento.
    - <input type="checkbox"> O usuário deve poder filtrar relatórios por período ou tipo de serviço.
    - <input type="checkbox"> Os comprovantes devem ter um código de verificação ou QR Code para autenticação.
    - <input type="checkbox"> Deve ser possível compartilhar ou salvar os documentos gerados.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF10</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

## US16 - Localização de Ônibus em Tempo Real {#us16}

??? abstract "Tabela 20 - História de Usuário - Permitir a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa"


    #### **Título:** Visualização da Localização de Ônibus em Tempo Real

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** visualizar a localização dos ônibus em tempo real com previsão de chegada e rota no mapa,  
    **Para que** eu possa planejar melhor meu deslocamento e reduzir o tempo de espera nos pontos.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O mapa deve mostrar a localização atual dos ônibus das linhas selecionadas.
    - <input type="checkbox"> A previsão de chegada deve ser atualizada em tempo real (máximo 30 segundos).
    - <input type="checkbox"> O usuário deve poder visualizar a rota completa da linha no mapa.
    - <input type="checkbox"> Deve ser possível buscar linhas por número ou destino.
    - <input type="checkbox"> O sistema deve indicar claramente quando não há dados disponíveis para uma linha.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF19</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

## US17 - Acesso Facilitado a Serviços de Impostos {#us17}

??? abstract "Tabela 21 - História de Usuário - Facilitar o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras"


    #### **Título:** Acesso Facilitado a Serviços de Impostos com Instruções

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** acessar facilmente serviços relacionados a impostos, como boletos do IPVA, com instruções claras,  
    **Para que** eu possa cumprir minhas obrigações fiscais sem dificuldades ou necessidade de ir presencialmente aos órgãos.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve listar claramente todos os serviços de impostos disponíveis.
    - <input type="checkbox"> Cada serviço deve ter instruções passo a passo para utilização.
    - <input type="checkbox"> Deve ser possível gerar e visualizar boletos diretamente no app.
    - <input type="checkbox"> O sistema deve mostrar datas de vencimento e valores atualizados.
    - <input type="checkbox"> As instruções devem usar linguagem simples e incluir exemplos visuais quando necessário.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF23</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----
    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

## US18 - Categorização de Ocorrências {#us18}

??? abstract "Tabela 22 - História de Usuário - Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes"

    #### **Título:** Categorias Pré-definidas para Tipos de Ocorrência

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** selecionar categorias pré-definidas ao reportar uma ocorrência,  
    **Para que** minha solicitação seja direcionada rapidamente ao órgão competente e tratada com a prioridade adequada.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve apresentar uma lista organizada de categorias de ocorrências.
    - <input type="checkbox"> As categorias devem ser claras e com descrições quando necessário.
    - <input type="checkbox"> Deve haver subcategorias para refinamento da classificação.
    - <input type="checkbox"> O usuário deve poder selecionar apenas uma categoria principal por ocorrência.
    - <input type="checkbox"> A interface deve sugerir a categoria mais adequada baseada em palavras-chave.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF34</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

**Vídeo 4** - Validação e Priorização com usuário por [Gabriel Lopes](https://github.com/BrzGab)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/826kOaNpEEc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=826kOaNpEEc" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Gabriel Lopes de Amorim](https://github.com/BrzGab) | Elaborador das histórias | 30/05/2025 | 21:00 |
| Daniel Rodrigues Nascimento | Cidadão | 30/05/2025 | 21:00 |

## Termo de consentimento de imagem 
Este documento confirma que o cidadão **Daniel Rodrigues Nascimento** forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1EB1p_smwvLfqsPcUb_7nWpKIXuzLOx02/view?usp=sharing)

## US19 - Centralização das Informações de Agendamento {#us19}

??? abstract "Tabela 24 - História de Usuário - Acessar informações de agendamento e reagendamento de forma centralizada, promovendo praticidade e transparência ao cidadão"

	#### **Título:** Acesso Centralizado a Agendamentos e Reagendamentos

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** acessar informações de agendamento e reagendamento em um local centralizado,  
	**Para que** eu possa acompanhar meus compromissos com o GDF de maneira prática e organizada.

	---

	#### Critérios de Aceitação

	- <input type="checkbox" checked> O sistema deve exibir uma área unificada com os agendamentos e reagendamentos realizados.
	- <input type="checkbox" checked> As informações devem estar atualizadas em tempo real.
	- <input type="checkbox" checked> Deve ser possível visualizar detalhes como data, horário, local e serviço.
	- <input type="checkbox" checked> O sistema deve permitir filtrar por tipo de serviço ou data.
	- <input type="checkbox" checked> A interface deve ser responsiva e acessível em diferentes dispositivos.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR17</a>

	---

	#### Estimativa de Esforço
   
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

## US20 - Reporte de Problemas pelo Mapa Interativo {#us20}

??? abstract "Tabela 25 - História de Usuário - Permitir que cidadãos reportem problemas da cidade de forma intuitiva, utilizando um mapa interativo para localização precisa"

	#### **Título:** Reporte de Problemas via Mapa Interativo

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** reportar problemas da cidade através de um mapa interativo,  
	**Para que** eu possa localizar facilmente o local da ocorrência e facilitar a identificação pelas autoridades responsáveis.

	---

	#### Critérios de Aceitação

	- <input type="checkbox" checked> O sistema deve disponibilizar um mapa interativo com zoom e movimentação.
	- <input type="checkbox" checked> O usuário deve poder clicar no mapa para marcar o local do problema.
	- <input type="checkbox" checked> Deve ser possível anexar uma descrição e foto ao ponto marcado.
	- <input type="checkbox" checked> O sistema deve registrar a coordenada geográfica do ponto selecionado.
	- <input type="checkbox" checked> O mapa deve permitir busca por endereço para facilitar a localização.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/entrevista/#anchor_EN09">EN09</a>

	---

	#### Estimativa de Esforço

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>


## US21 - Acesso a Serviços de Emergência {#us21}

??? abstract "Tabela 26 -  História de Usuário - Fornecer acesso rápido aos números de emergência da polícia, promovendo segurança e agilidade em situações críticas"

	#### **Título:** Acesso Rápido aos Números da Polícia

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** ter acesso imediato aos números de emergência da polícia,  
	**Para que** eu possa contatar as autoridades rapidamente em situações de perigo ou urgência.

	---

	#### Critérios de Aceitação

	- <input type="checkbox" checked> O sistema deve exibir claramente o número da polícia em uma área de fácil acesso.
	- <input type="checkbox" checked> O número deve estar disponível mesmo sem login no aplicativo.
	- <input type="checkbox" checked> Deve haver botão de chamada direta ao número de emergência.
	- <input type="checkbox" checked> O sistema deve permitir acesso rápido a partir da tela inicial.
	- <input type="checkbox" checked> A interface deve seguir padrões de acessibilidade.

	---

	#### Rastreabilidade

	- **Requisitos Funcionais Relacionados:** <a href="../tec_elicitacao/entrevista/#anchor_EN10">EN10</a>, <a href="../tec_elicitacao/entrevista/#anchor_INT05">INT05</a>

	---

	#### Estimativa de Esforço
   
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

## US22 - Solicitação de Serviços Públicos {#us22}

??? abstract "Tabela 27 - História de Usuário - Permitir que cidadãos solicitem serviços públicos de forma simples e eficiente, promovendo melhorias na infraestrutura urbana"

	#### **Título:** Solicitação de Serviços Públicos Diversos

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** solicitar serviços públicos como coleta de lixo e reparo de vias,  
	**Para que** a administração pública possa atender às necessidades da população de maneira mais ágil e organizada.

	---

	#### Critérios de Aceitação

	- <input type="checkbox" checked> O sistema deve apresentar uma lista de serviços públicos disponíveis para solicitação.
	- <input type="checkbox" checked> O usuário deve poder selecionar o serviço desejado e descrever o problema.
	- <input type="checkbox" checked>O sistema deve permitir a marcação da localização da solicitação.
	- <input type="checkbox" checked> O usuário deve poder anexar imagens da situação ao enviar a solicitação.
	- <input type="checkbox" checked> O sistema deve gerar um protocolo para acompanhamento da solicitação.

	---
	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/analisededocumentos/#anchor_AD02">AD02</a>

	---

	#### Estimativa de Esforço
   
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

## US23 - Visualização de Solicitações em Mapa {#us23}

??? abstract "Tabela 28 - História de Usuário - Permitir que o cidadão visualize no mapa onde serviços públicos foram solicitados, promovendo maior transparência e controle"

	#### **Título:** Localização de Solicitações de Serviço no Mapa

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** visualizar no mapa os locais onde os serviços públicos foram solicitados,  
	**Para que** eu possa acompanhar as demandas da minha região e verificar se minha solicitação foi registrada corretamente.

	---

	#### Critérios de Aceitação

	- <input type="checkbox" checked> O sistema deve exibir um mapa com marcadores indicando os pontos de solicitação de serviços.
	- <input type="checkbox" checked> Cada marcador deve apresentar informações básicas da solicitação.
	- <input type="checkbox" checked> O mapa deve permitir filtragem por tipo de serviço e status da solicitação.
	- <input type="checkbox" checked> A interface deve permitir zoom e movimentação do mapa.
	- <input type="checkbox" checked> As informações devem ser atualizadas em tempo real.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/analisededocumentos/#anchor_AD03">AD03</a>

	---

	#### Estimativa de Esforço


    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

## US24 - Integração com Assistente Virtual {#us24}

??? abstract "Tabela 29 - História de Usuário - Disponibilizar um assistente virtual para responder automaticamente dúvidas frequentes dos usuários, oferecendo suporte ágil e contínuo"


	#### **Título:** Chatbot para Dúvidas Frequentes

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** interagir com um assistente virtual ou chatbot com respostas automáticas,  
	**Para que** eu possa esclarecer dúvidas frequentes rapidamente, sem depender de atendimento humano.

	---

	#### Critérios de Aceitação

	- <input type="checkbox" checked> O sistema deve disponibilizar um chatbot acessível a partir da tela inicial.
	- <input type="checkbox" checked> O assistente virtual deve responder perguntas comuns sobre uso do aplicativo e serviços oferecidos.
	- <input type="checkbox" checked> O chatbot deve reconhecer palavras-chave e apresentar respostas coerentes.
	- <input type="checkbox" checked> Deve haver opção de redirecionamento para atendimento humano em casos mais complexos.
	- <input type="checkbox" checked> As respostas do chatbot devem ser claras, objetivas e acessíveis.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** RF43

	---

	#### Estimativa de Esforço
	   
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox" checked> Won't Have (WH)
    ----

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

**Vídeo 5** - Validação e Priorização com usuário por [Karoline Luz da Conceição](https://github.com/KarolineLuz)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/gzX2Ucv4jaw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=gzX2Ucv4jaw" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Karoline Luz da Conceição](https://github.com/KarolineLuz) | Elaborador das histórias | 30/05/2025 | 14:00 |
| Luis Felipe | Cidadão | 30/05/2025 | 14:20 |

## Termo de consentimento de imagem 
Este documento confirma que o cidadão **Luis Felipe** forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1H7Dfstb_DuL6bARuRGX9iviqqT8HXvhD/view?usp=sharing)



## US25 - Login Simples e Rápido {#us25}

??? abstract "Tabela 31 - História de Usuário -  Permitir que o usuário realize login de forma simples e rápida."


    #### **Título:** Login Simples e Rápido

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** realizar o login de forma simples e rápida,  
    **Para que** eu possa acessar as funcionalidades do aplicativo sem dificuldades e sem perder tempo.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve apresentar uma tela de login objetiva e intuitiva.
    - <input type="checkbox" checked> O login deve ser processado em até 5 segundos.
    - <input type="checkbox" checked> Deve haver feedback visual (carregamento) durante a autenticação.
    - <input type="checkbox" checked> Se o login falhar, uma mensagem clara e objetiva deve ser exibida.
    - <input type="checkbox" checked> O sistema deve permitir a recuperação de senha de forma intuitiva.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF01</a>

    ---

    #### Estimativa de Esforço

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025).</p></font>


## US26 - Acessibilidade para Usuários com Pouca Familiaridade Tecnológica {#us26}

??? abstract "Tabela 32 - História de Usuário - Ser acessível mesmo para quem possui pouca familiaridade com tecnologia."


    #### **Título:** Acessibilidade para Usuários com Pouca Familiaridade Tecnológica

    ---

    #### História

    **Como** um usuário com pouca familiaridade com tecnologia,  
    **Eu quero** acessar as funcionalidades do aplicativo de forma simples,  
    **Para que** eu possa utilizar todos os recursos sem dificuldades ou necessidade de ajuda externa.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> As principais funcionalidades devem ser acessíveis em no máximo dois cliques.
    - <input type="checkbox" checked> O app deve utilizar ícones e textos autoexplicativos.
    - <input type="checkbox" checked> Deve haver um tutorial opcional na primeira utilização.
    - <input type="checkbox" checked> As fontes e botões devem ter tamanho adequado para facilitar a leitura e interação.
    - <input type="checkbox" checked> O sistema deve possuir suporte a leitura por voz.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF02</a>

    ---

    #### Estimativa de Esforço
    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025).</p></font>


## US27 - Notificações Personalizadas por Localização {#us27}

??? abstract "Tabela 33 - História de Usuário - Enviar notificações personalizadas com base na localização do usuário."

    #### **Título:** Notificações Personalizadas por Localização

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** receber notificações personalizadas com base na minha localização,  
    **Para que** eu fique informado sobre eventos, notícias ou alertas relevantes ao meu contexto geográfico.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve solicitar permissão para acessar a localização do usuário.
    - <input type="checkbox" checked> As notificações devem ser enviadas apenas quando relevantes à região do usuário.
    - <input type="checkbox" checked> O usuário pode ativar ou desativar esse tipo de notificação nas configurações.
    - <input type="checkbox" checked> A privacidade dos dados de localização deve ser garantida conforme LGPD.
    - <input type="checkbox" checked> O sistema deve atualizar as notificações conforme a mudança de localização do usuário.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF03</a>

    ---

    #### Estimativa de Esforço
       
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025).</p></font>


## US28 - Acesso e Visualização de Notícias Relevantes {#us28}

??? abstract "Tabela 34 - História de Usuário - Permitir ao usuário acessar e visualizar notícias relevantes."

    #### **Título:** Acesso e Visualização de Notícias Relevantes

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** acessar e visualizar notícias relevantes,  
    **Para que** eu me mantenha informado sobre assuntos importantes de maneira rápida e organizada.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve exibir uma lista atualizada de notícias na tela inicial ou seção dedicada.
    - <input type="checkbox" checked> Cada notícia deve conter título, resumo e link para conteúdo completo.
    - <input type="checkbox" checked> As notícias devem ser classificadas por relevância ou data.
    - <input type="checkbox" checked> O carregamento das notícias deve ser rápido e sem travamentos.
    - <input type="checkbox"> O sistema deve permitir favoritar notícias para leitura posterior.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF09</a>

    ---

    #### Estimativa de Esforço

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox" checked> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025).</p></font>

 

## US29 - Menu Principal na Tela Inicial {#us29}

??? abstract "Tabela 35 - História de Usuário - Apresentar um menu com as principais funções na tela inicial."


    #### **Título:** Menu Principal na Tela Inicial

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** acessar um menu com as principais funções diretamente na tela inicial,  
    **Para que** eu consiga navegar rapidamente pelas opções mais importantes.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O menu deve estar visível na tela inicial, com ícones e descrições claras.
    - <input type="checkbox" checked> Cada item do menu deve redirecionar corretamente para sua respectiva funcionalidade.
    - <input type="checkbox" checked> O menu deve ser responsivo e adaptado a diferentes tamanhos de tela.
    - <input type="checkbox" checked> O design deve seguir o padrão visual do aplicativo.
    - <input type="checkbox" checked> O menu deve permitir personalização da ordem dos itens pelo usuário.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF15</a>

    ---

    #### Estimativa de Esforço

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox" checked> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025).</p></font>


## US30 - Links para Serviços Externos com Explicações Claras {#us30}

??? abstract "Tabela 36 - História de Usuário - Fornecer links para serviços externos, com explicações claras sobre o que o usuário encontrará."

    #### **Título:** Links para Serviços Externos com Explicações Claras

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** acessar links para serviços externos com explicações claras sobre o que encontrarei,  
    **Para que** eu possa navegar com confiança e saber o que esperar ao clicar.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> Antes de acessar o serviço externo, uma explicação clara deve ser exibida.
    - <input type="checkbox" checked> O link deve abrir em uma nova janela ou aba para não interromper a navegação.
    - <input type="checkbox" checked> O sistema deve garantir que os links estejam sempre atualizados.
    - <input type="checkbox" checked> Os textos explicativos devem ser simples e objetivos.
    - <input type="checkbox" checked> O sistema deve permitir ao usuário avaliar a utilidade do link acessado.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF20</a>

    ---

    #### Estimativa de Esforço

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025).</p></font>
 

**Vídeo 6** - Validação e Priorização com os usuário por: [Ana Victória](https://github.com/navicg)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/KnZz2TXLhOI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/KnZz2TXLhOI" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Ana Victória](https://github.com/navicg) | Elaborador das histórias | 30/05/2025 | 13:00 |
| Leonardo Rodrigues | Cidadão | 30/05/2025 | 13:30 |

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Leonardo Rodrigues forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1x4C8j9SZMFaVtb9Qn5FgTMY8lQrNefc5/view?usp=sharing)

## US31 - Consulta Centralizada de Agendamentos e Serviços {#us31}

??? abstract "Tabela 38 - História de Usuário - Consultar agendamentos e serviços em um único local centralizado"

    #### **Título:** Consulta Centralizada de Agendamentos e Serviços

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** consultar todos os meus agendamentos e serviços em um único local centralizado,  
    **Para que** eu possa gerenciar minhas atividades e compromissos de forma eficiente e organizada.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve exibir uma lista consolidada de todos os agendamentos e serviços do usuário.
    - <input type="checkbox" checked> Os agendamentos devem ser organizados por data e categoria.
    - <input type="checkbox" checked> O usuário deve poder filtrar os agendamentos por tipo de serviço.
    - <input type="checkbox" checked> Cada item deve mostrar informações essenciais como data, hora e tipo de serviço.
    - <input type="checkbox" checked> O sistema deve atualizar a lista automaticamente quando houver mudanças.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF04</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta
          
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>


## US32 - Compartilhamento e Salvamento de Informações Importantes {#us32}

??? abstract "Tabela 39 - História de Usuário - Ter acesso a um assistente virtual com acessibilidade por voz"


    #### **Título:** Assistente Virtual com Acessibilidade por Voz

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** ter acesso a um assistente virtual que responda a comandos de voz,  
    **Para que** eu possa interagir com o aplicativo de forma mais acessível e natural.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve reconhecer e processar comandos de voz com precisão.
    - <input type="checkbox" checked> O assistente deve responder através de áudio de forma clara e compreensível.
    - <input type="checkbox" checked> Deve haver suporte para diferentes sotaques e variações linguísticas.
    - <input type="checkbox" checked> O assistente deve funcionar mesmo com ruído ambiente moderado.
    - <input type="checkbox" checked> O usuário deve poder ativar/desativar o assistente facilmente.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF05</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Baixa
          
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>


## US33 - Tutoriais Passo a Passo {#us33}

??? abstract "Tabela 40 - História de Usuário -  Poder acessar tutoriais passo a passo sobre como usar o app"


    #### **Título:** Tutoriais Passo a Passo do Aplicativo

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** acessar tutoriais passo a passo sobre como usar as funcionalidades,  
    **Para que** eu possa aprender a utilizar o aplicativo de forma independente.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> Os tutoriais devem estar organizados por categorias de funcionalidades.
    - <input type="checkbox" checked> Cada tutorial deve ter instruções claras e objetivas.
    - <input type="checkbox" checked> Deve haver imagens ou vídeos ilustrativos quando necessário.
    - <input type="checkbox" checked> O usuário deve poder marcar tutoriais como concluídos.
    - <input type="checkbox" checked> Os tutoriais devem ser acessíveis offline após primeiro acesso.

    ---
    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF06</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta
          
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox" checked> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>



## US34 - Integração com Serviços Essenciais {#us34}

??? abstract "Tabela 41 - História de Usuário - Permitir a integração com serviços de saúde, educação e mobilidade"


    #### **Título:** Integração com Serviços de Saúde, Educação e Mobilidade

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** ter acesso integrado aos serviços de saúde, educação e mobilidade,  
    **Para que** eu possa gerenciar diferentes aspectos da minha vida através de uma única plataforma.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve integrar-se com os sistemas de saúde pública.
    - <input type="checkbox" checked> Deve haver acesso às informações educacionais da rede pública.
    - <input type="checkbox" checked> A integração com serviços de mobilidade deve ser em tempo real.
    - <input type="checkbox" checked> O usuário deve poder alternar entre os serviços facilmente.
    - <input type="checkbox" checked> As informações devem ser sincronizadas periodicamente.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF11</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média
          
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>
    
 

## US35 - Consulta de Informações Educacionais {#us35}

??? abstract "Tabela 42 - História de Usuário - Oferecer funcionalidades para consulta de informações educacionais"


    #### **Título:** Consulta de Informações Educacionais

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** consultar informações educacionais como calendário letivo e status de vagas,  
    **Para que** eu possa me manter informado sobre o sistema educacional.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve exibir o calendário letivo atualizado.
    - <input type="checkbox" checked> Deve ser possível consultar vagas disponíveis nas instituições.
    - <input type="checkbox" checked> As informações devem ser atualizadas em tempo real.
    - <input type="checkbox" checked> O usuário deve poder filtrar informações por região ou escola.
    - <input type="checkbox" checked> Deve haver notificações sobre atualizações importantes.

    ---
    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF21</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média
          
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

  

## US36 - Registro de Ocorrências de Infraestrutura {#us36}

??? abstract "Tabela 43 -  História de Usuário - Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana"

    #### **Título:** Registro de Ocorrências de Infraestrutura Urbana

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** registrar ocorrências relacionadas a problemas de infraestrutura urbana,  
    **Para que** as autoridades competentes possam ser notificadas e resolver os problemas.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox" checked> O sistema deve permitir o registro detalhado da ocorrência.
    - <input type="checkbox" checked> Deve ser possível anexar fotos do problema.
    - <input type="checkbox" checked> O usuário deve poder marcar a localização exata no mapa.
    - <input type="checkbox" checked> O sistema deve gerar um número de protocolo para acompanhamento.
    - <input type="checkbox" checked> O usuário deve receber atualizações sobre o status da ocorrência.

    ---
    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF33</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta
          
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox" checked> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

**Vídeo 6** - Validação e Priorização com usuário por [Artur Mendonça](https://github.com/ArtyMend07)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/ToXDVRxCUCk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/ToXDVRxCUCk" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Artur Mendonça](https://github.com/ArtyMend07) | Elaborador das histórias | 30/05/2025 | 10:40 |
| Arthur Fernandes Alencar | Cidadão | 30/05/2025 | 10:40 |


## Termo de consentimento de imagem 
Este documento confirma que o cidadão Arthur Fernandes Alencar forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](docs/assets/termo-de-imagem-hu/Termo_Artur_Historia.pdf)

## US37 - Acompanhar histórico de interações {#us37}

??? abstract "Tabela 45 - História de Usuário - Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos."


    ### Título: Acompanhar histórico de interações

    ---

    ### História

    **Como** um cidadão do Distrito Federal e usuário do aplicativo,  
    **Eu quero** visualizar meu histórico de interações, solicitações e agendamentos,  
    **Para que** eu possa acompanhar e revisar tudo o que já realizei no app de forma organizada.

    ---

    ### Critérios de Aceitação
    - <input type="checkbox" checked> O histórico deve exibir todas as interações realizadas pelo usuário.  
    - <input type="checkbox" checked> Devem estar incluídos agendamentos, solicitações e ações executadas.  
    - <input type="checkbox" checked> As informações devem estar organizadas por data.  
    - <input type="checkbox" checked> O usuário deve conseguir filtrar por tipo de interação.
    ---

    ### Rastreabilidade
    - **Requisito Funcional Relacionado:** RF41

    ---

    ### Estimativa de Esforço
    - **Prioridade:** MH

    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----


    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

   

## US38 - Acesso a notícias oficiais do GDF {#us38}

??? abstract "Tabela 46 - História de Usuário - Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal."


    ### Título: Acesso a notícias oficiais do GDF

    ---

    ### História

    **Como** um cidadão do Distrito Federal e usuário do aplicativo,  
    **Eu quero** ter acesso a um feed com notícias oficiais e atualizadas do Governo do Distrito Federal,  
    **Para que** eu possa me manter informado sobre assuntos públicos e decisões governamentais.

    ---

    ### Critérios de Aceitação
    - <input type="checkbox" checked> O feed deve ser alimentado com fontes confiáveis do GDF.  
    - <input type="checkbox" checked> As notícias devem conter título, resumo, data e link para leitura completa.  
    - <input type="checkbox" checked> As atualizações devem ocorrer de forma periódica.  
    - <input type="checkbox" checked> Deve ser possível compartilhar notícias via redes sociais.

    ---

    ### Rastreabilidade
    - **Requisito Funcional Relacionado:** RF42

    ---

    ### Estimativa de Esforço
    - **Prioridade:** SH

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox" checked> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----
    
    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>



## US39 - Agendar serviços sociais {#us39}

??? abstract "Tabela 47 - História de Usuário -Permitir agendamentos em serviços sociais, como centros de assistência social e habitação."


    ### Título: Agendar serviços sociais

    ---

    ### História

    **Como** um cidadão do Distrito Federal e usuário do aplicativo,  
    **Eu quero** poder agendar atendimentos de serviços socias,  
    **Para que** eu consiga ter acesso aos serviços públicos do DF de forma simples e organizada.

    ---

    ### Critérios de Aceitação
    - <input type="checkbox" checked> Deve ser possível selecionar local, serviço e horário disponíveis.  
    - <input type="checkbox" checked> O usuário deve receber confirmação do agendamento.  
    - <input type="checkbox" checked> O sistema deve validar os dados antes de concluir o agendamento.  
    - <input type="checkbox" checked> Deve ser possível consultar e cancelar agendamentos realizados.

    ---

    ### Rastreabilidade
    - **Requisito Funcional Relacionado:** RF39

    ---

    ### Estimativa de Esforço
    - **Prioridade:** MH

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox" checked> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>



## US40 - Emitir tributos, certidões e documentos fiscais {#us40}

??? abstract "Tabela 48 - História de Usuário - Disponibilizar a emissão de tributos, certidões e outros documentos fiscais." 

    ### Título: Emitir tributos, certidões e documentos fiscais

    ---

    ### História

    **Como** um cidadão contribuinte do distrito federal,  
    **Eu quero** poder emitir tributos, certidões e documentos fiscais diretamente no aplicativo,  
    **Para que** eu possa regularizar minha situação de forma prática e digital.

    ---

    ### Critérios de Aceitação
    - <input type="checkbox" checked> O app deve permitir emissão de segunda via de tributos.  
    - <input type="checkbox" checked> Deve permitir gerar certidões.  
    - <input type="checkbox" checked> Os documentos gerados devem ser salvos em PDF.  
    - <input type="checkbox" checked> A funcionalidade deve estar segura e em conformidade com a LGPD.

    ---
    ### Rastreabilidade
    - **Requisito Funcional Relacionado:** RF40

    ---

    ### Estimativa de Esforço
    - **Prioridade:** CH

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox"> Should Have (SH)
    - <input type="checkbox" checked> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>
    
## US41 - Acompanhar pendências educacionais {#us41}

??? abstract "Tabela 49 - História de Usuário - Implementar funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos."

    ### Título: Acompanhar pendências educacionais

    ### História

    **Como** um aluno ou professor da rede pública do distrito federal,  
    **Eu quero** acompanhar pendências escolares,  
    **Para que** eu possa organizar minhas obrigações de forma mais eficiente.

    ### Critérios de Aceitação
    - <input type="checkbox" checked> O sistema deve exibir pendências de tarefas, avaliações e frequência dos alunos.  
    - <input type="checkbox" checked> Professores devem visualizar tarefas pendentes para correção.  
    - <input type="checkbox" checked> O sistema deve permitir notificar mudanças ou atrasos.  
    - <input type="checkbox" checked> A interface deve ser clara e acessível para todos os perfis.

    ---

    ### Rastreabilidade
    - **Requisito Funcional Relacionado:** RF24

    ### Estimativa de Esforço
    - **Prioridade:** SH

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox" checked> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>



## US42 - Receber notificações categorizadas {#us42}

??? abstract "Tabela 50 - História de Usuário - Permitir notificações por categorias como saúde, educação, transporte"


    ### Título: Receber notificações categorizadas

    ---

    ### História

    **Como** um cidadão do Distrito Federal e usuário do app,  
    **Eu quero** receber notificações por categorias como saúde, educação e transporte,  
    **Para que** eu possa me manter informado sobre assuntos relevantes para mim de forma simples e rápida.

    ---

    ### Critérios de Aceitação
    - <input type="checkbox" checked> O app deve permitir que o usuário escolha categorias de interesse.  
    - <input type="checkbox" checked> As notificações devem ter estilos visuais diferentes para cada categoria.
    - <input type="checkbox" checked> Deve ser possível alterar as categorias a qualquer momento.  
    - <input type="checkbox" checked> O conteúdo da notificação deve ser claro e conciso.

    ---
    ### Rastreabilidade
    - **Requisito Funcional Relacionado:** RF17

    ---

    ### Estimativa de Esforço
    - **Prioridade:** SH

    
    #### Priorização (Técnica MoSCoW)    
    - <input type="checkbox"> Must Have (MH)
    - <input type="checkbox" checked> Should Have (SH)
    - <input type="checkbox"> Could Have (CH)
    - <input type="checkbox"> Won't Have (WH)
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>
**Vídeo 7** - Validação e Priorização com usuário por [Lucas Mendonça](https://github.com/lucasarruda9)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/V2vTp1LULbI?si=xEAsK0MRSV45BRNN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/V2vTp1LULbI?si=xEAsK0MRSV45BRNN" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Lucas Mendonça](https://github.com/lucasarruda9) | Elaborador das histórias | 01/06/2025 | 18:30 |
| Ryan | Cidadão | 01/06/2025 | 18:30 |


## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a>PRESSMAN, Roger S. Engenharia de software: uma abordagem profissional. 8. ed. Porto Alegre: AMGH, 2016.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/cria%C3%A7%C3%A3o-de-hist%C3%B3rias-de-usu%C3%A1rio/docs/assets/modelagem/historia_usuario1.png" >
</div>

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/cria%C3%A7%C3%A3o-de-hist%C3%B3rias-de-usu%C3%A1rio/docs/assets/modelagem/historia_usuario2.png" >
</div>

## Histórico de Versões

| Versão | Descrição                      | Autor(es)                                             | Data       | Revisor(es)                               | Data de Revisão |
| ------ | ------------------------------ | ----------------------------------------------------- | ---------- | ----------------------------------------- | --------------- |
| 1.0    | Criação da página e introdução | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 23/05/2025 | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | 23/05/2025      |
| 1.1    | Criação e elaboração das história de usuário RF22 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 27/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.2  | Criação e elaboração das história de usuário RF18 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 27/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.3  | Criação e elaboração das história de usuário RF27 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 27/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.4  | Criação e elaboração das história de usuário RF30 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 27/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.4  | Criação e elaboração das história de usuário RF31 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 27/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.5  | Criação e elaboração das história de usuário RF32 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 27/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.6  | Criação e elaboração das história de usuário RF12 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 27/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.7  | Criação e elaboração das história de usuário RF13 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 27/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.8  | Criação e elaboração das história de usuário RF14 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 27/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.9  | Criação e elaboração das história de usuário RF35 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 27/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.10  | Criação e elaboração das história de usuário RF36 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 27/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.11  | Criação e elaboração das história de usuário RF38 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 27/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.12  | Criação e elaboração das história de usuário RF07 | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.13  | Criação e elaboração das história de usuário RF08 | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.14  | Criação e elaboração das história de usuário RF10 | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.15  | Criação e elaboração das história de usuário RF19 | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.16  | Criação e elaboração das história de usuário RF23 | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.17  | Criação e elaboração das história de usuário RF34 | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.18  | Adicionando introdução, metodologia e referências bibliográficas | [Ana Victória Guedes da Costa](https://github.com/navicg) | 28/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.19  |        Criação e elaboração das história de usuário RF16                                          |     [Karoline Luz](https://github.com/KarolineLuz)                                         | 28/05/2025             |   [Artur Mendonça](https://github.com/ArtyMend07)                                          |   03/06/2025                |
| 1.20  |        Criação e elaboração das história de usuário RF25                                          |     [Karoline Luz](https://github.com/KarolineLuz)                                         | 28/05/2025             |   [Artur Mendonça](https://github.com/ArtyMend07)                                          |   03/06/2025                |
| 1.21  |        Criação e elaboração das história de usuário RF26                                          |     [Karoline Luz](https://github.com/KarolineLuz)                                         | 28/05/2025             |   [Artur Mendonça](https://github.com/ArtyMend07)                                          |   03/06/2025                |
| 1.22  |        Criação e elaboração das história de usuário RF28                                         |     [Karoline Luz](https://github.com/KarolineLuz)                                         | 28/05/2025             |   [Artur Mendonça](https://github.com/ArtyMend07)                                          |   03/06/2025                |
| 1.23  |        Criação e elaboração das história de usuário RF29                                          |     [Karoline Luz](https://github.com/KarolineLuz)                                         | 28/05/2025             |   [Artur Mendonça](https://github.com/ArtyMend07)                                          |   03/06/2025                |
| 1.24 |        Criação e elaboração das história de usuário RF43                                          |     [Karoline Luz](https://github.com/KarolineLuz)                                         | 28/05/2025             |   [Artur Mendonça](https://github.com/ArtyMend07)                                          |   03/06/2025                |
| 1.25  | Criação e elaboração das história de usuário RF01 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.26 | Criação e elaboração das história de usuário RF02 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.27 | Criação e elaboração das história de usuário RF03 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.28  | Criação e elaboração das história de usuário RF09 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.29  | Criação e elaboração das história de usuário RF15 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.30  |Criação e elaboração das história de usuário RF20 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.31  |Criação e elaboração das história de usuário RNF13 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 29/05/2025 |[João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.32  |Criação e elaboração das história de usuário RNF16 | [Karoline Luz](https://github.com/KarolineLuz) | 29/05/2025 |[Artur Mendonça](https://github.com/ArtyMend07) | 03/06/2025      |
| 1.33  | Criação e elaboração das história de usuário RNF22 | [Gabriel Lopes](https://github.com/BrzGab) | 29/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025      |
| 1.34  | Criação e elaboração da história de usuário RF04 | [Artur Mendonça](https://github.com/ArtyMend07) | 29/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.35  | Criação e elaboração da história de usuário RF05 | [Artur Mendonça](https://github.com/ArtyMend07) | 29/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.36  | Criação e elaboração da história de usuário RF06 | [Artur Mendonça](https://github.com/ArtyMend07) | 29/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.37  | Criação e elaboração da história de usuário RF11 | [Artur Mendonça](https://github.com/ArtyMend07) | 29/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.38  | Criação e elaboração da história de usuário RF21 | [Artur Mendonça](https://github.com/ArtyMend07) | 29/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.39  | Criação e elaboração da história de usuário RF33 | [Artur Mendonça](https://github.com/ArtyMend07) | 29/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.40  | Criação e elaboração da história de usuário RNF20 | [Artur Mendonça](https://github.com/ArtyMend07) | 30/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.41  | Criação e elaboração da história de usuário RF39 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.42  | Criação e elaboração da história de usuário RF41 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.43  | Criação e elaboração da história de usuário RF42 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.44  | Criação e elaboração da história de usuário RF24 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.45  | Criação e elaboração da história de usuário RF40 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.46  | Criação e elaboração da história de usuário RF17 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.47  | Criação e elaboração da história de usuário RNF23 | [Lucas Mendonça](https://github.com/lucasarruda9) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.48  | Adição de validação das histórias de usuário | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 30/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025 |
| 1.49  | Adição de validação das histórias de usuário 1 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 30/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 03/06/2025 |
| 1.50  | Adição de validação das histórias de usuário 2 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 30/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 03/06/2025 |
| 1.51  | Organizando histórias de usuário e adicionando tabela do que cada um desenvolveu | [Ana Victória Guedes da Costa](https://github.com/navicg) | 31/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025 |
| 1.52  | Adição de validação das histórias de usuário | [Ana Victória Guedes da Costa](https://github.com/navicg) | 31/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 03/06/2025 |
| 1.53  | Adição do Termo de Consentimento e vídeo da entrevista | [Artur Mendonça](https://github.com/ArtyMend07) | 31/05/2025 | [Luiza Silva](https://github.com/Luizaxx) | 03/06/2025      |
| 1.54  | Adicionando o link da validação das histórias de usuário | [Gabriel Lopes](https://github.com/BrzGab) | 31/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 03/06/2025 |
| 1.55  | Adicionando metodoliga de moscow | [Karoline Luz](https://github.com/KarolineLuz) | 31/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 03/06/2025 |
| 1.56  | Adicionando Video de entrevista e Termo de Consentimento | [Karoline Luz](https://github.com/KarolineLuz) | 31/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 03/06/2025 |
| 1.57  | Removendo Subtarefas | [Karoline Luz](https://github.com/KarolineLuz) |01/06/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 03/06/2025 |
| 1.58  | Adicionando link do vídeo 7 | [Lucas Mendonça](http://github.com/lucasarruda9) |01/06/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 01/06/2025 |
| 2.0 | Removendo Requisitos Não-Funcionais |  [Karoline Luz](https://github.com/KarolineLuz) |19/06/2025 |[João Marcos Moraes](https://github.com/JJOAOMARCOSS)  | 22/06/2025 |