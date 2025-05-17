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
| Restrições | - Tempo de login exceder um tempo limite.<br>- O serviço de autenticação deve estar ativo.                                                |
| Exceção    | - O serviço gov.br estiver indisponível.<br>- Erro de conexão à internet durante o login. |

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
| Restrições | - Interface com muitos jargões técnicos.<br>- A interface não seguir padrões de acessibilidade (cores, tamanho de fonte, linguagem simples)                                                    |
| Exceção    | - Usuário se perder no aplicativo e não ter opção de ajuda.<br>- Erro de conexão à  internet, e não aparecer mensagem informando o erro.                        |

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
| Exceção    | - GPS desativado.<br>- Erro de conexão à internet e a notificação não ser entregue.            |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Ana Victória](https://github.com/navicg), 2025)</p></font>

### Cenário 4: Consulta centralizada de agendamentos e serviços

| Elemento     | Descrição                                                         |
|--------------|------------------------------------------------------------------|
| Objetivo     | Facilitar a visualização de todos os agendamentos em uma única tela. |
| Contexto     | Um servidor público deseja conferir todos seus compromissos no app. |
| Recursos     | App eGDF, agenda pessoal, conexão com internet.                  |
| Ator(res)    | Servidor público (usuário), sistema eGDF.                        |
| Episódios    | - Abre o app.<br>- Vai até “Meus Agendamentos”.<br>- Visualiza tudo em um só lugar. |
| Restrições   | Deve sincronizar com serviços de agendamento do GDF.             |
| Exceção      |- Sistema parceiro estiver fora do ar.<br>- Erro de conexão à internet. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Artur Mendonça Arruda](https://github.com/ArtyMend07), 2025)</p></font>

---

### Cenário 5: Assistente virtual com voz

| Elemento     | Descrição                                                         |
|--------------|------------------------------------------------------------------|
| Objetivo     | Ajudar o usuário por meio de comandos de voz com acessibilidade. |
| Contexto     | Um cidadão com deficiência visual usa comandos para emitir boleto do IPVA. |
| Recursos     | Smartphone com microfone, app eGDF, sistema de voz.              |
| Ator(res)    | Cidadão com deficiência (usuário), sistema eGDF.                 |
| Episódios    | - Usuário diz “Emitir IPVA”.<br>- Assistente pergunta CPF.<br>- Responde por voz.<br>- Gera boleto. |
| Restrições   | - Reconhecimento de voz pouco intuitivo.     |
| Exceção      |- Ambiente com muito ruído.<br>- Perda de conexão com a internet durante o uso da assistente virtual com voz.             |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Artur Mendonça Arruda](https://github.com/ArtyMend07), 2025)</p></font>

---

### Cenário 6: Tutoriais passo a passo

| Elemento     | Descrição                                                         |
|--------------|------------------------------------------------------------------|
| Objetivo     | Ajudar novos usuários a entenderem o funcionamento do app.       |
| Contexto     | Uma nova usuária acessa o app para agendar consulta médica.      |
| Recursos     | App eGDF, tutoriais animados.                                    |
| Ator(res)    | Usuária iniciante, sistema eGDF.                                 |
| Episódios    | - App detecta primeiro uso.<br>- Exibe passo a passo para agendamento.<br>- Usuária realiza com sucesso. |
| Restrições   | - O tutorial ser muito extenso<br> - Ser pouco intuitivo.                   |
| Exceção      |- Usuário ignorar o tutorial.<br>- Perda de conexão da internet durante o tutorial.” |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Artur Mendonça Arruda](https://github.com/ArtyMend07), 2025)</p></font>

---
### Cenário 7: Alterar tamanho da fonte e contraste

| Elemento     | Descrição                                                                 |
|--------------|---------------------------------------------------------------------------|
| Objetivo     | Tornar o app acessível a pessoas com deficiência visual ou sensibilidade ocular. |
| Contexto     | Um aposentado deseja aumentar o tamanho da fonte e ativar alto contraste. |
| Recursos     | Smartphone, app eGDF, configurações de acessibilidade.                    |
| Ator(res)    | Aposentado (usuário), sistema eGDF.                                       |
| Episódios    | - Acessa configurações. <br> - Altera fonte para “Grande”. <br> - Ativa “Modo Alto Contraste”. |
| Restrições   | Interface não se ajustar dinamicamente as alterações.                |
| Exceção      | - Dispositivo não ser compatível com essa funcionalidade.<br>- Erro de conexão ao fazer as alterações.   |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

### Cenário 8: Modo escuro

| Elemento     | Descrição                                                                 |
|--------------|---------------------------------------------------------------------------|
| Objetivo     | Reduzir o cansaço visual e economizar bateria em telas OLED.              |
| Contexto     | Um usuário utiliza o app à noite e ativa o modo escuro.                   |
| Recursos     | App eGDF, configurações do sistema, suporte a temas.                      |
| Ator(res)    | Usuário noturno, sistema eGDF.                                            |
| Episódios    | - Acessa configurações. <br> - Ativa “Modo Escuro”. <br> - Interface muda imediatamente. |
| Restrições   | Não funcionar pra todos os dispositivos e telas.                            |
| Exceção      | - Haver incompatibilidade com a versão do Android/iOS.<br>- Erro de conexão ao mudar para o modo escuro.   |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>


### Cenário 9: O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos

| Elemento   | Descrição                                                                                                                                         |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário acesse relatórios e comprovantes dos agendamentos realizados, para fins de controle, conferência ou documentação.          |
| **Contexto**   | O usuário está autenticado no sistema via portal web corporativo durante o horário comercial, em um ambiente de trabalho com acesso à internet.    |
| **Recursos**   | Sistema de agendamentos, banco de dados de agendamentos, módulo de relatórios, interface gráfica, botão "Gerar Relatório", botão "Visualizar Comprovante". |
| **Ator(res)**  | Usuário final (ex: servidor público ou atendente administrativo)                                                                               |
| **Episódios**  |- O usuário acessa o módulo de agendamentos no sistema <br> - Seleciona o período desejado <br> - Clica em "Gerar Relatório" <br> - O sistema gera e exibe o relatório <br> - O usuário seleciona um agendamento específico <br> - Clica em "Visualizar Comprovante" <br> - O sistema exibe ou permite o download do comprovante em PDF. |
| **Restrições** | - O acesso aos relatórios e comprovantes só é permitido a usuários autenticados com permissão adequada. <br> - Relatórios só podem ser gerados para datas válidas. |
| **Exceção**    | - Não haver agendados dísponiveis na data selacionado e o sistema não informar isso.<br>- Erro de conexão à internet.<br> - O sistema não gerar o relátorio corretamente.      |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

### Cenário 10: Alterar idioma do aplicativo

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| Objetivo   | Permitir que o usuário utilize o aplicativo no idioma de sua preferência.                     |
| Contexto   | O usuário acessa o aplicativo em um ambiente multilíngue, como uma viagem internacional.       |
| Recursos   | Smartphone, aplicativo, configurações de idioma.                                               |
| Ator(res)  | Usuário cidadão, sistema eGDF.                                                                 |
| Episódios  | - Usuário acessa as configurações do app. <br> - Clica na opção "Idioma". <br> - Seleciona o idioma desejado (ex: inglês). <br> - O app é recarregado com os textos traduzidos. |
| Restrições | - Nem todos os conteúdos podem estar disponíveis em todos os idiomas. <br> - A tradução deve ser previamente implementada para cada idioma. |
| Exceção    | - Falha ao aplicar o novo idioma. <br> - Tradução ausente para o idioma escolhido.<br> - Erro de conexão à internet ao mudar de idioma         |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 11: Personalizar preferências e perfis para recomendações

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| Objetivo   | Permitir que o usuário configure seu perfil e preferências para receber recomendações mais relevantes. |
| Contexto   | O usuário está criando ou editando seu perfil dentro do aplicativo em casa, durante o uso regular. |
| Recursos   | Smartphone, aplicativo, base de dados de preferências.                                         |
| Ator(res)  | Usuário cidadão, sistema eGDF.                                                                 |
| Episódios  | - Usuário acessa a área de "Preferências". <br> - Informa dados como localização, faixa etária e interesses. <br> - Salva o perfil personalizado. <br> - O sistema usa as informações para oferecer recomendações de serviços públicos. |
| Restrições | - O sistema deve proteger os dados pessoais conforme a LGPD. <br> - As recomendações dependem das informações fornecidas. |
| Exceção    | - O usuário não finaliza o cadastro. <br> - O sistema falha ao salvar as preferências.<br>- Ocorre um erro de internet ao personalizar as preferências.     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Cenário 12: Enviar mensagens curtas sobre vencimentos e lembretes

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| Objetivo   | Informar o usuário sobre vencimentos de prazos ou eventos importantes através de mensagens curtas. |
| Contexto   | O usuário tem prazos a cumprir (como pagamento de taxas) e está com o app instalado no celular. |
| Recursos   | Smartphone, aplicativo, notificações push ou SMS, banco de dados de prazos.                    |
| Ator(res)  | Sistema eGDF, usuário cidadão.                                                                 |
| Episódios  | - O sistema verifica prazos próximos no cadastro do usuário. <br> - Gera mensagem com lembrete. <br> - Envia notificação para o celular do usuário. <br> - O usuário recebe e visualiza o lembrete. |
| Restrições | - O usuário não ter autorizado o envio de notificações. <br> - Os lembretes não serem configurados previamente. |
| Exceção    | - O usuário está sem internet ou com notificações desativadas. <br> - Mensagens duplicadas ou fora de contexto são enviadas. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025)</p></font>

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
| 1.0    |  Adicionando introdução e metodologia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 15/05/2025 |
| 1.1    |  Adicionando tabelas de cenários e Bibliografia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|14/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 15/05/2025 |
| 1.2    |  Adição dos 3 primeiros cenários baseados nos requisitos funcionais não implementados| [Ana Victória](https://github.com/navicg)|16/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.3    | Cenários 4, 5 e 6 incorporados ao documento. | [Artur Mendonça Arruda](https://github.com/ArtyMend07) |16/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.4    | Elaboração do sétimo, oitavo e nono cenário | [Gabriel Lopes](https://github.com/BrzGab)|16/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.5    | Adição do cenário 10, 11 e 12 no artefato. | [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)|16/04/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |