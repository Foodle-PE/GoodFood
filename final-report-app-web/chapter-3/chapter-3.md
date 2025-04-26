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
        <tr style="text-align:center">
            <td>HU07</td>
            <td>Acceso multiusuario</td>
            <td><strong>Como</strong> dueño de restaurante. <strong>Quiero</strong> que mi equipo tenga cuentas propias. <strong>Para</strong> dividir responsabilidades.</td>
            <td>
                <h5>Escenario 01: Acceso por rol.</h5>
                <strong>Dado</strong> que tengo diferentes roles.<br>
                <strong>Cuando</strong> un cocinero accede.<br>
                <strong>Entonces</strong> solo ve lo relevante a cocina.<br>
                <h5>Escenario 02: Gestión de accesos.</h5>
                <strong>Dado</strong> que soy administrador.<br>
                <strong>Cuando</strong> gestiono usuarios.<br>
                <strong>Entonces</strong> puedo crear o quitar accesos.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU08</td>
            <td>Lectura de temperatura desde sensores</td>
            <td><strong>Como</strong> gerente. <strong>Quiero</strong> conocer la temperatura del almacén. <strong>Para</strong> asegurar condiciones óptimas.</td>
            <td>
                <h5>Escenario 01: Visualización de temperatura.</h5>
                <strong>Dado</strong> que el sensor está activo.<br>
                <strong>Cuando</strong> abro la app.<br>
                <strong>Entonces</strong> me muestra la temperatura en grados.<br>
                <h5>Escenario 02: Alerta por temperatura anómala.</h5>
                <strong>Dado</strong> que la temperatura es inadecuada.<br>
                <strong>Cuando</strong> supera los límites.<br>
                <strong>Entonces</strong> se emite una alerta.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU09</td>
            <td>Adaptabilidad del sistema</td>
            <td><strong>Como</strong> dueño de restaurante. <strong>Quiero</strong> que el sistema se adapte a mis instalaciones. <strong>Para</strong> que funcione sin importar el tamaño.</td>
            <td>
                <h5>Escenario 01: Instalación en local mediano.</h5>
                <strong>Dado</strong> que tengo un restaurante mediano.<br>
                <strong>Cuando</strong> instalo los sensores.<br>
                <strong>Entonces</strong> se integran sin necesidad de infraestructura extra.<br>
                <h5>Escenario 02: Escalabilidad a cadena.</h5>
                <strong>Dado</strong> que crezco a una cadena.<br>
                <strong>Cuando</strong> amplío el sistema.<br>
                <strong>Entonces</strong> la app permite escalar la solución.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU10</td>
            <td>Historial de temperaturas</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> ver un historial de temperatura por producto. <strong>Para</strong> detectar posibles fallas.</td>
            <td>
                <h5>Escenario 01: Revisión ante producto dañado.</h5>
                <strong>Dado</strong> que un alimento se estropea.<br>
                <strong>Cuando</strong> consulto su historial.<br>
                <strong>Entonces</strong> veo si hubo cambios bruscos de temperatura.<br>
                <h5>Escenario 02: Consulta por fecha.</h5>
                <strong>Dado</strong> que accedo a los datos.<br>
                <strong>Cuando</strong> selecciono una fecha.<br>
                <strong>Entonces</strong> se me muestra la evolución.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU11</td>
            <td>Registro de entrada de productos</td>
            <td><strong>Como</strong> encargado. <strong>Quiero</strong> registrar la llegada de productos. <strong>Para</strong> tener un control preciso del inventario.</td>
            <td>
                <h5>Escenario 01: Registro de nuevo lote.</h5>
                <strong>Dado</strong> que llega un nuevo lote.<br>
                <strong>Cuando</strong> ingreso los datos.<br>
                <strong>Entonces</strong> el inventario se actualiza automáticamente.<br>
                <h5>Escenario 02: Notificación de omisión.</h5>
                <strong>Dado</strong> que olvido registrar.<br>
                <strong>Cuando</strong> reviso el inventario.<br>
                <strong>Entonces</strong> me aparece una notificación de producto sin ingreso.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU12</td>
            <td>Registro de salida de productos</td>
            <td><strong>Como</strong> trabajador. <strong>Quiero</strong> registrar qué productos se usan. <strong>Para</strong> mantener actualizado el stock.</td>
            <td>
                <h5>Escenario 01: Registro de uso.</h5>
                <strong>Dado</strong> que utilizo un ingrediente.<br>
                <strong>Cuando</strong> marco su salida.<br>
                <strong>Entonces</strong> el inventario lo descuenta.<br>
                <h5>Escenario 02: Auditoría de omisiones.</h5>
                <strong>Dado</strong> que un producto no se marca.<br>
                <strong>Cuando</strong> hay diferencias.<br>
                <strong>Entonces</strong> se registra en una auditoría.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU13</td>
            <td>Aplicación móvil compatible</td>
            <td><strong>Como</strong> cocinero. <strong>Quiero</strong> acceder desde mi celular. <strong>Para</strong> consultar el inventario sin ir al almacén.</td>
            <td>
                <h5>Escenario 01: Acceso desde el móvil.</h5>
                <strong>Dado</strong> que tengo conexión a internet.<br>
                <strong>Cuando</strong> descargo la app.<br>
                <strong>Entonces</strong> puedo consultar el inventario desde mi móvil.<br>
                <h5>Escenario 02: Acceso sin conexión.</h5>
                <strong>Dado</strong> que no tengo red.<br>
                <strong>Cuando</strong> accedo a la app.<br>
                <strong>Entonces</strong> veo los datos más recientes en caché.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU14</td>
            <td>Reducción de desperdicio alimentario</td>
            <td><strong>Como</strong> gerente. <strong>Quiero</strong> reducir el desperdicio. <strong>Para</strong> disminuir mis costos.</td>
            <td>
                <h5>Escenario 01: Alerta de caducidad próxima.</h5>
                <strong>Dado</strong> que se detectan productos a punto de vencer.<br>
                <strong>Cuando</strong> recibo la alerta.<br>
                <strong>Entonces</strong> los priorizo en la cocina.<br>
                <h5>Escenario 02: Evaluación mensual de reducción.</h5>
                <strong>Dado</strong> que aplico el sistema.<br>
                <strong>Cuando</strong> pasa un mes.<br>
                <strong>Entonces</strong> los desperdicios se reducen al menos un 20%.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU15</td>
            <td>Soporte técnico incluido</td>
            <td><strong>Como</strong> usuario. <strong>Quiero</strong> tener soporte técnico. <strong>Para</strong> resolver problemas con los sensores.</td>
            <td>
                <h5>Escenario 01: Solicitud de soporte.</h5>
                <strong>Dado</strong> que el sensor no responde.<br>
                <strong>Cuando</strong> solicito ayuda.<br>
                <strong>Entonces</strong> recibo soporte en menos de 24h.<br>
                <h5>Escenario 02: Uso del chat de ayuda.</h5>
                <strong>Dado</strong> que tengo una duda.<br>
                <strong>Cuando</strong> uso el chat de ayuda.<br>
                <strong>Entonces</strong> recibo orientación clara.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
    <tr style="text-align:center">
            <td>HU16</td>
            <td>Reporte de productos en mal estado</td>
            <td><strong>Como</strong> supervisor. <strong>Quiero</strong> reportar alimentos dañados. <strong>Para</strong> hacer seguimiento a sus causas.</td>
            <td>
                <h5>Escenario 01: Registro de producto dañado.</h5>
                <strong>Dado</strong> que detecto un alimento podrido.<br>
                <strong>Cuando</strong> lo marco como dañado.<br>
                <strong>Entonces</strong> se crea un registro.<br>
                <h5>Escenario 02: Análisis de recurrencias.</h5>
                <strong>Dado</strong> que analizo el reporte.<br>
                <strong>Cuando</strong> veo recurrencias.<br>
                <strong>Entonces</strong> identifico patrones y ajusto el proceso.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU17</td>
            <td>Integración con hojas de cálculo</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> exportar los datos a Excel. <strong>Para</strong> analizarlos con mi equipo.</td>
            <td>
                <h5>Escenario 01: Exportación de inventario.</h5>
                <strong>Dado</strong> que accedo al módulo de reportes.<br>
                <strong>Cuando</strong> selecciono exportar.<br>
                <strong>Entonces</strong> obtengo un archivo .xlsx.<br>
                <h5>Escenario 02: Análisis con filtros.</h5>
                <strong>Dado</strong> que edito en Excel.<br>
                <strong>Cuando</strong> realizo filtros.<br>
                <strong>Entonces</strong> visualizo las tendencias de consumo.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU18</td>
            <td>Visualización por categorías de producto</td>
            <td><strong>Como</strong> usuario. <strong>Quiero</strong> ver los productos agrupados. <strong>Para</strong> organizar mejor el inventario.</td>
            <td>
                <h5>Escenario 01: Filtro por categoría.</h5>
                <strong>Dado</strong> que accedo al inventario.<br>
                <strong>Cuando</strong> aplico un filtro.<br>
                <strong>Entonces</strong> puedo ver solo carnes, verduras, etc.<br>
                <h5>Escenario 02: Búsqueda eficiente.</h5>
                <strong>Dado</strong> que hay muchos productos.<br>
                <strong>Cuando</strong> uso el buscador.<br>
                <strong>Entonces</strong> los resultados se ordenan por relevancia.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU19</td>
            <td>Entrenamiento inicial</td>
            <td><strong>Como</strong> nuevo usuario. <strong>Quiero</strong> recibir una capacitación. <strong>Para</strong> usar la plataforma correctamente.</td>
            <td>
                <h5>Escenario 01: Capacitación programada.</h5>
                <strong>Dado</strong> que recién contrato el sistema.<br>
                <strong>Cuando</strong> llega el día de capacitación.<br>
                <strong>Entonces</strong> el equipo me enseña en 1 hora.<br>
                <h5>Escenario 02: Aplicación práctica.</h5>
                <strong>Dado</strong> que termino el entrenamiento.<br>
                <strong>Cuando</strong> empiezo a usar la app.<br>
                <strong>Entonces</strong> entiendo todas las funciones básicas.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU20</td>
            <td>Módulo de auditoría</td>
            <td><strong>Como</strong> gerente. <strong>Quiero</strong> saber quién hizo cambios. <strong>Para</strong> tener trazabilidad del inventario.</td>
            <td>
                <h5>Escenario 01: Revisión de historial.</h5>
                <strong>Dado</strong> que se edita un producto.<br>
                <strong>Cuando</strong> reviso la auditoría.<br>
                <strong>Entonces</strong> veo quién, cuándo y qué modificó.<br>
                <h5>Escenario 02: Corrección de errores.</h5>
                <strong>Dado</strong> que hay errores.<br>
                <strong>Cuando</strong> reviso el historial.<br>
                <strong>Entonces</strong> puedo corregirlos.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU21</td>
            <td>Notificaciones de stock crítico</td>
            <td><strong>Como</strong> responsable de compras. <strong>Quiero</strong> recibir alertas cuando un insumo esté por agotarse. <strong>Para</strong> evitar faltantes.</td>
            <td>
                <h5>Escenario 01: Alerta de stock crítico.</h5>
                <strong>Dado</strong> que un producto alcanza el nivel mínimo.<br>
                <strong>Cuando</strong> reviso la app.<br>
                <strong>Entonces</strong> recibo una alerta de stock crítico.<br>
                <h5>Escenario 02: Visualización de cantidades.</h5>
                <strong>Dado</strong> que recibo la alerta.<br>
                <strong>Cuando</strong> ingreso al inventario.<br>
                <strong>Entonces</strong> puedo ver exactamente qué cantidad queda.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU22</td>
            <td>Integración con sistema de pedidos</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> que el sistema se conecte con mi proveedor. <strong>Para</strong> generar pedidos automáticamente.</td>
            <td>
                <h5>Escenario 01: Generación de pre-pedido.</h5>
                <strong>Dado</strong> que un insumo está por agotarse.<br>
                <strong>Cuando</strong> se activa la regla de pedido.<br>
                <strong>Entonces</strong> se genera un pre-pedido al proveedor.<br>
                <h5>Escenario 02: Actualización tras recepción.</h5>
                <strong>Dado</strong> que el pedido se completa.<br>
                <strong>Cuando</strong> llega el producto.<br>
                <strong>Entonces</strong> se actualiza automáticamente el inventario.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU23</td>
            <td>Planes de suscripción escalables</td>
            <td><strong>Como</strong> dueño de restaurante. <strong>Quiero</strong> elegir entre diferentes planes. <strong>Para</strong> pagar solo por lo que necesito.</td>
            <td>
                <h5>Escenario 01: Selección de plan básico.</h5>
                <strong>Dado</strong> que soy un local pequeño.<br>
                <strong>Cuando</strong> contrato el servicio.<br>
                <strong>Entonces</strong> selecciono el plan básico.<br>
                <h5>Escenario 02: Escalado de plan.</h5>
                <strong>Dado</strong> que abro más sucursales.<br>
                <strong>Cuando</strong> actualizo el plan.<br>
                <strong>Entonces</strong> accedo a funciones premium.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU24</td>
            <td>Control de caducidad con código QR</td>
            <td><strong>Como</strong> usuario. <strong>Quiero</strong> escanear productos con código QR. <strong>Para</strong> agilizar el control de fechas.</td>
            <td>
                <h5>Escenario 01: Registro mediante escaneo.</h5>
                <strong>Dado</strong> que un producto tiene QR.<br>
                <strong>Cuando</strong> lo escaneo.<br>
                <strong>Entonces</strong> se registra su fecha de vencimiento.<br>
                <h5>Escenario 02: Actualización automática.</h5>
                <strong>Dado</strong> que el sistema reconoce el código.<br>
                <strong>Cuando</strong> lo almaceno.<br>
                <strong>Entonces</strong> se actualiza automáticamente el inventario.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU25</td>
            <td>Soporte multilenguaje</td>
            <td><strong>Como</strong> trabajador no hispanohablante. <strong>Quiero</strong> poder usar la app en inglés. <strong>Para</strong> entender mejor las funciones.</td>
            <td>
                <h5>Escenario 01: Cambio de idioma.</h5>
                <strong>Dado</strong> que cambio el idioma.<br>
                <strong>Cuando</strong> selecciono inglés.<br>
                <strong>Entonces</strong> toda la interfaz se adapta.<br>
                <h5>Escenario 02: Idioma por usuario.</h5>
                <strong>Dado</strong> que varios trabajadores usan la app.<br>
                <strong>Cuando</strong> acceden con su cuenta.<br>
                <strong>Entonces</strong> la app se muestra en su idioma elegido.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU26</td>
            <td>Análisis de tendencias de consumo</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> ver estadísticas de consumo. <strong>Para</strong> planificar mejor mis compras.</td>
            <td>
                <h5>Escenario 01: Consulta de productos más usados.</h5>
                <strong>Dado</strong> que reviso el módulo de análisis.<br>
                <strong>Cuando</strong> selecciono un rango de fechas.<br>
                <strong>Entonces</strong> veo qué productos se usan más.<br>
                <h5>Escenario 02: Ajuste de pedidos.</h5>
                <strong>Dado</strong> que veo un producto con alta rotación.<br>
                <strong>Cuando</strong> planifico compras.<br>
                <strong>Entonces</strong> ajusto el pedido según el historial.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU27</td>
            <td>Registro de condiciones de almacenamiento</td>
            <td><strong>Como</strong> supervisor. <strong>Quiero</strong> saber si las condiciones fueron correctas durante el día. <strong>Para</strong> evitar riesgos sanitarios.</td>
            <td>
                <h5>Escenario 01: Revisión diaria de condiciones.</h5>
                <strong>Dado</strong> que reviso el registro diario.<br>
                <strong>Cuando</strong> detecto temperaturas fuera del rango.<br>
                <strong>Entonces</strong> se marca en rojo ese día.<br>
                <h5>Escenario 02: Informe de cumplimiento.</h5>
                <strong>Dado</strong> que todo estuvo estable.<br>
                <strong>Cuando</strong> cierro el día.<br>
                <strong>Entonces</strong> se genera un informe de cumplimiento.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>    
    <tbody>
        <tr style="text-align:center">
            <td>HU28</td>
            <td>Soporte en español por WhatsApp</td>
            <td><strong>Como</strong> usuario. <strong>Quiero</strong> contactar soporte por WhatsApp en español. <strong>Para</strong> resolver dudas rápidamente.</td>
            <td>
                <h5>Escenario 01: Atención por mensaje.</h5>
                <strong>Dado</strong> que tengo un problema.<br>
                <strong>Cuando</strong> escribo al número de soporte.<br>
                <strong>Entonces</strong> me responde un agente en español.<br>
                <h5>Escenario 02: Solución rápida.</h5>
                <strong>Dado</strong> que explico el problema.<br>
                <strong>Cuando</strong> recibo la respuesta.<br>
                <strong>Entonces</strong> soluciono el inconveniente en minutos.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU29</td>
            <td>Recomendaciones automáticas de uso</td>
            <td><strong>Como</strong> cocinero. <strong>Quiero</strong> que la app me sugiera usar productos a punto de caducar. <strong>Para</strong> evitar desperdicio.</td>
            <td>
                <h5>Escenario 01: Sugerencia en pantalla principal.</h5>
                <strong>Dado</strong> que un producto vence pronto.<br>
                <strong>Cuando</strong> inicio sesión.<br>
                <strong>Entonces</strong> me aparece una recomendación para usarlo.<br>
                <h5>Escenario 02: Reducción de descartes.</h5>
                <strong>Dado</strong> que sigo la sugerencia.<br>
                <strong>Cuando</strong> uso el producto.<br>
                <strong>Entonces</strong> reduzco los descartes innecesarios.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
    <tbody>
        <tr style="text-align:center">
            <td>HU30</td>
            <td>Evaluación del sistema por los usuarios</td>
            <td><strong>Como</strong> administrador. <strong>Quiero</strong> que los usuarios califiquen el sistema. <strong>Para</strong> saber su nivel de satisfacción.</td>
            <td>
                <h5>Escenario 01: Solicitud de evaluación.</h5>
                <strong>Dado</strong> que pasa un mes de uso.<br>
                <strong>Cuando</strong> el usuario abre la app.<br>
                <strong>Entonces</strong> se le pide que evalúe su experiencia.<br>
                <h5>Escenario 02: Mejora basada en feedback.</h5>
                <strong>Dado</strong> que recibimos feedback.<br>
                <strong>Cuando</strong> lo analizamos.<br>
                <strong>Entonces</strong> mejoramos la plataforma según los comentarios.
            </td>
            <td>EP01</td>
        </tr>
    </tbody>
        
