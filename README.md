# <h1>GitHub Copilot para auxiliar na solução de algoritmos em Python</h1>
<h2>Um código simples para mostras o entendimento do ChartGPT, como o COPILOT usar o ChartGPT5, fiz o exemplo direto 
com o chartGpt, mostrarei como a pesquisa do programador mudou radicalmente de pesquisado de páginas web para ser servido com resultados 
incrivelmente mastigados.</h2> 
<h3>Fiz uma pergunta? Conexao com banco de dados no Mysql com Python com os campos matricula, nome e cpf.</h3>
<B>Resultado:</B><br>
pip install mysql-connector-python
<br>
<B>Estrutura da tabela no MySQL</B>
CREATE DATABASE escola;
USE escola;

CREATE TABLE alunos (
    matricula INT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    cpf VARCHAR(14) NOT NULL UNIQUE
);
<br>
<b>Conexão com MySQL em Python</b>

