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

A criação das histórias de usuário desenvolvidas nesta disciplina seguiu uma abordagem centrada no usuário, considerando tanto os requisitos funcionais já implementados quanto os ainda não implementados, todos identificados por meio de quatro técnicas de elicitação de requisitos aplicadas, que visaram garantir uma compreensão ampla e fiel das necessidades dos usuários e, consequentemente, orientar o desenvolvimento das histórias. As seguintes técnicas foram:

- **Entrevista:** Um diálogo aberto com os usuários, guiado por um roteiro previamente elaborado, mas com flexibilidade para adaptar-se conforme necessário, buscando compreender suas demandas, expectativas e desafios ao utilizar os serviços oferecidos pelo eGDF.

- **Introspecção:** Avaliação realizada com base na experiência pessoal dos responsáveis pelo projeto, buscando identificar possíveis falhas e oportunidades de melhoria.

- **Análise de Documentos:** Técnica que consiste na revisão e interpretação de materiais já existentes — como relatórios, manuais, normativas ou registros — para extrair informações relevantes sobre o sistema ou domínio em questão.

- **Brainstorming:** Método colaborativo que reúne um grupo de pessoas para gerar, de forma espontânea e criativa, o maior número possível de ideias e soluções relacionadas ao sistema ou problema que está sendo analisado.

 Cada requisito identificado foi transformado em uma história de usuário, e cada integrante da equipe ficou responsável por elaborar seis histórias, conforme demonstrado na **Tabela 2**. O modelo adotado para a elaboração está apresentado na **Tabela 1**, contendo os elementos utilizados nas histórias, juntamente com suas respectivas definições.

### Tabela 1: Modelo de História de Usuário

| **Elemento**                | **Definição** |
|-----------------------------|---------------|
| **Título**                  | Um resumo claro e direto sobre a funcionalidade ou requisito que será implementado. |
| **Como**                    | Identifica o perfil ou tipo de usuário que necessita da funcionalidade. |
| **Eu quero**                | Descreve a ação ou funcionalidade desejada pelo usuário. |
| **Para que**                | Indica o objetivo ou benefício que o usuário deseja alcançar com a funcionalidade. |
| **Critérios de Aceitação**  | Conjunto de condições que determinam quando a história será considerada concluída e aceita. |
| **Subtarefas**              | Lista de atividades técnicas e operacionais necessárias para implementar a funcionalidade descrita. |
| **Rastreabilidade**         | Referência ao requisito ou artefato relacionado, garantindo o vínculo entre a história de usuário e o requisito formal. |
| **Estimativa de Esforço**   | Avaliação da complexidade ou prioridade da implementação da funcionalidade. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as) ( [Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>


### Tabela 2: Requisitos abordados nas histórias de usuário

| ID   | Descrição                                                                                                     | Rastreabilidade                                                             | Autor                                              |
| ---- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | -------------------------------------------------- |
| RF22 | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial. | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN04</a>         | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF18 | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)     | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR20</a>      | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF27 | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso.                             | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN11</a>         | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF30 | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.                   | <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD04</a> | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF31 | O sistema deve permitir que o usuário confirme a resolução de problemas relatados.                            | <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD06</a> | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF32 | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo.                                | <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD07</a> | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF12   | O usuário deve poder alterar o idioma do aplicativo                                                                                                                     | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR13</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF13   | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços                                                                             | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR14</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF14   | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes                                                                        | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR15</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF35   | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo).                                                                               | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT03</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF36   | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência.                                                                                      | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT04</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF38   | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade.                                                                            | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT08</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF07 | O usuário deve poder alterar o tamanho da fonte e o contraste de cores | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR07</a>, <a href="../tec_elicitacao/entrevista/#anchor_EN">EN08</a>, <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD08</a> | [Gabriel Lopes](https://github.com/BrzGab) |
| RF08 | O aplicativo deve permitir modo escuro | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR08</a> | [Gabriel Lopes](https://github.com/BrzGab) |
| RF10 | O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos | <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR11</a> | [Gabriel Lopes](https://github.com/BrzGab) |
| RF19 | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa. | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN01</a> | [Gabriel Lopes](https://github.com/BrzGab) |
| RF23 | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras. | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN05</a> | [Gabriel Lopes](https://github.com/BrzGab) |
| RF34 | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes. | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT02</a> | [Gabriel Lopes](https://github.com/BrzGab) |
| RF16 | O sistema deve permitir que o usuário acesse informações centralizadas sobre agendamentos e reagendamentos.     | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR17</a>      | [Karoline Luz da Conceição](https://github.com/KarolineLuz) |
| RF25 | O sistema deve permitir que o usuário reporte problemas urbanos por meio de um mapa interativo.                 | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN09</a>         | [Karoline Luz da Conceição](https://github.com/KarolineLuz) |
| RF26 | O sistema deve fornecer acesso aos números de serviços de emergência, como os da polícia.                       | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN10</a>, <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT05</a> | [Karoline Luz da Conceição](https://github.com/KarolineLuz) |
| RF28 | O sistema deve permitir que o usuário solicite serviços públicos, como coleta de lixo, reparo de vias e outros. | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD02</a> | [Karoline Luz da Conceição](https://github.com/KarolineLuz) |
| RF29 | O sistema deve permitir que o usuário utilize um mapa para localizar onde os serviços foram solicitados.        | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD03</a> | [Karoline Luz da Conceição](https://github.com/KarolineLuz) |
| RF43 | O sistema deve integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes.     | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT13</a>, <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR18</a> | [Karoline Luz da Conceição](https://github.com/KarolineLuz) |






??? info "📋 O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial."

    **História de Usuário — RF22: Autenticação Segura via gov.br**

    ---

    #### **Título:** Autenticação Segura via gov.br

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** me autenticar de forma segura utilizando a plataforma gov.br, com suporte a reconhecimento facial,  
    **Para que** eu possa acessar os serviços oferecidos pelo aplicativo sem precisar criar uma nova conta e com total segurança.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve redirecionar o usuário para a tela oficial de login do gov.br.
    - <input type="checkbox"> Devem ser aceitas formas de autenticação oferecidas pelo gov.br (ex: senha, reconhecimento facial).
    - <input type="checkbox"> Após login bem-sucedido, o sistema deve retornar o usuário ao app com sessão iniciada.
    - <input type="checkbox"> Se o login falhar, uma mensagem clara deve ser exibida e o usuário poderá tentar novamente.
    - <input type="checkbox"> O sistema deve estar em conformidade com a LGPD no tratamento de dados do usuário.

    ---

    #### Subtarefas

    - <input type="checkbox"> Integrar SDK/API do gov.br ao backend do app.
    - <input type="checkbox"> Implementar interface de redirecionamento para o login gov.br.
    - <input type="checkbox"> Tratar respostas da autenticação (sucesso, falha, erro de rede).
    - <input type="checkbox"> Criar alertas e mensagens de erro amigáveis.
    - <input type="checkbox"> Validar conformidade de dados com a LGPD.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF22</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio
  
    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


??? info "📋 O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)."

    **História de Usuário — RF18: Compartilhamento e Salvamento de Informações Importantes**

    ---

    #### **Título:** Compartilhamento e Salvamento de Informações Importantes

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** compartilhar ou salvar informações importantes, como protocolos ou comprovantes,  
    **Para que** eu possa manter registros acessíveis e enviar os dados facilmente para outras pessoas ou sistemas.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O aplicativo deve permitir ao usuário salvar protocolos ou comprovantes em formato PDF ou imagem.
    - <input type="checkbox"> O sistema deve oferecer a opção de compartilhamento via e-mail, WhatsApp ou outros aplicativos instalados.
    - <input type="checkbox"> As opções de compartilhamento devem estar disponíveis após a conclusão de um serviço ou solicitação.
    - <input type="checkbox"> O usuário deve receber uma confirmação visual de que o arquivo foi salvo ou compartilhado com sucesso.
    - <input type="checkbox"> O recurso deve estar disponível mesmo em dispositivos com acesso restrito à internet (no caso de salvamento local).

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar componente de geração de comprovantes em PDF.
    - <input type="checkbox"> Implementar botão de "Salvar comprovante" com feedback visual.
    - <input type="checkbox"> Integrar opções de compartilhamento nativas do sistema operacional (iOS/Android).
    - <input type="checkbox"> Validar compatibilidade com diferentes tipos de arquivos gerados.
    - <input type="checkbox"> Testar fluxo offline para salvamento local.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF18</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média
    
    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>
    

??? info "📋 O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso."

    **História de Usuário — RF27: Acesso a Suporte com Instruções de Uso**

    ---

    #### **Título:** Acesso a Suporte com Instruções de Uso

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** acessar uma seção de suporte com instruções de uso,  
    **Para que** eu possa entender como utilizar as funcionalidades do aplicativo sem precisar de ajuda externa.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O aplicativo deve disponibilizar um botão ou aba de "Ajuda" ou "Suporte" visível no menu principal.
    - <input type="checkbox"> A seção de suporte deve conter instruções de uso organizadas por temas ou funcionalidades.
    - <input type="checkbox"> As instruções devem conter texto claro, com possibilidade de incluir imagens ilustrativas.
    - <input type="checkbox"> O suporte deve estar disponível sem necessidade de login no aplicativo.
    - <input type="checkbox"> Deve haver um campo de busca para facilitar a localização de tópicos de ajuda.

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar layout da seção de suporte com estrutura de navegação clara.
    - <input type="checkbox"> Redigir e revisar textos explicativos das funcionalidades.
    - <input type="checkbox"> Adicionar imagens ou ilustrações nas instruções.
    - <input type="checkbox"> Implementar campo de busca dentro da seção de suporte.
    - <input type="checkbox"> Garantir acesso ao suporte mesmo para usuários não autenticados.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF27</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

??? info "📋 O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações."

    **História de Usuário — RF30: Acompanhamento de Status de Solicitações**

    ---

    #### **Título:** Acompanhamento de Status de Solicitações

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** visualizar e acompanhar o status das minhas solicitações,  
    **Para que** eu possa saber em que etapa está meu pedido e me planejar de acordo com o andamento.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve exibir uma lista com todas as solicitações realizadas pelo usuário.
    - <input type="checkbox"> Cada item da lista deve mostrar claramente o status atual (ex: recebido, em análise, concluído).
    - <input type="checkbox"> O sistema deve permitir visualizar os detalhes de cada solicitação individualmente.
    - <input type="checkbox"> O status deve ser atualizado automaticamente conforme a movimentação no sistema.
    - <input type="checkbox"> O usuário deve ser notificado quando houver mudança no status da solicitação.

    ---

    #### Subtarefas

    - <input type="checkbox"> Implementar backend para consulta de status por usuário autenticado.
    - <input type="checkbox"> Criar interface com lista e detalhes das solicitações.
    - <input type="checkbox"> Integrar com o sistema interno de processamento para atualizar status em tempo real.
    - <input type="checkbox"> Desenvolver mecanismo de notificação de mudanças de status.
    - <input type="checkbox"> Testar a consistência dos dados apresentados ao usuário.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF30</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

??? info "📋 O sistema deve permitir que o usuário confirme a resolução de problemas relatados."

    **História de Usuário — RF31: Confirmação da Resolução de Problemas**

    ---

    #### **Título:** Confirmação da Resolução de Problemas

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** confirmar se um problema que relatei foi resolvido,  
    **Para que** a administração do sistema saiba que minha demanda foi atendida corretamente.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve permitir que o usuário visualize os problemas que ele relatou.
    - <input type="checkbox"> Cada problema deve ter a opção de “Confirmar resolução” disponível após resposta da equipe.
    - <input type="checkbox"> Após a confirmação, o problema deve ser marcado como “Resolvido pelo usuário”.
    - <input type="checkbox"> O sistema deve registrar data e hora da confirmação feita pelo usuário.
    - <input type="checkbox"> O usuário não deve conseguir modificar a confirmação após enviada.

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar interface de listagem de problemas relatados.
    - <input type="checkbox"> Adicionar botão “Confirmar resolução” com controle de disponibilidade por status.
    - <input type="checkbox"> Implementar registro da confirmação no banco de dados.
    - <input type="checkbox"> Exibir feedback visual após confirmação.
    - <input type="checkbox"> Testar regras de bloqueio de edição após confirmação.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF31</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

??? info "📋 O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo."

    **História de Usuário — RF32: Exclusão de Conta e Dados Pessoais**

    ---

    #### **Título:** Exclusão de Conta e Dados Pessoais

    ---

    #### História

    **Como** um cidadão usuário do aplicativo,  
    **Eu quero** excluir minha conta e todos os meus dados pessoais do sistema,  
    **Para que** eu tenha controle total sobre minhas informações e possa encerrar meu vínculo com o aplicativo a qualquer momento.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve disponibilizar uma opção clara de exclusão de conta nas configurações do usuário.
    - <input type="checkbox"> Antes da exclusão, o sistema deve apresentar uma mensagem de confirmação e consequências da ação.
    - <input type="checkbox"> A exclusão deve remover todos os dados pessoais do usuário dos bancos ativos, conforme LGPD.
    - <input type="checkbox"> Após a exclusão, o usuário não poderá mais acessar sua conta.
    - <input type="checkbox"> O sistema deve registrar a solicitação e data de exclusão para fins de auditoria legal.

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar interface de gerenciamento de conta com botão “Excluir conta”.
    - <input type="checkbox"> Desenvolver tela de confirmação com informações claras ao usuário.
    - <input type="checkbox"> Implementar lógica backend para remoção de dados e encerramento de sessão.
    - <input type="checkbox"> Garantir que a exclusão atenda aos critérios da LGPD.
    - <input type="checkbox"> Registrar a operação para fins de rastreabilidade legal (sem violar privacidade).

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF32</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

??? info "🌐 O aplicativo permite que o usuário altere o idioma da interface para melhor usabilidade."

    **História de Usuário — US12: Alteração de Idioma no Aplicativo**

    ---

    #### **Título:** Alteração de Idioma no Aplicativo

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder alterar o idioma da interface do aplicativo facilmente,  
    **Para que** eu possa utilizar o app no idioma que me for mais confortável ou apropriado.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve disponibilizar uma lista com os idiomas suportados para seleção.
    - <input type="checkbox"> A alteração de idioma deve refletir imediatamente na interface do usuário.
    - <input type="checkbox"> A preferência de idioma do usuário deve ser salva para futuras sessões.
    - <input type="checkbox"> O sistema deve manter a consistência da interface após a mudança de idioma.
    - <input type="checkbox"> Caso o idioma selecionado não seja suportado, deve-se exibir mensagem apropriada.

    ---

    #### Subtarefas

    - <input type="checkbox"> Implementar componente para seleção de idioma na interface.
    - <input type="checkbox"> Integrar mecanismo de internacionalização (i18n) no app.
    - <input type="checkbox"> Armazenar preferência do idioma no perfil do usuário ou localmente.
    - <input type="checkbox"> Traduzir textos e mensagens para os idiomas suportados.
    - <input type="checkbox"> Testar mudança de idioma em diferentes telas e fluxos.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF12</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

??? info "⚙️ O aplicativo permite que o usuário personalize suas preferências e perfil para recomendações mais assertivas."

    **História de Usuário — US13: Personalização de Preferências e Perfil**

    ---

    #### **Título:** Personalização de Preferências e Perfil para Recomendações

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder personalizar minhas preferências e configurar meu perfil,  
    **Para que** as recomendações de serviços oferecidas pelo aplicativo sejam mais adequadas aos meus interesses e necessidades.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve permitir que o usuário edite informações do seu perfil (ex: interesses, preferências, localização).
    - <input type="checkbox"> O usuário deve conseguir selecionar categorias ou tipos de serviços de interesse.
    - <input type="checkbox"> As preferências personalizadas devem ser salvas e usadas para ajustar as recomendações.
    - <input type="checkbox"> O sistema deve apresentar sugestões baseadas no perfil e preferências configuradas.
    - <input type="checkbox"> O usuário deve poder alterar suas preferências a qualquer momento.

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar interface para edição do perfil e preferências.
    - <input type="checkbox"> Desenvolver backend para armazenar e gerenciar as preferências do usuário.
    - <input type="checkbox"> Implementar mecanismo de recomendação baseado nas preferências do usuário.
    - <input type="checkbox"> Testar persistência e atualização das preferências.
    - <input type="checkbox"> Garantir feedback visual claro ao salvar preferências.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF13</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

??? info "✉️ O aplicativo permite o envio de mensagens curtas para alertar sobre vencimentos e lembretes importantes."

    **História de Usuário — US14: Envio de Mensagens Curtas para Lembretes**

    ---

    #### **Título:** Envio de Mensagens Curtas sobre Vencimentos e Lembretes

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** receber mensagens curtas com alertas sobre vencimentos e lembretes importantes,  
    **Para que** eu possa ser notificado de forma prática e rápida, evitando perder prazos ou compromissos.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve enviar notificações ou mensagens curtas para alertar sobre vencimentos próximos.
    - <input type="checkbox"> O usuário deve poder configurar quais tipos de lembretes deseja receber.
    - <input type="checkbox"> As mensagens devem ser claras, objetivas e conter informações relevantes.
    - <input type="checkbox"> O sistema deve garantir o envio das mensagens dentro do prazo configurado.
    - <input type="checkbox"> O usuário deve poder ativar ou desativar essas notificações a qualquer momento.

    ---

    #### Subtarefas

    - <input type="checkbox"> Implementar sistema de notificações para vencimentos e lembretes.
    - <input type="checkbox"> Criar interface para configuração das preferências de mensagens.
    - <input type="checkbox"> Desenvolver mecanismo para agendamento e envio das mensagens.
    - <input type="checkbox"> Testar o envio das mensagens em diferentes cenários.
    - <input type="checkbox"> Garantir conformidade com políticas de privacidade e comunicação.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF14</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

??? info "🔧 O aplicativo permite ao usuário selecionar o tipo de serviço desejado, como implantação, limpeza ou reparo."

    **História de Usuário — US35: Seleção do Tipo de Serviço**

    ---

    #### **Título:** Seleção do Tipo de Serviço (Implantação, Limpeza ou Reparo)

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder selecionar o tipo de serviço que desejo contratar, seja implantação, limpeza ou reparo,  
    **Para que** eu possa receber um atendimento personalizado conforme minha necessidade específica.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve apresentar claramente as opções de serviço (implantação, limpeza, reparo).
    - <input type="checkbox"> O usuário deve conseguir selecionar apenas um tipo de serviço por solicitação.
    - <input type="checkbox"> A seleção do tipo de serviço deve influenciar nas opções e recomendações exibidas.
    - <input type="checkbox"> O sistema deve confirmar a seleção antes de prosseguir com o atendimento.
    - <input type="checkbox"> O usuário pode alterar a seleção antes da confirmação final.

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar componente de interface para seleção do tipo de serviço.
    - <input type="checkbox"> Integrar a seleção com o fluxo de atendimento do aplicativo.
    - <input type="checkbox"> Implementar validação para garantir seleção única por solicitação.
    - <input type="checkbox"> Testar impacto da seleção na exibição das opções e recomendações.
    - <input type="checkbox"> Desenvolver mensagens de confirmação e possibilidade de alteração.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF35</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

??? info "📍 O aplicativo permite ao usuário adicionar descrição textual, imagem e localização GPS da ocorrência."

    **História de Usuário — US36: Registro Detalhado da Ocorrência**

    ---

    #### **Título:** Adição de Descrição, Imagem e Localização GPS da Ocorrência

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** poder adicionar uma descrição textual, anexar imagens e registrar a localização GPS da ocorrência,  
    **Para que** eu possa fornecer informações completas e precisas sobre o evento reportado.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve permitir a inserção de texto descritivo livre sobre a ocorrência.
    - <input type="checkbox"> O usuário deve conseguir anexar uma ou mais imagens relacionadas à ocorrência.
    - <input type="checkbox"> O sistema deve capturar ou permitir o envio da localização GPS do usuário ou da ocorrência.
    - <input type="checkbox"> As informações adicionadas devem ser salvas corretamente e associadas à ocorrência.
    - <input type="checkbox"> O usuário deve receber confirmação do sucesso no registro dos dados.

    ---

    #### Subtarefas

    - <input type="checkbox"> Implementar campo de texto para descrição da ocorrência.
    - <input type="checkbox"> Desenvolver funcionalidade para upload e visualização de imagens.
    - <input type="checkbox"> Integrar captura ou envio manual da localização GPS.
    - <input type="checkbox"> Garantir armazenamento e associação dos dados ao registro da ocorrência.
    - <input type="checkbox"> Criar feedback visual para confirmação do envio.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF36</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>

??? info "🚌 O aplicativo oferece acesso a serviços de transporte público, incluindo o pré-cadastro do Cartão Mobilidade."

    **História de Usuário — US38: Acesso a Serviços de Transporte e Pré-cadastro do Cartão Mobilidade**

    ---

    #### **Título:** Acesso a Serviços de Transporte Público e Pré-cadastro do Cartão Mobilidade

    ---

    #### História

    **Como** um usuário do aplicativo,  
    **Eu quero** ter acesso aos serviços de transporte público e poder realizar o pré-cadastro do Cartão Mobilidade,  
    **Para que** eu possa utilizar o transporte público de forma mais prática e rápida, sem precisar fazer todo o cadastro presencialmente.

    ---

    #### Critérios de Aceitação

    - <input type="checkbox"> O sistema deve disponibilizar informações sobre os serviços de transporte público disponíveis.
    - <input type="checkbox"> O usuário deve poder iniciar o pré-cadastro do Cartão Mobilidade pelo aplicativo.
    - <input type="checkbox"> O sistema deve validar os dados fornecidos no pré-cadastro.
    - <input type="checkbox"> O usuário deve receber confirmação e orientações sobre os próximos passos após o pré-cadastro.
    - <input type="checkbox"> O sistema deve garantir a segurança e privacidade dos dados pessoais durante o processo.

    ---

    #### Subtarefas

    - <input type="checkbox"> Criar interface para acesso às informações e serviços de transporte público.
    - <input type="checkbox"> Desenvolver formulário para pré-cadastro do Cartão Mobilidade.
    - <input type="checkbox"> Implementar validação dos dados de pré-cadastro.
    - <input type="checkbox"> Integrar sistema de confirmação e orientações pós-cadastro.
    - <input type="checkbox"> Garantir conformidade com normas de segurança e privacidade.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF38</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Médio

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([João Marcos Moraes](https://github.com/JJOAOMARCOSS), 2025).</p></font>


??? info " O usuário deve poder alterar o tamanho da fonte e o contraste de cores"

    **História de Usuário — RF07: Ajuste de Tamanho de Fonte e Contraste**

    ---

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

    #### Subtarefas

    - <input type="checkbox"> Implementar controles deslizantes ou botões para ajuste de fonte.
    - <input type="checkbox"> Criar temas de alto contraste seguindo diretrizes de acessibilidade.
    - <input type="checkbox"> Aplicar mudanças dinamicamente em todos os componentes.
    - <input type="checkbox"> Persistir preferências de acessibilidade no perfil do usuário.
    - <input type="checkbox"> Testar conformidade com WCAG 2.1 nível AA.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF07</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


??? info " O aplicativo deve permitir modo escuro"

    **História de Usuário — RF08: Ativação do Modo Escuro**

    ---

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

    #### Subtarefas

    - <input type="checkbox"> Criar paleta de cores para o tema escuro.
    - <input type="checkbox"> Implementar toggle switch para alternar entre temas.
    - <input type="checkbox"> Adaptar todos os componentes visuais para o modo escuro.
    - <input type="checkbox"> Salvar preferência de tema no armazenamento local/perfil.
    - <input type="checkbox"> Validar contraste e legibilidade no modo escuro.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF08</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Média

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


??? info " O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos"

    **História de Usuário — RF10: Geração de Relatórios e Comprovantes**

    ---

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

    #### Subtarefas

    - <input type="checkbox"> Desenvolver templates para relatórios e comprovantes.
    - <input type="checkbox"> Implementar gerador de PDF com dados do agendamento.
    - <input type="checkbox"> Criar sistema de filtros para busca de agendamentos.
    - <input type="checkbox"> Adicionar código de verificação/QR Code aos comprovantes.
    - <input type="checkbox"> Integrar opções de compartilhamento e download.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF10</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


??? info " O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa"

    **História de Usuário — RF19: Localização de Ônibus em Tempo Real**

    ---

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

    #### Subtarefas

    - <input type="checkbox"> Integrar API de rastreamento de transporte público.
    - <input type="checkbox"> Implementar mapa interativo com marcadores de ônibus.
    - <input type="checkbox"> Desenvolver algoritmo de previsão de chegada.
    - <input type="checkbox"> Criar sistema de busca e filtro de linhas.
    - <input type="checkbox"> Implementar atualização automática da posição dos veículos.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF19</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


??? info " O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras"

    **História de Usuário — RF23: Acesso Facilitado a Serviços de Impostos**

    ---

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

    #### Subtarefas

    - <input type="checkbox"> Criar interface organizada para serviços de impostos.
    - <input type="checkbox"> Desenvolver guias passo a passo para cada tipo de imposto.
    - <input type="checkbox"> Integrar com sistemas de geração de boletos fiscais.
    - <input type="checkbox"> Implementar calendário de vencimentos e alertas.
    - <input type="checkbox"> Adicionar recursos visuais explicativos (imagens, vídeos).

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF23</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


??? info " Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes"

    **História de Usuário — RF34: Categorização de Ocorrências**

    ---

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

    #### Subtarefas

    - <input type="checkbox"> Definir taxonomia de categorias com órgãos responsáveis.
    - <input type="checkbox"> Criar interface de seleção hierárquica de categorias.
    - <input type="checkbox"> Implementar sistema de sugestão baseado em palavras-chave.
    - <input type="checkbox"> Mapear categorias com órgãos e departamentos responsáveis.
    - <input type="checkbox"> Adicionar tooltips explicativos para categorias ambíguas.

    ---

    #### Rastreabilidade

    - **Requisito Funcional Relacionado:** <a href="/elicitacao/req_elicitados/#anchor_RF">RF34</a>

    ---

    #### Estimativa de Esforço

    - **Prioridade:** Alta

    ----

    <font size="3"><p style="text-align: center">Elaborado pelo autor: ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


??? info "Acessar informações de agendamento e reagendamento de forma centralizada, promovendo praticidade e transparência ao cidadão"

	**História de Usuário — RF16: Centralização das Informações de Agendamento**

	---

	#### **Título:** Acesso Centralizado a Agendamentos e Reagendamentos

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** acessar informações de agendamento e reagendamento em um local centralizado,  
	**Para que** eu possa acompanhar meus compromissos com o GDF de maneira prática e organizada.

	---

	#### Critérios de Aceitação

	- <input type="checkbox"> O sistema deve exibir uma área unificada com os agendamentos e reagendamentos realizados.
	- <input type="checkbox"> As informações devem estar atualizadas em tempo real.
	- <input type="checkbox"> Deve ser possível visualizar detalhes como data, horário, local e serviço.
	- <input type="checkbox"> O sistema deve permitir filtrar por tipo de serviço ou data.
	- <input type="checkbox"> A interface deve ser responsiva e acessível em diferentes dispositivos.

	---

	#### Subtarefas

	- <input type="checkbox"> Mapear os serviços do GDF que exigem agendamento.
	- <input type="checkbox"> Criar interface para exibição consolidada de agendamentos.
	- <input type="checkbox"> Integrar sistema com as APIs dos serviços para obtenção dos dados.
	- <input type="checkbox"> Implementar filtros e ordenações por tipo de serviço e data.
	- <input type="checkbox"> Garantir acessibilidade da interface (WCAG).

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/brainstorming/#anchor_BS">BR17</a>

	---

	#### Estimativa de Esforço

	- **Prioridade:** Alta

	---

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>


??? info "Permitir que cidadãos reportem problemas da cidade de forma intuitiva, utilizando um mapa interativo para localização precisa"

	**História de Usuário — RF25: Reporte de Problemas pelo Mapa Interativo**

	---

	#### **Título:** Reporte de Problemas via Mapa Interativo

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** reportar problemas da cidade através de um mapa interativo,  
	**Para que** eu possa localizar facilmente o local da ocorrência e facilitar a identificação pelas autoridades responsáveis.

	---

	#### Critérios de Aceitação

	- <input type="checkbox"> O sistema deve disponibilizar um mapa interativo com zoom e movimentação.
	- <input type="checkbox"> O usuário deve poder clicar no mapa para marcar o local do problema.
	- <input type="checkbox"> Deve ser possível anexar uma descrição e foto ao ponto marcado.
	- <input type="checkbox"> O sistema deve registrar a coordenada geográfica do ponto selecionado.
	- <input type="checkbox"> O mapa deve permitir busca por endereço para facilitar a localização.

	---

	#### Subtarefas

	- <input type="checkbox"> Integrar API de mapa interativo (ex: Google Maps ou OpenStreetMap).
	- <input type="checkbox"> Criar interface para seleção e marcação do local da ocorrência.
	- <input type="checkbox"> Implementar campos para descrição e upload de imagem.
	- <input type="checkbox"> Validar dados geográficos e armazenar com o reporte.
	- <input type="checkbox"> Adicionar busca de endereços com sugestão automática.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/entrevista/#anchor_EN09">EN09</a>

	---

	#### Estimativa de Esforço

	- **Prioridade:** Média

	---

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>


??? info "Fornecer acesso rápido aos números de emergência da polícia, promovendo segurança e agilidade em situações críticas"

	**História de Usuário — RF26: Acesso a Serviços de Emergência**

	---

	#### **Título:** Acesso Rápido aos Números da Polícia

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** ter acesso imediato aos números de emergência da polícia,  
	**Para que** eu possa contatar as autoridades rapidamente em situações de perigo ou urgência.

	---

	#### Critérios de Aceitação

	- <input type="checkbox"> O sistema deve exibir claramente o número da polícia em uma área de fácil acesso.
	- <input type="checkbox"> O número deve estar disponível mesmo sem login no aplicativo.
	- <input type="checkbox"> Deve haver botão de chamada direta ao número de emergência.
	- <input type="checkbox"> O sistema deve permitir acesso rápido a partir da tela inicial.
	- <input type="checkbox"> A interface deve seguir padrões de acessibilidade.

	---

	#### Subtarefas

	- <input type="checkbox"> Identificar os serviços de emergência relevantes para exibir.
	- <input type="checkbox"> Criar componente visual destacado para número da polícia.
	- <input type="checkbox"> Implementar funcionalidade de chamada direta.
	- <input type="checkbox"> Garantir visibilidade do recurso mesmo sem autenticação.
	- <input type="checkbox"> Testar responsividade e acessibilidade do botão.

	---

	#### Rastreabilidade

	- **Requisitos Funcionais Relacionados:** <a href="../tec_elicitacao/entrevista/#anchor_EN10">EN10</a>, <a href="../tec_elicitacao/entrevista/#anchor_INT05">INT05</a>

	---

	#### Estimativa de Esforço

	- **Prioridade:** Alta

	---

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

??? info "Permitir que cidadãos solicitem serviços públicos de forma simples e eficiente, promovendo melhorias na infraestrutura urbana"

	**História de Usuário — RF28: Solicitação de Serviços Públicos**

	---

	#### **Título:** Solicitação de Serviços Públicos Diversos

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** solicitar serviços públicos como coleta de lixo e reparo de vias,  
	**Para que** a administração pública possa atender às necessidades da população de maneira mais ágil e organizada.

	---

	#### Critérios de Aceitação

	- <input type="checkbox"> O sistema deve apresentar uma lista de serviços públicos disponíveis para solicitação.
	- <input type="checkbox"> O usuário deve poder selecionar o serviço desejado e descrever o problema.
	- <input type="checkbox"> O sistema deve permitir a marcação da localização da solicitação.
	- <input type="checkbox"> O usuário deve poder anexar imagens da situação ao enviar a solicitação.
	- <input type="checkbox"> O sistema deve gerar um protocolo para acompanhamento da solicitação.

	---

	#### Subtarefas

	- <input type="checkbox"> Definir os serviços públicos que poderão ser solicitados via aplicativo.
	- <input type="checkbox"> Criar interface de seleção e detalhamento da solicitação.
	- <input type="checkbox"> Integrar módulo de geolocalização para marcação do local.
	- <input type="checkbox"> Implementar envio de imagens junto à solicitação.
	- <input type="checkbox"> Desenvolver sistema de protocolo e acompanhamento.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/analisededocumentos/#anchor_AD02">AD02</a>

	---

	#### Estimativa de Esforço

	- **Prioridade:** Alta

	---

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>

??? info "Permitir que o cidadão visualize no mapa onde serviços públicos foram solicitados, promovendo maior transparência e controle"

	**História de Usuário — RF29: Visualização de Solicitações em Mapa**

	---

	#### **Título:** Localização de Solicitações de Serviço no Mapa

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** visualizar no mapa os locais onde os serviços públicos foram solicitados,  
	**Para que** eu possa acompanhar as demandas da minha região e verificar se minha solicitação foi registrada corretamente.

	---

	#### Critérios de Aceitação

	- <input type="checkbox"> O sistema deve exibir um mapa com marcadores indicando os pontos de solicitação de serviços.
	- <input type="checkbox"> Cada marcador deve apresentar informações básicas da solicitação.
	- <input type="checkbox"> O mapa deve permitir filtragem por tipo de serviço e status da solicitação.
	- <input type="checkbox"> A interface deve permitir zoom e movimentação do mapa.
	- <input type="checkbox"> As informações devem ser atualizadas em tempo real.

	---

	#### Subtarefas

	- <input type="checkbox"> Integrar API de mapas com capacidade de marcação dinâmica.
	- <input type="checkbox"> Mapear dados das solicitações com coordenadas geográficas.
	- <input type="checkbox"> Criar marcadores customizados por tipo/status de serviço.
	- <input type="checkbox"> Implementar sistema de filtros por categoria e status.
	- <input type="checkbox"> Garantir responsividade e desempenho da visualização no mapa.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** <a href="../tec_elicitacao/analisededocumentos/#anchor_AD03">AD03</a>

	---

	#### Estimativa de Esforço

	- **Prioridade:** Alta

	---

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>


??? info "Disponibilizar um assistente virtual para responder automaticamente dúvidas frequentes dos usuários, oferecendo suporte ágil e contínuo"

	**História de Usuário — RF43: Integração com Assistente Virtual**

	---

	#### **Título:** Chatbot para Dúvidas Frequentes

	---

	#### História

	**Como** um cidadão usuário do aplicativo,  
	**Eu quero** interagir com um assistente virtual ou chatbot com respostas automáticas,  
	**Para que** eu possa esclarecer dúvidas frequentes rapidamente, sem depender de atendimento humano.

	---

	#### Critérios de Aceitação

	- <input type="checkbox"> O sistema deve disponibilizar um chatbot acessível a partir da tela inicial.
	- <input type="checkbox"> O assistente virtual deve responder perguntas comuns sobre uso do aplicativo e serviços oferecidos.
	- <input type="checkbox"> O chatbot deve reconhecer palavras-chave e apresentar respostas coerentes.
	- <input type="checkbox"> Deve haver opção de redirecionamento para atendimento humano em casos mais complexos.
	- <input type="checkbox"> As respostas do chatbot devem ser claras, objetivas e acessíveis.

	---

	#### Subtarefas

	- <input type="checkbox"> Definir as dúvidas frequentes e respostas padrão.
	- <input type="checkbox"> Integrar API ou serviço de chatbot com o aplicativo.
	- <input type="checkbox"> Criar interface de chat com histórico de conversas.
	- <input type="checkbox"> Implementar fallback para atendimento humano quando necessário.
	- <input type="checkbox"> Realizar testes de usabilidade com interações reais.

	---

	#### Rastreabilidade

	- **Requisito Funcional Relacionado:** RF43

	---

	#### Estimativa de Esforço

	- **Prioridade:** Alta

	---

	<font size="3"><p style="text-align: center">Elaborado pelo autor: ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025).</p></font>


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
