# Image docker java21
FROM mdsol/java21-jdk

WORKDIR /app

# Copie des fichiers de bff/target et redirection vers le dossier /app
COPY ./target/* /app/

# Commandes pour démarrer l'application java
CMD ["java", "-jar", "/app/bff-0.0.1-SNAPSHOT.jar"]