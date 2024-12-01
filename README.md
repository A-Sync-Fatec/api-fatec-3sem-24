<img src="/documents/capa_readme.png">

<br>

<p align="center">
  <a href="#visao">Visão Geral </a>  |
  <a href="#funcionalidades">Funcionalidades </a>  |
  <a href="#tecnologias">Tecnologias </a>  |
  <a href="#DoR">Definition of Ready (DoR) </a> |
  <a href="#DoD">Definition of Done (DoD) </a> |
  <a href="#sprints">Sprints</a>  |
  <a href="#requisitos">Requisitos do parceiro</a> |
  <a href="#backlog">Product Backlog</a>  |
  <a href="#cronograma">Cronograma</a>  |
  <a href="#padrao_commit">Padrão de Commit</a>  |
  <a href="#equipe">Equipe</a>
</p>

<br>
<br>

<span id="visao">
  
## 📖 Visão Geral

Este projeto é uma releitura do portal de transparência da Fundação de Apoio à Pesquisa de Pós-Graduandos(FAPG), desenvolvido com foco na segurança e acessibilidade. Aproveitando as tecnologias e linguagens de programação mais recentes, buscamos oferecer uma plataforma robusta e confiável, que facilite o acesso às informações públicas de maneira transparente e eficiente.

<br>
<br>

<span id="funcionalidades">
  
## ⚙️ Funcionalidades Principais
<br>
<img src="/documents/funcionalidades.png">

<br>
<br>

<span id="tecnologias">
  
## 💻 Tecnologias
<br>
<img src="/documents/tecnologias.png">

<br>
<br>

<span id="DoR">

## 📝 Definition of Ready (DoR)
<img src="/documents/definition_of_ready.png">

<br>
<br>

<span id="DoD">

## 🆗 Definition of Done (DoD)
<img src="/documents/definition_of_done.png">

<br>
<br>

<span id="sprints">

## 📁 Sprints
| Sprint | Período | Status |
| :----: | :-----: | :----: |
| [Sprint 1](https://github.com/A-Sync-Fatec/api-fatec-3sem-24/tree/sprint1) | 09/09/2024 - 29/09/2024 | ✅ |  <br>
| [Sprint 2](https://github.com/A-Sync-Fatec/api-fatec-3sem-24/tree/sprint2) | 30/09/2024 - 20/10/2024 | ✅ | <br>
| [Sprint 3](https://github.com/A-Sync-Fatec/api-fatec-3sem-24/tree/sprint3) | 21/10/2024 - 10/11/2024 | ✅ | <br>
| [Sprint 4](https://github.com/A-Sync-Fatec/api-fatec-3sem-24/tree/sprint4)| 11/11/2024 - 01/12/2024  | ✅ |

<br>
<br>

<span id="requisitos">

## ☝️ Requisitos do Parceiro
| ID | Requisitos Funcionais |
| :--: | :-----------------: |
| 1 | Ferramenta para migração dos dados do sistema da FAPG para o novo banco de dados |
| 2 | Interface para registro de novos projetos no sistema |
| 3 | Interface para busca de projetos |
| 4 | Interface para criar e gerenciar perfis de usuários |
| 5 | Relatórios e dashboards dos projetos, permitindo o uso de diferentes filtros |

<br>

| ID | Requisitos Não-Funcionais |
| :--: | :---------------------: |
| 6 | Documentação de apoio para uso do sistema |
| 7 | Aplicação Web com suporte para múltiplos usuários simultâneos |
| 8 | Design responsivo, adaptável a diferentes dispositivos |
| 9 | Medidas de segurança para proteger as informações do sistema |

<br>

<span id="backlog">

## 🌱 Product Backlog
| Sprint | User Stories                                                                                                                                           | Estimativa |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| 1      | Como Super Admin, quero poder fazer login no sistema para acessar configurações avançadas e gerenciar o portal de forma eficiente.                     | 3          |
| 1      | Como Super Admin, quero poder adicionar novos projetos ao sistema.                                                                                     | 5          |
| 1      | Como Usuário e Admin, quero que os projetos do Portal de Transparência sejam integrados ao meu sistema, garantindo que os dados sejam preservados e a transparência seja mantida. | 8          |
| 1      | Como Usuário e Admin, desejo visualizar os projetos armazenados no banco de dados na página da FAPG para garantir a transparência.                     | 7          |
| 2      | Como Super Admin, quero poder modificar projetos já criados para corrigir erros ou atualizar informações.                                              | 6          |
| 2      | Como Super Admin, quero poder excluir projetos obsoletos ou irrelevantes, mantendo o portal organizado.                                                | 6          |
| 2      | Como usuário, desejo visualizar os projetos por um intervalo de datas, para visualizar apenas aqueles que ocorreram ou estão ocorrendo dentro do período especificado      | 5          |
| 2      | Como Admin, quero visualizar no gráfico quantos projetos estão em andamento ou encerrados.                                                             | 4          |
| 2      | Como Usuário, quero visualizar os projetos pelo coordenador responsável para visualizar seus projetos                                                  | 4          |
| 2      | Como Admin, quero poder visualizar no gráfico os projetos pelo coordenador responsável, para acompanhar a performance dos coordenadores.               | 4          |
| 2      | Como Usuário, quero visualizar os projetos pela situação atual para visualizar quais projetos estão em andamento ou encerrados.                        | 6          |
| 2      | Como Admin, quero poder visualizar no gráfico os projetos pela situação atual para monitorar quais projetos estão em andamento ou encerrados.          | 6          |
| 2      | Como Admin, quero poder visualizar os projetos por faixa orçamentária para identificar e analisar projetos dentro de um determinado intervalo de valores.                  | 7          |
| 2      | Como Usuário, quero visualizar os projetos por referência do projeto para visualizá-los por palavra-chave.                                             | 7          |
| 2      | Como Usuário e Admin, quero poder realizar uma combinação de filtros para localizar os projetos de forma mais precisa.                                 | 9          |
| 3      | Como Super Admin, quero poder preencher um formulário de cadastro com as informações necessárias para criar um novo ADM.                               | 3          |
| 3      | Como um Admin recém-cadastrado, quero receber um e-mail de boas-vindas com instruções para acessar o sistema e definir uma senha.                      | 4          |
| 3      | Como Super Admin, quero poder visualizar uma lista de todos os Administradores cadastrados no sistema, incluindo detalhes como nome, e-mail, e data de criação.            | 3          |
| 3      | Como Super Admin, quero poder editar as informações de um Admin cadastrado caso haja a necessidade de atualizar dados, como o e-mail ou número de telefone.                | 6          |
| 3      | Como Super Admin, quero poder desativar um Admin que não deve mais ter acesso ao sistema.                                                                                  | 2          |
| 3      | Como Super Admin, quero aceitar ou não a proposta de criação, edição ou exclusão de projetos pelos administradores para ter mais controle da aplicação.                    | 5          |
| 4      | Como Super Admin, quero ter acesso a um histórico de todas as operações CRUDs feitas nos projetos e administradores.                                   | 7          |
| 4      | Como Usuário, quero poder exportar projetos em formatos PDF ou Excel para que eu possa consultá-los offline ou compartilhá-los com terceiros.          | 10          |
| 4      | Como Administrador,  quero poder cadastrar bolsistas que participam da Fundação, junto com o valor da sua bolsa, duração e projeto envolvido.          | 6          |
| 4      | Como Administrador, quero poder cadastrar os convênios (parcerias) firmadas entre a Fundação e outras entidades.                                       | 6          |
| 4      | Como Administrador, quero poder cadastrar materiais comprados pela Fundação que alguns projetos podem precisar.                                        | 6          |
| 4      | Como Administrador, quero poder cadastrar análises finais de projetos que foram finalizados.                                                           | 7          |

<br>
<br>

<span id="cronograma">

## 📅 Cronograma
<br>
<img src="/documents/cronograma.png" style="width: 50%;">

<br>
<br>

<span id="padrao_commit">

## 📃 Padrão de Commit
<br>
<img src="/documents/padrao_commit.png" style="width: 50%;">

<br>
<br>

# 📄 Manual do Usuário
<br>

## Manual Geral

Aqui você encontrará uma visão abrangente das funcionalidades disponíveis para todos os perfis de usuário, ajudando a navegar e utilizar o site de forma eficiente.

[PDF do Manual Completo](./documents/manual_usuario_sprint04.pdf)

## Manual do Administrador Principal

Este manual é destinado ao Administrador Principal, que possui controle total sobre o sistema. Aqui você encontrará instruções detalhadas para gerenciar todas as funcionalidades e garantir o bom funcionamento da plataforma.

[PDF do Administrador Principal](./documents/ManualADMPrincipal.pdf)

## Manual do Administrador Menor

Este manual foi criado para o Administrador Menor, com foco nas funções limitadas atribuídas a esse perfil. Explore as instruções para desempenhar suas responsabilidades de forma eficiente e segura.

[PDF do Administrador Menor](./documents/ManualADMMenor.pdf)


## Manual do Usuário Comum

Este guia é para você, usuário comum, e explica como acessar e aproveitar as funcionalidades do site.

[PDF do Usuário Comum](./documents/ManualUsuarioComum.pdf)

<span id="equipe">

## 👥 Equipe
| Foto | Nome | Função | Github | LinkedIn |
| :--: | :----: | :--: | :----: | :------: |
| <img src="https://github.com/maarantes.png?size=50" width=50px> | Marco Antonio Arantes | Product Owner | <a href="https://github.com/maarantes"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/marco-antonio-arantes/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/eberssj.png?size=50" width=50px> | Eber de Souza Junior | Scrum Master | <a href="https://github.com/eberssj"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/eber-junior-b2a4a3211/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <a href="https://github.com/ErikaDias2"> <img src="https://avatars.githubusercontent.com/ErikaDias2" alt="fotoperfil" width="50"></a> | Erika Dias Ribeiro | DEV Team | <a href="https://github.com/erikadias2004"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/erika-dias-ribeiro-608359266/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <a href="https://github.com/DiogoPalharini"> <img src="https://avatars.githubusercontent.com/DiogoPalharini" alt="fotoperfil" width="50"></a> | Diogo Palharini | DEV Team | <a href="https://github.com/DiogoPalharini"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/diogo-palharini-10b803275/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|  <a href="https://github.com/ZduardoPereira"><img src="https://avatars.githubusercontent.com/u/127692036?v=4" alt="fotoperfil" width="50"></a> | José Eduardo Fernandes | DEV Team | <a href="https://github.com/ZduardoPereira"><img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white&color=000000'/></a> | <a href="https://www.linkedin.com/in/jos%C3%A9-eduardo-fernandes-pereira-b26517284/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <a href="https://github.com/ojuansoares"><img src="https://avatars.githubusercontent.com/ojuansoares" alt="fotoperfil" width="50"></a> | Juan Garcia Soares | DEV Team | <a href="https://github.com/ojuansoares"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/ojuansoares"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
