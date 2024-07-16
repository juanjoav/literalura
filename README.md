# Challenge Literalura 👩‍💻
## ¡Bienvenido(a) a Literalura! 📚
Literalura es una aplicación que te permite gestionar tu biblioteca personal de libros.

## ¿Qué puedes hacer con Literalura? 📋
- Buscar libros por título o autor.
- Listar libros y autores registrados.
- Buscar autores vivos en un año específico.
- Listar libros por idioma.
- Obtener el top 10 de libros más buscados.
- Generar estadísticas sobre las descargas de libros.

### Instala las dependencias:
`cd literalura`
`mvn install`

### Ejecuta la aplicación:
`mvn spring-boot:run`
¡Empieza a disfrutar de Literalura!

## Estructura del proyecto:
- src/main/java:
  - com.alura.literalura:
    - model: Contiene las clases que representan los datos de libros y autores.
    - repository: Contiene las interfaces y clases que se utilizan para acceder a la base de datos.
    - service: Contiene las clases que implementan la lógica de negocio de la aplicación.
    - principal: Contiene la clase principal de la aplicación.
- src/main/resources: Contiene los archivos de configuración de la aplicación.
- pom.xml: Contiene las dependencias del proyecto.

## Tecnologías utilizadas:
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
