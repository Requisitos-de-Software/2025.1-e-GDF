# Entrevista

## Introdução
Entre as técnicas estudadas na disciplina de Requisitos de Software, as entrevistas se destacam por sua praticidade e eficácia na coleta de informações diretamente com os usuários. Essa abordagem permite compreender de forma mais aprofundada as necessidades e expectativas do público-alvo, seja em conversas individuais ou em pequenos grupos. No contexto do estudo do eGDF, as entrevistas realizadas com os usuários do aplicativo tiveram como objetivo principal levantar dados sobre suas perspectivas, demandas e dificuldades encontradas na utilização da solução eletrônica para os serviços do Distrito Federal.

## Metodologia 

A entrevista foi realizada induvidulamente, pelos membros da equipe [Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07). Cada integrante foi responsável por realizar entrevistas específicas com usuários distintos, conforme detalhado na tabela abaixo. O processo seguiu um roteiro pré-definido, elaborado para garantir a consistência das perguntas e facilitar a coleta de dados comparáveis. No entanto, o script foi aplicado de maneira flexível, permitindo ajustes em tempo real para se adequar ao perfil e às respostas de cada entrevistado, tornando a conversa mais natural e aprofundada quando necessário. Com os dados coletados a partir das respostas dos entrevistados, foram levantados os **requisitos funcionais** e **não funcionais**.

<font size="3"><p style="">**Tabela 1: Detalhes da Entrevista**.</p></font>

<center>

| Entrevistador |Entrevistado|Data|  Hora | Local|Duração|
| ---------------------------------------|------------ |------------------------ | ------ |-------|----------|
|[Ana Victória](https://github.com/navicg)| Luís Felipe |30/04/2025| 12:20 | UnB-FCTE | 07:40|
| [Ana Victória](https://github.com/navicg) | Júnia Luz |01/05/2025|  17:11 | Microsoft Teams|10:20|
| [Artur Mendonça](https://github.com/ArtyMend07)|...| ...| ...|... |...|

</center>

Fonte: [Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07), 2025.

## Links das Gravações
[Primeira Entrevista - Luis felipe](https://youtu.be/t8xXrzlBbdM)

[Segunda Entrevista - Júnia Luz ](https://youtu.be/CpYU4PauOWY)

## Perguntas Realizadas

**Conhecimento e Primeiro Contato com o App:**

1. Você conhece o aplicativo eGDF?


2. Como ficou sabendo do aplicativo?


3. Por que decidiu instalar ou usar o app?


4. Lembra da sua primeira impressão ao abrir o aplicativo?



**Frequência e Objetivo de Uso:**

5. Com que frequência você usa o eGDF?


6. Em geral, para que você costuma usar o aplicativo?



**Usabilidade e Experiência:**

7. Você acha fácil navegar pelo app? Por quê?


8. As informações são claras e bem organizadas?


9. Já ficou perdido(a) ou sem saber onde clicar? Em qual parte?


10. Você costuma conseguir resolver o que precisa só pelo app, ou acaba buscando ajuda por outros meios?




**Funcionalidades e Conteúdo:**

11. Quais funcionalidades do app você mais usa ou considera mais úteis?


12. Existe alguma função que você esperava encontrar no app e não tinha?


13. Já encontrou informações desatualizadas ou erradas no aplicativo?



**Problemas e Suporte:**

14. Já teve algum problema técnico usando o app? Travamentos, lentidão, erros?


15. Se teve algum problema, conseguiu resolvê-lo? Como?


16. Já procurou ajuda ou suporte dentro do app? Foi fácil encontrar?


**Segurança e Confiança:**

17. Você se sente seguro(a) usando o app, em relação aos seus dados pessoais?


18. O processo de login (autenticação) te parece fácil e confiável?


19. Você confia nas informações que o app mostra?




**Acessibilidade e Inclusão:**

20. Você acha que o aplicativo é acessível para todos os tipos de usuários (pessoas idosas, com deficiência visual, etc.)?



**Melhorias e Expectativas:**

21. O que você mudaria no aplicativo, se pudesse?


22. Tem alguma ideia de funcionalidade nova que você acha que poderia ajudar outros usuários?


23. Em uma escala de 0 a 5, qual nota você daria e porque?

## Requisitos Elicitados
<font size="3"><p style="">**Tabela 2: Requisitos Funcionais**.</p></font>

<center>

| Tipo | Descrição | ID | Implementado |
|------|-----------|----|--------------|
| RF01 | O aplicativo permite a visualização da localização dos ônibus em tempo real, incluindo previsão de chegada e rota no mapa. | RF01 | Sim |
| RF02 | O aplicativo fornece links para serviços externos (como Secretaria da Fazenda) de forma eficiente, com explicações claras sobre o que o usuário encontrará após clicar. | RF02 | Parcial |
| RF03 | O aplicativo oferece funcionalidades para consulta de informações educacionais, como calendário letivo e status de vagas no CIL. | RF03 | Parcial |
| RF04 | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial. | RF04 | Parcial |
| RF05 | O aplicativo facilita o acesso a serviços relacionados a impostos (como boletos do IPVA) com instruções claras. | RF05 | Sim |
| RF06 | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos. | RF06 | Não |
| RF07 | O aplicativo inclui recursos de acessibilidade como leitura em áudio para deficientes visuais e suporte em Libras para deficientes auditivos. | RF07 | Não |
| RF08 | O aplicativo permite ajuste de tamanho de fonte para facilitar a leitura, especialmente por usuários idosos. | RF08 | Não |

</center>

Fonte: [Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07), 2025.

<font size="3"><p style="">**Tabela 3: Requisitos Não Funcionais**.</p></font>

<center>

| Tipo | Descrição | ID | Implementado |
|------|-----------|----|--------------|
| RNF01 | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos. | RNF01 | Não |
| RNF02 | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação. | RNF02 | Parcial |
| RNF03 |O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis.| RNF03 | Não |
| RNF04 | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança. | RNF04 | Sim |
| RNF05 | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida. | RNF05 | Não |
| RNF06 | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis. | RNF06 | Não |


</center>

Fonte: [Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07), 2025.


## Bibliografia

WIEGERS, Karl E.; BEATTY, Joy. Software requirements. 3. ed. Redmond: Microsoft Press, 2013. Disponível em:
[https://olivroqueaprende.com/WDK/Software_Requirements_3rd_Edition.pdf](https://olivroqueaprende.com/WDK/Software_Requirements_3rd_Edition.pdf). Acesso em 01 mai.2025

## Histórico de Versões

| Versão | Data | Descrição| Autor(es)             | Revisor(es)      |Data de Revisão |
| :----: | :----------------: | :--------------------------------------------------: | :-------------------: | :-------------:  |  :-----------: |
| 1.0 | 01/05/2025 | Organizando e adicionando algumas informações das entrevistas feitas. | [Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07)| [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | .. |