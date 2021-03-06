# Reto de código N° 3

## Descripción del Proyecto:

El proyecto consiste en la elaboración del sketch del dashboard de Laboratoria. Una herramienta utilizada por profesores, training managers, directores y gerentes de Laboratoria para ver rápidamente qué está pasando en el salón de clases.

##Objetivo
Desarrollar el prototipo de un dashboard para los trending managers de Laboratoria.

##Desarrollo
Para la resolución del reto seguimos las estapas de DCU(Diseño Centrado en el Usuario).

##Etapas DCU (Diseño Centrado en el Usuario):

A. Descubrimiento e Investigación
Actividades:
1.- Entrevista con usuarios.
El usuario entrevistado fue Alejandra, trainding manager de Laboratoria-Lima.
Ella acotó que necesitaba una palataforma sencilla de utilizar y que brindara información sobre el desempeño de las alumnas, de todas las cedes.
Donde por defecto se muestre la última data de la sede en la que ella labora. 

B. Síntesis y definición

Actividades:
1.- Definición del problema: 
Los training managers de Laboratoria no cuentan con una plataforma donde tener la información detallada de las estudiantes (Notas, número de alumnas, ranking)


2.- Definición de User persona:

Nombre: Martha Rivas
Edad: 27 años.
Profesión: Training Manager.
Frase de vida: "Lo principal es una buena organización"
Escenario: Martha trabaja hace 3 años en Laboratoria. Durante los primeros años han manejado la data de las alumnas a través de documentos de excel, pero a la larga se iban acumulando. Como una persona a la que le gusta mucho el orden, se le hizo difícil sintetizar esa informació. Además de que la manera de mostrar los datos era confusa.

Metas:
- Crear un proyecto de emprendimiento social.
- Trabajar con estudiantes de otros países.
- Generar un cambio en la educación de su país.

Frustracciones:

- Los datos que se acumulan todos los días y no logra sintetizarlos.
- La presión por los el ritmo de trabajo.

Necesidades :

- Una plataforma donde pueda obtener toda la información que necesita de primera mano.
- Un sistema que le ayude a organizarse.
- Una plataforma que le ayude a mantenerse comunicada con los otros training managers. 


C. Prototipado:

### Primera ventana:

#### Descripción:

Ventana de inicio de sesión y/o registro.


![Dashboard-0](assets/images/dashboard-0.jpg)

En esta primera vetana se le pide al usuario ingresar su nombre de usuario y contraseña para acceder. También tiene la opción de que se guarde su contraseña, para no tener que ingresarla todas las veces. Hay una opción debajo del botón de ingresar, en caso de que el usuario haya olvidado su contraseña y también hay un enlace para registrarse. 
En la parte inferior hay un footer con navegación global, que Laboratoria mantiene en su página principal.


## Segunda ventana:

#### Descripción:

Ventada de saludo al usuario.


![Dashboard-1](assets/images/dashboard-1.jpg)

Una vez que el usuario ha ingresado a su cuenta, se abre otra ventana donde un círculo va apareciendo conforme a la velocidad con que carga la página. Cuando se llega a 100% se completa el círculo y aparece el texto "Bienvenido", más el nombre del usuario. Luego de unos segundos de transición se muestra la siguiente ventana.


## Tercera ventana:

#### Descripción:

Muestra las opciones generales y el perfil del usuario.

![Dashboard-2](assets/images/dashboard-2.jpg)

La tercera ventana muestra en la parte superior que está en "Dashboard", la opción "Workspace" es para que el usuario pueda insertar su propia gráfica y la opción "Configuración", para modificar su perfil.

El perfil del usuario al lado izquierdo, contiene las siguientes opciones:

1. Home: Lleva al inicio de la página.

2. Sedes: Se despliegan las opciones de cada sede de Laboratoria.

3. Estadísticas: Acceso directo a estadísticas.

4. Tablas: Acceso directo a las tablas de cada página.

5. Calendario: Un calendario personalizado.

6. Mensajes: Mensajes que pueden mandarse entre usuarios.

7. Log out: Salir de su cuenta.

En la parte central de la ventana están las opciones generales.

Cuando el usuario selecciona una sede en específico, el fondo de las opciones generales cambia de color y de inmediato los datos devueltos serán de esa sede en específico. 


