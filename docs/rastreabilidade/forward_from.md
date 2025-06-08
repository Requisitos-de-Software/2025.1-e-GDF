# Forward-From

## Introdução

O conceito de *forward-from* está relacionado à rastreabilidade para frente (*forward traceability*), que permite a ligação dos requisitos a artefatos desenvolvidos nas fases posteriores do ciclo de vida do software. De acordo com Sayão e Leite (2005), “no primeiro tipo temos a rastreabilidade *forward-to* (para frente), que liga documentos obtidos no processo de elicitação a requisitos relevantes” <a id="anchor_1" href="#FRM1"> [1]</a> </q>, e mais adiante, os autores descrevem que “no segundo tipo temos rastreabilidade *forward-from*, que liga requisitos a artefatos de desenho e implementação”<a id="anchor_1" href="#FRM1"> [1]</a> </q>.

Essa capacidade de ligação é essencial para garantir que os requisitos definidos estejam refletidos adequadamente nos artefatos de implementação, assegurando consistência e completude entre o que foi requisitado e o que está sendo construído. Segundo os autores, essa rastreabilidade permite acompanhar a “vida” do requisito ao longo do processo de desenvolvimento, sendo o *forward-from* uma das direções em que esse acompanhamento pode ocorrer.

Essa abordagem favorece o controle de mudanças e facilita a verificação do atendimento aos requisitos ao longo do desenvolvimento. A rastreabilidade *forward-from*, portanto, é uma ferramenta valiosa para garantir a qualidade e a conformidade do produto final.


## Metodologia

Com base no meta-modelo de Toranzo, adaptado por Sayão e Leite, esta metodologia propõe um modelo de rastreabilidade voltado à organização, identificação e manutenção de elos entre os artefatos produzidos no processo de desenvolvimento de software.

## Classificação das Informações

Inicialmente, as informações a serem rastreadas são categorizadas em quatro níveis distintos:

- **Ambiental**: informações externas à organização, como normas regulatórias, fatores políticos ou tendências de mercado.
- **Organizacional**: informações relacionadas à missão, objetivos estratégicos e políticas internas da organização.
- **Gerencial**: dados utilizados na condução e gerenciamento de projetos.
- **Desenvolvimento**: artefatos diretamente relacionados ao processo de desenvolvimento, como requisitos, modelos, código, casos de teste e outros.

No contexto da disciplina, será adotado o nível de desenvolvimento, que abrange os artefatos explorados ao longo das entregas e aplicados no projeto.

## Identificação e Categorização dos Artefatos

Os artefatos envolvidos no processo de desenvolvimento devem ser previamente identificados e documentados. Exemplos incluem:

* **Casos de Uso**  
* **Cenários**
* **Histórias de Usuário**
* **Léxicos**
* **Especificação Suplementar**
* **NFR Framework**

A rastreabilidade será estabelecida entre pares de artefatos por meio de elos classificados conforme o tipo de relação.

## Tipos de Elos de Rastreabilidade

A metodologia considera os seguintes tipos de elos:

- **Satisfação**: a origem depende da realização do destino (ex.: requisito satisfeito por caso de uso).
- **Recurso**: a origem depende de um recurso fornecido pelo destino (ex.: Sprint depende do backlog do produto).
- **Responsabilidade**: relaciona atores humanos aos artefatos nos quais atuam (ex.: desenvolvedor responsável por requisito).
- **Representação**: o destino representa ou modela o conteúdo da origem (ex.: diagrama que representa requisitos).
- **Alocado**: a origem está alocada a um módulo ou subsistema.
- **Agregação**: o destino é uma composição de elementos da origem.

## Registro dos Elos

Cada elo deve conter os seguintes elementos:

<font size="3"><p style="text-align: center">Tabela X: Modelo de Cartão de Rastreabilidade (Forward-from)</p></font>

| Item               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Descrição do requisito | [Inserir descrição do requisito funcional ou não funcional]               |
| Categoria           | Desenvolvimento                                                          |
| Elementos           | [Inserir links para artefatos relacionados, como requisitos, casos de uso, cenários, léxicos, etc.]<br>Exemplo: [RFXX](#), [ISXX](#), [Cenário XX](#), [UCXX](#), [LXX](#) |
| Elos Forward-from   | [Inserir os elos de rastreabilidade com tipo e destino] <br> Exemplo: <br> Satisfação – [Destino]<br> Recurso – [Destino]<br>  Responsabilidade – [Destino] <br> Agregação – [Destino] <br>|
| Status              | Implementado / Não implementado                                           |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos(as) autores(as): ([Ana Victória](https://github.com/navicg) e [Karoline Luz](https://github.com/KarolineLuz), 2025)</p></font>

# Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação n° 20/05. Departamento de Informática, PUC-Rio, 2005.

# Histórico de Versões

| Versão | Descrição                                                                                          | Autor(es)                                             | Data       | Revisor(es)                                        | Data de revisão |
| ------ | -------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ---------- | -------------------------------------------------- | --------------- 
| 1.0    | Adicionando introdução e metologia do forward-from | [Ana Victória](https://github.com/navicg) | 08/06/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 08/06/2025  |