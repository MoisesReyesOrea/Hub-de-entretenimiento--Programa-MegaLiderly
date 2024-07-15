# Hub De Entretenimiento Mega - Liderly

## 1. Descripción
Este repositorio cuenta con una app web realizada con [Angular CLI](https://github.com/angular/angular-cli) version 16.2.14. Se trata de una aplicacion frontend para la visualizacion de peliculas, series, deporte y más en formato de streaming.

### Objetivo
El objetivo es crear una aplicación full stack siendo este proyecto la parte del frontend que sera conectada a un backend para la visualizacion de archivos multimedia.

## 2. Requerimientos técnicos:
NODE: Se debe instalar NODE JS v18 en el sistema operativo  
ANGULAR/CLI: Para poder manipular el proyecto con la interfaz de Angular v16  
GIT: Debe tener Instalado GIT  

## 3. ¿Cómo ejecutar la aplicación?

-- Cloná el repositorio haciendo git clone https://github.com/MoisesReyesOrea/Hub-de-entretenimiento--Programa-MegaLiderly.git  
-- Instalá de los paquetes y módulos requeridos: npm install  
-- Abre cualquier terminal en la direccion dentro de la carpeta del proyecto y ejecuta el comando 'npm start' o 'ng serve' o bien hacerlo desde un editor de código.  
-- Abre algún navegador y ve a la dirección `http://localhost:4200/` la aplicación se ejecutará en ese enlace.  

## 4. Explicación
![ejecucion](https://github.com/user-attachments/assets/1fb79272-7f6f-4588-aa74-1d883f188433)

Para correr la aplicación se ejecuta el comando 'npm start', esta imágen muestra el server en ejecucion para el funcionamiento de la aplicación.


![inicio-de-sesion](https://github.com/user-attachments/assets/e65a4703-e9eb-452d-bf50-f32066e4c494)

Página de inicio de sesión, los campos de ingreso de datos cuentan con validaciones que deberán ser cumplidas para habilitar el boton de inicio de sesión y así entrar a la aplicación

![home-page](https://github.com/user-attachments/assets/c8a196d0-9597-41f1-9645-adbf2dda6d89)

Página de inicio de la aplicación aquí se muestran algunas recomendaciónes populares, en la parte de abajo esta la barra de navegación para visitar diferentes páginas y ver distinto contenido.

![movies-page](https://github.com/user-attachments/assets/4e367769-3835-4c39-b5fc-46e22e32f06c)

Pagina de peliculas, aqui se muestran todas las peliculas disponibles en el momento, hay otras páginas similares con contenido distinto como series, eventos deportivos, historial de visitas y favoritos.

## 5. Proceso de desarrollo

### Detalles
Angular es un framework de código abierto en TypeScript mantenido por Google y una comunidad activa de desarrolladores.

Diseñado para la creación eficiente de aplicaciones web dinámicas y de una sola página (SPA), Angular ofrece una estructura robusta basada en componentes.



## 6. Tabla con Sprint Review
¿Qué salio bien?  
La navegación entre componentes es fluida y dinámica, así como la comunicación entre ellos.

¿Qué puedo hacer diferente?
Se pudieran crear servicios, organizar mejor los componentes y modulos para reutilizar de una mejor manera el código, ademas de que se da una mejor eficiencia y facilidad de escalamiento a la aplicación.  

¿Qué no salio bien ?  
El manejo de listas como: favoriteList, viewedList, popularList que son listas dinamicas que van agregando o eliminando elementos durante la ejecución y actualizar eso de manera reactiva no salio como esperaba.





This project was generated with Angular CLI version 16.2.14.



## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
