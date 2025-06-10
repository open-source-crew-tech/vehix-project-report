# Capítulo IV: Product Design
## 4.1. Style Guidelines
En esta sección, presentamos nuestra propuesta de diseño para el landing page y la aplicación web. Las guías de estilo de **Vehix** establecen los lineamientos visuales y comunicativos que aseguran una experiencia coherente, intuitiva y accesible en toda la aplicación. Estas guías fueron diseñadas para mantener consistencia en todos los puntos de contacto con el usuario, incluyendo interfaz, notificaciones y mensajes del sistema.

### 4.1.1. General Style Guidelines
Aquí se muestran las normas básicas que nos permiten mantener una presentación clara y coherente de nuestros productos.

#### **Colores**
   
  La identidad visual de **Vehix** está centrada en una paleta monocromática compuesta por tonalidades de **blanco y negro**, complementada con un **color de acento turquesa** que aporta un toque moderno, tecnológico y fresco, sin perder sobriedad.

  Esta combinación logra un equilibrio entre seriedad y accesibilidad, ideal para una aplicación enfocada en el mantenimiento vehicular.

* Colores principales
   
   La gama de grises elegida permite mantener una interfaz visualmente limpia, neutra y moderna,
   facilitando el enfoque en el contenido y las funcionalidades sin distracciones visuales innecesarias. Además, el gris proporciona un equilibrio entre profesionalismo y accesibilidad.
   
* Escala de grises
   
| Color                                      | Justificación                                                                                                                                                                          |
| ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `#FAFAFA`  `#F5F5F5`                       | Se utiliza como fondo base en formularios y secciones de contenido. Aporta luminosidad sin ser completamente blanco, reduciendo la fatiga visual. Ideal para mantener limpieza visual. |
| `#EEEEEE`  `#E0E0E0`                       | Aplicado como fondo en tarjetas, cajas de contenido o elementos con jerarquía secundaria. Brinda separación visual sin contraste excesivo.                                             |
| `#BDBDBD`  `#9E9E9E`                       | Sirve para bordes, líneas divisoras o elementos neutros. Ayuda a estructurar la interfaz sin añadir ruido visual.                                                                      |
| `#757575`  `#616161`  `#424242`  `#212121` | Utilizado en textos secundarios, íconos, botones no activos y etiquetas. Proporciona contraste sin recurrir al negro puro, facilitando una jerarquía visual adecuada.                  |

![escala-gris](/assets/imgs/chapter-IV/escala-gris.PNG)

* Escala de negros

  La escala de negros con diferentes niveles de opacidad se usa estratégicamente para reforzar el contraste, resaltar contenido principal y crear una sensación de profundidad en la interfaz.

| RGBA                                          | Justificación                                                                                                                        |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `rgba(0, 0, 0, 0.87)`                         | Ideal para texto principal, títulos y mensajes importantes. Asegura máxima legibilidad en interfaces claras.                         |
| `rgba(0, 0, 0, 0.6)` a `rgba(0, 0, 0, 0.42)`  | Aplicado en textos secundarios, etiquetas o descripciones más sutiles. Mantiene legibilidad sin competir con el contenido principal. |
| `rgba(0, 0, 0, 0.26)` a `rgba(0, 0, 0, 0.06)` | Utilizado en bordes suaves, sombras o elementos desactivados. Ayuda a construir jerarquía y profundidad sin distracción visual.      |


![escala-negra](/assets/imgs/chapter-IV/escala-negra.PNG)
 
