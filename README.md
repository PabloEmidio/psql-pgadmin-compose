# psql-pgadmin-compose
A docker-compose to up a connection between postgresql and pgadmin4 images



# ⚈ Required
This application uses Docker and Docker Compose, to install access the links bellow.

- [Docker](https://docs.docker.com/get-docker/)
- [Docker compose](https://docs.docker.com/compose/install/)

---

# ⚈ How to use

  ``` 
  [example@example]$ git clone https://github.com/PabloEmidio/psql-pgadmin-compose
  [example@example]$ cd psql-pgadmin-compose
  [example@example psql-pgadmin-compose]$ docker-compose up -d
  [example@example psql-pgadmin-compose]$ URL="http://127.0.0.1:8889/login?next=%2F"; xdg-open $URL || sensible-browser $URL || x-www-browser $URL || gnome-open $URL
  ```
---

warning: the pgadmin page usually works after 60s from the "docker-compose up" commad, wait and reload a page until to load
