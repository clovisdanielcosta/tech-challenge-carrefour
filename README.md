<h1 align="center">
:small_red_triangle_down:  Tech Challenge Carrefour
</h1>
<h2 align="center">
Criação de App para Compra em Grupo
</h3>
<h3 align="center">
Bootcamp Global FullStack Developer da Digital Innovation One
</h3>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=7159c1&labelColor=000000">
</p>

<p>
O objetivo deste projeto é vender a ideia de um app para melhorar o relacionamento entre o Grupo Carrefour e seus clientes  aplicando alguns conceitos aprendidos no cursos de Python, JavaScript, HTML5 e CSS3.
</p>

<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-instalando">Instalando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#small_orange_diamond-contribuindo">Contribuindo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#small_orange_diamond-licença">Licença</a>
</p>

<p align="center">
  <img alt="Appo" src="core/static/img/carrefour.gif" width="90%">
</p>

## :rocket: Tecnologias

Nesse projeto foram usadas as seguintes tecnologias:

- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Postgres](https://www.postgresql.org/)
- [Html5](https://developer.mozilla.org/pt-BR/docs/Web/HTML/HTML5)
- [Css3](http://www.linhadecodigo.com.br/artigo/3566/introducao-as-novidades-do-css3.aspx)
- [Sqlalchemy](https://www.sqlalchemy.org/)
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)

## :computer: Instalando

1. É requisito necessário ter instalados na máquina Python, Django e Postgres.

2. Faça o clone deste repositório numa pasta desejada: 

    `$ git clone https://github.com/clovisdanielcosta/python-agenda.git`

3. Entre na pasta do app:

    `$ cd python-agenda`

4. Rode este comando para instalar as dependências:
  
    `$ pip install -r requirements.txt`

5. Rode este comando para efetuar as migrations:
  
    `$ python manage.py migrate`

6. Rode este comando para criar o super usuário:
  
    `$ python manage.py createsuperuser --username admin`

7. Rode este comando para subir o servidor:
  
    `$ python manage.py runserver`

8. Digite o comando abaixo na barra de endereço de um navegador e crie um usuário:
  
    `localhost:8000/admin`

9. Digite o comando abaixo na barra de endereço de um navegador para logar no sistema:
  
    `localhost:8000/`

## :small_orange_diamond: Contribuindo

1. Para que o Django localize seus arquivos estáticos, por exemplo de imagens ou estilos, deverá criar um diretório dentro do projeto chamado "static" e colocar estes arquivos dentro desta pasta. Depois disto basta fazer as referências deles dentro dos templates das seguintes formas:

```python

    <img width="45px" src="{% static 'img/icon-logout.png' %}?version=1"/>

    <link rel="stylesheet" href="{% static 'css/agenda.css' %}?version=1">

```
2. Para saber mais sobre a migração de Sqlite para Postgres acesse o link abaixo:

    [https://www.youtube.com/watch?v=ZgRkGfoy2nE](https://www.youtube.com/watch?v=ZgRkGfoy2nE)

3. Para entender melhor como fazer o deploy de aplicações em Python com Django no Heroku acesse o link abaixo:

    [https://www.youtube.com/watch?v=wsi0xpHUM00](https://www.youtube.com/watch?v=wsi0xpHUM00)

## :small_orange_diamond: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
A(s) imagem(s) usada(s) neste projeto são originais do autor ou foram obtidas através de sites de terceiros com a devida autorização para uso gratuito.

## :small_orange_diamond: Agradecimentos

Quero agradecer a <b>Digital Innovation One</b> e ao Banco Carrefour pelo excelente projeto perante a comunidade. 
Parabéns, a sociedade só tem a agradecer! 

Muito obrigado! :clap::clap:

