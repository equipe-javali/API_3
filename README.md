<span id="topo">
<h1 align='center'>
:boar: EQUIPE JAVALI :boar:

APRENDIZAGEM POR PROJETOS INTEGRADOS

3º SEMESTRE DSM - 2024
</h1>

<h1 align='center'> :keyboard: CTLR A :keyboard: </h1>

## :mag_right: Índice
<p align='center'>
    <a href="#objetivo">Objetivo</a> | 
    <a href="#relatorios">Relatórios</a> |
    <a href="#backlog">Backlog total</a> |
    <a href="#sprints">Sprints</a> |
    <a href="#tecnologias">Tecnologias</a> | 
    <a href="#instrucoes">Instruções</a> | 
    <a href="#equipe">Equipe</a> 
</p>

<span id='objetivo'>

## :dart: Objetivo
<p align='justify'>
    O projeto visa facilitar o manuseio dos ativos de uma empresa,
    sendo acompanhar quem atualmente possui o ativo, acompanhar manutenções do ativo, entre outros.
</p>

<span id='relatorios'>

## :pushpin: Relatórios
Na tabela abaixo é possível visualizar os resultados de cada Sprint clicando em "Ver entrega". 
<!-- [ver entrega](link da sprint correspondente) -->
| Sprint |  Entrega   |            Status           | Relatório |
|:------:|:----------:|:---------------------------:|:---------:|
| 01     | 14/04/2024 | ✔️ Finalizada | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-1) |
| 02     | 05/05/2023 | ✔️ Finalizada | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-2) |
| 03     | 26/05/2023 | ✔️ Finalizada | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-3) |
| 04     | 16/06/2023 | :construction: Em progresso | --        |

→ [Voltar ao topo](#topo)

<span id='backlog'>

## :clipboard: Requisitos Funcionais

<img src="doc/assets/Product Backlog.png" width="750px">
→ [Voltar ao topo](#topo)

## :clipboard: Requisitos NÃO Funcionais
:pushpin: Manual do Usuário   
:pushpin: Software Web e Multiusuário  
:pushpin: Sistema Responsivo   
:pushpin: Desenvolver o back-end com microserviços e o front-end com SPA  

<span id='sprints'>
<h2>Backlog das sprints</h2>

| Sprint |  Backlog da sprint   |
|:------:|:----------:|
| 01     | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-1?tab=readme-ov-file#backlog) | 
| 02     | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-2?tab=readme-ov-file#backlog) | 
| 03     | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-3?tab=readme-ov-file#backlog) | 
| 04     | [Clique aqui](https://github.com/equipe-javali/API_3/tree/Sprint-4?tab=readme-ov-file#backlog) | 

→ [Voltar ao topo](#topo)

<span id='tecnologias'>

## 💻 Tecnologias
Foram usadas as seguintes ferramentas, linguagens e tecnologias para a execução do projeto:
- [Figma](https://www.figma.com): Prototipagem
- [Git](https://git-scm.com): Versionamento
- [GitHub](https://github.com/): Armazenamento de código e documentação
- [TypeScript](https://www.w3schools.com/js/default.asp): Linguagem de programação do frontend
- [Java](https://java.com): Linguagem de programação do backend
- [Jira](https://www.atlassian.com/software/jira): Organização de tarefas
- [PostgreSQL](https://www.postgresql.org/): Banco de dados
- [Supabase](https://supabase.com/): Banco de dados PostgreSQL on-line
- [React](https://pt-br.reactjs.org/): Framework do frontend
- [Spring](https://spring.io/): Framework do backend

→ [Voltar ao topo](#topo)  
<span id="instrucoes">

## :gear: Instruções para Executar o Projeto

### Banco de Dados

1. Instalar o PostgreSQL: [Download PostgreSQL](https://www.postgresql.org/download/)
   (Selecionar as Command line tools nas opções de instalação)
2. Criar um banco de dados vazio: `create database ctrlA_BD;`
3. Copiar o arquivo ctrlA_BD.sql na raiz do repositório do Banco de Dados: [Repositório do Banco de Dados](https://github.com/equipe-javali/API_3_BD)
4. Executar esse arquivo para criar as tabelas e alimentar o banco de dados com o comando: `psql -h localhost -p 5432 -d ctrlA_BD -U postgres -f ctrlA_BD.sql`
5. Inserir a sua senha do Postgres

### Backend 

1. Instalar Java: [Download Java](https://www.java.com/download/ie_manual.jsp)
2. Clonar o repositório do backend: `git clone https://github.com/equipe-javali/API_3_BACK`
3. Editar o arquivo application.properties na pasta `API_3_BACK\CtrlA\src\main\resources` com sua senha do Postgres (alterar a porta e o usuário, se necessário)
4. Executar o backend usando um IDE como Eclipse ou Intellij (Maven).

### Frontend

1. Clonar o repositório do frontend: `git clone https://github.com/equipe-javali/API_3_FRONT`
2. Acessar a pasta `API_3_FRONT\ctrl-a` e executar os comandos: `npm install` e `npm start`

### Login

Para fazer login no sistema, use os seguintes dados:
- email: joane@email.com
- senha: melancia


→ [Voltar ao topo](#topo)  
<span id="equipe">

## :busts_in_silhouette: Equipe
|     Função    |            Nome           |                                                                                                    LinkedIn                                                                                                    |                                                                                    GitHub                                                                                    |
| :-----------: | :-----------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner | Katiane Soares | <a href="https://www.linkedin.com/in/katiane-soares-4b8193245/" target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">          | <a href="https://github.com/Katianefatec" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>          |
| Scrum Master      | Caique Silva    | <a href="https://www.linkedin.com/in/caiquepastelsilva" target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">       | <a href="https://github.com/PasteldePaodeCoxinha" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |
| Dev Team      | Bruno Serpa   | <a href="https://www.linkedin.com/in/brunoserpa" target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">              | <a href="https://github.com/BrunoSerpa" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>           |
| Dev Team      | Mariana Izumi       | <a href="https://www.linkedin.com/in/mariana-izumi-developer" target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> | <a href="https://github.com/MariMiks/" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>            |
| Dev Team      | Rafael Nunes  | <a href="https://www.linkedin.com/in/rafael-nunes-silva"  target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">     | <a href="https://github.com/Rafael-Nunes-Silva" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |
| Dev Team      | Silmara Bittencourt  | <a href="https://www.linkedin.com/in/silmara-in%C3%AAs-bittencourt-da-costa-243478214/?trk=people-guest_people_search-card&originalSubdomain=br"  target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">     | <a href="https://github.com/SBittencourt"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |
| Dev Team      | Maria Gabriela | <a href="https://www.linkedin.com/in/gabrieia-mello-3819a9270/"  target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">     | <a href="https://github.com/MariaGabrielaMello" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |
| Dev Team      | Marcus Betti | <a href="https://www.linkedin.com/in/marcus-betti-715b6614a/"  target="_blanck"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">     | <a href="https://github.com/marcusvbe"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>   |

→ [Voltar ao topo](#topo)
