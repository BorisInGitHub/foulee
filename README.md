# Foulee
Site web des foulées



## Démarrage sous linux

Via `docker - dockerCompose`

* https://docs.docker.com/compose/wordpress/
* https://joshmobley.net/writing/2017/04/09/easy-wordpress-migration-with-docker.html
* https://codeable.io/wordpress-developers-intro-to-docker-part-two/

```bash
cd dockerCompose/
docker-compose up
```

Clean
```bash
docker-compose down --volumes
```

Puis aller sur le site http://localhost:8000, la configuration se fait via http://localhost:8000/wp-admin/index.php


Configuration `wordpress`
username `foulees_admin`
password `^dRI)$&WjJ7jGHc0BS`
mail `boris.reynard@gmail.com`


Images:
https://pixabay.com/fr/
