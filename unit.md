# Instalación Angular Windows

![Angular Logo](assets/logo.png?raw=true "Angular Logo")

En esta play, vamos a instalar *angular/cli* y usarlo para empezar una aplicación Angular.


keywords: "angular","install","windows"

## Introducción

[Angular](https://angular.io/) es un framework para desarrollar el front-end de aplicaciones web. Angular esta desarrollado en [Angular](https://www.typescriptlang.org/), es mantenido por Google y es de código abierto.

### Dirigido a

Desarrolladores que quieran empezar a desarrollar aplicaciones web. Analistas QA y Scrum Master donde son miembros de un proyecto Angular. 


### Use este play para...

1. Instalar *angular/cli*  en la estación de trabajo.
2. Empezar una aplicación web simple en Angular, usando la consola *angular/cli*


### Necesito este play porque...

Para poder desarrollar una aplicación de front-end en angular, se recomiendo usar *angular/cli*. La consola permite con un solo comando descargar todo lo necesario para empezar a desarrollar la aplicación web.


### Información
- 10 minutos.
- Dificultad: Múy Fácil.


### Conocimientos previos

1. Instalar paquetes de Nodejs.


### Materiales

1. Computador con acceso a internet.
2. Nodejs instalado.
3. npm Instalado.

## Ejecución  


### Paso 1: Instalar angular/cli (3 minutos)

- Abrir alguna terminal. En el caso de Windows abrir *cmd* o *powershell*
- Ejecutar el siguiente comando npm: 

```sh 
npm install -g @angular/cli
```

- Una ves descargado, podemos llamar a la consola Angular con `ng`. Por ejemplo, podemos revisar la versión descargada con el siguiente comando:

```sh 
ng -v
```


### Paso 2: Crear proyecto Angular (4 minutos)


- Para crear un proyecto se utiliza el comando `new <nombre-proyecto>`. Donde `<nombre-proyecto>` corresponde al nombre de nuestro proyecto. Para esta unidad, vamos a crear un proyecto llamado *proyecto-ejemplo*:

```sh 
ng new proyecto-ejemplo
```

El comando va a crear un directorio, en este caso llamado *proyecto-ejemplo*. Dentro de este se encuentra los archivos base para nuestro proyecto. 

### Paso 3 Levantar el proyecto (3 minutos)

- Entrar al proyecto. Para entrar al proyecto hay que entrar a la carpeta recién creada. Por ejemplo: 
```sh 
cd proyecto-ejemplo
```

- Levantar el proyecto utilizando `serve` dentro de la carpeta del proyecto. Por ejemplo:

```sh 
ng serve
```

El comando anterior va a compilar y levantar el proyecto de forma local. Por defecto Angular levanta la aplicación en el puerto 4200.


- Visitar la aplicación levantada usando el browser (chrome, fifefox, etc...). La ruta de la aplicación es http://localhost:4200 .


Pro-tip: Podemos cambiar el puerto donde se levanta la aplicación con el siguiente comando:

```sh 
ng serve --port <puerto>
```

Por ejemplo:

```sh 
ng serve --port 4201
```


## Ejercicios

### Crear otro projecto (3 minutos)

- Cree otro projecto angular llamado *proyecto-ejemplo2*, y ejecútelo. 

## Conclusión

En esta unidad vimos todo lo necesario para empezar el desarrollo de una aplicación Angular. 


### Alternativas

- [Instalar React](link-a-play) 
- [Instalar Vue](link-a-play) 


### Próximos pasos

- Play de Angular
- Play de Angular con docker












