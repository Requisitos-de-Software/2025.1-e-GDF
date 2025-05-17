# Cenários

## Introdução

Cenários são narrativas detalhadas que descrevem situações reais ou plausíveis de uso de um sistema, tendo como foco principal os usuários, seus objetivos, ações e o ambiente em que estão inseridos. <q>Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002)<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Essa técnica contribui significativamente para a elicitação de requisitos, especialmente aqueles relacionados ao comportamento dos usuários frente ao sistema. Além de fornecer uma representação concreta das interações esperadas, os cenários demandam menor investimento de tempo e recursos quando comparados a protótipos, o que os torna uma ferramenta eficiente e acessível no processo de design de software.

## Metodologia

Neste projeto, a construção de cenários de uso foi orientada pela definição prévia dos [requisitos elicitados](../elicitacao/req_elicitados.md), com o objetivo de representar interações plausíveis e contextualizadas com o aplicativo [eGDF](../index.md). Foram utilizados os **requisitos funcionais** não implementados para a elaboração desses cenários, que foram elicitados a partir das seguintes técnicas de elicitação de requisitos, como [entrevistas](../elicitacao/tec_elicitacao/entrevista.md) com usuários reais, [análise de documentos](../elicitacao/tec_elicitacao/analise_documentos.md) relacionados ao sistema, sessões de [brainstorming](../elicitacao/tec_elicitacao/brainstorming.md) com partes interessadas e membros da equipe e [introspecção](../elicitacao/tec_elicitacao/introspeccao.md) e cada participante da equipe ficou responsável pela elaboração de 3 cenários.

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


### Cenário 1: Realizar login de forma simples e rápida

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário acesse o aplicativo rapidamente sem complicações.                    |
| Contexto   | Um cidadão tenta abrir o app e acessar seus serviços públicos.                              |
| Recursos   | Smartphone, app eGDF, conexão com internet.                                                  |
| Ator(res)  | Usuário cidadão, sistema eGDF.                                                               |
| Episódios  | - Usuário abre o app.<br>- Seleciona "Entrar com gov.br".<br>- Insere os dados da sua conta<br>- Realiza login.               |
| Restrições | - Tempo de login não pode exceder 5 segundos.<br>- O serviço de autenticação deve estar ativo                                                 |
| Exceção    | - Se o serviço gov.br estiver indisponível, oferecer login alternativo.<br>- Em caso de erro de conexão à internet, exibir mensagem de falha e solicitar nova tentativa. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Ana Victória](https://github.com/navicg), 2025)</p></font>
---

### Cenário 2: Acesso com pouca familiaridade tecnológica

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Garantir acesso ao app por pessoas com pouca experiência em tecnologia.                     |
| Contexto   | Um idoso utiliza o app pela primeira vez.                                                    |
| Recursos   | Smartphone, app eGDF.                                                                        |
| Ator(res)  | Idoso (usuário), sistema eGDF.                                                               |
| Episódios  | - Usuário acessa app.<br>- Usa ícones simples e textos descritivos.<br>- Encontra serviços. |
| Restrições | - Interface deve evitar jargões técnicos.<br>- A interface deve seguir padrões de acessibilidade (cores, tamanho de fonte, linguagem simples)                                                    |
| Exceção    | - Caso o usuário se perca, botão "Ajuda" o redireciona.<br>- Em caso de erro de conexão à internet, exibir instrução para verificar a rede.                        |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Ana Victória](https://github.com/navicg), 2025)</p></font>
---

### Cenário 3: Notificações baseadas em localização

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Enviar notificações úteis com base na localização do usuário.                               |
| Contexto   | Um cidadão passa próximo a um posto de vacinação.                                           |
| Recursos   | GPS do celular, app eGDF, servidor de notificações.                                         |
| Ator(res)  | Cidadão (usuário), sistema eGDF.                                                             |
| Episódios  | - Sistema detecta proximidade.<br>- Envia alerta “Vacinação disponível aqui perto”.         |
| Restrições | - Necessário consentimento para uso de localização.<br>- O usuário deve ter permitido o recebimento de notificações        .                                  |
| Exceção    | - Caso o GPS esteja desativado, nenhuma notificação é enviada.<br>- Em caso de erro de conexão à internet, a notificação não é enviada e será reagendada.            |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Ana Victória](https://github.com/navicg), 2025)</p></font>

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
| 1.0    |  Adicionando introdução e metodologia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.1    |  Adicionando tabelas de cenários e Bibliografia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.2    |  Adição dos 3 primeiros cenários baseados nos requisitos funcionais não implementados| [Ana Victória](https://github.com/navicg)|16/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |