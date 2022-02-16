# DesarrollosDebitosAutomaticos

Este proyecto se genero con angular 12

## Ejecucion del server

Para ejecutar el server es mediante ng serve - o se despliega en `http://localhost:4200/`.

Comandos utiles :

ng g class models/...

ng g s services/...

ng g c components/...

Estructura del proyecto

app-routing.modules.ts: este archivo es enrutador interno de la app. cada path le corresponde a una  opcion del menu

components
  aca esta cada funcionalidad de la app. con su correspiente html, css y ts. este ultimo se comunica con el service
layout 
  aca este el menu central de la app
models
   Son los objetos de la capa de presentacion
   
service
  Esta capa es la que se comunica con el back end de java.
 
