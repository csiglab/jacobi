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
- [Your Program as a Transpiler by Edoardo Vacchi](https://www.youtube.com/watch?v=TWfigR9wGsA)
- [sqlflow](https://github.com/sql-machine-learning/sqlflow)
- [Trino Sql Parser](https://github.com/trinodb/trino/tree/018e75c665ae08a7dac9417332daa1ff43cfe88f/core/trino-parser)
- [ANTLR SQL Grammars](https://github.com/antlr/grammars-v4/tree/master/sql)
- [Java Parser](https://javaparser.org/)
- [c2go](https://github.com/elliotchance/c2go)
- [JavaScript Transpilers: What They Are And Why We Need Them](https://www.digitalocean.com/community/tutorials/javascript-transpilers-what-they-are-why-we-need-them)
- [sqlglot](https://github.com/tobymao/sqlglot)
- [Transpiler](https://devopedia.org/transpiler)

## TODO

- 
