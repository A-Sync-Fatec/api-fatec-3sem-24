<img src="https://drive.google.com/uc?id=1Uqw_d2XyZff0uYNJiRQhQnYzFTcjyc0x">
<br>


<p align="center">
  <a href="#objetivo">Objetivo da Sprint </a>  |
  <a href="#backlog">Sprint Backlog</a>
</p>

</br>

<span id="objetivo">
  
## 🎯 Objetivo da Sprint
A sprint tem como foco permitir que o super administrador faça login no sistema, crie novos projetos, e visualize esses projetos tanto para si quanto para os usuários comuns. Além disso, os projetos serão migrados do portal de transparência para nosso sistema.

<br>

<span id="backlog">

## 📖 Sprint Backlog
| **User Stories** | **Estimativa (pontos)** | **Critérios de aceitação** | **Tarefas front** | **Tarefas back** | **Tarefas BD** |
|------------------|------------------------|----------------------------|-------------------|------------------|----------------|
| Como super administrador quero fazer login no sistema para acessar configurações avançadas e gerenciar o portal de forma eficiente | 20 | O sistema deverá validar as credenciais inseridas pelo usuário e permitir o acesso apenas aos administradores já cadastrados, os encaminhando ao sistema dos administradores. Caso o usuário insira credenciais inválidas, negar sua entrada e exibir uma mensagem informando o motivo do erro. | Interface da tela de login com os campos usuário email e senha. Implementar a validação dos campos email e senha (formato padrão de email, senha obrigatória). Exibir mensagem (pop-up) de erro quando as credenciais forem inválidas. Redirecionar para a área dos administradores quando as credenciais forem válidas. | Implementar endpoint de login com verificação de credenciais e integrar o sistema de autenticação JWT. | Criar tabela de super administradores e armazenar seus tokens de sessão/JWT. |
| Como super administrador quero adicionar novos projetos ao sistema para manter o portal de transparência sempre atualizado e informativo | 29 | O sistema deve permitir que o super administrador adicione um novo projeto com as seguintes informações: referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, data de início e término, propostas/relatórios técnicos, contratos e artigos. Ao adicionar o projeto, o sistema deve validar todas as informações obrigatórias. Caso falte alguma informação obrigatória, o sistema deve exibir uma mensagem de erro clara indicando o campo que precisa ser corrigido. | Criar a tela de adicionar novos projetos com os campos necessários. Implementar validações no formulário para garantir que os campos obrigatórios sejam preenchidos. Permitir apenas o envio de arquivos no formato pdf e docx. Exibir mensagem de erro em caso de falha na criação do novo projeto. Redirecionar para a página de listagem de projetos após a criação do projeto com sucesso. | Implementar endpoint de criação de novos projetos. Integrar lógica para informar qual situação do projeto o novo projeto se encaixa. Implementar verificação de permissões para garantir que apenas super administradores possam criar projetos. | Criar tabela de Projetos com os campos necessários. Garantir que o esquema do banco de dados inclua validações para os campos obrigatórios. |
| Como usuário e administrador, quero que os projetos do Portal de Transparência sejam integrados ao meu sistema, garantindo que os dados sejam preservados e mantenham a transparência | 20 | Os projetos adicionados do Portal de Transparência ao sistema devem manter todos os dados, incluindo suas informações e seus documentos. | Adicionar os projetos do Portal de Transparência à interface do sistema, exibindo os detalhes: referência do projeto, data início e término, coordenador. | Implementar a funcionalidade de raspagem de dados (web scraping) dos projetos diretamente do Portal de Transparência. | Adicionar os projetos extraídos do Portal de Transparência ao banco de dados do sistema. |
