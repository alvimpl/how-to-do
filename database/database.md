### Banco de Dados

A escolha do banco de dados terá grande influência no projeto, qual objetivo e tamanho da demanda que será atendida?
Antes de mais nada, qual tipo de banco usar, **Relacional** ou **Não Relacional**? A estrutura que você usará pode contribuir para o desempenho.

**Banco de dados Relacional**:
Aqui é minha escolha, por trabalharmos com dados fixos, muitos dados cruzados e a necessidade de joins para correlações entre tabelas, é o mais indicado também por termos várias regras de negócio mais complexas neste projeto.

**Banco de dados Não Relacional**:
Funciona nem para coisas ágeis, como APIs, IoTs, Sistemas Web escaláveis.

Para sistemas de poucos usuários podemos usar controladores menos robustos, como o SQL Lite, uma vez que este é focado para poucos acessos simultâneos, como empresas com 10 funcionários o menos. Isso é regra? Não, mas é algo que é comum ouvir no meio dos desenvolvedores.
Caso a projeção do Software seja bem robusta, utilize MySQL que é Open Source e gratuito, vai evitar problemas de licença no futuro.

**_Partindo daí deixo a configuração do projeto usando SQL Lite e todo seu passo à passo, usando versão gratuita disponível atualmente no ano desta documentação (2025)._**


[**SQLite**](sqlite.md)  
- <a href="(https://sqlitestudio.pl)" target="_blank">Download SQLiteStudio</a>
- <a href="(https://www.sqlite.org/download.html)" target="_blank">Download SQLite</a>
	- Configurações  
	- Nome do Banco  
	- Criando usuários  
	- Tabelas  
	- PK / FK  
	- Procedures / Funções  
	- Triggers  
