# DESAFIO-BEEDOO
Desafio Analista de Qualidade de Software Júnior - Beedoo

Historia de usuário : Módulo de Gestão de Cursos

Como administrador, 
Quero gerenciar cursos 
Para fornecer conteúdos educacionais organizados.

Detalhes da História

Como um administrador, 
Eu quero criar, excluir e listar cursos, 
Para que eu possa manter o catálogo de cursos atualizado e organizado.

Critérios de Aceitação

1.Criar Curso (caso de sucesso/happy path):

 - Dado que estou na página de gestão de cursos,
 - Quando eu clicar no botão "Criar Novo Curso" e preencher as informações necessárias (nome do curso, descrição, instrutor, etc.),
 - Então um novo curso deve ser criado e adicionado ao catálogo.

1.1Criar Curso (caso de falha):

- Dado que estou na página de gestão de cursos,
 - Quando eu clicar no botão "Criar Novo Curso" e não preencher as informações necessárias (nome do curso, descrição, instrutor, etc.),
-Então um novo curso não será criado e uma mensagem deverá aparecer para o usuário preencher os campos com as informações necessárias.


2.Excluir Curso (caso de sucesso/happy path):

 - Dado que estou na página de gestão de cursos e vejo uma lista de cursos,
 - Quando eu clicar no ícone de lixeira ao lado de um curso e confirmar a exclusão,
 - Então o curso deve ser removido do catálogo.

2.1. Excluir Curso (caso de falha):

 - Dado que estou na página de gestão de cursos e vejo uma lista de cursos,
 - Quando eu clicar no ícone de lixeira ao lado de um curso e confirmar a exclusão,
 - Então o curso não será removido do catálogo.

3.Listar Cursos (caso de sucesso/happy path):

 - Dado que estou na página de gestão de cursos,
 - Quando eu acessar a página,
 - Então eu devo ver uma lista de todos os cursos disponíveis, incluindo informações básicas como nome, descrição e instrutor.

3.1. Listar Cursos (caso de falha):

 - Dado que estou na página de gestão de cursos,
 - Quando eu acessar a página,
 - Então eu devo ver uma lista de todos os cursos disponíveis, incluindo informações básicas como nome, descrição e instrutor.

