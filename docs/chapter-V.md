# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
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
| Rios Piñan, Dayro Richard|addicted2u| C | 
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
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint
