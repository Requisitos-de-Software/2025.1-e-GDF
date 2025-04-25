# MoSCoW

## Introdução

A técnica MoSCoW é uma abordagem de priorização usada para identificar a importância relativa de diferentes requisitos em um projeto. Seu nome é um acrônimo para quatro categorias de prioridade: **Must Have**, **Should Have**, **Could Have** e **Won’t Have**.

No contexto do projeto do aplicativo **e-GDF**, essa técnica foi utilizada para definir quais funcionalidades e requisitos são essenciais, desejáveis, opcionais ou fora do escopo neste momento.

Contudo, apesar de sua popularidade, a técnica MoSCoW possui limitações importantes. De acordo com o International Institute of Business Analysis (IIBA, 2009):

### **[Must Have](#must-have):**
O requisito **deve ser atendido** para que a solução seja considerada um sucesso.
### **[Should Have](#should-have):** 
O requisito é **importante** e **deveria ser incluído** na solução, se possível, mas **não é essencial** para o sucesso imediato.
### **[Could Have](#could-have):** 
É um recurso **desejável**, mas que pode ser **adiado ou até eliminado**, sendo implementado apenas se houver tempo e recursos suficientes.
### **[Won’t Have](#wont-have):** 
Indica um requisito que **não será implementado no momento**, mas **poderá ser considerado futuramente**.

Apesar da clareza nas classificações, a técnica não oferece um critério objetivo para decidir qual requisito se encaixa em qual categoria. Isso gera **ambiguidade**, especialmente na categoria "Won’t", que pode ser interpretada como "não agora" ou "nunca". Tais distinções precisam estar claras para que todos os envolvidos compartilhem do mesmo entendimento.

Na prática, muitos usuários tentam garantir que seus requisitos recebam a classificação “Must”, pois compreendem que qualquer outra categoria é vista como "não será implementado em breve". Assim, a técnica acaba não funcionando bem como método real de priorização quando mal interpretada ou mal aplicada.

## Metodologia

A técnica MoSCoW foi aplicada por meio de reuniões com os participantes do projeto, que discutiram e classificaram os requisitos com base em critérios como impacto no usuário, viabilidade técnica, alinhamento com os objetivos do governo e disponibilidade de recursos. Apesar de sua simplicidade, foi necessário cuidado para que as classificações fossem coerentes e refletissem verdadeiramente o valor e a urgência dos requisitos.

## Participantes
- [Ana Vitória](https://github.com/navicg) – Participante da priorização
- [Gabriel Lopes](https://github.com/BrzGab)– Participante da priorização
- [Karoline Luz](https://github.com/KarolineLuz) – Participante da priorização


## Requisitos Priorizados

**Legenda:**

- **RF**: Requisito Funcional  
- **RNF**: Requisito Não Funcional

### Requisitos Funcionais

**Tabela 1: Requisitos Funcionais**

| Tipo | Descrição | ID | Prioridade |
|------|---------------------------------------------------------------------------|------|-------------|
| RF | Login com CPF e senha para acesso ao sistema | RF01 | [Must Have](#must-have) |
| RF | Consulta de contracheques | RF02 | [Must Have](#must-have) |
| RF | Visualização de dados funcionais (matrícula, cargo, órgão) | RF03 | [Must Have](#must-have) |
| RF | Notificações de atualizações do sistema | RF04 | [Should Have](#should-have) |
| RF | Agendamento de atendimentos presenciais | RF05 | [Could Have](#could-have) |
| RF | Acesso por biometria | RF06 | [Could Have](#could-have) |
| RF | Personalização de notificações | RF07 | [Won’t Have](#wont-have) |


Fonte: [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz)


### Requisitos Não Funcionais

**Tabela 2: Requisitos Não Funcionais**

| Tipo | Descrição | ID | Prioridade |
|------|---------------------------------------------------------------------------|-------|-------------|
| RNF | Aplicativo compatível com Android e iOS | RNF01 | [Must Have](#must-have) |
| RNF | Interface responsiva e acessível | RNF02 | [Must Have](#must-have) |
| RNF | Tempo de resposta inferior a 2 segundos | RNF03 | [Should Have](#should-have) |
| RNF | Modo escuro | RNF04 | [Could Have](#could-have) |
| RNF | Suporte multilíngue | RNF05 | [Won’t Have](#wont-have) |

Fonte: [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz)

## Referências Bibliográficas

> Priorização de Requisitos – UnB-FCTE. [PDF](https://aprender3.unb.br/pluginfile.php/3096091/mod_resource/content/3/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf)  
> Técnica MoSCoW – Trecho do material de Priorização de Requisitos – UnB-FCTE. [PDF](https://drive.google.com/file/d/1P-nfa2q3aiHsXSLgVBxa65OvOc0iSW58/view)  
> Aula 07 – Requisitos – UnB-FCTE.  [PDF](https://aprender3.unb.br/pluginfile.php/3096092/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf)  
> Portal do GDF. [Link do site](https://www.df.gov.br/)  
> Aplicativo e-GDF. [Loja de Aplicativos](https://play.google.com/store/apps/details?id=br.gov.df.eGDF&hl=pt_BR)  
> GOV.BR - Portal Oficial. [https://www.gov.br/pt-br](https://www.gov.br/pt-br)


## Histórico de Versões

| Versão | Data       | Descrição                                | Autor(es)             | Revisor(es) |Data de Revisão |
|--------|------------|------------------------------------------|------------------------|-------------|-------------|
| 1.0    | 24/04/2025 | Criação do documento com requisitos MoSCoW | [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz)| [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)| 
1.1 | 24/04/2025| Correção e adição de melhorias no artefato| [Ana Victória](https://github.com/navicg), [Gabriel Lopes](https://github.com/BrzGab) e [Karoline Luz](https://github.com/KarolineLuz)|[João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)| |
