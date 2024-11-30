<div align="center">
  <img alt="logo" src="documents/sprint_02.png"
</div>

<br>
<br>

<div align="left">
  
## 📦 Objetivo da Sprint
<br>

Esta sprint terá como foco a criação de dashboards que permitirão uma visualização abrangente dos projetos, com opções de filtragem por data, coordenador, situação atual e faixa orçamentária. 
<br>
<br>
Além disso, também será possível o administrador atualizar e excluir projetos, além do usuário conseguir realizar a busca com filtros.

</div>

<br>

<div align="left">

## 📖 Sprint Backlog
<br>

| ID  | User Storie | Estimativa (pontos) | Critérios de Aceitação | Tarefas Front | Tarefas Back |
| --- | ----------- | ------------------- | ---------------------- | ------------- | ------------ |
| 1   | Como super administrador, quero modificar projetos já criados para corrigir erros ou atualizar informações.  | 6 | O ícone de edição na página de projetos do administrador levará para a interface de edição de projetos, onde mostrará as informações do projeto atual. Quando alterar as informações e clicar no botão “atualizar”, os novos dados serão modificados e enviados ao banco. | - Interface: criar a página de edição de projeto com a validação de campos obrigatórios.<br>- Atualizar: conectar ao backend e utilizar a rota de atualizar projeto para enviar as atualizações ao banco quando clicar no botão “Atualizar”. | - Função: adicionar uma rota para a função de atualização do projeto. |
| 2   | Como super administrador, quero excluir projetos obsoletos ou irrelevantes, mantendo o portal organizado.    | 6 | Quando clicar no ícone de exclusão, o projeto selecionado será excluído do banco de dados, retornando uma mensagem informando o sucesso da exclusão. | - Deletar: adicionar um ícone de lata de lixo vermelho ao lado dos projetos na visualização do administrador e conectar ao backend utilizando a rota de deletar projeto para a exclusão do projeto quando clicar no ícone. | - Função: adicionar uma rota para a função de exclusão do projeto.     |
| 3   | Como usuário, desejo filtrar os projetos por um intervalo de datas.                                          | 5                  | Quando selecionada a data no input “Data de início” será mostrado os projetos da data selecionada. Caso não houver projetos na data especificada, mostrar uma mensagem informando o usuário.                                                                    | - Função Reutilizável: filtrar os projetos do banco entre a data de início inserida no input até a data atual.<br>- Função Reutilizável: filtrar os projetos do banco entre a primeira data inserida no banco e a data de término inserida no input.                                                                                       |                                                     |
| 4   | Como administrador, quero filtrar no gráfico os projetos por período de execução.                           | 5                  | Quando selecionada a data no filtro “Data de início” será mostrado o gráfico com os projetos da data selecionada. Caso não houver projetos na data especificada, mostrar uma mensagem informando o administrador.                                                | - Função Reutilizável: filtrar os projetos do banco entre a data de início inserida no input até a data atual.<br>- Gráfico: chamar a função do front para inserir os dados no gráfico quando os inputs forem preenchidos.                                                                                                                   |                                                     |
| 5   | Como usuário, quero filtrar os projetos pelo coordenador responsável.                                        | 4                 | Quando selecionado o input “Coordenadores”, será exibido um dropdown com todos os coordenadores, podendo também digitar para encontrar mais rapidamente.                                                                                                                           | - Dropdown Reutilizável: exibir todos os coordenadores em ordem alfabética e mostrar os coordenadores correspondentes ao digitado conforme o administrador digita cada letra. Caso o coordenador digitado não existir, mostrar uma mensagem informando o administrador.<br>- Função Reutilizável: buscar todos os projetos do coordenador selecionado no input dropdown. |                                                     |
| 6   | Como administrador, quero filtrar no gráfico os projetos pelo coordenador responsável.                       | 4                  | Quando selecionado o filtro “Coordenadores”, será exibido um dropdown com todos os coordenadores. Após a seleção do coordenador, o gráfico mostrará todos os projetos já feitos por ele.                                                                                           | - Dropdown Reutilizável: exibir todos os coordenadores e mostrar os correspondentes ao digitado.<br>- Gráfico: quando o coordenador for selecionado, exibir o gráfico com o resultado da função que busca os projetos do coordenador, contendo uma linha do tempo com todos seus projetos já feitos.                                          |                                                     |
| 7   | Como usuário, quero filtrar os projetos pela situação atual.                                                 | 6                   | Quando selecionado o input “Situação atual”, será exibido um dropdown com as opções “Em andamento” e “Encerrado“. Caso existir projetos na situação escolhida, exibi-los. Caso não existir, retornar uma mensagem informando o usuário.                                             | - Função Reutilizável: buscar os projetos por “em andamento” e “encerrado”.                                                                                                                                                                                                                                                                                                       |                                                     |
| 8   | Como administrador, quero filtrar no gráfico os projetos pela situação atual.                                | 6                  | Quando selecionado o filtro “Situação atual”, será exibido um dropdown com as opções “Em andamento” e “Encerrado“. Caso existir projetos na situação escolhida, exibir o gráfico com os projetos.                                                                                   | - Função Reutilizável: buscar os projetos por “em andamento” e “encerrado”.<br>- Gráfico: exibir os projetos com a situação atual escolhida.                                                                                                                                                                                                                                     |                                                     |
| 9   | Como administrador, quero filtrar os projetos por faixa orçamentária.                                        | 7                  | Quando selecionado o valor no filtro “valor mínimo” será mostrado o gráfico com os projetos a partir do valor inserido até o maior valor armazenado.                                                                                                                                | - Função: filtrar os projetos do banco entre o valor mínimo inserido no input até o maior valor armazenado no banco.<br>- Gráfico: exibir os dados filtrados no gráfico.                                                                                                                                                                                                        |                                                     |
| 10  | Como usuário, quero filtrar os projetos por referência do projeto.                                           | 9                   | Quando selecionado o input “Referência do projeto”, será exibido um dropdown com todas as referências de projeto. Caso o nome digitado não existir, mostrar uma mensagem informando o usuário.                                                                                     | - Função: filtrar projetos comparando com as letras escritas no input text e os projetos armazenados no banco.                                                                                                                                                                                                                                                                  |                                                     |
| 11  | Como administrador e usuário, quero realizar uma combinação de filtros para localizar os projetos.           | 10                   | Quando selecionado dois ou mais filtros, será mostrado o gráfico com as informações de ambos os filtros selecionados.                                                                                                                                                             | - Função Reutilizável: combinar os dados dos filtros e aplicar no gráfico.                                                                                                                                                                                                                                                                                                      |                                                     |
</div>

<br>
<br>

<div align="left">
  
## 📄 Manual do Usuário
<br>

<a href="https://github.com/A-Sync-Fatec/api-fatec-3sem-24/blob/main/documents/ManualdoUsuario-sprint2.pdf">Clique aqui</a>
</div>
