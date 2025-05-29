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

### Propagação de Impactos

A propagação de impactos é o processo que analisa como a satisfação ou negação de um *softgoal* afeta outros *softgoals* conectados. Isso permite avaliar consequências de decisões e balancear trade-offs durante o design de sistemas. As possíveis marcações são:

- ✓ – *satisfeito*
- 𝒲+ – *fracamente satisfeito*
- X – *negado*
- 𝒲- – *fracamente negado*
- 🗲 – *conflitante*
- u – *indeterminado*

Ao entender como essas marcações se propagam, engenheiros de requisitos conseguem tomar decisões mais conscientes e equilibradas. <a id="anchor_2" href="#REF2">²</a>


## Metodologia

1. Definição dos temas (e.g., Confiabilidade, Desempenho, Suportabilidade, Usabilidade).
2. Introspecção e levantamento de Requisitos Não-Funcionais (Tabela de Especificação).
3. Construção dos SIGs no Draw.io para cada tema.
4. Validação com revisão bibliográfica e feedback de equipe.


## Tabela de Requisitos Não Funcionais 
| Código  | Descrição                                                                                                                         | Rastreabilidade        | Implementado |
|---------|-------------------------------------------------------------------------------------------------------------------------------------|------------------------|--------------|
| RNF01  | O sistema deve ser compatível com vários dispositivos como Android e iOS.                                                          | <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD09</a>                | Sim          |
| RNF02  | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD).                                                  | <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD10</a>                | Sim          |
| RNF03  | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos                                                      | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN01</a>                   | Sim          |
| RNF04  | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual                                            | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN02</a>                   | Não          |
| RNF05  | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware                                                    | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN04</a>                   | Sim          |
| RNF06  | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos                                 | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN05</a>                   | Não          |
| RNF07  | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta                                             | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN06</a>                   | Sim          |
| RNF08  | O layout deve ser responsivo para diferentes tamanhos de tela                                                                      | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN07</a>, <a href="../tec_elicitacao/integracao/#anchor_INTT">INT22</a> | Sim          |
| RNF09  | O sistema deve ter compatibilidade com leitores de tela                                                                            | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN08</a>                   | Sim          |
| RNF10  | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade                                        | <a href="../tec_elicitacao/brainstorming/#anchor_BRN">BRN09</a>                   | Não          |
| RNF11  | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos.         | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN01</a> <a href="../tec_elicitacao/analise_documentos/#anchor_AD">AD11</a> | Não          |
| RNF12  | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente em saúde e educação. | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN02</a>        | Sim          |
| RNF13  | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis.          | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN03</a>                        | Não          |
| RNF14  | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança.         | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN04</a>                        | Sim          |
| RNF15  | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida.                             | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN05</a>                        | Não          |
| RNF16  | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam acessíveis.    | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN06</a>                        | Não          |
| RNF17  | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais.                 | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN07</a>, <a href="../tec_elicitacao/integracao/#anchor_INTT">INT19</a> | Não          |
| RNF18  | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários.                              | <a href="../tec_elicitacao/entrevista/#anchor_EN">EN08</a>                        | Não          |
| RNF19  | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS.                                          | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT15</a>                    | Sim          |
| RNF20  | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência.                         | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT16</a>                    | Sim          |
| RNF21  | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade.           | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT17</a>                    | Sim          |
| RNF22  | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura.                                  | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT18</a>                    | Sim          |
| RNF23  | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas.                                   | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT20</a>                    | Não          |
| RNF24  | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis.                              | <a href="../tec_elicitacao/integracao/#anchor_INTT">INT21</a>                    | Sim          |


## Diagramas e Análises





## Bibliografia

> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf>. Acesso em: 22/05/2025

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.
> 
> <a id="REF2" href="#anchor_2">2.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2025.


## Histórico de Versões

| Versão | Descrição                            | Autor(es)                                                                                         | Data       | Revisor(es)                                                                                                 | Data de Revisão |
| ------ | ------------------------------------ | ------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------- | --------------- |
| 1.0    | Criação da página e introdução | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 23/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 23/05/2025      |