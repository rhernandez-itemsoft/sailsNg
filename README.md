# SailsJs 1.2.4 + Angular 10

+ [Sails v1](https://sailsjs.com)
+ [Angular 10](https://angular.io/)

### Descripción
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
  




### > ng version
-----------------------------------------------------------
- Angular CLI: 10.0.0
- Node: 12.18.1
- OS: win32 x64
-----------------------------------------------------------
- Angular: 10.0.0
- ... animations, cli, common, compiler, compiler-cli, core, forms
- ... platform-browser, platform-browser-dynamic, router
- Ivy Workspace: Yes

-----------------------------------------------------------
- Package                           Version
-----------------------------------------------------------
- @angular-devkit/architect         0.1000.0
- @angular-devkit/build-angular     0.1000.0
- @angular-devkit/build-optimizer   0.1000.0
- @angular-devkit/build-webpack     0.1000.0
- @angular-devkit/core              10.0.0
- @angular-devkit/schematics        10.0.0
- @ngtools/webpack                  10.0.0
- @schematics/angular               10.0.0
- @schematics/update                0.1000.0
- rxjs                              6.5.5
- typescript                        3.9.5
- webpack                           4.43.0
