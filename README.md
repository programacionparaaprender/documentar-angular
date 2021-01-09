# Crear proyecto
npm install -g @angular/cli
ng new my-app
cd my-app
ng serve --open
npm install --save @angular/http @toverux/ngx-sweetalert2 sweetalert2
npm install @compodoc/compodoc @types/node --save-dev

#### dependencies
@agm/core
@agm/js-marker-clusterer
@angular/http
@toverux/ngx-sweetalert2
chart.js
core-js
i18n-config
js-marker-clusterer
ng2-charts
ngx-easy-table
sweetalert2
### dev dependencies
@compodoc/compodoc
@types/node



-------------
## Extensiones
----------------
typescript importer

https://angular.io/docs
https://www.typescriptlang.org/docs/home.html
https://compodoc.app/guides/getting-started.html
https://ionicframework.com/docs/
https://nodejs.org/es/
https://github.com/compodoc-course
https://github.com/compodoc-course/compodoc-angular-ionic
https://compodoc.app/
https://compodoc.app/guides/installation.html
https://compodoc.app/guides/themes.html

### Curso


package.json 
agregar en scripts

"compodoc": "npx compodoc -p src/tsconfig.app.json" 

luego ejecutar npm run compodoc

esto se coloca luego para definir la carpeta donde se almacenara la documentación

"compodoc": "npx compodoc -p src/tsconfig.app.json  --output src/docs"

Abre la documentación
Genera la documentación en el servidor localhost:8080

--open
--serve
"compodoc": "npx compodoc -p src/tsconfig.app.json --output src/docs --serve --open" 

para agregar el tema 

--theme material
"compodoc-material": "npx compodoc -p src/tsconfig.app.json --output src/docs --serve --open --theme material"

npm run compodoc-vagrant

----------------------------
realización de un sumario
----------------------------
https://compodoc.app/guides/tips-and-tricks.html

añade información sobre el proyecto, que falta, funcionalidad

mkdir src/aditional-docs
touch src/aditional-docs/a-file.md
touch src/aditional-docs/b-file.md 
touch src/aditional-docs/summary.json

"compodoc-plus": "npx compodoc -p src/tsconfig.app.json --output src/docs --serve --open --includes src/aditional-docs"

----------------
Añadir Favicon
----------------
https://compodoc.app/guides/usage.html
package.json agregar
"compodoc-favicon-title": "npx compodoc -p src/tsconfig.app.json --output src/docs --serve --open --includes src/aditional-docs --customFavicon src/favicon.ico -n \"Angular Compodoc Cource\" "

-----------
ESTILOS
------------------
npm run compodoc-custom-style
npm run compodoc-custom-style-personal


-----------------
Logo personal
-----------------
"compodoc-favicon-title-personal": "npx compodoc -p src/tsconfig.app.json --output src/docs --serve --open --includes src/aditional-docs --name \"Angular Compodoc Cource\" --customFavicon src/favicon.ico --hideGenerator "


