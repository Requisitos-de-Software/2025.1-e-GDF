# NFR Framework

## Introdução

O **NFR Framework** é uma abordagem para representar e analisar [Requisitos Não-Funcionais](../../elicitacao/req_elicitados.md), oferecendo uma estrutura formal para armazenar tanto o desenho quanto o racional por trás do processo de design de requisitos. Seu objetivo é auxiliar desenvolvedores na implementação de soluções personalizadas, considerando:

- Características do domínio e do sistema em questão;
- Requisitos funcionais e não-funcionais;
- Prioridades e carga de trabalho.

Esses fatores determinam a escolha das alternativas de desenvolvimento mais adequadas para cada sistema. Para isso, o framework utiliza grafos chamados **Softgoal Interdependency Graphs (SIGs)**, nos quais os *softgoals* representam objetivos abstratos de satisfação imprecisa.<a id="anchor_1" href="#REF1">[1]</a>

## Softgoal Interdependency Graph (SIG)

O **SIG** é um grafo que registra as decisões da equipe de desenvolvimento sobre *softgoals* e explicita suas interdependências de forma gráfica e concisa. Cada nó do grafo é um *softgoal* e as arestas modelam relações de decomposição ou de contribuição entre eles.<a id="anchor_1" href="#REF1">[1]</a>

### Tipos de Softgoal

1. **Softgoals NFR**
   Representam diretamente os Requisitos Não-Funcionais, organizados hierarquicamente e em catálogos.

2. **Softgoals de Operacionalização**
   Soluções concretas (operações, processos, estruturas de dados, restrições) para satisfazer *softgoals* NFR ou outros de operacionalização.

3. **Softgoals de Afirmação**
   Registros em linguagem natural que refletem fatores do domínio (prioridades, carga de trabalho) e justificativas de projeto.

### Interdependências

As interdependências expressam como *softgoals* se relacionam:

- **Decomposições** subdividem um *softgoal* em vários:
  - NFR: refina objetivos gerais em partes menores para reduzir ambiguidade e facilitar priorização.
  - Operacionalização: detalha soluções gerais em ações específicas.
  - Afirmação (claims): apoia ou nega justificativas de design.
  - Priorização: cria refinamentos com nível de prioridade associado. <a id="anchor_2" href="#REF2">[2]</a>

- **Contribuições** indicam impacto de um *softgoal* derivado sobre outro:
  - AND, OR
  - MAKE (++), BREAK (--)
  - HELP (+), HURT (-)
  - UNKNOWN (?), EQUALS, SOME  <a id="anchor_2" href="#REF2">[2]</a>

### Propagação de Impactos

Modela como a satisfação ou mudança de um *softgoal* afeta outros requisitos:

- ✓ (satisfeito), 𝒲+ (fracamente satisfeito)
- X (negado), 𝒲- (fracamente negado)
- 🗲 (conflitante), u (indeterminado)  <a id="anchor_2" href="#REF2">[2]</a>

## Metodologia

1. Definição dos temas (e.g., Confiabilidade, Desempenho, Suportabilidade, Usabilidade).
2. Introspecção e levantamento de Requisitos Não-Funcionais (Tabela de Especificação).
3. Construção dos SIGs no Draw.io para cada tema.
4. Validação com revisão bibliográfica e feedback de equipe.

## Diagramas e Análises



# Bibliografia

> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf>. Acesso em: 22/05/2025

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.
> <a id="REF2" href="#anchor_2">2.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2025.


## Histórico de Versões

| Versão | Descrição                            | Autor(es)                                                                                         | Data       | Revisor(es)                                                                                                 | Data de Revisão |
| ------ | ------------------------------------ | ------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------- | --------------- |
| 1.0    | Criação da página e introdução | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 23/05/2025 | [Luiza da Silva Pugas](https://github.com/Luizaxx) | 23/05/2025      |