<br>

<p align="center">
  <a href="#objetivo">Objetivo da Sprint </a>  |
  <a href="#backlog">Sprint Backlog</a>
</p>

</br>

<span id="objetivo">
  
## 🎯 Objetivo da Sprint


<br>

<span id="backlog">

## 📖 Sprint Backlog
| **User Stories** | **Estimativa (horas)** | **Critérios de Aceitação** | **Tarefas Front** | **Tarefas Back** | **Tarefas BD** |
|------------------|------------------------|----------------------------|-------------------|------------------| -------------- |
| Como super administrador quero fazer login no sistema para acessar configurações avançadas e gerenciar o portal de forma eficiente |                       | O sistema deverá validar as credenciais inseridas pelo usuário e permitir o acesso apenas aos administradores já cadastrados, os encaminhando ao sistema dos administradores. Caso o usuário insira credenciais inválidas, negar sua entrada e exibir uma mensagem informando o motivo do erro.               | - Interface da tela de login com os campos usuário (CPF ou email) e senha. <br> - Implementar a validação dos campos usuário (CPF ou email) e senha (formato padrão de email, senha obrigatória). <br>  - Implementar máscara no CPF quando informado no campo usuário. <br> - Exibir mensagem (pop-up) de erro quando as credenciais forem inválidas. <br> - Redirecionar para a área dos administradores quando as credenciais forem válidas. | - Implementar endpoint de login com verificação de credenciais e integrar o sistema de autenticação JWT | - Criar tabela de super administradores e armazenar seus tokens de sessão/JWT |
| Como super administrador quero adicionar novos projetos ao sistema para manter o portal de transparência sempre atualizado e informativo |                        | O sistema deve permitir que o super administrador adicione um novo projeto com as seguintes informações: referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, data de início e término, propostas/relatórios técnicos, contratos e artigos. Caso falte alguma informação obrigatória, o sistema deve exibir uma mensagem de erro clara indicando o campo que precisa ser corrigido. | - Criar a tela de adicionar novos projetos com os campos: referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, data de início e término, propostas/relatórios técnicos, contratos e artigos. <br> - Implementar validações no formulário para garantir que os campos obrigatórios sejam preenchidos. <br> - Permitir apenas o envio de arquivos no formato pdf e docx. <br> - Exibir mensagem (pop-up) de erro em caso de falha na criação de novo projeto. <br> - Redirecionar para página de listagem de projetos. | - Implementar endpoint de criação de novos projetos. <br> - Integrar lógica para informar qual situação do projeto o novo projeto se encaixa. <br> - Implementar verificação de permissões. | - Criar tabela de Projetos com os campos: referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, data de início e término. |
| Como usuário quero visualizar projetos por filtros para encontrar rapidamente as informações que procuro no portal |                        | O sistema deve exibir uma opção de filtros na página de projetos com as seguintes opções: referência do projeto, coordenador, data de início, data de término, classificação, situação do projeto. O sistema deve permitir que o usuário limpe os filtros para visualizar novamente a lista completa de projetos. | - Criar a interface de filtros na página de listagem de projetos, permitindo filtros por referência do projeto, coordenador, data de início, data de término, classificação, situação do projeto. <br> - Implementar a interação do usuário com os filtros. <br> - Exibir a lista de projetos filtrada conforme os critérios selecionados. | - Implementar endpoint que retorne a lista de projetos com os filtros escolhidos. <br> - Implementar paginação na listagem de projetos filtrados | - Filtrar projetos por referência do projeto, coordenador, data de início, data de término, classificação, situação do projeto. |
