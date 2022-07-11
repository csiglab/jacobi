# jacobi
jacobi - Es un traductor de sentencias sql a sigef.

![Tracuccion](https://idiomasgalion.com/wp-content/uploads/2020/09/traduccion.png)

Example:

```sql
SELECT * 
FROM SG_DATOS
```

```java
StringBuilder sql = new StringBuilder();
sql.append( ConstantesSQL.SELECT  )
.append("*")
.append(ConstantesSQL.FROM),
.append(MapDBdatos.TABLA);
```

¿Cómo resolver el problema?
- Formatear la sentencia SQL, tokenizar, reemplazar.

He encontrado una solución:

- [jOOQ](https://www.jooq.org/translate/)

## TODO

- Descargar y utilizar jOOQ,
- Hacer app web imitando a (SQL Translation)[https://www.jooq.org/translate/]
