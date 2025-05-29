# NFR Framework

## Introdução

O **NFR Framework** é uma abordagem para representar e analisar [Requisitos Não-Funcionais](../../elicitacao/req_elicitados.md), oferecendo uma estrutura formal para armazenar tanto o desenho quanto o racional por trás do processo de design de requisitos. Seu objetivo é auxiliar desenvolvedores na implementação de soluções personalizadas, considerando:

- Características do domínio e do sistema em questão;
- Requisitos funcionais e não-funcionais;
- Prioridades e carga de trabalho.

Esses fatores determinam a escolha das alternativas de desenvolvimento mais adequadas para cada sistema. Para isso, o framework utiliza grafos chamados **Softgoal Interdependency Graphs (SIGs)**, nos quais os *softgoals* representam objetivos abstratos de satisfação imprecisa.<a id="anchor_1" href="#REF1">¹</a>

## Softgoal Interdependency Graph (SIG)

O **Softgoal Interdependency Graph (SIG)** é uma ferramenta gráfica utilizada pelo *NFR Framework* para representar decisões de projeto relacionadas a *softgoals* — objetivos com critérios de satisfação vagos ou imprecisos. Cada nó do grafo representa um *softgoal*, enquanto as arestas indicam relações de decomposição ou de contribuição entre eles. <a id="anchor_1" href="#REF1">¹</a>

### Tipos de Softgoal

Para compreender o funcionamento do SIG, é essencial entender os diferentes tipos de *softgoal*:

1. **Softgoals NFR**  
   Representam diretamente os Requisitos Não-Funcionais. São organizados hierarquicamente e agrupados em catálogos temáticos (como desempenho, segurança, usabilidade, etc.).

2. **Softgoals de Operacionalização**  
   Correspondem a soluções concretas (operações, processos, estruturas de dados, restrições) que visam satisfazer *softgoals* NFR ou outros de operacionalização.

3. **Softgoals de Afirmação**  
   São registros em linguagem natural que expressam justificativas de projeto ou fatores do domínio, como carga de trabalho, decisões de priorização e contexto organizacional.

### Interdependências

As interdependências no SIG definem as associações entre os *softgoals* e se dividem em dois tipos principais:

#### Decomposições

A decomposição permite subdividir *softgoals* em objetivos mais específicos, facilitando a análise e a priorização. Pode ocorrer em todos os tipos de *softgoal*:

- **NFR**: Fragmenta objetivos amplos em partes menores, reduzindo ambiguidades.
- **Operacionalização**: Refina uma solução geral em alternativas específicas.
- **Afirmação**: Serve para afirmar ou refutar justificativas de projeto.
- **Priorização**: Permite atribuir diferentes níveis de prioridade entre *softgoals* do mesmo tipo.


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
- **SOME**: A contribuição é conhecida, mas sua intensidade é incerta. <a id="anchor_2" href="#REF2">²</a>

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


## Metodologia

1. Definição dos temas (e.g., Confiabilidade, Desempenho, Suportabilidade, Usabilidade).
2. Introspecção e levantamento de Requisitos Não-Funcionais (Tabela de Especificação).
3. Construção dos SIGs no Draw.io para cada tema.
4. Validação com revisão bibliográfica e feedback de equipe.

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

| Softgoal            | RNFs Relacionados                        |
| ------------------- | ---------------------------------------- |
| *Compatibilidade*   | RNF01, RNF19                             |
| *Segurança*         | RNF02, RNF14, RNF22                      |
| *Usabilidade*       | RNF03, RNF10, RNF11, RNF16, RNF21        |
| *Acessibilidade*    | RNF04, RNF09, RNF17                      |
| *Desempenho*        | RNF06, RNF07, RNF13, RNF15, RNF20, RNF24 |
| *Responsividade*    | RNF08                                    |
| *Confiabilidade*    | RNF12                                    |
| *Autonomia/Offline* | RNF23                                    |
| *Aparência*         | RNF18                                    |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

## Cartões de Especificação

Os cartões de especificação a seguir, Tabelas de 1 a n, foram utilizados para definir os Requisitos Não-Funcionais a serem utilizados na confecção dos NFR Frameworks.<a id="anchor_3" href="#REF3">³</a>

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
| *Prioridade*            | Um número usado para decidir a importância relativa deste requisito (ex: 1 = prioridade mínima, 5 = máxima) |
| *Conflitos*             | Requisitos conflitantes com este                                                                            |
| *História*              | Data de criação e de modificação                                                                            |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

----------

<p align="center"><b>Tabela 2</b> — Cartão de Especificação 2</p>

