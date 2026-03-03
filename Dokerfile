# Utiliser une image de base légère
FROM alpine:latest

# Mettre à jour et installer quelques outils de base
RUN apk add --no-cache curl

# Créer un répertoire de travail
WORKDIR /app

# Créer un fichier simple
RUN echo "Hello from Docker!" > hello.txt

# Commande par défaut
CMD ["cat", "hello.txt"]