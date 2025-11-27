<h1>2d2025</h1>
<p>
- Dados, informação e conhecimento<br>
- Sistemas de Gerenciamento de
Banco de Dados (SGBD)<br>
   Proprietários<br>
   - SQL Server (Microsoft)<br>
   Gratuitos<br>
   - PostgreSQL<br>
   - MySQL<br>
   - Oracle (java)<br>
- Bancos de Dados Relacionais(Tabela)<br>
- Modelagem de BD<br>
  - Entidade-Relacionamento<br>
    - Entidade (Objeto)<br>
      - É importante?<br>
      - Existe mais de um?<br>
      - Tem PK (chave primaria)?<br>
    - Atributos (Caracteristicas)<br>
    - Relacionamentos<br>
      - Associação entre DUAS,<br>
        e somente duas, entidades<br>
      - Cardinalidade<br>
        - Mínimo: 0 ou 1<br>
        - Máximo: 1 ou N<br>
      - Normalização<br>

- Codificação (MySQL)<br>
  - DDL(Linguagem de Definição de Dados)<br>
    - CREATE<br>
      - CREATE DATABASE nome_db;<br>
      - CREATE TABLE nome_tb(<br>
           nome TIPO(Tamanho) EXTRAS<br>
        );<br>
      - EXTRAS: NOT NULL, NULL, PRIMARY KEY, AUTO_INCREMENT<br>
      - Cláusulas: IF NOT EXISTS<br>
        Ex.: CREATE DATABASE IF NOT EXISTS escola;<br>
    - ALTER<br>
      - ALTER TABLE nome_tabela ADD campo TIPO(tamanho) EXTRAS;
      - ALTER TABLE nome_tabela CHANGE campo campo TIPO(tamanho) EXTRAS;
      - ALTER TABLE nome_tabela DROP campo;
      - Clausulas: FIRST, AFTER
    - DROP<br>
      - DROP TABLE nome_tabela;
      - DROP DATABASE nome_database;
  - DML(Linguagem de Manipulação de Dados)<br>
    - INSERT<br>
       - INSERT INTO nome_tabela(campo1,campo2,campoN) VALUES(valor1,valor2,valorN);
       - INSERT INTO nome_tabela VALUES(valor1,valor2,valorN);
       - INSERT INTO nome_tabela VALUES(valo1),(valo1A),(valor1N);
    - UPDATE<br>
       - UPDATE nome_tabela SET telefone = '(85)998282926';
       - UPDATE cliente SET telefone = '(85)998282926' WHERE id = 15;
    - SELECT<br>
    - DELETE<br>
       - DELETE FROM nome_tabela;
       - DELETE FROM cliente WHERE nome = 'Maria Mendes';
</p>
