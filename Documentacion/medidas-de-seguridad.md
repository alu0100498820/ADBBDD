# Medidas de Seguridad 

Las medidas de seguridad las podemos catalogar en dos grandes bloques, medidas fisicas y mediadas logicas.

Las medidas fisicas se dividne tambien varios subgrupos tales como seguridad de acceso que se encrgar de controlar quien accede fisicamente a las bases de datos y que no se puedan pasar por alto las medidas de acceso  y obligar a cumplirlas siempre , usando varias mediadas tales como tarjetas de control de acceso, control dactilar o llegando incluso a control de acceso con retina ocular. 

Otro subgrupo de medidas fisicas son las que combaten posibles catastrofes naturales tales como incendios, inundaciones, teremotos, etc.
Con medidas que van desde tener los datos de forma que siempre se puedan recuperar, medidas de extración de oxigeno para apagar un incendio o suelo a disitinto nivel para inundaciones, etc.


Las medidas de seguridad logicas son mas complejas que las fisicas puesto que han de realizarse en las bases de datos de manera que se garantize la seguridad de la base de datos. 

Para ello crearemos perfiles de usuarios en los que cada grupo de usuarios tiene distintos privilegios, con esto conseguimos que un usuario de una base de datos no pueda eliminar una tabla, etc.

Las vistas de las bases de datos son muy importantes puesto que delimitamos el contenido que se muestra de la base de datos a ciertos usuarios.

Una parte importante de la seguridas logica de las bases de datos es la de permitir realizarle auditorias a las bases de datos para ver que datos contiene y de que forma los contine.

Y para el final dejamos la mas importante de las medidas logicas la prevencion de la inyección sql, que basicamente consiste en modificar las consultas sql que se realizan a la bases de datos para obtener que no deberian ser publica. Para evitar estas introduciones podemos aplicar 4 sencillos pasos: 


- Asignación de privilegios mínimos, debe tener los privilegios necesarios, ni mas ni menos.
- Validar los datos introducidos, especifique el tipo de dato de entrada, si son números,asegúrese de que son solo números.
- Utilizar procedimientos almacenados y aceptar los datos del usuario como parámetros en lugar de comandos sql.
- Usar comillas dobles en lugar de simples


 