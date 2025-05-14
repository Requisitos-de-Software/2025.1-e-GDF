# Cenários

## Introdução

Cenários são narrativas detalhadas que descrevem situações reais ou plausíveis de uso de um sistema, tendo como foco principal os usuários, seus objetivos, ações e o ambiente em que estão inseridos. <q>Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002)<a id="anchor_1" href="#FRM1">^1^</a> </q>.

Essa técnica contribui significativamente para a elicitação de requisitos, especialmente aqueles relacionados ao comportamento dos usuários frente ao sistema. Além de fornecer uma representação concreta das interações esperadas, os cenários demandam menor investimento de tempo e recursos quando comparados a protótipos, o que os torna uma ferramenta eficiente e acessível no processo de design de software.

## Metodologia

Neste projeto, a construção de cenários de uso foi orientada pela definição prévia de perfis de usuário, com o objetivo de representar interações plausíveis e contextualizadas com o aplicativo eGDF. Para a elaboração desses perfis, foram aplicadas técnicas de elicitação de requisitos, como entrevistas com usuários reais, análise de documentos relacionados ao sistema e sessões de brainstorming com partes interessadas e membros da equipe.

<q>Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste artefato será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente <a id="anchor_2" href="#FRM2">^2^</a> </q>. Dessa maneira, para a padronização e guia na construção dos cenários criamos um modelo a ser seguido, que está representado na Tabela 1.

## Cenários

### Tabela 1: Modelo do cenário


| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os atores interagem                                            |
| Ator       | Pessoa ou estrutura organizacional                                                           |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário                                            |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 1: Consultando o calendário escolar do filho

| Elemento     | Descrição |
|--------------|-----------|
| **Cenário**  | Consultando o calendário escolar do filho. |
| **Título**   | Acesso ao calendário escolar pela cartegoria de educação. |
| **Meta/Objetivo** | Verificar as datas de início das aulas e feriados escolares para organizar a rotina familiar. |
| **Contexto** | Um servidor público da educação, pai de um estudante da rede pública, tenta acessar o calendário escolar no início do ano letivo. |
| **Atores**   | Servidor público (usuário), sistema eGDF. |
| **Recursos** | Smartphone com acesso à internet, aplicativo eGDF instalado. |
| **Exceção**  | Dificuldade para localizar a funcionalidade de calendário dentro do app devido à navegação pouco intuitiva. |
| **Episódios** | - O usuário abre o eGDF pela primeira vez no ano.<br>- Busca pela opção de "Educação" no menu inicial.<br>- Clica em diferentes ícones sem sucesso até encontrar o calendário escolar.<br>- Consegue visualizar as datas importantes, embora tenha levado mais tempo do que o esperado. |

### Cenário 2: Emitindo guia de pagamento do IPVA 

| Elemento     | Descrição                                                                                                                                     |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Cenário     | Emitindo guia de pagamento do IPVA                                                                                                            |
| Título       | Emissão rápida da guia do IPVA                                                                                                                |
| Meta/Objetivo| Emitir e pagar a guia do IPVA antes do vencimento.                                                                                           |
| Contexto     | Um estudante que acabou de comprar seu primeiro carro precisa emitir o boleto para pagamento do IPVA.                                        |
| Atores       | Estudante (usuário), sistema eGDF, banco.                                                                                                     |
| Recursos     | Smartphone, CPF e número do Renavam em mãos, conexão com internet.                                                                           |
| Exceção      | Usuário não sabe onde encontrar a opção de emissão de IPVA e considera o layout confuso.                                                     |
| Episódios    | - O estudante acessa o app eGDF e procura por "Tributos".<br>- Entra em “IPVA”, preenche os dados solicitados.<br>- Gera a guia e realiza o pagamento via internet banking.<br>- Finaliza satisfeito, mas com a impressão de que o caminho poderia ser mais direto. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 3: Consultando linhas e horários do transporte público

