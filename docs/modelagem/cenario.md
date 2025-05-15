# Cenários

## Introdução

Cenários são narrativas detalhadas que descrevem situações reais ou plausíveis de uso de um sistema, tendo como foco principal os usuários, seus objetivos, ações e o ambiente em que estão inseridos. <q>Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002)<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Essa técnica contribui significativamente para a elicitação de requisitos, especialmente aqueles relacionados ao comportamento dos usuários frente ao sistema. Além de fornecer uma representação concreta das interações esperadas, os cenários demandam menor investimento de tempo e recursos quando comparados a protótipos, o que os torna uma ferramenta eficiente e acessível no processo de design de software.

## Metodologia

Neste projeto, a construção de cenários de uso foi orientada pela definição prévia de [perfis de usuário](../elicitacao/perfil_de_usuario.md), com o objetivo de representar interações plausíveis e contextualizadas com o aplicativo [eGDF](../index.md). Para a elaboração desses perfis, foram aplicadas técnicas de elicitação de requisitos, como [entrevistas](../elicitacao/tec_elicitacao/entrevista.md) com usuários reais, [análise de documentos](../elicitacao/tec_elicitacao/analise_documentos.md) relacionados ao sistema e sessões de [brainstorming](../elicitacao/tec_elicitacao/brainstorming.md) com partes interessadas e membros da equipe.

<q>Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste artefato será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente <a id="anchor_2" href="#FRM2">[2]</a> </q>. Dessa maneira, para a padronização e guia na construção dos cenários criamos um modelo a ser seguido, que está representado na Tabela 1.

## Cenários

### Tabela 1: Modelo do cenário


| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os Ator(res)es interagem                                            |
| Ator(res)       | Pessoa ou estrutura organizacional                                                           |
| Episódios  | Ação realizada por um ou vários Ator(res)es com participação de outros Ator(res)es utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário                                            |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 1: Consultando o calendário escolar do filho

| Elemento     | Descrição                                                                                                                                                                                                                                                                               |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Verificar as datas de início das aulas e feriados escolares para organizar a rotina familiar.                                                                                                                                                                                           |
| **Contexto**   | Um servidor público da educação, pai de um estudante da rede pública, tenta acessar o calendário escolar no início do ano letivo.                                                                                                                                                       |
| **Recursos**   | Smartphone com acesso à internet, aplicativo eGDF instalado.                                                                                                                                                                                                                            |
| **Ator(res)**       | Servidor público (usuário), sistema eGDF.                                                                                                                                                                                                                                               |
| **Episódios**  | - O usuário abre o eGDF pela primeira vez no ano.<br>- Busca pela opção de "Educação" no menu inicial.<br>- Clica em diferentes ícones sem sucesso até encontrar o calendário escolar.<br>- Consegue visualizar as datas importantes, embora tenha levado mais tempo do que o esperado. |
| **Restrições** | Design pouco intuitivo e possibilidade de dificuldade na navegação do menu.                                                                                                                                                                                                             |
| **Exceção**    | Dificuldade para localizar a funcionalidade de calendário dentro do app devido à navegação pouco intuitiva. <br>Erro de conexão à internet.                                                                                                                                                                             |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 2: Emitindo guia de pagamento do IPVA

| Elemento     | Descrição                                                                                                                                                                                                                                                           |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Emitir e pagar a guia do IPVA antes do vencimento.                                                                                                                                                                                                                  |
| **Contexto**   | Um estudante que acabou de comprar seu primeiro carro precisa emitir o boleto para pagamento do IPVA.                                                                                                                                                               |
| **Recursos**   | Smartphone, CPF e número do Renavam em mãos, conexão com internet.                                                                                                                                                                                                  |
| **Ator(res)**       | Estudante (usuário), sistema eGDF, banco.                                                                                                                                                                                                                           |
| **Episódios**  | - O estudante acessa o app eGDF e procura por "Tributos".<br>- Entra em “IPVA”, preenche os dados solicitados.<br>- Gera a guia e realiza o pagamento via internet banking.<br>- Finaliza satisfeito, mas com a impressão de que o caminho poderia ser mais direto. |
| **Restrições** | Layout confuso, o usuário pode se perder em encontrar a opção.                                                                                                                                                                                                      |
| **Exceção**    | Usuário não sabe onde encontrar a opção de emissão de IPVA e considera o layout confuso.  <br>Erro de conexão à internet.                                                                                                                                                                          |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 3: Consultando linhas e horários do transporte público

| Elemento     | Descrição                                                                                                                                                                                                                             |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Saber o horário do próximo ônibus para planejar o deslocamento até o trabalho.                                                                                                                                                        |
| **Contexto**   | Um professor universitário precisa ir ao campus e busca informações no eGDF antes de sair de casa.                                                                                                                                    |
| **Recursos**   | Smartphone, conexão à internet, localização ativada.                                                                                                                                                                                  |
| **Ator(res)**       | Professor (usuário), sistema eGDF, sistema de transporte público.                                                                                                                                                                     |
| **Episódios**  | - O usuário abre o app e acessa a seção “DF no Ponto”.<br>- Informa sua linha de ônibus e ponto de partida.<br>- Visualiza os próximos horários e a previsão de chegada.<br>- Organiza sua saída de casa com base nos dados exibidos. |
| **Restrições** | O app pode demorar para carregar ou mostrar informações desatualizadas sobre a linha.                                                                                                                                                 |
| **Exceção**    | O app demora para carregar ou mostra informações desatualizadas sobre a linha. <br>Erro de conexão à internet.                                                                                                                                                        |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 4: Primeiro contato com o aplicativo após recomendação

