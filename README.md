<div align="center">
  <img alt="logo" src="documents/sprint_04.png"
</div>

<br>
</br>

<div align=left> 
  
## 📦 Objetivo da Sprint
<br>
Na Sprint 04 foi criada a possibilidade do administrador poder escolher a refêrencia do projeto que ele quiser na hora da criação de um projeto, sem ter que seguir um padrão. 
<br>
<br>
Também foi criado o CRUD de bolsistas, convênios, materiais e análises de projeto, e também uma geração de relatório que mostra listas e dados desses 4 novos CRUDs. 
<br>
<br>
Há uma nova página de histórico, no qual é possível ver ações que administradores fizeram no site e a data em que a ação foi feita. 
<br>
<br>
Por último, agora também é possível exportar projetos via PDF ou Excel.

</div>

<br>
<br>

<div align=left> 

## 📖 Sprint Backlog
<br>

| ID  | User Story | Estimativa (pontos) | Critérios de Aceitação | Tarefas Front | Tarefas Back |
| --- | ----------- | ------------------- | ---------------------- | ------------- | ------------ |
| 1   | Como administrador, quero poder escolher a referência de projeto que eu quiser na hora de criar um projeto. | 3 | Possibilidade do usuário digitar a referência de projeto preferida. | - Adicionar input para digitar a ref. do projeto. | - Na entidade "Projeto" mudar o atributo "Ref. Projeto" para guardar IDs no formato XXX/YY ao invés do nome do projeto. |
| 2   | Como administrador, quero uma página de relatório que liste todos os CRUDs de bolsistas, convênios, materiais e análises. | 7 | Página relatório que mostre os cards de todos os CRUDs mencionados. | Interface da página de relatório e conexão com o back para pegar as informações. |  |
| 3   | Como administrador, quero poder criar, visualizar, editar ou excluir bolsistas. | 4 | CRUD completo da entidade Bolsista. | Interface para criar e editar bolsistas, card de bolsista com botões de editar ou deletá-lo. | Função com rotas para cadastrar, visualizar, editar ou excluir bolsistas. |
| 4   | Como administrador, quero poder criar, visualizar, editar ou excluir convênios. | 4 | CRUD completo da entidade Convênio. | Interface para criar e editar convênios, card de convênio com botões de editar ou deletar. | Função com rotas para cadastrar, visualizar, editar ou excluir convênios. |
| 5   | Como administrador, quero poder criar, visualizar, editar ou excluir materiais. | 4 | CRUD completo da entidade Material. | Interface para criar e editar materiais, card de material com botões de editar ou deletar. | Função com rotas para cadastrar, visualizar, editar ou excluir materiais. |
| 6   | Como administrador, quero poder criar, visualizar, editar ou excluir análises. | 4 | CRUD completo da entidade Análise Projeto. | Interface para criar e editar análises, card de análise com botões de editar ou deletar. | Função com rotas para cadastrar, visualizar, editar ou excluir análises. |
| 7   | Como administrador, quero poder exportar todas as informações sobre bolsistas, convênios, materiais e análises em um PDF de relatório anual, junto com gráficos que mostrem mais informações para enriquecer o conteúdo. | 6 | Botão que consiga gerar todas as informações sobre os novos CRUDs junto com gráficos variados. | Criação do botão e lógica para captura das informações e geração dos gráficos para exportação. |  |
| 8   | Como administrador, quero poder ver o histórico de ações que outros administradores fizeram na aplicação. | 10 | Página de histórico que mostre as ações feitas por administradores junto com a data de modificação. | Interface da página de histórico e conexão com o back para pegar as informações. | Funções que gerem um JSON com as ações feitas por administradores. |
| 9   | Como administrador, quero poder exportar um projeto via PDF ou Excel. | 3 | Botões com funções de exportar um projeto via PDF e Excel. | Criação dos botões e lógica para captura das informações para exportação. |  |

</div>

## 📄 Manual do Usuário
<br>
<a href="https://github.com/A-Sync-Fatec/api-fatec-3sem-24/blob/main/documents/manual_usuario_sprint04.pdf">Clique aqui</a>