## Cuarta ventana:

### Estadísticas de estudiantes

#### Descripción:

Muestra las estadísticas generales de las estudiantes.


![Dashboard-3](assets/images/dashboard-3.jpg)

#### Header:

1. El logo de Laboratoria que lleva al usuario a la página principal de Laboratoria.

2. El título de la sección en que se encuentra el usuario.

3. Un elemento search de búsqueda directa.

4. Un ícono navegable que indica al usuario si tiene mensajes.

5. La imagen y nombre del usuario.



#### Navegación local 

Se mantiene en cada ventana que se abre cuando el usuario da "click" en alguna opción general:

1. Menú hamburguesa que al activarse muestra el perfil del usuario.

2. Cifra de número total de estuadiantes actuales.

3. Cifra del número total actual de estuadiantes egresadas.

4. Cifra del número total actual de estuadiantes de UX.

5. Cifra del número total actual de estuadiantes de Front End.

6. Un botón "Generaciones" el cual despliega opciones de selección de la generación de la cual se quiere ver la data. 

#### Opciones:

La data varía si el usuario cambia a alguna generación. 

1. Alumas por año.

2. Alumnas por especialidad.

3. Alumnas que desertaron. 


## Quinta ventana:

### Notas por sprint

#### Descripción:

Muestra las estadísticas de las notas por Sprint y por cada unidad de las estudiantes.


![Dashboard-4](assets/images/dashboard-4.jpg)

#### Header:

1. El logo de Laboratoria que lleva al usuario a la página principal de Laboratoria.

2. El título de la sección en que se encuentra el usuario.

3. Un elemento search de búsqueda directa.

4. Un ícono navegable que indica al usuario si tiene mensajes.

5. La imagen y nombre del usuario.



#### Navegación local 

Se mantiene en cada ventana que se abre cuando el usuario da "click" en alguna opción general:

1. Menú hamburguesa que al activarse muestra el perfil del usuario.

2. Cifra del número total de estuadiantes actuales.

3. Cifra del número total actual de estuadiantes egresadas.

4. Cifra del número total actual de estuadiantes de UX.

5. Cifra del número total actual de estuadiantes de Front End.

6. Un botón "generaciones" el cual despliega opciones de selección de la generación de la cual se quiere ver la data. 

#### Opciones:

La data varía si el usuario cambia a alguna generación. 

1. Promedio de notas general.

2. Alumnas que pasan el criterio mínimo de evaluación.

3. Botón desplegable que permite filtrar por sprint y la vez, cada sprint por unidad.


## Sexta ventana:

#### Descripción:

Muestra las estadísticas de las notas de Habilidades Socio Emocionales de las estudiantes.

### Notas de HSE

![Dashboard-5](assets/images/dashboard-5.jpg)

#### Header:

1. El logo de Laboratoria que lleva al usuario a la página principal de Laboratoria.

2. El título de la sección en que se encuentra el usuario.

3. Un elemento search de búsqueda directa.

4. Un ícono navegable que indica al usuario si tiene mensajes.

5. La imagen y nombre del usuario.



#### Navegación local 

Se mantiene en cada ventana que se abre cuando el usuario da "click" en alguna opción general:

1. Menú hamburguesa que al activarse muestra el perfil del usuario.

2. Cifra del número total de estuadiantes actuales.

3. Cifra del número total actual de estuadiantes egresadas.

4. Cifra del número total actual de estuadiantes de UX.

5. Cifra del número total actual de estuadiantes de Front End.

6. Un botón "generaciones" el cual despliega opciones de selección de la generación del cual se quiere ver la data. 

#### Opciones:

La data varía si el usuario cambia a alguna generación. 

1. Promedio de notas general.

2. Alumnas que pasan el criterio mínimo de evaluación.

3. Botón desplegable que permite filtrar por sprint y la vez, cada sprint por unidad.

4. Botón desplegable que permite filtrar por cada área de evaluación del HSE.



## Séptima ventana:

#### Descripción:

Muestra las estadísticas de las notas tecnicas de las estudiantes.

### Notas Técnicas

![Dashboard-6](assets/images/dashboard-6.jpg)

#### Header:

1. El logo de Laboratoria que lleva al usuario a la página principal de Laboratoria.

2. El título de la sección en que se encuentra el usuario.

3. Un elemento search de búsqueda directa.

4. Un ícono navegable que indica al usuario si tiene mensajes.

5. La imagen y nombre del usuario.



#### Navegación local 

Se mantiene en cada ventana que se abre cuando el usuario da "click" en alguna opción general:

1. Menú hamburguesa que al activarse muestra el perfil del usuario.

2. Cifra del número total de estuadiantes actuales.

3. Cifra del número total actual de estuadiantes egresadas.

4. Cifra del número total actual de estuadiantes de UX.

5. Cifra del número total actual de estuadiantes de Front End.

6. Un botón "generaciones" el cual despliega opciones de selección de la generación de la cual se quiere ver la data. 

#### Opciones:

La data varía si el usuario cambia a alguna generación. 

1. Promedio de notas general.

2. Alumnas que pasan el criterio mínimo de evaluación.

3. Botón desplegable que permite filtrar por sprint y la vez, cada sprint por unidad.

4. Botón desplegable que permite filtrar por cada tipo de evaluación técnica. 


## Octava ventana:

#### Descripción: 

Muestra las estadísticas a nivel general, es decir, las cuatro sedes juntas.

### Global

![Dashboard-7](assets/images/dashboard-7.jpg)

#### Header:

1. El logo de Laboratoria que lleva al usuario a la página principal de Laboratoria.

2. El título de la sección en que se encuentra el usuario.

3. Un elemento search de búsqueda directa.

4. Un ícono navegable que indica al usuario si tiene mensajes.

5. La imagen y nombre del usuario.



#### Navegación local 

Se mantiene en cada ventana que se abre cuando el usuario da "click" en alguna opción general:

1. Menú hamburguesa que al activarse muestra el perfil del usuario.

2. Cifra del número total de estuadiantes actuales.

3. Cifra del número total actual de estuadiantes egresadas.

4. Cifra del número actual total de estuadiantes de UX.

5. Cifra de número total actual de estuadiantes de Front End.

6. Un botón "generaciones" el cual despliega opciones de selección de la generación de la cual se quiere ver la data. 

#### Opciones:

La data de varía si el usuario cambia a alguna generación. 

En este caso de acuerdo a la opción que el usuario elija, volvería a mostrar las ventanas correspondientes a cada opción.

1. Estadísticas de estudiantes (de todas las sedes)

2. Notas HSE (de todas las sedes)

3. Notas por Sprint (de todas las sedes)

4. Notas técnicas (de todas las sedes).

5. Comparar las estadísticas. 


## Novena ventana:

### Comparar

![Dashboard-8](assets/images/dashboard-8.jpg)

#### Descripción:

Muestra la comparación de las estadísticas entre sedes, generaciones de estudiantes y sprints. 

#### Header:

1. El logo de Laboratoria que lleva al usuario a la página principal de Laboratoria.

2. El título de la sección en que se encuentra el usuario.

3. Un elemento search de búsqueda directa.

4. Un ícono navegable que indica al usuario si tiene mensajes.

5. La imagen y nombre del usuario.



#### Navegación local 

Se mantiene en cada ventana que se abre cuando el usuario da "click" en alguna opción general:

1. Menú hamburguesa que al activarse muestra el perfil del usuario.

2. Cifra del número total de estuadiantes actuales.

3. Cifra del número total actual de estuadiantes egresadas.

4. Cifra del número total actual de estuadiantes de UX.

5. Cifra de número total actual de estuadiantes de Front End.

6. Un botón "generaciones" el cual despliega opciones de selección de la generación de la cual se quiere ver la data. 

#### Opciones:

La data de varía si el usuario cambia a alguna generación. 

1. Se dan tres opciones para comparar: notas generales, nostas HSE y notas técnicas.

2. Al dar "click" en cualquiera de esas tres opciones, se abren tres botones desplegables: Sede, Generación y Sprint. Cada uno de ellos con sus respectivas opciones para que el usuario elija que quiere comparar.  

3. Una vez que el usuario ha seleccionado por ejemplo: "Notas Hse - Sede - Lima y Arequipa", se mostrará la estadística comparativa de acuerdo a lo seleccionado.
