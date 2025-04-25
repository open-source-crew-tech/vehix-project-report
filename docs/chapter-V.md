# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.

En esta sección, se tratará de explicar el procedimiento de despliegue de nuestros proyectos como LandingPage, Backend y FrontEnd.

##### LandingPage

Para el despliegue de nuestra landing page se escogio Git Page siendo una alternativa facil de usar y de configurar.

 - **Paso 1:** Para desplegar el LandingPage hay que dirigirse al repositorio del landingPage y luego entrar a la opción de settings.

![paso_1](/assets/imgs/chapter-V/paso-1.png)

 - **Paso 2**: Ahora entraremos a la opción de Pages donde seleccionaremos la rama del proyecto que queremos desplegar

![paso_2](/assets/imgs/chapter-V/paso-2.png)

- **Paso 3:** Es asi como debe quedarla selección de la rama 

![paso_3](/assets/imgs/chapter-V/paso-3.png)

- **Paso 4:** Luego de esperar unos minutos la pagina del LandingPage se desplegara y aparecerá la opción de acceder a esta misma

![paso_4](/assets/imgs/chapter-V/paso-4.png)

## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td>Sprint 1</td>
		</tr>
		<tr>
			<td colspan="2">Spring Planing Background</td>
		</tr>
		<tr>
			<td>Date</td>
			<td>2025-05-22</td>
		</tr>
		<tr>
			<td>Time</td>
			<td>4:50 PM</td>
		</tr>
		<tr>
			<td>Location</td>
			<td>Remote mode through the GitHub platform</td>
		</tr>
		<tr>
			<td colspan="2">Prepared by</td>
		</tr>
		<tr>
			<td>Attends (to planinning meeting)</td>
			<td>All members of crewtech</td>
		</tr>
		<tr>
			<td>Sprint 0 Review Summary</td>
			<td>Since this is our initial development sprint, a sprint summary has not yet been completed.</td>
		</tr>
		<tr>
			<td>Sprint 0 Retrospective Summary</td>
			<td>Since this is our initial development sprint, a sprint summary has not yet been completed.</td>
		</tr>
		<tr>
			<td colspan="2">Sprint Goal & User Stories</td>
		</tr>
		<tr>
			<td>Spritn 1 Goal</td>
			<td>We're focusing on building our landing page. We believe this contributes to the sustainability of the product within our organization. This will be confirmed when we see a significant increase in engagement with our landing page.</td>
		</tr>
		<tr>
			<td>Sprint 1 Velocity</td>
			<td>12</td>
		</tr>
		<tr>
			<td>Sum of Story points</td>
			<td>26</td>
		</tr>
	</tbody>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Landing page |
| ------------------------------------|-----------------|-------------------------------------------|
| Rios Piñan, Dayro Richard|Addicted2u| C | 
| Julca Minaya, Sergio Gino|sergioJM05| C |
| Navarro Chinga, Antonio Jhair | AntonioNavarro24 | L | 
| Baca Camargo, Vitaly Arturo | Mr-Code-Star | C | 
| Espinoza Chávez, Moisés Filemón | MoisesECh | C |