* Color de acento

  **Turquesa suave (#A9D8DC):** 
se utilizará para resaltar zonas clave de interacción como mensajes informativos, botones destacados en pantallas de registro, o fondos secundarios. Este color transmite **tecnología amigable**, **modernidad** y **claridad**.

![turquesa](/assets/imgs/chapter-IV/color_turquesa.PNG)

#### **Tipografía**

En **Vehix**, la tipografía es un componente esencial para transmitir claridad, profesionalismo y accesibilidad en cada pantalla de la aplicación. Se ha definido el uso de tres fuentes principales, combinando elegancia, legibilidad y modernidad.

 * PT Serif Regular

   - **Uso:** Indicaciones, descripciones cortas, y subtítulos informativos.
   - **Justificación:** Esta tipografía aporta una estética clásica y seria, ideal para mostrar mensajes auxiliares, instrucciones y textos complementarios. En tu interfaz, se aplica a pequeños textos explicativos como los de los campos del formulario o mensajes dentro de las tarjetas.

![pt-serif](/assets/imgs/chapter-IV/pt-serif-regular.PNG)
 
* Roboto Regular
  
  - **Uso:** Contenido general, campos de formularios y textos secundarios.
  - **Justificación:** Roboto es perfecta para ofrecer legibilidad en pantallas, especialmente en bloques de texto como descripciones, contenidos de planes, formularios de contacto y navegación. Aporta un estilo moderno y funcional sin perder claridad.

![roboto-regular](/assets/imgs/chapter-IV/roboto-regular.PNG)

* Montserrat Regular
  
  - **Uso:** Títulos principales, subtítulos y botones.
  - **Justificación:** Su estilo geométrico y moderno brinda un toque contemporáneo y profesional a la interfaz. Es utilizada para destacar los elementos más importantes visualmente como “VEHIX”, nombres de secciones y botones, lo que permite una jerarquía clara y elegante.

![monserrat-regular](/assets/imgs/chapter-IV/Monserrat-regular.PNG)

#### **Spacing**

Los elementos interactivos deben ser lo suficientemente grandes y estar bien espaciados para facilitar su uso, especialmente para quienes tienen dificultades motrices. Un espaciado adecuado asegura que los usuarios puedan tocar o hacer clic en los botones de manera segura, sin riesgo de presionar accidentalmente el botón incorrecto.

- **8 px:** Unidad mínima para separar pequeños elementos (íconos, etiquetas).

- **16 px:** Margen interno típico para botones, tarjetas y campos de formulario.

- **24 px:** Separación entre secciones pequeñas o subtítulos.

- **64 px:** Espaciado entre secciones grandes o bloques verticales principales.


#### **Branding**

 #### **Logo**

 ![logo](/assets/imgs/chapter-IV/logo.png)
 
 El logotipo de **Vehix** ha sido diseñado bajo principios de simplicidad, elegancia y profesionalismo, alineado con la propuesta de valor de la aplicación como una herramienta confiable para el cuidado preventivo de vehículos.

 #### **Características del logotipo**

- **Tipografía:** Se utiliza una fuente **sans serif moderna** con líneas limpias y proporciones equilibradas. Esta elección transmite claridad, orden y tecnología, elementos clave del producto.

- **Espaciado entre letras:** Las letras del nombre **“VEHIX”** se presentan en **mayúsculas y con espaciado amplio**, lo que aporta un toque formal y contemporáneo. Este detalle mejora la legibilidad y refuerza la presencia visual del nombre en distintos tamaños y soportes.

- **Colores:** El logotipo se presenta en **blanco o negro**, según el fondo sobre el que se aplique, asegurando **máximo contraste y versatilidad**. La decisión de evitar colores adicionales responde a la intención de mantener una estética sobria, profesional y adaptable.

- **Ausencia de íconos gráficos:** Por decisión estratégica, el logotipo **no incluye ilustraciones** (como autos, herramientas o ruedas), con el fin de mantener una imagen minimalista y evitar asociaciones literales que limiten la escalabilidad de la marca.

#### **Tono de Comunicación**

Vehix se comunica con sus usuarios de forma clara, cercana y empática. Para lograrlo, se han definido las siguientes **dimensiones de tono**.

| Dimensión                | Elección       | Justificación                                                                      |
| ------------------------ | -------------- | ---------------------------------------------------------------------------------- |
| Divertido / Serio        | **Serio**      | Se prioriza la confianza y seguridad, especialmente en contextos de alerta.        |
| Formal / Casual          | **Casual**     | Se busca cercanía sin perder profesionalismo, ideal para usuarios cotidianos.      |
| Respetuoso / Irreverente | **Respetuoso** | El respeto es clave para construir relaciones duraderas con los usuarios.          |
| Entusiasta / Sereno      | **Sereno**     | Un tono calmado evita alarmismos y transmite tranquilidad en situaciones técnicas. |


  
### 4.1.2. Web Style Guidelines

Se utilizó el patrón de lectura Z para guiar la atención del usuario desde el logo y menú superior, hacia el mensaje principal y finalmente a la imagen del producto. Este recorrido visual permite una lectura fluida y rápida, ideal para captar el mensaje en pocos segundos.

![img-landing-page](/assets/imgs/chapter-IV/img-lp.PNG)

Se aplicó el patrón de lectura F para estructurar la pantalla en bloques horizontales que el usuario escanea de arriba hacia abajo. Comienza con la navegación superior, continúa con la información principal como datos personales, plan de membresía estándar, los vehiculos disponibles para dicho plan y termina en la sección de ayuda. Este recorrido facilita una lectura rápida y jerárquica, ideal para pantallas móviles donde el desplazamiento es vertical.

![img-web](/assets/imgs/chapter-IV/img-web.PNG)

## 4.2. Information Architecture
En Vehix, la estructura de la información está diseñada para facilitar el acceso y la comprensión del contenido tanto en la página principal como en sus plataformas web y móviles. Se aplican métodos organizativos eficientes, como la disposición jerárquica y la clasificación temática, además de un etiquetado claro que favorece la exploración del sitio y la localización rápida de elementos. Asimismo, se incorpora una navegación amigable con herramientas de búsqueda precisas y filtros detallados, lo que permite a los usuarios encontrar lo que buscan de forma sencilla. Todo esto contribuye a ofrecer una interacción fluida y una experiencia consistente y agradable para quienes visitan y utilizan Vehix.

### 4.2.1. Organization Systems
En este sección se indicarán los sistemas de organización que se han usado para el "Landing page" y la aplicación web. Entre los tipos de estructuras que han sido escogidas son: jerárquica y secuenciale. Además también indicaremos los esquemas de categorización de contenido.

Para la landing page se ha utilizado una estructura jerárquica en la landing page de Vehix porque permite organizar la información de forma clara y progresiva, guiando al usuario desde lo más general hasta lo más específico.

- Inicio
  
   Banner: imagen principal que comunica el valor del producto
  
- Beneficios

Beneficios para conductores

Beneficios para mecánicos

- Testimonios

- Sobre nosotros
  
   Nuestra propuesta de valor como startup

  Perfiles de integrantes

- Preguntas frecuentes

- Compatibilidad de vehículos

- Contacto
  
  formulario de contacto
  
- Soporte
  
   Correo electrónico: canal directo de atención

   Redes sociales: enlaces a Facebook, Instagram, etc.

La Aplicación Web Vehix implementa múltiples sistemas de organización que permiten una navegación estructurada y eficaz, tanto para conductores como para mecánicos, en función de sus necesidades específicas.

**Organización Visual del Contenido**

Jerárquica (Visual Hierarchy):
- **Perfil de Vehículos Registrados:** Muestra una lista general de vehículos. Al seleccionar uno, se accede a su historial técnico, consumo, mantenimiento, alertas y diagnósticos.

- **Historial de Mantenimientos o Diagnósticos:** Ordenados por vehículo y fecha, donde cada ítem permite ver detalles como tipo de falla, solución aplicada y observaciones.

- **Panel de Talleres Cercanos:** El usuario visualiza un mapa general y puede hacer clic sobre cada taller para ver detalles: ubicación, calificación, tipo de servicio y horarios.

Secuencial (Step-by-Step to Accomplish):
- **Registro de Cuenta y Vehículo:** Flujo paso a paso donde se completa el perfil del usuario y luego se registran datos específicos del vehículo (modelo, marca, año, etc.).

- **Pago de Suscripción:** Flujo guiado que incluye selección de plan, ingreso de datos, confirmación y visualización de estado del plan.

- **Proceso de Diagnóstico (Mecánico):** Incluye conexión vía Bluetooth, detección automática de fallas, interpretación y sugerencia de soluciones.

Matricial (Comparación Cruzada):
- **Comparación entre Vehículos:** El usuario puede comparar el estado, desgaste, consumo y frecuencia de alertas de diferentes vehículos registrados.

- **Panel del Mecánico:** Visualización de vehículos diagnosticados por tipo de falla, cliente, fecha, y estado del mantenimiento realizado.

### 4.2.2. Labeling Systems
En el diseño de la interfaz de usuario, el sistema de etiquetado (**Labeling System**) cumple un rol fundamental para guiar la navegación y facilitar la comprensión del contenido. En el caso de **Vehix**, tanto en su landing page como en la aplicación web, se ha priorizado el uso de **etiquetas claras, breves y fácilmente reconocibles** para representar funciones, secciones y temas clave.

#### Landing Page

En el diseño del landing page de Vehix, las etiquetas se han seleccionado para **comunicar información de forma directa**, evitar la ambigüedad y facilitar la navegación del usuario. Se busca que las etiquetas sean **claras, breves y universales**, con un enfoque tanto informativo como persuasivo. 

##### Principios aplicados:

- **Lenguaje directo** para facilitar la lectura.
    
- **Máximo dos palabras** por etiqueta.
    
- **Ubicación estratégica** para guiar el recorrido del visitante


#### Etiquetas utilizadas

| Etiqueta          | Ubicación                      | Función asociada                      |
| ----------------- | ------------------------------ | ------------------------------------- |
| **Subscriptions** | Menú superior                  | Redirige a los planes de pago         |
| **Benefits**      | Menú superior y sección visual | Muestra ventajas por tipo de usuario  |
| **Testimonials**  | Menú superior                  | Muestra opiniones de usuarios reales  |
| **Who are we?**   | Menú superior                  | Presentación del equipo de desarrollo |
| **Support**       | Menú superior                  | Enlace al formulario de contacto      |
| **Compatibility** | Menú superior y sección visual | Muestra qué vehículos son compatibles |


#### Web Application

En la aplicación web, el sistema de etiquetado cumple una función de **navegación interna** y organización del contenido relacionado al estado del vehículo. Aquí, las etiquetas están orientadas a **acciones técnicas, diagnósticos y mantenimiento**, usando un lenguaje más funcional pero igualmente accesible.

##### Principios aplicados:

- **Claridad técnica**, sin ser excesivamente complejas.
    
- **Consistencia** entre elementos del dashboard.
    
- **Asociación directa** entre etiqueta y contenido mostrado.


#### Etiquetas utilizadas:

| Etiqueta                  | Ubicación      | Función asociada                            |
| ------------------------- | -------------- | ------------------------------------------- |
| **Home**                  | Barra superior | Acceso al panel principal                   |
| **Bluetooth**             | Barra superior | Conexión del adaptador vehicular            |
| **Library**               | Barra superior | Acceso a materiales técnicos y guías        |
| **Diagnostic**            | Barra superior | Acceso al sistema de escaneo                |
| **Historial de escaneos** | Dashboard      | Muestra los diagnósticos pasados            |
| **Resumen de estado**     | Dashboard      | Muestra el estado actual del vehículo       |
| **Alertas recientes**     | Dashboard      | Muestra notificaciones de fallos detectados |
| **Estado vehicular**      | Dashboard      | Información técnica en tiempo real          |
| **PLAN PRO**              | Dashboard      | Destaca visualmente la suscripción premium  |

### 4.2.3. SEO Tags and Meta Tags

Los **SEO Tags** y **Meta Tags** son elementos clave del código HTML que permiten mejorar el **posicionamiento web** y facilitar que los usuarios encuentren el sitio en buscadores como Google. A través de etiquetas como `title`, `description`, `keywords` y `author`, se define el contenido de cada página, haciendo que sea más visible, comprensible y atractiva para los motores de búsqueda y los visitantes.

#### Landing Page

  **Título de la página:**
  
``` 
<title> Vehix | Monitorea tu vehículo en tiempo real</title>
```

  Permite identificar la página en el navegador y en los resultados de Google. Comunica el nombre del proyecto y su función principal, lo que atrae clics y mejora el SEO.

**Meta Descripción:**

```
<meta name="description" content="Vehix es una plataforma inteligente que detecta fallas en tu vehículo, te da alertas y mejora la vida útil de tu auto. Conéctalo y cuídalo desde tu celular.">
```

  Resume de forma clara y directa los beneficios de usar la plataforma. Esta descripción aparece debajo del título en Google y ayuda a convencer al usuario de visitar el sitio.

**Palabras Clave (Keywords):**

```
<meta name="keywords" content="Vehix, plataforma automotriz, diagnóstico de vehículos, mantenimiento del auto, conectar carro, OBD2, app para autos">
```

   Incluye términos relevantes que los usuarios podrían buscar para encontrar una app como Vehix. Ayuda a mejorar el posicionamiento en buscadores (aunque hoy es menos usada por Google).

**Autor del sitio**

```
<meta name="author" content="Equipo de Vehix">
```

#### Web Application

 **Título:** 
 
```
<title>Vehix Dashboard | Estado y alertas de tu vehículo</title>
```

 Describe con precisión qué encontrará el usuario dentro de la aplicación: un panel para monitorear el estado del auto y recibir alertas. Mejora la usabilidad y el posicionamiento SEO.

**Meta Descripción:**

```
 <meta name="description" content="Consulta el estado actual de tu auto, recibe alertas, revisa mantenimientos y detecta problemas con el sistema Vehix."> 

```

Presenta los beneficios funcionales de la app para usuarios registrados. Aumenta el interés y claridad sobre lo que se puede hacer en el sistema.

**Palabras Clave (Keywords):**

```
<meta name="keywords" content="Vehix, dashboard auto, escaneo de vehículos, alertas automotrices, historial de mantenimientos, diagnóstico técnico, sensores auto">

```

Palabras clave más técnicas para posicionar la aplicación en entornos especializados.

**Autor del sistema**

```
<meta name="author" content="Equipo de Vehix">
```

Reconoce al equipo desarrollador, reforzando la identidad y el crédito del grupo creador del sistema.

### 4.2.4. Searching Systems
Para garantizar una experiencia de busqueda satisfactoria y eficiente para los usuarios de **Vehix** hemos implementado el sistema de búsqueda el cual está diseñado para facilitar la localización rápida de información dentro del producto digital, evitando que el usuario se sienta perdido entre múltiples secciones o volúmenes de contenido. Tanto en la **landing page** como en la **aplicación web**, se han integrado mecanismos que permiten **filtrar, ubicar y visualizar datos de forma clara**, mejorando la experiencia y reduciendo el tiempo de navegación.

#### **Landing Page**

En la landing page de Vehix, el enfoque está en una navegación **guiada por botones y secciones ancladas**, por lo que **no se implementa un buscador tradicional**. Sin embargo, el usuario puede acceder de manera directa a secciones clave como **Suscriptions, Benfits, Testimonials, Who are we?, Support y Compatibylity **, mediante el menú superior. Esto actúa como un sistema de búsqueda estructurada por **temas**, donde el contenido está **organizado y accesible sin necesidad de escribir términos manualmente**.

#### **Web Application**

En la aplicación web de Vehix, donde el volumen de datos técnicos puede ser mayor (como **historial de escaneos**, **alertas**, o **registros de diagnóstico**), se incorporan **funcionalidades específicas de búsqueda**:

**Opciones de búsqueda ofrecidas:**

 - **Buscador de vehículos registrados** (por nombre, placa o modelo)
    
- **Búsqueda de errores técnicos** (por código OBD2 o palabra clave)
    
- **Filtrado de historial** por fecha, tipo de mantenimiento o gravedad del error
    

**Filtros disponibles:**

- Fecha específica o por rangos (últimos 7 días, último mes, etc.)
    
- Tipo de alerta (mecánica, electrónica, mantenimiento)
    
- Estado del vehículo (óptimo, requiere revisión, crítico)
    

**Presentación de resultados:**

- Los resultados se muestran en **listas con tarjetas** o **tablas**, resaltando:
    
    - El nombre del vehículo
        
    - Código de error (si aplica)
        
    - Fecha del evento
        
    - Recomendación asociada
      
### 4.2.5. Navigation Systems

En Vehix, se ha diseñado un sistema de navegación claro y funcional que guía al usuario a lo largo de la **Landing Page** y la **Aplicación Web**, asegurando una experiencia fluida, lógica y sin confusiones. La navegación se estructura usando **técnicas visuales, menús accesibles y jerarquía de contenido**, adaptándose al tipo de usuario (visitante o registrado).


#### Navegación en el Landing Page

La navegación de la landing page de **Vehix** se ha diseñado para guiar al visitante de forma **fluida, clara y estructurada**, ayudándolo a recorrer cada bloque de contenido sin perderse. A través de una navegación vertical tipo scroll y un menú superior anclado, el usuario puede explorar los beneficios, conocer el producto y tomar decisiones rápidamente.

**Estructura y acciones:**
-  **Menú de navegación fijo en la parte superior**: con enlaces ancla que permiten saltar directamente a secciones como:
	- Home
	- Beneficios
	- Testimonios
	- Suscripciones
	- Quienes somos
	- Soporte
	- Compatibilidad

**Scroll guiado y orden lógico del contenido**: El contenido está distribuido en secciones que el usuario recorre haciendo scroll vertical. El orden sigue un **flujo lógico de presentación del producto**, pensado para convertir visitantes en usuarios:

| Orden | Sección                    | Propósito                                                                   |
| ----- | -------------------------- | --------------------------------------------------------------------------- |
| 1     | Hero Banner (introducción) | Presenta el producto y valor principal: "protege tu vehículo y tu bolsillo" |
| 2     | Video explicativo          | Responde a la pregunta: ¿Cómo funciona Vehix?                               |
| 3     | Planes                     | Muestra opciones de suscripción (call to action)                            |
| 4     | Beneficios                 | Separa claramente los beneficios para conductores y mecánicos               |
| 5     | Testimonios                | Refuerza la confianza a través de experiencias reales                       |
| 6     | Quiénes somos              | Presenta al equipo detrás del proyecto                                      |
| 7     | Preguntas frecuentes       | Resuelve dudas comunes rápidamente                                          |
| 8     | Compatibilidad             | Informa qué vehículos funcionan con Vehix                                   |
| 9     | Formulario de contacto     | Permite al usuario comunicarse antes de registrarse                         |


#### Navegación en la Aplicación Web

La navegación de la aplicación web de **Vehix** se ha diseñado para ofrecer una experiencia fluida, accesible y orientada a la acción. A través de una barra superior fija con accesos rápidos a secciones clave como **Home**, **Bluetooth**, **Library** y **Diagnostic**, el usuario puede moverse fácilmente dentro del sistema sin perder el contexto. La interfaz organiza la información en bloques visuales (tarjetas) que resumen el estado del vehículo, alertas, historial y plan de suscripción, permitiendo una comprensión rápida. Además, se utilizan flujos guiados paso a paso para procesos como el escaneo del vehículo, lo que facilita la interacción y asegura que el usuario complete sus objetivos sin complicaciones.

**Estructura y acciones:**

- **Barra de navegación superior fija**, con íconos claros para acceder a:
	- **Home** (panel principal)
	- **Bluetooth** (conexión del adaptador)
	- **Library** (recursos técnicos y guías)
	- **Diagnostic** (herramientas de escaneo)

- **Tarjetas funcionales** en el dashboard principal:
	-  Resumen del estado del vehículo
	-  Historial de escaneos
	-  Alertas recientes
	-  Estado técnico
	-  Plan actual del usuario
- **Navegación por flujo** (cuando se realiza un escaneo):
	-  Selección del vehículo
	-  Conexión del adaptador
	-  Inicio del diagnóstico
	-  Resultados y recomendaciones
   
## 4.3. Landing Page UI Design
En esta sección se presenta el diseño de la Landing Page de Vehix, enfocado en captar la atención de los usuarios objetivo desde el primer contacto. El diseño busca comunicar claramente el valor del producto, generar confianza e incentivar la acción mediante una interfaz moderna, intuitiva y alineada a los principios de usabilidad.

### 4.3.1. Landing Page Wireframe
Para la elaboración del esquema de nuestra landing page, hemos utilizado la herramienta de Figma para el proceso de diseño t desarrollo. Esta herramienta nos permitió completar de manera eficiente y efectiva los wireframes.

desktop:

**Hero section**: La sección principal de la landing page.

![header img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/header.png)

**Introductory video**: Sección donde se mostrará un video introductorio de Vehix.

![introductory-video img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/explanatory-video.png)

**Subscriptions**: En esta sección se mostrarán las subscripciones.

![subscription img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/subscriptions.png)

**Benefits**: Se mostrarán los beneficios de usar Vehix.

![benefits img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/benefits.png)

**Testimonials**: Se mostrarán testimonios de usuarios.

![testimonials img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/testimonials.png)

**About us**: Sección donde se presentarán a los integrantes del equipo encargado de desarrollar Vehix.

![who are we img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/who_are_we.png)

**Frequently asked questions**: Sección donde se mostrarán algunas preguntas comunes que los usuarios se hacen con su respectiva respuesta.

![faq img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/faq.png)

**Compatibility**: Aquí se mostrará la compatibilidad de Vehix con los vehículos

![compatible vehicles img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/compatibility.png)

**Contact us**: Vista donde se mostrará un formulario de contacto.

![contact img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/contact.png)

**Footer**: El pie de página de la landing page

![footer img](/assets/imgs/chapter-IV/landing-page-wireframes/desktop/footer.png)

**Enlace:** [Landing Page Wireframe Desktop](https://www.figma.com/board/FtAqVd7cIoi2dPF7zj6QyZ/Landing-Page-Wireframe-Desktop?node-id=0-1&t=G4vMdaFVt8oKgN35-1)

mobile:

**Hero section**: La sección principal de la landing page.

![header img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/header.png)

**Introductory video**: Sección donde se mostrará un video introductorio de Vehix.

![introductory-video img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/explanatory-video.png)

**Subscriptions**: En esta sección se mostrarán las subscripciones.

![subscription img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/subscriptions.png)

**Benefits**: Se mostrarán los beneficios de usar Vehix.

![benefits img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/benefits.png)

**Testimonials**: Se mostrarán testimonios de usuarios.

![testimonials img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/testimonials.png)

**About us**: Sección donde se presentarán a los integrantes del equipo encargado de desarrollar Vehix.

![who are we mobile img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/who_are_we_wireframe.png)

**Frequently asked questions**: Sección donde se mostrarán algunas preguntas comunes que los usuarios se hacen con su respectiva respuesta.

![faq mobile img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/faq_wireframe.png)

**Compatibility**: Aquí se mostrará la compatibilidad de Vehix con los vehículos.

![compatible vehicles mobile img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/compatibility_wireframe.png)

**Contact us**: Vista donde se mostrará un formulario de contacto.

![contact mobile img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/contact_wireframe.png)

**Footer**: El pie de página de la landing page

![footer mobile img](/assets/imgs/chapter-IV/landing-page-wireframes/mobile/footer_wireframe.png)

**Enlace:** [Landing Page Wireframe Mobile](https://www.figma.com/board/KkF7XJTKOPTObhSmUJVSjt/Landing-Page-Wireframe-Mobile?node-id=0-1&t=LUvRfxBfSQvpM2Ha-1)

### 4.3.2. Landing Page Mock-up
Finalizamos con éxito el desarrollo del mock-up del landing page, lo que nos permitió poner en práctica los principios y elementos de diseño previamente definidos. Estos principios y heurísticas son clave para ofrecer una experiencia más clara, intuitiva y centrada en el usuario final de nuestra plataforma.

Desktop:

**Hero section**: La sección principal de la landing page, se colocó una imagen con el logo de vehix y el slogan seguido de un texto introductorio.

![banner img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/banner.png)

**Introductory video**: Sección donde se mostrará un video introductorio de Vehix.

![explanatory img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/explanatory-video.png)

**Subscriptions**: En esta sección se mostrarán las subscripciones en un cuadro deslizante.

![subscription img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/subscription.png)

**Benefits**: Se mostrarán los beneficios de usar Vehix.

![benefits img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/benefits.png)

**Testimonials**: Se mostrarán testimonios de usuarios.

![testimonials img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/testimonials.png)

**About us**: Sección donde se presentarán a los integrantes del equipo encargado de desarrollar Vehix.

![who-are-we img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/who-are-we.png)

**Frequently asked questions**: Sección donde se mostrarán algunas preguntas comunes que los usuarios se hacen con su respectiva respuesta.

![frequently-asked-questions img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/frequently-asked-questions.png)

**Compatibility**: Aquí se mostrará la compatibilidad de Vehix con los vehículos.

![compatibility img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/compatibility.png)

**Contact us**: Vista donde se mostrará un formulario de contacto.

![contact-us img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/contact-us.png)

**Footer**: El pie de página de la landing page, donde se muestran las redes sociales de Vehix.

![footer img](/assets/imgs/chapter-IV/landing-page-mock-ups/desktop/footer.png)

**Enlace:** [Landing Page Mock-up Desktpo (ANGULAR)](https://www.figma.com/design/lRwE2inDrGxkbKubGMD60s/Landing-Page-material?node-id=6-2&t=g0WNp2SZQcUv5WAn-1)

Mobile:

**Hero section**: La sección principal de la landing page, se colocó una imagen con el logo de vehix y el slogan seguido de un texto introductorio.

![banner img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/banner.png)

**Introductory video**: Sección donde se mostrará un video introductorio de Vehix.

![explanatory-video img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/explanatory-video.png)

**Subscriptions**: En esta sección se mostrarán las subscripciones en un cuadro deslizante.

![subscription img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/subscription.png)

**Benefits**: Se mostrarán los beneficios de usar Vehix.

![benefits img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/benefits.png)

**Testimonials**: Se mostrarán testimonios de usuarios.

![testimonials img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/testimonials.png)

**About us**: Sección donde se presentarán a los integrantes del equipo encargado de desarrollar Vehix.

![who-are-we img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/who-are-we.png)

**Frequently asked questions**: Sección donde se mostrarán algunas preguntas comunes que los usuarios se hacen con su respectiva respuesta.

![frequently-asked-questions img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/frequently-asked-questions.png)

**Compatibility**: Se mostrará la compatibilidad de Vehix con los vehículos.

![compatibility img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/compatibility.png)

**Contact us**: Vista donde se mostrará un formulario de contacto.

![contact-us img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/contact-us.png)

**Footer**: El pie de página de la landing page, donde se muestran las redes sociales de Vehix.

![footer img](/assets/imgs/chapter-IV/landing-page-mock-ups/mobile/footer.png)

**Enlace:** [Landing Page Mock-up Mobile (ANGULAR)](https://www.figma.com/design/C6GwXgygcEA8isP6H55iR1/landing-page-mobile-angular-material?node-id=6-2&t=s0KQX1d2S1xfxRsS-1)

## 4.4. Web Applications UX/UI Design
En esta sección se incluyen secciones internas en el cual se presentará y explicará la propuesta visual y de interacción para las aplicaciones que conforman la interacción del usuario con los productos digitales. 
### 4.4.1. Web Applications Wireframes
A continuación, hemos creado el diseño de los wireframes para el diseño de nuestras aplicaciones, lo que ayudará a planificar la interfaz y la navegación antes de empezar su desarrollo. Para este proyecto utilizamos la herramienta Figma para la elaboración de los wireframes de manera colaborativa y eficiente.

**Enlace:** [Wireframes en Figma (ANGULAR)](https://www.figma.com/design/K1IvSygg5TLNZ1OypNJV42/aplication-web-angular-material?node-id=6-2&t=9PJfXaLh7mZjTde0-1)

### Log in, sign up and subscription

Vistas para registro e ingreso del usuario, además está la vista para escoger una subscripción.

![log-in](/assets/imgs/chapter-IV/wireframe/log-in/log-in.png)
![sign-up](/assets/imgs/chapter-IV/wireframe/log-in/sign-up.png)
![subscriptions-plannes](/assets/imgs/chapter-IV/wireframe/log-in/subscriptions-plannes.png)

### Plan PRO

Los siguientes wireframes pertenecen a el tópico de mantenimiento. Se pueden apreciar las vistas de "car useful life", "recent repairs", entre otras.

![maintenance](/assets/imgs/chapter-IV/wireframe/plan-pro/maintenance-view-1.png)

![maintenance](/assets/imgs/chapter-IV/wireframe/plan-pro/maintenance-view-2.png)

Los siguientes wireframes pertenecen a el tópico de biblioteca. Se le ofrecerá al usuario diferentes recursos informativos.

![library](/assets/imgs/chapter-IV/wireframe/plan-pro/library-view-1.png)

![library](/assets/imgs/chapter-IV/wireframe/plan-pro/library-view-2.png)

Los siguientes wireframes pertenecen a el tópico de sincronización. Se mostrará la vista principal de sincronización con el auto.

![sync](/assets/imgs/chapter-IV/wireframe/plan-pro/sync-views.png)

Los siguientes wireframes pertenecen al manejo de perfil del usuario. 

![profile](/assets/imgs/chapter-IV/wireframe/plan-pro/profile-views.png)

### Plan STANDARD

Los siguientes wireframes pertenecen a el tópico de mantenimiento. Se pueden apreciar las vistas de "car useful life", "recent repairs", entre otras. Sin embargo, tendrá ciertas vistas o componentes bloqueados debido a que es de un plan estándar y no pro.

![maintenance](/assets/imgs/chapter-IV/wireframe/plan-standard/maintenance-view-11.png)

![maintenance](/assets/imgs/chapter-IV/wireframe/plan-standard/maintenance-view-22.png)

Los siguientes wireframes pertenecen a el tópico de biblioteca. Se le ofrecerá al usuario diferentes recursos informativos. Sin embargo, tendrá ciertas vistas o componentes bloqueados debido a que es de un plan estándar y no pro.

![library](/assets/imgs/chapter-IV/wireframe/plan-standard/library-view-11.png)

![library](/assets/imgs/chapter-IV/wireframe/plan-standard/library-view-22.png)

Los siguientes wireframes pertenecen a el tópico de sincronización. Se mostrará la vista principal de sincronización con el auto.

![sync](/assets/imgs/chapter-IV/wireframe/plan-standard/sync-view.png)

Los siguientes wireframes pertenecen al manejo de perfil del usuario. 

![profile](/assets/imgs/chapter-IV/wireframe/plan-standard/profile-view.png)


### 4.4.2. Web Applications Wireflow Diagrams
Se le presenta el Enlace en el cual hemos desarrollado los wireflows de nuestra aplicación en la herramienta de Lucidchart

**Enlace:** [Web Applications Wireflow Diagrams](https://lucid.app/lucidchart/3eb6847b-a363-4738-8eb6-d7f082327aa7/edit?viewport_loc=-19256%2C-8573%2C63373%2C29183%2C0_0&invitationId=inv_0ed080f8-295b-41da-9e88-53d0d46112c9)

A continuación, se presentan los wireflows que competen a nuestros user goals.

- User goal: Como propietario de vehículo urbano, quiero registrarme en la plataforma.
  
![topic-1](/assets/imgs/chapter-IV/register.png)

El usuario llena un formulario de registro, elige un plan (Standard o Pro) y se suscribe para utilizar las funcionalidades de la aplicación, con beneficios y precios visibles para cada plan.

- User goal: Como propietario de vehículo urbano, quiero iniciar sesión en la plataforma.
  
![topic-2](/assets/imgs/chapter-IV/login.png)

El usuario ingresa sus credenciales en la pantalla de login. Si son correctas, accede a la pantalla principal donde puede visualizar diagnósticos, conectar su vehículo y acceder a la biblioteca.

- User goal: Como mecánico automotriz, quiero conectar el escáner al vehículo vía Bluetooth.
  
![topic-3](/assets/imgs/chapter-IV/bluetooth-conection.png)

El mecánico accede a la sección de conexión Bluetooth, sigue las instrucciones de vinculación del dispositivo, y tras conectar exitosamente el escáner, puede iniciar el diagnóstico, adaptándose al plan STANDARD o PRO.

- User goal: Como propietario de vehículo urbano, quiero registrar mi vehículo en la aplicación.
  
![topic-4](/assets/imgs/chapter-IV/add-new-vihecle.png)

El propietario ingresa al sistema, accede a la opción de agregar un nuevo vehículo, completa la información necesaria y visualiza el estado del vehículo registrado, diferenciando los permisos entre plan STANDARD y PRO.

- User goal: Como conductor independiente, quiero editar mis datos personales dentro de la plataforma.
  
![topic-5](/assets/imgs/chapter-IV/editing-personal-information.png)

Desde su perfil, el conductor puede actualizar información como nombre, correo y otros datos. Los usuarios del plan STANDARD encuentran restricciones en ciertas secciones, mientras que el plan PRO permite editar y visualizar todo el contenido.

- User goal: Como conductor independiente, quiero ver una descripción sencilla del problema detectado en mi vehículo.
  
![topic-6](/assets/imgs/chapter-IV/summary-description.png)

El conductor accede al diagnóstico rápido del vehículo, donde se muestra un resumen de las fallas detectadas. Los usuarios con plan PRO acceden al detalle técnico, mientras que los de plan STANDARD visualizan contenido bloqueado.

- User goal: Como conductor independiente, quiero encontrar talleres mecánicos cercanos a mi ubicación.
  
![topic-7](/assets/imgs/chapter-IV/find-a-mechanical-workshop.png)

Después de realizar un escaneo vehicular, el usuario accede a una sección que muestra talleres mecánicos cercanos basados en GPS. Los usuarios del plan PRO visualizan detalles de talleres, mientras que los usuarios del plan STANDARD deben actualizar su plan para acceder a esta información.

- User goal: Como mecánico automotriz, quiero acceder a una biblioteca automotriz.
  
![topic-8](/assets/imgs/chapter-IV/library.png)

El usuario entra a la sección de biblioteca donde puede elegir entre videos tutoriales, artículos técnicos, manuales, avances del sector y recomendaciones de mantenimiento, facilitando su actualización profesional.

- User goal: Como mecánico automotriz, quiero realizar un diagnóstico detallado del vehículo.
  
![topic-9](/assets/imgs/chapter-IV/pro-vehicle-diagnostics.png)

Desde la sección de diagnóstico, el mecánico puede acceder a múltiples funcionalidades como pronóstico de fallas, vida útil del vehículo, diagnóstico rápido, historial de escaneos y reparaciones recientes, todo pensado para un análisis técnico completo.

- User goal: Como conductor independiente, quiero renovar mi suscripción dentro de la plataforma.
  
![topic-10](/assets/imgs/chapter-IV/renew-subscription.png)

El usuario accede a su perfil, visualiza el estado de su suscripción y procede a renovarla o cambiar de plan mediante un proceso de pago sencillo para no perder el acceso a las funcionalidades.

- User goal: Como propietario de vehículo urbano, quiero realizar un escaneo básico de mi vehículo.
  
![topic-11](/assets/imgs/chapter-IV/standard-diagnosis.png)

El usuario accede al diagnóstico estándar donde puede visualizar datos generales del vehículo y fallas encontradas. Parte del contenido técnico queda bloqueado para los usuarios de plan STANDARD, incentivando la actualización al plan PRO para obtener información más detallada.

- User goal: Como propietario de vehículo urbano, quiero realizar el pago de mi suscripción de forma rápida.
  
![topic-12](/assets/imgs/chapter-IV/subscription-payment.png)

Después de registrarse, el usuario elige entre el plan Standard o el plan Pro y procede a realizar el pago ingresando los datos requeridos. Dependiendo del plan seleccionado, el usuario accede a diferentes beneficios en la aplicación.

- User goal: Como mecánico automotriz, quiero visualizar el estado técnico del vehículo con datos detallados.
  
![topic-13](/assets/imgs/chapter-IV/technical-data.png)

Desde el diagnóstico, el mecánico puede acceder a los datos técnicos identificados en el último escaneo. Los usuarios con plan PRO acceden a información detallada, mientras que los usuarios de plan STANDARD tienen contenido bloqueado que los invita a actualizar su plan.

- User goal: Como conductor independiente, quiero consultar el estado de mi suscripción.
  
![topic-14](/assets/imgs/chapter-IV/view-subscription-status.png)

Tras iniciar sesión, el usuario ingresa a su cuenta donde puede visualizar el tipo de plan activo (Standard o Pro). La vista muestra claramente el estado de la suscripción, beneficios actuales y posibles restricciones según el tipo de plan.

### 4.4.3. Web Applications Mock-ups
Los mockups representan una etapa clave en el diseño de nuestras aplicaciones, ya que nos brindan una vista previa de la estética y la organización de los componentes antes de iniciar el proceso de desarrollo. A continuación, se  le presenta el Enlace de los mock-ups elaborados en la herramienta de Figma.

**Enlace:** [Mock-ups en Figma (ANGULAR)](https://www.figma.com/design/K1IvSygg5TLNZ1OypNJV42/aplication-web-angular-material?node-id=6-2&t=9PJfXaLh7mZjTde0-1)

### Log in, sign up and subscriptions

Vistas para registro e ingreso del usuario.

![log-in](/assets/imgs/chapter-IV/mock-up/log-in/log-in.png)
![sign-up](/assets/imgs/chapter-IV/mock-up/log-in/sign-up.png)
![subscriptions-plannes](/assets/imgs/chapter-IV/mock-up/log-in/subscriptions-plannes.png)

### Plan PRO

Los siguientes mock-ups pertenecen a el tópico de mantenimiento. Se pueden apreciar las vistas de "car useful life", "recent repairs", entre otras.

![maitenance](/assets/imgs/chapter-IV/mock-up/plan-pro/maintenance-1.png)

![maintenance](/assets/imgs/chapter-IV/mock-up/plan-pro/maintenance-2.png)

![maintenance](/assets/imgs/chapter-IV/mock-up/plan-pro/maintenance-3.png)

Los siguientes mock-ups pertenecen a el tópico de biblioteca. Se le ofrecerá al usuario diferentes recursos informativos.

![library](/assets/imgs/chapter-IV/mock-up/plan-pro/library-1.png)

![library](/assets/imgs/chapter-IV/mock-up/plan-pro/library-2.png)

Los siguientes mock-ups pertenecen a el tópico de sincronización. Se mostrará la vista principal de sincronización con el auto.

![sync](/assets/imgs/chapter-IV/mock-up/plan-pro/sync.png)

Los siguientes mock-ups pertenecen al manejo de perfil del usuario. 

![profile](/assets/imgs/chapter-IV/mock-up/plan-pro/profile.png)

Los siguientes mock-ups pertenecen a la vista manejo de "home".

![home](/assets/imgs/chapter-IV/mock-up/plan-standard/home.png)

### Plan STANDARD

Los siguientes wireframes pertenecen a el tópico de mantenimiento. Se pueden apreciar las vistas de "car useful life", "recent repairs", entre otras. Se bloquearon algunas funcionalidades de mantenimiento del auto debido al plan elegido.

![maintenance](/assets/imgs/chapter-IV/mock-up/plan-standard/maintenance-11.png)

![maintenance](/assets/imgs/chapter-IV/mock-up/plan-standard/maintenance-22.png)

Los siguientes mock-ups pertenecen a el tópico de biblioteca. Se le ofrecerá al usuario diferentes recursos informativos. Se bloquearon algunos recursos debido al plan elegido.

![library](/assets/imgs/chapter-IV/mock-up/plan-standard/library-11.png)

![library](/assets/imgs/chapter-IV/mock-up/plan-standard/library-22.png)

Los siguientes mock-ups pertenecen a el tópico de sincronización. Se mostrará la vista principal de sincronización con el auto.

![sync](/assets/imgs/chapter-IV/mock-up/plan-standard/sync-e.png)

Los siguientes mock-ups pertenecen al manejo de perfil del usuario. Se bloquearon algunas funcinalidades debido al plan elegido

![profile](/assets/imgs/chapter-IV/mock-up/plan-standard/profile-e.png)

Los siguientes mock-ups pertenecen a la vista manejo de "home".

![home](/assets/imgs/chapter-IV/mock-up/plan-standard/home.png)

### 4.4.4. Web Applications User Flow Diagrams
Se le presenta el Enlace en el cual hemos desarrollado los User Flow de nuestra aplicación en la herramienta de Lucidchart.
**Enlace:** [Web Applications Wireflow Diagrams](https://lucid.app/lucidchart/3eb6847b-a363-4738-8eb6-d7f082327aa7/edit?viewport_loc=-4736%2C-4813%2C10504%2C4366%2C0_0&invitationId=inv_0ed080f8-295b-41da-9e88-53d0d46112c9)

A continuación, se muestran los diagramas de flujo que ilustran los recorridos de los usuarios en función de los User Goals.

- User goal: Como propietario de vehículo urbano, quiero registrarme en la plataforma.
  
![topic-1](/assets/imgs/chapter-IV/user-flow/register.png)

El usuario llena un formulario de registro, elige un plan (Standard o Pro) y se suscribe para utilizar las funcionalidades de la aplicación, con beneficios y precios visibles para cada plan.

- User goal: Como propietario de vehículo urbano, quiero iniciar sesión en la plataforma.
  
![topic-2](/assets/imgs/chapter-IV/user-flow/Login.png)

El usuario ingresa sus credenciales en la pantalla de login. Si son correctas, accede a la pantalla principal donde puede visualizar diagnósticos, conectar su vehículo y acceder a la biblioteca.

- User goal: Como mecánico automotriz, quiero conectar el escáner al vehículo vía Bluetooth.
  
![topic-3](/assets/imgs/chapter-IV/user-flow/bluetooth-connection.png)

El mecánico accede a la sección de conexión Bluetooth, sigue las instrucciones de vinculación del dispositivo, y tras conectar exitosamente el escáner, puede iniciar el diagnóstico, adaptándose al plan STANDARD o PRO.

- User goal: Como propietario de vehículo urbano, quiero registrar mi vehículo en la aplicación.
  
![topic-4](/assets/imgs/chapter-IV/user-flow/add-new-vehicle.png)

El propietario ingresa al sistema, accede a la opción de agregar un nuevo vehículo, completa la información necesaria y visualiza el estado del vehículo registrado, diferenciando los permisos entre plan STANDARD y PRO.

- User goal: Como conductor independiente, quiero editar mis datos personales dentro de la plataforma.
  
![topic-5](/assets/imgs/chapter-IV/user-flow/editing-personal-information.png)

Desde su perfil, el conductor puede actualizar información como nombre, correo y otros datos. Los usuarios del plan STANDARD encuentran restricciones en ciertas secciones, mientras que el plan PRO permite editar y visualizar todo el contenido.

- User goal: Como conductor independiente, quiero ver una descripción sencilla del problema detectado en mi vehículo.
  
![topic-6](/assets/imgs/chapter-IV/user-flow/see-description.png)

El conductor accede al diagnóstico rápido del vehículo, donde se muestra un resumen de las fallas detectadas. Los usuarios con plan PRO acceden al detalle técnico, mientras que los de plan STANDARD visualizan contenido bloqueado.

- User goal: Como conductor independiente, quiero encontrar talleres mecánicos cercanos a mi ubicación.
![topic-7](/assets/imgs/chapter-IV/user-flow/locate-a-mechanics-workshop.png)

Después de realizar un escaneo vehicular, el usuario accede a una sección que muestra talleres mecánicos cercanos basados en GPS. Los usuarios del plan PRO visualizan detalles de talleres, mientras que los usuarios del plan STANDARD deben actualizar su plan para acceder a esta información.

- User goal: Como mecánico automotriz, quiero acceder a una biblioteca automotriz.
  
![topic-8](/assets/imgs/chapter-IV/user-flow/library.png)

El usuario entra a la sección de biblioteca donde puede elegir entre videos tutoriales, artículos técnicos, manuales, avances del sector y recomendaciones de mantenimiento, facilitando su actualización profesional.

- User goal: Como mecánico automotriz, quiero realizar un diagnóstico detallado del vehículo.
  
![topic-9](/assets/imgs/chapter-IV/user-flow/pro-vehicle-diagnostics.png)

Desde la sección de diagnóstico, el mecánico puede acceder a múltiples funcionalidades como pronóstico de fallas, vida útil del vehículo, diagnóstico rápido, historial de escaneos y reparaciones recientes, todo pensado para un análisis técnico completo.

- User goal: Como conductor independiente, quiero renovar mi suscripción dentro de la plataforma.
  
![topic-10](/assets/imgs/chapter-IV/user-flow/renew-subscription.png)

El usuario accede a su perfil, visualiza el estado de su suscripción y procede a renovarla o cambiar de plan mediante un proceso de pago sencillo para no perder el acceso a las funcionalidades.

- User goal: Como propietario de vehículo urbano, quiero realizar un escaneo básico de mi vehículo.
  
![topic-11](/assets/imgs/chapter-IV/user-flow/standar-diagnosis.png)

El usuario accede al diagnóstico estándar donde puede visualizar datos generales del vehículo y fallas encontradas. Parte del contenido técnico queda bloqueado para los usuarios de plan STANDARD, incentivando la actualización al plan PRO para obtener información más detallada.

- User goal: Como propietario de vehículo urbano, quiero realizar el pago de mi suscripción de forma rápida.
  
![topic-12](/assets/imgs/chapter-IV/user-flow/subscription-payment.png)

Después de registrarse, el usuario elige entre el plan Standard o el plan Pro y procede a realizar el pago ingresando los datos requeridos. Dependiendo del plan seleccionado, el usuario accede a diferentes beneficios en la aplicación.

- User goal: Como mecánico automotriz, quiero visualizar el estado técnico del vehículo con datos detallados
  
![topic-13](/assets/imgs/chapter-IV/user-flow/technical-data.png)

Desde el diagnóstico, el mecánico puede acceder a los datos técnicos identificados en el último escaneo. Los usuarios con plan PRO acceden a información detallada, mientras que los usuarios de plan STANDARD tienen contenido bloqueado que los invita a actualizar su plan.

- User goal: Como conductor independiente, quiero consultar el estado de mi suscripción.
  
![topic-14](/assets/imgs/chapter-IV/user-flow/view-subscription-status.png)

Tras iniciar sesión, el usuario ingresa a su cuenta donde puede visualizar el tipo de plan activo (Standard o Pro). La vista muestra claramente el estado de la suscripción, beneficios actuales y posibles restricciones según el tipo de plan.


**Enlace:** [Web Applications Wireflow Diagrams](https://lucid.app/lucidchart/2d4d7fa2-3681-48f3-ab65-b0a939d8a934/edit?viewport_loc=-26575%2C-4225%2C46975%2C19525%2C0_0&invitationId=inv_07979f6b-6654-4d6f-9531-c3db9200aa75)


- User goal: Como propietario de vehículo, quiero registrar un nuevo vehículo en mi cuenta.
  
![topic-1](/assets/imgs/chapter-IV/user-flow/mobile/add-new-vehicle.png)

El usuario accede a la sección de vehículos, selecciona agregar uno nuevo, introduce los datos correspondientes y finalmente puede visualizar la información básica y alertas del vehículo registrado.

- User goal: Como propietario de vehículo, quiero conectar un escáner Bluetooth a mi vehículo.
  
![topic-2](/assets/imgs/chapter-IV/user-flow/mobile/bluetooth-connection.png)

El usuario ingresa a la sección de conexión Bluetooth, sigue las instrucciones de emparejamiento de dispositivos, conecta exitosamente el escáner y procede a iniciar el proceso de escaneo en su vehículo.

- User goal: Como usuario registrado, quiero actualizar mi información personal y método de pago.
  
![topic-3](/assets/imgs/chapter-IV/user-flow/mobile/editing-personal-information.png)

Desde el menú de perfil, el usuario puede editar su nombre, correo, teléfono y actualizar su método de pago, además de visualizar su tipo de plan de suscripción y fecha del próximo cobro.


- User goal: Como conductor, quiero encontrar talleres mecánicos cercanos a mi ubicación.
  
![topic-4](/assets/imgs/chapter-IV/user-flow/mobile/locate-a-nerby-auto-repair-shop.png)

Después de acceder al estado de su vehículo, el usuario puede localizar talleres cercanos a través de un mapa interactivo con información detallada de cada taller automotriz.

- User goal: Como usuario registrado, quiero iniciar sesión en la plataforma.
  
![topic-5](/assets/imgs/chapter-IV/user-flow/mobile/login.png)

El usuario ingresa su usuario y contraseña en la pantalla de login. Una vez autenticado, accede al panel principal donde puede consultar el estado de sus vehículos y su historial de escaneos.

- User goal: Como usuario, quiero cerrar sesión en la aplicación.
  
![topic-6](/assets/imgs/chapter-IV/user-flow/mobile/logout.png)

Desde el menú lateral, el usuario selecciona la opción "Log out", lo que lo redirige nuevamente a la pantalla de inicio de sesión, asegurando el cierre de su cuenta activa.

- User goal: Como mecánico automotriz o conductor del plan PRO, quiero realizar un diagnóstico avanzado de mi vehículo.
  
![topic-7](/assets/imgs/chapter-IV/user-flow/mobile/pro-diagnosis.png)

El usuario del plan PRO accede a distintas secciones de diagnóstico avanzado que incluyen pronóstico de fallas, vida útil del vehículo, diagnósticos rápidos, historial de escaneos y localización de reparaciones recientes con mayor nivel de detalle.

- User goal: Como mecánico automotriz del plan PRO, quiero acceder a una biblioteca de contenidos técnicos, manuales y avances automotrices.
  
![topic-8](/assets/imgs/chapter-IV/user-flow/mobile/pro-library.png)

Desde la sección de biblioteca, los usuarios PRO pueden ingresar a contenido exclusivo como artículos técnicos, manuales de reparación, noticias del sector y recomendaciones sobre mantenimiento y reparaciones, todo organizado de manera intuitiva.

- User goal: Como nuevo usuario, quiero registrarme en la plataforma.
  
![topic-9](/assets/imgs/chapter-IV/user-flow/mobile/register.png)

El usuario completa el formulario de registro ingresando sus datos personales, eligiendo un género, y creando su cuenta, lo que le permite acceder a la plataforma y gestionar su suscripción.

- User goal: Como usuario del plan PRO, quiero ver un resumen detallado de las fallas detectadas en mi vehículo.
  
![topic-10](/assets/imgs/chapter-IV/user-flow/mobile/see-summary-description-of-the-vehicle-failure-plan-pro.png)

El usuario visualiza un resumen gráfico de las áreas del vehículo que presentan fallos, acompañado de una descripción técnica detallada para facilitar la comprensión y posible solución de los problemas detectados.

- User goal: Como usuario del plan Standard, deseo ver una versión resumida de las fallas de mi vehículo.
  
![topic-11](/assets/imgs/chapter-IV/user-flow/mobile/see-summary-description-of-the-vehicle-failure-standard-plan.png)

Después de realizar un escaneo básico, el usuario puede visualizar una lista limitada de las principales fallas detectadas.

- User goal: Como usuario registrado, quiero actualizar mi información personal y método de pago.
  
![topic-12](/assets/imgs/chapter-IV/user-flow/mobile/editing-personal-information.png)

Desde el menú de perfil, el usuario puede editar su nombre, correo, teléfono y actualizar su método de pago, además de visualizar su tipo de plan de suscripción y fecha del próximo cobro.

- User goal: Como usuario del plan Standard, deseo acceder a artículos y guías disponibles gratuitamente.
  
![topic-13](/assets/imgs/chapter-IV/user-flow/mobile/standar-library.png)

El usuario navega en la biblioteca y puede consultar artículos, guías y recomendaciones, con restricciones en algunas secciones premium.

- User goal: Como usuario, quiero adquirir el plan PRO.
  
![topic-14](/assets/imgs/chapter-IV/user-flow/mobile/subscription-payment-pro.png)

El usuario se registra, elige el plan PRO, revisa el resumen de compra y completa el pago para acceder a funciones premium.

- User goal: Como usuario, quiero adquirir el plan Standard.
  
![topic-15](/assets/imgs/chapter-IV/user-flow/mobile/subscription-payment-standar.png)

El usuario se registra, selecciona el plan Standard, revisa los detalles de la suscripción y completa el proceso de pago.

- User goal: Como usuario del plan Standard, deseo ver el estado de mi suscripción y cuándo debo renovarla.
  
![topic-16](/assets/imgs/chapter-IV/user-flow/mobile/view-pro-plan-subscription-standar.png)

Desde la sección "Personal Information", el usuario revisa el tipo de plan activo, el método de pago y la fecha del siguiente cobro.

- User goal: Como usuario del plan PRO, deseo visualizar el estado y detalles de mi suscripción activa.
  
![topic-17](/assets/imgs/chapter-IV/user-flow/mobile/view-pro-plan-subscription-status.png)

En el perfil de usuario, se muestra el tipo de plan PRO contratado, la información de pago y la fecha de renovación.

- User goal: Como usuario del plan Standard, deseo validar mi suscripción y estado de conexión Bluetooth de forma sencilla.
  
![topic-18](/assets/imgs/chapter-IV/user-flow/mobile/view-subscription-status.png)

 El usuario puede ver su historial de escaneos, los dispositivos conectados y el estado general de su plan Standard.

## 4.5. Web Applications Prototyping
A continuación, se muestra el prototipo elaborado a partir de los mockups previamente diseñados y documentados. Este prototipo nos permite visualizar y validar algunos de los flujos que posteriormente serán implementados en el desarrollo del código.

**Enlace:** [Prototipo en Figma (ANGULAR)](https://www.figma.com/design/K1IvSygg5TLNZ1OypNJV42/aplication-web-angular-material?node-id=6-2&t=9PJfXaLh7mZjTde0-1)

![web-applications-prototyping](/assets/imgs/chapter-IV/web-applications-prototyping.png)

## 4.6. Domain-Driven Software Architecture
En esta sección utilizaremos el modelo C4 para definir la arquitectura del software, abarcando niveles como el contexto, los contenedores y los componentes. Este enfoque facilita una visión clara y comprensible de la estructura del sistema, tanto para el equipo de desarrollo como para los stakeholders externos.

### 4.6.1. Software Architecture Context Diagram
El diagrama de contexto del sistema VEHIX representa una visión general de alto nivel de las principales interacciones que el sistema web VEHIX mantiene con usuarios externos y servicios de terceros. Este modelo ilustra cómo el sistema se integra en su ecosistema tecnológico y humano.

![context](/assets/imgs/chapter-IV/arquitecture/context/context.png)

**Actores principales:**

- **Independent Drivers:** Conductores particulares que poseen un vehículo y acceden a VEHIX para obtener diagnósticos y sugerencias de mantenimiento.
    
- **Professional Drivers:** Conductores profesionales que utilizan su vehículo como medio de ingreso (por ejemplo, servicios de taxi o delivery) y dependen de un sistema confiable para mantener su vehículo en óptimas condiciones.
    
- **Mechanics:** Técnicos automotrices que acceden al sistema para visualizar diagnósticos, realizar mantenimientos o atender fallas detectadas.
    

Todos los usuarios acceden al sistema VEHIX a través de un navegador web, utilizando el dominio vehix.com.

**Sistemas externos integrados:**

- **Google Maps:** VEHIX consume su API para ofrecer a los usuarios información sobre talleres mecánicos cercanos y rutas hacia estos puntos de servicio.
    
- **Payments (Visa, Mastercard o American Express):** Se utiliza para procesar pagos dentro del sistema, por ejemplo, para planes premium o servicios contratados por los usuarios.
    
- **Firebase Cloud Messaging:** Este servicio permite a VEHIX enviar notificaciones en tiempo real a los usuarios, como alertas de fallas o recordatorios de mantenimiento.
    
- **Auth0:** Servicio de autenticación encargado de verificar la identidad de los usuarios y otorgarles acceso seguro a la plataforma VEHIX.

### 4.6.2. Software Architecture Container Diagrams
El **diagrama de contenedores** representa la arquitectura interna de alto nivel del sistema VEHIX, descomponiendo el sistema web en contenedores lógicos (como aplicaciones, bases de datos y APIs) y mostrando cómo interactúan entre sí, con los usuarios y con sistemas externos.

![containers](/assets/imgs/chapter-IV/arquitecture/containers/container.png)

#### **Contenedores del sistema VEHIX**

1. **VEHIX Landing Page**  
    Proporciona acceso general e información básica sobre el sistema a través de una interfaz web pública.
    
2. **Web Application**  
    Entrega contenido estático y dinámico (como HTML, CSS, JS) para la SPA (_Single Page Application_).
    
3. **VEHIX Single Page Application (SPA)**  
    Es la aplicación principal que corre en el navegador del usuario. Permite analizar fallos, consultar datos del vehículo y recibir notificaciones. Se comunica con la API mediante solicitudes REST.
    
4. **API Application**  
    Backend del sistema que expone endpoints RESTful para manejar diagnósticos, gestión de usuarios, pagos y más. Orquesta la lógica de negocio y se conecta con los contextos internos.
    
5. **Vehix DB**  
    Base de datos del sistema. Almacena información clave como perfiles, diagnósticos, fallas, pagos, preferencias y suscripciones.
    

#### **Bounded Contexts**

- **Analytics Context:** Proporciona análisis y visualización de datos estadísticos del sistema.
    
- **Profile and References:** Gestiona perfiles de usuario, preferencias, y relaciones entre usuarios y vehículos.
    
- **Assets and Resource Management:** Administra recursos como vehículos, sensores y datos de sensores.
    
- **Service Operation and Monitoring:** Ejecuta diagnósticos, auditorías de fallos y seguimiento en tiempo real.
    
- **Identity and Guest Management:** Gestiona autenticación, roles, sesiones y acceso de invitados.
    
- **Subscription and Payments:** Administra suscripciones, membresías y pagos.


### 4.6.3. Software Architecture Components Diagrams
Estos diagramas de componentes representan la arquitectura de las funcionalidades clave de Vehix. Permiten visualizar su estructura interna y la forma en que se integran con servicios y sistemas externos.

#### **Diagrama de Componentes: Vehix Single Page Application**
Este diagrama representa los **componentes internos** del contenedor **Vehix Single Page Application**, la aplicación Angular que se ejecuta en el navegador del usuario. Aquí se detallan los distintos módulos funcionales y servicios de frontend, junto con sus responsabilidades e interacciones, tanto internas como externas.

![components](/assets/imgs/chapter-IV/arquitecture/components/single-page-aplication-component.png)

##### **Componentes principales (Angular Components)**

- **LanguageSwitcherComponent:** Permite al usuario cambiar el idioma de la aplicación.
    
- **DiagnosticComponent:** Escanea el vehículo y presenta los resultados del diagnóstico.
    
- **FailureListComponent:** Muestra una lista de fallos detectados, clasificados por gravedad.
    
- **SubscriptionComponent:** Permite gestionar y visualizar el plan de suscripción del usuario.
    
- **ProfileComponent:** Permite editar la información del usuario y de su vehículo.
    
- **VehicleCardComponent:** Muestra un resumen visual con la información del vehículo.
    
- **DashboardComponent:** Pantalla principal del usuario con una vista general del estado del vehículo.
    
- **LoginComponent:** Pantalla de autenticación que inicia sesión mediante Auth0.
    

##### **Servicios asociados**

- **TranslationService:** Administra el idioma activo y las traducciones en la interfaz.
    
- **DiagnosticService:** Encapsula la lógica del escaneo del vehículo y realiza llamadas a la API.
    
- **ProfileService:** Administra la comunicación de datos entre el frontend y el backend sobre usuario y vehículo.
    
- **SubscriptionService:** Gestiona las suscripciones y se comunica con la API.
    
- **NotificationService:** Envía notificaciones push a los usuarios a través de Firebase.
    
- **AuthService:** Controla el flujo de autenticación del usuario utilizando Auth0.

#### **Diagrama de Componentes: Profile and References**
El contenedor **Profile and References** dentro del sistema VEHIX se encarga de gestionar toda la información relacionada con el perfil del usuario, sus preferencias y los datos asociados a su vehículo. Este diagrama descompone su estructura en tres componentes principales que colaboran para brindar una funcionalidad coherente y bien organizada.

![components](/assets/imgs/chapter-IV/arquitecture/components/profile-and-references.png)


##### **Componentes**

- **ProfileController**  
    Es el componente principal de entrada (controlador) que expone los endpoints relacionados con el perfil del usuario. Actúa como intermediario entre las solicitudes externas y los servicios que manejan los datos.
    
- **PreferenceService**  
    Se encarga de gestionar las preferencias del usuario, como idioma, tipo de notificaciones, visualización u otras configuraciones personalizadas. El controlador invoca este servicio para leer o actualizar dichas preferencias.
    
- **VehicleService**  
    Maneja la información relacionada con los vehículos registrados por los usuarios. Esto incluye datos técnicos, historial de mantenimiento, marca, modelo, entre otros. El controlador utiliza este servicio para acceder y modificar la información del vehículo.

##### **Relaciones**

- `ProfileController` llama a `PreferenceService` para leer y actualizar las preferencias del usuario.
    
- `ProfileController` también interactúa con `VehicleService` para gestionar los datos del vehículo registrado por el usuario.

#### Diagrama de Componentes: Assets and Resource Management
El contenedor **Assets and Resource Management** forma parte de la arquitectura del sistema VEHIX y se encarga de la gestión de los datos históricos, archivos y recursos asociados a los usuarios. Este contenedor organiza su funcionalidad mediante componentes especializados, siguiendo principios de separación de responsabilidades y escalabilidad.

![components](/assets/imgs/chapter-IV/arquitecture/components/assets-and-resource-managements.png)

##### **Componentes principales**

- **ResourcesController**  
    Es el componente de entrada que expone los endpoints relacionados con los recursos del sistema. Permite que otros contenedores o servicios accedan a funcionalidades como la recuperación de archivos, el acceso a historiales o comentarios.
    
- **HistoryService**  
    Encargado de manejar la lógica relacionada con la exportación e importación de datos históricos del usuario, como registros de diagnósticos, resultados anteriores o trazabilidad del vehículo.
    
- **FileService**  
    Administra la subida, almacenamiento y acceso a archivos. Se encarga de que los documentos o datos generados por el usuario (por ejemplo, informes de diagnóstico o comentarios adjuntos) puedan ser gestionados de forma segura.
    
- **ResourcesModel**  
    Representa el modelo de datos que agrupa los distintos recursos que gestiona este contenedor. Incluye entidades como `History`, `Comment`, `File` y `Sample`, que permiten estructurar la información relacionada con el usuario y su vehículo.

##### **Relaciones internas**

- `ResourcesController` actúa como orquestador y delega las solicitudes al `HistoryService` para operaciones de historial, o al `FileService` para subir o descargar archivos.
    
- Ambos servicios utilizan el modelo `ResourcesModel` para representar y manipular los datos asociados a recursos del sistema.

#### **Diagrama de Componentes: Analytics Context**
El contenedor **Analytics Context** forma parte de la arquitectura de VEHIX y se especializa en recolectar, analizar y visualizar datos de uso del sistema. Este contenedor permite generar informes útiles tanto para los usuarios con el objetivo de mejorar el rendimiento del sistema y la experiencia del usuario mediante el análisis de patrones de comportamiento y uso vehicular.

![components](/assets/imgs/chapter-IV/arquitecture/components/analytics-context.png)

##### **Componentes principales**

- **AnalyticsController**  
    Es el componente encargado de exponer los endpoints necesarios para consultar datos analíticos. Recibe solicitudes externas y las redirige a los servicios internos adecuados.
    
- **UsageStatsService**  
    Se encarga de recolectar y procesar los datos de uso del sistema. Su función principal es proporcionar una base sólida de información que puede ser utilizada para análisis y generación de reportes.
    
- **TrendAnalyzerService**  
    Analiza los datos procesados para identificar patrones recurrentes en el uso del sistema o comportamiento del vehículo. Este componente es clave para detectar anomalías.
    
- **ReportGeneratorService**  
    Genera informes descargables a partir de los datos analizados. Se alimenta de las estadísticas procesadas y es invocado por el controlador o por el componente visual.
    
- **AnalyticsView**  
    Componente de presentación que transforma los datos analíticos en contenido visual para el frontend. Permite mostrar la información de forma clara y comprensible al usuario.

##### **Relaciones clave**

- `AnalyticsController` solicita a `UsageStatsService` la recopilación y análisis de datos.
    
- `UsageStatsService` entrega información a `TrendAnalyzerService` para detectar tendencias.
    
- `ReportGeneratorService` utiliza datos procesados por `UsageStatsService` para crear reportes.
    
- `AnalyticsView` transforma esos reportes en contenido visual.
    
- Todo el flujo parte del controlador y termina con la visualización clara y útil para el usuario.

#### **Diagrama de Componentes: Subscription and Payments**
El contenedor **Subscription and Payments** del sistema VEHIX se encarga de la administración de planes de suscripción, procesamiento de pagos y generación de facturas. Este módulo permite a los usuarios acceder a funcionalidades premium mediante pagos integrados con proveedores externos como Visa, Mastercard o American Express.

![components](/assets/imgs/chapter-IV/arquitecture/components/subscription-and-payments.png)

##### **Componentes principales**

- **SubscriptionController**  
    Componente controlador que expone los endpoints públicos relacionados con las suscripciones. Es responsable de iniciar procesos como el pago de un plan, o la consulta y modificación del estado de suscripción del usuario.
    
- **PlanService**  
    Encargado de gestionar los planes de suscripción disponibles. Administra los datos relacionados con los planes, como su precio, duración y características, y permite actualizar el plan asociado a un usuario.
    
- **BillingService**  
    Maneja la lógica del procesamiento de pagos. Coordina con el proveedor externo de pagos y se encarga de validar y completar las transacciones iniciadas por el usuario.
    
- **InvoiceService**  
    Genera comprobantes de pago (facturas) una vez completada la transacción. Además, permite recuperar facturas anteriores asociadas a una suscripción.

##### **Integración con sistema externo**

- **Payments (Visa, Mastercard o American Express)**  
    Es el sistema externo que se utiliza para realizar el procesamiento de los pagos. El `BillingService` se conecta con esta plataforma para completar la transacción de forma segura.

##### **Relaciones entre componentes**

- `SubscriptionController` inicia el procesamiento de pago a través de `BillingService`, y consulta los datos del plan mediante `PlanService`.
    
- Una vez realizado el pago, `BillingService` solicita a `InvoiceService` que genere una factura correspondiente.
    
- `BillingService` también se encarga de contactar al proveedor externo de pagos (Payments) para ejecutar la transacción.

#### **Diagrama de Componentes: Identity and Guest Management**
El contenedor **Identity and Guest Management** dentro de la arquitectura de VEHIX es responsable de gestionar el proceso de autenticación de usuarios, registro de nuevos perfiles y control de acceso basado en roles. Este contenedor asegura que sólo usuarios autorizados puedan acceder a funcionalidades específicas, manteniendo la seguridad y privacidad del sistema.

![components](/assets/imgs/chapter-IV/arquitecture/components/identity-and-guest-management.png)

##### **Componentes principales**

- **IdentityController**  
    Actúa como punto de entrada para todas las operaciones de autenticación y registro. Este controlador maneja las solicitudes de inicio de sesión y registro de nuevos usuarios, delegando las operaciones a los servicios correspondientes.
    
- **AuthServiceBackend**  
    Se encarga de procesar los inicios y cierres de sesión del usuario. Además, es responsable de verificar las credenciales y delegar la autenticación en el sistema externo (Auth0).
    
- **UserRegistrationService**  
    Gestiona el proceso de registro de nuevos usuarios, incluyendo validaciones y almacenamiento de datos. Se comunica con el sistema de autenticación externo cuando es necesario.
    
- **AccessControlService**  
    Aplica reglas de acceso basadas en roles. Asegura que cada usuario tenga permisos adecuados según su perfil (por ejemplo, conductor, mecánico, invitado, etc.).

##### **Integración externa**

- **Auth0**  
    Servicio de autenticación de terceros que verifica la identidad de los usuarios y proporciona un acceso seguro a VEHIX. El componente `IdentityController` delega en Auth0 la verificación de identidad y autenticación de credenciales.
    
##### **Relaciones clave**

- `IdentityController` redirige las solicitudes de inicio de sesión a `AuthServiceBackend` y las de registro a `UserRegistrationService`.
    
- `AuthServiceBackend` utiliza `AccessControlService` para verificar permisos basados en el rol del usuario.
    
- Tanto `AuthServiceBackend` como `UserRegistrationService` delegan en **Auth0** la verificación de credenciales y autenticación segura.

#### Diagrama de Componentes: Service Operation and Monitoring Context
El contenedor **Service Operation and Monitoring Context** es uno de los núcleos funcionales más importantes del sistema VEHIX. Se encarga del **monitoreo en tiempo real** del estado del vehículo y la generación de alertas basadas en los datos recibidos por sensores y servicios de localización GPS. Este módulo es fundamental para garantizar una experiencia de usuario proactiva y preventiva.

![components](/assets/imgs/chapter-IV/arquitecture/components/service-operation-monitoring.png)

##### **Componentes principales**

- **MonitoringController**  
    Controlador principal del contenedor. Expone los endpoints relacionados con el monitoreo del vehículo y es el punto de entrada para los datos provenientes de sensores u otras fuentes.
    
- **LiveTrackingService**  
    Servicio que gestiona el rastreo del vehículo utilizando datos GPS. Permite seguir la ubicación en tiempo real y enriquecer los análisis diagnósticos con contexto geográfico.
    
- **DiagnosticEngineService**  
    Núcleo de análisis del sistema. Procesa los datos de sensores y ubicación para detectar anomalías, comportamientos inusuales o patrones que requieran atención inmediata. Su salida puede activar alertas.
    
- **AlertService**  
    Genera alertas en tiempo real cuando el motor de diagnóstico detecta fallos. Estas alertas son enviadas directamente a los usuarios para mantenerlos informados sobre el estado del vehículo.
    
##### **Integraciones externas**

- **Firebase Cloud Messaging (FCM):**  
    Utilizado para enviar las alertas generadas por el `AlertService` directamente al dispositivo del usuario mediante notificaciones push.
    
- **Google Maps:**  
    Servicio utilizado por `LiveTrackingService` para obtener y usar datos de geolocalización, mejorando el análisis y visualización del estado del vehículo en contexto espacial.
    

##### **Relaciones clave**

- `MonitoringController` recibe los datos y los entrega al `DiagnosticEngineService`.
    
- `LiveTrackingService` proporciona información de ubicación tanto al `DiagnosticEngineService` como a Google Maps.
    
- Si se detecta un fallo, `DiagnosticEngineService` lo reporta al `AlertService`, que a su vez genera una alerta y la envía a través de Firebase.


## 4.7. Software Object-Oriented Design
En la sección de Software Object-Oriented Design se presentarán dos aspectos fundamentales: los diagramas de clase y el diccionario de clases.

### 4.7.1. Class Diagram
En esta vista se le presenta el diagrama de clase con sus entidades respectivas del sistema y sus relaciones de manera visual, lo que facilita la comprensión de cómo se organiza el sistema y cómo interactúan entre sí los distintos componentes del software.

![class-diagram](/assets/imgs/chapter-IV/class-diagram.png)
### 4.7.2. Class Dictionary
El diccionario de clases describe en detalle las propiedades y responsabilidades de cada entidad dentro del sistema, sirviendo como una guía integral para comprender el comportamiento y la lógica del software.

#### **WorkShop**

 - **name:** name of the workshop
 - **direction:** name of the workshop
 - **boss:** mechanical boss assigned to the workshop


#### **MechanicalBoss**

 - **name:** name of the mechanical boss
 - **phoneNumber:** : phone number of the mechanical boss
 - **expertTopic:** mechanical topic the boss specializes in


#### **ListFailure**

 - **listFailure:** list containing the failures detected
 - **quantity:** total number of failures registered


#### **ListAlerts**
- **listFailure:** list containing the alerts detected.
- **quantity:** total number of alerts registered.


#### **Failure**
- **name:** name of the failure
- **code:** code that identifies the failure
- **severityLevel:** level of severity of the failure
- **state:** status of the failure (active or solved)
- **descripcionCause:** description of the cause of the failure


#### **Alert**

 - **name:** name of the alert
 - **severityLevel:** level of severity of the alert
 - **description:** description of the alert


#### **Diagnostic**

 - **fecha:** date when the diagnostic was made
 - **hour:** time when the diagnostic was made
 - **resultSummary:** summary of the diagnostic results

   
#### **Membership**
- **state:** status of the membership (active or inactive)
- **name:** name of the membership plan
- **price:** price of the membership
- **expirationDate:** expiration date of the membership
- **type:** type of membership


 #### **Payment**
- **paymentId:** number that identifies the payment
- **cardNumber:** number of the card used
- **expirationDate:** expiration date of the card
- **securityCode:** security code of the card
- **discount:** discount applied to the payment
- **total:** total amount to pay

  
 #### **Order**
- **idOrder:** number that identifies the order
- **orderDate:** date when the order was made
- **nameMembership:** name of the membership purchased
- **subTotal:** subtotal amount before discounts
- **total:** total amount after discounts


 #### **User**
- **userId:** number that identifies the user
- **name:** name of the user
- **phoneNumber:** phone number of the user
- **email:** email of the user
- **direction:**  address of the user
- **city:** city where the user lives
- **country:** country where the user lives
- **province :** where the user lives
- **postalCode:**  postal code of the user
- **password:** password of the user account
- **listVehicleRegistered:** list of vehicles registered by the user
- **type_plan:** membership plan of the user
- **car:** car information of the user


 #### **Scanner**
- **name:** name of the scanner
- **model:** model of the scanner
- **price:** price of the scanner
- **engineState:** state of the engine
- **transmissionState:** state of the transmission
- **brakeState:** state of the brakes
- **electricalState:** state of the electrical system 
- **steeringState:** state of the steering system 
- **suspensionState:** state of the suspension 
- **fuelState:** state of the fuel system 
- **refrigerationState:** state of the refrigeration system


 #### **RepairedHistory**
- **quantity:** number of repairs recorded
- **date:** date of the repair
- **comments:** comments or notes related to the repair


 #### **itemLibrary**
- **sectionName:** name of the section of the item
- **content:** content of the item
- **reference:** reference associated with the item
  

 #### **Library**
- **listItemLibrary:** list containing items of the library


 #### **Vehicle**
- **idOrder:** number that identifies the order associated with the vehicle
- **name:** name of the vehicle
- **plaque:** plate number of the vehicle
- **mileage:** mileage of the vehicle
- **age:** age of the vehicle
- **color:** color of the vehicle
- **type:** type of vehicle
- **commentStylePerformance:** comments on performance style
- **commentsFutures:** comments about future improvements



## 4.8. Database Design
En la parte dedicada al Diseño de la Base de Datos, se mostrará un diagrama que ilustra cómo están organizadas las entidades y sus vínculos, facilitando un manejo eficiente de los datos tanto para almacenarlos como para consultarlos.

### 4.8.1. Database Diagram
Los diagramas de base de datos muestran la organización interna y las conexiones entre las entidades, facilitando la comprensión de cómo se guardan y vinculan los datos dentro del sistema de forma óptima.

![database-diagram](/assets/imgs/chapter-IV/vehix-db.png)
