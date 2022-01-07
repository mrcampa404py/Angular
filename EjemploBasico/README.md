# EjemploBasico

Esta aplicacion es solo un ejemplo basico
con algunas modificaciones en el index. 

Para iniciar debemos de conocer la distribucion interna del proyecto, siendo esta: 

1. e2e

2. node_modules: Carpeta con todas las librerias necesarias para la compilacion y el desarrollo. 

3. src: En esta carpeta se encuentra todo el codigo principal, cuando se traslade a produccion basicamente se compilara solo esta informacion. 

4. Todo lo demas: por el momento no es importante pero lo detallaremos despues. 

## Flujo de Angular 

Toda aplicacion Angular es una SPA (Single Page Application), esto significa que Angular 
solicita una sola vez una pagina html y posteriormente solo va sustituyendo secciones en 
concreto llamadas componentes. 
