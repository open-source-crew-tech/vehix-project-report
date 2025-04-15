# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Vehix es una aplicación innovadora diseñada para supervisar constantemente el estado de un vehículo, ayudando así a preservar y prolongar su vida útil. De modo que, muchos conductores enfrentan el problema frecuente del desconomiento de las condiciones reales de su vehículo. Esto suele llevar a descuidos en el mantenimiento y, eventualmente, a reparaciones costosas cuando los problemas ya se han agravado. Por otro lado, Vehix facilita una comunicación clara y eficiente entre el conductor y el mecánico, traduciendo los datos técnicos del vehículo en información comprensible. Esto permite que ambos puedan entender con precisión el origen de las fallas, evitando malos entendidos y agilizando el proceso de diagnóstico y reparación.


Vehix adopta un enfoque centrado en el conductor, buscando entender sus necesidades de mantenimiento y cuidado vehicular para ofrecer soluciones personalizadas que garanticen el óptimo rendimiento de sus vehículos. Su objetivo es transformar la relación entre los usuarios y sus automóviles, mediante el uso de tecnología inteligente y un compromiso constante con la excelencia funcional y técnica.

| **Misión** | **Visión** |
|------------|------------|
| Brindar a los conductores y mecánicos una solución inteligente y accesible para el monitoreo, diagnóstico y cuidado preventivo de sus vehículos, utilizando adapatadores de diganóstico conectados y análisis de datos en tiempo real, con el fin de prolongar la vida útil de los automóviles y reducir los costos por fallas mecánicas. | Convertirno en una plataforma líder en el Perú para el mantenimiento predictivo vehicular, destacándose por nuestra capcidad de brindar un cuidado vehicular a través de nuestra aplicación. |

### 1.1.2. Perfiles de integrantes del equipo

| Fotos de los integrantes |   Descripción   |
|------------|------------|
|![Dayro img](/assets/imgs/chapter-I/dayro.jpg)|Mi nombre es Dayro Ríos, tengo 18 años, estoy cursando el tercer ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en los lenguajes de programación c++, python, html y css, además gestores de base de datos como mssql. Cuando trabajo en equipo soy comunicativo, responsable y trato de realizar el trabajo lo mejor posible|
|![Antonio img](/assets/imgs/chapter-I/Antonio.jpg)| Mi nombre es Antonio Jhair Navarro Chinga tengo 19 años y soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy colaborativo, responsable y tengo conocimientos en programación estructurada, programación orientada a objetos y algoritmos. |
|![Vitaly img](/assets/imgs/chapter-I/vitaly.jpg) | Mi nombre es Vitaly Baca Camargo, Tengo 19 años y actualmente estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas (UPC). Tengo conocimiento en SQL y C ++, programación orientada objetos y estructura de datos. Además de HTML y CSS. Me considero una persona responsable y comprometida en mis trabajos, por lo que siempre intento ayudar a mi grupo con cualquier duda.|
| ![Moises img](/assets/imgs/chapter-I/moises.png) |Mi nombre es Moisés Espinoza Chávez, estoy estudiando la carrera de Ingeniería de Software y actualmente me encuentro cursando el quinto ciclo.Me gusta el deporte y mantenerme en constante aprendizaje, a menudo disfruto pasar tiempo con amigos, escuchar música o leer algo, considero que tengo habilidades para la adaptabilidad, así como la responsabilidad. Me comprometo con mi grupo para dar lo mejor en este proyecto y hacerlo siempre a tiempo.|
|![Sergio img](/assets/imgs/chapter-I/Sergio.jpg) | Mi nombre es Sergio Gino Julca Minaya, con código u202318274. Actualmente soy estudiante del 5to ciclo de la carrera de Ingienería de Software, con conocimiento de html, css, desarrollo agile, método scrum, entre otros. Asimismo, me considero una persona constante, autodidacta, responsable y me gusta trabajar en equipo, de esta manera apoyaré a mi grupo en todo momento. |
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
+ Se asume que los usuarios estarán dispuestos a pagar por una suscripción mensual para un servicio que les ofrezca monitoreo continuo y recomendaciones personalizadas.
+ Se asume que el pago recurrente de los usuarios permitirá generar ingresos estables para el negocio y hacer rentable el servicio a largo plazo.
+ Se asume que, dado el aumento de la adopción tecnológica, los conductores están dispuestos a integrar un adaptador de diagnóstico (ELM327) y apps en sus vehículos para mejorar la experiencia de conducción y optimizar el mantenimiento.
+ Se asume que los usuarios valoran la simplicidad y conveniencia en la integración de tecnología con sus vehículos.

