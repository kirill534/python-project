Репозиторий интернет-магазина на Django 3.

Установка (для пользователей операционных систем семейства **MacOs/Linux**):

1. Открыть терминал или консоль и перейти в нужную Вам директорию
2. Прописать команду `git clone git@gitlab.com:PyCoding1/django3-ecommerce.git`
3. Если Вы используете https, то: `git clone https://gitlab.com/PyCoding1/django3-ecommerce.git`
4. Прописать следующие команды:
- `python3 -m venv ДиректорияВиртуальногоОкружения`
- `source ДиректорияВиртуальногоОкружения/bin/activate`
-  Перейти в директорию **django3-ecommerce**
- `pip install -r requirements.txt`
- `python manage.py migrate`
5. Запустить сервер - `python manage.py runserver`
6. Не забудьте создать директорию **media**, куда будут сохраняться изображения для товара

**Создание характеристик для товара**

1. Зайти в админку и создать товар
2. На странице этого же товара в админке будет кнопка "**Создать характеристики для товара**"
3. После этого вы попадете на страницу админки характеристик
4. Сначала необходимо создать характеристику и выбрать категорию, к которой она относится
5. После этого необходимо создать для этой характеристики значение
6. Как только все вышеперечисленное сделали, можно переходить к следующей ссылке - создание характеристики для самого товара.

В проекте необходимо проделать так называемый санитайзинг, т.е у некоторых переменных, точнее у селекторов
в шаблонах переменные названы, мягко говоря, не очень, что может затруднить
изучение кода. Пока что в таком виде. По просьбам трудящихся выкладываю.