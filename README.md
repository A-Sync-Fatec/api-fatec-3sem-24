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
| 3   | Como administrador, quero poder fazer adição, remoção ou edição de projetos.    | 5 | Quando clicar no ícone de exclusão, o projeto selecionado será excluído do banco de dados, retornando uma mensagem informando o sucesso da exclusão. | - Deletar: adicionar um ícone de lata de lixo vermelho ao lado dos projetos na visualização do administrador e conectar ao backend utilizando a rota de deletar projeto para a exclusão do projeto quando clicar no ícone. | - Função: adicionar uma rota para a função de exclusão do projeto.     |
| 4   | Como super administrador, quero poder permitir solicitções de modificações de administradores.                                                 | 5                   | Após uma modificação feita por um administrador, seja encaminhada uma mensagem para o super administrador para "aceitar" ou "recusar" a modificação em específica.                                            | - Função: ticket para “aceitar” ou “recusar” solicitção de modificação de projetos.    | 
| 5  | Como administrador, quero poder alterar alguns dados pessoais.                           | 3                  | Visualizando dados pessoais em uma interface, a opção de mudar dados como "e-mail", "senha", "endereço" e "telefone".                                                | - Função Reutilizável: modificar dados do administrador e enviar ao banco de forma segura e concreta.<br>- Interface: criar icone apra exibir as informações pessoais do admnistrador                                                                                                                   |                                                     |
| 6   | Como super administrador, quero poder visualizar dados dos usuarios administradores.                                        | 6                  | Quando clicar no botão "detalhes", dentro da pagina dentro da pagina de administradores e exibir detalhadamente cada dado do administrador "email, telefone, nome, data de nascimento, RG, cargo, especialização, endereço".                                                                                                                           | - Interface: exibir todos os dados do administrador. |                                                     |
| 7   | Como super administrador, quero poder desativar contas de administradores.                                                 | 2                   | Dentro da pagina de administradores, uma opção dentro de "detalhes" um botão "desativar administrador".                                            | - Função: qundo clicar em desativar admnistrador, desativar as permissões dele, mas manter com status de desativado no banco.<br>- Interface: criar botão "desativar administrador"    |                                                   |                                                                                                                                                                                                                                                                                                               
