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
| Adição de tabela Compatibilidade                 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)                                                      | 28/05/2025      |
| Adição de tabela Segurança                       | [Luiza da Silva Pugas](https://github.com/Luizaxx)                                                         | 28/05/2025      |
| Adição de tabela Usabilidade                     | [Lucas Mendonça](https://github.com/lucasarruda9)                                                          | 28/05/2025      |
| Adição de tabela Acessibilidade                  | [Ana Victória Guedes da Costa](https://github.com/navicg)                                                  | 28/05/2025      |
| Adição de tabela Desempenho                      | [Artur Mendonça Arruda](https://github.com/ArtyMend07)                                                     | 28/05/2025      |
| Adição de tabela Responsividade                  | [Gabriel Lopes](https://github.com/BrzGab)                                                                 | 28/05/2025      |
| Adição de tabela Confiabilidade                  | [Karoline Luz da Conceição](https://github.com/KarolineLuz)                                                | 28/05/2025      |
| Adição de tabela Autonomia/Offline               | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025      |
| Adição de tabela Aparência                       | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025      |

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
| RNF01 | O sistema deve ser compatível com vários dispositivos como Android e iOS.                                                                     | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD09</a>                                                                      | Sim          |
| RNF02 | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).                                                             | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD10</a>                                                                      | Sim          |
| RNF03 | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos                                                                 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN01</a>                                                                         | Sim          |
| RNF04 | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                                                       | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a>                                                                         | Não          |
| RNF05 | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                                                               | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a>                                                                         | Sim          |
| RNF06 | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos                                             | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN05</a>                                                                         | Não          |
| RNF07 | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta                                                        | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a>                                                                         | Sim          |
| RNF08 | O layout deve ser responsivo para diferentes tamanhos de tela                                                                                 | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN07</a>, <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT22</a> | Sim          |
| RNF09 | O sistema deve ter compatibilidade com leitores de tela                                                                                       | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a>                                                                         | Sim          |
| RNF10 | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade                                                   | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BRN">BRN09</a>                                                                         | Não          |
| RNF11 | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos.                    | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN01</a> <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD11</a>  | Não          |
| RNF12 | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente em saúde e educação. | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN02</a>                                                                              | Sim          |
| RNF13 | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis.                     | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN03</a>                                                                              | Não          |
| RNF14 | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.                    | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a>                                                                              | Sim          |
| RNF15 | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida.                                        | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN05</a>                                                                              | Não          |
| RNF16 | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam acessíveis.               | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN06</a>                                                                              | Não          |
| RNF17 | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais.                             | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN07</a>, <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT19</a>      | Não          |
| RNF18 | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários.                                          | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN08</a>                                                                              | Não          |
| RNF19 | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.                                                     | <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT15</a>                                                                           | Sim          |
| RNF20 | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.                                     | <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT16</a>                                                                           | Sim          |
| RNF21 | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade.                       | <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT17</a>                                                                           | Sim          |
| RNF22 | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura.                                              | <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT18</a>                                                                           | Sim          |
| RNF23 | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.                                               | <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT20</a>                                                                           | Não          |
| RNF24 | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis.                                          | <a href="/elicitacao/tec_elicitacao/integracao/#anchor_INTT">INT21</a>                                                                           | Sim          |

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
A Figura 3 ilustra a representação visual dessa taxonomia, facilitando a compreensão das relações entre os Softgoals e seus respectivos Requisitos não funcionais.

<p align="center">
  <img src="/assets/modelagem/nfr/Taxonomia.drawio.png" width="600">
</p>
<p align="center"><i>Figura 3: Taxonomia</i></p>

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

| *Item*                  | *Descrição*                                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF02</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF14</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF22</a>                                                                                       |
| *Classificação*         | Segurança                                                                                                   |
| *Descrição*             | O sistema deve proteger os dados dos usuários, estar em conformidade com a LGPD e usar autenticação segura. |
| *Justificativa*         | É essencial garantir a privacidade, segurança e confiança do usuário na utilização do aplicativo.           |
| *Origem*                | Análise documental, entrevista com stakeholders, boas práticas de segurança digital.                        |
| *Critério de Aceitação* | Assegurar criptografia de dados, autenticação via gov.br e conformidade com a LGPD.                         |
| *Dependências*          | RNF15 (Performance de login), RNF23 (Modo offline pode impactar segurança)                                  |
| *Prioridade*            |  **M** (Must have)                                                                                                |
| *Conflitos*             | Pode limitar certas funcionalidades ou aumentar a complexidade de implementação.                            |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

---

<p align="center"><b>Tabela 3</b> — Cartão de Especificação 3</p>

| *Item*                  | *Descrição*                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF03</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF10</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF11</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF16</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF21</a>                                                                                |
| *Classificação*         | Usabilidade                                                                                                           |
| *Descrição*             | O sistema deve ser intuitivo, acessível, com linguagem clara e apropriada a diferentes perfis de usuários.            |
| *Justificativa*         | Uma boa usabilidade aumenta a adesão ao aplicativo e reduz a curva de aprendizado dos usuários.                       |
| *Origem*                | Análise documental, brainstorming e entrevistas com usuários.                                                         |
| *Critério de Aceitação* | Interface limpa e clara, compatível com leitores de tela, linguagem acessível, responsividade, e navegação intuitiva. |
| *Dependências*          | RNF08 (Responsividade), RNF17 (Acessibilidade)                                                                        |
| *Prioridade*            |  **M** (Must have)                                                                                                           |
| *Conflitos*             | Pode exigir mais tempo de design e testes com usuários reais.                                                         |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

------

<p align="center"><b>Tabela 4</b> — Cartão de Especificação 4</p>

| *Item*                  | *Descrição*                                                                                                                      |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF04</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF09</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF17</a>                                                                                                            |
| *Classificação*         | Acessibilidade                                                                                                                   |
| *Descrição*             | O sistema deve oferecer suporte a leitores de tela, acessibilidade visual e opções de uso para idosos e pessoas com deficiência. |
| *Justificativa*         | Garante que o sistema seja inclusivo, atendendo usuários com diferentes capacidades.                                             |
| *Origem*                | Brainstorming, entrevistas e boas práticas de acessibilidade digital.                                                            |
| *Critério de Aceitação* | Funcionalidades compatíveis com leitores de tela, layout adaptado e recursos para daltônicos ou baixa visão.                     |
| *Dependências*          | RNF03 (Interface intuitiva), RNF11 (Linguagem acessível)                                                                         |
| *Prioridade*            |  **M** (Must have)                                                                                                                     |
| *Conflitos*             | Pode exigir testes especializados e maior atenção no design visual e técnico.                                                    |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                                          |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg) e [Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

-----

<p align="center"><b>Tabela 5</b> — Cartão de Especificação 5</p>

| *Item*                  | *Descrição*                                                                                                                              |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF06</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF07</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF13</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF15</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF20</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF24</a>                                                                                            |
| *Classificação*         | Desempenho                                                                                                                               |
| *Descrição*             | O sistema deve garantir fluidez na navegação, carregamento rápido, estabilidade e tempo de resposta adequado, mesmo em conexões móveis.  |
| *Justificativa*         | Garante uma experiência eficiente e satisfatória para o usuário, especialmente em contextos com recursos limitados.                      |
| *Origem*                | Brainstorming, entrevistas e critérios técnicos de desempenho.                                                                           |
| *Critério de Aceitação* | O tempo de resposta das ações deve ser inferior a dois segundos; o sistema não deve travar em redes móveis ou em dispositivos limitados. |
| *Dependências*          | RNF08 (Responsividade), RNF01 (Compatibilidade)                                                                                          |
| *Prioridade*            | **S** (Should have)                                                                                                                            |
| *Conflitos*             | Pode aumentar o esforço de desenvolvimento e exigir otimizações específicas por plataforma.                                              |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                                                  |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça Arruda](https://github.com/ArtyMend07), 2025)</p></font>

---

<p align="center"><b>Tabela 6</b> — Cartão de Especificação 6</p>

| *Item*                  | *Descrição*                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | <a href="/elicitacao/req_elicitados/#anchor_RF">RNF01</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF08</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF12</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF18</a>  / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF19</a> / <a href="/elicitacao/req_elicitados/#anchor_RF">RNF23</a>                                                                                                     |
| *Classificação*         | Confiabilidade                                                                                                |
| *Descrição*             | O aplicativo deve garantir que as informações exibidas estejam atualizadas e reflitam fielmente a realidade.  |
| *Justificativa*         | Evita decisões erradas baseadas em dados desatualizados, essencial para áreas críticas como saúde e educação. |
| *Origem*                | Entrevistas                                                                                                   |
| *Critério de Aceitação* | Os dados sensíveis devem ser atualizados automaticamente de fontes confiáveis a cada 24h.                     |
| *Dependências*          | RNF13 (Estabilidade), RNF22 (Segurança)                                                                       |
| *Prioridade*            | **M** (Must have)                                                                                                  |
| *Conflitos*             | Necessidade de sincronização frequente pode impactar desempenho em conexões lentas.                           |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                       |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

-----

## Diagramas e Análises





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
| 1.5    | Adição de tabela Usabilidade | [Lucas Mendonça](https://github.com/lucasarruda9) | 28/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 03/06/2025      |
| 1.6    | Adição de tabela Acessibilidade | [Ana Victória Guedes da Costa](https://github.com/navicg) | 28/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 03/06/2025      |
| 1.7    | Adição de tabela Desempenho | [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 28/05/2025 | [Ana Victória Guedes da Costa](https://github.com/navicg) | 03/06/2025      |
| 1.8    | Adição de tabela Responsividade | [Gabriel Lopes](https://github.com/BrzGab) | 28/05/2025 | [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 03/06/2025      |
| 1.9    | Adição de tabela Confiabilidade | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | 28/05/2025 | [Gabriel Lopes](https://github.com/BrzGab) | 03/06/2025      |
| 1.10    | Adição de tabela Autonomia/Offline | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.11    | Adição de tabela Aparência | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 28/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
| 1.12    | Arruamndo as tabelas diminuindo com base na taxonomia | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 31/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) | 03/06/2025      |
