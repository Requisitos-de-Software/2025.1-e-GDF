# Léxico

## Introdução

<a id="ref-lexico-fonte1"></a>
O léxico é uma técnica de modelagem que visa estabelecer um vocabulário comum entre as partes interessadas do projeto, garantindo que todos compartilhem o mesmo entendimento sobre os termos utilizados no sistema. Esta técnica é particularmente útil para evitar ambiguidades e garantir a consistência na comunicação entre desenvolvedores, analistas e usuários.

## Metodologia
Para a elaboração deste léxico do sistema eGDF, adotou-se a notação do Léxico Ampliado da Linguagem (LAL), aplicando à análise dos requisitos funcionais e não implementados do sistema para identificar os termos mais relevantes e suas relações com o sistema. A seguir, apresentamos duas tabelas que guiam a estruturação do documento:

- A Tabela 1 detalha os conceitos fundamentais para descrever cada termo do léxico.
- A Tabela 2 apresenta o template utilizado para organizar as informações de cada termo.

---

<font size="3"><p style="text-align: center"><b>Tabela 1</b> -  Léxico Ampliado da Linguagem (LAL)</p></font>


| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |
---

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/ArtyMend07">Artur Mendonça</a> e <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025).</p></font>

---
<a id="ref-lexico-fonte2"></a>
<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Template Léxicos </p></font>




| **Campo**    | **Descrição**                                                                 |
|--------------|--------------------------------------------------------------------------------|
| **Símbolo**  | Nome do termo identificado na entrevista (entidade, ação ou estado relevante).|
| **Noção**    | Definição do termo: quem é, o que faz ou o que representa.                    |
| **Impacto**  | Efeitos da ação, uso do objeto ou implicações do estado descrito.             |
| **Sinônimos**| Termos equivalentes ou próximos encontrados durante a entrevista.             |
| **Tipo**     | Classificação como VERBO, OBJETO ou ESTADO, com base nas regras da Tabela 1.  |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/ArtyMend07">Artur Mendonça</a> e <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025).</p></font>

---

<a id="ref-lexico-fonte3"></a>
**Exemplo prático de entrada de léxico:**

| Símbolo | Renovação de Exemplar de Livro |
|---------|-------------------------------|
| Noção   | Exemplar de livro está emprestado a um usuário da biblioteca. Usuário deseja permanecer com o exemplar de livro por mais tempo. |
| Impacto | Funcionário da biblioteca altera data da devolução do exemplar de livro de modo que fique emprestado ao usuário por mais tempo. |

- Explicação com uma definição quase de "dicionário".
- Hyperlink: [exemplar de livro](#) / [usuário](#)
- Ocorrências do símbolo na aplicação.

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/ArtyMend07">Artur Mendonça</a> e <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025).</p></font>

---

## Léxico
> **VERBOS**

- **Login**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Login](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD01](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Noção**     | Processo de autenticação do usuário no sistema através da plataforma gov.br, com opções como reconhecimento facial. |
| **Impacto**   | Permite o acesso seguro às funcionalidades do aplicativo, garantindo a privacidade dos dados do usuário e uma experiência fluida. |
| **Sinônimos** | Autenticação, Acesso |
| **Tipo**      | **Verbo** |

<p style="text-align: center"><b>Tabela 3:</b> Léxico de Login</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/navicg">Ana Vitória</a> e <a href="https://github.com/Luizaxx">Luiza da Silva Pugas</a>, 2025).</p></font>




---

- **Agendamento**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Agendamento](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Marcação de horário para serviços específicos, como atendimentos em órgãos públicos. |
| **Impacto**   | Permite ao usuário organizar seus compromissos com serviços públicos de forma centralizada e eficiente. |
| **Sinônimos** | Marcação, Agenda |
| **Tipo**      | **Verbo** |


<p style="text-align: center"><b>Tabela 4:</b> Léxico de Agendamento</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/ArtyMend07">Artur Mendonça</a> e <a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025).</p></font>




---
- **Serviços**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Serviços](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Noção**     | Sistema que permite ao usuário avaliar e comentar sobre os serviços públicos utilizados. |
| **Impacto**   | Fornece feedback para melhorias nos serviços e transparência na gestão pública. |
| **Sinônimos** | Feedback, Avaliação |
| **Tipo**      | **Verbo** |


<p style="text-align: center"><b>Tabela 5:</b> Léxico de Serviços</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025).</p></font>