**Business Outcomes**
+ Los usuarios seguirán suscritos al servicio a largo plazo si perciben un valor claro en la mejora de la durabilidad de sus vehículos y la reducción de costos de reparación.
+ Una vez validado el producto en un mercado objetivo inicial, se busca ampliar el alcance a más conductores en diversas regiones.  
+ La suscripción mensual debería generar un flujo de ingresos constante, lo que permitirá expandir el negocio y financiar mejoras continuas en el producto.
+ A medida que la aplicación recibe más datos de los usuarios, los algoritmos de inteligencia artificial mejoran. Esto permite que el servicio sea más eficiente, ya que las recomendaciones y alertas serán más precisas y útiles. Como resultado, se reducirán los costos de operación y mejorará la calidad del servicio para los usuarios.

**User Assumptions**
+ Creo que mis clientes necesitan una solución práctica y accesible para monitorear el estado de sus vehículos en tiempo real, y mejorar la los diagnósticos y comunicación mecánico-conductor, ya que muchos de estos desconocen cuándo deben realizar mantenimiento preventivo o detectar fallas antes de que se conviertan en problemas costosos o peligrosos.
  
+ Estas necesidades se pueden resolver mediante una aplicación conectada por Bluetooth a un escáner OBD-II (como el ELM327), que permita recibir datos del vehículo directamente en el celular, visualizar alertas, obtener recomendaciones y llevar un historial de mantenimiento y comportamiento del auto.

+ Mis clientes iniciales incluirán conductores de vehículos particulares (de uso diario o familiar), jóvenes adultos con interés en tecnología automotriz, padres de familia que priorizan la seguridad vehicular y mecánico que buscan mejorar sus diagnóstico y fortalecer la confianza con sus clientes.

+ El valor #1 que un cliente quiere de mi servicio es la seguridad y tranquilidad de saber que su vehículo está funcionando correctamente y que será alertado de cualquier posible problema antes de que ocurra una falla mayor.

+ Los usuarios también podrían obtener beneficios adicionales como: historial técnico del auto, recordatorios inteligentes de mantenimiento, patrones de conducción registrados, conexión con técnicos de confianza, y posibles recomendaciones de servicios automotrices aliados.

+ Voy a adquirir a la mayoría de mis usuarios mediante estrategias digitales, como campañas en redes sociales, contenido en YouTube/TikTok sobre mantenimiento de autos, alianzas con tiendas de autopartes y talleres, y presencia en ferias automotrices o de tecnología.

+ Generaré ingresos a través de la app, por medio de las suscripciones mensuales que incluirá funcionalidades como informes detallados del vehículo, predicción de fallas basada en patrones. También se considerará a futuro la alianzas con talleres y servicios técnicos.

+ Nuestra competencia principal son otras apps de diagnóstico automotriz conectadas vía OBD-II, como FIXD, CarMD y Drivvo, además de servicios técnicos tradicionales que no usan tecnología, y plataformas que ofrecen revisiones periódicas sin seguimiento digital.

+ Superaremos a la competencia ofreciendo una experiencia de usuario simple y conectada, con diseño amigable y asistencia, combinando monitoreo inteligente con funciones prácticas como historial y alertas predictivas y en tiempo real.

+ El riesgo más grande para el producto es la resistencia de los usuarios a usar dispositivos adicionales (como el ELM327) o la poca familiaridad con el uso de herramientas tecnológicas en vehículos.

+ Resolveremos este riesgo mediante alianzas con tiendas de autopartes que incluyan el dispositivo con descuento o de regalo, educación simple desde la app sobre cómo usarlo, y funciones que motiven su uso mostrando de forma clara el ahorro, la seguridad y los beneficios de tener el vehículo siempre monitoreado.

