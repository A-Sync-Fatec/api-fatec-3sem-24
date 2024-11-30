<div align="center">
  <img src="/documents/sprint_03.png">
</div>

<br>

</br>


## 📦 Objetivo da Sprint
<br>
A Sprint 03 teve como foco Super Administradores poderem criar, editar ou desativarem Administradores normais. Ao desativar um Admin Normal, sua conta não é excluída, mas sim desativada, significando que não conseguem mais fazer login até um Super Admin reativarem sua conta. Ao criar um Admin Normal, o mesmo receberá em seu e-mail cadastrado um link para redefinir sua senha.
<br>
<br>
Também foi criado a página Notificações, no qual Super Administradores podem aceitar ou recusar pedidos de alteração de projetos feitos por Admins Normais. Super Administradores não precisam fazer pedidos de alterações. A página também avisa que projetos que estão próximos de acabarem.

<br>
<br>

## 📖 Sprint Backlog
<br>

| ID  | User Story | Estimativa (pontos) | Critérios de Aceitação | Tarefas Front | Tarefas Back |
| --- | ----------- | ------------------- | ---------------------- | ------------- | ------------ |
| 1   | Como super administrador, quero poder visualizar todos admnistradores em uma pagina.  | 3 | Página que mostra todos admnistradores, com um ícone "detalhes" que abre as informações pessoais do mesmo. | - Interface: criar a página de exibição e usuarios para controle.<br>- Interface: criar um botão "detalhes" para exibir dados pessoais ao super administrador. | - Função: adicionar uma rota para a pagina de exibição dos administrdores. |
| 2   | Como super administrador, quero criar novos administradores.  | 3 | O botão "criar administrador" permite criar novo administrador, e após isso o novo admnistrador tera permissões de acessar a pagina de criação de projetos e dashboard | - Interface: criar botão "criar administrador" | - Função: adicionar uma função para criar novo administrador e enviar s informações passadas no cadastro para o banco de dados. |
| 3   | Como administrador, quero receber um e-mail para criar minha senha.  | 3 | Quando cadastrado um novo administrador, seja enviado um e-mail com credenciais de login temporaria, onde o administrador loga e muda sua senha. |  | - Função: criar uma função, onde é mandada o login  temporario do administrador via e-mail. |
| 4   | Como administrador, quero poder  solicitar fazer mudança nos projetos.    | 5 | Quando clicar em salvar alterações, ou adiconar projeto seja enviado um pedido de aceitação ao super administrador | - Interface: adicionar mensagem na tela do super administrador pedindo para aceitar a modificação feita pelo admnistrador "aceitar" ou "recusar". | - Função: adicionar rota do pedido ser enviado para a conta .     |
| 5   | Como super administrador, quero poder permitir solicitações de modificações de administradores.                                                 | 5                   | Após uma modificação feita por um administrador, seja encaminhada uma mensagem para o super administrador para "aceitar" ou "recusar" a modificação em específica.                                            | - Função: ticket para “aceitar” ou “recusar” solicitação de modificação de projetos.    | 
| 6  | Como administrador, quero poder alterar alguns dados pessoais.                           | 3                  | Visualizando dados pessoais em uma interface, a opção de mudar dados como "e-mail", "senha", "endereço" e "telefone".                                                | - Função Reutilizável: modificar dados do administrador e enviar ao banco de forma segura e concreta.<br>- Interface: criar icone apra exibir as informações pessoais do admnistrador                                                                                                                   |                                                     |
| 7   | Como super administrador, quero poder visualizar dados dos usuarios administradores.                                        | 6                  | Quando clicar no botão "detalhes", dentro da pagina dentro da pagina de administradores e exibir detalhadamente cada dado do administrador "email, telefone, nome, data de nascimento, RG, cargo, especialização, endereço".                                                                                                                           | - Interface: exibir todos os dados do administrador. |                                                     |
| 8   | Como super administrador, quero poder desativar contas de administradores.                                                 | 2                   | Dentro da pagina de administradores, uma opção dentro de "detalhes" um botão "desativar administrador".                                            | - Função: qundo clicar em desativar admnistrador, desativar as permissões dele, mas manter com status de desativado no banco.<br>- Interface: criar botão "desativar administrador"    |                                                   |                                                                                                                                                                                                                                                                                                               
<br>

<span id="manual">

### 📄 Manual do Usuário
  
<br>
<a href="https://github.com/A-Sync-Fatec/api-fatec-3sem-24/blob/main/documents/ManualdoUsuario-3sprint.pdf">Clique aqui</a>