---

- **Compartilhamento**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Compartilhamento](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Ação de distribuir informações do sistema com outros usuários, como protocolos ou comprovantes. |
| **Impacto**   | Facilita a comunicação e troca de informações entre usuários, promovendo colaboração. |
| **Sinônimos** | Distribuição, Envio |
| **Tipo**      | **Verbo** |


<p style="text-align: center"><b>Tabela 7:</b> Léxico de Compartilhamento</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pela autora (<a href="https://github.com/Luizaxx">Luiza da Silva Pugas</a>, 2025).</p></font>


---

> **OBJETOS**

- **Notificação**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Notificação](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Alerta ou mensagem enviada ao usuário sobre eventos relevantes, personalizada com base em sua localização. |
| **Impacto**   | Mantém o usuário informado sobre atualizações, lembretes e eventos importantes relacionados aos serviços. |
| **Sinônimos** | Alerta, Aviso |
| **Tipo**      | **Objeto** |


<p style="text-align: center"><b>Tabela 8:</b> Léxico de Notificação</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/navicg">Ana Vitória</a> e <a href="https://github.com/JJOAOMARCOSS">João Marcos Moraes</a>, 2025).</p></font>



---

- **Funcionalidades Educacionais**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Funcionalidades Educacionais](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN06) |
| **Noção**     | Recursos específicos para acompanhamento de pendências de professores e alunos. |
| **Impacto**   | Melhora a gestão e acompanhamento das atividades educacionais. |
| **Sinônimos** | Recursos Educacionais |
| **Tipo**      | **Objeto** |


<p style="text-align: center"><b>Tabela 9:</b> Léxico de Funcionalidades Educacionais</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025).</p></font>

---

- **Mapa Interativo**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Mapa Interativo](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN09) |
| **Noção**     | Interface para reportar problemas urbanos através de um mapa. |
| **Impacto**   | Facilita a identificação e registro de problemas na cidade. |
| **Sinônimos** | Mapa de Ocorrências |
| **Tipo**      | **Objeto** |

<p style="text-align: center"><b>Tabela 10:</b> Léxico de Mapa Interativo</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pela autora (<a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025).</p></font>

----

