# API REQUEST IBGE COM STREAMLIT
Projeto desenvolvido para empresa onde eu trabalho bright cities onde trabalho como estagiário em engenharia de dados, foi proposto que desenvolvesse uma aplicação para poder 
pegar os dados do IBGE de uma forma fácil, analisando bastante descobri que o IBGE possui uma API que eu poderia utilizar, e com isso descobri a biblioteca streamlit que ela 
cria uma espécie de um site para utilizar em ciência de dados que era exatamente o que eu estava procurando, conforme foi desenvolvido o aplicativo onde eu solicito a o usuário
o número da tabela, número do indicador e ano para fazer o request na API do IBGE, com isso ele pega todos os dados desta tabela e eu jogo para um DataFrame de pandas e faço um 
merge com uma tabela que eu retiro de dentro do nosso banco de dados da AWS S3 e verifico se alguma cidade foi criada ou mudou o nome do determinado ano selecionado até o ano 
atual e com isso eu posso deletar do DataFrame as cidades que mudaram de nome ou foram criadas e para facilitar utilizei um código para poder salvar estes dados no computador,
também criei outra página que mostra uma tabela contendo o nome e o número desta tabela assim facilitando bastante a visualização, com tudo criado a única coisa que faltava era 
colocar este site no ar, com algumas pesquisas descobri que existe uma plataforma chamada Heroku que eu conseguiria colocar este site no ar através de algumas linhas de comando. 

https://request-ibge.herokuapp.com/
