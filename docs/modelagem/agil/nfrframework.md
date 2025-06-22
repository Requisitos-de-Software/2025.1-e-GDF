# NFR Framework

## Introdução

O **NFR Framework** é uma abordagem para representar e analisar [Requisitos Não-Funcionais](../../elicitacao/req_elicitados.md), oferecendo uma estrutura formal para armazenar tanto o desenho quanto o racional por trás do processo de design de requisitos. Seu objetivo é auxiliar desenvolvedores na implementação de soluções personalizadas, considerando:

- Características do domínio e do sistema em questão;
- Requisitos funcionais e não-funcionais;
- Prioridades e carga de trabalho.

Esses fatores determinam a escolha das alternativas de desenvolvimento mais adequadas para cada sistema. Para isso, o framework utiliza grafos chamados **Softgoal Interdependency Graphs (SIGs)**, nos quais os *softgoals* representam objetivos abstratos de satisfação imprecisa.<a id="anchor_1" href="#REF1">[1]</a>

## Softgoal Interdependency Graph (SIG)

O **Softgoal Interdependency Graph (SIG)** é uma ferramenta gráfica utilizada pelo *NFR Framework* para representar decisões de projeto relacionadas a *softgoals* — objetivos com critérios de satisfação vagos ou imprecisos. Cada nó do grafo representa um *softgoal*, enquanto as arestas indicam relações de decomposição ou de contribuição entre eles. <a id="anchor_1" href="#REF1">[1]</a>

### Tipos de Softgoal

Para compreender o funcionamento do SIG, é essencial entender os diferentes tipos de *softgoal*:

1. **Softgoals NFR**  
   Representam diretamente os Requisitos Não-Funcionais. São organizados hierarquicamente e agrupados em catálogos temáticos (como desempenho, segurança, usabilidade, etc.).

2. **Softgoals de Operacionalização**  
   Correspondem a soluções concretas (operações, processos, estruturas de dados, restrições) que visam satisfazer *softgoals* NFR ou outros de operacionalização.

3. **Softgoals de Afirmação**  
   São registros em linguagem natural que expressam justificativas de projeto ou fatores do domínio, como carga de trabalho, decisões de priorização e contexto organizacional.

A figura 1 mostra a representação dos tipos de *softgoals* que estão presentes em um NRF Framework:

<p align="center"><i>Figura 1: Tipos das Softgoals</i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/tipos.png" width="600">
</p>

<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

### Interdependências

As interdependências no SIG definem as associações entre os *softgoals* e se dividem em dois tipos principais:

#### Decomposições

A decomposição permite subdividir *softgoals* em objetivos mais específicos, facilitando a análise e a priorização. Pode ocorrer em todos os tipos de *softgoal*:

- **NFR**: Fragmenta objetivos amplos em partes menores, reduzindo ambiguidades.
- **Operacionalização**: Refina uma solução geral em alternativas específicas.
- **Afirmação**: Serve para afirmar ou refutar justificativas de projeto.
- **Priorização**: Permite atribuir diferentes níveis de prioridade entre *softgoals* do mesmo tipo.

A figura 2 ilustra essas diferentes formas de decomposição dentro do NFR Framework:

<p align="center"><i>Figura 2: Tipos de Decomposição das Softgoals</i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/tabela2.png" width="600">
</p>

<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

#### Contribuições

Contribuições indicam como um *softgoal* impacta outro. Podem ser:

- **AND**: Todos os derivados devem ser satisfeitos para satisfazer o *softgoal* principal.
- **OR**: A satisfação de ao menos um derivado é suficiente.
- **MAKE (++):** Contribuição totalmente positiva.
- **BREAK (--):** Contribuição totalmente negativa.
- **HELP (+):** Contribuição levemente positiva.
- **HURT (-):** Contribuição levemente negativa.
- **UNKNOWN (?)**: Contribuição desconhecida.
- **EQUALS**: Correlação direta entre os níveis de satisfação.
- **SOME**: A contribuição é conhecida, mas sua intensidade é incerta. <a id="anchor_2" href="#REF2">[2]</a>

## Procedimento de Avaliação no NFR Framework

O **procedimento de avaliação** determina o grau em que os requisitos não funcionais (softgoals) são satisfeitos por um conjunto de decisões. Dessa forma, ele verifica se cada softgoal ou interdependência do Softgoal Interdependency Graph (SIG) foi suficientemente atendido.<a id="anchor_2" href="#REF2">[2]</a>

### Tipos de rótulos usados

- ✓ **Satisfeito**: O requisito não funcional é plenamente satisfeito.
- 𝒲+ **Fracamente satisfeito**: Satisfação parcial; impacto positivo, mas menos forte que ✓.
- X **Negado**: O requisito não é satisfeito e pode até contradizer os objetivos do sistema.
- 𝒲- **Fracamente negado**: Negação parcial; impacto negativo, mas mais brando que X.
- 🗲 **Conflitante**: Há conflitos entre requisitos; coexistem aspectos positivos e negativos.
- u **Indeterminado**: Não há dados suficientes para determinar o impacto entre os requisitos.

<p align="center"><i>Figura 3: Tipos de rótulos utilizados pelos softgoals</i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/tabela3.png" width="600">
</p>

<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>


<p align="center"><b>Tabela</b> — Histórico de Contribuições</p>

| O que foi feito                                  | Autor(es)                                                                                                  | Data de Criação |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | --------------- |
| Adição das tabela modelo de RNF                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025      |
| Adição das tabela modelo Cartão de Especificação | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025      |
| Adição de tabela Segurança                       | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx)                                                         | 28/05/2025      |
| Adição de tabela Usabilidade                     | [Lucas Mendonça](https://github.com/lucasarruda9)                                                          | 28/05/2025      |
| Adição de tabela Desempenho                      | [Artur Mendonça](https://github.com/ArtyMend07)                                                     | 28/05/2025      |
| Adição de tabela Responsividade                  | [Gabriel Lopes](https://github.com/BrzGab)                                                                 | 28/05/2025      |
| Adição de tabela Confiabilidade                  | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)                                                | 28/05/2025      |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

## Priorização MoSCoW

Para organizar e definir a importância relativa dos requisitos não-funcionais identificados, este projeto utiliza a técnica de priorização [**MoSCoW**](../../elicitacao/tec_priorizacao/moscow.md).

O método **MoSCoW** categoriza os requisitos em quatro grupos principais:

- **Must have (M)** → Essenciais para o sucesso do sistema. Sem eles, o projeto falha.
- **Should have (S)** → Importantes, mas não críticos. Sua ausência pode ser contornada temporariamente.
- **Could have (C)** → Desejáveis, porém opcionais. Podem ser incluídos se houver tempo e recursos.
- **Won’t have this time (W)** → Fora do escopo atual. Requisitos que foram deliberadamente deixados para versões futuras.

### Aplicação no NFR Framework

No contexto deste projeto, a priorização **MoSCoW** será usada para:

1. **Atribuir prioridades aos softgoals NFR e aos requisitos relacionados**, complementando os valores numéricos de prioridade já indicados nos cartões de especificação.
2. **Guiar decisões de implementação**, ajudando a equipe a entender quais requisitos não-funcionais são indispensáveis, quais podem ser adiados e quais são opcionais.
3. **Registrar as decisões nos Softgoal Interdependency Graphs (SIGs)**, utilizando as tags **M / S / C / W** nos nós e/ou nas legendas, para manter rastreabilidade visual das prioridades.

Essa priorização também será documentada nas tabelas de especificação, adicionando uma coluna e a anotação que indique a categoria **MoSCoW** de cada requisito.

## Metodologia

1. Definição dos temas principais: Usabilidade, Desempenho, Segurança, Acessibilidade, Confiabilidade.
2. Modelagem com o NFR Framework, representando os requisitos não funcionais como softgoals.
3. Construção dos Softgoal Interdependency Graphs (SIGs) no Draw.io para cada tema.
4. Análise de contribuições e conflitos entre softgoals (por exemplo: trade-offs entre desempenho e segurança).
5. Aplicação do procedimento de avaliação, atribuindo rótulos como satisfeito, fracamente satisfeito, negado, fracamente negado, conflitante ou indeterminado para cada softgoal.
6. Validação final com revisão bibliográfica e feedback da equipe, garantindo alinhamento com o estado da arte.


## Tabela de Requisitos Não Funcionais 

| ID    | Descrição                                                                                                                                     | Rastreabilidade                                                                                                                                  | Implementado |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ |
| RNF01 | O sistema deve ser compatível com vários dispositivos como Android e iOS.                                                                     | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD09</a>                                                                      | Sim          |
| RNF02 | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).                                                             | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD10</a>                                                                      | Sim          |
| RNF03 | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos                                                                 | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN01</a>                                                                         | Sim          |
| RNF04 | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                                                       | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a>                                                                         | Não          |
| RNF05 | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                                                               | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a>                                                                         | Sim          |
| RNF06 | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos                                             | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN05</a>                                                                         | Não          |
| RNF07 | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta                                                        | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a>                                                                         | Sim          |
| RNF08 | O layout deve ser responsivo para diferentes tamanhos de tela                                                                                 | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN07</a>, <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT22</a> | Sim          |
| RNF09 | O sistema deve ter compatibilidade com leitores de tela                                                                                       | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a>                                                                         | Sim          |
| RNF10 | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade                                                   | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN09</a>                                                                         | Não          |
| RNF11 | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos.                    | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN01</a> <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD11</a>  | Não          |
| RNF12 | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente em saúde e educação. | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN02</a>                                                                              | Sim          |
| RNF13 | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis.                     | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN03</a>                                                                              | Não          |
| RNF14 | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.                    | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a>                                                                              | Sim          |
| RNF15 | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida.                                        | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN05</a>                                                                              | Não          |
| RNF16 | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam acessíveis.               | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN06</a>                                                                              | Não          |
| RNF17 | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais.                             | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN07</a>, <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT19</a>      | Não          |
| RNF18 | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários.                                          | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>                                                                              | Não          |
| RNF19 | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.                                                     | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT15</a>                                                                           | Sim          |
| RNF20 | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.                                     | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT16</a>                                                                           | Sim          |
| RNF21 | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade.                       | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT17</a>                                                                           | Sim          |
| RNF22 | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura.                                              | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT18</a>                                                                           | Sim          |
| RNF23 | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.                                               | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT20</a>                                                                           | Não          |
| RNF24 | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis.                                          | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT21</a>                                                                           | Sim          |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

## Taxonomia

A taxonomia é um esquema de classificação que organiza termos e suas relações no contexto de uma área de conhecimento. Segundo Usman et al. (2017), **“taxonomias contribuem para amadurecer um campo de conhecimento, permitindo descrever seus elementos e evoluindo ao longo do tempo ao incorporar novos conhecimentos”**<a id="anchor_2" href="#REF2">[2]</a>.

<p align="center"><b>Tabela</b> — Taxonomia</p>

| Softgoal            | RNFs Relacionados                        |
| ------------------- | ---------------------------------------- |
| *Segurança*         | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF02</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF14</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF22</a>                      |
| *Usabilidade*       | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF03</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF10</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF11</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF16</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF21</a>        |
| *Acessibilidade*    | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF04</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF09</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF17</a>                     |
| *Desempenho*        | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF06</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF07</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF13</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF15</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF20</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF24</a> |
| *Confiabilidade*    | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF01</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF08</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF12</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF18</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF19</a>, <a href="/elicitacao/req_elicitados/#anchor_RF">RNF23</a> |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

A taxonomia apresentada nesta tabela organiza os Softgoals (objetivos de qualidade não-funcionais) do sistema e relaciona cada um com os Requisitos Não-Funcionais correspondentes. Essa classificação ajuda a estruturar os critérios que devem ser atendidos para garantir aspectos importantes do software, como compatibilidade, segurança, usabilidade, acessibilidade, desempenho, entre outros.

---

## Cartões de Especificação

Os cartões de especificação a seguir, Tabelas de 1 a 10, foram utilizados para definir os Requisitos Não-Funcionais a serem utilizados na confecção dos NFR Frameworks.<a id="anchor_2" href="#REF2">[2]</a>

<p align="center"><b>Tabela 1</b> — Cartão de Especificação modelo</p>

| *Item*                  | *Descrição*                                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | Um número sequencial                                                                                        |
| *Classificação*         | Classificação do RNF conforme taxonomia                                                                     |
| *Descrição*             | Declaração única do significado do requisito                                                                |
| *Justificativa*         | Justificativa sobre a criação do requisito                                                                  |
| *Origem*                | Origem do requisito (stakeholder, norma, etc.)                                                              |
| *Critério de Aceitação* | Métrica do requisito que possa ser testada e validada                                                       |
| *Dependências*          | Requisitos relacionados e estruturas dependentes                                                            |
| *Prioridade*            | Categoria de prioridade: **M** (Must have), **S** (Should have), **C** (Could have), **W** (Won’t have) |
| *Conflitos*             | Requisitos conflitantes com este                                                                            |
| *História*              | Data de criação e de modificação                                                                            |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

----------

<p align="center"><b>Tabela 2</b> — Cartão de Especificação 2</p>

| *Item*                  | *Descrição*                                                                                  |
| ----------------------- | -------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF02</a>                                    |
| *Classificação*         | Segurança                                                                                    |
| *Descrição*             | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).            |
| *Justificativa*         | Garantir a proteção legal dos dados pessoais dos usuários e evitar penalidades legais.       |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD10</a>                                        |
| *Critério de Aceitação* | O sistema deve demonstrar conformidade com os princípios e obrigações da LGPD em auditorias. |
| *Dependências*          | RNF14 (Proteção de dados), RNF22 (Autenticação segura).                                      |
| *Prioridade*            | **M** (Must have)                                                                            |
| *Conflitos*             | Pode exigir ajustes em funcionalidades para reduzir coleta ou armazenamento de dados.        |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                      |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

----

<p align="center"><b>Tabela 3</b> — Cartão de Especificação 3</p>

| *Item*                  | *Descrição*                                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF14</a>                                                   |
| *Classificação*         | Segurança                                                                                                   |
| *Descrição*             | O sistema deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade. |
| *Justificativa*         | A proteção de dados é essencial para manter a confiança dos usuários e evitar vazamentos ou ataques.        |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a>                                                           |
| *Critério de Aceitação* | Implementação de criptografia em repouso e em trânsito, políticas de acesso restrito e logs de auditoria.   |
| *Dependências*          | RNF02 (Conformidade LGPD), RNF22 (Autenticação segura), RNF15 (Performance de login).                       |
| *Prioridade*            | **M** (Must have)                                                                                           |
| *Conflitos*             | Pode impactar a performance do sistema, especialmente no processo de login e acesso a dados sensíveis.      |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                     |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

---

<p align="center"><b>Tabela 4</b> — Cartão de Especificação 4</p>

| *Item*                  | *Descrição*                                                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------------------------------ |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF22</a>                                                    |
| *Classificação*         | Segurança                                                                                                    |
| *Descrição*             | O sistema deve usar autenticação segura, preferencialmente integrada ao gov.br, para proteger o acesso.      |
| *Justificativa*         | Autenticação robusta é necessária para evitar acessos não autorizados e fraudes.                             |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT18</a>                                            |
| *Critério de Aceitação* | Implementação de autenticação integrada ao gov.br, uso de protocolos seguros (OAuth, SAML) e logs de acesso. |
| *Dependências*          | RNF14 (Proteção de dados), RNF15 (Performance de login).                                                     |
| *Prioridade*            | **M** (Must have)                                                                                            |
| *Conflitos*             | Pode aumentar a complexidade de implementação e gerar impacto na experiência do usuário (tempo de login).    |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                      |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

## NFR01: Segurança

Este SIG (Softgoal Interdependency Graph) foi elaborado com base nos requisitos não funcionais relacionados à segurança do sistema no que tange ao dados. A segurança é responsável por garantir que os dados do usuário e de todas as partes envolvidas no uso do sistema tenham uma camada de proteção contra a exposição indesejada das suas informações.

## Requisitos: 
Requisitos utilizados para desenvolver o SIG da Figura 4:

### Tabela de Requisitos Relacionados à LGPD

| **Código** | **Descrição**                                                                                                                             |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| RNF02      | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).                                                         |
| RNF14      | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.               |
| RNF22      | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura.                                          |

<p align="center"><i>Figura 4: SIG: Segurança </i></p>

<p align="center">
  <img src="https://i.ibb.co/Hf9MwG4L/image.png" width="600">
</p>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

### Propagação dos Impactos

A Tabela 1, apresentada a seguir, mostra a avaliação da propagação dos impactos representados na imagem acima.

### Tabela 1: Tabela de Impactos - Segurança

| *NFR*                        | *Impacto* | *Avaliador*           |
|-----------------------------|-----------|------------------------|
| Conformidade com a LGPD     | ✔         | [Luiza da Silva Pugas](https://github.com/Luizaxx) e [João Marcos](https://github.com/JJOAOMARCOSS)    |
| Proteção de dados           | 𝒲+       | [Luiza da Silva Pugas](https://github.com/Luizaxx) e [João Marcos](https://github.com/JJOAOMARCOSS)    |
| Autenticar de forma segura  | 𝒲+       | [Luiza da Silva Pugas](https://github.com/Luizaxx) e [João Marcos](https://github.com/JJOAOMARCOSS)     |
| Criptografar dados          | 𝒲+       | [Luiza da Silva Pugas](https://github.com/Luizaxx) e [João Marcos](https://github.com/JJOAOMARCOSS)     |
| Satisfação do usuário       | 𝒲+       | [Luiza da Silva Pugas](https://github.com/Luizaxx) e [João Marcos](https://github.com/JJOAOMARCOSS)    |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

---

**Vídeo 1** - Validação e Priorização de NFR com usuário por [Luiza da Silva Pugas](https://github.com/Luizaxx)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/xOqd3H6dOds" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/xOqd3H6dOds" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que a cidadã Nívea Cecília forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](../../assets/termo-img/Assinatura%20Nivea%20.pdf)

---

**Vídeo 2** - Validação e Priorização de NFR com usuário por [João Marcos Moraes](https://github.com/JJOAOMARCOSS)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/yuTljJG5Xr8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/yuTljJG5Xr8" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Gabriel Souza forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](../../assets/termo-img/Termo-Gabriel-Souza.pdf)

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Luiza da Silva Pugas](https://github.com/Luizaxx) | Elaborador dos NFR | 01/06/2025 | 14:30 |
| [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | Elaborador dos NFR | 01/06/2025 | 12:30 |
| Nívea Cecília | Cidadã | 01/06/2025 | 14:30 |
| Gabriel Souza | Cidadão | 01/06/2025 | 12:30 |

---

<p align="center"><b>Tabela 5</b> — Cartão de Especificação 5</p>

| *Item*                  | *Descrição*                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF03< a>                                                                                |
| *Classificação*         | Usabilidade                                                                                                           |
| *Descrição*             | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos.            |
| *Justificativa*         | Reduzir a carga visual, facilitando a identificação de funcionalidades e melhorando a experiência do usuário.
| *Origem*                | brainstorming.                                                         |
| *Critério de Aceitação* | Pelo menos 90% dos usuários, com no mínimo 10 participantes, devem conseguir localizar as funcionalidades desejadas sem ajuda externa, e num período de 20 segundos por tarefa. 
| *Dependências*          |  RNF10 (linguagem clara), RNF11 (navegação intuitiva).
| *Prioridade*            |  **M** (Must have)                                                                                                           |
| *Conflitos*             | Risco de omitir informações importantes, tornando a interface minimalista demais.
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

---



<p align="center"><b>Tabela 6</b> — Cartão de Especificação 6</p>

| *Item*                  | *Descrição*                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF11</a>                     |
| *Classificação*         | Usabilidade                                                                                                           |
| *Descrição*             | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos.
| *Justificativa*         | Facilita o uso do sistema por usuários com diferentes níveis de familiaridade tecnológica.
| *Origem*                | Análise de documentos e entrevista.                                                         |
| *Critério de Aceitação* | Uso da heurística de Nielsen "Consistência e padronização". Testes serão feitos com no mínimo 5 usuários. Se forem identificados mais que 3 desvios dessa heurística que causem confusão, o requisito não está atendido. 
| *Dependências*          |  RNF06 (navegação rápida)
| *Prioridade*            |  **M** (Must have)                                                                                                           |
| *Conflitos*             | Reduzir redirecionamentos vai fazer com que possa ter sobrecarga de informações em uma tela.
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

---

<p align="center"><b>Tabela 7</b> — Cartão de Especificação 7</p>

| *Item*                  | *Descrição*                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF16</a>                     |
| *Classificação*         | Usabilidade                                                                                                           |
| *Descrição*             | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam acessíveis.
| *Justificativa*         | Promove inclusão digital e amplia o alcance do sistema, facilitando o uso para uma parcela significativa da população
| *Origem*                | Entrevista.                                                         |
| *Critério de Aceitação* | Avaliação com grupo de usuários idosos, buscando pelo menos 80% de aprovação em testes de usabilidade focados em legibilidade, navegação e tamanho de elementos. 
| *Dependências*          |  RNF03 (interface simples e limpa)
| *Prioridade*            |  **M** (Must have)                                                                                                           |
| *Conflitos*             | Reduzir redirecionamentos vai fazer com que possa ter sobrecarga de informações em uma tela.
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

---

<p align="center"><b>Tabela 8</b> — Cartão de Especificação 8</p>

| *Item*                  | *Descrição*                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF21</a>                     |
| *Classificação*         | Usabilidade                                                                                                           |
| *Descrição*             | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade.
| *Justificativa*         | Facilita a compreensão das funcionalidades, reduzindo a curva de aprendizado e o risco de abandono por parte dos usuários.
| *Origem*                | Introspecção.                                                         |
| *Critério de Aceitação* | Em teste com usuários, pelo menos 90% devem conseguir realizar tarefas básicas (ex: cadastro, consulta, envio de dados) sem ajuda externa ou leitura de instruções externas.
| *Dependências*          |  RNF11 (navegação intuitiva).
| *Prioridade*            |  **M** (Must have)                                                                                                           |
| *Conflitos*             | Dados podem exigir terminologia mais complexa
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

---

## NFR02: Usabilidade

Este Softgoal Interdependency Graph (SIG) foi elaborado para representar visualmente os aspectos relacionados à usabilidade no sistema FGTS. Ele demonstra como certos requisitos não funcionais influenciam positivamente ou negativamente esse atributo de qualidade.

## Requisitos: 
Requisitos utilizados para desenvolver o SIG da Figura 5:

### Tabela de Requisitos Relacionados à Usabilidade

| **Código** | **Descrição**                                                                                                                                          |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| RNF03      | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos.                                                                          |
| RNF11      | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos.                             |
| RNF16      | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam acessíveis.                         |
| RNF21      | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade.                                 |


<p align="center"><i>Figura 5: SIG: Usabilidade </i></p>


<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/Usabilidade.drawio.png"600">
</p>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

### Propagação dos Impactos

A Tabela 2, apresentada a seguir, mostra a avaliação da propagação dos impactos representados na imagem acima.

### Tabela 2: Tabela de Impactos - Usabilidade

| *NFR*                        | *Impacto* | *Avaliador*           |
|-----------------------------|-----------|------------------------|
| Interface limpa     | ✔         |   [Lucas Mendonça](https://github.com/lucasarruda9)  |
| Usar linguagem acessível          | ✔       |   [Lucas Mendonça](https://github.com/lucasarruda9)  |
| Implementar design simples | ✔       |   [Lucas Mendonça](https://github.com/lucasarruda9)   |
| Acessibilidade         | ✔      |   [Lucas Mendonça](https://github.com/lucasarruda9)  |
| Navegação      |  𝒲+      |   [Lucas Mendonça](https://github.com/lucasarruda9) |
| Navegação intuitiva          | ✔       |   [Lucas Mendonça](https://github.com/lucasarruda9)  |
| Redirecionamento externos | 𝒲       |   [Lucas Mendonça](https://github.com/lucasarruda9)   |
| Interface intuitiva         | ✔       |   [Lucas Mendonça](https://github.com/lucasarruda9)  |
| Usabilidade     | ✔       |   [Lucas Mendonça](https://github.com/lucasarruda9) |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

**Vídeo 3** - Validação e Priorização de NFR com usuário por [Lucas Mendonça](https://github.com/lucasarruda9)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/wxBJ2hGhygs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtube.com/wxBJ2hGhygs" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Lucas Mendonça](https://github.com/lucasarruda9) | Elaborador dos NFR | 01/06/2025 | 18:30 |
| Gabriel Lima | Usuário | 01/06/2025 | 18:30 |

------

<p align="center"><b>Tabela 9</b> — Cartão de Especificação 9</p>

| *Item*                  | *Descrição*                                                                                                                  |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF04</a>                                                                    |
| *Classificação*         | Acessibilidade                                                                                                               |
| *Descrição*             | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual.                                     |
| *Justificativa*         | Garante que o sistema seja inclusivo para públicos com diferentes necessidades e limitações físicas.                         |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a>                                                         |
| *Critério de Aceitação* | Testes mostrando compatibilidade com recursos de acessibilidade do sistema operacional, como ajustes de tamanho e contraste. |
| *Dependências*          | RNF03 (Interface intuitiva), RNF11 (Linguagem acessível).                                                                    |
| *Prioridade*            | **M** (Must have)                                                                                                            |
| *Conflitos*             | Pode exigir ajustes adicionais no design visual e maior atenção em testes especializados.                                    |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                                      |



<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

---

<p align="center"><b>Tabela 10</b> — Cartão de Especificação 10</p>

| *Item*                  | *Descrição*                                                                                                               |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF09</a>                                                                 |
| *Classificação*         | Acessibilidade                                                                                                            |
| *Descrição*             | O sistema deve ter compatibilidade com leitores de tela para atender usuários com deficiência visual.                     |
| *Justificativa*         | Permite o uso do sistema por usuários cegos ou com baixa visão, garantindo acesso à informação.                           |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a>                                                      |
| *Critério de Aceitação* | Testes com leitores de tela como TalkBack (Android) e VoiceOver (iOS), garantindo leitura correta dos elementos e fluxos. |
| *Dependências*          | RNF03 (Interface intuitiva), RNF11 (Linguagem acessível).                                                                 |
| *Prioridade*            | **M** (Must have)                                                                                                         |
| *Conflitos*             | Pode limitar certas escolhas visuais, exigindo atenção na marcação semântica e descrição de imagens.                      |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                                   |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

---

<p align="center"><b>Tabela 11</b> — Cartão de Especificação 11</p>

| *Item*                  | *Descrição*                                                                                                                |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF17</a>                                                                  |
| *Classificação*         | Acessibilidade                                                                                                             |
| *Descrição*             | O aplicativo deve fornecer suporte para daltônicos e outros tipos de deficiência visual.                                   |
| *Justificativa*         | Assegura que os elementos visuais sejam acessíveis a diferentes tipos de deficiência, ampliando o público-alvo do sistema. |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN07</a>, <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT19</a>                                                       |
| *Critério de Aceitação* | Testes de contraste, inclusão de ícones não baseados apenas em cor, e modos de exibição adaptados.                         |
| *Dependências*          | RNF03 (Interface intuitiva), RNF11 (Linguagem acessível).                                                                  |
| *Prioridade*            | **M** (Must have)                                                                                                          |
| *Conflitos*             | Pode exigir ajustes detalhados no design de cores, contrastes e elementos gráficos.                                        |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                                    |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

---

## NFR03: Acessibilidade

Este SIG (Softgoal Interdependency Graph) foi elaborado a partir de requisitos não funcionais relacionados à acessibilidade do sistema. Esses requisitos garantem que o aplicativo seja inclusivo e acessível a todos os usuários, incluindo aqueles com deficiências visuais, auditivas ou motoras.

## Requisitos:

Requisitos utilizados para desenvolver o SIG da Figura 5:

### Tabela de Requisitos Relacionados à Acessibilidade

| *Código* | *Descrição*                                                                                         |
| ---------- | ----------------------------------------------------------------------------------------------------- |
| RNF04      | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual.              |
| RNF09      | O sistema deve ter compatibilidade com leitores de tela para atender usuários com deficiência visual. |
| RNF17      | O aplicativo deve fornecer suporte para daltônicos e outros tipos de deficiência visual.              |

---

<p align="center"><i>Figura 5: SIG: Acessibilidade </i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/modelagem/nfr/nfr_acessibilidade.png" width="600">
</p>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

## Propagação dos Impactos

A Tabela 3 apresenta a análise dos impactos dos requisitos de acessibilidade.

### Tabela 3: Tabela de Impactos - Acessibilidade

| NFR                                                          | Impacto | Avaliador                                                                                                              |
| -------------------------------------------------------------- | --------- | ------------------------------------------------------------------------------------------------------------------------ |
| Acessibilidade                                                 | ✔         | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Acessibilidade para idosos e deficientes visuais               | 𝒲+      | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Compatibilidade com leitores de tela                           | 𝒲+     | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Compatibilidade com TalkBack e VoiceOver                       | 𝒲+      | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Ajuste de fonte e contraste automático                         | 𝒲+     | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Paleta de cores compatível com daltonismo                      |𝒲+      | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Ícones com formatos diferenciados                              | 𝒲+     | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Entrevistas com usuários que relataram falta de acessibilidade | 𝒲+      | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |
| Inclusão de usuários PCD aumenta alcance do app                |𝒲+     | [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)  |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

**Vídeo 4** - Validação e Priorização de NFR com usuário por [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/Izlb7lYmxLk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/Izlb7lYmxLk" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem

Este documento confirma que o cidadão João Vitor forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1ByY5FYenlySd8Yn5wnW8HtmIhyFg-c35/view?usp=sharing)

---

**Vídeo 5** - Validação e Priorização de NFR com usuário por [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/84UQW38g9vI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/84UQW38g9vI" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem

Este documento confirma que o cidadão João Vitor forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1ByY5FYenlySd8Yn5wnW8HtmIhyFg-c35/view?usp=sharing)




---


<p align="center"><b>Tabela 12</b> — Cartão de Especificação 12</p>

| *Item*                  | *Descrição*                                                                                               |
| ----------------------- | --------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF06</a>                                                 |
| *Classificação*         | Desempenho                                                                                                |
| *Descrição*             | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos.        |
| *Justificativa*         | Garante que os usuários tenham uma experiência ágil e sem interrupções ao usar o sistema.                 |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN05</a>                                                           |
| *Critério de Aceitação* | O tempo de transição entre telas deve ser inferior a dois segundos, sem redirecionamentos desnecessários. |
| *Dependências*          | RNF08 (Responsividade), RNF01 (Compatibilidade).                                                          |
| *Prioridade*            | **S** (Should have)                                                                                       |
| *Conflitos*             | Pode exigir otimizações e adaptações específicas para diferentes dispositivos ou plataformas.             |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                   |



<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

---

<p align="center"><b>Tabela 13</b> — Cartão de Especificação 13</p>

| *Item*                  | *Descrição*                                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF07</a>                                                   |
| *Classificação*         | Desempenho                                                                                                  |
| *Descrição*             | O sistema deve carregar as informações de forma otimizada, reduzindo o tempo de resposta.                   |
| *Justificativa*         | Minimiza o tempo de espera do usuário, tornando a interação mais eficiente.                                 |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a>                                                             |
| *Critério de Aceitação* | As principais informações devem ser carregadas em até dois segundos, mesmo sob condições de rede moderadas. |
| *Dependências*          | RNF06 (Navegação fluida), RNF08 (Responsividade).                                                           |
| *Prioridade*            | **S** (Should have)                                                                                         |
| *Conflitos*             | Otimizações de carregamento podem impactar o consumo de recursos do dispositivo.                            |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

---

<p align="center"><b>Tabela 14</b> — Cartão de Especificação 14</p>

| *Item*                  | *Descrição*                                                                                                               |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF13</a>                                                                 |
| *Classificação*         | Desempenho                                                                                                                |
| *Descrição*             | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis. |
| *Justificativa*         | Garante que o sistema funcione bem mesmo em condições adversas de conexão, evitando perda de confiança do usuário.        |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN03</a>                                                                           |
| *Critério de Aceitação* | Testes de estabilidade mostrando menos de 1% de falhas em redes móveis durante sessões prolongadas.                       |
| *Dependências*          | RNF05 (Baixo hardware), RNF20 (Tempo de resposta rápido).                                                                 |
| *Prioridade*            | **S** (Should have)                                                                                                       |
| *Conflitos*             | Requer testes detalhados e ajustes específicos para diferentes condições de rede.                                         |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                                   |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

---

<p align="center"><b>Tabela 15</b> — Cartão de Especificação 15</p>

| *Item*                  | *Descrição*                                                                                                        |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------ |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF15</a>                                                          |
| *Classificação*         | Desempenho                                                                                                         |
| *Descrição*             | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida.             |
| *Justificativa*         | O login é um ponto crítico da experiência, e sua eficiência impacta diretamente a satisfação do usuário.           |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN05</a>                                                                              |
| *Critério de Aceitação* | O login deve ser concluído em menos de três segundos em 90% das tentativas, considerando diferentes tipos de rede. |
| *Dependências*          | RNF22 (Autenticação segura), RNF14 (Proteção de dados).                                                            |
| *Prioridade*            | **S** (Should have)                                                                                                |
| *Conflitos*             | Melhorar performance pode limitar certos mecanismos de segurança mais robustos.                                    |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                            |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

---

<p align="center"><b>Tabela 16</b> — Cartão de Especificação 16</p>

| *Item*                  | *Descrição*                                                                                               |
| ----------------------- | --------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF20</a>                                                 |
| *Classificação*         | Desempenho                                                                                                |
| *Descrição*             | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência. |
| *Justificativa*         | A resposta rápida mantém o usuário engajado e reduz a sensação de lentidão no uso do aplicativo.          |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT16</a>                                                              |
| *Critério de Aceitação* | Medição de tempo de resposta com limite de dois segundos para as funções críticas.                        |
| *Dependências*          | RNF07 (Carregamento otimizado), RNF06 (Navegação fluida).                                                 |
| *Prioridade*            | **S** (Should have)                                                                                       |
| *Conflitos*             | Pode demandar otimizações agressivas, impactando legibilidade ou modularidade do código.                  |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                   |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

---

<p align="center"><b>Tabela 17</b> — Cartão de Especificação 17</p>

| *Item*                  | *Descrição*                                                                                           |
| ----------------------- | ----------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF24</a>                                             |
| *Classificação*         | Desempenho                                                                                            |
| *Descrição*             | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido, mesmo em conexões móveis. |
| *Justificativa*         | Reduzir tempo de upload e evitar frustração, especialmente em regiões com internet limitada.          |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT21</a>                                                          |
| *Critério de Aceitação* | Upload concluído em menos de cinco segundos para imagens até 5MB em redes móveis padrão.              |
| *Dependências*          | RNF13 (Estabilidade), RNF05 (Baixo hardware).                                                         |
| *Prioridade*            | **S** (Should have)                                                                                   |
| *Conflitos*             | Compressão agressiva pode impactar a qualidade visual das imagens.                                    |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                               |


<p align="center"><i>Figura 6: SIG: Desempenho </i></p>


<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfr_desempenho.png"600">
</p>

### Propagação dos Impactos

A Tabela 4, apresentada a seguir, mostra a avaliação da propagação dos impactos representados na imagem acima.

### Tabela 4: Tabela de Impactos - Desempenho

| *NFR*                        | *Impacto* | *Avaliador*           |
|-----------------------------|-----------|------------------------|
| Navegação flúida     | ✔         |   [Artur Mendonça](https://github.com/ArtyMend07)  |
| Carregar informações otimizadas          | ✔       |   [Artur Mendonça](https://github.com/ArtyMend07)  |
| Estabilidade em redes móveis | ✔       |   [Artur Mendonça](https://github.com/ArtyMend07)   |
| Autenticação rápida         | ✔      |   [Artur Mendonça](https://github.com/ArtyMend07)  |
| Funcionalidades principais otimizadas      |  ✔       |   [Artur Mendonça](https://github.com/ArtyMend07)
| Otimização de envio de imagens          | ✔       |   [Artur Mendonça](https://github.com/ArtyMend07)  |
| Desempenho | ✔        |   [Artur Mendonça](https://github.com/ArtyMend07)   |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

**Vídeo 6** - Validação e Priorização de NFR com usuário por [Artur Mendonça](https://github.com/ArtyMend07)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/ry4nA8fRX_4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/ry4nA8fRX_4" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Artur Mendonça](https://github.com/ArtyMend07) | Elaborador dos NFR | 01/06/2025 | 19:30 |
| Vitor Guilherme | Usuário | 01/06/2025 | 19:30 |

## Termo de consentimento de imagem 
Este documento confirma que a(o) cidadão **Vitor Guilherme** forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1qYeorZ4h1cOOnnTkN-RvqZnSo8YIGk71/view?usp=sharing)

---

<p align="center"><b>Tabela 18</b> — Cartão de Especificação 18</p>

| *Item*                  | *Descrição*                                                                                                         |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF01</a>                                                           |
| *Classificação*         | Confiabilidade                                                                                                      |
| *Descrição*             | O sistema deve ser compatível com vários dispositivos, como Android e iOS.                                          |
| *Justificativa*         | Garante que o sistema funcione corretamente em diferentes ambientes, aumentando seu alcance e robustez.             |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD09</a>                                                                                    |
| *Critério de Aceitação* | Funcionalidade completa testada e validada em pelo menos 95% dos dispositivos Android e iOS mais usados no mercado. |
| *Dependências*          | RNF08 (Responsividade), RNF19 (Compatibilidade com versões).                                                        |
| *Prioridade*            | **M** (Must have)                                                                                                   |
| *Conflitos*             | Pode aumentar a complexidade de testes e a necessidade de manutenção contínua.                                      |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                             |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

<p align="center"><b>Tabela 19</b> — Cartão de Especificação 19</p>

| *Item*                  | *Descrição*                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF08</a>                                                     |
| *Classificação*         | Confiabilidade                                                                                                |
| *Descrição*             | O layout deve ser responsivo para diferentes tamanhos de tela.                                                |
| *Justificativa*         | Assegura uma boa experiência em dispositivos variados, prevenindo falhas de visualização e uso.               |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN07</a>, <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT22</a>                                                                  |
| *Critério de Aceitação* | Interface validada em telas de diferentes tamanhos (smartphones, tablets, desktops) com 100% de legibilidade. |
| *Dependências*          | RNF01 (Compatibilidade), RNF19 (Versões Android/iOS).                                                         |
| *Prioridade*            | **M** (Must have)                                                                                             |
| *Conflitos*             | Pode exigir adaptações específicas por plataforma e aumentar o esforço de design.                             |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                       |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

<p align="center"><b>Tabela 20</b> — Cartão de Especificação 20</p>

| *Item*                  | *Descrição*                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF12</a>                                                     |
| *Classificação*         | Confiabilidade                                                                                                |
| *Descrição*             | O aplicativo deve garantir que as informações exibidas estejam atualizadas e reflitam fielmente a realidade.  |
| *Justificativa*         | Evita decisões erradas baseadas em dados desatualizados, essencial para áreas críticas como saúde e educação. |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN02</a>                                                                                                  |
| *Critério de Aceitação* | Os dados sensíveis devem ser atualizados automaticamente de fontes confiáveis a cada 24h.                     |
| *Dependências*          | RNF13 (Estabilidade), RNF22 (Segurança).                                                                      |
| *Prioridade*            | **M** (Must have)                                                                                             |
| *Conflitos*             | Necessidade de sincronização frequente pode impactar desempenho em conexões lentas.                           |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                       |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

<p align="center"><b>Tabela 21</b> — Cartão de Especificação 21</p>

| *Item*                  | *Descrição*                                                                                                     |
| ----------------------- | --------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF18</a>                                                       |
| *Classificação*         | Confiabilidade                                                                                                  |
| *Descrição*             | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários.            |
| *Justificativa*         | A aparência impacta a percepção de qualidade e credibilidade, essencial para aceitação do sistema.              |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>                                                                                |
| *Critério de Aceitação* | Testes de percepção com usuários mostrando pelo menos 85% de avaliação positiva quanto à confiabilidade visual. |
| *Dependências*          | RNF03 (Interface intuitiva), RNF21 (Design acessível).                                                          |
| *Prioridade*            | **M** (Must have)                                                                                               |
| *Conflitos*             | Pode aumentar custos de design e refinamento visual.                                                            |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                         |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

<p align="center"><b>Tabela 22</b> — Cartão de Especificação 22</p>

| *Item*                  | *Descrição*                                                                                       |
| ----------------------- | ------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF19</a>                                         |
| *Classificação*         | Confiabilidade                                                                                    |
| *Descrição*             | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.         |
| *Justificativa*         | Garante que o sistema esteja atualizado e funcione corretamente nos dispositivos mais usados.     |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT15</a>                                                                  |
| *Critério de Aceitação* | Testes confirmando funcionamento total nas três versões mais recentes dos sistemas Android e iOS. |
| *Dependências*          | RNF01 (Compatibilidade), RNF08 (Responsividade).                                                  |
| *Prioridade*            | **M** (Must have)                                                                                 |
| *Conflitos*             | Pode exigir atualizações frequentes e adaptações rápidas a mudanças de sistema operacional.       |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                           |



<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

---

<p align="center"><b>Tabela 23</b> — Cartão de Especificação 23</p>

| *Item*                  | *Descrição*                                                                                                       |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF23</a>                                                         |
| *Classificação*         | Confiabilidade                                                                                                    |
| *Descrição*             | O aplicativo deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.      |
| *Justificativa*         | Permite uso contínuo mesmo em condições de rede instáveis, aumentando a confiabilidade do sistema.                |
| *Origem*                | <a href="../../elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT20</a>                                                                                       |
| *Critério de Aceitação* | As principais funcionalidades devem permanecer acessíveis offline, com sincronização automática ao voltar online. |
| *Dependências*          | RNF12 (Dados atualizados), RNF13 (Estabilidade).                                                                  |
| *Prioridade*            | **M** (Must have)                                                                                                 |
| *Conflitos*             | Sincronização offline pode gerar desafios técnicos e de consistência de dados.                                    |
| *História*              | Criado em 28/05/2025 – Última modificação em 31/05/2025                                                           |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

## NFR05: Confiabilidade

Este SIG (Softgoal Interdependency Graph) foi elaborado a partir de requisitos não funcionais relacionados à confiabilidade do sistema. Esses requisitos garantem que o sistema seja robusto, estável e funcione corretamente em diferentes situações e dispositivos.

## Requisitos:
Requisitos utilizados para desenvolver o SIG da Figura 5:

### Tabela de Requisitos Relacionados à Confiabilidade

| **Código** | **Descrição**                                                                                                                             |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| RNF01      | O sistema deve ser compatível com vários dispositivos, como Android e iOS.                                                                |
| RNF08      | O layout deve ser responsivo para diferentes tamanhos de tela.                                                                            |
| RNF12      | O aplicativo deve garantir que as informações exibidas estejam atualizadas e reflitam fielmente a realidade.                              |
| RNF18      | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários.                                      |
| RNF19      | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.                                                 |
| RNF23      | O aplicativo deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.                              |

<p align="center"><i>Figura 5: SIG: Confiabilidade</i></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/modelagem/nfr/confiabilidade.png" width="800">
</p>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

### Análise do SIG

O diagrama de Confiabilidade foi estruturado utilizando decomposição **AND**, indicando que todos os sub-softgoals devem ser satisfeitos para alcançar o objetivo principal de confiabilidade do sistema.

#### Softgoals identificados:
1. **Compatibilidade de Plataforma** (RNF01)
2. **Responsividade** (RNF08) 
3. **Dados Atualizados** (RNF12)
4. **Aparência Profissional** (RNF18)
5. **Compatibilidade de Versões** (RNF19)
6. **Funcionamento Offline** (RNF23)

#### Operacionalizações:
- **Para Compatibilidade de Plataforma**: "Testes em 95% dos dispositivos Android/iOS" [MAKE (++)]
- **Para Compatibilidade de Versões**: "Suporte às 3 versões mais recentes" [MAKE (++)]
- **Para Responsividade**: "Validação em múltiplos tamanhos de tela" [MAKE (++)] e "100% legibilidade garantida" [MAKE (++)]
- **Para Aparência Profissional**: "85% aprovação em testes de percepção" [MAKE (++)]
- **Para Dados Atualizados**: "Sincronização automática a cada 24h" [MAKE (++)]
- **Para Funcionamento Offline**: "Cache local de dados" [MAKE (++)]

#### Contribuições entre softgoals:
- **Compatibilidade de Versões** → **Compatibilidade de Plataforma**: MAKE (++)
- **Responsividade** → **Compatibilidade de Plataforma**: HELP (+)
- **Aparência Profissional** → **Responsividade**: HELP (+)
- **Funcionamento Offline** → **Dados Atualizados**: HURT (-)

### Propagação dos Impactos

A Tabela 5, apresentada a seguir, mostra a avaliação da propagação dos impactos no SIG de Confiabilidade.

<p align="center"><b>Tabela 5</b> — Tabela de Impactos - Confiabilidade</p>

| **NFR**                          | **Impacto** | **Avaliador**                                    |
|----------------------------------|-------------|--------------------------------------------------|
| Confiabilidade                   | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Compatibilidade de Plataforma    | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Compatibilidade de Versões       | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Responsividade                   | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Aparência Profissional           | 𝒲+          | [Gabriel Lopes](https://github.com/BrzGab)       |
| Dados Atualizados                | 𝒲+          | [Gabriel Lopes](https://github.com/BrzGab)       |
| Funcionamento Offline            | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Testes em 95% dos dispositivos   | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Suporte 3 versões recentes       | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| Validação múltiplos tamanhos     | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| 100% legibilidade garantida      | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |
| 85% aprovação em testes          | 𝒲+          | [Gabriel Lopes](https://github.com/BrzGab)       |
| Sincronização a cada 24h         | 𝒲+          | [Gabriel Lopes](https://github.com/BrzGab)       |
| Cache local de dados             | ✓           | [Gabriel Lopes](https://github.com/BrzGab)       |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

### Análise dos Resultados

A análise da propagação mostra que:
- Os requisitos de **compatibilidade** e **responsividade** foram plenamente satisfeitos (✓)
- **Aparência Profissional** e **Dados Atualizados** foram fracamente satisfeitos (𝒲+), indicando necessidade de melhorias
- Os requisitos de **funcionamento offline** e **compatibilidade de versões** foram plenamente satisfeitos (✓)
- As operacionalizações relacionadas a testes e validações técnicas obtiveram satisfação plena

### Priorização MoSCoW

Aplicando a técnica MoSCoW aos requisitos de confiabilidade:

| **Requisito** | **Prioridade** | **Justificativa**                                                                                           |
|---------------|----------------|-------------------------------------------------------------------------------------------------------------|
| RNF01         | **M** (Must)   | Compatibilidade multi-plataforma é essencial para alcançar todos os usuários                               |
| RNF08         | **M** (Must)   | Responsividade é crítica para experiência do usuário em diferentes dispositivos                            |
| RNF12         | **M** (Must)   | Dados atualizados são fundamentais para a credibilidade do sistema                                         |
| RNF18         | **M** (Must)   | Aparência profissional impacta diretamente na confiança dos usuários                                       |
| RNF19         | **M** (Must)   | Compatibilidade com versões recentes garante funcionamento nos dispositivos atuais                         |
| RNF23         | **M** (Must)   | Funcionamento offline é essencial para áreas com conectividade limitada                                    |

Todos os requisitos de confiabilidade foram classificados como **Must have**, refletindo sua importância crítica para o sucesso do sistema.

### Validação com Usuário

**Vídeo 7** - Validação e Priorização de NFR de Confiabilidade com usuário por [Gabriel Lopes](https://github.com/BrzGab)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/2zSk5e3hW_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=2zSk5e3hW_k" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Gabriel Lopes](https://github.com/BrzGab) | Elaborador dos NFR | 01/06/2025 | 19:30 |
| Daniel Rodrigues Nascimento | Cidadão | 01/06/2025 | 19:30 |

## Termo de consentimento de imagem 
Este documento confirma que a(o) cidadão **Daniel Rodrigues Nascimento** forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1EB1p_smwvLfqsPcUb_7nWpKIXuzLOx02/view)


---

## Diagrama compilado

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfr_compilado.jpeg" >
</div>



## Bibliografia

> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf>. Acesso em: 22/05/2025

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfrchung.png" >
</div>

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfrchung2.png" >
</div>
 
> <a id="REF2" href="#anchor_2">2.</a>SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2025.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfrreinaldo2.png" >
</div>

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfrreinaldo.jpeg" >
</div>

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/nfr/docs/assets/nfr/nfrcartaodeespecifica%C3%A7%C3%A3o.png" >
</div>


## Histórico de Versões

| Versão | Descrição                            | Autor(es)                                                                                         | Data       | Revisor(es)                                                                                                 | Data de Revisão |
| ------ | ------------------------------------ | ------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------- | --------------- |
| 1.0    | Criação da página e introdução | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 23/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 23/05/2025      |
| 1.1    | Adição das tabela modelo de RNF | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.2    | Adição das tabela modelo Cartão de Especificação | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.3    | Adição de tabela Compatibilidade | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.4    | Adição de tabela Segurança | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.5    | Adição dos cartões de especificação 5, 6, 7 e 8 sobre Usabilidade | [Lucas Mendonça](https://github.com/lucasarruda9) | 28/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.6    | Adição de tabela Acessibilidade | [Ana Victória Guedes da Costa](https://github.com/navicg) | 28/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 03/06/2025      |
| 1.7    | Adição de tabela Desempenho | [Artur Mendonça](https://github.com/ArtyMend07) | 28/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.8    | Adição de tabela Responsividade | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Artur Mendonça](https://github.com/ArtyMend07) | 03/06/2025      |
| 1.9    | Adição de tabela Confiabilidade | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | 28/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.10    | Adição de tabela Autonomia/Offline | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.11    | Adição de tabela Aparência | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.12    | Arrumando as tabelas diminuindo com base na taxonomia | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 31/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.13    | Adicção do video com o usuario | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 01/06/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.14    | Adicção do video com o usuario | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 01/06/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.15   | Adicionando draw.io NFR                               | [Karoline Luz da Conceição](https://github.com/KarolineLuz) e [Ana Victória Guedes da Costa](https://github.com/navicg) | 01/06/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)     | 01/06/2025      |
| 1.16   | Adicionando diagrama NFR                               | [Gabriel Lopes](https://github.com/BrzGab) | 01/06/2025 | [Artur Mendonça](https://github.com/ArtyMend07)     | 01/06/2025      |
| 1.17   | Adicionando Entrevista NFR                               |[Karoline Luz da Conceição](https://github.com/KarolineLuz) e [Ana Victória Guedes da Costa](https://github.com/navicg) | 01/06/2025 |  [João Marcos Moraes](https://github.com/JJOAOMARCOSS)     | 01/06/2025      |
| 1.18   | Adicionando validação NFR                               | [Gabriel Lopes](https://github.com/BrzGab) | 01/06/2025 | [Artur Mendonça](https://github.com/ArtyMend07)     | 01/06/2025      |
| 1.19    | Adição do video, diagrama e validação do diagrama| [Lucas Mendonça](https://github.com/lucasarruda9) | 01/06/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.20   | Adicionando entrevista, imagem, termo de consentimento, e validação do NFR| [Artur Mendonça](https://github.com/ArtyMend07) | 01/06/2025 | [Gabriel Lopes](https://github.com/BrzGab)     | 01/06/2025      |
| 2.0| Adicionando correções e aba de entrevista presencial| [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)| 16/06/2025 |  [João Marcos Moraes](https://github.com/JJOAOMARCOSS)     | 22/06/2025      |
| 2.1| Adicionando vídeo de entrevista presencial| [Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz)| 18/06/2025 |  [João Marcos Moraes](https://github.com/JJOAOMARCOSS)     | 22/06/2025      |