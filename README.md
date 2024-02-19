# Fleet Management Software API

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación del proyecto](#5-criterios-de-aceptación-del-proyecto)
* [6. Stack de tecnologías](#6-stack-de-tecnologías)
* [7. Pistas, tips y lecturas complementarias](#7-pistas-tips-y-lecturas-complementarias)
* [8. Funcionalidades opcionales](#8-funcionalidades-opcionales)

***

## 1. Preámbulo

De acuerdo con
[Wikipedia](https://es.wikipedia.org/wiki/Internet_de_las_cosas),
la internet de las cosas (IoT, por sus siglas en inglés)​ es un concepto que
se refiere a una interconexión digital de objetos cotidianos con internet.
Constituye un cambio radical en la calidad de vida de las personas en la
sociedad, ofreciendo nuevas oportunidades en el acceso a
datos, educación, seguridad, asistencia
sanitaria y en el transporte, entre otros campos. Por ejemplo,
en logística y manejo de flotas, se puede hacer seguimiento en
todo momento de la ubicación y las condiciones de vehículos
mediante sensores inalámbricos conectados a internet que envían alertas en
caso de eventualidades (demoras, daños, robos, etc.).

![zach-vessels-utMdPdGDc8M-unsplash](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fthumb.jpg?alt=media)

La IoT también plantea retos como el almacenamiento, análisis y
visualización de la gran cantidad de información que genera.
Se calcula que para el 2025 los dispositivos IoT generen
[79.4 zettabytes](https://www.statista.com/statistics/1017863/worldwide-iot-connected-devices-data-size/)
(1 zettabyte equivale a 1 trillón de gigabytes).
Como desarrolladoras debemos estar al tanto de estos retos y contribuir para
su solución desde nuestra experiencia, conocimiento y ganas de aprender.

## 2. Resumen del proyecto

En este proyecto construirás la API REST de un
[Fleet Management Software](https://en.wikipedia.org/wiki/Fleet_management)
para consultar las ubicaciones de los vehículos de una empresa
de taxis en Beijing, China.

Te entregaremos las ubicaciones de casi 10 mil
taxis. Esperamos que como desarrolladora explores nuevas alternativas y
técnicas para almacenar y consultar esta
información y puedas garantizar la mejor experiencia de usuaria en tu
API REST.

## 3. Objetivos de aprendizaje


Reflexiona y luego marca los objetivos que has llegado a entender y aplicar en tu proyecto. Piensa en eso al decidir tu estrategia de trabajo.

### Java

- [ ] **Modificadores de acesso (public, private, protected)**

- [ ] **Variables**

- [ ] **Uso de condicionales**

- [ ] **Uso de bucles (Loops)**

#### Tipos de data

- [ ] **Primitivos**

- [ ] **Datos primitivos vs no primitivos**

- [ ] **Cadenas**

- [ ] **Arreglos**

#### Colecciones

- [ ] **ArrayList**

- [ ] **HashMap**

- [ ] **HashSet**

#### Testing

- [ ] **JUnit**

- [ ] **Mockito**

#### Spring Framework

- [ ] **Initializr**

  <details><summary>Links</summary><p>

  * [Spring Initializr](https://start.spring.io/)
</p></details>

- [ ] **Spring Boot**

  <details><summary>Links</summary><p>

  * [Spring Boot Reference Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/)
</p></details>

- [ ] **Controladores**

- [ ] **Servicios**

- [ ] **Spring Data JPA**

  <details><summary>Links</summary><p>

  * [Spring Data JPA - Reference Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
</p></details>

- [ ] **Entidad**

- [ ] **Repositorio**

##### Conceptos Core _(Spring Framework)_

- [ ] **Beans**

- [ ] **Inversión de Control**

- [ ] **Anotaciones**

##### Spring Web _(Spring Framework)_

- [ ] **RestController**

- [ ] **RequestMapping**

- [ ] **RequestParam**

##### Testing _(Spring Framework)_

- [ ] **Spring Test**

- [ ] **Hamcrest**

#### Hibernate ORM

- [ ] **Configuración**

- [ ] **Esquema**

- [ ] **Entidad**

- [ ] **Tabla**

- [ ] **Columna**

- [ ] **Identificadores**

- [ ] **Asociaciones**

- [ ] **Colecciones**

- [ ] **Persistencia**

- [ ] **Consultas**

### Python

- [ ] **Variables (declaración, asignación, ámbito)**

  <details><summary>Links</summary><p>

  * [Variables in Python – Real Python (en inglés)](https://realpython.com/python-variables/)
  * [Variables in Python - GeeksforGeeks (en inglés)](https://www.geeksforgeeks.org/python-variables/)
</p></details>

- [ ] **Uso de condicionales (if, elif, ternario)**

  <details><summary>Links</summary><p>

  * [Conditional Statements in Python – Real Python (en inglés)](https://realpython.com/python-conditional-statements/)
</p></details>

- [ ] **Operadores (identidad, aritméticos, comparación etc)**

  <details><summary>Links</summary><p>

  * [Python Operators - GeeksforGeeks (en inglés)](https://www.geeksforgeeks.org/python-operators/)
</p></details>

- [ ] **Docstrings (y su diferencia de comentarios)**

  <details><summary>Links</summary><p>

  * [Docstrings - Python Docs (en inglés)](https://docs.python.org/3/tutorial/controlflow.html#documentation-strings)
</p></details>

- [ ] **Linting (pylint)**

  <details><summary>Links</summary><p>

  * [Pylint - Documentación oficial](https://pylint.pycqa.org/en/latest/)
  * [Linting Python in Visual Studio Code - Visual Studio Code Docs (en inglés)](https://code.visualstudio.com/docs/python/linting)
</p></details>

- [ ] **Serialización (y deserialización)**

  <details><summary>Links</summary><p>

  * [Serialize Your Data With Python – Real Python (en inglés)](https://realpython.com/python-serialize-data/)
</p></details>

#### Tipos de datos

- [ ] **Tipos de datos primitivos (int, float, str, bool)**

  <details><summary>Links</summary><p>

  * [Data Types - Python Docs (en inglés)](https://docs.python.org/3/library/datatypes.html)
  * [Data types in Python (en inglés)](https://www.educative.io/answers/data-types-in-python)
</p></details>

- [ ] **Listas (arrays)**

  <details><summary>Links</summary><p>

  * [Lists - Python Docs (en inglés)](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
  * [Lists and Tuples in Python - Real Python (en inglés)](https://realpython.com/python-lists-tuples/)
</p></details>

- [ ] **Tuples**

  <details><summary>Links</summary><p>

  * [Tuples - Python Docs (en inglés)](https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences)
  * [Lists and Tuples in Python - Real Python (en inglés)](https://realpython.com/python-lists-tuples/)
</p></details>

- [ ] **Dictionaries (Dicts)**

  <details><summary>Links</summary><p>

  * [Dictionaries - Python Docs (en inglés)](https://docs.python.org/3/tutorial/datastructures.html#dictionaries)
  * [Dictionaries in Python - Real Python (en inglés)](https://realpython.com/python-dicts/)
</p></details>

- [ ] **Sets**

  <details><summary>Links</summary><p>

  * [Sets - Python Docs (en inglés)](https://docs.python.org/3/tutorial/datastructures.html#sets)
  * [Sets in Python - Real Python (en inglés)](https://realpython.com/python-sets/)
</p></details>

#### Funciones

- [ ] **Conceptos basicos (params, args, default values, return)**

  <details><summary>Links</summary><p>

  * [Python Functions - GeeksforGeeks (en ingles)](https://www.geeksforgeeks.org/python-functions/)
</p></details>

- [ ] ***args y **kwargs**

  <details><summary>Links</summary><p>

  * [*args and **kwargs in Python - GeeksforGeeks (en inglés)](https://www.geeksforgeeks.org/args-kwargs-python/)
</p></details>

- [ ] **Cierres (closures)**

  <details><summary>Links</summary><p>

  * [Closures - Python Docs (en inglés)](https://docs.python.org/3/reference/datamodel.html#emulating-closures-and-nested-scope)
</p></details>

- [ ] **Funciones lambda**

  <details><summary>Links</summary><p>

  * [Lambda Functions - Python Docs (en inglés)](https://docs.python.org/3/tutorial/controlflow.html#lambda-expressions)
  * [How to Use Python Lambda Functions – Real Python (en inglés)](https://realpython.com/python-lambda/)
</p></details>

- [ ] **Decoradores**

  <details><summary>Links</summary><p>

  * [Decorators - Python Docs (en inglés)](https://docs.python.org/3/glossary.html#term-decorator)
  * [Decorators in Python - Geeks for Geeks (en inglés)](https://www.geeksforgeeks.org/decorators-in-python/)
</p></details>

#### Iteración

- [ ] **Uso de bucles/ciclos (while, for..in)**

  <details><summary>Links</summary><p>

  * [Loops in Python - For, While and Nested Loops - GeeksforGeeks](https://www.geeksforgeeks.org/loops-in-python/)
  * [Loops - Learn Python - Free Interactive Python Tutorial](https://www.learnpython.org/en/Loops)
</p></details>

- [ ] **Comprensión de listas**

  <details><summary>Links</summary><p>

  * [List Comprehension - Python Docs (en inglés)](https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions)
  * [List Comprehension in Python - GeeksforGeeks (en inglés)](https://www.geeksforgeeks.org/list-comprehensions-in-python/)
  * [When to Use a List Comprehension in Python – Real Python (en inglés)](https://realpython.com/list-comprehension-python/)
</p></details>

- [ ] **Técnicas funcionales (map, filter, reduce)**

  <details><summary>Links</summary><p>

  * [Our Guide to Map, Filter, and Reduce Functions in Python - Udacity (en inglés)](https://www.udacity.com/blog/2020/12/our-guide-to-map-filter-and-reduce-functions-in-python.html)
  * [Map, Filter, Reduce - Learn Python - Free Interactive Python Tutorial (en inglés)](https://www.learnpython.org/en/Map%2C_Filter%2C_Reduce)
</p></details>

#### Testing en Python

- [ ] **Pruebas unitarias (unit tests, unittest, pytest)**

  <details><summary>Links</summary><p>

  * [unittest - Python Docs (en inglés)](https://docs.python.org/3/library/unittest.html)
  * [pytest - Documentación oficial](https://docs.pytest.org/en/6.2.x/)
</p></details>

- [ ] **Uso de mocks (y patch)**

  <details><summary>Links</summary><p>

  * [unittest.mock - Python Docs (en inglés)](https://docs.python.org/3/library/unittest.mock.html)
  * [Python Mock Library - Real Python (en inglés)](https://realpython.com/python-mock-library/)
</p></details>

- [ ] **Uso de fixtures**

  <details><summary>Links</summary><p>

  * [pytest fixtures - Documentación oficial](https://docs.pytest.org/en/6.2.x/fixture.html)
</p></details>

#### Modularización

- [ ] **Módulos**

  <details><summary>Links</summary><p>

  * [Módulos - Python Docs (en inglés)](https://docs.python.org/3/tutorial/modules.html)
</p></details>

- [ ] **Paquetes**

  <details><summary>Links</summary><p>

  * [Paquetes - Python Docs (en inglés)](https://docs.python.org/3/tutorial/modules.html#packages)
</p></details>

#### Manejo de dependencias

- [ ] **pip (instalación y uso de paquetes)**

  <details><summary>Links</summary><p>

  * [pip - Python Docs (en inglés)](https://docs.python.org/3/installing/index.html)
</p></details>

- [ ] **Virtual Environment (ambientes virtuales, virtualenv)**

  <details><summary>Links</summary><p>

  * [venv — Creation of virtual environments — Python 3.12.2 documentation (en inglés)](https://docs.python.org/3/library/venv.html)
  * [Python Virtual Environments: A Primer – Real Python (en inglés)](https://realpython.com/python-virtual-environments-a-primer/)
</p></details>

- [ ] **requirements.txt**

  <details><summary>Links</summary><p>

  * [requirements.txt - Documentación oficial](https://pip.pypa.io/en/stable/user_guide/#requirements-files)
</p></details>

#### Flask

##### Rutas _(Flask)_

- [ ] **Decorador de ruta**

  <details><summary>Links</summary><p>

  * [Routing - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/quickstart/#routing)
</p></details>

- [ ] **Función de vista**

  <details><summary>Links</summary><p>

  * [View Functions - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/quickstart/#view-functions)
</p></details>

- [ ] **Reglas de variables (urls dinamica)**

  <details><summary>Links</summary><p>

  * [Variable Rules - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/quickstart/#variable-rules)
</p></details>

##### Request Object _(Flask)_

- [ ] **Argumentos**

  <details><summary>Links</summary><p>

  * [Request - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/quickstart/#accessing-request-data)
</p></details>

- [ ] **Headers (cabeceras)**

  <details><summary>Links</summary><p>

  * [Request - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/quickstart/#accessing-request-data)
</p></details>

##### Response Object _(Flask)_

- [ ] **Partes de la respuesta (status, body, headers)**

  <details><summary>Links</summary><p>

  * [Response - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/quickstart/#about-responses)
</p></details>

- [ ] **jsonify**

  <details><summary>Links</summary><p>

  * [jsonify - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/api/#flask.json.jsonify)
</p></details>

##### Testing en Flask _(Flask)_

- [ ] **Configuración de fixtures**

  <details><summary>Links</summary><p>

  * [Testing - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/testing/#fixtures)
</p></details>

- [ ] **Test Client**

  <details><summary>Links</summary><p>

  * [Testing - Flask Docs (en inglés)](https://flask.palletsprojects.com/en/3.0.x/testing/#sending-requests-with-the-test-client)
</p></details>

#### Django

- [ ] **Views**

  <details><summary>Links</summary><p>

  * [Base views](https://docs.djangoproject.com/en/5.0/ref/class-based-views/base/)
</p></details>

- [ ] **Testing**

  <details><summary>Links</summary><p>

  * [Testing in Django](https://docs.djangoproject.com/en/5.0/topics/testing/)
  * [Testing rest framework](https://www.django-rest-framework.org/api-guide/testing/#testing)
</p></details>

- [ ] **queryset**

  <details><summary>Links</summary><p>

  * [The queryset argument](https://www.django-rest-framework.org/api-guide/relations/#the-queryset-argument)
</p></details>

- [ ] **Filter**

  <details><summary>Links</summary><p>

  * [Filtering](https://www.django-rest-framework.org/api-guide/filtering/)
</p></details>

- [ ] **Order By**

  <details><summary>Links</summary><p>

  * [OrderingFilter](https://www.django-rest-framework.org/api-guide/filtering/#orderingfilter)
</p></details>

- [ ] **URLs (Path, URLconf, urlpatterns)**

  <details><summary>Links</summary><p>

  * [Django URLs](https://tutorial.djangogirls.org/en/django_urls/)
  * [URL dispatcher](https://docs.djangoproject.com/en/5.0/topics/http/urls/)
</p></details>

##### Configuración _(Django)_

- [ ] **Migraciones**

  <details><summary>Links</summary><p>

  * [Migraciones](https://docs.djangoproject.com/es/5.0/topics/migrations/#module-django.db.migrations)
</p></details>

- [ ] **Setup app**

  <details><summary>Links</summary><p>

  * [Installed apps](https://docs.djangoproject.com/es/5.0/ref/settings/#std-setting-INSTALLED_APPS)
</p></details>

##### Modelos _(Django)_

- [ ] **Fields**

  <details><summary>Links</summary><p>

  * [Field types](https://docs.djangoproject.com/en/5.0/topics/db/models/#Fields)
</p></details>

- [ ] **Foreign Key**

  <details><summary>Links</summary><p>

  * [Model field reference](https://docs.djangoproject.com/en/5.0/ref/models/fields/)
</p></details>

##### Rest Framework _(Django)_

- [ ] **Serializers**

  <details><summary>Links</summary><p>

  * [Serializers](https://www.django-rest-framework.org/community/third-party-packages/#serializers)
</p></details>

- [ ] **Pagination**

  <details><summary>Links</summary><p>

  * [Pagination](https://www.django-rest-framework.org/api-guide/pagination/#pagination)
</p></details>

- [ ] **Query params**

  <details><summary>Links</summary><p>

  * [query_params](https://www.django-rest-framework.org/api-guide/requests/#query_params)
</p></details>

- [ ] **ViewSet**

  <details><summary>Links</summary><p>

  * [ViewSet](https://www.django-rest-framework.org/api-guide/viewsets/#viewset)
</p></details>

- [ ] **Apiview**

  <details><summary>Links</summary><p>

  * [GenericAPIView](https://www.django-rest-framework.org/api-guide/generic-views/#genericapiview)
</p></details>

### Programación Orientada a Objetos (OOP)

- [ ] **Clases**

- [ ] **Objetos**

- [ ] **Métodos**

- [ ] **Atributos**

- [ ] **Constructores**

- [ ] **Encapsulamiento**

- [ ] **Abstracción**

- [ ] **Composición**

- [ ] **Interfaces**

- [ ] **Herencia (super, extends, override)**

- [ ] **Lenguaje de Modelado Unificado (UML, class diagrams)**

### Node.js

- [ ] **Instalar y usar módulos con npm**

  <details><summary>Links</summary><p>

  * [Sitio oficial de npm (en inglés)](https://www.npmjs.com/)
</p></details>

- [ ] **Configuración de package.json**

  <details><summary>Links</summary><p>

  * [package.json - Documentación oficial (en inglés)](https://docs.npmjs.com/files/package.json)
</p></details>

- [ ] **Configuración de npm-scripts**

  <details><summary>Links</summary><p>

  * [scripts - Documentación oficial (en inglés)](https://docs.npmjs.com/misc/scripts)
</p></details>

- [ ] **process (env, argv, stdin-stdout-stderr, exit-code)**

  <details><summary>Links</summary><p>

  * [Process - Documentación oficial (en inglés)](https://nodejs.org/api/process.html)
</p></details>

- [ ] **File system (fs, path)**

  <details><summary>Links</summary><p>

  * [File system - Documentación oficial (en inglés)](https://nodejs.org/api/fs.html)
  * [Path - Documentación oficial (en inglés)](https://nodejs.org/api/path.html)
</p></details>

### SQL

- [ ] **Creación y modificación de tablas**

  <details><summary>Links</summary><p>

  * [SQL CREATE TABLE Statement - w3schools (en inglés)](https://www.w3schools.com/sql/sql_create_table.asp)
  * [CREATE TABLE Statement - PostgreSQL Docs (en inglés)](https://www.postgresql.org/docs/9.1/sql-createtable.html)
  * [ALTER TABLE Statement - PostgreSQL Docs (en inglés)](https://www.postgresql.org/docs/9.1/sql-altertable.html)
</p></details>

- [ ] **Operaciones CRUD (Create-Read-Update-Delete)**

  <details><summary>Links</summary><p>

  * [INSERT](https://www.postgresql.org/docs/9.5/sql-insert.html)
  * [SELECT](https://www.postgresql.org/docs/9.5/sql-select.html)
  * [UPDATE](https://www.postgresql.org/docs/9.1/sql-update.html)
  * [DELETE](https://www.postgresql.org/docs/8.1/sql-delete.html)
</p></details>

- [ ] **Borrado de tablas o bases de datos enteras con DROP**

  <details><summary>Links</summary><p>

  * [DROP TABLE](https://www.postgresql.org/docs/8.2/sql-droptable.html)
  * [DROP DATABASE](https://www.postgresql.org/docs/8.2/sql-dropdatabase.html)
</p></details>

### Bases de datos

- [ ] **Modelado de datos**

- [ ] **Conexión**

- [ ] **Índices y limitaciones**

### PostgreSQL

- [ ] **Tipos de datos**

  <details><summary>Links</summary><p>

  * [Chapter 8. Data Types - Docs (en inglés)](https://www.postgresql.org/docs/14/datatype.html)
</p></details>

- [ ] **Índices**

  <details><summary>Links</summary><p>

  * [Chapter 11. Indexes - Docs (en inglés)](https://www.postgresql.org/docs/14/indexes.html)
</p></details>

## 4. Consideraciones generales

* Este proyecto se debe "resolver" en duplas.
* El rango de tiempo estimado para completar el proyecto es de 4 a 6 Sprints.

## 5. Criterios de aceptación del proyecto

Nuestra cliente ha instalado dispositivos GPS en sus taxis.
Estos dispositivos utilizan señales satelitales para determinar
con precisión las coordenadas geográficas del taxi.

Nuestra clienta requiere:

1. Cargar la información de archivos SQL a una
base de datos Postgresql.
2. Desarrollar una API REST que permita consultar, mediante
peticiones HTTP, la información almancenada en la base de datos.

### Definición del producto

El [_Product Owner_](https://www.youtube.com/watch?v=r2hU7MVIzxs&t=202s)
nos presenta este _backlog_ que es el resultado de su trabajo con la clienta
hasta hoy.

***

#### [Historia de usuario 1] Cargar información a base de datos

Yo, como desarrolladora, quiero cargar la información almacenada hasta ahora en
[archivos sql](https://drive.google.com/file/d/1T5m6Vzl9hbD75E9fGnjbOiG2UYINSmLx/view?usp=drive_link)
en una base de datos PostgreSQL, para facilitar su consulta y análisis.

##### Criterios de aceptación

* Se debe tener en cuenta el siguiente diagrama para la implementación de las
relaciones entre las tablas

![mer](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fsql-diagram.png?alt=media)

* La tabla de _trajectories_ se debe crear con el "id" que se incremente
automáticamente (SERIAL) para poder insertar los valores sin necesidad
de especificar un identificador

##### Definición de terminado

* La base de datos tiene creada la tabla de taxis
* La tabla de taxis tiene cargada la data de taxis
* La base de datos tiene creada la tabla de trayectorias
* La tabla de taxis tiene cargada la data de trayectorias

***

##### [Historia de usuario 2] Endpoint listado de taxis

Yo como clienta de la API REST requiero un _endpoint_ para
listar todos los taxis.

##### Criterios de aceptación

* El _endpoint_ responde para cada taxi: id y placa.
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

#### [Historia de usuario 3] Endpoint historial de ubicaciones

Yo como clienta de la API REST requiero un _endpoint_ para
consultar todas las ubicaciones de un taxi dado el id y una fecha.

##### Criterios de aceptación

* El _endpoint_ responde con el id del taxi y una fecha mostrando
  la siguiente información: latitud, longitud y timestamp (fecha y hora).
* El _endpoint_ paginamos los resultados para asegurar que las
  respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

#### [Historia de usuario 4] Endpoint última ubicación

Yo como clienta de la API REST requiero un _endpoint_ para
consultar la última ubicación reportada por cada taxi.

##### Criterios de aceptación

* El _endpoint_ responde para cada taxi la siguiente información:
id, placa, latitud, longitud y timestamp (fecha y hora).
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

## 6. Stack de tecnologías

Puedes implementar este proyecto en JavaScript, Python o Java.

* [NodeJs](./docs/stack-node.md)
* [Java](./docs/stack-java.md)
* [Python](./docs/stack-python.md)

## 7. Pistas, tips y lecturas complementarias

### Modelamiento de datos

La base de datos recomendada para tu aplicación es PostgreSQL. Te
recomendamos usar [vercel Postgresql](https://vercel.com/docs/storage/vercel-postgres)
para que no tengas que instalar PostgreSQL en tu computadora.

Una vez tengas acceso a una instancia de PostgreSQL, deberás crear tablas en
tu base de datos para almacenar la información entregada. Te recomendamos
entonces crear dos tablas, una para almacenar la información de taxis y otra
para almacenar la información de ubicaciones. Deberás definir las columnas
de cada tabla de acuerdo a la información entregada.

Puedes crear una tabla en PostgreSQL usando
[SQL](https://www.postgresqltutorial.com/postgresql-create-table/).

### Definir endpoints de API

Deberás definir y documentar los endpoints de tu API.
Debes usar [Swagger](https://swagger.io/) para esto.

Para una API REST debes definir para cada endpoint entre otras cosas el
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).

Por ejemplo, en la siguiente figura se define un endpoint para consultar la
información de los taxis en la aplicación. El método del endpoint es _GET_,
la url es _/taxis_. Recibe un parámetro _query_, retorna la información con
_código HTTP_ 200 en formato json gracias al _header_
`Content-type` con valor `application/json`.

![Ejemplo Endpoint API Rest](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fexample-endpoint-api-rest.png?alt=media)

## 8. Funcionalidades opcionales

Si completaste todas las funcionalidades del proyecto te invitamos a trabajar en
las [funcionalides opcionales](./docs/extension.md)
