# <h1>GitHub Copilot para auxiliar na solução de algoritmos em Python</h1>
<h2>Um código simples para mostras o entendimento do ChartGPT, como o COPILOT usar o ChartGPT5, fiz o exemplo direto 
com o chartGpt, mostrarei como a pesquisa do programador mudou radicalmente de pesquisado de páginas web para ser servido com resultados 
incrivelmente mastigados.</h2> 
<h3>Fiz uma pergunta ao chartgpt. <br>Quero uma conexao com banco de dados no Mysql com Python com os campos matricula, nome e cpf.</h3>
<B>Resultado:</B><br>
<B> 1-Instalar o conector MySQL para Python</B><br>
pip install mysql-connector-python
<br>
<B> 2-Estrutura da tabela no MySQL</B>
CREATE DATABASE escola;<br>
USE escola;<br>

CREATE TABLE alunos (<br>
    matricula INT PRIMARY KEY,<br>
    nome VARCHAR(100) NOT NULL,<br>
    cpf VARCHAR(14) NOT NULL UNIQUE<br>
);<br>

<b>Conexão com MySQL em Python</b>
import mysql.connector<br>

 <B> Conexão com o banco</B><br>
conexao = mysql.connector.connect(<br>
    host="localhost",<br>
    user="root",<br>
    password="sua_senha_aqui",<br>
    database="escola"<br>
)<br>

cursor = conexao.cursor()<br>

print("Conectado com sucesso!")<br>