**User Outcomes**
+ Los usuarios podrán anticipar problemas en sus vehículos antes de que se conviertan en fallos mayores, reduciendo así la cantidad de reparaciones costosas.
+ Con un monitoreo adecuado y la implementación de las recomendaciones de mantenimiento preventivo, los usuarios lograrán que sus vehículos tengan una vida útil más larga.
+ Los usuarios tendrán acceso a datos confiables sobre el estado de su automóvil, lo que les permitirá sentirse más seguros al conducir y menos preocupados por posibles fallos inesperados.

**Features**
+ **Apdatador diagnóstico para vehículos:** Un adapatador diagnóstico con chip ELM327 instalado en el vehículo que exporta datos a tu celular sobre el estado técnico del automóvil, comportamiento de conducción y hábitos de uso.
+ **Aplicación móvil con dashboard de fácil acceso:** Una interfaz intuitiva que muestre en tiempo real el estado del vehículo, las alertas de mantenimiento y recomendaciones personalizadas para mejorar los hábitos de conducción.
+ **Alertas de mantenimiento preventivo:** Notificaciones proactivas cuando se detectan comportamientos de conducción ineficientes o cuando se acerca el momento de realizar un mantenimiento preventivo.
+ **Asistente de conducción inteligente:** Sugerencias inteligentes sobre cómo mejorar la conducción, realizar el mantenimiento o ajustar los hábitos para maximizar la vida útil del vehículo.
+ **Informes detallados sobre el rendimiento del vehículo:** Resúmenes periódicos que proporcionen a los usuarios una visión completa de cómo están cuidando su vehículo y qué acciones se deben tomar a continuación.

**User Benefits**
+ Monitoreo inteligente y continuo del estado técnico del vehículo.
+ Detección temprana de fallos y alertas preventivas para evitar averías.
+ Mayor control sobre el estado del vehículo y los hábitos de conducción.
+ Recomendaciones personalizadas para el mantenimiento preventivo.
+ Ahorro en gastos de reparación gracias a intervenciones anticipadas.
+ Acceso constante a diagnósticos, alertas y reportes desde el celular.
+ Facilidad de uso sin necesidad de conocimientos mecánicos.

#### 1.2.2.3. Lean UX Hypothesis Statements
- _Creemos que los propietarios de vehículos están dispuestos a pagar una suscripción mensual para tener acceso a una aplicación que les permita monitorear y mejorar el estado de su vehículo._
   - Sabremos que nuestra hipótesis es correcta cuando veamos un aumento significativo del 25% en la cantidad de usuarios que se suscriben a la aplicación y pagan la suscripción mensual.

- _Creemos que existe un mercado creciente de propietarios de vehículos que buscan soluciones tecnológicas para mejorar la eficiencia y reducir los costos de mantenimiento de sus vehículos._
   - Sabremos que nuestra hipótesis es correcta cuando recibamos un aumento del 40% de comentarios positivos de los usuarios sobre la utilidad y eficacia de la aplicación.

- _Creemos que la aplicación Vehix puede proporcionar información y recomendaciones precisas para mejorar el estado de los vehículos y reducir los costos de mantenimiento._
   - Sabremos que nuestra hipótesis es correcta cuando veamos una reducción del 15% a más en los costos de mantenimiento y reparación de los vehículos de los usuarios a través de encuestas por medio de la app.

- _Creemos que la aplicación Vehix puede proporcionar una experiencia de usuario personalizada y adaptada a las necesidades individuales de cada propietario de vehículo._
   - Sabremos que nuestra hipótesis es correcta cuando veamos un aumento del 25% de comentarios positivos de los usuarios sobre la personalización y la adaptabilidad de la aplicación.

- _Creemos que la aplicación Vehix puede ayudar a los propietarios de vehículos a tomar decisiones informadas sobre el mantenimiento y la reparación de sus vehículos._
   - Sabremos que nuestra hipótesis es correcta cuando veamos un aumento del 20% en la cantidad de decisiones informadas tomadas por los propietarios de vehículos sobre el mantenimiento y la reparación de sus vehículos.

#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivos
