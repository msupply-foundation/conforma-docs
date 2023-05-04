+++
title = "4. Revisar una solicitud de registro de empresa"
description = "Demonstration of a sample Conforma system"
date = 2021-05-01T08:20:00+00:00
updated = 2021-05-01T08:20:00+00:00
draft = false
weight = 13
sort_by = "weight"
template = "docs/page.html"

+++

Regresa a la página de inicio de sesión del sistema de demostración (¡preferiblemente en otro navegador!) navegando a:
https://conforma-demo.msupply.org:50000/ 

Ahora, para esta parte del tutorial, vamos a iniciar sesión como miembro del personal de la Agencia Reguladora.

Vamos a utilizar las siguientes credenciales de un miembro del personal:

![Internal user details](/docs/about/demo/24.png)

Como se señala arriba, el rol de Alice es Administradora de Servicios Empresariales y parte de su trabajo es administrar las solicitudes de registro de empresas

Ve adelante e inicia sesión utilizando las credenciales de Alice (arriba)..

### Navegando en el sistema como un usuario del personal regulador

Una vez que hayas iniciado sesión, serás llevado a la página de inicio del tablero de Alice. Puede que hayas notado que el diseño del tablero se parece mucho a la página de inicio de tu cuenta de usuario externa que creaste anteriormente.

¡Sin embargo, hay diferencias entre las cuentas de usuario externas e internas!

En esta sección explicamos algunas de las principales diferencias.

**Para empezar, veamos las diferencias al mirar el tablero de control:**

1. En la esquina superior izquierda, verás que los miembros del personal interno están asociados con la organización 'Autoridad Reguladora'

![Internal organisation](/docs/about/demo/25.png)

2. Los tipos de solicitudes/ flujos de trabajo con los que puedes interactuar están limitados por tus permisos.

   A continuación, se presentan ejemplos de dos miembros del personal diferentes de la Autoridad Reguladora. La primera es Alice y la segunda es Bob Vance, jefe de sección de la sección de registro de medicamentos. 

3. La sección de resumen de solicitudes muestra las solicitudes relevantes en las que puedes trabajar.

4. Las bases de datos son bases de datos internas que incluyen todos los productos de solicitudes aprobados (por ejemplo, una base de datos de todas las empresas registradas)

<div class="note">
Como se mencionó anteriormente, los diferentes miembros del personal tendrán diferentes accesos a diferentes módulos/ solicitudes según sus permisos. Por ejemplo, Alice puede ver e interactuar con olicitudes de registro de empresas, pero no con solicitudes de registro de productos.
</div>



---------------

### Página de revisión de solicitudes
 
Bien, echemos un vistazo a la página de revisión de la solicitud que presentaste anteriormente.

 1. Haz clic en **Revisiones pendientes de asignación** para filtrar la lista de aplicaciones a aquellas que aún necesitan ser asignadas.


    Esto mostrará una lista filtrada como:

    ![Filtered application list](/docs/about/demo/26.png)

 2. Haz clic en el enlace de la solicitud que acabas de enviar.

   ![Application link](/docs/about/demo/27.png)


 3. Esto te llevará a la página de revisión de la solicitud. 
 
   La página de revisión tiene 4 pestañas de información/función que se describen a continuación

    **Overview tab**

    Dentro de la pestaña de resumen se puede ver información como:

    - Detalles de la solicitud: *Información básica relacionada con la solicitud, como quién la presentó, la fecha de presentación y el ID de la solicitud*

    - Historial de Actividad: *Esta sección muestra un historial detallado del proceso de flujo de trabajo de la solicitud. Es especialmente útil para las solicitudes con más de una etapa para monitorear y realizar un seguimiento de su progreso*

    ![overview tab](/docs/about/demo/28.png)


     **Pestaña de asignación**

     Dentro de la pestaña de asignación, puedes asignar aplicaciones y ver asignaciones actuales y pasadas para todas las etapas de una solicitud.

     Para la mayoría de las solicitudes, cuando asignas una sección, asigna todas las secciones de una solicitud al usuario. Para solicitudes complejas, que pueden necesitar ser revisadas por múltiples personas al mismo tiempo, cada sección puede ser asignada a un miembro del personal diferente.
        

     ![assignment tab](/docs/about/demo/30.png)

     **Pestaña de notas internas**

     La pestaña de notas internas permite a los miembros del personal interno agregar comentarios y archivos ad hoc relacionados con una solicitud. El sistema registra el historial de quién hizo cada comentario.

     En el siguiente ejemplo, otro miembro del personal adjuntó una consulta por correo electrónico relacionada con una solicitud. 


     ![internal notes tab](/docs/about/demo/29.png)

     **Pestaña de notas de documentos**

     Dentro de la pestaña de documentos, podrás ver cualquier certificado generado por el sistema relacionado con una solicitud (por ejemplo, un certificado de registro de producto). En el caso de que no se haya generado ningún certificado, esta sección estará en blanco. 

     ![Documents tab](/docs/about/demo/31.png)

----------------

### Asignar la solicitud a tu carga de trabajo
 
Ahora que estás familiarizado con la página de revisión y su funcionalidad, comencemos a revisar la solicitud de registro de empresa que presentaste anteriormente.

