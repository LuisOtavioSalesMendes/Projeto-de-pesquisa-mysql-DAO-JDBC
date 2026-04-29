# Projeto-de-pesquisa-mysql-DAO-JDBC

# DAO

  DAO ou Data Access Object, são padrões de projeto reutilizáveis, são uma prática de programação que tem como intuito facilitar a resolução de problemas
  eles não são códigos prontos para fazer aplicações mas sim modelos de resolução de problemas, amplamente considerados uma boa prática para programadores que precisam corrigir problemas comuns em seus sistemas ou aplicações.

 O DAO encapsula o acesso dos dados em uma camada separada, permitindo que a lógica de negócios permanessa agnostica em relação ao tipo de banco de dados ou a tecnologia de persistência usada, isso traz vantagens como por exemplo a separação das preocupações separando as lógicas de acesso a dados e negócios faz um código mais limpo e fácil de manter, permitindo também que as equipes trabalhem em partes diferentes do sistema sem interferir umas nas outras.


 # JDBC

 JDBC ou Java Database Connectivity, é uma API que permite java se conectar e interajir com banco dde dados, sendo MySQL, SQL Sever, PostgreSQL dentre outros, para isso é usado um driver JDBC ele funciona como tradutor para a comunicação entre java e o banco de dados, cada banco de dados possui seu própio driver.

 O JDBC permite você gerenciar uma conecxão com o banco e dar comandos SQL (INSERT, UPDATE, DELETE) e fechar a conexão após o uso.


# MVC (Model-View-Controller)

 O MVC ou (Modelo-Visão-Controle), se trata de um metodo de organização de dados extremamente eficiente, ele separa a programação em 3 camadas, model é a camada acima do banco de dados, nesse caso o model é onde fica a conexão com o banco de dados e onde os comandos queries(Consultas SQL) são efetuadoss, além disso no model também é onde se faz a verificação dos dados antes deles serem salvos no sistema.
 
  O View é onde fica a interface ou UI(User interface), ele lê os dados do model e os exibe para o usuário, no view é onde vai ficar os componentes que o usuário vai ver na tela, como por exemplo caixas de texto ou elementos quais o usuário vai interagir




# Fontes de pesquisa

# Fontes para a pesquisa sobre DAO
https://medium.com/@felipe.damasceno.b/padr%C3%B5es-de-projeto-e-o-data-access-object-dao-7d7e4818866c
https://pt.stackoverflow.com/questions/113840/como-funciona-o-padr%C3%A3o-dao

# JDBC
https://medium.com/@gtbarbosa/java-jdbc-hibernate-e-spring-data-jpa-jpa-hibernate-e-jdbc-falando-sobre-java-e-acesso-a-849c8855905e

