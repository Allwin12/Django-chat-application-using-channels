# Django-chat-application-using-channels

install the requirements using

> $ pip install requirements.txt

run the redis server using the following command(This is essentital for the websocket connection, without this the chat application will not work)

> $ docker run -p 6379:6379 -d redis:2.8

migrate the database and makemigrations

> $ python manage.py migrate
> $ python manage.py makemigrations


make sure you have docker installed. Goto http://localhost/chat.
Type in the name of the lobby. Open another one tab and go to the same lobby
