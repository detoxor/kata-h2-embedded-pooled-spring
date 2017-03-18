# Kata H2 + Spring používající nativní přístup a je poolován
Nejjednodušší integrace H2 a Spring používající nativní přístup konfigurace H2 via xml s tím, že jdbc-template je nyní poolována - formou ukázky/příkladu, viz odkaz: [URL2].

Projekt lze snadno spustit:

```sh
mvn clean package && mvn exec:java
```

## Zdroje
+ (URL0) [Connection using JDBC, official](http://h2database.com/html/tutorial.html#connecting_using_jdbc)
+ (URL1) [Data access with JDBC](https://docs.spring.io/spring/docs/current/spring-framework-reference/html/jdbc.html)
+ (URL2) [Embedded database support](https://docs.spring.io/spring/docs/current/spring-framework-reference/html/jdbc.html#jdbc-embedded-database-support)
+ (URL3) [Spring embedded database examples](http://www.mkyong.com/spring/maven-spring-jdbc-example/)
+ (URL4) [Official page Apache Commons DBCP](https://commons.apache.org/proper/commons-dbcp/)