Primero, necesitamos asignarnos la solicitud para poder comenzar a revisarla.

1. Navega hasta la pestaña de asignaciones de la solicitud

<div class="tip">
¡Puedes acceder directamente a la pestaña de asignaciones desde la lista de solicitudes, simplemente haz clic en el botón de autoasignación!
</div>

![self-assign](/docs/about/demo/32.png)

2. Utilizando la lista desplegable que muestra **Not assigned**,'Tú mismo' de la lista.

3. Ahora haz clic en el botón **enviar** 

![assignment tab](/docs/about/demo/30.png)

4. Ahora has sido asignado a la solicitud. 

    Esto se refleja en la pestaña de asignaciones.

![assignment tab](/docs/about/demo/33.png)


<div class="tip">
No olvides que esta actividad también se refleja en la sección de actividad de la pestaña de resumen.
</div>

-----------

### Revisión de una solicitud de registro de empresa

Ahora que la solicitud ha sido asignada a ti mismo, puedes empezar a trabajar y revisar la aplicación.

1. Dentro de la pestaña de asignaciones en la página de revisión, haz clic en el botón **Empezar**.

![assignment tab](/docs/about/demo/35.png)

2. Dentro de cada formulario de la solicitud, se pueden revisar todos los campos que requieren revisión. Para revisar un campo individual, haz clic en el botón **Revisar**. Esto abre un espacio para que el revisor marque el requisito del formulario como Conforme (cumple con los requisitos) o No conforme (no cumple con los requisitos). 

    Avanza a través del formulario de revisión y marca cada requisito como un campo conforme o no conforme. Para este tutorial, marca todo como conforme por ahora (¡nos ocuparemos del resto después!).   
    
    El campo de comentarios dentro del cuadro de revisión se puede utilizar para registrar notas internas según sea necesario. Las notas internas para los campos conformes no son visibles para el solicitante. 
    
   Sin embargo, cuando se marca un campo con un resultado no conforme, se requiere un comentario para comunicar al solicitante (.por ejemplo, proporcionar orientación al solicitante).
    

<div class="tip">
También se puede utilizar el botón Aprobar todo para marcar todos los campos de esa sección como requisitos conformes.
</div>

![assignment tab](/docs/about/demo/37.png)


<div class="warning">
Recuerda que si registras elementos del formulario con un resultado de no conformidad y emites una lista de preguntas (o solicitud de información) al solicitante, cualquier comentario incluido en esos campos no conformes será visible para el solicitante.
</div>


3. Una vez que hayas completado tu revisión de todos los campos del formulario, es hora de registrar el resultado de tu revisión para esa solicitud. Para esta aplicación solo hay una etapa. 

    El siguiente diagrama describe lo que significan los resultados para esta solicitud.

    ![assignment tab](/docs/about/demo/38.png)

    Los botones de resultado de la revisión aparecen en la parte inferior de la página y cambian según la revisión de los campos del formulario anterior.

    Como seleccionamos 'Conforme' para todos los campos anteriores, nuestra única opción es marcar el resultado de la aplicación como **Conform**.

    ![assignment tab](/docs/about/demo/39.png)

4. El último campo para completar es el campo de **Comentario general**. 

    Este campo es un cuadro de texto libre que se puede utilizar de la siguiente manera:

    - Si el resultado es aprobar o enviar una lista de preguntas al solicitante, se puede utilizar el comentario general para registrar una nota sobre la decisión interna. Esto no será visible para el solicitante. 

    - Si el resultado es rechazar la solicitud, **debe** tilizarse el comentario general para registrar el motivo del rechazo. Este comentario será utilizado por el sistema para generar la correspondencia de rechazo. 

![assignment tab](/docs/about/demo/40.png)


<div class="warning">
Recuerda que si marcas el resultado general de la aplicación como No Conforme, debes incluir el motivo del rechazo en el campo de Comentario general para proporcionar al solicitante. 
</div>

5. Una vez que estés satisfecho con tu revisión, haz clic en el botón **Enviar revisión**.

    Aparecerá una ventana emergente de confirmación final que te preguntará si deseas confirmar tu decisión de enviar la revisión.

    Haz clic en **Enviar**

![submission message](/docs/about/demo/41.png)

6. Genial, ahora has aprobado la solicitud de registro de empresa. En la pantalla verás un resumen de tu revisión. Este registro de revisión se almacenará en el sistema y se puede acceder en cualquier momento.

7. Si has utilizado tu cuenta de correo electrónico para registrarte en el sistema, habrás recibido un correo electrónico que indica la aprobación de la solicitud de registro de empresa.

    Los correos electrónicos se pueden adaptar para cada tipo de solicitud y resultado. Para esta solicitud, el correo electrónico debería verse así:

    ![Company approval email](/docs/about/demo/42.png)

----------

Ahora que has aprobado esa solicitud de registro de empresa, cierra la sesión de la cuenta de Alice y vuelve a tu cuenta de usuario creada para solicitantes. 

Luego, continúa con la sección **5. Envío de una solicitud de registro de producto** del tutorial para continuar con la guía.