#### 5.2.1.3. Sprint Backlog 1
<table>
	<tbody>
		<tr>
			<td><strong>Sprint #</strong></td>
			<td colspan="7">Sprint 1</td>
		</tr>
		<tr>
			<td colspan="2"><strong>User Story</strong></td>
			<td colspan="6"><strong>Work-item / Task</strong></td>
		</tr>
		<tr>
			<td><strong>Id</strong></td>
			<td><strong>Title</strong></td>
			<td><strong>Id</strong></td>
			<td><strong>Title</strong></td>
			<td><strong>Description</strong></td>
			<td><strong>Estimation (Hours)</strong></td>
			<td><strong>Assisgned To</strong></td>
			<td><strong>Status (To-do / In- Porcess / To-review / Done)</strong></td>
		</tr>
		<tr>
			<td rowspan="3">EP02-US02</td>
			<td rowspan="3">Navegación rápida</td>
			<td>T1</td>
			<td>Añadir lista de etiquetas</td>
			<td>Se añadirán las etiquetas de “Home”,” Subscriptions”,” Benefits”,” Testimonial”, ¿” Who are we?”, “FAQ”, “Support” y “Compatitbility”</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T2</td>
			<td>Vinculación de secciones y estilos</td>
			<td>Se concatenan las etiquetas con sus secciones respectivas, y se añaden estilos correspondientes</td>
			<td>1</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T3</td>
			<td>Nav-var responsive</td>
			<td>Se añade las propiedades en css para el diseño responsive</td>
			<td>1</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP02-US03</td>
			<td>Evidencia de beneficios</td>
			<td>T4</td>
			<td>Añadir lista de beneficios y estilo</td>
			<td>Se añade una lista de beneficios de usar la plataforma y estilos correspondientes</td>
			<td>0.5</td>
			<td>Moises Espinoza</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US31</td>
			<td rowspan="2">Contextualización de la plataforma</td>
			<td>T5</td>
			<td>Añadir descripción de la aplicación</td>
			<td>Se agrega un párrafo atractivo y concreto para el visitante</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T6</td>
			<td>Añadir imágenes y estilos</td>
			<td>Se agrega imagen referencial de dispositivos compatibles y estilos correspondientes</td>
			<td>1</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US32</td>
			<td rowspan="2">Testimonios</td>
			<td>T7</td>
			<td>Añadir comentarios</td>
			<td>Se agrega un comentario por cada usuario acerca de su experiencia con la aplicación</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T8</td>
			<td>Agregar imágenes de usuarios y estilos</td>
			<td>Se agrega fotos de los usuarios que han dejado sus comentarios y se agrega estilos correspondientes</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US33</td>
			<td rowspan="2">Suscripciones</td>
			<td>T9</td>
			<td>Añadir tipo de plan y precios</td>
			<td>Se agregan los títulos de cada plan y sus precios</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T10</td>
			<td>Añadir beneficios y estilos.</td>
			<td>Se listan los beneficios de cada plan y se añaden los estilos correspondientes</td>
			<td>1</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US34</td>
			<td rowspan="2">Video introductorio</td>
			<td>T11</td>
			<td>Creación de video</td>
			<td>Se sube video de guía a YouTube acerca de cómo funciona la aplicación</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T12</td>
			<td>Añadir video y estilo</td>
			<td>Se agrega el link del video de YouTube junto al estilo predefinido</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US35</td>
			<td rowspan="2">Soporte y redes</td>
			<td>T13</td>
			<td>Añadir redes</td>
			<td>Se añaden iconos de las redes sociales de la empresa</td>
			<td>0.5</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T14</td>
			<td>Añadir sección de registro y estilos</td>
			<td>Se añade formulario y se añade los estilos correspondietes</td>
			<td>1</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US36</td>
			<td rowspan="2">Diseño responsive</td>
			<td>T15</td>
			<td>Correccion de errores</td>
			<td>Se corrigen los errores de diseño responsive</td>
			<td>2</td>
			<td>Antonio Nvarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T16</td>
			<td>Añadir propiedades </td>
			<td>Se añaden propiedades principales de estilos y de diseño responsive faltantes.</td>
			<td>1</td>
			<td>Antonio Navarro</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US37</td>
			<td rowspan="2">Visualización de creadores</td>
			<td>T17</td>
			<td>Añadir imágenes y estilos</td>
			<td>Se añade las fotos de cada integrante y se agregan el estilo correspondiente.</td>
			<td>1</td>
			<td>Sergio Julca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T18</td>
			<td>Añadir descripción</td>
			<td>Se añaden descripciones de cada integrante</td>
			<td>0.5</td>
			<td>Sergio Julca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US38</td>
			<td rowspan="2">Visualización de redes</td>
			<td>T19</td>
			<td>Añadir pie de pagina</td>
			<td>Se añade iconos referenciales de cada red social de la empresa</td>
			<td>0.5</td>
			<td>Sergio Julca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T20</td>
			<td>Añadir estilo al pie de pagina</td>
			<td>Se añaden estilos predefinidos al pie de pagina</td>
			<td>1</td>
			<td>Sergio Julca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="3">EP02-US39</td>
			<td rowspan="3">Preguntas frecuentes</td>
			<td>T21</td>
			<td>Añadir preguntas</td>
			<td>Se añaden preguntas frecuentes de los usuarios</td>
			<td>0.5</td>
			<td>Vitaly Baca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T22</td>
			<td>Añadir respuestas</td>
			<td>Se añade mínimo un párrafo de descripción a cerca de la pregunta correspondiente</td>
			<td>0.5</td>
			<td>Vitaly Baca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T23</td>
			<td>Añadir estilo</td>
			<td>Se añade estilos correspondientes y efecto acordeón</td>
			<td>1</td>
			<td>Vitaly Baca</td>
			<td>Done</td>
		</tr>
		<tr>
			<td rowspan="2">EP02-US40</td>
			<td rowspan="2">Sección de vehículos compatibles</td>
			<td>T24</td>
			<td>Añadir información de vehículos compatibles</td>
			<td>Se añade breve información de vehículos compatibles, resaltando el año y tipo de combustible.</td>
			<td>1</td>
			<td>Dayro Rios</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>T25</td>
			<td>Añadir imagen referencial</td>
			<td>Se añade imagen referencial de carros correspondientes a la descripción.</td>
			<td>1</td>
			<td>Dayro Rios</td>
			<td>Done</td>
		</tr>
	</tbody>
</table>

#### 5.2.1.4. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Messaage | Commit Message Body | Commited on |
|------------|--------|-----------|-----------------|---------------------|-------------|
| sergioJM05/vehix-landing-page | main | 01665b9 | initial commmit | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | develop | 01665b9 | initial commmit | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | release | 01665b9 | initial commmit | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/rapid-navigation | b038263 | chore: add initial image | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/rapid-navigation | 11d6326 | feat: add rapid navigation | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/rapid-navigation | feecd09 | chore: add rapid navigation images | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/rapid-navigation | 0185221  | feat: add rapid navigation section in en and es | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |feature/platform-contextualization | d0b3401  | feat: add platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |feature/platform-contextualization | e5ed21c  | feat: add platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |feature/platform-contextualization | 39ef15b  | feat: update platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |develop | a6fc669  | feat: add platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |feature/platform-contextualization | d0b3401  | feat: add platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |feature/platform-contextualization | e5ed21c  | feat: add platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page |feature/platform-contextualization | 39ef15b  | feat: update platform contextualization | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | develop | a6fc669  | feat: add platform contextualization | feature/platform-contextualization | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/introduction-video | f3cb7d3 | feat: add introduction video | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/introduction-video | 1323e5e | feat: add introduction video in es | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | develop | 014691a | feat: add introduction video in es | feature/introduction-video | 25/04/2025 |
| MoisesECh/vehix-landing-page | feature/benefits-evidence | 2d755ea | feature: add benefits evidence | - | 25/04/2025 |
| MoisesECh/vehix-landing-page | feature/benefits-evidence | a851b82 | feature: add benefits evidence in spanish | - | 25/04/2025 |
| MoisesECh/vehix-landing-page | feature/benefits-evidence | 4cae4d3 | chore: add benefits evidence images | - | 25/04/2025 |
| MoisesECh/vehix-landing-page | develop | 4cb8eff  | feat: add benefits evidence in en and es | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/suscriptions | 6864421 | feat: add subscriptions | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/suscriptions | d9c6cfb | feat: add subscriptions | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | develop | c909fac | feat: add subscriptions section in en and es | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/testimonials | 05b116e | feat: add testimonials | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | feature/testimonials | f8ab97e | feat: add testimonials in spanish | - | 25/04/2025 |
| AntonioNavarro24/vehix-landing-page | develop | b729dd3 | feat: add testimonials section in en and es | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | 30058f1 | feat: add creators visualization | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | 6c74848 | feat: add creators visualization in spanish | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | eda6d9d | chore: add creators images | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | eda6d9d | chore: add creators images | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | - | Deleted branch | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | b729dd3  | feat: add testimonials section in en and es | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | aabfcd2  | feat: add creators visualization | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | 32ec068  | feat: add creators visualization in spanish | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | feature/creators-visualization | c674d25  | chore: add creators images | - | 25/04/2025 |
| sergioJM05/vehix-landing-page | develop | 789cc3e | feat: add creators visualization section in es and en | feature/creators-visualization | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | feature/frequently-asked-questions | 75e5adb | feat: add frequently asked questions | - | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | feature/frequently-asked-questions | 082da5c | feat: add frequently asked questions | - | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | develop | 4173cb1 | feat: add frequently asked questions section in en and es | feature/frequently-asked-questions | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | feature/style-javascript | a498504 | feat: add app.js | - | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | feature/style-javascript | a23e30b | feat: add script | - | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | feature/style-javascript | 9498386 | feat: add script | - | 25/04/2025 |
| Mr-Code-Star/vehix-landing-page | develop | eec610e | feat: add app.js | feature/style-javascript | 25/04/2025 |
| Addicted2you/vehix-landing-page | feature/compatible-vehicles | 413d1a4 | feat: add compatible vehicles | - | 25/04/2025 |
| Addicted2you/vehix-landing-page | feature/compatible-vehicles | 7331157 | feat: add compatible vehicles (index_es) | - | 25/04/2025|
| Addicted2you/vehix-landing-page | feature/compatible-vehicles | df55ba1 | feat: add compatible vehicles | feature/compatible-vehicles | 25/04/2025|
| Addicted2you/vehix-landing-page | feature/styles | 888162f | feat: add styles | - | 25/04/2025|
| Addicted2you/vehix-landing-page | develop | 91d4e64 | feat: add styles | feature/styles | 25/04/2025|
| AntonioNavarro24/vehix-landing-page | feature/support-and-networks | 76e9fb9 | feat: add support and networks| - | 25/04/2025|
| AntonioNavarro24/vehix-landing-page | feature/support-and-networks | 5cd7ded | feat: add support and networks| - | 25/04/2025|
| AntonioNavarro24/vehix-landing-page | develop | 0a91751 | feat: add support and networks section in en and es | - | 25/04/2025|
| sergioJM05/vehix-landing-page | feature/network-visualization | 2b973f5 | feat: add footer | - | 25/04/2025|
| sergioJM05/vehix-landing-page | feature/network-visualization | f1888d4 | feat: update footer | - | 25/04/2025|
| sergioJM05/vehix-landing-page | feature/network-visualization | d02dbd2 | feat: add footer in spanish | - | 25/04/2025|
| sergioJM05/vehix-landing-page | develop | 218e3ce | feat: add network visualization section in en and es | feature/network-visualization | 25/04/2025|
| AntonioNavarro24/vehix-landing-page | feature/introduction-video | 990bafb | feat: update video | - | 25/04/2025|
| AntonioNavarro24/vehix-landing-page | feature/introduction-video | 6316ed2 | feat: update video in spanish | - | 25/04/2025|
| AntonioNavarro24/vehix-landing-page | develop | ca4c51c | feat: update introduction video in en and es | feature/introduction-video | 25/04/2025|
| sergioJM05/vehix-landing-page | release | 1ed8491 | feat: add develop | - | 25/04/2025|
| sergioJM05/vehix-landing-page | main | 08e0023 | feat: add release | - | 25/04/2025|
| sergioJM05/vehix-landing-page | feature/platform-contextualization | 10e9700 |fix: change rout of hero image | - | 25/04/2025|
| sergioJM05/vehix-landing-page | feature/platform-contextualization | 222773d |fix: change route of hero image| - | 25/04/2025|
| sergioJM05/vehix-landing-page | develop | ad84967 | feat: fix routes images | feature/platform-contextualization | 25/04/2025|
| sergioJM05/vehix-landing-page | release | 2407cdd | feat: add develop | develop | 25/04/2025|
| sergioJM05/vehix-landing-page | main | 0bbe59e | feat: add release | release | 25/04/2025|

