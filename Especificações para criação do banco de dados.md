# Colaboratory

Estou enviando nesse repositório o código fonte do  projet

Para o download do banco de dados digite no seu editor: !pip install db-sqlite3
Em seguida importe o banco de dados usando o código: import sqlite3
Para criar o banco digitei: banco = sqlite3.connect('banco_convest.db')
E para interagir criando Tabelas e  valores das colunas digitei o código :  
cursor = banco.cursor()
cursor.execute("CREATE TABLE b3sa (preco integer, data date)")
cursor.execute("CREATE TABLE petro (preco integer, data date)")
cursor.execute("INSERT INTO b3sa VALUES('"+dadosb+"','"+meta_dados_b+"')
cursor.execute("INSERT INTO petro VALUES('"+dadosp+"','"+meta_dados_p+"')

Consigui criar a estrutura do banco, porém tive dificuldade de fazer a interação com os dados.
