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
| [João Marcos Moraes](https://github.com/JJOAOMARCOSS)   | Mediador      |
| Wanjo Christopher    | Cliente       |
| [Luiza da Silva Pugas](https://github.com/Luizaxx) | Desenvolvedor |

<font size="3"><p style="text-align: center">Elaborado por: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

### Reuniões realizadas

- *(Adicione aqui a data e descrição das reuniões, caso deseje)*

---

# Elicitação de Requisitos Funcionais

Legenda da Tabela:  
- RFx: Requisito Funcional nºx  
- **ID**: Link para a técnica de elicitação

### Tabela 1: Requisitos Funcionais

| Requisitos | ID                                                 | Descrição                                                                                                                  |
| ---------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| RF01       | <a href="../../tec_elicitacao/analise_decisao/#anchor_AD">AD02</a> | O sistema deve permitir que o usuário solicite serviços públicos como coleta de lixo, reparo de vias e diversos.           |
| RF02       | <a href="../../tec_elicitacao/analise_decisao/#anchor_AD">AD03</a> | O sistema deve permitir o usuário utilizar um mapa para localizar onde foi solicitado o serviço.                           |
| RF03       | <a href="../../tec_elicitacao/analise_decisao/#anchor_AD">AD04</a> | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.                                |
| RF04       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT01</a>  | Permitir o registro de ocorrências relacionadas a problemas de infraestrutura urbana, como buracos ou falta de iluminação. |
| RF05       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT02</a>  | Disponibilizar categorias pré-definidas para o tipo de ocorrência, facilitando a triagem pelos órgãos competentes.         |
| RF06       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT03</a>  | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo).                                |
| RF07       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT04</a>  | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência.                                        |
| RF08       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT06</a>  | Disponibilizar agendamento de serviços de saúde pública, como vacinação ou doação de sangue.                               |
| RF09       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT10</a>  | Disponibilizar a emissão de tributos, certidões e outros documentos fiscais.                                               |
| RF10       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT11</a>  | Fornecer um histórico de interações do usuário com o aplicativo, incluindo solicitações e agendamentos.                    |
| RF11       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT12</a>  | Apresentar um feed de notícias atualizadas com informações úteis do Governo do Distrito Federal.                           |
| RF12       | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT14</a>  | Fornecer um mapa com localização de unidades de serviço público e ocorrências próximas.                                    |

<font size="3"><p style="text-align: center">Elaborado por: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

--------------
# Elicitação de Requisitos Não-Funcionais

Legenda da Tabela:  
- RNFx: Requisito Não-Funcional nºx  
- **ID**: Link para a técnica de elicitação


### Tabela 2: Requisitos não Funcionais

| Requisitos | ID                                                 | Descrição                                                                                                                                               |
| ---------- | --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RNF01      | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a> | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual.                                                                |
| RNF02      | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a> | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware.                                                                        |
| RNF03      | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a> | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta.                                                                 |
| RNF04      | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a> | O sistema deve ter compatibilidade com leitores de tela.                                                                                                |
| RNF05      | <a href="../../tec_elicitacao/entrevista/#anchor_EN">EN02</a>      | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação. |
| RNF06      | <a href="../../tec_elicitacao/entrevista/#anchor_EN">EN04</a>      | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.                              |
| RNF07      | <a href="../../tec_elicitacao/integracao/#anchor_INTT">INT16</a>   | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.                                               |

<font size="3"><p style="text-align: center">Elaborado por: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

---

# Histórico de Versões

| Versão | Descrição                                     | Autor(es)                                                                                                  | Data       | Revisor(es)                            | Data de revisão |
| ------ | --------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------- | --------------- |
| 1.0    | Criação da documentação do First Things First | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 02/05/2025 | [Artur](https://github.com/ArtyMend07) | 02/05/2025      |
| 1.1    | Modificação nas tabelas de funcionais e não funcionais | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 04/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 04/05/2025      |