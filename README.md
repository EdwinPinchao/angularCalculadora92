# Angularcalculadora

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

creamos el proyecto en la terminal

$ng new angularCalculadora
yes en las rutas 
$cd angularCalculadora
correr el aplicativo
$ng serve -o

que correra en nuestra navegador en la direccion 
localhost:4200

si por algun motivo interfiere con el puerto podemos correr el comando 
$ng serve --port 4201

crearemos las rutas eso veremos más adelante 

en este proyecto creado pondremos atención al archivos al.
 package.json

Package.json define el nombre y versión de nuestro proyecto, 
así como las dependencias de paquetes de desarrollo
 (Por ejemplo el compilador angular y angular-cli) y 
las dependencias de paquetes sobre la que construiremos nuestra aplicación 
(Por ejemplo angular core, que es el conjunto de librerías con los componentes 
básicos de angular).



angular crea app de tipo SPA (Single Page APlication) 
 el cual la 
Index.html (SPA) esta es la que toma como inicio para ejecutar la aplicación

donde encontramos el elemento
  <app-root></app-root>


que este se encuentra dentro de nuestra carpeta app en app.components.ts

dentro del componente tiene el selector que es app-root que se esta usando para 
levantar el componente.

vamos a ver el archivo main.ts
AppModule en este caso estamos levantando el módulo de APP módulo este módulo es una
clase de TS y si vamos a un archivo de APP módulo de TS podemos observar que esta 
clase se llama AppModule


## Errores comunes 
**es la importación de los paquetes de import { NgModule } from '@angular/core'; en el 
archivo app.module.ts  en carpeta APP
**el primer error que se puede encontrar es que en el arhivo app.module.ts en el 
decorador NgModule no importemos los Componentes  

**declaraciones es donde vamos a ingresar nuestros componentes que hemos creado.

que se encuentra dentro del archivo 

App component.ts

en este tenemos un decorator
** cuando suben al git o github aveces se olvida quitar los paquetes de node que son los que mas pesan 
cuando para eso se utiliza el package.json para instalar todas las dependencias 
para su uso. con el comando
$ se clona el proyecto y se baja el archivo
$ npm install

