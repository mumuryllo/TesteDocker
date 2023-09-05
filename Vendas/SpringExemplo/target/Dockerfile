# Use a imagem base do OpenJDK 11
FROM openjdk:17

# Exponha a porta em que a aplicação Spring Boot será executada (substitua pela porta correta)
EXPOSE 8080

# Copie o arquivo JAR do sistema de arquivos local para o contêiner
COPY spring-boot-docker.jar /target/spring-boot-docker.jar

# Defina o diretório de trabalho dentro do contêiner
WORKDIR /target

# Comando para iniciar a aplicação Spring Boot
CMD ["java", "-jar", "spring-boot-docker.jar"]