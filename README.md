mysql -u root -p

create database projeto_individual_m4

create table curso (
id_curso int primary key,
id_turma int,
carga_horaria int,
valor int);

create table turma (
id_turma int primary key,
id_curso int,
id_turnos varchar(20),
id_alunos int);

create table alunos (
id_alunos int primary key,
id_turma int,
id_nome varchar(255),
id_cpf varchar(20));

⇨ Existem outras entidades além dessas três?
Sim. (Ex: instrutores e disciplinas)

⇨ Quais são os principais campos e tipos?
Curso- id curso int. Turma- id turma int. Alunos- id alunos int.

⇨ Como essas entidades estão relacionadas?
cursos tem turmas e turmas tem alunos.


