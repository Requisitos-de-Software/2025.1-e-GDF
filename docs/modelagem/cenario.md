# Cenários

## Introdução

Cenários são narrativas detalhadas que descrevem situações reais ou plausíveis de uso de um sistema, tendo como foco principal os usuários, seus objetivos, ações e o ambiente em que estão inseridos. <q>Os cenários podem ser utilizados em diversas etapas do processo, com diferentes objetivos: para descrever uma história num domínio de atividade, visando capturar requisitos e auxiliar no entendimento da atividade, levantar questões sobre a introdução de tecnologia, explorar diferentes soluções de design e avaliar se um produto satisfaz a necessidade dos seus usuários (Rosson e Carroll, 2002)<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Essa técnica contribui significativamente para a elicitação de requisitos, especialmente aqueles relacionados ao comportamento dos usuários frente ao sistema. Além de fornecer uma representação concreta das interações esperadas, os cenários demandam menor investimento de tempo e recursos quando comparados a protótipos, o que os torna uma ferramenta eficiente e acessível no processo de design de software.

## Metodologia

Neste projeto, a construção de cenários de uso foi orientada pela definição prévia dos [requisitos elicitados](../elicitacao/req_elicitados.md), com o objetivo de representar interações plausíveis e contextualizadas com o aplicativo [eGDF](../index.md). Foram utilizados os **requisitos funcionais** não implementados para a elaboração desses cenários, que foram elicitados a partir das seguintes técnicas de elicitação de requisitos, como [entrevistas](../elicitacao/tec_elicitacao/entrevista.md) com usuários reais, [análise de documentos](../elicitacao/tec_elicitacao/analise_documentos.md) relacionados ao sistema, sessões de [brainstorming](../elicitacao/tec_elicitacao/brainstorming.md) com partes interessadas e membros da equipe e [introspecção](../elicitacao/tec_elicitacao/introspeccao.md) e cada participante da equipe ficou responsável pela elaboração de 2 à 3 cenários, como pode ser observado na **Tabela 1**, em que mostra os cenários que cada um participou.

<q>Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste artefato será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente <a id="anchor_2" href="#FRM2">[2]</a> </q>. Dessa maneira, para a padronização e guia na construção dos cenários criamos um modelo a ser seguido, que está representado na **Tabela 2**.


### Tabela 1: Cenários que cada participante desenvolveu

**Legenda:**

- **CENxx**: Identificador do cenário desenvolvido

