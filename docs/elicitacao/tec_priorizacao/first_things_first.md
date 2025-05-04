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


| ID  | Descrição | Rastreabilidade | Implementação |
| --- | --------- | --------------- | ------------- |
| RF29   | O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos.                                                        | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD02</a>                                                                                                                 | Não           |
| RF30   | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço                                                                          | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD03</a>                                                                                                                 | Não           |
| RF31   | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.                                                                              | <a href="../tec_elicitacao/analise_decisao/#anchor_AD">AD04</a>                                                                                                                 | Não           |
| RF34   | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação.                                              | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT01</a>                                                                                                                  | Sim           |
| RF35   | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes.                                                     | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT02</a>                                                                                                                  | Sim           |
| RF36   | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo).                                                                               | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT03</a>                                                                                                                  | Sim           |
| RF37   | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência.                                                                                      | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT04</a>                                                                                                                  | Sim           |
| RF38   | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue.                                                                              | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT06</a>                                                                                                                  | Sim           |
| RF41   | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais.                                                                                            | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT10</a>                                                                                                                  | Sim           |
| RF42   | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos.                                                                  | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT11</a>                                                                                                                  | Sim           |
| RF43   | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal.                                                                         | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT12</a>                                                                                                                  | Sim           |
| RF45   | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas.                                                                                  | <a href="../tec_elicitacao/introspeccao/#anchor_INT">INT14</a>                                                                                                                  | Sim           |
| RNF05  | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                                                                                 | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a>                                                                                                                  | Não           |
| RNF06  | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                                                                                         | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a>                                                                                                                  | Sim           |
| RNF08  | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta                                                                                  | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a>                                                                                                                  | Sim           |
| RNF10  | O sistema deve ter compatibilidade com leitores de tela                                                                                                                 | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a>                                                                                                                  | Sim           |
| RNF13  | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação.                 | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN02</a>                                                                                                                       | Sim           |
| RNF15  | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.                                             | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN04</a>                                                                                                                       | Sim           |
| RNF21  | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.                                                               | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT16</a>                                                                                                                   | Sim           |








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
