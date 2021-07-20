# 🚨<a href="https://platzi.com/clases/postgresql/" target="_blank">Curso de PostgreSQL</a>🚨
## ✅Class#1⚡️
```Qué aprenderás sobre PostgreSQL```
## ✅Class#2⚡️
```¿Qué es Postgresql?```
* Es un motor de base de datos.
* Open Source.
* Basado en SQL.
* Desde 1986(University of California, Berkeley).
* Permite el uso de PostGiS, para no depender de un backend.
* Cumple con el Estandar:
    * A: Atomicity - Atomicity es la idea de que si una transacción falla, no debe ejecutarse ninguna de las operaciones que contenía.
    * C: Consistency - Con consistencia se refiere a que los datos se deben almacenar en la base de datos en el orden y forma que se creó.
    * I: Isolation - Isolación es la idea de que una transacción no puede tener acceso a los datos de otra transacción durante su ejecución.
    * D: Durability - Durabilidad es la idea de que una transacción debe almacenar los datos durante su ejecución y no se va a perder si la base de datos se daña.
## ✅Class#3⚡️
```Instalación y configuración de la Base de Datos```
```
Vamos a instalar PostgreSQL en nuestra computadora. A continuación veremos el paso a paso y algunos consejos útiles para instalar y configurar correctamente PostgreSQL en nuestro equipo. En éste caso, usaremos Windows, pero los pasosson bastante similares entre los diferentes sistemas operativos.
```
* Forma tradicional:
    1. Primer paso: ir a [https://www.postgresql.org/](https://www.postgresql.org/).
    2. Seleccionar la versión de PostgreSQL que desees instalar.
    3. Next, Next... finish.
* Forma recomendada:
    0. Instalar docker
    1. docker run -d --name postgres -p 5432:5432 -e POSTGRES_PASSWORD=platzi postgres:9.6.6-alpine
    2. docker exec -it postgres psql -U postgres -d postgres
    3. \q
## ✅Class#4⚡️
```Interacción con Postgres desde la Consola```
   * \?: Mostrará una lista de comandos disponibles.
   * \l: Mostrará las bases de datos creadas.
   * \dt: Mostrará las tablas de la base de datos de posgres.
   * \c: Se conecta a la base de datos deseada.
   * \d: Mostrará las columnas de una tabla.
   * \h: Mostrará una lista de comandos SQL disponibles.
   * SELECT version();: Mostrará la versión de PostgreSQL instalada.
   * \g: Mostrar lista de comandos que se estan ejecutando en la base de datos actual.
   * \timing: Mostrará el tiempo que tarda cada comando en ejecutarse.
## 🚧Lecturas recomendadas🚨
* [Qué es el teorema CAP y cómo elegir la base de datos para tu proyecto](https://platzi.com/blog/que-es-el-teorema-cap-y-como-elegir-la-base-de-datos-para-tu-proyecto)
* [PostgreSQL: The world's most advanced open source database](https://www.postgresql.org/)
