# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

![image](https://github.com/user-attachments/assets/1c1dc8fd-8cb0-450f-81af-52ed5d8eb867)

![image](https://github.com/user-attachments/assets/2d332299-958a-407c-8f2c-7cb06d36d4e5)



## 3.2. User Stories.

<table>
    <thead>
        <tr style="text-align:center">
            <th>ID</th>
            <th>Nombre</th>
            <th>Descripción</th>
            <th>Criterios de aceptación</th>
            <th>Épica</th>
        </tr>
    </thead>
    <tbody>
        <tr style="text-align:center">
            <td>HU01</td>
            <td>Monitoreo en tiempo real</td>
            <td><strong>Como</strong> gerente. <strong>Quiero</strong> monitorear las condiciones del inventario en tiempo real. <strong>Para</strong> para evitar pérdidas por mal almacenamiento.</td>
            <td>
                <h5>Escenario 01: Actualización de estado.</h5>
                <strong>Dado</strong>  que el sistema esté conectado a sensores IoT.<br>
                <strong>Cuando</strong>  se detecte un cambio en temperatura.<br>
                <strong>Entonces</strong> se actualiza el estado en la app instantáneamente.
                <h5>Escenario 02: Visualización de estado.</h5>
                <strong>Dado</strong> que los sensores funcionen correctamente. <br>
                <strong>Cuando</strong> accedo a la app.<br>
                <strong>Entonces</strong> visualizo la temperatura y humedad actuales de los alimentos.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HUXX</td>
            <td></td>
            <td><strong>Como</strong> nombre <strong>Quiero</strong>  <strong>Para</strong> </td>
            <td>
                <h5>Escenario 01: </h5>
                <strong>Dado</strong>  <br>
                <strong>Cuando</strong>  <br>
                <strong>Entonces</strong> 
                <h5>Escenario 02: </h5>
                <strong>Dado</strong>  <br>
                <strong>Cuando</strong> <br>
                <strong>Entonces</strong> 
            </td>
            <td>EPXX</td>
        </tr>
    </tbody>
    <tbody>
    <tr style="text-align:center">
            <td>HU02</td>
            <td>Alertas por fecha de caducidad</td>
            <td><strong>Como</strong> encargado de almacén. <strong>Quiero</strong> recibir alertas antes de que un alimento caduque. <strong>Para</strong> evitar su desperdicio.</td>
            <td>
                <h5>Escenario 01: Alerta previa a caducidad.</h5>
                <strong>Dado</strong> que un producto esté próximo a caducar.<br>
                <strong>Cuando</strong> falten menos de 3 días.<br>
                <strong>Entonces</strong> el sistema me envía una notificación.<br>
                <h5>Escenario 02: Alerta de producto caducado.</h5>
                <strong>Dado</strong> que un alimento ya haya caducado.<br>
                <strong>Cuando</strong> ingreso al inventario.<br>
                <strong>Entonces</strong> se visualiza con una alerta roja.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU03</td>
            <td>Reportes automáticos de inventario</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> recibir reportes automáticos de stock. <strong>Para</strong> optimizar mis compras semanales.</td>
            <td>
                <h5>Escenario 01: Envío de reportes programados.</h5>
                <strong>Dado</strong> que llegue fin de semana.<br>
                <strong>Cuando</strong> sea sábado a las 8 am.<br>
                <strong>Entonces</strong> recibo un reporte por correo.<br>
                <h5>Escenario 02: Identificación de productos a reabastecer.</h5>
                <strong>Dado</strong> que tengo bajo stock.<br>
                <strong>Cuando</strong> reviso el reporte.<br>
                <strong>Entonces</strong> identifico los productos a reabastecer.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU04</td>
            <td>Interfaz intuitiva</td>
            <td><strong>Como</strong> trabajador de cocina. <strong>Quiero</strong> una app sencilla con iconos claros. <strong>Para</strong> usarla sin complicaciones.</td>
            <td>
                <h5>Escenario 01: Navegación sencilla.</h5>
                <strong>Dado</strong> que ingreso a la app.<br>
                <strong>Cuando</strong> navego entre secciones.<br>
                <strong>Entonces</strong> entiendo fácilmente las funciones.<br>
                <h5>Escenario 02: Registro rápido.</h5>
                <strong>Dado</strong> que necesito registrar un nuevo producto.<br>
                <strong>Cuando</strong> toco el botón de agregar.<br>
                <strong>Entonces</strong> el proceso no toma más de 3 pasos.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU05</td>
            <td>Visualización de niveles de stock</td>
            <td><strong>Como</strong> encargado de compras. <strong>Quiero</strong> ver el nivel actual de stock. <strong>Para</strong> saber cuándo hacer pedidos.</td>
            <td>
                <h5>Escenario 01: Stock bajo visualizado.</h5>
                <strong>Dado</strong> que un producto está por agotarse.<br>
                <strong>Cuando</strong> reviso el panel.<br>
                <strong>Entonces</strong> lo veo en color naranja o rojo.<br>
                <h5>Escenario 02: Stock suficiente visualizado.</h5>
                <strong>Dado</strong> que hay suficiente stock.<br>
                <strong>Cuando</strong> veo el tablero.<br>
                <strong>Entonces</strong> el producto aparece en verde.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tr style="text-align:center">
            <td>HU06</td>
            <td>Configuración de alertas personalizadas</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> configurar las alertas según mis necesidades. <strong>Para</strong> priorizar los productos más críticos.</td>
            <td>
                <h5>Escenario 01: Configuración de umbrales.</h5>
                <strong>Dado</strong> que accedo a configuración.<br>
                <strong>Cuando</strong> selecciono un producto.<br>
                <strong>Entonces</strong> puedo definir umbrales de alerta.<br>
                <h5>Escenario 02: Notificación personalizada.</h5>
                <strong>Dado</strong> que configuro alertas por caducidad.<br>
                <strong>Cuando</strong> se cumple el plazo.<br>
                <strong>Entonces</strong> recibo la notificación según mi configuración.
            </td>
            <td>EP01</td>
        </tr>
    <tbody>
        
    </tbody>
        
</table>
    

## 3.3. Impact Mapping.

## 3.4. Product Backlog.
| id | epic |

## 3.5 chapter

