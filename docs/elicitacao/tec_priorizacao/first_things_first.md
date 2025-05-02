# Priorização dos Requisitos - Técnica First Things First (FTF)

## Introdução

A técnica **First Things First** (FTF), proposta por **Karl Wiegers (1999)**, é um método de priorização que visa equilibrar os interesses do cliente e do desenvolvedor ao considerar benefícios, penalidades, custos e riscos associados a cada requisito. O objetivo é garantir que a priorização maximize o valor de negócio e minimize riscos e custos, de forma alinhada com as regras de negócio e as capacidades da equipe de desenvolvimento.

O método fornece um ranking quantitativo de requisitos para apoiar a tomada de decisão no planejamento do projeto. Para aplicá-lo, são seguidos os 8 (oito) passos abaixo:

1. **Listar todos os requisitos** em uma tabela, retirando aqueles dependentes de outro requisito.
2. **Estimar o benefício relativo** que cada recurso fornece ao cliente ou ao negócio, de 1 a 9, em que 1 é o menos significativo e 9 é o mais significativo.
3. **Estimar a penalidade** que o negócio sofreria se o recurso não fosse incluído, de 1 a 9, em que 1 indica menor penalidade e 9 maior penalidade.
4. **Calcular o valor total** de cada requisito:  
\[
Valor\ total = (Benefício × Peso_{benefício}) + (Penalidade × Peso_{penalidade})
\]  
Os pesos utilizados neste trabalho foram **2** para benefício e **1** para penalidade.
5. **Estimar o custo relativo** de implementação de cada requisito, de 1 a 9.
6. **Estimar o risco relativo** associado a cada requisito, em uma escala de 1 a 9.
7. **Calcular a prioridade** de cada requisito usando a fórmula:  
\[
Prioridade = \frac{Valor(\%)}{Custo(\%) × Peso_{custo} + Risco(\%) × Peso_{risco}}
\]  
Os pesos utilizados foram **1** para custo e **0,5** para risco.
8. **Ordenar a lista** em ordem decrescente de prioridade. Os requisitos no topo da lista devem ser priorizados na implementação.

## Metodologia

### Participantes

O processo de priorização FTF foi conduzido a partir de sessões de brainstorming, envolvendo os seguintes participantes:

| Nome                 | Função        |
| -------------------- | ------------- |
| João Marcos Moraes   | Mediador      |
| Wanjo Christopher    | Cliente       |
| Luiza da Silva Pugas | Desenvolvedor |

<font size="3"><p style="text-align: center">Fonte: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

### Reuniões realizadas

- *(Adicione aqui a data e descrição das reuniões, caso deseje)*

---

# Elicitação de Requisitos Funcionais

Legenda da Tabela:  
- RFx: Requisito Funcional nºx  
- **ID**: Link para a técnica de elicitação (Brainstorming)

### Tabela 1: Requisitos Funcionais

| Tipo                      | ID                                                         | Descrição                                                                                                 | Código | Implementado |
| ------------------------- | ---------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------ | ------------ |
| **REQUISITOS FUNCIONAIS** |                                                            |                                                                                                           |        |              |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR01</a> | O usuário deve conseguir realizar login de forma simples e rápida                                         | RF01   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR02</a> | O usuário deve conseguir acessar funcionalidades mesmo com pouca familiaridade com tecnologia             | RF02   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR03</a> | O usuário deve poder receber notificações personalizadas com base em sua localização                      | RF03   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR04</a> | O usuário deve poder consultar agendamentos e serviços em um único local centralizado                     | RF04   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR05</a> | O usuário deve ter acesso a um assistente virtual com acessibilidade por voz                              | RF05   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR06</a> | O usuário deve poder acessar tutoriais passo a passo sobre como usar o app                                | RF06   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR07</a> | O usuário deve poder alterar o tamanho da fonte e o contraste de cores                                    | RF07   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR08</a> | O aplicativo deve permitir modo escuro                                                                    | RF08   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR10</a> | O usuário deve poder acessar e visualizar notícias relevantes                                             | RF10   | Sim          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR11</a> | O usuário deve poder gerar relatórios e visualizar comprovantes de agendamentos                           | RF11   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR12</a> | O aplicativo deve permitir a integração com serviços de saúde, educação e mobilidade                      | RF12   | Sim          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR13</a> | O usuário deve poder alterar o idioma do aplicativo                                                       | RF13   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR14</a> | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços               | RF14   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR15</a> | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes          | RF15   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR16</a> | O usuário deve poder acessar um menu com as principais funções logo na tela inicial                       | RF16   | Sim          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR17</a> | O usuário deve poder acessar informações de agendamento e reagendamento de forma centralizada             | RF17   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR18</a> | O usuário deve poder utilizar chatbot para tirar dúvidas                                                  | RF18   | Sim          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR19</a> | O aplicativo deve permitir notificações por categorias como saúde, educação, transporte                   | RF19   | Não          |
|                           | <a href="../../tec_elicitacao/brainstorming/#anchor_BS">BR20</a> | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes) | RF20   | Não          |

<font size="3"><p style="text-align: center">Fonte: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

---

# Elicitação de Requisitos Não-Funcionais

Legenda da Tabela:  
- RNFx: Requisito Não-Funcional nºx  
- **ID**: Link para a técnica de elicitação (Brainstorming)

### Tabela 2: Requisitos Não-Funcionais

| Tipo                          | ID                                                            | Descrição                                                                                         | Código | Implementado |
| ----------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------ | ------------ |
| **REQUISITOS NÃO FUNCIONAIS** |                                                               |                                                                                                   |        |              |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN01</a> | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos                     | RNF01  | Sim          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN02</a> | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual           | RNF02  | Não          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN04</a> | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                   | RNF04  | Sim          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN05</a> | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos | RNF05  | Não          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN06</a> | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta            | RNF06  | Sim          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN07</a> | O layout deve ser responsivo para diferentes tamanhos de tela                                     | RNF07  | Sim          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN08</a> | O sistema deve ter compatibilidade com leitores de tela                                           | RNF08  | Sim          |
|                               | <a href="../../tec_elicitacao/brainstorming/#anchor_BSNF">BRN09</a> | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade       | RNF09  | Não          |

<font size="3"><p style="text-align: center">Fonte: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

---

# Histórico de Versões

| Versão | Descrição                                     | Autor(es)                                                                                                  | Data       | Revisor(es)                            | Data de revisão |
| ------ | --------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------- | --------------- |
| 1.0    | Criação da documentação do First Things First | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 02/05/2025 | [Artur](https://github.com/ArtyMend07) | 02/05/2025      |
