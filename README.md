**Абстрактный магазин**

Проект написан на Django версии 3.2

-   Дамп базы данных осуществлён в файл 'fixtures.json'.

-   Учётная запись для администрирования (superuser): email - admin@admin.com; password - admin

Документация по проекту:

-   Для запуска проекта необходимо установить зависимости:

        pip install -r requirements.txt

-   Выполнить следующие команды:

        python manage.py migrate
        python manage.py loaddata fixtures.json
        python manage.py runserver