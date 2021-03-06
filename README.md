# Introdução a SGBD

## Banco de Dados Relacional - DB Relacional

Um banco de Daos relacional é formado por um conjunto de relações.

1. Tabela: relação
2. linhas: tuplas, registros
3. Colunas: atributos, campos

## Esquema de um BD relacional:
* Definição de um conjunto de tabelas e seus atributos que vão compor a base de dados (estrutura de BD relacional).

## Instância de um BD relacional:
* Conjunto de dados armazenados no BD em um determinado momento.

#### Dominio:
* Um conjunto de valores que uma coluna pode assumir. Cada domínio apresenta um tipo de - caractere, número, data etc.

#### Relação:
* Matemáticamente é um subconjunto de um produto cartesiano de uma lista de domínios.

## Emxemple de relação entre tabelas.

cod. func | nome func.     
--------- | ------
   1      | Everaldo
   2      | Eduardo
   3      | Edson
 
 ##     --------------   x ------------

   cod. func | nome func.
--------- | ------
   1      | Arroz
   2      | Feijão
   3      | Carne
   4      | Pão


## Caracteristicas das Relações:
* As linhas não são ordenadas
* Os atributos não são ordenados, pois devem ser referenciados pelo nome.
* Os Valores dos atributos são atômicos e monovalorados - cada atributo tem um valor, isto é, produto não pode ser manga, banana, maçã, laranja etc.

### Chaves:
* Uma chave pode ser formada por mais de um atributo, mas precisa ser menor conjunto de atributos possivél.

#### Chave primária - **PK - Primary Key**:
* Identifica unicamente um registro numa tabela. 

#### Chave candidata:
* Todas as chaves que **PODEM** ser primária da tabela. Uma tabela só pode ter *uma chave primária*.
#### Chave estrangeira - **FK Foren Key**:
* Relaciona o atributo de uma tabela á cahave primária de outra. 


#### Chave

## Integridade no DBs relacionais: 

### Integridade de domínio
* Os valores de uma coluna (atributo) deven estar dentro do conjunto de valores possíveis do domínio.

### Integridade de vazio
* Define se o valor de uma colina pode ser nulo (não é zero, nem branco) ou não.

### Integridade de entidade
* Os valores de uma chave primária não pode ser nulos.

### Integridade referencial
(**Chave estrangeira - FK**): chave estrangeira que relaciona uma coluna (**atributo**) à chave primária de outra tabela (**identitade**)

## Linguagem SQL
* A sigla refere-se à Structured Query, que significa Linguagem Estruturada de Consulta.

* A Linguagem **SQL** é a mais utilizada para consulta e manipulação de banco de dados.

### Data Definition Languagem (DDL):
* Manipulação da estrutura do banco de dados, por exemplo, criação e alteração de tabelas.

### Data Manipulation Languagem (DML):
* Permite a manutenção dos daos, como, por exemplo, inclusão e alteração dos registros de uma tabela.

### Data Query Language (DQL):
* Permite a pesquisa de dados, ou seja, possibilita a consulta de dados por meio do comando **SELECT** composto por várias clásulas e opções.

### Data Control Language (DCL):
* responsável pelo controle de autorização (acesso) dos dados.



