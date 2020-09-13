Tutorial de ejemplo de Angular en Typescript (https://angular.io/start)
----

[Editado en  StackBlitz ⚡️](https://stackblitz.com/edit/angular-ntjpm5-wcqpl7)
Para crearlo desde StackBlitz accder al enlace: https://angular.io/generated/live-examples/getting-started-v0/stackblitz.html
# Crear el proyecto

## Conceptos iniciales 
* *ngFor 
* *ngIf 
* Interpolación {{ }} 
* Enlace de propiedades [ ] 
* Enlace de eventos ( ) 

## Componentes https://angular.io/guide/architecture-components
Son partes reutilizables dentro de la interfaz de ususario. Constan de:
* Clase de Componente
* Plantilla html
* Hoja de estilos CSS
En el ejemplo: 
* app-root: shell de la aplicación o pagina base. Primer componente que se carga y el elemento primario de todos los demás componentes.  
* app-top-bar: (arriba) nombre de la tienda y el botón de pago.
* app-product-list: (abajo) lista de productos que se muestra iterativamente.
## Entrada
PAra crear un nuevo componente, con el boton derecho del raton en la carpeta app -> menu:Angular Generator -> component. LE damos el nombre ***product-alerts***