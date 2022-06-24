# Azure-Monitor
Creación de Azure Monitor para vigilar recursos

![Logo de Azure Monitor](https://github.com/AlanAlvaradoR/Azure-Monitor/blob/main/imagenes/monitor.jpg)

## Requisitos

- Cuenta de [Azure](https://portal.azure.com/) con suscripción activa
- Recurso (o recursos) ya creado(s) que se quiera monitorear su rendimiento
- Computadora con Windows, Linux o MacOs

---------------------------------------------------------

## Pasos

### Crear una gráfica de métricas de un recurso ###

1. Se inicia sesión en la página de [Azure](https://portal.azure.com/)

2. Se busca "Monitor" en el buscador superior y se da enter

3.  Se selecciona en el menú lateral izquierdo el apartado de "Métricas"

4. Se abrirá un nuevo menú donde se debe seleccionar el recurso a vigilar. Una vez seleccionado se da click en "aplicar".

5. Se cerrará el menú anterior. Ahora se seleciona la métrica que se quiera ver en la gráfica (uso de CPU, uso de red, etc.) y la agregación (promedio, máximo, etc.)

6. Una vez seleccionados los parámetros anteriores, se da click en "actualizar".

7. Si se desea mostrar en el menú principal de Azure para gacilitar su acceso y vista al iniciar sesión, se da click en "guardar en el panel" después en "anclar al panel" y finalmente en "Anclar"

### Crear una alerta de un recurso ###

1. Se inicia sesión en la página de [Azure](https://portal.azure.com/)

2. Se busca "Monitor" en el buscador superior y se da enter

3.  Se selecciona en el menú lateral izquierdo el apartado de "Alertas"

4. Se da click en "crear" y luego en "regla de alertas"

5. Se abrirá una pestaña donde se deberá indicar el recurso el del cual se emitirá la alerta, una vez seleccionado se da click en "Listo". Si se tiene un ámbito, también se puede seleccionar.

6. En la pestaña superior se cambia al apartado de condición. Se abrirá una nueva pestaña donde se debe buscar y seleccionar la condición que se debe cumplir para mandar la alerta (uso de CPU, uso de Red, etc.). Una vez seleccionado se mostrará más opciones en la parte baja donde se pueden especificar los parámetros (mayor que, menor que, etc.) y la frecuencia de evaluación. También es necesario usar un grupo de acciones. Una vez seleccionados los parámetros se da click en "Listo".
*Nota: si se desea crear una alerta, es necesario también usar o, en su defecto, crear un grupo de acciones*

*Nota: cada alerta tiene un pequeño costo*

7. Se cambia al apartado de detalles en la parte superior.

8. Se selecciona el grupo de recursos, la gravedad, se le da un nombre, una descripción y y se seleciona la casilla de "habilitar después de la creación".

9. Se da click en "revisar y crear". Se espera a que se habilite el botón de "crear" y se da click en él.
