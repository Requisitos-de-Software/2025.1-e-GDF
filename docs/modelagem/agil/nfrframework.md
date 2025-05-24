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