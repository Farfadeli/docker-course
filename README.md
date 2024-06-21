Cloner le repository comme suit :
```console
foo@bar:~$ git clone https://github.com/Farfadeli/docker-course.git
```
Ensuite naviguer dans le dossier :
```console
foo@bar:~$ cd docker-course
```

Exécuter les deux commandes suivantes à la source du repository
```console
foo@bar:~$ docker-compose build --no-cache
foo@bar:~$ docker-compose up -d
```

Enfin se rendre sur un navigateur et checrher les url suivantes :
```url
http://localhost/
http://localhost/api/
```
