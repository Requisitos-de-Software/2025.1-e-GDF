# Especificação Suplementar

## Introdução

<q>Especificação Suplementar pode ser definida como um documento em linguagem natural no qual são descritos os requisitos num sistema<a id="anchor_1" href="#FRM1"> [1]</a> .</q> Ela é complementar aos [casos de uso](../modelagem/casos_de_uso.md), pois ela captura os requisitos do sistema que não foram elicitados no método anterior. Entre os requisitos capturados estão incluídos: Requisitos legais e de regulamentação, padrões de aplicativos, atributos de qualidade, requisitos de utilidade, confiabilidade, desempenho, suportabilidade e outros requisitos como sistemas e ambientes operacionais, requisitos de compatibilidade e restrições de design. A metodologia mais utilizada para a produção de uma especificação suplementar é a FURPS+.

- funcionalidade
- usabilidade
- confiabilidade
- desempenho
- suportabilidade

## Metodologia

Consoante ao tópico anterior, o modelo utilizado para este artefato é o FURPS+, metodologia a qual define reqisitos de um sistema dnetro de um dos cinco pilares citados anteriormente.

- F - Functionality: são os aspectos funcionais do sistema, os quais estão explicitados nos [casos de uso](../modelagem/casos_de_uso.md).
- U - Usability: o quão fácil é para o usuário realizar suas demandas via o software.
- R - Reliability: o quão confiável foi desenhado o software.
- P - Performance: como é o desempenho do software.
- S - Supportability: requisitos que agrupam caracteristicas como: manutenibilidade, adaptabilidade, internacionalização, portabilidade e outros aspectos relevantes.
- +: símbolo que emgloba outros requisitos não funcionais, os quais não se encaixam nos pilares listados, como: design, implementação, interface, físico.

### Funcionalidade

Os requisitos funcionais foram elicitados na seção de elicitação e a [tabela 1](../elicitacao/req_elicitados.md) da página de [requisitos elicitados](../elicitacao/req_elicitados.md) demonstra todos os requisitos priorizados.

### Usabilidade

Esse tópico diz respeito aos requisitos relacionados a facilidade do usuário de utilizar a aplicação.

Para essa categoria os requisitos identificados estão representados na tabela 1 a seguir.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

| Requisito | Descrição Ampliada e Específica |
|-----------|---------------------------------|
| U01 | O sistema deve apresentar uma interface intuitiva, que permita ao usuário executar tarefas básicas e avançadas com poucos cliques, preferencialmente em até 3 cliques para realizar ações principais, reduzindo a curva de aprendizado e minimizando dúvidas sem a necessidade de treinamento formal. |
| U02 | A interface deve ser limpa, com elementos visuais organizados de forma clara e objetiva, utilizando ícones ilustrativos facilmente reconhecíveis para cada função, garantindo que o usuário identifique rapidamente os botões e opções sem sobrecarregar visualmente a tela. |
| U03 | O aplicativo deve incorporar funcionalidades específicas de acessibilidade, tais como ajuste de tamanho da fonte (mínimo 16pt), alto contraste entre texto e fundo, e suporte para leitores de tela, visando atender usuários idosos e com deficiência visual, garantindo uso confortável e eficiente. |
| U04 | O layout deve ser responsivo, adaptando automaticamente a diferentes dispositivos (smartphones, tablets, desktops) e resoluções de tela, mantendo a proporção dos elementos e a funcionalidade completa, assegurando tempo de carregamento máximo de 2 segundos em conexões móveis. |
| U05 | O sistema deve garantir compatibilidade total com leitores de tela como NVDA e JAWS, incluindo descrições alternativas para imagens, navegação via teclado e uso adequado de ARIA labels, para permitir que usuários com deficiência visual possam acessar todas as funcionalidades. |
| U06 | O aplicativo deve utilizar linguagem clara, objetiva e acessível, evitando termos técnicos desnecessários, de forma que usuários com escolaridade mínima de ensino fundamental possam compreender instruções, mensagens e funcionalidades sem dificuldades. |
| U07 | A navegação do aplicativo deve ser autoexplicativa, com fluxos simples onde o usuário não precise voltar mais de uma tela para corrigir uma ação, evitando redirecionamentos externos, de modo que o uso seja fluido e natural, com tempo máximo de resposta de 1 segundo por ação. |
| U08 | O design do aplicativo deve considerar as necessidades de usuários idosos, apresentando botões com tamanho mínimo de 44x44 pixels, espaços adequados entre elementos para evitar cliques acidentais, e instruções visuais claras, facilitando o uso sem dependência de auxílio externo. |
| U09 | O sistema deve disponibilizar recursos de acessibilidade para daltonismo, como paletas de cores alternativas (pelo menos 3 opções) e símbolos adicionais para diferenciação, além de suporte para outros tipos de deficiência visual, garantindo acesso inclusivo a todas as funções do aplicativo. |
| U10 | A interface deve apresentar um design profissional e coerente, utilizando cores, fontes e layouts padronizados que transmitam segurança e confiabilidade ao usuário, reforçando a percepção de que seus dados e interações estão protegidos. |
| U11 | A interface deve manter um design simples e objetivo, com textos curtos e diretos, utilizando linguagem que facilite a compreensão de usuários com variados níveis de escolaridade, com no máximo 150 caracteres por mensagem ou instrução para evitar confusão. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

