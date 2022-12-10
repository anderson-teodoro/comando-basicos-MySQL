# comando-basicos-MySQL
Aqui estão alguns exemplos de comandos que você pode usar no MySQL:

### Para conectar ao MySQL:
mysql -u username -p

### Para selecionar uma base de dados:
USE nome_da_base_de_dados;

### Para exibir todas as bases de dados existentes:
SHOW DATABASES;

### Para criar uma nova base de dados:
CREATE DATABASE nome_da_base_de_dados;

### Para exibir todas as tabelas de uma base de dados:
SHOW TABLES;

### Para criar uma nova tabela:
CREATE TABLE nome_da_tabela (
   id int(11) NOT NULL AUTO_INCREMENT,
   nome varchar(255) DEFAULT NULL,
   idade int(11) DEFAULT NULL,
   PRIMARY KEY (id)
);

### Para inserir dados em uma tabela:
INSERT INTO nome_da_tabela (nome, idade) VALUES ('João', 25);

### Para selecionar dados de uma tabela:
SELECT * FROM nome_da_tabela;

##Esses são apenas alguns exemplos básicos de comandos MySQL. Existem muitos outros comandos que você pode usar, dependendo da sua necessidade. Para obter mais informações, consulte a documentação do MySQL.