- **Assistente Virtual**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Assistente Virtual](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [AD05](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD), [INT13](../elicitacao/tec_elicitacao/introspeccao.md#anchor_INT) |
| **Noção**     | Sistema automatizado que auxilia o usuário através de interações por voz ou texto, com respostas automáticas para dúvidas frequentes. |
| **Impacto**   | Fornece suporte e orientação aos usuários, facilitando a navegação e resolução de dúvidas. |
| **Sinônimos** | Chatbot, Ajudante Virtual |
| **Tipo**      | **Objeto** |

<p style="text-align: center"><b>Tabela 11:</b> Léxico de Assistente Virtual</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/ArtyMend07">Artur Mendonça</a> e <a href="https://github.com/Luizaxx">Luiza da Silva Pugas</a>, 2025).</p></font>


---

- **Tutorial**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Tutorial](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Guia passo a passo sobre como utilizar as funcionalidades do aplicativo. |
| **Impacto**   | Ajuda novos usuários a compreenderem as funcionalidades do sistema, reduzindo a necessidade de suporte externo. |
| **Sinônimos** | Guia, Manual |
| **Tipo**      | **Objeto** |

<p style="text-align: center"><b>Tabela 12:</b> Léxico de Tutorial</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/ArtyMend07">Artur Mendonça</a>, 2025).</p></font>


---

- **Relatório**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Relatório](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Documento gerado contendo informações sobre atividades do usuário, como agendamentos e solicitações. |
| **Impacto**   | Permite ao usuário acompanhar suas interações e serviços utilizados. |
| **Sinônimos** | Comprovante, Registro |
| **Tipo**      | **Objeto** |

<p style="text-align: center"><b>Tabela 13:</b> Léxico de Relatório</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelos autores (<a href="https://github.com/BrzGab">Gabriel Lopes</a> e <a href="https://github.com/KarolineLuz">Karoline Luz</a>, 2025).</p></font>


---

- **Preferência**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Preferência](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Configurações personalizadas do usuário para adaptar o sistema às suas necessidades. |
| **Impacto**   | Adapta o sistema às necessidades específicas de cada usuário, melhorando a experiência. |
| **Sinônimos** | Configuração, Personalização |
| **Tipo**      | **Objeto** |

<p style="text-align: center"><b>Tabela 14:</b> Léxico de Preferência</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/JJOAOMARCOSS">João Marcos Moraes</a>, 2025).</p></font>


---

- **Lembretes**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Lembretes](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Alertas sobre eventos futuros ou pendências importantes para o usuário. |
| **Impacto**   | Mantém o usuário informado sobre compromissos e prazos importantes. |
| **Sinônimos** | Alertas, Notificações |
| **Tipo**      | **Objeto** |

<p style="text-align: center"><b>Tabela 15:</b> Léxico de Lembretes</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/lucasarruda9">Lucas Mendonça</a>, 2025).</p></font>


---

>**ESTADOS**


- **Acessibilidade**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Acessibilidade](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS), [EN08](../elicitacao/tec_elicitacao/entrevista.md#anchor_EN), [AD08](../elicitacao/tec_elicitacao/analise_documentos.md#anchor_AD) |
| **Noção**     | Recursos que tornam o aplicativo utilizável por pessoas com diferentes necessidades. |
| **Impacto**   | Garante que o sistema possa ser utilizado por todos os usuários, promovendo inclusão digital. |
| **Sinônimos** | Inclusão Digital |
| **Tipo**      | **Estado** |

<p style="text-align: center"><b>Tabela 16:</b> Léxico de Acessibilidade</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pela autora (<a href="https://github.com/navicg">Ana Vitória</a>, 2025).</p></font>


---

- **Modo Escuro**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Modo Escuro](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Tema visual com cores escuras para reduzir o brilho da tela. |
| **Impacto**   | Melhora a experiência do usuário em ambientes com pouca luz, reduz consumo de bateria e oferece personalização. |
| **Sinônimos** | Tema Escuro |
| **Tipo**      | **Estado** |

<p style="text-align: center"><b>Tabela 17:</b> Léxico de Modo Escuro</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025).</p></font>


---

- **Ajuste de Acessibilidade**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Ajuste de Acessibilidade](../elicitacao/tec_elicitacao/analise_documentos.md#ajuste-de-acessibilidade---ad08) |
| **Noção**     | Funcionalidade que permite aumentar ícones e o tamanho da fonte no aplicativo por meio de um botão. |
| **Impacto**   | Melhora a usabilidade e a experiência para usuários com deficiência visual ou idosos. |
| **Sinônimos** | Ampliar Fonte, Aumentar Ícones |
| **Tipo**      | **Estado** |

<p style="text-align: center"><b>Tabela 18:</b> Léxico de Ajuste de Acessibilidade</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/BrzGab">Gabriel Lopes</a>, 2025).</p></font>


---

- **Idioma**

| Campo     | Descrição |
|-----------|-----------|
| **Símbolo**   | [Idioma](../elicitacao/tec_elicitacao/brainstorming.md#anchor_BS) |
| **Noção**     | Configuração de linguagem do aplicativo, permitindo sua utilização em diferentes idiomas. |
| **Impacto**   | Permite que usuários de diferentes nacionalidades utilizem o sistema em seu idioma preferido. |
| **Sinônimos** | Linguagem |
| **Tipo**      | **Estado** |

<p style="text-align: center"><b>Tabela 19:</b> Léxico de Idioma</p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor (<a href="https://github.com/JJOAOMARCOSS">João Marcos Moraes</a>, 2025).</p></font>


---

## Referência Bibliográfica

> SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.]. [ver no texto](#ref-lexico-fonte1)
> SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.]. [ver no texto](#ref-lexico-fonte2)
> SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.]. [ver no texto](#ref-lexico-fonte3)
> SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.]. [ver no texto](#ref-lexico-fonte4)
> SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.]. [ver no texto](#ref-lexico-fonte5)

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.]. Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/
mod_resource/content/1/Aula%2010.pdf. Acesso em: 15 mai. 2025.

> LEITE, J. C. S. P. et al. Enhancing a Requirements Baseline with Scenarios. In: INTERNATIONAL SYMPOSIUM ON REQUIREMENTS ENGINEERING, 1997, Annapolis. Proceedings... Los Alamitos: IEEE Computer Society Press, 1997. p. 44-53.

<center>
<figure>
    <img src="/assets/modelagem/lexico-fonte1.png" alt="Fonte 1 do Léxico" width="500">
    <figcaption>Fonte: SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.], p. 13.</figcaption>
