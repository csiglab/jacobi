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


## References

- [jOOQ](https://www.jooq.org/translate/)
- [Source-to-source compiler](https://en.wikipedia.org/wiki/Source-to-source_compiler)
- [SQL2LINQConvertor](https://github.com/ganeshkamath89/SQL2LINQConvertor)
- [Transpiling between any programming languages (Part 1)](https://engineering.mongodb.com/post/transpiling-between-any-programming-languages-part-1)

## TODO

- 
