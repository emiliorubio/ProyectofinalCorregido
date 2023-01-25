Nombre programador: Emilio Rubio Madariaga
Profesor: Federico Osandon
Nombre E-commerce: Amor Propio
Proyecto creado con React Js, presentado como trabajo final de la comision #43545 en CoderHouse.


para correr el proyecto: descargar o clonar repo > npm install > npm start
y ahy corre la aplicacion en el http://localhost:3000 en el navegador.
tambien la puede visualizar en el enlace de netlify https://amorpropio.netlify.app/

este proyecto fue creado con
- Visual Studio Code
- Node.js / version 18.13.0

Dependencias adicionales:

- boxicons para la biblioteca de iconos del proyecto
- react-audio-player esta se uso para integrar los audios en la seccion de podcast 

Orden de archivos
partiendo desde la base tenemos
- Carpeta `src` contiene practicamente el codigo completo y sus funcionalidades, dentro de esta carpeta encontraremos la carpeta
`Components` la cual almacena todos los componentes de la aplicacion, como por ejemplo el Header, Carrito, Footer como asi tambien
    la funcionalidad del proyecto en si como carrito y la interaccion entre secciones del proyecto.
    dentro de esta carpeta se encuentran mas carpetas con subcarpetas como la de `Productos` el cual dentro almacena las diferentes secciones
    y en si dentro de Components estan la mayoria de funcionalidades de este proyecto.

Despues fuera de la carpeta components encontraremos carpetas como `images` en el cual esta almacenado todas las imagenes del proyecto
en la carpeta `assets` encontrara todos los audios que se utilizaron para la seccion de podcast 
y distintas carpetas como `Firebase`, `context`, `screens`, etc
tambien encontraremos dentro de la carpeta `src` algunos archivos .js como la `App.js` , `Data.js` , `index.js` y el `index.css` el cual contiene
practicamente el 95% de estilos de este proyecto

- En la carpeta `Pages` se encuentran las secciones principales de la aplicacion entres las cuales se puede navegar para acceder a las propiedades disponibles.

- En `Firestore` se pueden encontrar los componentes que configuran el acceso a la base de datos de Firestore, la cual almacena los productos mostrados en la tienda, y guarda las ordenes de los usuarios que realizaron una compra.
- Los archivos de estilo `.css` se encuentran en las carpetas correspondientes a cada componente, en adicion al archivo principal `App.css`ubicado en la raiz del proyecto.
- El archivo `App.jsx` es el punto de inicio de la aplicacion de React.
Funcionalidad y caracteristicas
La aplicacion simula la tienda en la nube de un local de computaciòn y tecnologìa llamada "NewComputer". La app cuenta con dos secciones principales, una correspondiente a la pagina de inicio yvisualizacion de productos y la ultima que permite al usuario contactarse con la empresa. Se puede acceder al catalogo de productos, ver las caracteristicas de cada uno de ellos, agregarlo al carrito y realizar la simulacion de una compra.

Se implemento Firestore de Firebase para almacenar la coleccion de productos, a la cual se realizan las consultas necesarias para acceder a la informacion. Una vez confirmada la compra se almacenan en otra coleccion los documentos con la descripcion de la compra realizada.

Se utilizaron diversos componentes para generar el UI y implementar el codigo que permite la funcionalidad de la App. Se uitlizaron los principales recurso de React, tales como los hooks, los contextos, los Routers para la navegacion y diferentes tecnicas de rendering condicionales.

El resultado es un simulador de una tienda con todas las funcionalidades comunes correspondientes a un e-commerce.
