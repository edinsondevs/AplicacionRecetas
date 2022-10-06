Aplicación Recetas
=============
Es una aplicación para el manejo y visualización recetas de comida 

Scripts de Inicio de la Aplicación
-------------

Para ejecutar correr la aplicación es necesario ejecutar los sigientes comandos en la terminal de windows o git bash:

1. Para levantar el cliente: abrir otra terminal y posicionarse en la carpeta /client y ejecutar el comando `npm run start` + enter

2. Para levantar servidor json: abrir otra terminal y posicionarse en la carpeta api/src/json y ejecutar el comando ```json-server --watch db.json --port 3004```  + enter  

3. Para levantar el servidor: abrir otra terminal y posicionarse en la carpeta /api y ejecutar el comando `npm run start` + enter 

Esta aplicación se abrira en tu navegador en http://localhost:3000

Funcionalidad de la aplicación
-------------

En esta aplicación el usuario podra visualizar una variedad de recetas de comida, que segun su gusto y/o preferencias podrá:

#### :heavy_check_mark:Filtrar Recetas:

Tendra la posibilidad de buscar solo por algun tipo de dieta en particular dentro de las opciones mostradas.

####  :heavy_check_mark:Buscar Recetas:

Tendra la posibilidad de buscar varias recetas introduciendo algun nombre en el buscador y al pulsar el boton search se mostraran las recetas que contemplen el nombre que el usuario introdujo.

#### :heavy_check_mark:Ordenamiento

Tendra la opción de ordenar por nombre y/o score de manera ascendente o descendente.

#### :heavy_check_mark:Detalle de una Receta

Tendra la posibilidad de visualizar el detalle con mucha mas información de la receta al pulsar en el boton Detail que se visualiza en cada card.

#### :heavy_check_mark:Creación de Receta

El usuario tendra la posibilidad de crear recetas si asi lo deseara, pulsando sobre la opción que se visualiza en el navbar de create Recipe, que lo dirijirá al formulario de creación y una vez completado los datos esta se guardara en la base de datos y se podra visualizar luego en la pantalla principal en conjunto con las otras recetas predefinidas.

#### :heavy_check_mark:Borrado

Tendra la opción de eliminar solamente la receta que haya creado el usuario y este boton se habilitara si la receta mostrada fue creada por el usuario.

Tecnologías Utilizadas:
-------------
<div align="center">

<a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="70" height="70"/> </a> 
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="70" height="70"/> </a> 
<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="70" height="70"/> </a> 

<a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="70" height="70"/> </a> 
<a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="70" height="70"/> </a> 
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="70" height="70"/> </a> 

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="70" height="70"/> </a> 
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="70" height="70"/> </a> 
<a href="https://redux.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="70" height="70"/> </a> 

</div>
