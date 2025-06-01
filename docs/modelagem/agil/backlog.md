# Backlog

## Introdução

Este documento apresenta o backlog do produto para o aplicativo e-GDF, uma plataforma digital do Governo do Distrito Federal que centraliza serviços públicos e facilita o acesso do cidadão a diversas funcionalidades governamentais. 

O Backlog do produto é uma lista contendo todas as funcionalidades desejadas para um produto. O conteúdo desta lista é definido pelo Product Owner. O Product Backlog não precisa estar completo no início de um projeto. Pode-se começar com tudo aquilo que é mais óbvio em um primeiro momento. Com o tempo, o Product Backlog cresce e muda à medida que se aprende mais sobre o produto e seus usuários[¹](#ref1){: #citacao1}.

Um backlog bem gerenciado traz diversos benefícios para o projeto, incluindo[²](#ref2){: #citacao2}:

- Priorização aprimorada das tarefas mais críticas
- Maior eficiência no desenvolvimento
- Melhor comunicação entre a equipe
- Redução do desperdício de recursos
- Maior satisfação do cliente através da priorização baseada em feedback

Para este projeto, o backlog foi estruturado seguindo as melhores práticas de desenvolvimento ágil, organizando os requisitos funcionais em uma hierarquia clara de épicos, features e histórias de usuário. O processo de elaboração incluiu a análise detalhada dos requisitos funcionais levantados nas etapas anteriores do projeto, a criação de histórias de usuário que representam as necessidades reais dos cidadãos do DF, e a validação com usuários reais para garantir que as funcionalidades propostas atendam efetivamente às expectativas e necessidades da população.

## Participantes

**Tabela 1** - Participantes da elaboração do backlog

| **Participante** | **Função** |
| :-------------- | :--------- |
| [Nome do PO] | Product Owner |
| [Ana Victória Guedes da Costa](https://github.com/navicg) | Desenvolvedor(a) |
| [Artur Mendonça Arruda](https://github.com/ArtyMend07) | Desenvolvedor |
| [Gabriel Lopes de Amorim](https://github.com/BrzGab) | Desenvolvedor |
| [João Marcos Moraes De Andrade](https://github.com/JJOAOMARCOSS) | Desenvolvedor |
| [Karoline Luz da Conceição](https://github.com/KarolineLuz) | Desenvolvedor(a) |
| [Lucas Mendonça Arruda](https://github.com/lucasarruda9) | Desenvolvedor |
| [Luiza da Silva Pugas](https://github.com/Luizaxx) | Desenvolvedor(a) |

*Fonte: Elaborado por ([Artur Mendonça Arruda](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab), 2025).*

## Metodologia

O desenvolvimento do backlog seguiu uma abordagem sistemática e colaborativa, onde cada integrante da equipe foi responsável por um conjunto específico de requisitos funcionais. A metodologia adotada compreendeu as seguintes etapas:

1. **Análise e Agrupamento**: Os requisitos funcionais foram analisados e agrupados em temas relacionados, considerando as principais áreas de serviço do aplicativo e-GDF.

2. **Criação de Épicos**: A partir dos temas identificados, foram elaborados épicos que representam grandes narrativas de funcionalidades, agrupando features relacionadas.

3. **Definição de Features**: Cada épico foi decomposto em features específicas que representam funcionalidades concretas do sistema.

4. **Elaboração de Histórias de Usuário**: As features foram detalhadas em histórias de usuário no formato padrão "Como... Eu quero... Para que...", garantindo clareza sobre o valor entregue ao usuário final.

5. **Priorização**: Os itens do backlog foram priorizados considerando[²](#ref2){: #citacao3}:
   - Prioridade do cliente e feedback dos usuários
   - Urgência no recebimento de feedback
   - Dificuldade de implementação relativa
   - Relações e dependências entre itens de trabalho

6. **Validação com Usuários**: Cada integrante realizou validação presencial com usuários reais, apresentando os backlogs elaborados e coletando feedback para garantir alinhamento com as necessidades dos cidadãos.

## Temas {: #temas}

Analisando as histórias de usuário, foi possível organizá-las inicialmente em 9 grandes temas:

### Tema 1: Autenticação {: #tema-1-autenticação}
Sistema de autenticação seguro e integrado, permitindo que os usuários acessem seus dados pessoais e utilizem os serviços governamentais de forma protegida e confiável.

### Tema 2: Usabilidade {: #tema-2-usabilidade}
Interface intuitiva e personalizável para usuários com diferentes níveis de familiaridade com tecnologia, garantindo navegação eficiente e confortável.

### Tema 3: Serviços do Cidadão {: #tema-3-serviços-do-cidadão}
Acesso centralizado aos principais serviços públicos, permitindo resolver demandas de forma prática e digital sem deslocamento físico.

### Tema 4: Comunicação {: #tema-4-comunicação}
Sistema de notificações e comunicações personalizadas e relevantes, mantendo o cidadão informado sobre assuntos importantes de forma oportuna.

### Tema 5: Documentos {: #tema-5-documentos}
Gestão de documentos e comprovantes digitais, permitindo gerar, visualizar e compartilhar documentos com acesso rápido ao histórico de interações.

### Tema 6: Atendimento {: #tema-6-atendimento}
Canais de suporte e sistemas de registro de ocorrências, permitindo resolver dúvidas e contribuir para a melhoria dos serviços públicos.

### Tema 7: Mobilidade {: #tema-7-mobilidade}
Informações e serviços relacionados ao transporte público do DF, facilitando o planejamento de deslocamentos e gestão de serviços de mobilidade.

### Tema 8: Privacidade {: #tema-8-privacidade}
Controle sobre informações pessoais e garantias de conformidade legal, assegurando o uso do aplicativo com confiança e segurança.

### Tema 9: Acessibilidade {: #tema-9-acessibilidade}
Recursos de apoio visual e auditivo para usuários com necessidades especiais, garantindo navegação sem barreiras.

## Épicos {: #epicos}

Após a definição dos temas, eles são "quebrados" em épicos de modo a diminuir ainda mais a abstração das atividades que deverão ser realizadas no projeto.

### Épico 1: Autenticação Segura (EP01) {: #épico-1-autenticação-segura}
Como usuário do aplicativo e-GDF, eu quero ter acesso a um sistema de autenticação seguro e integrado, para que eu possa acessar meus dados pessoais e utilizar os serviços governamentais de forma protegida e confiável.

### Épico 2: Interface Personalizável (EP02) {: #épico-2-interface-personalizável}
Como usuário com diferentes níveis de familiaridade com tecnologia, eu quero ter acesso a uma interface intuitiva e personalizável, para que eu possa utilizar o aplicativo de forma eficiente e confortável, independentemente das minhas limitações ou preferências.

### Épico 3: Recursos de Acessibilidade (EP03) {: #épico-3-recursos-acessibilidade}
Como usuário com necessidades especiais de acessibilidade, eu quero ter recursos de apoio visual e auditivo, para que eu possa navegar e utilizar todas as funcionalidades do aplicativo sem barreiras.

### Épico 4: Serviços Centralizados (EP04) {: #épico-4-serviços-centralizados}
Como cidadão do Distrito Federal, eu quero ter acesso centralizado aos principais serviços públicos, para que eu possa resolver minhas demandas de forma prática e digital sem precisar me deslocar fisicamente.

### Épico 5: Informações Públicas (EP05) {: #épico-5-informações-públicas}
Como usuário interessado em informações públicas, eu quero ter acesso a notícias e informações oficiais do governo, para que eu possa me manter informado sobre políticas e serviços que me afetam.

### Épico 6: Agendamentos (EP06) {: #épico-6-agendamentos}
Como cidadão que utiliza serviços públicos, eu quero poder agendar e acompanhar meus atendimentos, para que eu possa organizar minha agenda e ter controle sobre os serviços solicitados.

### Épico 7: Comunicações Personalizadas (EP07) {: #épico-7-comunicações-personalizadas}
Como usuário do aplicativo, eu quero receber comunicações personalizadas e relevantes, para que eu possa ser notificado sobre assuntos que são importantes para mim de forma oportuna e organizada.

### Épico 8: Gestão de Documentos (EP08) {: #épico-8-gestão-documentos}
Como cidadão que precisa de documentos e comprovantes, eu quero poder gerar, visualizar e compartilhar meus documentos digitais, para que eu possa ter acesso rápido aos meus comprovantes e histórico de interações com o governo.

### Épico 9: Canais de Suporte (EP09) {: #épico-9-canais-suporte}
Como usuário que precisa de ajuda ou tem problemas para relatar, eu quero ter acesso a canais de suporte e sistemas de registro de ocorrências, para que eu possa resolver dúvidas e contribuir para a melhoria dos serviços públicos.

### Épico 10: Transporte Público (EP10) {: #épico-10-transporte-público}
Como usuário do transporte público do DF, eu quero ter acesso a informações e serviços relacionados ao transporte, para que eu possa planejar meus deslocamentos e gerenciar meus serviços de mobilidade urbana.

### Épico 11: Controle de Privacidade (EP11) {: #épico-11-controle-privacidade}
Como usuário preocupado com a privacidade dos meus dados, eu quero ter controle sobre minhas informações pessoais e garantias de conformidade legal, para que eu possa utilizar o aplicativo com confiança e segurança.

## Estrutura da tabela do Backlog

**Tabela 2** - Estrutura do backlog

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade**  | **Rastreabilidade** |
|:--|:--|:--|:--|:--|:--|
|Nome do [Tema](#temas) definido|Nome do [Épico](#epicos) (Identificador do [Épico](#epicos)) |Título da [História de Usuário](./historia-de-usuario.md) (Identificador da [História de Usuário](./historia-de-usuario.md))|Identificador do Requisito referente a [História de usuário](./historia-de-usuario.md)|Prioridade baseada na técnica do [MoSCoW](../../elicitacao/tec_priorizacao/moscow.md) | Rastreabilidade do requisito utilizado    |

*Fonte: Elaborado por ([Artur Mendonça Arruda](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab), 2025).*

## Backlog

**Tabela 3** - Backlog completo do produto e-GDF

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Rastreabilidade** |
|:--:|:--:|:--:|:--:|:--:|:--:|
| [Autenticação](#tema-1-autenticação) | [Autenticação Segura](#épico-1-autenticação-segura) (EP01) | Realizar login com acesso unificado do GOV.br ([US01](./historia-de-usuario.md)) | RF22 | MH | [EN04](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Compartilhamento e salvamento de informações importantes ([US02](./historia-de-usuario.md)) | RF18 | CH | [BR20](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Acesso a suporte com instruções de uso ([US03](./historia-de-usuario.md)) | RF27 | CH | [EN11](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Acompanhamento de status de solicitações ([US04](./historia-de-usuario.md)) | RF30 | SH | [AD04](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Confirmação da resolução de problemas ([US05](./historia-de-usuario.md)) | RF31 | SH | [AD06](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Privacidade](#tema-8-privacidade) | [Controle de Privacidade](#épico-11-controle-privacidade) (EP11) | Exclusão de conta e dados pessoais ([US06](./historia-de-usuario.md)) | RF32 | SH | [AD07](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Privacidade](#tema-8-privacidade) | [Controle de Privacidade](#épico-11-controle-privacidade) (EP11) | Conformidade com LGPD ([US07](./historia-de-usuario.md)) | RNF02 | SH | [AD10](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Alteração de idioma no aplicativo ([US08](./historia-de-usuario.md)) | RF12 | CH | [BR13](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Personalização de preferências e perfil ([US09](./historia-de-usuario.md)) | RF13 | CH | [BR14](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Comunicação](#tema-4-comunicação) | [Comunicações Personalizadas](#épico-7-comunicações-personalizadas) (EP07) | Envio de mensagens curtas para lembretes ([US10](./historia-de-usuario.md)) | RF14 | SH | [BR15](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Seleção do tipo de serviço (implantação, limpeza ou reparo) ([US11](./historia-de-usuario.md)) | RF35 | SH | [INT03](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Registro detalhado da ocorrência ([US12](./historia-de-usuario.md)) | RF36 | SH | [INT04](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Mobilidade](#tema-7-mobilidade) | [Transporte Público](#épico-10-transporte-público) (EP10) | Acesso a serviços de transporte e pré-cadastro do cartão mobilidade ([US13](./historia-de-usuario.md)) | RF38 | SH | [INT08](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Compatibilidade com Android e iOS ([US14](./historia-de-usuario.md)) | RNF01 | SH | [AD09](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Acessibilidade](#tema-9-acessibilidade) | [Recursos de Acessibilidade](#épico-3-recursos-acessibilidade) (EP03) | Ajuste de tamanho de fonte e contraste de cores ([US15](./historia-de-usuario.md)) | RF07 | SH | [BR07](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Ativação do modo escuro ([US16](./historia-de-usuario.md)) | RF08 | CH | [BR08](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Geração de relatórios e visualização de comprovantes ([US17](./historia-de-usuario.md)) | RF10 | SH | [BR11](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Mobilidade](#tema-7-mobilidade) | [Transporte Público](#épico-10-transporte-público) (EP10) | Localização de ônibus em tempo real ([US18](./historia-de-usuario.md)) | RF19 | SH | [EN01](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Acesso facilitado a serviços de impostos ([US19](./historia-de-usuario.md)) | RF23 | SH | [EN05](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Categorização de ocorrências ([US20](./historia-de-usuario.md)) | RF34 | SH | [INT02](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Privacidade](#tema-8-privacidade) | [Controle de Privacidade](#épico-11-controle-privacidade) (EP11) | Proteção de informações pessoais com criptografia ([US21](./historia-de-usuario.md)) | RNF22 | SH | [INT18](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INTT) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Acessar informações de agendamento e reagendamento ([US22](./historia-de-usuario.md)) | RF16 | MH | [BR17](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Reportar problemas da cidade via mapa interativo ([US23](./historia-de-usuario.md)) | RF25 | MH | [EN09](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Acessar números de serviços de emergência ([US24](./historia-de-usuario.md)) | RF26 | SH | [EN10](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT05](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Solicitar serviços como coleta de lixo e reparos ([US25](./historia-de-usuario.md)) | RF28 | MH | [AD02](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Localizar solicitações no mapa ([US26](./historia-de-usuario.md)) | RF29 | CH | [AD03](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Emitir tributos, certidões e documentos fiscais ([US27](./historia-de-usuario.md)) | RF43 | SH | [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [BR18](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Acessibilidade](#tema-9-acessibilidade) | [Recursos de Acessibilidade](#épico-3-recursos-acessibilidade) (EP03) | Interface acessível para idosos ([US28](./historia-de-usuario.md)) | RNF16 | SH | [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Autenticação](#tema-1-autenticação) | [Autenticação Segura](#épico-1-autenticação-segura) (EP01) | Realizar login com acesso unificado do GOV.br ([US29](./historia-de-usuario.md)) | RF01 | MH | [BR01](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Interface acessível para usuários com pouca familiaridade tecnológica ([US30](./historia-de-usuario.md)) | RF02 | SH | [BR02](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Comunicação](#tema-4-comunicação) | [Comunicações Personalizadas](#épico-7-comunicações-personalizadas) (EP07) | Receber notificações personalizadas baseadas em localização ([US31](./historia-de-usuario.md)) | RF03 | CH | [BR03](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Informações Públicas](#épico-5-informações-públicas) (EP05) | Acessar e visualizar notícias relevantes ([US32](./historia-de-usuario.md)) | RF09 | CH | [BR10](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Menu com principais funções na tela inicial ([US33](./historia-de-usuario.md)) | RF15 | CH | [BR16](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Links para serviços externos com explicações claras ([US34](./historia-de-usuario.md)) | RF20 | CH | [EN02](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Autenticação](#tema-1-autenticação) | [Autenticação Segura](#épico-1-autenticação-segura) (EP01) | Estabilidade e desempenho em redes móveis ([US35](./historia-de-usuario.md)) | RNF13 | SH | [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Consulta centralizada de agendamentos e serviços ([US36](./historia-de-usuario.md)) | RF04 | SH | [BR04](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Acessibilidade](#tema-9-acessibilidade) | [Recursos de Acessibilidade](#épico-3-recursos-acessibilidade) (EP03) | Assistente virtual com acessibilidade por voz ([US37](./historia-de-usuario.md)) | RF05 | SH | [BR05](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Tutoriais passo a passo do aplicativo ([US38](./historia-de-usuario.md)) | RF06 | CH | [BR06](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Integração com serviços de saúde, educação e mobilidade ([US39](./historia-de-usuario.md)) | RF11 | SH | [BR12](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Consulta de informações educacionais ([US40](./historia-de-usuario.md)) | RF21 | SH | [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT07](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Registro de ocorrências de infraestrutura ([US41](./historia-de-usuario.md)) | RF33 | SH | [INT01](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Performance das funcionalidades principais ([US42](./historia-de-usuario.md)) | RNF20 | SH | [INT16](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INTT) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Emitir tributos, certidões e documentos fiscais ([US43](./historia-de-usuario.md)) | RF39 | SH | [INT09](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Comunicação](#tema-4-comunicação) | [Informações Públicas](#épico-5-informações-públicas) (EP05) | Feed com notícias oficiais do GDF ([US44](./historia-de-usuario.md)) | RF42 | CH | [INT12](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Agendar atendimentos de serviços sociais ([US45](./historia-de-usuario.md)) | RF37 | SH | [INT06](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Acompanhar pendências escolares ([US46](./historia-de-usuario.md)) | RF24 | SH | [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Visualizar histórico de interações e solicitações ([US47](./historia-de-usuario.md)) | RF41 | SH | [INT11](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| [Comunicação](#tema-4-comunicação) | [Comunicações Personalizadas](#épico-7-comunicações-personalizadas) (EP07) | Receber notificações por categorias ([US48](./historia-de-usuario.md)) | RF17 | CH | [BR19](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Consultar informações offline ([US49](./historia-de-usuario.md)) | RNF23 | SH | [INT20](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INTT) |

<font size="3"><p style="text-align: center"> Fonte: Elaborado por ([Artur Mendonça Arruda](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


## Validação


**Tabela 4** - Estrutura da tabela de validação

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--|:--|:--|:--|:--|:--|:--|:--|
|Nome do [Tema](#temas) definido|Nome do [Épico](#epicos) (Identificador do [Épico](#epicos)) |Título da [História de Usuário](./historia-de-usuario.md) (Identificador da [História de Usuário](./historia-de-usuario.md))|Identificador do Requisito referente a [História de usuário](./historia-de-usuario.md)|Prioridade baseada na técnica do [MoSCoW](../../elicitacao/tec_priorizacao/moscow.md)| Status de conclusão da validação | Rastreabilidade do requisito utilizado  | [Autor](#autores)      |

<font size="3"><p style="text-align: center"> Fonte: Elaborado por ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>


### Validação 1 - Ana Victória

**Vídeo 1** - Validação com usuário por Ana Victória

<iframe width="560" height="315" src="https://www.youtube.com/embed/yfFuc19aF20" title="Validação Backlog - Ana Victória" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


**Tabela 4** - Informações da validação 1


| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Autenticação](#tema-1-autenticação) | [Autenticação Segura](#épico-1-autenticação-segura) (EP01) | Realizar login com acesso unificado do GOV.br ([US29](./historia-de-usuario.md)) | RF01 | MH | Validado | [BR01](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Ana Victória](https://github.com/navicg) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Interface acessível para usuários com pouca familiaridade tecnológica ([US30](./historia-de-usuario.md)) | RF02 | MH | Validado | [BR02](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Ana Victória](https://github.com/navicg) |
| [Comunicação](#tema-4-comunicação) | [Comunicações Personalizadas](#épico-7-comunicações-personalizadas) (EP07) | Receber notificações personalizadas baseadas em localização ([US31](./historia-de-usuario.md)) | RF03 | SH | Validado | [BR03](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Ana Victória](https://github.com/navicg) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Informações Públicas](#épico-5-informações-públicas) (EP05) | Acessar e visualizar notícias relevantes ([US32](./historia-de-usuario.md)) | RF09 | CH | Validado | [BR10](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Ana Victória](https://github.com/navicg) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Menu com principais funções na tela inicial ([US33](./historia-de-usuario.md)) | RF15 | MH | Validado | [BR16](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Ana Victória](https://github.com/navicg) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Links para serviços externos com explicações claras ([US34](./historia-de-usuario.md)) | RF20 | MH | Validado | [EN02](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Ana Victória](https://github.com/navicg) |
| [Autenticação](#tema-1-autenticação) | [Autenticação Segura](#épico-1-autenticação-segura) (EP01) | Estabilidade e desempenho em redes móveis ([US35](./historia-de-usuario.md)) | RNF13 | SH | Validado | [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Ana Victória](https://github.com/navicg) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [Ana Victória](https://github.com/navicg) | Ana Geralda Xavier |

<font size="3"><p style="text-align: center"> Fonte: Elaborado por ([Ana Victória](https://github.com/navicg), 2025).</p></font>

## Termo de consentimento de imagem 
Este documento confirma que a cidadã Ana Geralda Xavier forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1xYrhXi9XEChbp37phZao5D57Tu_ZPrM6/view?usp=sharing)

<p style="text-align: center"><font size="3">Fonte: Elaborado por (<a href="https://github.com/navicg">Ana Victória</a>, 2025).</font></p>

### Validação 2 - Artur Mendonça


**Vídeo 2** - Validação com usuário por Artur Mendonça

<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ARTUR_MENDONCA" title="Validação Backlog - Artur Mendonça" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Tabela 5** - Informações da validação 2

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Consulta centralizada de agendamentos e serviços ([US36](./historia-de-usuario.md)) | RF04 | MH | em progresso | [BR04](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Artur Mendonça](https://github.com/ArtyMend07) |
| [Acessibilidade](#tema-9-acessibilidade) | [Recursos de Acessibilidade](#épico-3-recursos-acessibilidade) (EP03) | Assistente virtual com acessibilidade por voz ([US37](./historia-de-usuario.md)) | RF05 | MH | em progresso | [BR05](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Artur Mendonça](https://github.com/ArtyMend07) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Tutoriais passo a passo do aplicativo ([US38](./historia-de-usuario.md)) | RF06 | SH | em progresso | [BR06](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Artur Mendonça](https://github.com/ArtyMend07) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Integração com serviços de saúde, educação e mobilidade ([US39](./historia-de-usuario.md)) | RF11 | MH | em progresso | [BR12](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Artur Mendonça](https://github.com/ArtyMend07) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Consulta de informações educacionais ([US40](./historia-de-usuario.md)) | RF21 | MH | em progresso | [EN03](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT07](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Artur Mendonça](https://github.com/ArtyMend07) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Registro de ocorrências de infraestrutura ([US41](./historia-de-usuario.md)) | RF33 | MH | em progresso | [INT01](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Artur Mendonça](https://github.com/ArtyMend07) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Performance das funcionalidades principais ([US42](./historia-de-usuario.md)) | RNF20 | MH | em progresso | [INT16](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INTT) | [Artur Mendonça](https://github.com/ArtyMend07) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [Artur Mendonça](https://github.com/ArtyMend07) |  |

<font size="3"><p style="text-align: center"> Fonte: Elaborado por ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>


### Validação 3 - Gabriel Lopes


**Vídeo 3** - Validação com usuário por Gabriel Lopes

<iframe width="560" height="315" src="https://www.youtube.com/embed/GdncDHMK1DQ" title="Validação Backlog - Gabriel Lopes" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Tabela 6** - Informações da validação 3

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Acessibilidade](#tema-9-acessibilidade) | [Recursos de Acessibilidade](#épico-3-recursos-acessibilidade) (EP03) | Ajuste de tamanho de fonte e contraste de cores ([US15](./historia-de-usuario.md)) | RF07 | SH | Validado | [BR07](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Gabriel Lopes](https://github.com/BrzGab) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Ativação do modo escuro ([US16](./historia-de-usuario.md)) | RF08 | CH | Validado | [BR08](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Gabriel Lopes](https://github.com/BrzGab) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Geração de relatórios e visualização de comprovantes ([US17](./historia-de-usuario.md)) | RF10 | SH | Validado | [BR11](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Gabriel Lopes](https://github.com/BrzGab) |
| [Mobilidade](#tema-7-mobilidade) | [Transporte Público](#épico-10-transporte-público) (EP10) | Localização de ônibus em tempo real ([US18](./historia-de-usuario.md)) | RF19 | SH | Validado | [EN01](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Gabriel Lopes](https://github.com/BrzGab) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Acesso facilitado a serviços de impostos ([US19](./historia-de-usuario.md)) | RF23 | SH | Validado | [EN05](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Gabriel Lopes](https://github.com/BrzGab) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Categorização de ocorrências ([US20](./historia-de-usuario.md)) | RF34 | SH | Validado | [INT02](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Gabriel Lopes](https://github.com/BrzGab) |
| [Privacidade](#tema-8-privacidade) | [Controle de Privacidade](#épico-11-controle-privacidade) (EP11) | Proteção de informações pessoais com criptografia ([US21](./historia-de-usuario.md)) | RNF22 | MH | Validado | [INT18](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INTT) | [Gabriel Lopes](https://github.com/BrzGab) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [Gabriel Lopes](https://github.com/BrzGab) | Daniel Rodrigues Nascimento |

<font size="3"><p style="text-align: center"> Fonte: Elaborado por ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão **Daniel Rodrigues Nascimento** forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1EB1p_smwvLfqsPcUb_7nWpKIXuzLOx02/view?usp=sharing)



### Validação 4 - João Marcos Moraes


**Vídeo 4** - Validação com usuário por [João Marcos Moraes](https://github.com/JJOAOMARCOSS)

<iframe width="560" height="315" src="https://www.youtube.com/embed/jNa4ZpVfA0M" title="Validação Backlog - João Marcos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<p style="text-align: center"><a href="https://youtu.be/jNa4ZpVfA0M" target="_blank">Clique aqui para assistir no YouTube</a></p>

**Tabela 7** - Informações da validação 4

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Alteração de idioma no aplicativo ([US08](./historia-de-usuario.md)) | RF12 | MH | em progresso | [BR13](../../elicitacao/tec_elicitacao/brainstorming.md#anMHor_BS) | [João Marcos](https://github.com/JJOAOMARCOSS) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Personalização de preferências e perfil ([US09](./historia-de-usuario.md)) | RF13 | MH | em progresso | [BR14](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [João Marcos](https://github.com/JJOAOMARCOSS) |
| [Comunicação](#tema-4-comunicação) | [Comunicações Personalizadas](#épico-7-comunicações-personalizadas) (EP07) | Envio de mensagens curtas para lembretes ([US10](./historia-de-usuario.md)) | RF14 | MH | em progresso | [BR15](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [João Marcos](https://github.com/JJOAOMARCOSS) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Seleção do tipo de serviço (implantação, limpeza ou reparo) ([US11](./historia-de-usuario.md)) | RF35 | MH | em progresso | [INT03](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [João Marcos](https://github.com/JJOAOMARCOSS) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Registro detalhado da ocorrência ([US12](./historia-de-usuario.md)) | RF36 | MH | em progresso | [INT04](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [João Marcos](https://github.com/JJOAOMARCOSS) |
| [Mobilidade](#tema-7-mobilidade) | [Transporte Público](#épico-10-transporte-público) (EP10) | Acesso a serviços de transporte e pré-cadastro do cartão mobilidade ([US13](./historia-de-usuario.md)) | RF38 | MH | em progresso | [INT08](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [João Marcos](https://github.com/JJOAOMARCOSS) |
| [Usabilidade](#tema-2-usabilidade) | [Interface Personalizável](#épico-2-interface-personalizável) (EP02) | Compatibilidade com Android e iOS ([US14](./historia-de-usuario.md)) | RNF01 | MH | em progresso | [AD09](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [João Marcos](https://github.com/JJOAOMARCOSS) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [João Marcos](https://github.com/JJOAOMARCOSS) | Bianca Regina |

<font size="3"><p style="text-align: center"> Fonte: Elaborado por ([João Marcos](https://github.com/JJOAOMARCOSS), 2025).</p></font>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Vitor Pereira forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](/docs/assets/backlog-termo/Bianca-termo%20de%20Consentimento%20.pdf)


### Validação 5 - Karoline Luz


**Vídeo 5** - Validação com usuário por Karoline Luz

<iframe width="560" height="315" src="https://www.youtube.com/embed/E0MSih6ABqg" title="Validação Backlog - Karoline Luz" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Tabela 8** - Informações da validação 5

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Acessar informações de agendamento e reagendamento ([US22](./historia-de-usuario.md)) | RF16 | MH | Validado | [BR17](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Karoline Luz](https://github.com/KarolineLuz) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Reportar problemas da cidade via mapa interativo ([US23](./historia-de-usuario.md)) | RF25 | MH |Validado | [EN09](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Karoline Luz](https://github.com/KarolineLuz) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Acessar números de serviços de emergência ([US24](./historia-de-usuario.md)) | RF26 | SH | Validado | [EN10](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [INT05](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Karoline Luz](https://github.com/KarolineLuz) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Solicitar serviços como coleta de lixo e reparos ([US25](./historia-de-usuario.md)) | RF28 | MH | Validado | [AD02](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Karoline Luz](https://github.com/KarolineLuz) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Localizar solicitações no mapa ([US26](./historia-de-usuario.md)) | RF29 | CH | Validado | [AD03](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Karoline Luz](https://github.com/KarolineLuz) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Emitir tributos, certidões e documentos fiscais ([US27](./historia-de-usuario.md)) | RF43 | SH | Validado | [INT13](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT), [BR18](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Karoline Luz](https://github.com/KarolineLuz) |
| [Acessibilidade](#tema-9-acessibilidade) | [Recursos de Acessibilidade](#épico-3-recursos-acessibilidade) (EP03) | Interface acessível para idosos ([US28](./historia-de-usuario.md)) | RNF16 | SH | Validado | [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Karoline Luz](https://github.com/KarolineLuz) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [Karoline Luz](https://github.com/KarolineLuz) |  Leonardo Rodrigues Martins|


## Termo de consentimento de imagem 
Este documento confirma que o cidadão Leonardo Rodrigues Martins forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1K8P5RS7xYEd8k3xGEkLp9QrjuAOqB51s/view?usp=sharing)

<p style="text-align: center"><font size="3">Fonte: Elaborado por (<a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025).</font></p>

### Validação 6 - Lucas Mendonça

**Vídeo 6** - Validação com usuário por Lucas Mendonça

<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_LUCAS_MENDONCA" title="Validação Backlog - Lucas Mendonça" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Tabela 9** - Informações da validação 6

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Emitir tributos, certidões e documentos fiscais ([US43](./historia-de-usuario.md)) | RF39 | SH | em progresso | [INT09](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Lucas Mendonça](https://github.com/lucasarruda9) |
| [Comunicação](#tema-4-comunicação) | [Informações Públicas](#épico-5-informações-públicas) (EP05) | Feed com notícias oficiais do GDF ([US44](./historia-de-usuario.md)) | RF42 | CH | em progresso | [INT12](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Lucas Mendonça](https://github.com/lucasarruda9) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Agendar atendimentos de serviços sociais ([US45](./historia-de-usuario.md)) | RF37 | SH | em progresso | [INT06](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Lucas Mendonça](https://github.com/lucasarruda9) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Serviços Centralizados](#épico-4-serviços-centralizados) (EP04) | Acompanhar pendências escolares ([US46](./historia-de-usuario.md)) | RF24 | SH | em progresso | [EN06](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Lucas Mendonça](https://github.com/lucasarruda9) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Visualizar histórico de interações e solicitações ([US47](./historia-de-usuario.md)) | RF41 | SH | em progresso | [INT11](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) | [Lucas Mendonça](https://github.com/lucasarruda9) |
| [Comunicação](#tema-4-comunicação) | [Comunicações Personalizadas](#épico-7-comunicações-personalizadas) (EP07) | Receber notificações por categorias ([US48](./historia-de-usuario.md)) | RF17 | CH | em progresso | [BR19](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Lucas Mendonça](https://github.com/lucasarruda9) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Consultar informações offline ([US49](./historia-de-usuario.md)) | RNF23 | SH | em progresso | [INT20](../../elicitacao/tec_elicitacao/introspeccao.md#anchor_INTT) | [Lucas Mendonça](https://github.com/lucasarruda9) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [Lucas Mendonça](https://github.com/lucasarruda9) |  |

<p style="text-align: center"><font size="3">Fonte: Elaborado por (<a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025).</font></p>

### Validação 7 - Luiza Silva

**Vídeo 7** - Validação com usuário por Luiza Silva

<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_LUIZA_SILVA" title="Validação Backlog - Luiza Silva" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Tabela 10** - Informações da validação 7

| **Tema** | **Épico (ID)** | **História do Usuário (US)** | **ID** | **Prioridade** | **Status** | **Rastreabilidade** | **Autor** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [Autenticação](#tema-1-autenticação) | [Autenticação Segura](#épico-1-autenticação-segura) (EP01) | Realizar login com acesso unificado do GOV.br ([US01](./historia-de-usuario.md)) | RF22 | MH | em progresso | [EN04](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| [Documentos](#tema-5-documentos) | [Gestão de Documentos](#épico-8-gestão-documentos) (EP08) | Compartilhamento e salvamento de informações importantes ([US02](./historia-de-usuario.md)) | RF18 | CH | em progresso | [BR20](../../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| [Atendimento](#tema-6-atendimento) | [Canais de Suporte](#épico-9-canais-suporte) (EP09) | Acesso a suporte com instruções de uso ([US03](./historia-de-usuario.md)) | RF27 | CH | em progresso | [EN11](../../elicitacao/tec_elicitacao/entrevista.md#anchor_EN) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Acompanhamento de status de solicitações ([US04](./historia-de-usuario.md)) | RF30 | SH | em progresso | [AD04](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| [Serviços do Cidadão](#tema-3-serviços-do-cidadão) | [Agendamentos](#épico-6-agendamentos) (EP06) | Confirmação da resolução de problemas ([US05](./historia-de-usuario.md)) | RF31 | SH | em progresso | [AD06](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| [Privacidade](#tema-8-privacidade) | [Controle de Privacidade](#épico-11-controle-privacidade) (EP11) | Exclusão de conta e dados pessoais ([US06](./historia-de-usuario.md)) | RF32 | SH | em progresso | [AD07](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| [Privacidade](#tema-8-privacidade) | [Controle de Privacidade](#épico-11-controle-privacidade) (EP11) | Conformidade com LGPD ([US07](./historia-de-usuario.md)) | RNF02 | SH | em progresso | [AD10](../../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) | [Luiza da Silva Pugas](https://github.com/Luizaxx) |

| **Autor** | **Usuário Participante** |
| :-------- | :---------------------- |
| [Luiza Silva](https://github.com/Luizaxx) |  |

<p style="text-align: center"><font size="3">Fonte: Elaborado por (<a href="https://github.com/Luizaxx">Luiza Silva</a>, 2025).</font></p>

## Referência Bibliográfica

> <a id="REF1" href="#citacao1">1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Universidade de Brasília, Faculdade do Gama, [s.d.].

> <a id="REF2" href="#citacao2">2.</a> RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian.

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Universidade de Brasília, Faculdade do Gama, [s.d.]. Disponível em: [Link](https://aprender3.unb.br/pluginfile.php/3096144/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 28 maio 2025.

> RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Link](https://www.atlassian.com/br/agile/scrum/backlogs). Acesso em: 28 maio 2025.

> O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Link](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto). Acesso em: 28 maio 2025. 

<figure id="ref-backlog-fonte1">
    <img src="../../../../assets/agil/backlog/backlog-fonte1.png" alt="Exemplo de Product Backlog" width="500" onerror="this.onerror=null;this.src='../../assets/agil/backlog/backlog-fonte1.png'">
    <figcaption>Fonte: SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 15. Universidade de Brasília, Faculdade do Gama, [s.d.].</figcaption>
</figure>

<figure id="ref-backlog-fonte2">
    <img src="../../../../assets/agil/backlog/backlog-fonte2.png" alt="Benefícios e Priorização do Product Backlog" width="500" onerror="this.onerror=null;this.src='../../assets/agil/backlog/backlog-fonte2.png'">
    <figcaption>Fonte: RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian.</figcaption>
</figure>

## Histórico de Versões

| Versão | Descrição | Autor | Data | Revisor | Data Revisão |
|--------|-----------|-------|------|---------|--------------|
| 1.0 | Criação da página | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 23/05/2025 | [Ana Victória](https://github.com/navicg) | 23/05/2025 |
| 1.1 | Criação da introdução e do padrão a ser seguido | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 28/05/2025 |
| 1.2 | Reorganização das seções de referências e adição base das referências bibliográficas | [Artur Mendonça](https://github.com/ArtyMend07) | 28/05/2025| [Gabriel Lopes](https://github.com/BrzGab) | 29/05/2025 |
| 1.3 | Criação de tabelas de Product Backlog RF12, RF13, RF14, RF35, RF36, RF38, RNF01 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 30/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 30/05/2025 |
| 1.4 | Criação de tabelas de Product Backlog RF22, RF18, RF27, RF30, RF31, RF32, RNF02 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 30/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 30/05/2025 |
| 1.5 | Criação de tabelas de Product Backlog RF04, RF05, RF06, RF11, RF21, RF33, RNF20 | [Artur Mendonça](https://github.com/ArtyMend07) | 30/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 30/05/2025 |
| 1.6 | Criação de tabelas de Product Backlog RF16, RF25, RF26, RF28, RF29, RF43, RNF16 | [Karoline Luz](https://github.com/KarolineLuz) | 30/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 30/05/2025 |
| 1.7 | Criação de tabelas de Product Backlog RF01, RF02, RF03, RF09, RF15, RF20, RNF13 | [Ana Victória](https://github.com/navicg) | 30/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 30/05/2025 |
| 1.8 | Criação de tabelas de Product Backlog RF07, RF08, RF10, RF19, RF23, RF34, RNF22 | [Gabriel Lopes](https://github.com/BrzGab) | 30/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 30/05/2025 |
| 1.9 | Criação de tabelas de Product Backlog US46, US43, US49, US47, US45, US44, US48 | [Lucas Mendonça](https://github.com/lucasarruda9) | 31/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 31/05/2025 |
| 2.0 | Criação dos temas, épicos e das tabelas | [Gabriel Lopes](https://github.com/BrzGab) | 31/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 31/05/2025 |
| 2.1 | Ajuste dos temas e épicos, e adição de rastreabilidade (hyperlinks)  | [Artur Mendonça](https://github.com/ArtyMend07) e [Gabriel Lopes](https://github.com/BrzGab) | 01/06/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 01/06/2025 | 
| 2.2 | Adicionando Entrevista e Termo de consentimento  | [Karoline Luz](https://github.com/KarolineLuz) | 01/06/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 01/06/2025 |
| 2.3 | Correção das prioridades dos requisitos RF16, RF25, RF26, RF28, RF29, RF43, RNF16  | [Artur Mendonça](https://github.com/ArtyMend07) | 01/06/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 01/06/2025 |
| 2.4 | Validação do Product Backlog  RF01, RF02, RF03, RF09, RF15, RF20, RNF13 com usuário real | [Ana Victória](https://github.com/navicg) | 01/06/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 01/06/2025 |
| 2.5 | Validaçaõ do Product Backlog com usuario real RF07, RF08, RF10, RF19, RF23, RF34, RNF22 | [Gabriel Lopes](https://github.com/BrzGab) | 01/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 30/05/2025 |