|Cenário Realizado| Participante|
|------|-------|
|CEN 01, 02 e 03| [Ana Victória Guedes da Costa](https://github.com/navicg) |
|CEN 04, 05 e 06 |  [Artur Mendonça Arruda](https://github.com/ArtyMend07) |
| CEN 07, 08 e 09  |  [Gabriel Lopes](https://github.com/BrzGab)  |
| CEN 10, 11 e 12    |    [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)   |
| CEN 13 e 14  |  [Lucas Mendonça](https://github.com/lucasarruda9)   |
| CEN 15 e 16| [Karoline Luz da Conceição](https://github.com/KarolineLuz) |
|CEN 17, 18 e 19.|  [Luiza da Silva Pugas](https://github.com/Luizaxx)| 

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [Ana Victória](https://github.com/navicg) e [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

### Tabela 2: Modelo do cenário

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

## Cenários

### Cenário 1: Realizar login de forma simples e rápida

**Rastreabilidade do RF01**: [BR01, AD01](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

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

**Rastreabilidade do RF02**: [BR02](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

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

**Rastreabilidade do RF03**: [BR03](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Enviar notificações úteis com base na localização do usuário.                               |
| Contexto   | Um cidadão passa próximo a um posto de vacinação.                                           |
| Recursos   | GPS do celular, app eGDF, servidor de notificações.                                         |
| Ator(res)  | Cidadão (usuário), sistema eGDF.                                                             |
| Episódios  | - Sistema detecta proximidade.<br>- Sistema personaliza a notificação com base no perfil do usuário (ex: idade, grupo prioritário).<br>- Envia alerta “Vacinação disponível aqui perto”.<br> - Usuário toca na notificação e é direcionado para a tela com mais informações (endereço, horário).<br>- O usuário confirma interesse.    |
| Restrições | - Necessário consentimento para uso de localização.<br>- O usuário deve ter permitido o recebimento de notificações        .                                  |
| Exceção    | - GPS desativado.<br>- Erro de conexão à internet e a notificação não ser entregue.            |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Ana Victória](https://github.com/navicg), 2025)</p></font>

---
### Cenário 4: Consulta centralizada de agendamentos e serviços

**Rastreabilidade do RF04**: [BR04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)  

| Elemento     | Descrição                                                         |
|--------------|------------------------------------------------------------------|
| **Objetivo**     | Facilitar a visualização de todos os agendamentos em uma única tela. |
| **Contexto**   | Um servidor público deseja conferir todos seus compromissos no app. |
| **Recursos**     | App eGDF, agenda pessoal, conexão com internet.                  |
| **Ator(res)**    | Servidor público (usuário), sistema eGDF.                        |
| **Episódios**    | - Abre o app.<br>- Vai até “Meus Agendamentos”.<br>- Visualiza tudo em um só lugar. |
| **Restrições**   | Deve sincronizar com serviços de agendamento do GDF.             |
| **Exceção**      |- Sistema parceiro estiver fora do ar.<br>- Erro de conexão à internet. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Artur Mendonça Arruda](https://github.com/ArtyMend07), 2025)</p></font>

---

### Cenário 5: Assistente virtual com voz

**Rastreabilidade do RF05**: [BR05, AD05, INT13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

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

**Rastreabilidade do RF06**:[BR06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)  

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

**Rastreabilidade do RF07**: [BR07, EN08, AD08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

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

**Rastreabilidade do RF08**: [BR08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)  

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


---
### Cenário 9: O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos

**Rastreabilidade do RF10**: [BR11](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

| Elemento   | Descrição                                                                                                                                         |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário acesse relatórios e comprovantes dos agendamentos realizados, para fins de controle, conferência ou documentação.          |
| **Contexto**   | O usuário está autenticado no sistema via portal web corporativo durante o horário comercial, em um ambiente de trabalho com acesso à internet.    |
| **Recursos**   | App do eGDF, Sistema de agendamentos, banco de dados de agendamentos, módulo de relatórios, interface gráfica, botão "Gerar Relatório", botão "Visualizar Comprovante". |
| **Ator(res)**  | Usuário final (ex: servidor público ou atendente administrativo)                                                                               |
| **Episódios**  |- O usuário acessa o módulo de agendamentos no sistema <br> - Seleciona o período desejado <br> - Clica em "Gerar Relatório" <br> - O sistema gera e exibe o relatório <br> - O usuário seleciona um agendamento específico <br> - Clica em "Visualizar Comprovante" <br> - O sistema exibe ou permite o download do comprovante em PDF. |
| **Restrições** | - O acesso aos relatórios e comprovantes só é permitido a usuários autenticados com permissão adequada. <br> - Relatórios só podem ser gerados para datas válidas. |
| **Exceção**    | - Não haver agendados dísponiveis na data selacionado e o sistema não informar isso.<br>- Erro de conexão à internet.<br> - O sistema não gerar o relátorio corretamente.      |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

### Cenário 10: Alterar idioma do aplicativo

 **Rastreabilidade do RF12**: [BR13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| Objetivo   | Permitir que o usuário utilize o aplicativo no idioma de sua preferência.                     |
| Contexto   | O usuário acessa o aplicativo em um ambiente multilíngue, como uma viagem internacional.       |
| Recursos   | Smartphone, aplicativo do eGDF, configurações de idioma.                                               |
| Ator(res)  | Usuário cidadão, sistema eGDF.                                                                 |
| Episódios  | - Usuário acessa as configurações do app. <br> - Clica na opção "Idioma". <br> - Seleciona o idioma desejado (ex: inglês). <br> - O app é recarregado com os textos traduzidos. |
| Restrições | - Nem todos os conteúdos podem estar disponíveis em todos os idiomas. <br> - A tradução deve ser previamente implementada para cada idioma. |
| Exceção    | - Falha ao aplicar o novo idioma. <br> - Tradução ausente para o idioma escolhido.<br> - Erro de conexão à internet ao mudar de idioma         |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 11: Personalizar preferências e perfis para recomendações

 **Rastreabilidade do RF13**: [BR14](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| Objetivo   | Permitir que o usuário configure seu perfil e preferências para receber recomendações mais relevantes. |
| Contexto   | O usuário está criando ou editando seu perfil dentro do aplicativo em casa, durante o uso regular. |
| Recursos   | Smartphone, aplicativo do eGDF, base de dados de preferências.                                         |
| Ator(res)  | Usuário cidadão, sistema eGDF.                                                                 |
| Episódios  | - Usuário acessa a área de "Preferências". <br> - Informa dados como localização, faixa etária e interesses. <br> - Salva o perfil personalizado. <br> - O sistema usa as informações para oferecer recomendações de serviços públicos. |
| Restrições | - O sistema deve proteger os dados pessoais conforme a LGPD. <br> - As recomendações dependem das informações fornecidas. |
| Exceção    | - O usuário não finaliza o cadastro. <br> - O sistema falha ao salvar as preferências.<br>- Ocorre um erro de internet ao personalizar as preferências.     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 12: Enviar mensagens curtas sobre vencimentos e lembretes

 **Rastreabilidade do RF14**:  [BR15](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| Objetivo   | Informar o usuário sobre vencimentos de prazos ou eventos importantes através de mensagens curtas. |
| Contexto   | O usuário tem prazos a cumprir (como pagamento de taxas) e está com o app instalado no celular. |
| Recursos   | Smartphone, aplicativo eGDF, notificações push ou SMS, banco de dados de prazos.                    |
| Ator(res)  | Sistema eGDF, usuário cidadão.                                                                 |
| Episódios  | - O sistema verifica prazos próximos no cadastro do usuário. <br> - Gera mensagem com lembrete. <br> - Envia notificação para o celular do usuário. <br> - O usuário recebe e visualiza o lembrete. |
| Restrições | - O usuário não ter autorizado o envio de notificações. <br> - Os lembretes não serem configurados previamente. |
| Exceção    | - O usuário está sem internet ou com notificações desativadas. <br> - Mensagens duplicadas ou fora de contexto são enviadas. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

**Vídeo X** - Validação dos cenários 10, 11 e 12.

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/uetRdOUmZXI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/uetRdOUmZXI" target="_blank">Clique aqui para assistir no YouTube</a></p>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Luiz Guilherme forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF]()

| Participante   | Entrevistador                                             | Data       | Horário       | Local |
| -------------- | ----------------------------------------------------- | ---------- | ------------- | ----- |
| Luiz Guilherme | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 17/06/2025 | 09:00 - 09:30 | FGA   |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

### Cenário 13: Acompanhamento de pendências na área educacional 

 **Rastreabilidade do RF24**: [EN06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| **Objetivo**  | Permitir o acompanhamento de pendências escolares relacionadas ao usuário |
| **Contexto**   | O usuário acessa o aplicativo para ver a sua frequência escolar . |
| **Recursos**   | Smartphone com aplicativo do eGDF instalado, autenticação gov, base de dados escolares                    |
| **Ator(res)**  | Alunos (Usuário).                                                                 |
| **Episódios** | - O usuário faz login no aplicativo. <br> - O sistema consulta a base de dados escolares. <br> - O usuário acessa a seção sobre educação <br> - O usuário visualiza a sua frequência escolar. |
| **Restrições** | - O usuário precisa estar vinculado a uma unidade escolar cadastrada. <br> - Base de dados deve estar atualizada e disponível. |
| **Exceção**    | - Falha na conexão com a internet. <br> - Base de dados indisponível para consulta. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

---

### Cenário 14: Notificações por categorias do aplicativo

 **Rastreabilidade do RF17**: [BR19](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento   | Descrição                                                                                      |
|------------|------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário receba notificações classificadas por categorias |
| **Contexto**   | O usuário deseja identificar qual categoria pertence a notificação . |
| **Recursos**   | Smartphone com aplicativo do eGDF instalado, autenticação gov, conexão com a internet                    |
| **Ator(res)**  | Usuário.                                                                 |
| **Episódios**  | - O usuário faz login no aplicativo. <br> - O sistema envia notificações classificadas por categoria. <br> - O usuário identifica a categoria e a informação relacionada. |
| **Restrições** | - O usuário precisa autorizar o recebimento de notificações. <br> - O usuário precisa estar conectado com a internet. |
| **Exceção**    | - Falha na conexão com a internet. <br> - Erro de sincronização entre o backend e o app. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>


---
### Cenário 15: Acessar informações de reagendamentos em um só lugar

 **Rastreabilidade do RF16**: [BR17](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento    | Descrição                                                                                                                                   |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário acesse informações de agendamentos existentes e realize o reagendamento de forma prática e centralizada pelo app do eGDF. |
| **Contexto**   | O usuário está em casa, no período da noite, utilizando seu smartphone com acesso à internet para consultar e alterar seus agendamentos.         |
| **Recursos**   | Aplicativo do eGDF, conexão com o banco de dados de agendamentos, interface gráfica de visualização e reagendamento.                          |
| **Ator(res)**  | Usuário (paciente) do eGDF                                                                                                                  |
| **Episódios**  |- O usuário abre o aplicativo do eGDF<br>- Acessa a seção de “Meus Agendamentos”<br>- Visualiza seus agendamentos futuros e seleciona um deles para reagendar.<br>- O app apresenta as datas e horários disponíveis<br>- O usuário escolhe uma nova data e confirma a alteração<br>- O sistema atualiza automaticamente o agendamento. |
| **Restrições** |- O reagendamento só pode ser feito com no mínimo 24 horas de antecedência<br>- É necessário que o usuário esteja autenticado no sistema.         |
| **Exceção**    | - O usuário tentar reagendar para uma data sem disponibilidade<br>- Erro de conexão à internet |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

---

### Cenário 16: Reportar problemas urbanos por meio de um mapa interativo

 **Rastreabilidade do RF25**: [EN09](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento    | Descrição                                                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Permitir que o usuário reporte problemas urbanos (como buracos nas ruas, iluminação pública, lixo acumulado) por meio de um mapa interativo no app do eGDF. |
| **Contexto**   | O usuário está caminhando pelo bairro durante o dia, percebe um buraco em via pública e decide reportar o problema imediatamente pelo aplicativo.         |
| **Recursos**   | Aplicativo do eGDF, mapa interativo com geolocalização, formulário de registro de problema, câmera do celular.                                           |
| **Ator(res)**  | Usuário (morador da cidade), sistema municipal de manutenção urbana.                                                                                     |
| **Episódios**  | - O usuário abre o aplicativo do eGDF<br> - Acessa a funcionalidade de mapa interativo<br>- Localiza o ponto exato do problema<br>- Adiciona uma descrição e uma foto, e envia o relato<br>- O sistema registra a ocorrência e a encaminha para a secretaria responsável. |
| **Restrições** | O envio do problema exige conexão com a internet; o usuário precisa conceder permissão de acesso à localização e à câmera.                                |
| **Exceção**    | Caso a localização não seja detectada automaticamente, o usuário pode selecionar manualmente o local no mapa; se estiver sem internet, o app salva o relato localmente e envia quando a conexão for restabelecida. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

---
### Cenário 17: Autenticação via gov.br de forma segura e por reconhecimento facial

 **Rastreabilidade do RF22**: [EN04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

| Elemento   | Descrição |
|------------|-----------|
| **Objetivo** | Garantir que o usuário acesse o aplicativo de forma segura por meio da autenticação na plataforma gov.br, utilizando recursos como reconhecimento facial. |
| **Contexto** | O usuário está utilizando um dispositivo móvel com câmera frontal funcional e conexão com a internet, no momento de realizar login no aplicativo. |
| **Recursos** | Plataforma gov.br, câmera do dispositivo, sistema de login do aplicativo. |
| **Ator(res)** | Usuário final, plataforma gov.br |
| **Episódios** | - O usuário escolhe a opção de login via gov.br<br> - É redirecionado para a autenticação segura<br>- Realiza reconhecimento facial com sucesso e retorna autenticado ao aplicativo. |
| **Restrições** | - A autenticação exige conta ativa e verificada no gov.br<br> - O dispositivo deve possuir câmera compatível. |
| **Exceção** | - Reconhecimento facial pode falhar pelo gov.br estar indisponível<br>- A câmera pode apresentar problemas que impessam o uso para o reconhecimento facial<br> - Pode ocorrer erro de conexão à internet|


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

---

### Cenário 18: Compartilhar ou Salvar Informações Importantes

 **Rastreabilidade do RF18**: [BR20](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) 

| Elemento   | Descrição |
|------------|-----------|
| **Objetivo** | Permitir que o usuário compartilhe ou salve comprovantes e protocolos gerados pelo aplicativo após a realização de ações importantes (como matrículas, atualizações de dados ou solicitações). |
| **Contexto** | O usuário está autenticado no aplicativo eGDF, utilizando seu smartphone com acesso à internet, imediatamente após concluir uma ação que gera um protocolo ou comprovante. |
| **Recursos** | Interface do aplicativo eGDF, visualização de protocolo/comprovante em PDF, sistema de compartilhamento nativo do dispositivo, armazenamento local do celular. |
| **Ator(res)** | Usuário final. |
| **Episódios** |- Após concluir uma matrícula ou solicitação, o aplicativo exibe o comprovante na tela<br>-  O usuário escolhe entre "Salvar no dispositivo" ou "Compartilhar", podendo enviar via e-mail, WhatsApp ou outro app instalado<br>- O sistema realiza a ação e exibe uma confirmação. |
| **Restrições** | - O compartilhamento depende dos aplicativos instalados no dispositivo<br>- O salvamento requer permissão de acesso ao armazenamento. |
| **Exceção** | - O usuário pode negar a permissão de armazenamento<br> - O sistema de compartilhamento pode falhar devido a problemas técnicos<br> - Erro de conexão à internet |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>


---

### Cenário 19: Seção de suporte ao usuário

 **Rastreabilidade do RF27**: [EN09](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/)

| Elemento    | Descrição                                                                                                                                   |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**   | Facilitar o uso do aplicativo eGDF por cidadãos que não estão familiarizados com tecnologia, por meio de uma seção de suporte acessível e clara. |
| **Contexto**   | Um morador do Distrito Federal, com baixa familiaridade com smartphones, acessa o aplicativo eGDF pela primeira vez em sua casa, no período da noite, buscando informações sobre agendamentos de serviços públicos. |
| **Recursos**   | Aplicativo eGDF instalado, smartphone com acesso à internet, seção de suporte com perguntas frequentes (FAQ), tutoriais passo a passo em texto e vídeo. |
| **Ator(res)**  | Cidadão do Distrito Federal.                                                                                                              |
| **Episódios**  | - O cidadão abre o aplicativo EGDF.<br>- Ele não entende como agendar atendimento para um serviço de saúde pública.<br>- No menu, localiza e acessa a seção “Ajuda” ou “Suporte ao Usuário”.<br>- Navega pelas instruções de uso até encontrar o tópico sobre agendamento de serviços.<br>- Segue o tutorial passo a passo com imagens e/ou vídeo.<br>- Retorna à área de serviços do app e realiza o agendamento corretamente. |
| **Restrições** | - A seção de suporte exige conexão com a internet para carregar vídeos e imagens.<br>- O conteúdo está apenas em português, limitando o acesso de estrangeiros ou pessoas com baixa alfabetização. |
| **Exceção**    |- O usuário não encontrar a resposta na seção de suporte<br>- Ocorrer um erro de conexão à internet |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo(a) autor(a) ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

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
| 1.2    |  Adição dos 3 primeiros cenários baseados nos requisitos funcionais não implementados.| [Ana Victória](https://github.com/navicg)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.3    | Cenários 4, 5 e 6 incorporados ao documento. | [Artur Mendonça Arruda](https://github.com/ArtyMend07) |16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.4    | Elaboração do sétimo, oitavo e nono cenário. | [Gabriel Lopes](https://github.com/BrzGab)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.5    | Adição do cenário 10, 11 e 12 no artefato. | [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.6    | Adição do cenário 13 e 14 no artefato. | [Lucas Mendonça](https://github.com/lucasarruda9)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.7    | Implementando os cenários 15 e 16 no artefato. | [Karoline Luz da Conceição](https://github.com/KarolineLuz)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.8    | Adicionando os cenários 18, 19 e 20| [Luiza da Silva Pugas](https://github.com/Luizaxx)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.9    | Adicionando tabela que identifica o cenário que cada um participou e rastreabilidade dos requisitos elicitados. | [Ana Victória](https://github.com/navicg)|18/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |