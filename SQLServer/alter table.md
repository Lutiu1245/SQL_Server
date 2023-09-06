	
ALTER TABLE -> Altera uma tabela, mas cuidado ao fazer isso em tabelas já populadas
// adicionando um campo que por acaso possa ter sido esquecido de ser criado com a tabela
ALTER TABLE [NOME_TABELA]
		ADD [NOME_COLUNA] TIPO_CAMPO

Para dropar uma coluna com o alter table ->

ALTER TABLE [NOME_TABELA]
		DROP COLUMN [NOME_COLUNA]

Altera tabela =>

ALTER TABLE [NOME_TABELA]
		ALTER COLUMN [NOME_COLUNA] TIPO_ALTERADO

ALTER TABLE