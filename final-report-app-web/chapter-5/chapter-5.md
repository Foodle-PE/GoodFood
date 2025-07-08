# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

En esta sección, se incluirá los productos de software que se usaron el en proyecto.

Se clasificará en el siguiente orden:
- Producto UX/UI Design.
- Software Development.
- Software Deployment.

**Producto UX/UI Design:**<br>
- [Figma](https://www.figma.com/) - Herramienta de diseño colaborativo para crear prototipos y maquetas de interfaces de usuario.
- [Lucidchart](https://lucid.app/) - Herramienta de diagramación para crear diagramas de flujo, wireframes y otros elementos visuales.
- [Uxpressia](https://uxpressia.com/) - Herramienta de diseño centrada en el usuario para crear mapas de empatía y customer journey maps.
- [Structurizr](https://structurizr.com/) - Herramienta de modelado de software para crear diagramas de arquitectura y diseño orientado a dominios.

**Software Development:**<br>
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) - Entorno de desarrollo integrado (IDE) para Java y otros lenguajes de programación.
- [Github](https://www.github.com/) - Plataforma de control de versiones y colaboración para el desarrollo de software.
- [Visual Studio Code](https://code.visualstudio.com/) - Editor de código fuente ligero y potente para varios lenguajes de programación.
- [HTML](https://www.w3.org/TR/html52/) - Lenguaje de marcado para la creación de páginas web.
- [CSS](https://www.w3.org/Style/CSS/) - Lenguaje de estilo para la presentación de documentos HTML.

**Software Deployment:**<br>
- GitHub Pages - Servicio de alojamiento web para proyectos estáticos.

### 5.1.2. Source Code Management.
Para el sistema, se usará Github como herramienta de gestión de código fuente. Se creará un repositorio para el proyecto, donde se almacenará todo el código fuente y los documentos relacionados.

**URL de la organización:** https://github.com/Foodle-PE <br>
**URL del repositorio del informe:** https://github.com/Foodle-PE/GoodFood <br>
**URL del repositorio de la landing page:** https://github.com/Foodle-PE/Landing-Page <br>
**URL del frontend deployment:** https://foodle-pe.github.io/Frontend/<br>
**URL del repositorio del backend:** https://github.com/Foodle-PE/GoodFood-Platform<br>

Para el modelo de desarrollo, se decidió usar GitFlow como modelo de ramificación. Este modelo permite una gestión eficiente de las ramas y facilita la colaboración entre los desarrolladores.
Se crearán las siguientes ramas:
- **dev:** Rama principal de desarrollo, donde se integrarán todas las características y correcciones de errores.
- **chapter-1:** Rama para el desarrollo del capítulo 1 del informe.
- **chapter-2:** Rama para el desarrollo del capítulo 2 del informe.
- **chapter-3:** Rama para el desarrollo del capítulo 3 del informe.
- **chapter-4:** Rama para el desarrollo del capítulo 4 del informe.
- **chapter-5:** Rama para el desarrollo del capítulo 5 del informe.

### 5.1.3. Source Code Style Guide & Conventions.

**Principios Generales**<br>
- **Idioma estándar:** Todo el código está en inglés.

- **Legibilidad primero:** Se prefiere nombres descriptivos, claros y significativos sobre abreviaciones o tecnicismos innecesarios.

- **Formato consistente:** Se sigue el mismo estilo en todo el equipo y en todos los lenguajes.

- **Nombres significativos:** Se ua sustantivos para clases, nombres de archivos y componentes. Verbos para funciones o métodos.

**HTML & CSS**<br>
- Archivos HTML terminan en .html

- Archivos CSS terminan en .css

- Se usa kebab-case para nombres de clases y archivos:
  Ej: main-header, product-card, login-form.

**HTML**
- Elementos estructurados correctamente (header, section, nav, footer).

- Se usa alt para imágenes y aria-* para accesibilidad.

### 5.1.4. Software Deployment Configuration.
En esta sección se describe la configuración necesaria para desplegar cada uno de los componentes del proyecto: Landing Page, Web Services y Frontend Web Application. El objetivo es garantizar que, a partir del código fuente almacenado en los repositorios, se pueda lograr una publicación funcional y accesible para los usuarios.

#### Despliegue de Landing Page

La **Landing Page** fue desarrollada usando HTML y CSS, y fue desplegada mediante **GitHub Pages**, un servicio gratuito de hosting para sitios estáticos.

**Pasos de despliegue:**
1. Se creó el repositorio `landing-page` en GitHub.
2. Se subió el código fuente HTML, CSS y recursos estáticos.
3. Desde la configuración del repositorio, se activó **GitHub Pages** seleccionando la rama `main` y la carpeta raíz (`/`).
4. Automáticamente, GitHub publicó el sitio web en una URL pública.

**Repositorio:** https://github.com/Foodle-PE/Landing-Page <br>
**URL desplegada:** https://foodle-pe.github.io/Landing-Page/ <br>

**Evidencia de despliegue:**

![github_deployment](https://github.com/user-attachments/assets/827ba827-4788-4045-8084-4f4d4dfbb069)


### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

<table>
<tr>
    <th colspan="5">Sprint 1</th>
    <th colspan="9">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-06-18</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">5:30 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Torres Flores, Paolo Alessandro</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Torres Flores, Paolo Alessandro; Aguirre Castillo, Sergio Cesar; Muñoz Machuca, Maria Elena; Montañez Moreno, Luis Angel</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Review Summary</td>
    <td colspan="8">En esta primera sección de la tercera entrega se planteó el desarrollo de la landing page para el proyecto de GoodFood.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Retrospective Summary</td>
    <td colspan="8">En esta sección todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades realizando la landing page</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Goal</td>
    <td colspan="8">
Desarrollar y desplegar una landing page que detalle las principales funcionalidades de la aplicación web.</td>
</tr>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators 
<table>
  <tr>
    <td>Team Member</td>
    <th>Paolo Alessandro Torres Flores</th>
    <th>Sergio Cesar Aguirre Castillo</th>
    <th>Maria Elena Muñoz Machuca</th>
    <th>Luis Angel Montañez Moreno</th>
  </tr>
  <tr>
    <td>Github Username</td>
    <td>PaLeToFo</td>
    <td>Aguirrat157</td>
    <td>maria-mm0907</td>
    <td>Luiso-AM</td>
  </tr>
  <tr>
    <td>Leader (L) / Collaborator (C)</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
</table>

#### 5.2.1.3. Sprint backlog 1
![Screenshot 2025-04-26 004012](https://github.com/user-attachments/assets/288ff5bf-1ecc-4935-a629-5bd286dac2eb)

| Sprint \# |          Sprint 1          |  |  |  |  |  |  |
| :---: |:--------------------------:| :---: | :---: | :---: | :---: | ----- | :---: |
| User Story |                            | Work-Item / Task |  |  |  |  |  |
| ID |           Title            | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| US31 |       Sección Header       | US31-1 | Implementación de la barra de navegación | Como visitante quiero acceder a la barra de navegación para moverse rápidamente a cualquier sección de la página. | 3 | Luis | Done |
| US32 |    Sección Introducción    | US32-1 | Implementacion de Seccion Introducción | Como visitante quiero ver un mensaje de bienvenida y una descripción para entender el funcionamiento de GoodFood. | 3 | Paolo | Done |
| US33 |      Sección Features      | US33-1 | Implementación de la sección features | Como visitante quiero ver las características que hacen a GoodFood distinta de la competencia para elegir una plataforma. | 4 | Sergio | Done |
| US34 | Sección Acerca de nosotros | US34-1 | Implementación Sección acerca de nosotros | Como visitante quiero conocer la misión y visión de GoodFood para conocer más acerca de sus objetivos.  | 2 | Maria | Done |
| US35 |     Sección Beneficios     | US35-1 | Implementacion de Beneficios | Como visitante quiero conocer sobre los beneficios que me ofrece GoodFood para poder elegir si se lainean con mis necesidades | 4 | Luis Miguel | Done |
| US36 |      Sección Contacto      | US36-1 | Implementacion de sección contacto | Como visitante quiero poder contactarme en caso requiera más información parapoder conocer mejor sobre el producto | 2 | Paolo | Done |
| US49 |           Footer           | US49-1 | Implementacion de Footer | Como visitante quiero visualizar las redes sociales de la aplicación para poder ver las novedades que tienen para ofrecer. | 2 | Luis | Done |


| Sprint # |                Sprint 1                 |  |  |  |  |  |        |
| :---: |:---------------------------------------:| :---: | :---: | :---: | :---: | ----- |:------:|
| Technical Story |                                         | Work-Item / Task |  |  |  |  |        |
| ID |                  Title                  | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| TS01 |        Implementación de login con validación         | TS01-1 | Crear pantalla de inicio de sesión | Programación del formulario de login con validación de campos. Se incluye lógica de registro automático si no se encuentra el usuario. | 5 | Paolo |  Done  |
| TS02 |         Clasificación dinámica de alertas         | TS01-1 | Clasificar Alertas por tipo | Programar la estructura de datos y lógica de frontend para clasificar alertas por tipo (caducidad, temperatura, etc.). | 5 | Luis |  Done  |
| TS03 |         	Visualización de severidad con colores         | TS03-1 | Visualizar severidad de alertas por colores | Implementar diseño visual (CSS + lógica) para diferenciar niveles de severidad de alertas mediante códigos de color. | 3 | Maria |  Done  |
| TS04 |         	Gráficos de sensores en tiempo real         | TS04-1 | Generar gráficos de sensores | Integrar biblioteca de gráficos para visualizar datos en tiempo real desde sensores (temperatura, gas, etc.). | 5 | Sergio |  Done  |
| TS05 |         Implementación de toolbar funcional       | TS05-1 | 	Visualizar opciones de navegación | Construcción de toolbar con links funcionales a Inventario, Alertas y Sensores. Integración con rutas y componentes. | 3 | Paolo |  Done  |
| TS06 |         Sistema de feedback al usuario        | TS06-1 | Mostrar mensajes de feedback | Implementar mensajes (toasts, modales, alertas) en eventos clave: login, carga de sensores, errores de red. | 3 | Paolo |  Done  |
| TS07 |         Registro de productos en inventario       | TS06-1 | Ingresar productos al inventario | Desarrollar formulario para agregar productos con campos validados: nombre, expiración, cantidad. Guardado en base de datos. | 3 | Paolo |  Done  |

#### 5.2.1.4. Development Evidence for Sprint Review
![WhatsApp Image 2025-04-25 at 22 04 57_f0943c99](https://github.com/user-attachments/assets/2b793699-ab56-4de1-b47c-52b62b2a124f)

Aquí podemos notar como está conformado el grupo de trabajo dentro de la organización.

![WhatsApp Image 2025-04-25 at 22 06 51_15ec1a09](https://github.com/user-attachments/assets/2d24e1b9-9811-450f-b746-15b3fd9b62d4)

#### 5.2.1.5. Execution Evidence for Sprint Review 
Aquí podemos notar la aplicación en ejecución luego de los sprints realizados.

![goodfood1](https://github.com/user-attachments/assets/5a0a08d5-1f59-43d1-87b0-52ab8dfd59a4)


Aquí vemos la evidencia de la creación de dichos repositorios mencionados con anterioridad.

![goodfood2](https://github.com/user-attachments/assets/9820a42c-1dfb-4e84-9e66-623ce6fde8d6)


Aquí podemos notar la ejecución de los commits a lo largo del reporte

![goodfood3](https://github.com/user-attachments/assets/2ad4c92c-59ba-484d-bacf-247c940ca573)


#### 5.2.1.6. Services Documentation Evidence for Sprint Review. 
En esta sección se evidencia el servicio documentado al detalle dentro del reporte.

![SERVICES DOC EVIDENCE ](https://github.com/user-attachments/assets/39057e9d-016e-41c5-b1ff-f0830db1754a)

#### 5.2.1.7. Software Deployment Evidence for Sprint Review. 
Aquí podemos evidenciar como ya se realizaron las tareas y no hay ningún error que corregir.

![SOFTWARE DEPLOYMENT EVIDENCE](https://github.com/user-attachments/assets/9717afc4-86e6-4037-ab2d-8e640fa81ba4)

#### 5.2.1.8. Team Collaboration Insights during Sprint. 
![image](https://github.com/user-attachments/assets/447e3f7f-64aa-4615-90c3-2b8bf14322d3)


### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2
<table>
<tr>
    <th colspan="5">Sprint 2</th>
    <th colspan="9">Sprint 2</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-06-18</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">5:30 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Torres Flores, Paolo Alessandro</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Torres Flores, Paolo Alessandro; Aguirre Castillo, Sergio Cesar; Muñoz Machuca, Maria Elena; Montañez Moreno, Luis Angel</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Review Summary</td>
    <td colspan="8">En esta primera sección de la segunda entrega se planteó el desarrollo del frontend para el proyecto de GoodFood.</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Retrospective Summary</td>
    <td colspan="8">En esta sección todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades realizando el frontend</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Goal</td>
    <td colspan="8">
Desarrollar y desplegar una capa de presentación que muestre las principales funcionalidades de la aplicación web.</td>
</tr>
</table>
#### 5.2.2.2. Aspect Leaders and Collaborators 
<table>
  <tr>
    <td>Team Member</td>
    <th>Paolo Alessandro Torres Flores</th>
    <th>Sergio Cesar Aguirre Castillo</th>
    <th>Maria Elena Muñoz Machuca</th>
    <th>Luis Angel Montañez Moreno</th>
  </tr>
  <tr>
    <td>Github Username</td>
    <td>PaLeToFo</td>
    <td>Aguirrat157</td>
    <td>maria-mm0907</td>
    <td>Luiso-AM</td>
  </tr>
  <tr>
    <td>Leader (L) / Collaborator (C)</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
</table>

#### 5.2.2.3. Sprint backlog 2
| Sprint # |                Sprint 2                 |  |  |  |  |  |        |
| :---: |:---------------------------------------:| :---: | :---: | :---: | :---: | ----- |:------:|
| User Story |                                         | Work-Item / Task |  |  |  |  |        |
| ID |                  Title                  | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
  | US01 |        Monitoreo en tiempo real         | US01-1 | Implementar monitoreo en tiempo real | Como gerente quiero monitorear las condiciones del inventario en tiempo real para evitar pérdidas por mal almacenamiento. | 5 | Paolo |  Done  |
| US02 |     Alertas por fecha de caducidad      | US02-1 | Crear sistema de alertas para caducidad | Como encargado quiero recibir alertas para evitar desperdicio. | 3 | Sergio |  Done  |
| US03 |   Reportes automáticos de inventario    | US03-1 | Implementar reportes automáticos | Como administrador quiero reportes automáticos de stock para optimizar compras. | 5 | Sergio |  Done  |
| US04 |           Interfaz intuitiva            | US04-1 | Diseñar interfaz sencilla con iconos claros | Como trabajador quiero una app sencilla para usar sin complicaciones. | 2 |  Maria Elena |  Done  |
| US05 |    Visualización de niveles de stock    | US05-1 | Visualizar niveles de stock actuales | Como encargado quiero ver el nivel actual para saber cuándo pedir. | 3 | Paolo |  Done  |
| US06 | Configuración de alertas personalizadas | US06-1 | Permitir configurar alertas personalizadas | Como administrador quiero priorizar productos críticos. | 3 | Paolo |  Done  |
| US07 |           Acceso multiusuario           | US07-1 | Implementar cuentas para el equipo | Como dueño quiero cuentas propias para dividir responsabilidades. | 3 | Maria Elena |  Done  |
| US08 |  Lectura de temperatura desde sensores  | US08-1 | Integrar lectura de sensores IoT | Como gerente quiero conocer temperatura del almacén. | 5 | Paolo |  Done  |
| US09 |        Adaptabilidad del sistema        | US09-1 | Adaptar sistema a diferentes tamaños | Como dueño quiero que funcione sin importar tamaño. | 2 | Luis |  Done  |
| US11 |    Registro de entrada de productos     | US11-1 | Registrar llegada de productos | Como encargado quiero control preciso del inventario. | 2 | Paolo |  Done  |
| US12 |     Registro de salida de productos     | US12-1 | Registrar productos usados y actualizar stock | Como trabajador quiero mantener stock actualizado. | 2 | Luis |  Done  |
| US13 |       Aplicación móvil compatible       | US13-1 | Acceso móvil al inventario | Como cocinero quiero consultar inventario desde celular. | 3 | Luis |  Done  |
| US14 |  Reducción de desperdicio alimentario   | US14-1 | Implementar alertas para reducir desperdicios | Como gerente quiero disminuir costos. | 2 | Paolo |  Done  |
| US15 |        Soporte técnico incluido         | US15-1 | Implementar soporte técnico para sensores | Como usuario quiero resolver problemas rápido. | 1 | Luis |  Done  |
| US21 |     Notificaciones de stock crítico     | US21-1 | Crear alertas por stock crítico | Como responsable quiero alertas para evitar faltantes. | 2 | Maria Elena |  Done  |
| US25 |          Soporte multilenguaje          | US25-1 | Agregar soporte multilenguaje | Como trabajador quiero usar la app en inglés para mejor comprensión. | 1 | Maria Elena |  Done  |

| Sprint # |                Sprint 2                 |  |  |  |  |  |        |
| :---: |:---------------------------------------:| :---: | :---: | :---: | :---: | ----- |:------:|
| Technical Story |                                         | Work-Item / Task |  |  |  |  |        |
| ID |                  Title                  | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| TS01 |        Pantalla de inicio de sesión con validación de campos         | TS01-1 | Crear pantalla de inicio de sesión | Crear una pantalla de login con validación básica (correo y contraseña). Si el usuario no existe, se debe mostrar una opción para registrarse automáticamente. | 5 | Paolo |  Done  |
| TS02 |         Visualización de alertas clasificadas por tipo         | TS01-2 | Clasificar Alertas por tipo | Diseñar una sección donde se muestren las alertas clasificadas por tipo: recordatorio de fecha de expiración, temperatura, etc. | 5 | Luis |  Done  |
| TS03 |         Indicador visual de severidad en las alertas         | TS03-1 | Visualizar severidad de alertas por colores | Agregar colores para distinguir alertas según severidad (Alta, Media, Baja). | 3 | Maria |  Done  |
| TS04 |         Renderizado de gráficos de sensores en tiempo real         | TS04-1 | Generar gráficos de sensores | Mostrar gráficos en tiempo real con los datos de sensores (temperatura, gas, etc.) | 5 | Sergio |  Done  |
| TS05 |         Toolbar con opciones de navegación        | TS05-1 | Visualizar opciones de inventario, alertas y sensores | Mostrar opciones en la barra de navegación como Inventario, Alertas y Sensores | 3 | Paolo |  Done  |
| TS06 |         Mensajes de feedback al usuario        | TS06-1 | Mostrar mensajes de feedback al usuario | Implementar notificaciones y mensajes para dar feedback durante operaciones como login, carga de alertas y sensores. | 3 | Paolo |  Done  |
| TS07 |         Productos agregados al inventario       | TS06-1 | Ingresar productos al inventario | Ingresar productos al inventario y llenar los campos de nombre, fecha de expiración y cantidad. | 3 | Paolo |  Done  |

![image](https://github.com/user-attachments/assets/78b76df2-1bc8-499f-9afd-79a20060c8fa)

#### 5.2.2.4. Development Evidence for Sprint Review
![image](https://github.com/user-attachments/assets/1540cb14-c4d3-4071-866e-bbcb098f1212)
Aquí podemos notar como está conformado el grupo de trabajo dentro de la organización.


![image](https://github.com/user-attachments/assets/b7b68bb0-cef3-40e4-befe-69bbb9de27f5)


#### 5.2.2.5. Execution Evidence for Sprint Review

Aquí podemos notar la aplicación en ejecución luego de los sprints realizados.

![image](https://github.com/user-attachments/assets/723f828d-1fce-4993-8ccd-43be552219d4)

![image](https://github.com/user-attachments/assets/b2611285-1c13-4077-a108-61abbb230dbb)

![image](https://github.com/user-attachments/assets/a50836b0-ddeb-4c6a-9183-f6012d104570)


#### 5.2.2.6. Services Documentation Evidence for Sprint Review. 
En esta sección se evidencia el servicio documentado al detalle dentro del reporte.

![SERVICES DOC EVIDENCE ](https://github.com/user-attachments/assets/39057e9d-016e-41c5-b1ff-f0830db1754a)

#### 5.2.2.7. Software Deployment Evidence for Sprint Review.
Aquí podemos evidenciar como ya se realizaron el deploy del frontend

![image](https://github.com/user-attachments/assets/4acea044-bc74-4fe4-ae0c-3ac1fa6ee7b0)

#### 5.2.2.8. Team Collaboration Insights during Sprint. 
![image](https://github.com/user-attachments/assets/e345c248-ab7d-4454-a867-62e9c3b9feee)


### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning 3
<table>
<tr>
    <th colspan="5">Sprint 3</th>
    <th colspan="9">Sprint 3</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-06-18</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">5:30 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Torres Flores, Paolo Alessandro</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Torres Flores, Paolo Alessandro; Aguirre Castillo, Sergio Cesar; Rojas Piñero, Luis Miguel; Muñoz Machuca, Maria Elena; Montañez Moreno, Luis Angel</td>
</tr>
<tr>
    <td colspan="5">Sprint 3 Review Summary</td>
    <td colspan="8">En esta primera sección de la tercera entrega se planteó el desarrollo del backend para el proyecto de GoodFood.</td>
</tr>
<tr>
    <td colspan="5">Sprint 3 Retrospective Summary</td>
    <td colspan="8">En esta sección todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades realizando el backend</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal</td>
</tr>
<tr>
    <td colspan="5">Sprint 3 Goal</td>
    <td colspan="8">
Desarrollar y desplegar una capa de datos que contenga datos de las principales funcionalidades de la aplicación web.</td>
</tr>
</table>

#### 5.2.3.2. Aspect Leaders and Collaborators 
<table>
  <tr>
    <td>Team Member</td>
    <th>Paolo Alessandro Torres Flores</th>
    <th>Sergio Cesar Aguirre Castillo</th>
    <th>Maria Elena Muñoz Machuca</th>
    <th>Luis Angel Montañez Moreno</th>
  </tr>
  <tr>
    <td>Github Username</td>
    <td>PaLeToFo</td>
    <td>Aguirrat157</td>
    <td>maria-mm0907</td>
    <td>Luiso-AM</td>
  </tr>
  <tr>
    <td>Leader (L) / Collaborator (C)</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
</table>
#### 5.2.3.3. Sprint backlog 3

| Sprint # | Sprint 3                              |               |       |            |        |               |         |
|:--------:|:--------------------------------------:|:-------------:|:-----:|:----------:|:------:|:-------------:|:-------:|
| User Story |                                      | Work-Item / Task            |       | Descripción                                                  | Estimación (Horas) | Asignado a    | Estado  |
| ID     | Título                                  | ID            | Título | Descripción                                                  | Estimación (Horas) | Asignado a    | Estado  |
| US01   | Monitoreo en tiempo real                | US01-1        | Implementar monitoreo en tiempo real | Como gerente quiero monitorear las condiciones del inventario en tiempo real para evitar pérdidas por mal almacenamiento. | 5                   | Paolo         | Done    |
| US02   | Alertas por fecha de caducidad          | US02-1        | Crear sistema de alertas para caducidad | Como encargado quiero recibir alertas para evitar desperdicio. | 3                   | Sergio        | Done    |
| US03   | Reportes automáticos de inventario      | US03-1        | Implementar reportes automáticos | Como administrador quiero reportes automáticos de stock para optimizar compras. | 5                   | Sergio        | Done    |
| US04   | Interfaz intuitiva                      | US04-1        | Diseñar interfaz sencilla con iconos claros | Como trabajador quiero una app sencilla para usar sin complicaciones. | 2                   | Maria Elena   | Done    |
| US05   | Visualización de niveles de stock       | US05-1        | Visualizar niveles de stock actuales | Como encargado quiero ver el nivel actual para saber cuándo pedir. | 3                   | Paolo         | Done    |
| US06   | Configuración de alertas personalizadas | US06-1        | Permitir configurar alertas personalizadas | Como administrador quiero priorizar productos críticos. | 3                   | Paolo         | Done    |
| US07   | Acceso multiusuario                     | US07-1        | Implementar cuentas para el equipo | Como dueño quiero cuentas propias para dividir responsabilidades. | 3                   | Maria Elena   | Done    |
| US08   | Lectura de temperatura desde sensores   | US08-1        | Integrar lectura de sensores IoT | Como gerente quiero conocer temperatura del almacén. | 5                   | Paolo         | Done    |
| US09   | Adaptabilidad del sistema               | US09-1        | Adaptar sistema a diferentes tamaños | Como dueño quiero que funcione sin importar tamaño. | 2                   | Luis          | Done    |
| US11   | Registro de entrada de productos        | US11-1        | Registrar llegada de productos | Como encargado quiero control preciso del inventario. | 2                   | Paolo         | Done    |
| US12   | Registro de salida de productos         | US12-1        | Registrar productos usados y actualizar stock | Como trabajador quiero mantener stock actualizado. | 2                   | Luis          | Done    |
| US13   | Aplicación móvil compatible             | US13-1        | Acceso móvil al inventario | Como cocinero quiero consultar inventario desde celular. | 3                   | Luis          | Done    |
| US14   | Reducción de desperdicio alimentario    | US14-1        | Implementar alertas para reducir desperdicios | Como gerente quiero disminuir costos. | 2                   | Paolo         | Done    |
| US15   | Soporte técnico incluido                | US15-1        | Implementar soporte técnico para sensores | Como usuario quiero resolver problemas rápido. | 1                   | Luis          | Done    |
| US21   | Notificaciones de stock crítico         | US21-1        | Crear alertas por stock crítico | Como responsable quiero alertas para evitar faltantes. | 2                   | Maria Elena   | Done    |
| US25   | Soporte multilenguaje                   | US25-1        | Agregar soporte multilenguaje | Como trabajador quiero usar la app en inglés para mejor comprensión. | 1                   | Maria Elena   | Done    |


| Sprint # |                Sprint 3                 |  |  |  |  |  |        |
| :---: |:---------------------------------------:| :---: | :---: | :---: | :---: | ----- |:------:|
| Technical Story |                                         | Work-Item / Task |  |  |  |  |        |
| ID |                  Title                  | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| TS08 | Integración de monitoreo en tiempo real       | TS08-1              | Programar monitoreo en tiempo real         | Conectar backend con sensores para obtener datos en vivo y mostrarlos en frontend con actualización automática. | 5          | Paolo          | Done   |
| TS09 | Sistema de alertas por fecha de caducidad     | TS09-1              | Implementar lógica de alertas por fechas   | Desarrollar algoritmo que calcule la proximidad de vencimiento y dispare alertas automáticas.             | 3          | Sergio         | Done   |
| TS10 | Generación de reportes automáticos            | TS10-1              | Crear backend para reportes en PDF/Excel   | Automatizar generación de reportes usando cron jobs o tareas programadas y exportarlos en formato legible. | 5          | Sergio         | Done   |
| TS11 | Diseño de interfaz intuitiva                  | TS11-1              | Aplicar diseño limpio con iconografía clara| Usar principios UX/UI para una interfaz amigable, con íconos representativos y navegación simple.         | 2          | Maria Elena    | Done   |
| TS12 | Visualización de niveles de stock             | TS12-1              | Crear componente visual de stock           | Implementar vista de stock con barras, colores y filtros por categoría.                                  | 3          | Paolo          | Done   |
| TS13 | Configuración personalizada de alertas        | TS13-1              | Desarrollar panel de configuración de alertas | Permitir al usuario establecer umbrales y preferencias para distintos productos desde el frontend.       | 3          | Paolo          | Done   |
| TS14 | Sistema multiusuario con roles                | TS14-1              | Crear sistema de autenticación por rol     | Implementar login para distintos tipos de usuario (admin, empleado) y limitar accesos por permisos.       | 3          | Maria Elena    | Done   |
| TS15 | Lectura de sensores IoT                       | TS15-1              | Conectar sensores físicos con backend      | Usar protocolo MQTT o API REST para obtener datos de temperatura desde sensores físicos.                  | 5          | Paolo          | Done   |
| TS16 | Diseño responsive y adaptable                 | TS16-1              | Adaptar UI para múltiples tamaños de pantalla | Utilizar diseño responsive (media queries, Flexbox/Grid) para compatibilidad con distintos dispositivos. | 2          | Luis           | Done   |
| TS17 | Registro de entrada de productos              | TS17-1              | Programar formulario de ingreso al inventario | Crear formulario con validaciones para registrar entradas de productos y actualizar la base de datos.    | 2          | Paolo          | Done   |
| TS18 | Registro de salida de productos               | TS18-1              | Programar formulario de salida y actualización de stock | Registrar productos utilizados y reflejar la salida en el sistema, validando cantidad mínima.   | 2          | Luis           | Done   |
| TS19 | Acceso móvil al inventario                    | TS19-1              | Optimizar interfaz móvil                   | Mejorar diseño móvil y permitir acceso vía navegadores móviles o app progresiva.                         | 3          | Luis           | Done   |
| TS20 | Sistema de alertas para reducción de desperdicio | TS20-1            | Vincular alertas con indicadores de desperdicio | Programar notificaciones cuando los productos estén por vencer o no se muevan en inventario.         | 2          | Paolo          | Done   |
| TS21 | Soporte técnico para sensores                 | TS21-1              | Crear módulo de diagnóstico de sensores     | Implementar vista para revisar estado de sensores y enviar reporte de fallos.                             | 1          | Luis           | Done   |
| TS22 | Notificaciones por stock crítico              | TS22-1              | Implementar alerta de umbral mínimo de stock | Disparar notificaciones automáticas cuando un producto esté por debajo del stock definido.               | 2          | Maria Elena    | Done   |
| TS23 | Soporte multilenguaje                         | TS23-1              | Implementar sistema i18n                   | Usar librería de internacionalización y cargar traducciones dinámicamente para español e inglés.         | 1          | Maria Elena    | Done   |

![Screenshot 2025-05-14 192919](https://github.com/user-attachments/assets/eda64bd5-ca84-4fce-979e-39ae3f21b9c2)

#### 5.2.3.4. Development Evidence for Sprint Review
![image](https://github.com/user-attachments/assets/133136fc-8417-4ad1-b180-1fb896806ea5)


Aquí podemos notar como está conformado el grupo de trabajo dentro de la organización.

![image](https://github.com/user-attachments/assets/2574c336-aa27-42e1-bf80-dab157685c51)

#### 5.2.3.5. Execution Evidence for Sprint Review 
Aquí podemos notar la aplicación en ejecución luego de los sprints realizados.

![image](https://github.com/user-attachments/assets/138b6c14-5349-436b-92ba-30f01af2e421)

![image](https://github.com/user-attachments/assets/44d6704b-129c-4fb6-b272-2265d3ee5dcb)


![image](https://github.com/user-attachments/assets/8263a0a2-6538-4b9b-a3b4-d23dd652ce4b)

#### 5.2.3.6. Services Documentation Evidence for Sprint Review. 
En esta sección se evidencia el servicio documentado al detalle dentro del reporte.

![SERVICES DOC EVIDENCE ](https://github.com/user-attachments/assets/39057e9d-016e-41c5-b1ff-f0830db1754a)

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
Aquí podemos evidenciar como ya se realizaron el deploy del backend
![image](https://github.com/user-attachments/assets/39ef328b-aba8-41d5-b9ab-80c758054b63)

Se puede evdenciar como se conecta con el repositorio de github
![image](https://github.com/user-attachments/assets/237850a8-89d0-4b65-9428-6ad6bf51922c)

#### 5.2.3.7. Software Deployment Evidence for Sprint Review. 
#### 5.2.3.8. Team Collaboration Insights during Sprint. 
Los commits realizados por Seratt15a se perdieron debido a que la cuenta es inrecuperable y se decidió cambiarla a otra. Los commits generados por Luiso_AM también son la suma del trabajo de Seratt15a ya que trabajan el mismo bounded context.

![image](https://github.com/user-attachments/assets/d8e30501-f53a-4bdc-8ba8-53e8100c0d71)


### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning 4.

<table>
  <tr>
    <th colspan="5">Sprint 4</th>
    <th colspan="8">Sprint 4</th>
  </tr>
  <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-07-04</td>
  </tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">6:00 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord</td>
  </tr>
  <tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Torres Flores, Paolo Alessandro</td>
  </tr>
  <tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">
      Torres Flores, Paolo Alessandro; Aguirre Castillo, Sergio Cesar; 
      Muñoz Machuca, Maria Elena; Montañez Moreno, Luis Angel
    </td>
  </tr>
  <tr>
    <td colspan="5">Sprint 4 Review Summary</td>
    <td colspan="8">
      En esta sección se consolidó la funcionalidad de alertas, edición de perfil y actualización de APIs, 
      asegurando la integración efectiva entre frontend y backend del sistema GoodFood.
    </td>
  </tr>
  <tr>
    <td colspan="5">Sprint 4 Retrospective Summary</td>
    <td colspan="8">
      Se destacó el trabajo colaborativo y la mejora en la comunicación del equipo. Se reconoció 
      la necesidad de planificar mejor los tiempos para tareas dependientes entre frontend y backend.
    </td>
  </tr>
  <tr>
    <td colspan="13">Sprint Goal</td>
  </tr>
  <tr>
    <td colspan="5">Sprint 4 Goal</td>
    <td colspan="8">
      Consolidar el módulo de gestión de alertas y permitir la edición de datos del usuario, 
      asegurando que todas las APIs necesarias estén protegidas y conectadas con el frontend.
    </td>
  </tr>
</table>


#### 5.2.4.2. Aspect Leaders and Collaborators 
<table>
  <tr>
    <td>Team Member</td>
    <th>Paolo Alessandro Torres Flores</th>
    <th>Sergio Cesar Aguirre Castillo</th>
    <th>Maria Elena Muñoz Machuca</th>
    <th>Luis Angel Montañez Moreno</th>
  </tr>
  <tr>
    <td>Github Username</td>
    <td>PaLeToFo</td>
    <td>Aguirrat157</td>
    <td>maria-mm0907</td>
    <td>Luiso-AM</td>
  </tr>
  <tr>
    <td>Leader (L) / Collaborator (C)</td>
    <td>L</td>
    <td>C</td>
    <td>C</td>
    <td>C</td>
  </tr>
</table>
#### 5.2.4.3. Sprint backlog 4

| Sprint #   | Sprint 4                               |                   |       |         |                    |               |         |
|:----------:|:---------------------------------------:|:-----------------:|:-----:|:-------:|:------------------:|:-------------:|:-------:|
| User Story |                                         | Work-Item / Task  |       | Descripción                                      | Estimación (Horas) | Asignado a    | Estado  |
| ID         | Título                                  | ID                | Título                                  | Descripción                                                                                          | Estimación (Horas) | Asignado a    | Estado  |
| US50       | Gestión de Alertas                      | US50-1            | Crear endpoint para listar alertas     | Como usuario quiero poder ver todas mis alertas activas para saber qué acciones tomar.              | 4                   | Sergio        | Done    |
|            |                                         | US50-2            | Crear endpoint para cerrar alertas     | Como usuario quiero cerrar alertas que ya no son relevantes para mantener mi bandeja organizada.     | 3                   | Luis Angel    | Done    |
|            |                                         | US50-3            | Crear endpoint para historial de alertas | Como usuario quiero ver el historial de alertas cerradas para tener registro de mis acciones pasadas. | 3                   | Sergio        | Done    |
| US51       | Edición de Información de Usuario       | US51-1            | Crear endpoint para editar perfil de usuario     | Como usuario quiero actualizar mis datos personales para mantener mi información actualizada.       | 4                   | Sergio        | Done    |
|            |                                         | US51-2            | Mostrar información del usuario en el frontend   | Como usuario quiero ver mis datos personales para saber qué información tengo registrada.           | 3                   | Paolo         | Done    |
|            |                                         | US51-3            | Agregar botón para editar y guardar cambios      | Como usuario quiero editar mi información desde el frontend para poder actualizarla fácilmente.     | 3                   | Maria         | Done    |
|            |                                         | US51-4            | Mostrar confirmación tras editar perfil          | Como usuario quiero ver una notificación de confirmación después de guardar cambios para saber que se actualizaron correctamente. | 2 | Paolo | Done |
| US52       | Actualización de APIs existentes        | US52-1            | Implementar endpoints del módulo de inventario   | Como desarrollador quiero contar con las APIs del inventario para poder gestionar productos y su stock desde el frontend. | 5 | Paolo | Done |
|            |                                         | US52-2            | Proteger endpoints con autorización por token     | Como usuario quiero que solo personas autenticadas puedan acceder a mis datos para garantizar la seguridad de la aplicación. | 4 | Maria | Done |
|            |                                         | US52-3            | Ajustar integración backend-frontend para nuevas APIs | Como desarrollador quiero que las nuevas APIs funcionen correctamente con el frontend para asegurar la conectividad entre capas. | 3 | Paolo | Done |


| Sprint # |                Sprint 4                 |  |  |  |  |  |        |
| :---: |:---------------------------------------:| :---: | :---: | :---: | :---: | ----- |:------:|
| Technical Story |                                         | Work-Item / Task |  |  |  |  |        |
| ID |                  Title                  | ID | Title | Description | Estimation (Hours) | Assigned To | Status |
| TS50 | Gestión de alertas – listar             | TS50-1              | Crear endpoint para listar alertas       | Como usuario quiero poder ver todas mis alertas activas para saber qué acciones tomar.                  | 4          | Sergio         | Done   |
| TS51 | Gestión de alertas – cerrar             | TS50-2              | Crear endpoint para cerrar alertas       | Como usuario quiero cerrar alertas que ya no son relevantes para mantener mi bandeja organizada.        | 3          | Luis Angel     | Done   |
| TS52 | Gestión de alertas – historial          | TS50-3              | Crear endpoint para historial de alertas | Como usuario quiero ver el historial de alertas cerradas para tener registro de mis acciones pasadas.   | 3          | Sergio         | Done   |
| TS53 | Edición de perfil – endpoint            | TS51-1              | Crear endpoint para editar perfil        | Como usuario quiero actualizar mis datos personales para mantener mi información actualizada.           | 4          | Sergio         | Done   |
| TS54 | Edición de perfil – mostrar datos       | TS51-2              | Mostrar información del usuario          | Como usuario quiero ver mis datos personales para saber qué información tengo registrada.               | 3          | Paolo          | Done   |
| TS55 | Edición de perfil – botón de edición    | TS51-3              | Agregar botón para editar y guardar      | Como usuario quiero editar mi información desde el frontend para poder actualizarla fácilmente.         | 3          | Maria          | Done   |
| TS56 | Edición de perfil – confirmación        | TS51-4              | Mostrar confirmación tras editar perfil  | Como usuario quiero ver una notificación de confirmación después de guardar cambios para saber que se actualizaron correctamente. | 2 | Paolo | Done |
| TS57 | APIs de inventario                      | TS52-1              | Implementar endpoints del inventario     | Como desarrollador quiero contar con las APIs del inventario para poder gestionar productos y su stock desde el frontend. | 5 | Paolo | Done |
| TS58 | Protección de endpoints                 | TS52-2              | Proteger endpoints con autorización      | Como usuario quiero que solo personas autenticadas puedan acceder a mis datos para garantizar la seguridad de la aplicación. | 4 | Maria | Done |
| TS59 | Integración backend-frontend            | TS52-3              | Ajustar integración backend-frontend     | Como desarrollador quiero que las nuevas APIs funcionen correctamente con el frontend para asegurar la conectividad entre capas. | 3 | Paolo | Done |

![image](https://github.com/user-attachments/assets/386b5910-5867-4d65-9b18-f43d3aabef86)

#### 5.2.4.4. Development Evidence for Sprint Review

![image](https://github.com/user-attachments/assets/c57c03bf-cd41-468e-92b0-9091e9b78745)

Aquí podemos notar como está conformado el grupo de trabajo dentro de la organización.
![image](https://github.com/user-attachments/assets/37efce22-48d0-4767-b146-b6d1cffac701)

#### 5.2.4.5. Execution Evidence for Sprint Review 
Aquí podemos notar la aplicación en ejecución luego de los sprints realizados.

#### 5.2.4.6. Services Documentation Evidence for Sprint Review.
En esta sección se evidencia el servicio documentado al detalle dentro del reporte.
![image](https://github.com/user-attachments/assets/c758048a-a83e-42f0-9491-292ed71f9cc3)

#### 5.2.4.7. Software Deployment Evidence for Sprint Review. 
![image](https://github.com/user-attachments/assets/afd4a6b1-8ba2-4776-afcc-ad9aa3d23e99)


#### 5.2.4.8. Team Collaboration Insights during Sprint. 

![image](https://github.com/user-attachments/assets/4c76efa8-7b48-4866-a382-9231546f77f1)


## 5.3. Validation Interviews
Esta sección está enfocada a registrar y explicar las acciones realizadas para las entrevistas de validación de cada segmento objetivo.

### 5.3.1. Diseño de Entrevistas

#### Segmento 1: Dueños de restaurantes

Para el segmento objetivo Trabajadores de Restaurante, se diseñó una sesión de validación centrada en evaluar la utilidad, claridad y funcionalidad de la solución propuesta. La entrevista incluyó una interacción guiada con la Landing Page y con la aplicación web funcional desplegada. A continuación, se detallan los elementos incluidos y los flujos validados durante la sesión:

##### Elementos incluidos en la sesión:
- Landing Page: El entrevistado navegó por todas las secciones informativas, incluyendo descripciones de beneficios y funcionalidades de la solución. Se resaltaron elementos visuales, testimonios y comparaciones con métodos tradicionales.

- Aplicación Web: Se presentó una versión desplegada de la app, permitiendo al entrevistado explorar cada uno de los módulos principales.

##### User Flows validados:

- Home:

Visualización de gráficos de sensores.

- Inventario:

Acceso al módulo de gestión de productos, donde se pudo revisar el registro completo del inventario.
Validación de la organización de productos y claridad de la información mostrada.

- Alertas:

Visualización de alertas activas y su relevancia para la gestión del inventario.

La entrevista permitió observar la interacción real del usuario con los distintos módulos, validar la coherencia del flujo general de uso, y recoger impresiones cualitativas sobre la experiencia ofrecida por la solución.

Durante la sesión, se realizaron preguntas clave para explorar la percepción del usuario y validar hipótesis del producto:
- ¿Qué características de la aplicación web usaría en su día a día?
- ¿Qué características le parecen más relevantes o útiles?
- ¿Considera que es importante la pantalla de gráficos? ¿Por qué?
- ¿Implementaría este sistema en su trabajo actual?

Estas preguntas fueron diseñadas para detectar qué funcionalidades generan más valor, cuáles podrían mejorarse, y si el sistema realmente resuelve problemas del día a día en la gestión operativa del restaurante.

### 5.3.2. Registro de Entrevistas

#### Segmento 1: Dueños de restaurantes

###### Información del entrevistado
| Nombre | Apellido | Edad | Distrito |
|--------|----------|------|----------|
| Kaled  | Arellano | 21   | Surco    | 

![image](https://github.com/user-attachments/assets/35be75e3-0e76-47c9-bc36-f02482d781c1)


🔗 Enlace al video de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310425_upc_edu_pe/Eb7sl3HehYNFomlQ1noiOCYBRM-VfItOuWH8nFGeIrBWNw?e=OTjGZb
- Duración Total: 4:27

###### Resumen de entrevista
Durante la sesión de validación, el entrevistado destacó varios aspectos clave del sistema que considera relevantes para su trabajo diario en el restaurante. Subrayó que el módulo de alertas es especialmente importante, ya que le permite estar al tanto del estado del negocio y anticipar problemas, lo que resulta útil para tomar decisiones estratégicas.

En cuanto al home con sensores, valoró positivamente su inclusión, ya que ofrece una visión general.

También sugirió que sería útil incluir una funcionalidad adicional: la visualización del aforo de comensales por horas. Esta capacidad permitiría analizar los momentos de mayor demanda, planificar mejor los recursos del local (como cantidad de mesas disponibles) y definir estrategias promocionales más efectivas.

Respecto al módulo de inventario, resaltó su utilidad práctica para el registro diario de productos. Indicó que el sistema facilita el control operativo y valoró especialmente las alertas automáticas sobre productos por vencer o con stock bajo, lo que contribuye directamente a una mejor gestión del abastecimiento.

###### Información del entrevistado
| Nombre  | Apellido | Edad | Distrito |
|---------|----------|------|----------|
| Augusto | Montez   | 22   | SMP      | 

![image](https://github.com/user-attachments/assets/76ebfc62-ab1c-4396-87b8-b552d5726cf8)


🔗 Enlace al video de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310425_upc_edu_pe/EY3YEMQNG9pLs4PHKtSRhcgB6Rj6Nb0pBOZG_XzokZxu_g?e=7JJdf1
- Duración Total: 4:18

###### Resumen de entrevista
Durante la sesión de validación, el entrevistado resaltó la utilidad general del sistema para optimizar la operatividad del restaurante.

En relación con el módulo de inventario, valoró positivamente la posibilidad de registrar productos con su fecha de expiración, tipo de medida y precio, ya que esto le permite mantener un mejor control del stock y evitar desperdicios. Destacó especialmente la función de alertas automáticas, la cual considera fundamental para anticipar problemas con productos vencidos o mal almacenados, algo que solía pasar con frecuencia en su negocio antes de implementar este tipo de tecnología.

El entrevistado también expresó que el home de sensores es una herramienta valiosa para la toma de decisiones.

Finalmente, sugirió que una funcionalidad adicional que podría mejorar el sistema sería la posibilidad de generar reportes automáticos semanales que se envíen por correo, para mantener a la gerencia informada sin necesidad de acceder manualmente a la plataforma.

###### Información del entrevistado
| Nombre | Apellido | Edad | Distrito |
|--------|----------|------|----------|
| Maria  | Castillo | 24   | Lince    | 

![image](https://github.com/user-attachments/assets/8283291a-83b1-4d3e-8739-c1466dc90e9d)


🔗 Enlace al video de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310425_upc_edu_pe/EZ3O5a93kslLkrutzFcQC94BbtC_s_mhi4pGJj8DE_SRYA?e=GDrHfz
- Duración Total: 3:42

###### Resumen de entrevista
Durante la entrevista de validación, la entrevistada propietaria de un restaurante de tamaño mediano comentó que la aplicación cubre varias de las necesidades clave que enfrenta en la gestión diaria de su negocio. Destacó que el módulo de home le permite tener una visión clara y actualizada del desempeño del restaurante, lo que considera fundamental para tomar decisiones rápidas y basadas en datos.

También elogió el módulo de alerts, especialmente por su capacidad de detectar productos cerca del vencimiento o almacenados en condiciones inadecuadas. Según su experiencia, este tipo de notificaciones reduce pérdidas por deterioro de productos y mejora los estándares de higiene y control.

Respecto al módulo de inventory, mencionó que ahora puede llevar un mejor control de los productos en stock y planificar compras con mayor precisión. Además, resaltó que registrar el tipo de unidad (litros, kilos, unidades, etc.) facilita una mejor organización de los insumos.


#### Segmento 2: Trabajadores de restaurantes

| Nombre    | Apellido  | Edad | Distrito               |
|-----------|-----------|------|------------------------|
| Giancarlo | Rodriguez | 25   | San Juan de Lurigancho | 

![image](https://github.com/user-attachments/assets/f4db703d-1813-4583-ad15-d43d9343577d)


🔗 Enlace al video de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/EVOvay2896tDs_xpFUx5kJwBocwfqfdk8WIrBBM00X2sjA?e=zXOe3z&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
- Duración Total: 9:11

###### Resumen de entrevista
Durante la entrevista de validación, el entrevistado destacó que la aplicación le ha facilitado varias tareas que antes realizaba de forma manual o con anotaciones físicas.

También resaltó que el módulo de inventory le resulta útil para registrar productos nuevos cuando llegan los pedidos de insumos. Afirmó que antes debía llevar este control en una libreta, lo cual se prestaba a errores u omisiones, mientras que ahora el sistema le permite guardar toda la información como fecha de vencimiento, cantidad y unidad de medida de manera ordenada y clara.

Otro punto que valoró fue la presencia del módulo de alerts, ya que ahora recibe notificaciones cuando un producto está a punto de vencer o presenta condiciones de almacenamiento inadecuadas. Dijo que esto le da más confianza al momento de organizar las cámaras de refrigeración y seleccionar los ingredientes durante el día.

Por último, comentó que al usar el sistema como trabajador, pudo loguearse fácilmente en su perfil sin necesidad de permisos especiales, y que la aplicación es intuitiva, incluso para quienes no tienen experiencia con tecnología. Como sugerencia, propuso incluir una opción para marcar productos como “usados” o “retirados”, de modo que el inventario refleje aún mejor la rotación diaria.



###### Información del entrevistado

| Nombre    | Apellido | Edad | Distrito |
|-----------|----------|------|----------|
| Alexandra | Moreno   | 22   | Surco    |

![image](https://github.com/user-attachments/assets/a2abaae4-b308-4e08-a1cd-5e4a535f05b0)


🔗 Enlace al video de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/EYIPlvrPVVpPqEHdGMpE0nIBKWzGzAnh_VZ3d9lekvi4ww?e=eiQeec&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
- Duración Total: 8:37

###### Resumen de entrevista
Durante la sesión de validación, la entrevistada, encargada del control de insumos en el almacén del restaurante, señaló que la aplicación representa una mejora significativa en el registro y seguimiento de los productos. Comentó que antes llevaba un control manual con hojas impresas, lo cual era lento y propenso a errores. Con la app, ahora puede registrar fácilmente la cantidad exacta, tipo de medida y fecha de expiración de cada producto al momento de recibirlo.

Valoró especialmente la capacidad del módulo de inventory para manejar distintos tipos de unidades, lo que le permite trabajar con precisión tanto con productos en unidades como en litros o kilos. Mencionó que esto facilita la verificación del stock disponible sin necesidad de hacer conteos físicos constantes.

Respecto al sistema de alertas, afirmó que ha sido clave para anticiparse a problemas logísticos. Comentó que ha recibido notificaciones a tiempo sobre productos a punto de vencer o almacenados en condiciones inadecuadas, lo que le ha permitido tomar medidas correctivas antes de que se generen pérdidas.

Como sugerencia, propuso que el sistema pudiera incluir una vista resumida de los productos más utilizados por semana, para ayudar en la planificación de compras futuras y evitar el sobreabastecimiento.

###### Información del entrevistado

| Nombre | Apellido | Edad | Distrito   |
|--------|----------|------|------------|
| Ingrid | Pacheco  | 24   | San Isidro | 

![image](https://github.com/user-attachments/assets/b95f7323-eb10-488e-9fdf-b5696b3081d2)


🔗 Enlace al video de la entrevista: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/Ec8Pic1F7s1BvPXW53dzn4sB5E3CjVY6q_OpDkoT1NMj-w?e=Ok8dWW&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
- Duración Total: 17:48

###### Resumen de entrevista
Durante la sesión de validación, la responsable del control de insumos en el almacén del restaurante destacó que la aplicación ha supuesto una mejora notable en el registro y seguimiento de productos. Explicó que anteriormente realizaba este control de forma manual con hojas impresas, lo cual era un proceso lento y propenso a errores. Ahora, gracias a la app, puede ingresar con facilidad la cantidad, unidad de medida y fecha de vencimiento de cada producto en el momento de su recepción.

Resaltó como especialmente útil la funcionalidad del módulo de inventario que permite gestionar diferentes tipos de unidades de medida. Esto le brinda mayor precisión al trabajar tanto con productos en unidades, como en litros o kilos, y le facilita verificar el stock disponible sin necesidad de hacer conteos físicos frecuentes.

En cuanto al sistema de alertas, mencionó que ha sido fundamental para prevenir problemas logísticos. Recibe notificaciones a tiempo sobre productos próximos a vencer o que están almacenados en condiciones no adecuadas, lo que le ha permitido tomar acciones correctivas y evitar pérdidas.

Como recomendación, sugirió incorporar una vista resumida de los productos más utilizados por semana, lo que contribuiría a una mejor planificación de compras y a evitar acumulación innecesaria de insumos.

### 5.3.3. Evaluaciones según heurísticas.

Site o App a evaluar: GoodFood

Tareas a evaluar | No incluidas en esta versión  <br>            
Incluidas en esta evaluación
1. Registro de un trabajador/dueño (Profile, LogIn & SignUp)
2. Ingreso de un nuevo producto en Inventory
3. Consulta de aletas generadas
4. Consulta rápida de sensores en el home

No están incluidas en esta versión de la evaluación las siguientes tareas:
1. Edición o eliminación de usuarios registrados.
2. Visualización de estadísticas comparativas mensuales o anuales en el Dashboard.
3. Accesibilidad extendida (lectores de pantalla, navegación por teclado, modo alto contraste).

Escala de severidad:

| Nivel | Descripción                                                                                                                                                                                       |
|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                     |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente    reléase |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.                                   |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                                 |

Tabla Resumen:

| #  | Problema detectado                                                               | Severidad | Heurística/Principio violado                             |
|----|----------------------------------------------------------------------------------|-----------|----------------------------------------------------------|
| 1  | Al guardar un producto no aparece mensaje de confirmación ni feedback visual.   | 3         | Usabilidad: Visibilidad del estado del sistema           |
| 2  | Gráficos del Home no tienen texto alternativo para lectores de pantalla.        | 3         | Inclusive Design: Proporciona experiencias comparables   |
| 3  | No existe opción para deshacer la creación de un producto recién añadido.       | 2         | Usabilidad: Control y libertad del usuario               |

No aparece mensaje de confirmación al guardar un pedido en Inventory

Problema #1
Severidad: 3 (Problema mayor)

Heurística violada: Usabilidad – Visibilidad del estado del sistema

Observación
Al registrar un nuevo producto desde el módulo Inventory, no se muestra ningún mensaje, alerta ni animación visual que indique que el pedido fue guardado correctamente. Esto genera incertidumbre en el usuario,
quien puede dudar si la acción fue exitosa o si debe repetirla.


Recomendación
Incluir un mensaje de confirmación visual como: “Producto guardado con éxito”, que desaparezca tras unos segundos. También podría añadirse una breve animación o cambio de estado en la tabla de inventario para reforzar el feedback.


PROBLEMA #2
Los gráficos del Home no incluyen texto alternativo accesible

Severidad: 3 (Problema mayor)

Heurística violada: Inclusive Design – Proporciona experiencias comparables

Observación
Los gráficos del home no ofrecen texto alternativo ni descripciones para tecnologías de asistencia como lectores de pantalla. Esto limita el acceso a la información visual para personas con discapacidad visual o usuarios que navegan sin ver la pantalla.

Recomendación
Incluir aria-label, alt o descripciones visibles/resumidas del contenido de cada gráfico. También se puede añadir una tabla textual con los mismos datos que se muestran visualmente.

PROBLEMA #3
No se puede deshacer la creación de un producto

Severidad: 2 (Problema menor)

Heurística violada: Usabilidad – Control y libertad del usuario

Observación
Al crear un nuevo producto con cantidad, fecha de expiración, no existe una opción para cancelar la acción ni para eliminar el producto justo después de creado.

Recomendación
Incluir un botón “Deshacer” o “Cancelar” visible después de crear un producto. También se podría agregar una notificación con la opción “Eliminar este producto” dentro de los primeros 10 segundos.

# Video About-the-Product.
Este video muestra el producto final desarrollado por el equipo GoodFood.
![image](https://github.com/user-attachments/assets/6e265821-b22e-4870-a6a4-50dcdf110ced)


**Link del video en Microsoft Stream:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223811_upc_edu_pe/EcxIxsv9HQdCj4Y0UhCmDk4Bb6QcTifZOMiD3jDkMwuAgw?e=7BoFmL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
<br>
<br>
**Link del video en Youtube:** https://youtu.be/VZfagHk0-T8

# Conclusiones

- Se reafirmó la importancia del trabajo en equipo y la colaboración entre los miembros del grupo para alcanzar los objetivos planteados.

- La planificación y organización fueron fundamentales en cada etapa del desarrollo de software, permitiendo optimizar tiempos y recursos.

- Las tecnologías de la información y comunicación (TIC) demostraron ser herramientas clave para abordar problemáticas reales mediante soluciones digitales.

- El proyecto desarrollado representa una solución rentable, escalable y sostenible frente a la problemática del desperdicio alimentario en el Perú.

- La aplicación permite a los restaurantes involucrarse activamente en la reducción del desperdicio alimentario, actuando  como agentes de cambio.

- Se emplea la tecnología para llegar a un público más amplio y generar un impacto social positivo.

- La aplicación presenta una buena usabilidad, lo que facilita una experiencia eficiente e intuitiva para los usuarios.

- La solución es escalable y puede adaptarse a diferentes necesidades, permitiendo su crecimiento y mejora continua a  futuro.

- En conjunto, el trabajo integra tecnología y compromiso social para brindar una herramienta funcional con impacto real en   la sociedad.

# Video About-the-Team.
Este video muestra el proceso de trabajo del equipo que desarrolló GoodFood.
Cada integrante aparece ante cámara para describir su rol, los principales outcomes logrados y las competencias que fortaleció durante el proyecto.

![image](https://github.com/user-attachments/assets/f5ae448d-73ff-4b35-bd33-d7c89d6f76a1)


**Link del video en Microsoft Stream:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221f613_upc_edu_pe/EaIZDBPFzuhGjddlCgPIXvgBqdy92g3BUFYgOPsKVYqCow?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=lwsRd8
<br>
<br>
**Link del video en Youtube:** https://youtu.be/APG5MgMBumU


# Bibliografía

- Bedoya-Perales, N. S., & Magro, G. P. D. (2021). Quantification of Food Losses and Waste in Peru: A Mass Flow Analysis along the Food Supply Chain. Sustainability, 13(5), 2807. https://doi.org/10.3390/su13052807

- Valderrama Pérez, V. (2018). CÓMO MEJORAR EL SERVICIO EN EL RESTAURANTE BISTRO 400 UBICADO EN EL DISTRITO DE MIRAFLORES APLICANDO LA TEORÍA DE DEMING. https://repositorio.usmp.edu.pe/bitstream/handle/20.500.12727/4338/valderrama_pva.pdf;jsessionid=9738274DA0640F881B7B0A2078783E0E?sequence=3
- Microsoft. (2024). ASP.NET Core Documentation. Retrieved from: https://learn.microsoft.com/en-us/aspnet/core/?view=aspnetcore-8.0

- Microsoft. (2024). C# Language Documentation. Retrieved from: https://learn.microsoft.com/en-us/dotnet/csharp/

- Microsoft. (2024). Entity Framework Core Documentation. Retrieved from: https://learn.microsoft.com/en-us/ef/core/

- Microsoft. (2024). Dependency Injection in ASP.NET Core. Retrieved from: https://learn.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection
- Postman. (2024). Postman Learning Center: Using Postman. Retrieved from: https://learning.postman.com/docs/getting-started/introduction/

- Swagger. (n.d.). Swagger Tools and OpenAPI Documentation. Retrieved from: https://swagger.io/tools/swagger-ui/

- JetBrains. (2024). Rider – The .NET IDE by JetBrains. Retrieved from: https://www.jetbrains.com/rider/


# Anexos
## Anexo A: Landing page Wireframes y Mockups:<br>
https://www.figma.com/design/UoCOsf8lHI64dQgrAhAiO7/WebApp-Wireframes---Mockups?node-id=0-1&t=Xg8IiUZc6xMsklW6-1

## Anexo B: Landing page deployed:<br>
https://foodle-pe.github.io/Landing-Page/

## Anexo C: Diagrama de clase y base de datos: <br>
https://lucid.app/lucidchart/9990a006-a793-4d40-90e0-e5d5481cd30f/edit?viewport_loc=-2215%2C-1011%2C6034%2C2780%2CHWEp-vi-RSFO&invitationId=inv_4b71b5c1-35b6-46b0-8ca9-5ef08a819431

## Anexo D: Trello: <br>
https://trello.com/invite/b/680c5df2be329c5196159826/ATTIa0e35c3f12f904fb93ef8e86cfada3b9C5482966/sprint-1-apps-webs

## Anexo E: Entrevistas: <br>
https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221f613_upc_edu_pe/EbnN3gP36-lMhnMd2U7JXlMBINOJR_jxeZNuOcoosuPSSg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=O5ACl2

## Anexo F: Web app wireframes and mockups: <br>
https://www.figma.com/design/UoCOsf8lHI64dQgrAhAiO7/WebApp-Wireframes---Mockups?node-id=0-1&t=Y401T6fFRprwfY02-1

## Anexo G: Structurizr: <br>
https://structurizr.com/share/93062
