<h1 align="center">
    <img alt="preview application" src= "https://imgur.com/LWsC853.png width="400px"/>
</h1>

## :book: Sobre o projeto:

<p> Este foi um projeto desenvolvido em 03 de Outrobro de 2018, fiz alguns updates e upei o projeto somente agora em 2020.

O curso foi ministrado através da Alura Ensino Online com duração de 24h. 
O curso teve como objetivo demonstrar os fundamentos para a criação de um sistema Web.
</p>

 ## :iphone: Tecnologias e ferramentas:

 <ul>
  <li>HTML: Básico.</li>
  <li>CSS: Trabalhando com Bootstrap.</li>
  <li>PHP: Funções com PHP, Entendendo GET e POST, Include, Require, Cookies ...</li>
  <li>MYSQL: SQL Injection, Inserindo produtos no banco de dados, Ação de login, lidando com select e checkbox ...</li>
 </ul>
 
## :computer: Rodando o projeto:

1 - Clone o projeto na pasta htdocs se estiver usando o XAMPP.

2 - Start o APACHE e o MYSQL.

3 - Acesse o MySQL atravès do usuário padrão e crie o banco de dados com as seguintes informações:
CREATE TABLE usuarios (id integer auto_increment primary key, email varchar(255), senha varchar(255));
CREATE TABLE produtos (id integer auto_increment primary key, nome varchar(255), preco decimal(10,2), descricao text, categoria_id integer, usado boolean default false);
CREATE TABLE categorias (id integer auto_increment primary key, nome varchar(255));

4 - Adicione as informações na tabela usuarios e categorias da seguinte maneira:
INSERT INTO usuarios (email, senha) values ('endereço de email', 'senha encriptografada MD5');
INSERT INTO categorias (nome) values ("categoria1"), ("categoria2"), ("categoria3");

5 - Abra o navegador e acesse http://localhost/loja/index.php


