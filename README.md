<div align="center">
  <img alt="logo" width="800" src="https://drive.google.com/uc?id=1U_xZRvSjeq6Havlb8ebhNp9dZKCCQ41b">
</div>

<br>

<p align="center">
  <a href="#objetivo">Objetivo da Sprint </a>  |
  <a href="#backlog">Sprint Backlog</a>
</p>

</br>

<span id="objetivo">
  
## 🎯 Objetivo da Sprint
Esta sprint terá como foco a criação de dashboards que permitirão uma visualização abrangente dos projetos, com opções de filtragem por data, coordenador, situação atual e faixa orçamentária. Além disso, também será possível o administrador atualizar e excluir projetos, além do usuário conseguir realizar a busca com filtros.

<br>

<span id="backlog">

## 📖 Sprint Backlog
| ID  | User Storie | Estimativa (pontos) | Critérios de Aceitação | Tarefas Front | Tarefas Back |
| --- | ----------- | ------------------- | ---------------------- | ------------- | ------------ |
| 1   | Como super administrador, quero poder visualizar todos admnistradores em uma pagina.  | 3 | Uma pagina onde mostra todos admnistradores, que com o icone "detalhes" abre as informações pessoais do mesmo. | - Interface: criar a página de exibição e usuarios para controle.<br>- Interface: criar um botão "detalhes" para exibir dados pessoais ao super administrador. | - Função: adicionar uma rota para a pagina de exibição dos administrdores. |
| 2   | Como super administrador, quero criar novos administradores.  | 3 | O botão "criar administrador" permite criar novo administrador, e após isso o novo admnistrador tera permissões de acessar a pagina de criação de projetos e dashboard | - Interface: criar botão "criar administrador" | - Função: adicionar uma função para criar novo administrador e enviar s informações passadas no cadastro para o banco de dados. |
| 3   | Como administrador, quero receber um e-mail para criar minha senha.  |  | Quando cadastrado um novo administrador, seja enviado um e-mail com credenciais de login temporaria, onde o administrador loga e muda sua senha. |  | - Função: criar uma função, onde é mandada o login  temporario do administrador via e-mail. |
| 4   | Como administrador, quero poder  solicitar fazer mudança nos projetos.    | 5 | Quando clicar em salvar alterações, ou adiconar projeto seja enviado um pedido de aceitação ao super administrador | - Interface: adicionar mensagem na tela do super administrador pedindo para aceitar a modificação feita pelo admnistrador "aceitar" ou "recusar". | - Função: adicionar rota do pedido ser enviado para a conta .     |
| 5   | Como super administrador, quero poder permitir solicitações de modificações de administradores.                                                 | 5                   | Após uma modificação feita por um administrador, seja encaminhada uma mensagem para o super administrador para "aceitar" ou "recusar" a modificação em específica.                                            | - Função: ticket para “aceitar” ou “recusar” solicitção de modificação de projetos.    | 
| 6  | Como administrador, quero poder alterar alguns dados pessoais.                           | 3                  | Visualizando dados pessoais em uma interface, a opção de mudar dados como "e-mail", "senha", "endereço" e "telefone".                                                | - Função Reutilizável: modificar dados do administrador e enviar ao banco de forma segura e concreta.<br>- Interface: criar icone apra exibir as informações pessoais do admnistrador                                                                                                                   |                                                     |
| 7   | Como super administrador, quero poder visualizar dados dos usuarios administradores.                                        | 6                  | Quando clicar no botão "detalhes", dentro da pagina dentro da pagina de administradores e exibir detalhadamente cada dado do administrador "email, telefone, nome, data de nascimento, RG, cargo, especialização, endereço".                                                                                                                           | - Interface: exibir todos os dados do administrador. |                                                     |
| 8   | Como super administrador, quero poder desativar contas de administradores.                                                 | 2                   | Dentro da pagina de administradores, uma opção dentro de "detalhes" um botão "desativar administrador".                                            | - Função: qundo clicar em desativar admnistrador, desativar as permissões dele, mas manter com status de desativado no banco.<br>- Interface: criar botão "desativar administrador"    |                                                   |                                                                                                                                                                                                                                                                                                               
