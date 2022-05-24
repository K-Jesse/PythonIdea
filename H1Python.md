# pw1 Hello DJ A

## A. Asenna Django-kehitysympäristö.

Aloitetaan asentamalla tarpeelliset ohjelmat.(Näihin hain apua Teron artikkelista [Django 4 Instant Customer Database Tutorial](https://terokarvinen.com/2022/django-instant-crm-tutorial/)) ![image](https://i.imgur.com/yQWo2xq.jpg)
Seuraavaksi kokeillaan toimiiko kyseinen django asennus. Tehdään siis uusi projekti. Ajetaan `django-admin startproject jesseco` ja siirrytään projektiin `cd jesseco`. Kokeillaan vielä, että käynnistyykö dev serveri ajamalla `./manage.py runserver` ja näyttäisi toimivan kuten seuraavasta kuvasta voi päätellä. ![image](https://i.imgur.com/XEYUtiv.jpg)
## B. (Update: tämä kohta muutettiin vapaaehtoiseksi) Lisää omia kenttiä malliin.

## C. Tee lisää käyttäjiä, jotka saavat kirjautua Djangon adminiin

Otetaan admin käyttöön tekemällä migraatiot `./manage.py makemigrations` `./manage.py migrate` ja luomalla superuser `./manage.py createsuperuser`. Käynnistetään seuraavaksi vielä palvelin uudestaan ja katotaan päästäänkö käsiksi admin paneeliin uusilla tunnuksilla. ![image](https://i.imgur.com/lLtR9CY.jpg) Näyttäisi toimivan.

## Lähteet

[Django 4 Instant Customer Database Tutorial](https://terokarvinen.com/2022/django-instant-crm-tutorial/))
[Python Web Service From Idea to Production](https://terokarvinen.com/2021/python-web-service-from-idea-to-production-2022/#pw1-hello-dj-a)
[Markdown](https://commonmark.org/help/)
[Publish Your Project with GitHub](https://terokarvinen.com/2016/publish-your-project-with-github/?fromSearch=git)