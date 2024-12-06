# GESTIÓN DE PRODUCCIÓN

------

## Caso de uso historia 
Carlos, encargado de producción, necesita asegurarse de que las órdenes de producción se cumplan a tiempo. Configura el sistema para recibir notificaciones automáticas cuando una etapa de producción experimente un retraso. Cuando una etapa se retrasa, el sistema envía una alerta a Carlos, quien puede tomar medidas correctivas de inmediato, como reasignar recursos o ajustar plazos, para minimizar el impacto en el cumplimiento de las órdenes.

---

<table id="customers">
  <tr class="idtext principal">
    <td>ID SYN-23</td>
  </tr>
  <tr class="single text">
    <td><strong>Requerimiento</strong>:Notificar retrasos en etapas de producción. ID SYN-23</td>
  </tr>
  <tr class="single gray">
    <td><strong>Historia de usuario</strong></td>
  </tr>
  <tr class="single text">
    <td>Como encargado de producción quiero recibir notificaciones sobre retrasos en las etapas de producción para tomar medidas correctivas rápidamente y minimizar impactos en el cumplimiento de las órdenes.
</td>
  </tr>
  <tr class="duo">
    <th class="gray"><strong>Estado de la tarea</strong></th>
    <th>En desarrollo</th>
  </tr>
  <tr class="single gray">
    <td><strong>Caso de uso (Pasos)</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
            <li>
             <li>El sistema monitorea continuamente el avance de las etapas de producción.</li>
            <li>Si una etapa supera su tiempo límite sin completarse, el sistema identifica el retraso.</li>
            <li>Se genera automáticamente una notificación con los siguientes detalles: Nombre de la etapa afectada, Orden de producción vinculada, Tiempo de retraso acumulado,Posibles causas.</li>
            <li>El sistema envía la notificación al encargado de producción y supervisores relevantes.</li>
            <li>Los responsables revisan la notificación y toman acciones correctivas para abordar el retraso.</li>
        </ol>
    </td>
  </tr>
  <tr class="single gray">
    <td><strong>Criterios de aceptación</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
              <li>El sistema debe identificar automáticamente retrasos cuando el tiempo límite de una etapa sea excedido.</li>
              <li>Las notificaciones deben incluir información clave, como etapa afectada, orden de producción y tiempo de retraso.</li>
              <li>Los usuarios deben recibir las notificaciones en tiempo real a través de correo electrónico, sistema interno o dispositivos móviles.</li>
              <li>La notificación debe registrarse en un historial accesible para seguimiento.</li>
            </ol>
 <tr class="duo">
    <th class="gray"><strong>Calidad</strong></th>
    <th>En desarrollo</th>
  </tr>
  <tr class="duo">
    <th class="gray"><strong>Versionamiento</strong></th>
    <th>En desarrollo</th>
  </tr>
</table>


---
## Diagrama de Clases
[Creado con plantuml](https://plantuml.com/es/)

![Image title](./assets/images/syn-25.png)

---