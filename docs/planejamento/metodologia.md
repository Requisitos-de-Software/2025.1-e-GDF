# Metodologia do Projeto – Carteira Digital de Trânsito

## Introdução

Este documento descreve a metodologia adotada pelo grupo para o desenvolvimento do trabalho de requisitos focado no aplicativo **Carteira Digital de Trânsito**. Após a análise das necessidades do projeto e das práticas de desenvolvimento ágil, optamos por utilizar o **Scrum** pela sua capacidade de organizar e evoluir projetos de forma incremental, garantindo transparência e colaboração entre os membros da equipe.

O Scrum permite entregas frequentes e feedback contínuo, possibilitando ajustes durante a definição, modelagem e validação dos requisitos do aplicativo.

## Escopo da Metodologia

O presente documento abrange:
- A definição da metodologia adotada.
- A estrutura e os papéis atribuídos dentro do Scrum.
- Os fluxos de trabalho e os padrões/convenções utilizados na gestão dos artefatos, como o controle de versão com Git e GitHub Pages.

**O que é Scrum?**  
Scrum é um framework ágil para o gerenciamento e desenvolvimento de projetos, fundamentado em ciclos de trabalho chamados *sprints*. Cada sprint possibilita uma entrega incremental do produto, permitindo feedback constante e ajustes rápidos conforme as necessidades dos usuários. Esse método enfatiza a colaboração, a transparência e a adaptabilidade do time, contribuindo para a melhoria contínua do processo de desenvolvimento.

## Abordagem e Estrutura do Scrum

No Scrum, o trabalho é dividido em ciclos curtos (*sprints*) que facilitam a revisão constante e a entrega incremental dos requisitos. Para este projeto, os papéis foram definidos da seguinte forma:

- **Product Owner:**  
  - **Artur Mendonça**  
  - Responsável por definir e priorizar os requisitos do aplicativo, mantendo a visão do produto alinhada com as necessidades dos usuários e stakeholders.

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
  Para facilitar a organização e priorização das issues, utilizamos as seguintes *labels*:
  - **documentation:** Indicada para questões e melhorias relacionadas à documentação.
  - **bug:** Utilizada para reportar erros ou problemas identificados no sistema.
  - **duplicate:** Para identificar issues que são cópias de outras já existentes.
  - **enhancement:** Sinaliza solicitações de melhorias ou novas funcionalidades.
  - **good first issue:** Para tarefas adequadas a colaboradores que estão iniciando.
  - **help wanted:** Indica que determinada tarefa necessita de colaboração ou apoio adicional.
  - **invalid:** Utilizada para issues que não se aplicam ou que foram identificadas como incorretas.
  - **question:** Para dúvidas ou solicitações de esclarecimento sobre algum aspecto do projeto.
  - **wontfix:** Indicada para issues que, por decisão da equipe, não serão corrigidas.

  ## Referências Bibliográficas

- Schwaber, K.; Sutherland, J. *The Scrum Guide*. Disponível em: [https://www.scrumguides.org/](https://www.scrumguides.org/). Último acesso: 10 abr. 2025.
- Rubin, K. S. *Essential Scrum: A Practical Guide to the Most Popular Agile Process*. Addison-Wesley Professional, 2012.
- Cohn, M. *Agile Estimating and Planning*. Prentice Hall, 2005.
- Sommerville, I. *Engenharia de Software*. 9ª Edição. Pearson Addison Wesley, 2019.
- Humble, J.; Farley, D. *Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation*. Addison-Wesley Professional, 2010.
- GITHUB. *GitHub Docs – Collaborating with issues and pull requests*. Disponível em: [https://docs.github.com/en/issues](https://docs.github.com/en/issues). Último acesso: 11 abr. 2025.

## Histórico de Versões

| Versão | Descrição      | Autor(es)                                            | Data              | Revisor(es)    | Data de Revisão |
|--------|------------|------------------------------------------------------|--------------------|------------| ------- |
| 1.0    |  Criação da documentação da metodologia               | [Artur Mendonça](https://github.com/ArtyMend07)   | 11/04/2025 | [Gabriel Lopes](https://github.com/BrzGab)   | 11/04/2025      |
| 1.1    |  Padronizando histórico de versões               |  [Lucas Mendonça ](https://github.com/lucasarruda9)  | 13/04/2025 | [Artur Mendonça](https://github.com/ArtyMend07)   | 13/04/2025      |