| *Item*                  | *Descrição*                                                                                                  |
| ----------------------- | ------------------------------------------------------------------------------------------------------------ |
| *Nr Requisito*          | RNF01 / RNF19                                                                                                |
| *Classificação*         | Compatibilidade                                                                                              |
| *Descrição*             | O sistema deve ser compatível com vários dispositivos, incluindo Android e iOS, e suportar versões recentes. |
| *Justificativa*         | Garantir que o maior número possível de usuários possa utilizar o sistema independentemente do dispositivo.  |
| *Origem*                | Análise documental, boas práticas de desenvolvimento multiplataforma.                                        |
| *Critério de Aceitação* | O sistema deve executar corretamente em dispositivos com Android (10 ou superior) e iOS (13 ou superior).    |
| *Dependências*          | RNF08 (Responsividade), RNF24 (Otimização de imagens para upload móvel)                                      |
| *Prioridade*            | 5                                                                                                            |
| *Conflitos*             | Pode limitar uso de recursos específicos de cada sistema operacional.                                        |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                      |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

<p align="center"><b>Tabela 3</b> — Cartão de Especificação 3</p>

| *Item*                  | *Descrição*                                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF02 / RNF14 / RNF22                                                                                       |
| *Classificação*         | Segurança                                                                                                   |
| *Descrição*             | O sistema deve proteger os dados dos usuários, estar em conformidade com a LGPD e usar autenticação segura. |
| *Justificativa*         | É essencial garantir a privacidade, segurança e confiança do usuário na utilização do aplicativo.           |
| *Origem*                | Análise documental, entrevista com stakeholders, boas práticas de segurança digital.                        |
| *Critério de Aceitação* | Assegurar criptografia de dados, autenticação via gov.br e conformidade com a LGPD.                         |
| *Dependências*          | RNF15 (Performance de login), RNF23 (Modo offline pode impactar segurança)                                  |
| *Prioridade*            | Média (1.67)                                                                                                |
| *Conflitos*             | Pode limitar certas funcionalidades ou aumentar a complexidade de implementação.                            |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                     |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

---

<p align="center"><b>Tabela 4</b> — Cartão de Especificação 4</p>

| *Item*                  | *Descrição*                                                                                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF03 / RNF10 / RNF11 / RNF16 / RNF21                                                                                 |
| *Classificação*         | Usabilidade                                                                                                           |
| *Descrição*             | O sistema deve ser intuitivo, acessível, com linguagem clara e apropriada a diferentes perfis de usuários.            |
| *Justificativa*         | Uma boa usabilidade aumenta a adesão ao aplicativo e reduz a curva de aprendizado dos usuários.                       |
| *Origem*                | Análise documental, brainstorming e entrevistas com usuários.                                                         |
| *Critério de Aceitação* | Interface limpa e clara, compatível com leitores de tela, linguagem acessível, responsividade, e navegação intuitiva. |
| *Dependências*          | RNF08 (Responsividade), RNF17 (Acessibilidade)                                                                        |
| *Prioridade*            | Alta (2.17)                                                                                                           |
| *Conflitos*             | Pode exigir mais tempo de design e testes com usuários reais.                                                         |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                               |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

------

<p align="center"><b>Tabela 5</b> — Cartão de Especificação 5</p>

| *Item*                  | *Descrição*                                                                                                                      |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF04 / RNF09 / RNF17                                                                                                            |
| *Classificação*         | Acessibilidade                                                                                                                   |
| *Descrição*             | O sistema deve oferecer suporte a leitores de tela, acessibilidade visual e opções de uso para idosos e pessoas com deficiência. |
| *Justificativa*         | Garante que o sistema seja inclusivo, atendendo usuários com diferentes capacidades.                                             |
| *Origem*                | Brainstorming, entrevistas e boas práticas de acessibilidade digital.                                                            |
| *Critério de Aceitação* | Funcionalidades compatíveis com leitores de tela, layout adaptado e recursos para daltônicos ou baixa visão.                     |
| *Dependências*          | RNF03 (Interface intuitiva), RNF11 (Linguagem acessível)                                                                         |
| *Prioridade*            | Média (1.67)                                                                                                                     |
| *Conflitos*             | Pode exigir testes especializados e maior atenção no design visual e técnico.                                                    |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                                          |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória Guedes da Costa](https://github.com/navicg), 2025)</p></font>

-----

<p align="center"><b>Tabela 6</b> — Cartão de Especificação 6</p>

| *Item*                  | *Descrição*                                                                                                                              |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF06 / RNF07 / RNF13 / RNF15 / RNF20 / RNF24                                                                                            |
| *Classificação*         | Desempenho                                                                                                                               |
| *Descrição*             | O sistema deve garantir fluidez na navegação, carregamento rápido, estabilidade e tempo de resposta adequado, mesmo em conexões móveis.  |
| *Justificativa*         | Garante uma experiência eficiente e satisfatória para o usuário, especialmente em contextos com recursos limitados.                      |
| *Origem*                | Brainstorming, entrevistas e critérios técnicos de desempenho.                                                                           |
| *Critério de Aceitação* | O tempo de resposta das ações deve ser inferior a dois segundos; o sistema não deve travar em redes móveis ou em dispositivos limitados. |
| *Dependências*          | RNF08 (Responsividade), RNF01 (Compatibilidade)                                                                                          |
| *Prioridade*            | Média (1.50)                                                                                                                             |
| *Conflitos*             | Pode aumentar o esforço de desenvolvimento e exigir otimizações específicas por plataforma.                                              |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                                                  |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Artur Mendonça Arruda](https://github.com/ArtyMend07), 2025)</p></font>


---

<p align="center"><b>Tabela 7</b> — Cartão de Especificação 7</p>

| *Item*                  | *Descrição*                                                                                                        |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------ |
| *Nr Requisito*          | RNF08                                                                                                              |
| *Classificação*         | Responsividade                                                                                                     |
| *Descrição*             | O layout do sistema deve se adaptar corretamente a diferentes tamanhos de tela (smartphones, tablets, etc.).       |
| *Justificativa*         | Melhorar a experiência do usuário em qualquer dispositivo, sem distorções visuais ou limitações funcionais.        |
| *Origem*                | Brainstorming e Integração                                                                                         |
| *Critério de Aceitação* | A interface deve se ajustar perfeitamente a pelo menos três resoluções distintas de tela sem perda de usabilidade. |
| *Dependências*          | RNF01 (Compatibilidade), RNF21 (Usabilidade)                                                                       |
| *Prioridade*            | Média (1.33)                                                                                                       |
| *Conflitos*             | Pode requerer maior esforço de desenvolvimento para manter uniformidade visual entre plataformas.                  |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                            |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab), 2025)</p></font>

