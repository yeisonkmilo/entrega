# GESTIÓN DE PRODUCCIÓN

------

## Caso de uso historia 
Carlos, encargado de producción, necesita analizar el desempeño del equipo y los procesos productivos. Accede al sistema y selecciona la opción para generar reportes de producción, filtrando por un período específico. El sistema genera un informe detallado que incluye el desempeño de la producción, los productos fabricados, las posibles fallas y los tiempos de ejecución. Con esta información, Carlos puede identificar áreas de mejora y tomar decisiones informadas para optimizar la producción.

---

<table id="customers">
  <tr class="idtext principal">
    <td>ID SYN-22</td>
  </tr>
  <tr class="single text">
    <td><strong>Requerimiento</strong>:Generar reportes de producción por período. ID SYN-22</td>
  </tr>
  <tr class="single gray">
    <td><strong>Historia de usuario</strong></td>
  </tr>
  <tr class="single text">
    <td>Como encargado de producción quiero generar reportes de producción por un período específico para analizar el desempeño, identificar fallas y tomar decisiones informadas.
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
             <li>El encargado de producción accede al módulo "Reportes de Producción".</li>
            <li>Selecciona la opción "Generar Reporte por Período".</li>
            <li>Ingresa los parámetros de búsqueda, incluyendo: Fecha de inicio y fecha de fin, filtros como producto, etapa o línea de producción.</li>
            <li>Confirma la generación del reporte.</li>
            <li>El sistema procesa la solicitud y genera un reporte que incluye: Resumen de producción, Detalles de productos fabricados, tiempos invertidos y cumplimiento de metas.</li>
            <li>El usuario puede visualizar el reporte en pantalla o exportarlo en formato PDF o Excel.</li>
        </ol>
    </td>
  </tr>
  <tr class="single gray">
    <td><strong>Criterios de aceptación</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
              <li>El sistema debe permitir al usuario generar reportes seleccionando un rango de fechas.</li>
              <li>Los reportes deben incluir: Cantidad de órdenes completadas, en proceso y pendientes, Tiempos de producción por etapa o producto, Comparación con metas establecidas (si aplican).</li>
              <li>Los datos deben actualizarse automáticamente para garantizar la precisión del reporte.</li>
              <li>El reporte debe ser exportable en al menos dos formatos: PDF y Excel.</li>
              <li>Los filtros opcionales (producto, etapa, línea) deben aplicarse correctamente para personalizar los resultados.</li>
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

![Image title](./assets/images/syn-24.png)

---
 