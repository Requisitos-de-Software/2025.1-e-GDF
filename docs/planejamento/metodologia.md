# Metodologia do Projeto – Carteira Digital de Trânsito

## Introdução

Este documento descreve a metodologia adotada pelo grupo para o desenvolvimento do trabalho de requisitos focado no aplicativo **Carteira Digital de Trânsito**. Após a análise das necessidades do projeto e das práticas de desenvolvimento ágil, optamos por utilizar o **Scrum** pela sua capacidade de organizar e evoluir projetos de forma incremental, garantindo transparência e colaboração entre os membros da equipe.

O Scrum permite entregas frequentes e feedback contínuo, possibilitando ajustes durante a definição, modelagem e validação dos requisitos do aplicativo.

## Escopo da Metodologia

O presente documento abrange:
- A definição da metodologia adotada.
- A estrutura e os papéis atribuídos dentro do Scrum.
- Os fluxos de trabalho e os padrões/convenções utilizados na gestão dos artefatos, como o controle de versão com Git e GitHub Pages.
- Os processos para criação e gerenciamento de issues e pull requests.

**O que é Scrum?**  
Scrum é um framework ágil para o gerenciamento e desenvolvimento de projetos, fundamentado em ciclos de trabalho chamados *sprints*. Cada sprint possibilita uma entrega incremental do produto, permitindo feedback constante e ajustes rápidos conforme as necessidades dos usuários. Esse método enfatiza a colaboração, a transparência e a adaptabilidade do time, contribuindo para a melhoria contínua do processo de desenvolvimento.

## Abordagem e Estrutura do Scrum

No Scrum, o trabalho é dividido em ciclos curtos (*sprints*) que facilitam a revisão constante e a entrega incremental dos requisitos. Para este projeto, os papéis foram definidos da seguinte forma:

- **Scrum Master:**  
  - **Lucas Mendonça**  
  - Responsável por facilitar os processos, remover impedimentos e assegurar a aplicação correta dos princípios do Scrum.

- **Equipe de Desenvolvimento:**  
  - Composta pelos demais membros do grupo, que executam as atividades de levantamento, modelagem e documentação dos requisitos.

## Padrões e Convenções de Desenvolvimento

Para manter a qualidade e a rastreabilidade dos artefatos, adotamos as seguintes práticas:

- **GitHub Pages e Git:**
  - **Pull Requests (PRs):** Alterações são submetidas via PRs para permitir a revisão colaborativa e garantir a integração contínua das modificações.
  - **Issues:** Utilizadas para reportar e gerenciar tarefas, bugs e solicitações de melhorias, contendo descrições detalhadas e critérios de aceitação.
  - **Branches:** Nomeadas conforme o padrão `<tipo>/<descricao-breve>`, por exemplo, `docs/cronograma` ou `feat/novo-requisito`.
  - **Histórico de Versões:** Atualizado de forma padronizada para documentar as mudanças realizadas, bem como os responsáveis por elas.

- **Tipos de Branches – Padrões Comuns**

Em projetos de desenvolvimento colaborativo com Git, é comum adotar uma convenção para nomear branches. O padrão geralmente utilizado segue a estrutura:

| Tipo        | Uso                                                   | Exemplo                          |
|-------------|--------------------------------------------------------|----------------------------------|
| `feat`      | Adição de nova funcionalidade                          | `feat/autenticacao-google`      |
| `fix`       | Correção de bugs                                       | `fix/erro-login`                |
| `docs`      | Atualizações na documentação                           | `docs/metodologia`              |
| `style`     | Mudanças de estilo (semântica, formatação, etc)        | `style/ajuste-padding`          |
| `refactor`  | Refatorações (sem mudança de comportamento)            | `refactor/controller-usuario`   |
| `test`      | Inclusão ou modificação de testes                      | `test/cobertura-login`          |
| `chore`     | Tarefas de manutenção (ex: dependências, configs)      | `chore/update-dependencies`     |
| `hotfix`    | Correção urgente diretamente em produção               | `hotfix/corrige-bloqueio-app`   |

Fonte: Tabela elaborada pelo autor – Artur, 2025.

- **Commits:**  
    As mensagens de commit devem seguir um padrão similar ao das branches, mas utilizando o separador `:` em vez de `/`. Por exemplo:  
    - `docs: atualizar seção de padrões e convenções`  
    - `feat: adicionar endpoint de autenticação`  
    - `bugfix: corrigir erro de validação de formulário`

- **Labels Padrão:**  
  Para facilitar a organização e priorização das issues e pull requests, utilizamos as seguintes *labels*:
  - **documentation:** Indicada para questões e melhorias relacionadas à documentação.
  - **bug:** Utilizada para reportar erros ou problemas identificados no sistema.
  - **duplicate:** Para identificar issues que são cópias de outras já existentes.
  - **enhancement:** Sinaliza solicitações de melhorias ou novas funcionalidades.
  - **good first issue:** Para tarefas adequadas a colaboradores que estão iniciando.
  - **help wanted:** Indica que determinada tarefa necessita de colaboração ou apoio adicional.
  - **invalid:** Utilizada para issues que não se aplicam ou que foram identificadas como incorretas.
  - **question:** Para dúvidas ou solicitações de esclarecimento sobre algum aspecto do projeto.
  - **wontfix:** Indicada para issues que, por decisão da equipe, não serão corrigidas.
  - **ata:** Utilizada para issues relacionadas às atas de reuniões.
  - **ponto de controle:** Para issues relacionadas aos pontos de controle do projeto.
  - **inspeção:** Utilizada para issues que representam inspeções realizadas em artefatos.

## Gestão de Issues e Pull Requests

Para padronizar e organizar o fluxo de trabalho, estabelecemos diretrizes específicas para a criação e gestão de issues e pull requests:

### Criação de Issues

Todas as issues devem obrigatoriamente seguir o template fornecido no repositório, que pode ser encontrado em `.github/ISSUE_TEMPLATE/`. O uso do template garante a padronização e a inclusão de todas as informações necessárias. Uma issue completa deve conter:

1. **Título claro e descritivo**: Que indique o objetivo principal da issue.
2. **Descrição detalhada**: Contexto e informações necessárias para compreender o escopo da tarefa.
3. **Tarefas específicas**: Listadas em formato de checklist para acompanhamento do progresso.
4. **Labels apropriadas**: Que categorizem adequadamente o tipo de trabalho a ser realizado.
5. **Responsáveis designados**: Os membros da equipe que irão trabalhar na issue.
6. **Prazo de entrega**: Quando aplicável, a data limite para conclusão da tarefa.
7. **Pull Request vinculado**: Quando a issue for resolvida, deve ser vinculada ao PR correspondente.

### Hierarquia de Issues

Para facilitar a organização e o acompanhamento das atividades, implementamos um sistema de hierarquia de issues:

1. **Issues Mães (Parent Issues)**: 
   - Representam atividades maiores, como pontos de controle ou entregas completas.
   - São identificadas com a label `ponto de controle`.
   - Contêm links para todas as issues filhas relacionadas.
   - Exemplo: "Ponto de Controle 1 - Planejamento".

2. **Issues Filhas (Child Issues)**:
   - Representam tarefas específicas que compõem uma entrega maior.
   - São vinculadas à issue mãe correspondente.
   - Exemplo: "Elaborar cronograma do projeto".

3. **Issues de Atas**:
   - Para cada reunião, será criada uma issue específica para a ata.
   - As atas individuais serão vinculadas à issue mãe do ponto de controle correspondente.
   - Serão identificadas com a label `ata`.
   - Uma issue mãe de "Atas do Ponto de Controle X" conterá todas as atas individuais daquele período.

### Pull Requests (PRs)

Todos os pull requests devem seguir o template disponível em `.github/PULL_REQUEST_TEMPLATE.md`. Um PR adequado deve:

1. **Utilizar o template**: Preenchendo todos os campos relevantes.
2. **Vincular à issue correspondente**: Utilizando palavras-chave como "Closes #123" ou "Fixes #123".
3. **Descrever claramente as mudanças**: Explicando o que foi feito e por quê.
4. **Designar revisores**: Ao menos um membro da equipe deve revisar antes do merge.
5. **Incluir capturas de tela**: Quando aplicável, para demonstrar visualmente as alterações.
6. **Ter testes passando**: Se houver testes automatizados no projeto.

### Atas de Reunião vs. Inspeções

É importante diferenciar entre atas de reunião e inspeções:

- **Atas de Reunião**: 
  - Documentam as decisões, discussões e encaminhamentos das reuniões regulares da equipe.
  - São categorizadas com a label `ata`.
  - Seguem um formato padronizado que inclui data, participantes, pauta, decisões e próximos passos.

- **Inspeções**: 
  - **Não são atas**, mas sim avaliações técnicas de artefatos.
  - São categorizadas com a label `inspeção`.
  - Podem ser realizadas pelo próprio grupo ou por grupos externos.
  - Documentam a análise crítica de um artefato, identificando pontos fortes, deficiências e sugestões de melhoria.
  - Servem como base para ações corretivas e aprimoramento dos artefatos.

## Referências Bibliográficas

- Schwaber, K.; Sutherland, J. *The Scrum Guide*. Disponível em: [https://www.scrumguides.org/](https://www.scrumguides.org/). Último acesso: 10 abr. 2025.
- Rubin, K. S. *Essential Scrum: A Practical Guide to the Most Popular Agile Process*. Addison-Wesley Professional, 2012.
- Cohn, M. *Agile Estimating and Planning*. Prentice Hall, 2005.
- Sommerville, I. *Engenharia de Software*. 9ª Edição. Pearson Addison Wesley, 2019.
- GITHUB. *GitHub Docs – Collaborating with issues and pull requests*. Disponível em: [https://docs.github.com/en/issues](https://docs.github.com/en/issues). Último acesso: 11 abr. 2025.
- GITHUB. *About issues*. Disponível em: [https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues). Último acesso: 14 abr. 2025.
- GITHUB. *About pull requests*. Disponível em: [https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests). Último acesso: 14 abr. 2025.
- Chacon, S.; Straub, B. *Pro Git*. Apress, 2014. Disponível em: [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2). Último acesso: 14 abr. 2025.
- ATLASSIAN. *Linking issues*. Disponível em: [https://support.atlassian.com/jira-software-cloud/docs/link-issues/](https://support.atlassian.com/jira-software-cloud/docs/link-issues/). Último acesso: 14 abr. 2025.
- CONVENTIONAL COMMITS. *A specification for adding human and machine readable meaning to commit messages*. Disponível em: [https://www.conventionalcommits.org/](https://www.conventionalcommits.org/). Último acesso: 21 abr. 2025.
- IEEE. *IEEE Standard for Software Reviews and Audits*. IEEE Std 1028-2008, 2008. Disponível em: [https://standards.ieee.org/standard/1028-2008.html](https://standards.ieee.org/standard/1028-2008.html). Último acesso: 21 abr. 2025.
- ATLASSIAN. *Epics, Stories, Versions, and Sprints*. Disponível em: [https://support.atlassian.com/jira-software-cloud/docs/epics-stories-versions-and-sprints/](https://support.atlassian.com/jira-software-cloud/docs/epics-stories-versions-and-sprints/). Último acesso: 21 abr. 2025.
- Fagan, M. E. *Design and code inspections to reduce errors in program development*. IBM Systems Journal, vol. 15, no. 3, pp. 182-211, 1976. Disponível em: [https://doi.org/10.1147/sj.153.0182](https://doi.org/10.1147/sj.153.0182). Último acesso: 21 abr. 2025.

## Histórico de Versões

| Versão | Descrição      | Autor(es)                                            | Data              | Revisor(es)    | Data de Revisão |
|--------|------------|------------------------------------------------------|--------------------|------------| ------- |
| 1.0    |  Criação da documentação da metodologia               | [Artur Mendonça](https://github.com/ArtyMend07)   | 11/04/2025 | [Gabriel Lopes](https://github.com/BrzGab)   | 11/04/2025      |
| 1.1    |  Padronizando histórico de versões               |  [Lucas Mendonça ](https://github.com/lucasarruda9)  | 13/04/2025 | [Artur Mendonça](https://github.com/ArtyMend07)   | 13/04/2025      |
| 1.2    |  Padronizando histórico de versões               |  [Lucas Mendonça ](https://github.com/lucasarruda9)  | 13/04/2025 | [Artur Mendonça](https://github.com/ArtyMend07)   | 13/04/2025      |
| 1.3    |  Inclusão de processos para gestão de issues e pull requests               |  [Artur Mendonça](https://github.com/ArtyMend07)  | 19/04/2025 | [Luiza da Silva ](https://github.com/Luizaxx)   | 20/04/2025      |