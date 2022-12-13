Configuración bases de datos relacionales o no relacionales

# MYSQL

Agregar estas propiedades en el archivo application.properties:

spring.jpa.hibernate.ddl-auto=update

spring.datasource.url=jdbc:mysql://localhost:3306/<nombre_db>?useSSL=false&serverTimezone=UTC&allowPublicKeyRetrieval=true

spring.datasource.username=root

spring.datasource.password=

spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect


- Se debe agregar de dependencia el MysqlDriver

# H2

Agregar estas propiedades en el archivo application.properties:

spring.datasource.url=jdbc:h2:mem:<nombre_db>

spring.h2.console.enabled=true

# Elasticsearch
Puerto para validar que esta arriba -> http://localhost:9200

Puerto para kibana -> http://localhost:5601