#### 5.2.1.5. Execution Evidence for Sprint Review

Nuestro equipo de desarrolladores logró concluir con el sprint 1, el cual involucra la implementación y despliegue de la landing page de Vehix. A continuación se mostrarán las evidencias.

![banner img](/assets/imgs/chapter-V/banner_evidence.png)

![first_time_evidence img](/assets/imgs/chapter-V/first_time_evidence.png)

![choose plan img](/assets/imgs/chapter-V/plan_evidence.png)

![benefits img](/assets/imgs/chapter-V/benefits_evidence.png)

![testimonials img](/assets/imgs/chapter-V/testimonials_evidence.png)

![who are we img](/assets/imgs/chapter-V/who_are_we_evidence.png)

![questions frequently asked img](/assets/imgs/chapter-V/questions_evidence.png)

![compatibility img](/assets/imgs/chapter-V/compatibility_evidence.png)

![contact us img](/assets/imgs/chapter-V/contact_evidence.png)

![footer img](/assets/imgs/chapter-V/footer_evidence.png)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint
En este apartado se evidencia como el equipo a trabajado de manera colaborativa para lograr la entrega del presente sprint. De esta manera, se incluyen las métricas correspondientes a la creación de la landing page, con el uso de HTML, CSS y JavaScript, y sus commits correspondientes.

![individual-commits](/assets/imgs/chapter-V/individual-commits.png)
![contributors-general-commits](/assets/imgs/chapter-V/contributors-general-commits.png)
