# Especificação Suplementar

## Introdução

<q>Especificação Suplementar pode ser definida como um documento em linguagem natural no qual são descritos os requisitos num sistema<a id="anchor_1" href="#FRM1"> [1]</a> .</q> Ela é complementar aos [casos de uso](../modelagem/casos_de_uso.md), pois ela captura os requisitos do sistema que não foram elicitados no método anterior. Entre os requisitos capturados estão incluídos: Requisitos legais e de regulamentação, padrões de aplicativos, atributos de qualidade, requisitos de utilidade, confiabilidade, desempenho, suportabilidade e outros requisitos como sistemas e ambientes operacionais, requisitos de compatibilidade e restrições de design. A metodologia mais utilizada para a produção de uma especificação suplementar é a FURPS+.

- funcionalidade
- usabilidade
- confiabilidade
- desempenho
- suportabilidade

## Metodologia

Consoante ao tópico anterior, o modelo utilizado para este artefato é o FURPS+, metodologia a qual define reqisitos de um sistema dnetro de um dos cinco pilares citados anteriormente.

- F - Functionality: são os aspectos funcionais do sistema, os quais estão explicitados nos [casos de uso](../modelagem/casos_de_uso.md).
- U - Usability: o quão fácil é para o usuário realizar suas demandas via o software.
- R - Reliability: o quão confiável foi desenhado o software.
- P - Performance: como é o desempenho do software.
- S - Supportability: requisitos que agrupam caracteristicas como: manutenibilidade, adaptabilidade, internacionalização, portabilidade e outros aspectos relevantes.
- +: símbolo que emgloba outros requisitos não funcionais, os quais não se encaixam nos pilares listados, como: design, implementação, interface, físico.

### Funcionalidade

Os requisitos funcionais foram elicitados na seção de elicitação e a [tabela 1](../elicitacao/req_elicitados.md) da página de [requisitos elicitados](../elicitacao/req_elicitados.md) demonstra todos os requisitos priorizados.

### Usabilidade

Esse tópico diz respeito aos requisitos relacionados a facilidade do usuário de utilizar a aplicação.

Para essa categoria os requisitos identificados estão representados na tabela 1 a seguir.

| Requisito | Texto original |
|-----------|----------------|
| U01 | O sistema deve ter uma interface intuitiva. |
| U02 | O sistema deve possuir uma interface simples, limpa e com ícones ilustrativos. |
| U03 | O aplicativo deve permitir acessibilidade para pessoas idosas ou com deficiência visual. |
| U04 | O layout deve ser responsivo para diferentes tamanhos de tela. |
| U05 | O sistema deve ter compatibilidade com leitores de tela. |
| U06 | O app deve conter linguagem clara e acessível, adequada a diferentes níveis de escolaridade. |
| U07 | O aplicativo deve ser mais autoexplicativo, com uma navegação intuitiva e menos dependência de redirecionamentos externos. |
| U08 | O aplicativo deve considerar a usabilidade para usuários idosos, garantindo que o design e as funcionalidades sejam facilmente compreensíveis e acessíveis. |
| U09 | O aplicativo deve fornecer suporte para acessibilidade, incluindo recursos para daltônicos e deficientes visuais. |
| U10 | O aplicativo deve ter uma aparência profissional e confiável para transmitir segurança aos usuários. |
| U11 | A interface deve ser simples, objetiva e utilizar linguagem acessível a usuários com diferentes níveis de escolaridade. |

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Ana Victória](https://github.com/navicg) e [Artur Mendonça](https://github.com/ArtyMend07), 2025)</p></font>

### Confiabilidade

Diz respeito ao quão confiável é o sistema, ou seja, qual é a frequência de falhas, possibilidade de recuperação e prevenção e tempo entre as falhas.

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

| Requisito | Texto original |
|-----------|----------------|
| R01 | O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD). |
| R02 | O aplicativo deve garantir que as informações exibidas sejam atualizadas e reflitam fielmente a realidade, especialmente nas áreas de saúde e educação. |
| R03 | O aplicativo deve apresentar estabilidade, evitando travamentos ou falhas de carregamento, especialmente em redes móveis. |
| R04 | O aplicativo deve garantir proteção de dados pessoais, reforçando a confiança do usuário quanto à privacidade e segurança. |
| R05 | O sistema deve proteger as informações pessoais com criptografia de dados e autenticação segura. |

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/karol), 2025)</p></font>


