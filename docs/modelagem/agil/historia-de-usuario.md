
| Código | Requisito                                                                                                                                     | Autor        | Rastreabilidade |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------------|--------------|-----------------|
| RF22   | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial.                                | Luiza Pugas  | EN04            |
| RF18   | O usuário deve conseguir compartilhar ou salvar informações importantes (como protocolos ou comprovantes).                                   | Luiza Pugas  | BR20            |
| RF27   | O aplicativo deve oferecer uma seção de suporte ao usuário com instruções de uso.                                                            | Luiza Pugas  | EN11            |
| RF30   | O sistema deve permitir que o usuário visualize e acompanhe o status das suas solicitações.                                                  | Luiza Pugas  | AD04            |
| RF31   | O sistema deve permitir que o usuário confirme a resolução de problemas relatados.                                                           | Luiza Pugas  | AD06            |
| RF32   | O sistema deve permitir que o usuário exclua seus dados e conta do aplicativo.                                                               | Luiza Pugas  | AD07            |


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