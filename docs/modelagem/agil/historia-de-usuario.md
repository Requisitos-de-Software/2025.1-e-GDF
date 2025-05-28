
| ID   | Descrição                                                                                                     | Rastreabilidade                                                             | Autor                                              |
| ---- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | -------------------------------------------------- |
| RF22 | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial. | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN04</a>         | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF18 | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes)     | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR20</a>      | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF27 | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso.                             | <a href="/elicitacao/tec_elicitacao/entrevista/#anchor_EN">EN11</a>         | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF30 | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.                   | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD04</a> | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF31 | O sistema deve permitir que o usuário confirme a resolução de problemas relatados.                            | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD06</a> | [Luiza da Silva Pugas](https://github.com/Luizaxx) |
| RF32 | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo.                                | <a href="/elicitacao/tec_elicitacao/analise_documentos/#anchor_AD">AD07</a> | [Luiza da Silva Pugas](https://github.com/Luizaxx) |

| RF12   | O usuário deve poder alterar o idioma do aplicativo                                                                                                                     | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR13</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF13   | O usuário deve poder personalizar suas preferências e perfis para recomendações de serviços                                                                             | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR14</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF14   | O aplicativo deve permitir o envio de mensagens curtas sobre vencimentos e lembretes importantes                                                                        | <a href="/elicitacao/tec_elicitacao/brainstorming/#anchor_BS">BR15</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF35   | Permitir ao usuário selecionar o tipo de serviço desejado (implantação, limpeza ou reparo).                                                                               | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT03</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF36   | Possibilitar a adição de descrição textual, imagem e localização GPS da ocorrência.                                                                                      | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT04</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |
| RF38   | Oferecer acesso a serviços de transporte público, incluindo pré-cadastro do Cartão Mobilidade.                                                                            | <a href="/elicitacao/tec_elicitacao/introspeccao/#anchor_INT">INT08</a>                                                                                                                  | [João Marcos Moraes](https://github.com/JJOAOMARCOSS)           |


<style>
details {
  background-color: #031b2e;
  border: 1px solidrgb(4, 55, 72);
  border-radius: 6px;
  padding: 10px;
  margin-bottom: 10px;
  color: white;
  font-family: sans-serif;
}

summary {
  cursor: pointer;
  font-weight: bold;
  color:rgb(253, 253, 253);
}
</style>

<details>
  <summary>📋 O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial. </summary>
  <p História de Usuário — US01: Autenticação Segura via gov.br
#### 
#### **Título:** Autenticação Segura via gov.br

---

####  História

**Como** um cidadão usuário do aplicativo,  
**Eu quero** me autenticar de forma segura utilizando a plataforma gov.br, com suporte a reconhecimento facial,  
**Para que** eu possa acessar os serviços oferecidos pelo aplicativo sem precisar criar uma nova conta e com total segurança.

---

####  Critérios de Aceitação

- [ ] O sistema deve redirecionar o usuário para a tela oficial de login do gov.br.
- [ ] Devem ser aceitas formas de autenticação oferecidas pelo gov.br (ex: senha, reconhecimento facial).
- [ ] Após login bem-sucedido, o sistema deve retornar o usuário ao app com sessão iniciada.
- [ ] Se o login falhar, uma mensagem clara deve ser exibida e o usuário poderá tentar novamente.
- [ ] O sistema deve estar em conformidade com a LGPD no tratamento de dados do usuário.

---

####  Subtarefas

- [ ] Integrar SDK/API do gov.br ao backend do app.
- [ ] Implementar interface de redirecionamento para o login gov.br.
- [ ] Tratar respostas da autenticação (sucesso, falha, erro de rede).
- [ ] Criar alertas e mensagens de erro amigáveis.
- [ ] Validar conformidade de dados com a LGPD.

---

####  Rastreabilidade

- **Requisito Funcional Relacionado:** RF22

---

####  Estimativa de Esforço

- **Story Points:** 5 (médio esforço)
</p>
</details>




























## Histórico de Versões

| Versão | Descrição                      | Autor(es)                                             | Data       | Revisor(es)                               | Data de Revisão |
| ------ | ------------------------------ | ----------------------------------------------------- | ---------- | ----------------------------------------- | --------------- |
| 1.0    | Criação da página e introdução | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 23/05/2025 | [Karoline Luz da Conceição](https://github.com/KarolineLuz) | 23/05/2025      |