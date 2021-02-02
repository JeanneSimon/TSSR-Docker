# Serveur web Apache avec Dockerfile

## Comment lancer le serveur

Il vous faut Docker, et build l'image dans le répertoire du serveur : 
```bash
    docker build -t serveur-apache .
```

Après construction de l'image, elle est présente dans vos images locales :
```bash
    docker images
```