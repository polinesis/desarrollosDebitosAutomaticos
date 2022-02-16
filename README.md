# KOLEKTOR desarrollosDebitosAutomaticos

Este proyecto esta desarrollado en Angular 12 

Comandos 

Se levanta con
ng serve -o

ng g class models/...

ng g s services

ng g c components


El objetivo del proyecto es agregar pantallas a nuestros desarrollos para futuras demos.

Actualmente esta desarrollado:
A-Embarcaciones para cuota unica y mensualizado para ente paypertic 
B-Adhesion de plan ant

Estructura:

Components
  Esta capa es la que se encarga por funcionalidad a desarrollar, contener un html, un ts que invoca a capa de servicios y un css.
  
layout
  Esta capa se encarga de contener el menu de opciones 

models 
  Esta capa modela objetos para presentacion y tambien se utiliza para enviar info al back java

services
    esta capa se conecta con back java. es la encargada de recibir las peticiones http


Rooteador interno 

app-routing.modules.ts , aca vamos a rutear las app que seleccionamos del menu