| Elemento      | Descrição                                                                                                                                     |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Cenário       | Consultando linhas e horários do transporte público                                                                                           |
| Título        | Consulta de horários no "DF no Ponto" antes de sair de casa                                                                                   |
| Meta/Objetivo | Saber o horário do próximo ônibus para planejar o deslocamento até o trabalho.                                                                |
| Contexto      | Um professor universitário precisa ir ao campus e busca informações no eGDF antes de sair de casa.                                            |
| Atores        | Professor (usuário), sistema eGDF, sistema de transporte público.                                                                             |
| Recursos      | Smartphone, conexão à internet, localização ativada.                                                                                          |
| Exceção       | O app demora para carregar ou mostra informações desatualizadas sobre a linha.                                                               |
| Episódios     | - O usuário abre o app e acessa a seção “DF no Ponto”.<br>- Informa sua linha de ônibus e ponto de partida.<br>- Visualiza os próximos horários e a previsão de chegada.<br>- Organiza sua saída de casa com base nos dados exibidos. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 4: Primeiro contato com o aplicativo após recomendação

| Elemento      | Descrição                                                                                                                                     |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Cenário       | Primeiro contato com o aplicativo após recomendação                                                                                           |
| Título        | Primeiro uso do eGDF por recomendação de um colega                                                                                            |
| Meta/Objetivo | Conhecer os serviços disponíveis e descobrir funcionalidades úteis.                                                                           |
| Contexto      | Um jovem tecnófilo ouve falar do app por um amigo e decide instalar para explorar os serviços digitais do governo.                           |
| Atores        | Jovem morador do DF, amigo que recomendou, sistema eGDF.                                                                                      |
| Recursos      | Smartphone, internet, acesso à loja de aplicativos.                                                                                           |
| Exceção       | O usuário sente-se perdido na navegação inicial e fecha o app sem concluir nenhuma tarefa.                                                    |
| Episódios     | - O jovem baixa e instala o eGDF.<br>- Ao abrir, visualiza várias opções no menu, mas sem orientações claras.<br>- Clica em “Receitas e Tributos” por curiosidade, mas não entende a utilidade imediata.<br>- Fecha o app com a intenção de tentar novamente depois com mais tempo. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 5: Usuário fazendo registro de problema na sua localização
| Elemento   | Descrição                                                                                                               |
| ---------- | ----------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Reportar um buraco em via pública à Administração Regional utilizando o aplicativo eGDF.                              |
| Contexto   | Morador do Distrito Federal nota um buraco crescente em sua rua após dias de chuva. À noite, em casa, decide reportar. |
| Recursos   | Smartphone, internet, aplicativo eGDF (módulo Administração 24 horas), câmera do celular.                             |
| Ator       | Morador de 36 anos, servidor público com familiaridade intermediária com tecnologia.                                   |
| Episódios  | - O usuário acessa o app eGDF, entra na aba "Administração 24 horas". <br> - Escolhe a opção de reportar problema. <br> - Preenche dados e anexa foto do buraco. <br>- Insere a localização que está ocorrendo o problema. <br>- Envia a postagem. |
| Restrições | Limitações no tamanho ou tipo do arquivo de imagem; localização automática imprecisa.                                 |
| Exceção    | Caso o app apresente erro no envio ou na captura da localização, o usuário tenta novamente mais tarde ou liga para a Administração Regional. |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>



## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a>BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> <a id="FRM1" href="#anchor_1">1.</a>ROSSON, M. B.; CARROLL, J. M. Usability Engineering: Scenario-Based Development. San Francisco: Morgan Kaufmann, 2002.

> <a id="FRM2" href="#anchor_2">2.</a>CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf. Acesso em: 10 de maio de 2023.


## Histórico de Versões

| Versão | Descrição    | Autor(es)                            | Data   | Revisor(es) | Data de Revisão |
|--------|------------|------------------------------------------|----------------------|-------------|----------------|
| 1.0    |  Adicionando introdução e metodologia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) |...|