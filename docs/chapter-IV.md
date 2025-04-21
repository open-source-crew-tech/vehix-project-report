# Capítulo IV: Product Design
## 4.1. Style Guidelines
Las guías de estilo de **Vehix** establecen los lineamientos visuales y comunicativos que aseguran una experiencia coherente, intuitiva y accesible en toda la aplicación. Estas guías fueron diseñadas para mantener consistencia en todos los puntos de contacto con el usuario, incluyendo interfaz, notificaciones y mensajes del sistema.
### 4.1.1. General Style Guidelines
#### 4.1.1.1 Colores
   
  La identidad visual de **Vehix** está centrada en una paleta monocromática compuesta por tonalidades de **blanco y negro**, complementada con un **color de acento turquesa** que aporta un toque moderno, tecnológico y fresco, sin perder sobriedad.

  Esta combinación logra un equilibrio entre seriedad y accesibilidad, ideal para una aplicación enfocada en el mantenimiento vehicular.

##### **Colores principales:**
   
- **Negro puro (#000000):** Para títulos, íconos, botones y elementos destacados.

- **Blanco puro (#FFFFFF):** Color base para fondos principales y espacios de lectura.

- **Gris oscuro (#2E2E2E):** Textos secundarios, menús colapsables o estados inactivos.

- **Gris medio (#7D7D7D):** Indicaciones complementarias y descripciones.

- **Gris claro (#D6D6D6):** Líneas divisoras, bordes y campos desactivados.

- **Gris muy claro (#F5F5F5):** Fondos de tarjetas o secciones secundarias.

  ![color_principales](/assets/imgs/chapter-IV/paleta_de_colores.PNG)
 
##### **Color de acento:**
 
- **Turquesa suave (#A9D8DC):** se utilizará para resaltar zonas clave de interacción como mensajes informativos, botones destacados en pantallas de registro, o fondos secundarios. Este color transmite **tecnología amigable**, **modernidad** y **claridad**.
![color_acento](/assets/imgs/chapter-IV/color_turquesa.PNG)

#### 4.1.1.2 Tipografía

En **Vehix**, la tipografía es un componente esencial para transmitir claridad, profesionalismo y accesibilidad en cada pantalla de la aplicación. Se ha definido el uso de tres fuentes principales, combinando elegancia, legibilidad y modernidad.

##### **PT Serif Regular**
 
 - **Uso:** Títulos principales o mensajes destacados.
 
 - **Justificación:** Su estilo clásico y elegante aporta seriedad y estructura visual, ideal para secciones donde se desea captar la atención con autoridad sin perder sofisticación.

![pt_serif_regular](/assets/imgs/chapter-IV/pt-serif-regular.PNG)

##### **Roboto Regular**
 
- **Uso:** Cuerpo de texto y contenidos largos.

- **Justificación:** Diseñada para pantallas digitales, Roboto ofrece alta legibilidad, ritmo equilibrado y modernidad. Es ideal para descripciones, formularios y mensajes explicativos.

![roboto_regular](/assets/imgs/chapter-IV/roboto-regular.PNG)

##### **Montserrat Regular**

- **Uso:** Botones, etiquetas, menús y elementos de navegación.

- **Justificación:** Con un estilo geométrico y contemporáneo, Montserrat da un toque moderno y dinámico. Es perfecta para jerarquizar acciones y destacar elementos interactivos.

![monserrat_regular](/assets/imgs/chapter-IV/Monserrat-regular.PNG)

#####  4.1.1.3 Spacing:

Los elementos interactivos deben ser lo suficientemente grandes y estar bien espaciados para facilitar su uso, especialmente para quienes tienen dificultades motrices. Un espaciado adecuado asegura que los usuarios puedan tocar o hacer clic en los botones de manera segura, sin riesgo de presionar accidentalmente el botón incorrecto.

- **8 px:** Unidad mínima para separar pequeños elementos (íconos, etiquetas).

- **16 px:** Margen interno típico para botones, tarjetas y campos de formulario.

- **24 px:** Separación entre secciones pequeñas o subtítulos.
  
- **64 px:** Espaciado entre secciones grandes o bloques verticales principales.

#### 4.1.1.4 Branding:

 ##### **Logo**
 
 El logotipo de **Vehix** ha sido diseñado bajo principios de simplicidad, elegancia y profesionalismo, alineado con la propuesta de valor de la aplicación como una herramienta confiable para el cuidado preventivo de vehículos.

![logo](/assets/imgs/chapter-IV/logo.png)

 #### **Características del logotipo**

- **Tipografía:** Se utiliza una fuente **sans serif moderna** con líneas limpias y proporciones equilibradas. Esta elección transmite claridad, orden y tecnología, elementos clave del producto.

- **Espaciado entre letras:** Las letras del nombre **“VEHIX”** se presentan en **mayúsculas y con espaciado amplio**, lo que aporta un toque formal y contemporáneo. Este detalle mejora la legibilidad y refuerza la presencia visual del nombre en distintos tamaños y soportes.

- **Colores:** El logotipo se presenta en **blanco o negro**, según el fondo sobre el que se aplique, asegurando **máximo contraste y versatilidad**. La decisión de evitar colores adicionales responde a la intención de mantener una estética sobria, profesional y adaptable.

- **Ausencia de íconos gráficos:** Por decisión estratégica, el logotipo **no incluye ilustraciones** (como autos, herramientas o ruedas), con el fin de mantener una imagen minimalista y evitar asociaciones literales que limiten la escalabilidad de la marca.

#### 4.1.1.5 Tono de Comunicación

Vehix se comunica con sus usuarios de forma clara, cercana y empática. Para lograrlo, se han definido las siguientes **dimensiones de tono**.

| Dimensión                | Elección       | Justificación                                                                      |
| ------------------------ | -------------- | ---------------------------------------------------------------------------------- |
| Divertido / Serio        | **Serio**      | Se prioriza la confianza y seguridad, especialmente en contextos de alerta.        |
| Formal / Casual          | **Casual**     | Se busca cercanía sin perder profesionalismo, ideal para usuarios cotidianos.      |
| Respetuoso / Irreverente | **Respetuoso** | El respeto es clave para construir relaciones duraderas con los usuarios.          |
| Entusiasta / Sereno      | **Sereno**     | Un tono calmado evita alarmismos y transmite tranquilidad en situaciones técnicas. |

  
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
En este apartado se indicarán los sistemas de organización que se han usado para el "Landing page" y la aplicación web. Entre los tipos de estructuras que han sido escogidas son: jerárquica y secuenciale. Además también indicaremos los esquemas de categorización de contenido.

Para la landing page se ha utilizado una estructura jerárquica en la landing page de Vehix porque permite organizar la información de forma clara y progresiva, guiando al usuario desde lo más general hasta lo más específico.

- Inicio
  
   Banner: imagen principal que comunica el valor del producto
  
   Call to Action: botón destacado como “Empieza ahora”

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

### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram
