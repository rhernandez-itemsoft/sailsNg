# SailsJs 1.2.4 + Angular 10

+ [Sails v1](https://sailsjs.com)
+ [Angular 10](https://angular.io/)

## Descripción
  Integración de SailsJs con Angular.
  - La carpeta de trabajo de angular es "src"
  - La carpeta de salida de angular es "assets". Se reemplazaron todos los archivos que existian y que pertenecian a SailsJS, si por alguna razon necesitas tener a "angular" bajo una ruta en específico debes modificar lo siguiente:
  - tsconfig.base.json: 
  - ...... compilerOptions->outDir 
  - ...... compilerOptions->baseUrl
  - angular.json: 
  - ...... projects->ngtest->architect->build->options->outputPath
  - ...... projects->ngtest->root
  - views/layout/layout.ejs
  - ...... &lt;base href="/"&gt;
  

## instalación
Dentro de la carpeta raíz ejecuta
- npm install 

## Ejecución
 ### ng build --watch    
- Con está instrucción compilas tus archivos de Angular que se encuentran en la carpeta "src" y ante cualquier cambio que hagas se compilará de nuevo, de tal manera que podrás ver los cambios en el front.
+ [Más información](https://angular.io/cli/build)


 ### sails lift
- Levanta la aplicación, por default tiene establecido el puerto 1337
+ [Más información](https://sailsjs.com/documentation/reference/application/advanced-usage/sails-lift)

## ng version
-----------------------------------------------------------
- Angular CLI: 10.0.0
- Node: 12.18.1
- OS: win32 x64
