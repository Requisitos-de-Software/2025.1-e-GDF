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
| [Luiza da Silva Pugas](https://github.com/Luizaxx) | Mediador |
| [Artur Mendonça](https://github.com/ArtyMend07)    | Desenvolvedor       |
| [Lucas Mendonça ](https://github.com/lucasarruda9) | Desenvolvedor |
| Camily Andressa    | Cliente       |
| Nivea Cecilia    | Cliente       |
| Gabriel Souza    | Cliente       |

<font size="3"><p style="text-align: center">Elaborado por: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

### Reuniões realizadas

### Gravação da Técnica First-Things-First com os Clientes

<p style="text-align: center">
  <iframe width="560" height="315" src="https://youtube.com/embed/g1nRaqaymdE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

<p style="text-align: center"><a href="https://youtu.be/g1nRaqaymdE" target="_blank">Clique aqui para assistir no YouTube</a></p>


### Gravação da Técnica First-Things-First com os Densevolvedores

<p style="text-align: center">
  <iframe width="560" height="315" src="https://youtube.com/embed/9PtmtIjqJJs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

<p style="text-align: center"><a href="https://youtu.be/9PtmtIjqJJs" target="_blank">Clique aqui para assistir no YouTube</a></p>

---

# Tabela de Priorização de Requisitos

### Tabela com os dados no Excel: 

<figure markdown="span">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Carteira-Digital-de-Transito/refs/heads/docs/first-things-first/docs/assets/Tabela-First-things-First.png">
</figure>
<font size="3"><p style="text-align: center">Elaborado por: [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>

### Tabela 1 em ordem decrescente de prioridade: 

| Requisito | ID                                                                 | Benefício relativo | Penalidade relativa | Valor total | Valor (%) | Custo relativo | Risco relativo | Esforço total | Custo (%) | Risco (%) | Prioridade |
| --------- | ------------------------------------------------------------------ | ------------------ | ------------------- | ----------- | --------- | -------------- | -------------- | ------------- | --------- | --------- | ---------- |
| RF06      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT03</a>  | 9                  | 9                   | 27          | 3,69%     | 2              | 1              | 2.5           | 1,01%     | 0,52%     | 242,59%    |
| RF05      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT02</a>  | 8                  | 7                   | 23          | 3,05%     | 4              | 2              | 5             | 1,97%     | 1,03%     | 122,55%    |
| RF12      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT14</a>  | 9                  | 9                   | 27          | 4,44%     | 5              | 5              | 7.5           | 2,96%     | 3,07%     | 114,98%    |
| RF09      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT10</a>  | 8                  | 8                   | 24          | 3,66%     | 6              | 4              | 8             | 3,28%     | 2,27%     | 82,99%     |
| RNF04     | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a> | 8                  | 7                   | 23          | 4,47%     | 4              | 5              | 6.5           | 2,78%     | 3,55%     | 81,76%     |
| RF11      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT12</a>  | 5                  | 5                   | 15          | 2,41%     | 4              | 3              | 5.5           | 2,31%     | 1,81%     | 74,87%     |
| RF08      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT06</a>  | 9                  | 9                   | 27          | 3,96%     | 7              | 8              | 11            | 3,68%     | 4,35%     | 71,76%     |
| RF01      | <a href="../../tec_elicitacao/analise_decisao/#anchor_AD">AD02</a> | 9                  | 9                   | 27          | 6,37%     | 8              | 6              | 11            | 6,84%     | 5,45%     | 66,58%     |
| RF07      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT04</a>  | 8                  | 7                   | 23          | 3,26%     | 7              | 7              | 10.5          | 3,55%     | 3,66%     | 60,57%     |
| RNF01     | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a> | 8                  | 8                   | 24          | 4,13%     | 8              | 8              | 12            | 4,88%     | 5,06%     | 55,75%     |
| RNF05     | <a href="../../tec_elicitacao/entrevista/#anchor_EN">EN02</a>      | 9                  | 8                   | 26          | 5,28%     | 9              | 9              | 13.5          | 6,43%     | 6,62%     | 54,27%     |
| RNF07     | <a href="../../tec_elicitacao/integracao/#anchor_INTT">INT16</a>   | 9                  | 5                   | 23          | 5,15%     | 8              | 8              | 12            | 6,40%     | 6,78%     | 52,56%     |
| RF02      | <a href="../../tec_elicitacao/analise_decisao/#anchor_AD">AD03</a> | 8                  | 7                   | 23          | 2,80%     | 6              | 6              | 9             | 2,65%     | 2,80%     | 52,05%     |
| RNF06     | <a href="../../tec_elicitacao/entrevista/#anchor_EN">EN04</a>      | 7                  | 5                   | 19          | 4,08%     | 6              | 9              | 10.5          | 4,58%     | 7,09%     | 51,68%     |
| RNF02     | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a> | 9                  | 9                   | 27          | 4,85%     | 4              | 1              | 4.5           | 2,56%     | 0,67%     | 95,13%     |
| RF03      | <a href="../../tec_elicitacao/analise_decisao/#anchor_AD">AD04</a> | 9                  | 9                   | 27          | 3,38%     | 9              | 8              | 13            | 4,09%     | 3,85%     | 56,26%     |
| RF04      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT01</a>  | 6                  | 4                   | 16          | 2,08%     | 8              | 6              | 11            | 3,79%     | 3,00%     | 36,31%     |
| RF10      | <a href="../../tec_elicitacao/introspeccao/#anchor_INT">INT11</a>  | 3                  | 2                   | 8           | 1,27%     | 4              | 6              | 7             | 2,26%     | 3,49%     | 37,33%     |
| RNF03     | <a href="../../tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a> | 5                  | 5                   | 15          | 2,83%     | 8              | 8              | 12            | 5,26%     | 5,37%     | 35,61%     |

<font size="3"><p style="text-align: center">Elaborado por: [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx).</p></font>


----

# Elicitação de Requisitos Funcionais

Legenda da Tabela:  
- RFx: Requisito Funcional nºx  
- **ID**: Link para a técnica de elicitação

### Tabela 2: Requisitos Funcionais

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


### Tabela 3: Requisitos não Funcionais

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

## Referências Bibliográficas

- FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf Acesso em 4 de março de 2025.

![](https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/tabela_Elicitacao.jpeg) 

## Histórico de Versões

| Versão | Descrição                                     | Autor(es)                                                                                                  | Data       | Revisor(es)                            | Data de revisão |
| ------ | --------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------- | --------------- |
| 1.0    | Criação da documentação do First Things First | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 02/05/2025 | [Artur](https://github.com/ArtyMend07) | 02/05/2025      |
| 1.1    | Modificação nas tabelas de funcionais e não funcionais | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 04/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 04/05/2025      |
| 1.2    | Adicionando os links para os videos | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 04/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 04/05/2025      |
| 1.3    | Adicionando a tabela | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 04/05/2025 | [Artur](https://github.com/ArtyMend07) | 04/05/2025      |
| 2.0    | Correção e padronização das tabelas, fontes e ajustes gerais | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 11/05/2025 | [Ana Victória](https://github.com/navicg)          | 12/05/2025      |