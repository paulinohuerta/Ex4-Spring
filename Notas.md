13-02-2017
==========
Vamos a ampliar la funcionalidad de la aplicación completando la CRUD con los pasos definidos en Github(issues) y en habitica.
En bd correrá con mysql.

14-02-2017
==========
Conseguido hoy: 
+ Los botones derivan al método en cuestión. (Salvo el de regresar atrás).
+ Ya no depende de Redis, sino que toma los datos directamente de mysql (incluso los de la pantalla que sólo lista las id).

Problemas:
~~Problemas para conseguir que jdbcTemplate devuelva un entero con las filas afectadas (previsiblemente 1)~~.
  ~~Probaremos sin comprobar si devuelve int~~.
    Corregido Delete.
