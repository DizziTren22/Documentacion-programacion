Configuración bases de datos relacionales o no relacionales

# MYSQL

Agregar estas propiedades en el archivo application.properties:

spring.jpa.hibernate.ddl-auto=update

spring.datasource.url=jdbc:mysql://localhost:3306/<nombre_db>?useSSL=false&serverTimezone=UTC&allowPublicKeyRetrieval=true

spring.datasource.username=root

spring.datasource.password=

spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect


- Se debe agregar de dependencia el MysqlDriver

