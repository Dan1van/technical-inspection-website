# Technical Inspection website

Веб-приложение, разработанное для проекта в университете. Основу составляет веб-фреймворк [Flask](https://flask.palletsprojects.com/en/1.1.x/) с дополнениями в виде библиотек: [flask-sqlalchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/), [flask-sequrity](https://pythonhosted.org/Flask-Security/), [flask-admin](https://flask-admin.readthedocs.io/en/latest/) и [flask-mail](https://pythonhosted.org/Flask-Mail/). Также в проекте была использована библиотека [wtforms](https://wtforms.readthedocs.io/en/2.3.x/fields/) для создания форм.

Веб-приложение умеет:
* Регистрировать заявку на ТО транспортного средства. (Можно подключить функцию отправки сообщения на зарегистрированный e-mail с указанным кодом отслеживания);
* Отслеживать статус и данные заявки по трек-коду.

## Установка

Склонируйте git-репозиторий и установите зависимости.

```bash
git clone https://github.com/Dan1van/technical-inspection-website.git
pip install -r requirements.txt
```

## Usage

Запустите файл technical-inspection-website/run.py и перейдите в браузере по адресу: http://127.0.0.1:5000/.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