| Elemento     | Descrição                                                                                                                                                                                                                                                                           |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Conhecer os serviços disponíveis e descobrir funcionalidades úteis.                                                                                                                                                                                                                 |
| **Contexto**   | Um jovem tecnófilo ouve falar do app por um amigo e decide instalar para explorar os serviços digitais do governo.                                                                                                                                                                  |
| **Recursos**   | Smartphone, internet, acesso à loja de aplicativos.                                                                                                                                                                                                                                 |
| **Ator(res)**       | Jovem morador do DF, amigo que recomendou, sistema eGDF.                                                                                                                                                                                                                            |
| **Episódios**  | - O jovem baixa e instala o eGDF.<br>- Ao abrir, visualiza várias opções no menu, mas sem orientações claras.<br>- Clica em “Receitas e Tributos” por curiosidade, mas não entende a utilidade imediata.<br>- Fecha o app com a intenção de tentar novamente depois com mais tempo. |
| **Restrições** | O app pode parecer confuso ou desorganizado para um primeiro uso.                                                                                                                                                                                                                   |
| **Exceção**    | O usuário sente-se perdido na navegação inicial e fecha o app sem concluir nenhuma tarefa. <br>Erro de conexão à internet.                                                                                                                                                                                         |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 5: Usuário fazendo registro de problema na sua localização

| Elemento     | Descrição                                                                                                                                                                                                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Reportar um buraco em via pública à Administração Regional utilizando o aplicativo eGDF.                                                                                                                                                          |
| **Contexto**   | Morador do Distrito Federal nota um buraco crescente em sua rua após dias de chuva. À noite, em casa, decide reportar.                                                                                                                            |
| **Recursos**   | Smartphone, internet, aplicativo eGDF (módulo Administração 24 horas), câmera do celular.                                                                                                                                                         |
| **Ator(res)**       | Morador de 36 anos, servidor público com familiaridade intermediária com tecnologia, sistema eGDF, Administração Regional.                                                                                                                        |
| **Episódios**  | - O usuário acessa o app eGDF, entra na aba "Administração 24 horas".<br> - Escolhe a opção de reportar problema. <br> - Preenche dados e anexa foto do buraco. <br>- Insere a localização que está ocorrendo o problema. <br>- Envia a postagem. |
| **Restrições** | Limitações no tamanho ou tipo do arquivo de imagem; localização automática imprecisa.                                                                                                                                                             |
| **Exceção**    | Caso o app apresente erro no envio ou na captura da localização, o usuário tenta novamente mais tarde ou liga para a Administração Regional. <br>Erro de conexão à internet.                                                                                                     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 6: Acompanhando andamento de solicitação no GDF Presente

| Elemento       | Descrição                                                                                                                                                                                                     |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Verificar o status de uma solicitação feita anteriormente no sistema GDF Presente.                                                                                                                            |
| **Contexto**   | Um morador do DF acessa o app eGDF de sua residência durante o dia, alguns dias após realizar uma solicitação.                                                                                                |
| **Recursos**   | Aplicativo eGDF, smartphone, conexão com a internet.                                                                                                                                                          |
| **Ator**       | Morador do DF                                                                                                                                                                                                 |
| **Episódios**  | - O usuário abre o aplicativo e acessa a seção "Administração 24h".<br>- Seleciona "Minhas Solicitações".<br>- Localiza a solicitação de poda de árvore.<br>- Verifica que o status consta como “Em análise”. |
| **Restrições** | A solicitação só pode ser consultada se o usuário estiver logado com CPF vinculado à solicitação anterior.                                                                                                    |
| **Exceção**    | O sistema não mostra atualizações recentes, gerando insegurança sobre o andamento da demanda. <br>Erro de conexão à internet.                                                                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 7: Agendando atendimento presencial em órgão público

| Elemento       | Descrição                                                                                                                                                                                                        |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objetivo**   | Agendar atendimento presencial para emissão da segunda via do RG.                                                                                                                                                |
| **Contexto**   | Um cidadão do DF acessa o app eGDF pela manhã, em sua casa, buscando evitar filas em um posto do Na Hora.                                                                                                        |
| **Recursos**   | Aplicativo eGDF, smartphone, CPF do cidadão, conexão com a internet.                                                                                                                                             |
| **Ator**       | Cidadão do DF                                                                                                                                                                                                    |
| **Episódios**  | - O usuário acessa o app.<br>- Vai à seção de agendamento de serviços.<br>- Seleciona “Segunda via de RG”.<br>- Escolhe o local, data e horário disponíveis.<br>- Confirma o agendamento e recebe o comprovante. |
| **Restrições** | Apenas horários futuros e unidades com vagas disponíveis podem ser agendados.                                                                                                                                    |
| **Exceção**    | Poucas datas disponíveis, com unidades distantes ou não exibidas por instabilidade no sistema.  <br>Erro de conexão à internet.                                                                                                                 |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a>BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> <a id="FRM1" href="#anchor_1">1.</a>ROSSON, M. B.; CARROLL, J. M. Usability Engineering: Scenario-Based Development. San Francisco: Morgan Kaufmann, 2002.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/cenarios/docs/assets/modelagem/Cenarios.png" >
</div>

> <a id="FRM2" href="#anchor_2">2.</a>CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf. Acesso em: 10 de maio de 2023.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/cenarios/docs/assets/modelagem/Cenarios2.png" >
</div>


## Histórico de Versões

| Versão | Descrição    | Autor(es)                            | Data   | Revisor(es) | Data de Revisão |
|--------|------------|------------------------------------------|----------------------|-------------|----------------|
| 1.0    |  Adicionando introdução e metodologia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 15/05/2025 |
| 1.1    |  Adicionando tabelas de cenários e Bibliografia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 15/05/2025 |