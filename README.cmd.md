# Desafío de Libros con Gutendex
## Descripción
Aplicación Java desarrollada para buscar y gestionar información de libros utilizando la API pública de Gutendex. El proyecto implementa un CRUD completo para libros, permitiendo almacenar, consultar, actualizar y eliminar registros en una base de datos MySQL. Además, incluye funcionalidades avanzadas como la obtención de estadísticas de los libros más descargados.

## Funcionalidades
**Consumo de la API Gutendex:** Realiza solicitudes a la API para obtener metadatos de libros.
**CRUD de libros:** Permite crear, leer, actualizar y eliminar registros de libros en la base de datos.
**Manejo de datos JSON:** Procesa los datos JSON obtenidos de la API y los mapea a objetos Java.
**JPA:** Utiliza JPA para interactuar con la base de datos MySQL.
**MySQL:** Base de datos relacional utilizada para almacenar la información de los libros.
**Menú de usuario:** Interfaz de línea de comandos para facilitar la interacción con la aplicación.
**Estadísticas:** Calcula y muestra las estadísticas de los libros más descargados.

## Tecnologías Utilizadas
| Tecnología | Versión | Descripción |
|---|---|---|
| Spring Boot | 3.1.5 | Framework para desarrollo de aplicaciones Java |
| Maven |  | Herramienta de gestión de dependencias |
| MySQL |  | Base de datos relacional |
| JPA |  | Especificación de persistencia de Java |

## Instalación
1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/ricardoleon98/Literalura
   ```
2. **Instalar dependencias:**
   ```bash
   mvn clean install
   ```
3. **Configurar la base de datos:**
   Crear una base de datos MySQL con el nombre especificado en el archivo de propiedades.

## Ejecución
   ```bash
   mvn spring-boot:run
   ```