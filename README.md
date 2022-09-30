
# Bindings en angular

## Explicación de la aplicación

Aplicación en agular que permite mantener un listado de personas.

Para añadir una persona escribimos su nombre y pulsamos sobre añadir.

Acto seguido aparecerá la persona en la lista.

Existe un componente persona que visualiza los datos de esa persona y que además tiene un botón para poder eliminarlo.

La aplicación redirige el router-outlet hacia la página home.

La página home mantiene una lista de personas con métodos para añadir y borrar.

La página home inyecta los componentes persona en la plantilla con la directiva *ngFor.

A cada componente persona se le pasa por un atributo "data" los datos de esa persona.

Además se dispone de un evento emitido por el componente persona, cuando se pulsa el botón de borrar dicha persona.

Al recibir el evento de borrar del componente se debe eliminar la persona de la lista de personas que mantiene la página Home.

Al borrar una persona, la directiva *ngFor se volverá a ejecutar por lo que el componente que anteriormente rencderizaba a dicha persona desaparecerá.


## Cosas que aprenderás

*ngIf (<https://angular.io/api/common/NgIf>)

*ngFor (<https://angular.io/api/common/NgFor>)

@Output (Eventos de salida) (<https://angular.io/api/core/Output>)

creación de componentes https://ionicframework.com/docs/cli/commands/generate>