**Vídeo 1** - Validação com usuário por [Karoline Luz da Conceição](https://github.com/KarolineLuz)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/k--cQShnJVY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/k--cQShnJVY" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que a cidadã Júnia Luz de Sousa forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1tAtNRMAKPoStT9ZyOU-DdT1I9mJgC5qK/view?usp=sharing)

| Entrevistador(es) |Cidadão|Data prevista| Data Realizada  |Horário Previsto|Horário Realizado|Local|Duração|
| ---------------------------------------|------------ |------------------------ | ------ |-------|----------|-------|-------|
|[Karoline Luz](https://github.com/KarolineLuz)|**Júnia L.S** |19/06/2025| 19/06/2025| 17:30  | 17:45|   Presencial |  02:05 min |


<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Karoline Luz](https://github.com/karol), 2025)</p></font>

### Desempenho

Diz respeito às condições que os requisitos devem operar. A velocidade, limites superiores e inferiores, tempo de resposta, restrições de interface e de funções, etc.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

| Requisito | Texto original |
|-----------|----------------|
| P01 | A navegação deve ser rápida e fluida entre telas, sem necessidade de redirecionamentos excessivos. |
| P02 | O sistema deve carregar as informações de forma otimizada, reduzindo tempo de resposta. |
| P03 | O aplicativo deve melhorar a performance do processo de login, permitindo uma experiência mais fluida. |
| P04 | As funcionalidades principais devem responder em, no máximo, dois segundos para garantir boa experiência. |
| P05 | As imagens capturadas pelo usuário devem ser otimizadas para upload rápido mesmo em conexões móveis. |

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS) e [Lucas Mendonça](https://github.com/lucasarruda9), 2025)</p></font>

### Suportabilidade

Envolve os requisitos relacionados ao suporte e manutenção do sistema. Isso inclui requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado, documentação adequada, facilidade de teste e diagnóstico de problemas.

Para essa categoria os requisitos identificados estão representados na tabela 4 a seguir.

| Requisito | Texto original |
|-----------|----------------|
| S01 | O sistema deve ser compatível com vários dispositivos como Android e iOS. |
| S02 | O sistema deve funcionar mesmo em dispositivos com baixa capacidade de hardware. |
| S03 | O aplicativo deve ser compatível com as versões mais recentes dos sistemas Android e iOS. |
| S04 | Deve funcionar em modo offline para consulta de registros ou informações previamente acessadas. |

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

### Requisitos de Licenciamento

O sistema deve restringir o uso através de termos de uso.

### Observações Legais, de Copyright e Outras

O sistema está sujeito à lei dos direitos autorais, portanto, para a utilização de outras marcas será necessário uma autorização prévia dos envolvidos. Deve-se atentar também para a legislação de proteção de dados (a LGPD) e as de serviços financeiros.

### Padrões Aplicáveis

O sistema deve seguir os padrões definidos pelas normas: WCAG, ISO 9241-11, ISO/TC-211, ISO 9000, ISO 9001-3, ISO 12207, ISO 12202 e pelos guias de estilo dos sistemas Android e iOS.

### Requisitos Físicos

O aplicativo é construído nas seguintes linguagens:  
Android: Kotlin, Java.  
iOS: Objective-C, Swift.

## Referências Bibliográficas

> <a id="FRM1" href="#anchor_1">1.</a>SALLES, André. Plano de ensino da disciplina. Disponível em: [slides](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em 15 de maio de 2025.

<div style="text-align: center">
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/docs/especifica%C3%A7%C3%A3o-suplementar/docs/assets/modelagem/especifica%C3%A7%C3%B5es.png">
</div>

## Bibliografia

> HENRIQUE, Mathes. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <<https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>>. Acesso em: 15 maio 2025.




## Histórico de Versões

| Versão | Descrição                                      | Autor(es)                                                                                         | Data       | Revisor(es)                                                                                                 | Data de Revisão |
| ------ | ---------------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------------------------------------- | --------------- |
| 1.0    | Adicionando a introdução e metodologia  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Lucas Mendonça](https://github.com/lucasarruda9) | 15/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 17/05/2025      |
| 1.1    | Adicionando o texto base do FURPS+  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) e [Lucas Mendonça](https://github.com/lucasarruda9) | 15/05/2025 | [Karoline Luz](https://github.com/KarolineLuz) | 17/05/2025      |
| 1.2    | Adição da tabela Desempenho      | [João Marcos Moraes](https://github.com/JJOAOMARCOSS), [Lucas Mendonça](https://github.com/lucasarruda9) | 15/05/2025 | [Karoline Luz](https://github.com/KarolineLuz), [Artur Mendonça](https://github.com/ArtyMend07)     | 17/05/2025      |
| 1.3    | Adição da tabela Confiabilidade  | [Gabriel Lopes](https://github.com/BrzGab), [Karoline Luz](https://github.com/KarolineLuz)          | 16/05/2025 | [Ana Victória](https://github.com/navicg), [Luiza da Silva Pugas](https://github.com/Luizaxx)       | 17/05/2025      |
| 1.4    | Adição da tabela Usabilidade     | [Ana Victória](https://github.com/navicg), [Artur Mendonça](https://github.com/ArtyMend07)          | 16/05/2025 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS), [Gabriel Lopes](https://github.com/BrzGab)    | 17/05/2025      |
| 1.5    | Adição da tabela Suportabilidade | [Luiza da Silva Pugas](https://github.com/Luizaxx)                                                | 16/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9)                                                  | 17/05/2025      |
| 2.0    | Adidionando entrevista e termo de conscentimento| [Karoline Luz](https://github.com/KarolineLuz)                                          | 20/06/2025 | [Ana Victória](https://github.com/navicg)                                                 | 20/06/2025      |