----

<p align="center"><b>Tabela 8</b> — Cartão de Especificação 8</p>

| *Item*                  | *Descrição*                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF12                                                                                                         |
| *Classificação*         | Confiabilidade                                                                                                |
| *Descrição*             | O aplicativo deve garantir que as informações exibidas estejam atualizadas e reflitam fielmente a realidade.  |
| *Justificativa*         | Evita decisões erradas baseadas em dados desatualizados, essencial para áreas críticas como saúde e educação. |
| *Origem*                | Entrevistas                                                                                                   |
| *Critério de Aceitação* | Os dados sensíveis devem ser atualizados automaticamente de fontes confiáveis a cada 24h.                     |
| *Dependências*          | RNF13 (Estabilidade), RNF22 (Segurança)                                                                       |
| *Prioridade*            | Média (1.67)                                                                                                  |
| *Conflitos*             | Necessidade de sincronização frequente pode impactar desempenho em conexões lentas.                           |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                       |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Karoline Luz da Conceição](https://github.com/KarolineLuz), 2025)</p></font>

-----

<p align="center"><b>Tabela 9</b> — Cartão de Especificação 9</p>

| *Item*                  | *Descrição*                                                                                                |
| ----------------------- | ---------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF23                                                                                                      |
| *Classificação*         | Autonomia / Modo Offline                                                                                   |
| *Descrição*             | O aplicativo deve funcionar parcialmente em modo offline, permitindo a consulta de registros já acessados. |
| *Justificativa*         | Permitir o uso em locais com conectividade instável, ampliando o alcance e utilidade do sistema.           |
| *Origem*                | Integração                                                                                                 |
| *Critério de Aceitação* | O usuário deve conseguir acessar os dados anteriormente consultados sem conexão com a internet.            |
| *Dependências*          | RNF24 (Desempenho de upload), RNF12 (Confiabilidade)                                                       |
| *Prioridade*            | Baixa (1.00)                                                                                               |
| *Conflitos*             | Pode exigir armazenamento local, aumentando o tamanho da instalação ou uso de memória.                     |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                    |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

-----

<p align="center"><b>Tabela 10</b> — Cartão de Especificação 10</p>

| *Item*                  | *Descrição*                                                                                                         |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------- |
| *Nr Requisito*          | RNF18                                                                                                               |
| *Classificação*         | Aparência                                                                                                           |
| *Descrição*             | O aplicativo deve ter uma aparência profissional e confiável para transmitir credibilidade ao usuário.              |
| *Justificativa*         | Aparência visual impacta a confiança e a percepção de segurança do usuário, especialmente em apps públicos.         |
| *Origem*                | Entrevistas                                                                                                         |
| *Critério de Aceitação* | A interface deve seguir os guias de estilo do governo e plataformas Android/iOS, com identidade visual padronizada. |
| *Dependências*          | RNF03 (Interface intuitiva), RNF11 (Linguagem clara)                                                                |
| *Prioridade*            | Alta (2.00)                                                                                                         |
| *Conflitos*             | Pode aumentar o tempo de design e exigência de revisão por múltiplas entidades governamentais.                      |
| *História*              | Criado em 28/05/2025 – Última modificação em 28/05/2025                                                             |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ( [João Marcos](https://github.com/JJOAOMARCOSS) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

----------
## Diagramas e Análises





## Bibliografia

> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf>. Acesso em: 22/05/2025

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.
> 
> <a id="REF2" href="#anchor_2">2.</a>SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2025.
>
> <a id="REF3" href="#anchor_3">3.</a>PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf. Acesso em: 28/05/2025




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