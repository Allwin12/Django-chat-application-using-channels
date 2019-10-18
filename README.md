# Django-chat-application-using-channels

install the requirements using

> $ pip install requirements.txt

run the redis server using the following command(This is essentital for the websocket connection, without this the chat application will not work)

make sure you have docker installed. 

> $ docker run -p 6379:6379 -d redis:2.8

Migrate the database.

> $ python manage.py migrate

Then makemigrations.

> $ python manage.py makemigrations

Then run the server.

> $ python manage.py runserver


Goto http://localhost/chat. You will see the following screen. 

![lobby name]()


Type in the name of the lobby. Open another one tab and go to the same lobby
