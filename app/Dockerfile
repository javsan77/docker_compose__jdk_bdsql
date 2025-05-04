#app/Dockerfile
FROM openjdk:17-jdk-slim

# Crea un directorio para la app
WORKDIR /app

# Copia el JAR
COPY sirh-2.0.jar .

#Comando para ejecutar el jar
CMD ["java", "-jar", "sirh-2.0.jar"]