</figure>

<figure>
    <img src="/assets/modelagem/lexico-fonte2.png" alt="Fonte 2 do Léxico" width="500">
    <figcaption>Fonte: SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.], p. 14.</figcaption>
</figure>

<figure>
    <img src="/assets/modelagem/lexico-fonte3.png" alt="Fonte 3 do Léxico" width="500">
    <figcaption>Fonte: SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.], p. 15.</figcaption>
</figure>

<figure>
    <img src="/assets/modelagem/lexico-fonte4.png" alt="Fonte 4 do Léxico" width="500">
    <figcaption>Fonte: SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.], p. 16.</figcaption>
</figure>

<figure>
    <img src="/assets/modelagem/lexico-fonte5.png" alt="Fonte 5 do Léxico" width="500">
    <figcaption>Fonte: SERRANO, Milene; SERRANO, Maurício. Aula 10. Universidade de Brasília, Faculdade Gama, [s.d.], p. 17.</figcaption>
</figure>
</center>



## Histórico de Versões

| Versão | Descrição | Autor(es) | Data | Revisor(es) | Data de Revisão |
|--------|-----------|-----------|------|-------------|-----------------|
| 1.0 | Introdução do documento | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 15/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.1 | Adição das imagens de referência | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 15/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.2 | Ajustes nas tabelas do léxico conforme novo modelo base | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 15/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.3 | Inclusão dos termos extraídos da técnica de entrevista (sem repetições) | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 15/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.4 | Adição dos termos de introspecção e correção da tabela de entrevista | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 16/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.5 | Adição dos termos de analise de documentos e alteração para a dinâmica correta da metodologia | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 16/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.6 | Adicionando Tabelas Léxas | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.7 | Removendo repetições e ambiguidade das Tabelas 3, 4, 5 e 6 | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.8 | Adicionando as Tabelas 3, 8 e 16 | [Ana Vitória](https://github.com/navicg) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.9 | Adicionando as Tabelas 4, 11 e 12 | [Artur Mendonça](https://github.com/ArtyMend07) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.10| Adicionando as Tabelas 13, 17 e 18 | [Gabriel Lopes](https://github.com/BrzGab) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.11| Adicionando as Tabelas 8, 14 e 19 | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.12| Adicionando as Tabelas 4, 9 e 15 | [Lucas Mendonça](https://github.com/lucasarruda9) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.13| Adicionando as Tabelas 3, 9 e 13 | [Karoline Luz](https://github.com/KarolineLuz) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.14| Adicionando as Tabelas 3, 7 e 10 |[Luiza da Silva Pugas](https://github.com/Luizaxx)| 17/05/2025 |  [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0)| 17/05/2025 |
| 1.15| Ajuste do histórico de versão, adição de referência bibliográfica e exemplo prático | [Artur Mendonça](https://github.com/ArtyMend07) | 17/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 17/05/2025 |
| 1.16| Correção dos caminhos das imagens e ajuste das fontes | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 18/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 18/05/2025 |
| 1.16.1| Adição de parênteses nas fontes e ajuste do tamanho das imagens | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 18/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 18/05/2025 |
| 1.16.2| Padronização completa do formato das fontes em todas as tabelas | [Artur Mendonça](https://github.com/ArtyMend07) e [Karoline Luz](https://github.com/KarolineLuz) | 18/05/2025 | [Lucas Mendonça](https://github.com/lucasarruda9) e [Gabriel Lopes](https://github.com/GabrielLopes0) | 18/05/2025 
