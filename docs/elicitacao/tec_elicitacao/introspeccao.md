# Introspecção

## Introdução

A elicitação de requisitos é uma das etapas mais importantes do desenvolvimento de sistemas, pois define o que o software deve fazer para atender às necessidades dos usuários e aos objetivos do projeto. Dentre as diversas técnicas existentes, a introspecção é caracterizada por ser baseada na experiência e julgamento do próprio analista, que se coloca no lugar de um usuário final e imagina como seria a utilização real do sistema, sem necessariamente consultar outras partes interessadas.

Neste documento, foi aplicada a técnica de introspecção para identificar requisitos do aplicativo [eGDF](https://play.google.com/store/apps/details?id=br.gov.df.eGDF&hl=pt_BR), uma plataforma digital desenvolvida pelo Governo do Distrito Federal para centralizar e facilitar o acesso a serviços públicos. A análise foi realizada de forma individual, explorando cenários comuns de uso e levantando tanto os requisitos essenciais quanto funcionalidades que poderiam tornar o sistema mais completo, eficiente e inclusivo.

## Metodologia

O processo foi conduzido pelo estudante [Gabriel Lopes](https://github.com/BrzGab), que executou uma análise com o ponto de vista de um cidadão utilizando o aplicativo em situações cotidianas. O exercício envolveu imaginar as dificuldades enfrentadas por usuários em diferentes contextos — como idosos, pessoas com deficiência, estudantes e trabalhadores — com o objetivo de identificar tanto funcionalidades fundamentais quanto pontos de melhoria.

Após essa etapa, os requisitos foram documentados, classificados e revisados. A análise foi dividida em requisitos funcionais, não funcionais e desejáveis não implementados.

### Cronograma da Atividade

| Participante                               | Data       | Horário |
|-------------------------------------------|------------|---------|
| [Gabriel Lopes](https://github.com/BrzGab) | 24/04/2025 | 21:00   |

---

## Tabela 1: Requisitos Funcionais

Estes requisitos descrevem as funcionalidades que o sistema deve obrigatoriamente oferecer para cumprir seus objetivos principais.


| Tipo | ID    | Descrição                                                                                                 | Implementado |
|------|-------|-----------------------------------------------------------------------------------------------------------|--------------|
| RF   | INT01 | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação. | Sim          |
| RF   | INT02 | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes. | Sim          |
| RF   | INT03 | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo).               | Sim          |
| RF   | INT04 | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência.                       | Sim          |
| RF   | INT05 | Oferecer acesso rápido a contatos de emergência, como Corpo de Bombeiros, Polícia Militar e Samu.         | Sim          |
| RF   | INT06 | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue.              | Sim          |
| RF   | INT07 | Permitir o acesso a informações sobre a rede pública de ensino, como calendário escolar e vagas disponíveis. | Sim        |
| RF   | INT08 | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade.            | Sim          |
| RF   | INT09 | Permitir agendamentos em serviços sociais, como centros de assistência social e habitação.                | Sim          |
| RF   | INT10 | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais.                              | Sim          |
| RF   | INT11 | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos.   | Sim          |
| RF   | INT12 | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal.          | Sim          |
| RF   | INT13 | Integrar um assistente virtual ou chatbot com respostas automáticas para dúvidas frequentes.              | Sim          |
| RF   | INT14 | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas.                   | Sim          |

Fonte: Elaborado pelo autor ( [Gabriel Lopes](https://github.com/BrzGab), 2025).

---

## Tabela 2: Requisitos Não Funcionais

Estes requisitos abordam qualidade, desempenho, acessibilidade, usabilidade e segurança do aplicativo.


| Tipo | ID     | Descrição                                                                                                       | Implementado |
|------|--------|-----------------------------------------------------------------------------------------------------------------|--------------|
| RNF  | INT15  | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.                       | Sim          |
| RNF  | INT16  | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.       | Sim          |
| RNF  | INT17  | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade. | Sim     |
| RNF  | INT18  | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura.                | Sim          |
| RNF  | INT19  | O app deve ser acessível a pessoas com deficiência, incluindo leitores de tela e contraste adequado.            | Não          |
| RNF  | INT20  | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.                 | Não          |
| RNF  | INT21  | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis.            | Sim          |
| RNF  | INT22  | O conteúdo do aplicativo deve ser responsivo, adaptando-se a diferentes tamanhos de tela, inclusive tablets.    | Sim          |

Fonte: Elaborado pelo autor ( [Gabriel Lopes](https://github.com/BrzGab), 2025).

---

## Tabela 3: Requisitos Desejáveis Não Implementados

Estes requisitos não são obrigatórios, mas sua implementação traria ganhos significativos em termos de experiência do usuário, acessibilidade, personalização e engajamento.


| Tipo | ID     | Descrição                                                                                             | Implementado |
|------|--------|-------------------------------------------------------------------------------------------------------|--------------|
| RF   | INT23  | Enviar notificações automáticas sobre mudanças no status de ocorrências registradas pelo usuário.     | Não          |
| RF   | INT24  | Possibilitar favoritar serviços frequentemente usados, criando um atalho personalizado.               | Não          |
| RF   | INT25  | Permitir avaliação dos serviços públicos utilizados, com notas e comentários para feedback governamental. | Não        |
| RF   | INT26  | Integrar opções de pagamento via carteiras digitais para tributos e taxas públicas.                   | Não          |
| RF   | INT27  | Disponibilizar um modo de acessibilidade com ícones maiores, narração de comandos e navegação simplificada. | Não      |
| RF   | INT28  | Implementar um chatbot baseado em IA com capacidade de aprendizado e respostas mais contextualizadas para dúvidas complexas dos cidadãos. | Não |
| RF   | INT29  | Fornecer feed de notícias com maior detalhamento e possibilidade de personalização por categorias de interesse do usuário. | Não |
| RF   | INT30  | Implementar sincronização offline completa que permita acesso a todos os documentos e histórico do usuário sem conexão à internet. | Não |
| RF   | INT31  | Possibilitar a criação de lembretes personalizados para prazos de serviços e documentos importantes. | Não |
| RF   | INT32  | Integrar um sistema de alerta para situações emergenciais no DF como enchentes, bloqueios de vias ou outros riscos. | Não |
| RF   | INT33  | Implementar suporte a leitores de tela para usuários com deficiência visual. | Não |
| RF   | INT34  | Fornecer legendas e transcrições para todos os conteúdos em áudio ou vídeo. | Não |
| RF   | INT35  | Disponibilizar opção de alto contraste e ajuste de tamanho de fonte para usuários com baixa visão. | Não |
| RF   | INT36  | Oferecer navegação por comando de voz para pessoas com limitações motoras. | Não |
| RNF  | INT37  | Adicionar suporte ao modo escuro para reduzir o cansaço visual em ambientes noturnos.                 | Não          |
| RNF  | INT38  | Disponibilizar o aplicativo em outros idiomas além do português, como espanhol e inglês.              | Não          |
| RNF  | INT39  | Implementar integração com assistentes de voz para acessibilidade e agilidade em comandos.            | Não          |
| RNF  | INT40  | Desenvolver mecanismo de compressão de dados que reduza o consumo de internet móvel em áreas com sinal limitado. | Não |

Fonte: Elaborado pelo autor ( [Gabriel Lopes](https://github.com/BrzGab), 2025).

---

## Considerações Finais

A introspecção proporcionou uma rica análise do aplicativo eGDF, permitindo a identificação não apenas de suas funcionalidades implementadas, mas também de diversas melhorias que poderiam ampliar sua eficácia, usabilidade e inclusão. 

Questões relacionadas à acessibilidade ainda precisam ser implementadas, pois o aplicativo atualmente não oferece recursos para pessoas com deficiência. O chatbot existente possui apenas funcionalidades básicas, sem capacidade de aprendizado ou contextualização para dúvidas mais complexas. O feed de notícias carece de detalhamento adequado e opções de personalização. Além disso, não há funcionalidade offline robusta, impedindo o acesso a documentos e histórico quando o usuário está sem conexão à internet.

A incorporação dos requisitos desejáveis descritos poderia contribuir significativamente para um serviço público digital mais eficiente, inclusivo e orientado ao usuário.

---

## Bibliografia

- SERRANO, Maurício; SERRANO, Milene. *Requisitos de Software*. [PDF](https://drive.google.com/file/d/1l9abHlbQtic5yluGeTDBHTRaqH1Eft0T/view?usp=sharing), 2025.  
- GOV.BR. Aplicativo eGDF – [https://www.df.gov.br](https://www.df.gov.br) (consultado em abril de 2025).  

---

## Histórico de Versões

| Versão | Data       | Descrição                                       | Autor(es)                                    | Revisor(es)                                       |
|--------|------------|--------------------------------------------------|----------------------------------------------|--------------------------------------------------|
| 1.0    | 25/04/2025 | Documento criado com análise por introspecção. | [Gabriel Lopes](https://github.com/BrzGab) | [Artur Mendonça](https://github.com/ArtyMend07) |