</table>

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :---- | :---- | :---- | :---- | :---- |
| EP01 | Monitoreo inteligente del inventario | Funcionalidades que permiten visualizar, controlar y mantener el estado del inventario en tiempo real. |  |  |
| US01 | Monitoreo en tiempo real | Como gerente. Quiero monitorear las condiciones del inventario en tiempo real. Para evitar pérdidas por mal almacenamiento. | Escenario 01: Actualización de estado. Dado que el sistema esté conectado a sensores IoT, Cuando se detecte un cambio en temperatura, Entonces se actualiza el estado en la app instantáneamente. Escenario 02: Visualización de estado. Dado que los sensores funcionen correctamente, Cuando accedo a la app, Entonces visualizo la temperatura y humedad actuales de los alimentos. | EP01 |
| US02 | Lectura de temperatura desde sensores | Como gerente. Quiero conocer la temperatura del almacén. Para asegurar condiciones óptimas. | Escenario 01: Visualización de temperatura. Dado que el sensor está activo, Cuando abro la app, Entonces me muestra la temperatura en grados. Escenario 02: Alerta por temperatura anómala. Dado que la temperatura es inadecuada, Cuando supera los límites, Entonces se emite una alerta. | EP01 |
| US03 | Historial de temperaturas | Como administrador. Quiero ver un historial de temperatura por producto. Para detectar posibles fallas. | Escenario 01: Revisión ante producto dañado. Dado que un alimento se estropea, Cuando consulto su historial, Entonces veo si hubo cambios bruscos de temperatura. Escenario 02: Consulta por fecha. Dado que accedo a los datos, Cuando selecciono una fecha, Entonces se me muestra la evolución. | EP01 |
| US04 | Análisis de tendencias de consumo | Como administrador. Quiero ver estadísticas de consumo. Para planificar mejor mis compras. | Escenario 01: Consulta de productos más usados. Dado que reviso el módulo de análisis, Cuando selecciono un rango de fechas, Entonces veo qué productos se usan más. Escenario 02: Ajuste de pedidos. Dado que veo un producto con alta rotación, Cuando planifico compras, Entonces ajusto el pedido según el historial. | EP01 |
| US05 | Registro de condiciones de almacenamiento | Como supervisor. Quiero saber si las condiciones fueron correctas durante el día. Para evitar riesgos sanitarios. | Escenario 01: Revisión diaria de condiciones. Dado que reviso el registro diario, Cuando detecto temperaturas fuera del rango, Entonces se marca en rojo ese día. Escenario 02: Informe de cumplimiento. Dado que todo estuvo estable, Cuando cierro el día, Entonces se genera un informe de cumplimiento. | EP01 |
| EP02 | Gestión proactiva de insumos | Funciones para automatizar la gestión del stock, prevenir pérdidas y facilitar el abastecimiento. |  |  |
| US06 | Alertas por fecha de caducidad | Como encargado de almacén. Quiero recibir alertas antes de que un alimento caduque. Para evitar su desperdicio. | Escenario 01: Alerta previa a caducidad. Dado que un producto esté próximo a caducar, Cuando falten menos de 3 días, Entonces el sistema me envía una notificación. Escenario 02: Alerta de producto caducado. Dado que un alimento ya haya caducado, Cuando ingreso al inventario, Entonces se visualiza con una alerta roja. | EP02 |
| US07 | Reportes automáticos de inventario | Como administrador. Quiero recibir reportes automáticos de stock. Para optimizar mis compras semanales. | Escenario 01: Envío de reportes programados. Dado que llegue fin de semana, Cuando sea sábado a las 8 am, Entonces recibo un reporte por correo. Escenario 02: Identificación de productos a reabastecer. Dado que tengo bajo stock, Cuando reviso el reporte, Entonces identifico los productos a reabastecer. | EP02 |
| US08 | Visualización de niveles de stock | Como encargado de compras. Quiero ver el nivel actual de stock. Para saber cuándo hacer pedidos. | Escenario 01: Stock bajo visualizado. Dado que un producto está por agotarse, Cuando reviso el panel, Entonces lo veo en color naranja o rojo. Escenario 02: Stock suficiente visualizado. Dado que hay suficiente stock, Cuando veo el tablero, Entonces el producto aparece en verde. | EP02 |
| US09 | Configuración de alertas personalizadas | Como administrador. Quiero configurar las alertas según mis necesidades. Para priorizar productos críticos. | Escenario 01: Configuración de umbrales. Dado que accedo a configuración, Cuando selecciono un producto, Entonces puedo definir umbrales de alerta. Escenario 02: Notificación personalizada. Dado que configuro alertas por caducidad, Cuando se cumple el plazo, Entonces recibo la notificación según mi configuración. | EP02 |
| US10 | Registro de entrada de productos | Como encargado. Quiero registrar la llegada de productos. Para tener un control preciso del inventario. | Escenario 01: Registro de nuevo lote. Dado que llega un nuevo lote, Cuando ingreso los datos, Entonces el inventario se actualiza automáticamente. Escenario 02: Notificación de omisión. Dado que olvido registrar, Cuando reviso el inventario, Entonces me aparece una notificación de producto sin ingreso. | EP02 |
| US11 | Registro de salida de productos | Como trabajador. Quiero registrar qué productos se usan. Para mantener actualizado el stock. | Escenario 01: Registro de uso. Dado que utilizo un ingrediente, Cuando marco su salida, Entonces el inventario lo descuenta. Escenario 02: Auditoría de omisiones. Dado que un producto no se marca, Cuando hay diferencias, Entonces se registra en una auditoría. | EP02 |
| US12 | Reducción de desperdicio alimentario | Como gerente. Quiero reducir el desperdicio. Para disminuir mis costos. | Escenario 01: Alerta de caducidad próxima. Dado que se detectan productos a punto de vencer, Cuando recibo la alerta, Entonces los priorizo en la cocina. Escenario 02: Evaluación mensual de reducción. Dado que aplico el sistema, Cuando pasa un mes, Entonces los desperdicios se reducen al menos un 20%. | EP02 |
| US13 | Integración con sistema de pedidos | Como administrador. Quiero que el sistema se conecte con mi proveedor. Para generar pedidos automáticamente. | Escenario 01: Generación de pre-pedido. Dado que un insumo está por agotarse, Cuando se activa la regla de pedido, Entonces se genera un pre-pedido al proveedor. Escenario 02: Actualización tras recepción. Dado que el pedido se completa, Cuando llega el producto, Entonces se actualiza automáticamente el inventario. | EP02 |
| US14 | Control de caducidad con código QR | Como usuario. Quiero escanear productos con código QR. Para agilizar el control de fechas. | Escenario 01: Registro mediante escaneo. Dado que un producto tiene QR, Cuando lo escaneo, Entonces se registra su fecha de vencimiento. Escenario 02: Actualización automática. Dado que el sistema reconoce el código, Cuando lo almaceno, Entonces se actualiza automáticamente el inventario. | EP02 |
| US15 | Recomendaciones automáticas de uso | Como cocinero. Quiero que la app me sugiera usar productos a punto de caducar. Para evitar desperdicio. | Escenario 01: Sugerencia en pantalla principal. Dado que un producto vence pronto, Cuando inicio sesión, Entonces me aparece una recomendación para usarlo. Escenario 02: Reducción de descartes. Dado que sigo la sugerencia, Cuando uso el producto, Entonces reduzco los descartes innecesarios. | EP02 |
| EP03 | Experiencia del usuario y usabilidad | Características centradas en la facilidad de uso, accesibilidad y experiencia fluida para el personal del restaurante. |  |  |
| US16 | Interfaz intuitiva | Como trabajador de cocina. Quiero una app sencilla con iconos claros. Para usarla sin complicaciones. | Escenario 01: Navegación sencilla. Dado que ingreso a la app, Cuando navego entre secciones, Entonces entiendo fácilmente las funciones. Escenario 02: Registro rápido. Dado que necesito registrar un nuevo producto, Cuando toco el botón de agregar, Entonces el proceso no toma más de 3 pasos. | EP03 |
| US17 | Acceso multiusuario | Como dueño de restaurante. Quiero que mi equipo tenga cuentas propias. Para dividir responsabilidades. | Escenario 01: Acceso por rol. Dado que tengo diferentes roles, Cuando un cocinero accede, Entonces solo ve lo relevante a cocina. Escenario 02: Gestión de accesos. Dado que soy administrador, Cuando gestiono usuarios, Entonces puedo crear o quitar accesos. | EP04 |
| US18 | Aplicación móvil compatible | Como cocinero. Quiero acceder desde mi celular. Para consultar el inventario sin ir al almacén. | Escenario 01: Acceso desde el móvil. Dado que tengo conexión a internet, Cuando descargo la app, Entonces puedo consultar el inventario desde mi móvil. Escenario 02: Acceso sin conexión. Dado que no tengo red, Cuando accedo a la app, Entonces veo los datos más recientes en caché. | EP03 |
| US19 | Visualización por categorías de producto | Como usuario. Quiero ver los productos agrupados. Para organizar mejor el inventario. | Escenario 01: Filtro por categoría. Dado que accedo al inventario, Cuando aplico un filtro, Entonces puedo ver solo carnes, verduras, etc. Escenario 02: Búsqueda eficiente. Dado que hay muchos productos, Cuando uso el buscador, Entonces los resultados se ordenan por relevancia. | EP03 |
| US20 | Soporte multilenguaje | Como trabajador no hispanohablante. Quiero poder usar la app en inglés. Para entender mejor las funciones. | Escenario 01: Cambio de idioma. Dado que cambio el idioma, Cuando selecciono inglés, Entonces toda la interfaz se adapta. Escenario 02: Idioma por usuario. Dado que varios trabajadores usan la app, Cuando acceden con su cuenta, Entonces la app se muestra en su idioma elegido. | EP03 |
| EP04 | Configuración y administración | Funcionalidades de configuración, seguridad, trazabilidad y administración del sistema por parte del restaurante. |  |  |
| US21 | Adaptabilidad del sistema | Como dueño de restaurante. Quiero que el sistema se adapte a mis instalaciones. Para que funcione sin importar el tamaño. | Escenario 01: Instalación en local mediano. Dado que tengo un restaurante mediano, Cuando instalo los sensores, Entonces se integran sin necesidad de infraestructura extra. Escenario 02: Escalabilidad a cadena. Dado que crezco a una cadena, Cuando amplío el sistema, Entonces la app permite escalar la solución. | EP04 |
| US22 | Soporte técnico incluido | Como usuario. Quiero tener soporte técnico. Para resolver problemas con los sensores. | Escenario 01: Solicitud de soporte. Dado que el sensor no responde, Cuando solicito ayuda, Entonces recibo soporte en menos de 24h. Escenario 02: Uso del chat de ayuda. Dado que tengo una duda, Cuando uso el chat de ayuda, Entonces recibo orientación clara. | EP04 |
| US23 | Reporte de productos en mal estado | Como supervisor. Quiero reportar alimentos dañados. Para hacer seguimiento a sus causas. | Escenario 01: Registro de producto dañado. Dado que detecto un alimento podrido, Cuando lo marco como dañado, Entonces se crea un registro. Escenario 02: Análisis de recurrencias. Dado que analizo el reporte, Cuando veo recurrencias, Entonces identifico patrones y ajusto el proceso. | EP04 |
| US24 | Integración con hojas de cálculo | Como administrador. Quiero exportar los datos a Excel. Para analizarlos con mi equipo. | Escenario 01: Exportación de inventario. Dado que accedo al módulo de reportes, Cuando selecciono exportar, Entonces obtengo un archivo .xlsx. Escenario 02: Análisis con filtros. Dado que edito en Excel, Cuando realizo filtros, Entonces visualizo las tendencias de consumo. | EP04 |
| US25 | Entrenamiento inicial | Como nuevo usuario. Quiero recibir una capacitación. Para usar la plataforma correctamente. | Escenario 01: Capacitación programada. Dado que recién contrato el sistema, Cuando llega el día de capacitación, Entonces el equipo me enseña en 1 hora. Escenario 02: Aplicación práctica. Dado que termino el entrenamiento, Cuando empiezo a usar la app, Entonces entiendo todas las funciones básicas. | EP04 |
| US26 | Módulo de auditoría | Como gerente. Quiero saber quién hizo cambios. Para tener trazabilidad del inventario. | Escenario 01: Revisión de historial. Dado que se edita un producto, Cuando reviso la auditoría, Entonces veo quién, cuándo y qué modificó. Escenario 02: Corrección de errores. Dado que hay errores, Cuando reviso el historial, Entonces puedo corregirlos. | EP04 |
| US27 | Planes de suscripción escalables | Como dueño de restaurante. Quiero elegir entre diferentes planes. Para pagar solo por lo que necesito. | Escenario 01: Selección de plan básico. Dado que soy un local pequeño, Cuando contrato el servicio, Entonces selecciono el plan básico. Escenario 02: Escalado de plan. Dado que abro más sucursales, Cuando actualizo el plan, Entonces accedo a funciones premium. | EP04 |
| US28 | Soporte en español por WhatsApp | Como usuario. Quiero contactar soporte por WhatsApp en español. Para resolver dudas rápidamente. | Escenario 01: Atención por mensaje. Dado que tengo un problema, Cuando escribo al número de soporte, Entonces me responde un agente en español. Escenario 02: Solución rápida. Dado que explico el problema, Cuando recibo la respuesta, Entonces soluciono el inconveniente en minutos. | EP04 |
| US29 | Evaluación del sistema por los usuarios | Como administrador. Quiero que los usuarios califiquen el sistema. Para saber su nivel de satisfacción. | Escenario 01: Solicitud de evaluación. Dado que pasa un mes de uso, Cuando el usuario abre la app, Entonces se le pide que evalúe su experiencia. Escenario 02: Mejora basada en feedback. Dado que recibimos feedback, Cuando lo analizamos, Entonces mejoramos la plataforma según los comentarios. | EP04 |
    

## 3.3. Impact Mapping.

## 3.4. Product Backlog.
| id | epic |



