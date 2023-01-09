# Crypto Sandbox API

Backend code for telegram bot 'crypto-sandbox-api'. Allows the user to simulate a crypto wallet with a start balance.  
Based on real exchange rates, buy and sell cryptocurrencies. View your activity data and monitor your balance.

## Technologies used

* **[Python3](https://www.python.org/downloads/)** - A programming language.
* **[PostgreSQL](https://www.postgresql.org/download/)** – Powerful, open source object-relational database system that uses and extends the SQL language.
* **[Flask](https://flask.palletsprojects.com/en/2.2.x/installation/)** - A microframework for Python based on WSGI, Werkzeug and Jinja 2.
* **[Flask-marshmallow](https://www.sqlalchemy.org/download.html)** - Flask-Marshmallow is a thin integration layer for Flask and marshmallow that adds additional features to marshmallow.
* **[SQLAlchemy](https://www.sqlalchemy.org/download.html)** - Python SQL toolkit and Object Relational Mapper.  
* And other requirements which are in the pipfile.

## Local development

The project comes with a basic configuration for start with [Docker](https://www.docker.com/).

> Get the code

```bash
git clone https://github.com/chkvdm/crypto-sandbox-api.git
cd crypto-sandbox-api
```

> Start the app in Docker

```bash
docker-compose up --build
```

## Testing

The project includes a complete postman collection of HTTP requests to all API endpoints. You can imported collection [from](./postman).  

<img width="800" alt="ScreenShot" src="https://user-images.githubusercontent.com/107465582/211280790-edb1570b-a93b-4eaf-bada-b77c55838134.png">

## Authors

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRr0qq7pHt2RAjrMGGKJ_-460bOO8Mpb038TQ&usqp=CAU" height="16"/>  [Vadim Chaiko](https://www.linkedin.com/in/vadim-chaiko-712279127/)

## License

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](https://opensource.org/licenses/MIT)