---

**Vídeo 2** - Validação com usuário por: [Ana Victória](https://github.com/navicg).

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/5cCeb5eTN6M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/5cCeb5eTN6M"  target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem

Este documento confirma que o cidadão Emanuel Maurício Costa forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1xkcr0UaikGhD1WTW-okJllMGEb4XXXhL/view?usp=drive_link)

| Entrevistador(es)                         | Cidadão         | Data prevista | Data Realizada | Horário Previsto | Horário Realizado | Local      | Duração   |
| ----------------------------------------- | --------------- | ------------- | -------------- | ---------------- | ----------------- | ---------- | --------- |
| [Ana Victória](https://github.com/navicg) | **Emanuel M.C** | 22/06/2025    | 22/06/2025     | 10:43            | 10:54             | Presencial | 04:52 min |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg), 2025).</p></font>

---

### Confiabilidade

Diz respeito ao quão confiável é o sistema, ou seja, qual é a frequência de falhas, possibilidade de recuperação e prevenção e tempo entre as falhas.

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

| Requisito | Descrição Ampliada e Específica |
|-----------|---------------------------------|
| R01 | O sistema deve estar em conformidade rigorosa com a Lei Geral de Proteção de Dados (LGPD), garantindo que todos os dados pessoais coletados sejam tratados conforme as diretrizes legais, com consentimento explícito do usuário, armazenamento seguro e possibilidade de exclusão ou anonimização dos dados mediante solicitação. |
| R02 | O aplicativo deve assegurar que todas as informações exibidas estejam atualizadas em tempo real ou com sincronização automática a cada no máximo 5 minutos, refletindo fielmente a realidade, especialmente para dados críticos nas áreas de saúde e educação, evitando desinformação e promovendo confiança no uso. |
| R03 | O aplicativo deve apresentar alta estabilidade operacional, prevenindo travamentos ou falhas de carregamento mesmo em condições adversas, como conexões móveis instáveis; deve suportar até 10.000 usuários simultâneos sem degradação perceptível da performance e garantir recuperação automática de erros em até 3 segundos. |
| R04 | O aplicativo deve garantir a proteção dos dados pessoais dos usuários por meio de mecanismos robustos de segurança, como autenticação multifator, controle de acesso granular e monitoramento constante, reforçando a confiança do usuário quanto à privacidade e segurança das informações manuseadas. |
| R05 | O sistema deve utilizar criptografia avançada para proteção dos dados pessoais, incluindo criptografia em trânsito (TLS 1.3) e em repouso (AES-256), além de autenticação segura via tokens JWT ou equivalente, garantindo que apenas usuários autorizados tenham acesso às informações sensíveis. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/karol), 2025)</p></font>

**Vídeo 1** - Validação com usuário por [Karoline Luz da Conceição](https://github.com/KarolineLuz)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/k--cQShnJVY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/k--cQShnJVY" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem

Este documento confirma que a cidadã Júnia Luz de Sousa forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1tAtNRMAKPoStT9ZyOU-DdT1I9mJgC5qK/view?usp=sharing)

| Entrevistador(es)                              | Cidadão       | Data prevista | Data Realizada | Horário Previsto | Horário Realizado | Local      | Duração   |
| ---------------------------------------------- | ------------- | ------------- | -------------- | ---------------- | ----------------- | ---------- | --------- |
| [Karoline Luz](https://github.com/KarolineLuz) | **Júnia L.S** | 19/06/2025    | 19/06/2025     | 17:30            | 17:45             | Presencial | 02:05 min |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Karoline Luz](https://github.com/karol), 2025)</p></font>

### Desempenho

Diz respeito às condições que os requisitos devem operar. A velocidade, limites superiores e inferiores, tempo de resposta, restrições de interface e de funções, etc.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

| Requisito | Descrição Ampliada e Específica |
|-----------|---------------------------------|
| P01 | A navegação entre as telas do aplicativo deve ser rápida e fluida, com transições que não ultrapassem 300 milissegundos, evitando redirecionamentos excessivos que possam causar atraso perceptível ao usuário. O fluxo deve ser contínuo, sem bloqueios visuais ou pausas maiores que 0,5 segundo. |
| P02 | O sistema deve carregar e apresentar as informações solicitadas pelo usuário em até 1,5 segundos, utilizando técnicas de cache local e otimização de consultas para minimizar o tempo de resposta, garantindo uma experiência ágil mesmo em conexões de internet móveis instáveis. |
| P03 | O processo de login do aplicativo deve ser otimizado para permitir autenticação e acesso à conta do usuário em até 2 segundos, contemplando validação dos dados, comunicação segura com o servidor e feedback visual imediato para indicar progresso. |
| P04 | Todas as funcionalidades principais, como busca, cadastro e atualização de dados, devem responder às solicitações do usuário em no máximo 2 segundos, assegurando uma interação fluida e evitando sensação de lentidão ou travamentos. |
| P05 | As imagens capturadas e enviadas pelo usuário devem ser comprimidas e otimizadas automaticamente para garantir upload rápido, mesmo em redes móveis com largura de banda limitada, mantendo qualidade visual aceitável e reduzindo o tamanho do arquivo para menos de 500 KB quando possível. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

### Suportabilidade

Envolve os requisitos relacionados ao suporte e manutenção do sistema. Isso inclui requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado, documentação adequada, facilidade de teste e diagnóstico de problemas.

Para essa categoria os requisitos identificados estão representados na tabela 4 a seguir.

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

| Requisito | Descrição Ampliada e Específica |
|-----------|---------------------------------|
| S01 | O sistema deve ser totalmente compatível com os sistemas operacionais Android (a partir da versão 8.0) e iOS (a partir da versão 13), garantindo funcionamento adequado em smartphones e tablets, respeitando suas especificidades de interface e hardware. |
| S02 | O aplicativo deve ser capaz de operar em dispositivos com recursos limitados, como processadores de até 1.5 GHz, 2 GB de RAM e armazenamento interno restrito, mantendo desempenho estável e evitando travamentos ou consumo excessivo de bateria. |
| S03 | O sistema deve receber atualizações regulares para garantir compatibilidade com as versões mais recentes dos sistemas Android e iOS, incluindo adaptações para mudanças nas APIs, políticas de segurança e recursos nativos. |
| S04 | O aplicativo deve disponibilizar modo offline que permita ao usuário acessar e consultar registros e informações previamente sincronizadas, com interface e funcionalidades básicas operando sem conexão de internet, sincronizando os dados automaticamente quando a conexão for restabelecida. |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

### Requisitos de Licenciamento

O sistema deve restringir o uso através de termos de uso.

### Observações Legais, de Copyright e Outras

O sistema está sujeito à lei dos direitos autorais, portanto, para a utilização de outras marcas será necessário uma autorização prévia dos envolvidos. Deve-se atentar também para a legislação de proteção de dados (a LGPD) e as de serviços financeiros.

### Padrões Aplicáveis

O sistema deve seguir os padrões definidos pelas normas: WCAG, ISO 9241-11, ISO/TC-211, ISO 9000, ISO 9001-3, ISO 12207, ISO 12202 e pelos guias de estilo dos sistemas Android e iOS.

### Requisitos Físicos

O aplicativo é construído nas seguintes linguagens:  
Android: Kotlin, Java.  
iOS: Objective-C, Swift.

## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a>SALLES, André. Plano de ensino da disciplina. Disponível em: [slides](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em 15 de maio de 2025.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/especifica%C3%A7%C3%A3o-suplementar/docs/assets/modelagem/especifica%C3%A7%C3%B5es.png">
</div>

## Bibliografia

> HENRIQUE, Mathes. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <<https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>>. Acesso em: 15 maio 2025.

## Histórico de Versões

| Versão | Descrição                                        | Autor(es)                                                                                                 | Data       | Revisor(es)                                                                                       | Data de Revisão |
| ------ | ------------------------------------------------ | --------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------------------------------------------------- | --------------- |
| 1.0    | Adicionando a introdução e metodologia           | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Lucas Mendonça](https://github.com/lucasarruda9) | 15/05/2025 | [Karoline Luz](https://github.com/KarolineLuz)                                                    | 17/05/2025      |
| 1.1    | Adicionando o texto base do FURPS+               | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Lucas Mendonça](https://github.com/lucasarruda9) | 15/05/2025 | [Karoline Luz](https://github.com/KarolineLuz)                                                    | 17/05/2025      |
| 1.2    | Adição da tabela Desempenho                      | [João Marcos Moraes](https://github.com/JJOAOMARCOSS), [Lucas Mendonça](https://github.com/lucasarruda9)  | 15/05/2025 | [Karoline Luz](https://github.com/KarolineLuz), [Artur Mendonça](https://github.com/ArtyMend07)   | 17/05/2025      |
| 1.3    | Adição da tabela Confiabilidade                  | [Gabriel Lopes](https://github.com/BrzGab), [Karoline Luz](https://github.com/KarolineLuz)                | 16/05/2025 | [Ana Victória](https://github.com/navicg), [Luiza da Silva Pugas](https://github.com/Luizaxx)     | 17/05/2025      |
| 1.4    | Adição da tabela Usabilidade                     | [Ana Victória](https://github.com/navicg), [Artur Mendonça](https://github.com/ArtyMend07)                | 16/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS), [Gabriel Lopes](https://github.com/BrzGab) | 17/05/2025      |
| 1.5    | Adição da tabela Suportabilidade                 | [Luiza da Silva Pugas](https://github.com/Luizaxx)                                                        | 16/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9)                                                 | 17/05/2025      |
| 1.6    | Arrumando nome das tabelas                       | [Lucas Mendonça](https://github.com/lucasarruda9)                                                         | 21/06/2025 | [Gabriel Lopes](https://github.com/BrzGab)                                                        | 22/06/2025      |
| 2.0    | Adidionando entrevista e termo de conscentimento | [Karoline Luz](https://github.com/KarolineLuz)                                                            | 20/06/2025 | [Ana Victória](https://github.com/navicg)                                                         | 20/06/2025      |
| 2.1    | Adidionando validação da Usabilidade             | [Ana Victória](https://github.com/navicg)                                                                 | 22/06/2025 | [Karoline Luz](https://github.com/KarolineLuz)                                                    | 22/06/2025      |
| 2.1    | Deixado Tabelas mais Descritivas           |      [Karoline Luz](https://github.com/KarolineLuz) e  [Ana Victória](https://github.com/navicg)                                                                    | 05/07/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)         | 06/07/2025      |
