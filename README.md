# DesarrollosDebitosAutomaticos

Este proyecto se genero con angular 12, angular matterial para las pantallas modal y alerts.

## Sobre el proyecto
    Este proyecto tiene como objetivo mostar los desarrollos de débitos automáticos, adaptando pantallas graficas para futuras demos de los desarrollos en curso. El diseño de las     pantallas no son las que van a estar en produccion, es solo para uso interno de débito automático.
 
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
 
