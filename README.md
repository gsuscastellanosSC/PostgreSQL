# 馃毃<a href="https://platzi.com/clases/postgresql/" target="_blank">Curso de PostgreSQL</a>馃毃
## 鉁匔lass#1鈿★笍
```Qu茅 aprender谩s sobre PostgreSQL```
## 鉁匔lass#2鈿★笍
```驴Qu茅 es Postgresql?```
* Es un motor de base de datos.
* Open Source.
* Basado en SQL.
* Desde 1986(University of California, Berkeley).
* Permite el uso de PostGiS, para no depender de un backend.
* Cumple con el Estandar:
    * A: Atomicity - Atomicity es la idea de que si una transacci贸n falla, no debe ejecutarse ninguna de las operaciones que conten铆a.
    * C: Consistency - Con consistencia se refiere a que los datos se deben almacenar en la base de datos en el orden y forma que se cre贸.
    * I: Isolation - Isolaci贸n es la idea de que una transacci贸n no puede tener acceso a los datos de otra transacci贸n durante su ejecuci贸n.
    * D: Durability - Durabilidad es la idea de que una transacci贸n debe almacenar los datos durante su ejecuci贸n y no se va a perder si la base de datos se da帽a.
## 鉁匔lass#3鈿★笍
```Instalaci贸n y configuraci贸n de la Base de Datos```
```
Vamos a instalar PostgreSQL en nuestra computadora. A continuaci贸n veremos el paso a paso y algunos consejos 煤tiles para instalar y configurar correctamente PostgreSQL en nuestro equipo. En 茅ste caso, usaremos Windows, pero los pasosson bastante similares entre los diferentes sistemas operativos.
```
* Forma tradicional:
    1. Primer paso: ir a [https://www.postgresql.org/](https://www.postgresql.org/).
    2. Seleccionar la versi贸n de PostgreSQL que desees instalar.
    3. Next, Next... finish.
* Forma recomendada:
    1. Instalar docker
    2. docker run -d --name postgres -p 5432:5432 -e POSTGRES_PASSWORD=platzi postgres:9.6.6-alpine
    3. docker exec -it postgres psql -U postgres -d postgres
    4. \q
## 鉁匔lass#4鈿★笍
```Interacci贸n con Postgres desde la Consola```
## 鉁匔lass#5鈿★笍
```PgAdmin: Interacci贸n con Postgres desde la Interfaz Gr谩fica```
## 馃毀Bash馃毃
* \?: Mostrar谩 una lista de comandos disponibles.
* \l: Mostrar谩 las bases de datos creadas.
* \dt: Mostrar谩 las tablas de la base de datos de posgres.
* \c: Se conecta a la base de datos deseada.
* \d: Mostrar谩 las columnas de una tabla.
* \h: Mostrar谩 una lista de comandos SQL disponibles.
* SELECT version();: Mostrar谩 la versi贸n de PostgreSQL instalada.
* \g: Mostrar lista de comandos que se estan ejecutando en la base de datos actual.
* \timing: Mostrar谩 el tiempo que tarda cada comando en ejecutarse.
## 馃毀Lecturas recomendadas馃毃
* [pgAdmin - PostgreSQL Tools](https://www.pgadmin.org/)
* [Qu茅 es el teorema CAP y c贸mo elegir la base de datos para tu proyecto](https://platzi.com/blog/que-es-el-teorema-cap-y-como-elegir-la-base-de-datos-para-tu-proyecto)
* [PostgreSQL: The world's most advanced open source database](https://www.postgresql.org/)