# 2021-06-07 Desarrollo Web Completo con HTML5, CSS3, JS AJAX PHP y MySQL
### Autor: Juan Pablo De La Torre Valdez
###### https://www.udemy.com/course/desarrollo-web-completo-con-html5-css3-js-php-y-mysql
###### https://mega.nz/folder/aMtUzLpA#7r3r6_B4RkKn66H1cTc4Sw/folder/iQsGiZKL

## Parte II

### Sección 09 Introduccion a CSS - Creando la Seccion Nosotros del Proyecto de Bienes Raices

#### Video 037 Mostrando el Contenido en 3 columnas.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<section class="contenedor seccion">    
			<h2>Más sobre nosotros</h2>

			<div class="iconos-nosotros">
				<div class="icono">
					<img src="img/icono1.svg" alt="Icono seguridad">
					<h3>Seguridad</h3>
					<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				</div>
		
				<div class="icono">
					<img src="img/icono2.svg" alt="Icono mejor precio">
					<h3>El mejor precio</h3>
					<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				</div>
		
				<div class="icono">
					<img src="img/icono3.svg" alt="Icono a tiempo">
					<h3>A tiempo</h3>
					<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				</div>
			</div>
		</section>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		h4{
			font-size: 2.6rem;
		}

		/** Utilidades **/
		.seccion{
			margin-top: 2rem;
			margin-bottom: 2rem;
		}

		/* Header */
		.site-header.inicio{
			background-image: url(../img/header.jpg);
			background-position: center center;
			background-size: cover; 
			height: 100vh;
			min-height: 60rem;
		}

		≡

		.navegacion a:last-of-type{
			margin-right: 0;
		}

		/** Iconos Nosotros **/
		.iconos-nosotros{
			display: flex;
			justify-content: space-between;
		}

		.icono{
			flex-basis: calc(33.3% - 1rem);
		}
		≡

#### Video 038 Creando algunas utilidades para las secciones y textos.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<section class="contenedor seccion">    
			<h2 class="fw-300 centrar-texto">Más sobre nosotros</h2>

			<div class="iconos-nosotros">
				<div class="icono">
					<img src="img/icono1.svg" alt="Icono seguridad">
					<h3>Seguridad</h3>
					<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				</div>
		
				<div class="icono">
					<img src="img/icono2.svg" alt="Icono mejor precio">
					<h3>El mejor precio</h3>
					<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				</div>
		
				<div class="icono">
					<img src="img/icono3.svg" alt="Icono a tiempo">
					<h3>A tiempo</h3>
					<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				</div>
			</div>
		</section>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Utilidades **/
		.seccion{
			margin-top: 2rem;
			margin-bottom: 2rem;
		}

		.fw-300{
			font-weight: 300;
		}

		.centrar-texto{
			text-align: center;
		}
		≡
		/** Iconos Nosotros **/
		.iconos-nosotros{
			display: flex;
			justify-content: space-between;
		}

		.icono{
			flex-basis: calc(33.3% - 1rem);
			text-align: center;
		}

		.icono h3{
			text-transform: uppercase;
		}

### Seccion 10 Introduccion a CSS - Creando los Anuncios del Proyecto de Bienes Raices

#### Video 039 Primeros pasos en la seccion de Anuncios e imagenes Responsive.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<main class="seccion contenedor">
			<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

			<div class="contenedor-anuncios">
				<div class="anuncio">
					<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
					<div class="contenido-anuncio">
						<h3>Casa de lujo en el lago</h3>
						<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
						<p>$3.000.000,00</p>
						<a href="#">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa terminados de lujo</h3>
						<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
						<p>$2.000.000,00</p>
						<a href="#">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p>$3.000.000,00</p>
						<a href="#">Ver propiedad</a>
					</div>
				</div>
			</div>

			<a href="anuncios.html">Ver todas</a>
		</main>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Globales **/
		img{
			max-width: 100%;
		}

		.contenedor{
			max-width: 120rem;	/** igual a 1200px **/
			margin: 0 auto;
		}
		≡
		.icono h3{
			text-transform: uppercase;
		}

		/** Anuncios **/
		.contenedor-anuncios{
			display: flex;
			justify-content: space-between;
		}
		.anuncio{
			flex-basis: calc(33.3% - 1rem);
		}
		≡

#### Video 040 CSS al contenido de los Anuncios.mp4
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Anuncios **/
		.contenedor-anuncios{
			display: flex;
			justify-content: space-between;
		}
		.anuncio{
			flex-basis: calc(33.3% - 1rem);
			border: 1px solid #B5B5B5;
			background-color: #F5F5F5;
		}

		.contenido-anuncio{
			padding: 2rem;
		}

		.contenido-anuncio h3, 
		.contenido-anuncio p{
			margin: 0;
		}

#### Video 041 Estilos a los Botones Precios en los Anuncios.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<main class="seccion contenedor">
			<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

			<div class="contenedor-anuncios">
				<div class="anuncio">
					<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
					<div class="contenido-anuncio">
						<h3>Casa de lujo en el lago</h3>
						<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
						<p class="precio">$3.000.000,00</p>
						<a href="#" class="boton boton-amarillo">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa terminados de lujo</h3>
						<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
						<p class="precio">$2.000.000,00</p>
						<a href="#" class="boton boton-amarillo">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p class="precio">$3.000.000,00</p>
						<a href="#" class="boton boton-amarillo">Ver propiedad</a>
					</div>
				</div>
			</div>

			<a href="anuncios.html" class="boton boton-verde">Ver todas</a>
		</main>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		.centrar-texto{
			text-align: center;
		}

		/** Botones **/
		.boton{
			color: #ffffff;
			font-weight: 700;
			text-decoration: none;
			font-size: 1.8rem;
			padding: 1rem 3rem;
		}
			
		.boton-amarillo{
			background-color: #E08709;
		}
			
		.boton-verde{
			background-color: #71B100;
		}

		/* Header */
		≡
		.contenido-anuncio h3, 
		.contenido-anuncio p{
			margin: 0;
		}

		.precio{
			color: #71B100;
			font-weight: 700;
		}

#### Video 042 Continuando con los Estilos de los Botones y Box Sizing.mp4
1. Modificar archivo de estilo **css/styles.css**:
	>

		html{
			box-sizing: border-box;
			font-size: 62.5%;	/** Reset para REMS - 62.5% = 10px de 16px **/
		}

		*, *::before, *:after{
			box-sizing: inherit;
		}

		body {
			font-family: 'Lato', sans-serif;
			font-size: 1.6rem;
			line-height: 2;
		}

		/** Globales **/
		img{
			max-width: 100%;
		}
		≡
		/** Botones **/
		.boton{
			color: #ffffff;
			font-weight: 700;
			text-decoration: none;
			font-size: 1.8rem;
			padding: 1rem 3rem;
			margin-top: 3rem;
			display: inline-block;
		}
			
		.boton-amarillo{
			background-color: #E08709;
		}
			
		.boton-verde{
			background-color: #71B100;
		}
		≡

#### Video 043 Finalizando los Botones.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<main class="seccion contenedor">
			<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

			<div class="contenedor-anuncios">
				<div class="anuncio">
					<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
					<div class="contenido-anuncio">
						<h3>Casa de lujo en el lago</h3>
						<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
						<p class="precio">$3.000.000,00</p>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa terminados de lujo</h3>
						<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
						<p class="precio">$2.000.000,00</p>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p class="precio">$3.000.000,00</p>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
			</div>

			<div class="ver-todas">
				<a href="anuncios.html" class="boton boton-verde">Ver todas</a>
			</div>
		</main>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡

		/** Utilidades **/
		.seccion{
			margin-top: 2rem;
			margin-bottom: 2rem;
		}

		.fw-300{
			font-weight: 300;
		}

		.centrar-texto{
			text-align: center;
		}

		.d-block{
			display: block!important;
		}

		≡

		/** Anuncios **/
		.contenedor-anuncios{
			display: flex;
			justify-content: space-between;
		}
		.anuncio{
			flex-basis: calc(33.3% - 1rem);
			border: 1px solid #B5B5B5;
			background-color: #F5F5F5;
		}

		.contenido-anuncio{
			padding: 2rem;
		}

		.contenido-anuncio h3, 
		.contenido-anuncio p{
			margin: 0;
		}

		.precio{
			color: #71B100;
			font-weight: 700;
		}

		.ver-todas{
			display: flex;
			justify-content: flex-end;
		}

#### Video 044 Creando la Imagen de Contacto
1. Modificar el archivo **index.html**:
	>

		≡
		<section class="imagen-contacto">
			<div class="contenedor contenido-contacto">
				<h2>Encuentra la casa de tus sueños</h2>
				<p>Llena el formulario de contacto y un asesor se pondrá en contacto contigo a la brevedad</p>
				<a href="contacto.html" class="boton boton-amarillo">Contáctanos</a> 
			</div>
		</section>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡

		/** Contacto Home **/
		.imagen-contacto{
			background-image: url(../img/encuentra.jpg);
			background-position: center center;
			background-size: cover; 
			height: 40rem;
			display: flex;
			align-items: center;
		}

		.contenido-contacto{
			flex: 1;
			color: #ffffff;
		}

		.contenido-contacto p{
			font-size: 1.8rem;
		}

#### Video 045 Ajustando los Iconos de los Anuncios.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<main class="seccion contenedor">
			<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

			<div class="contenedor-anuncios">
				<div class="anuncio">
					<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
					<div class="contenido-anuncio">
						<h3>Casa de lujo en el lago</h3>
						<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
						<p class="precio">$3.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa terminados de lujo</h3>
						<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
						<p class="precio">$2.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p class="precio">$3.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
			</div>

			<div class="ver-todas">
				<a href="anuncios.html" class="boton boton-verde">Ver todas</a>
			</div>
		</main>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Anuncios **/
		.contenedor-anuncios{
			display: flex;
			justify-content: space-between;
		}
		.anuncio{
			flex-basis: calc(33.3% - 1rem);
			border: 1px solid #B5B5B5;
			background-color: #F5F5F5;
		}

		.contenido-anuncio{
			padding: 2rem;
		}

		.contenido-anuncio h3, 
		.contenido-anuncio p{
			margin: 0;
		}

		.precio{
			color: #71B100;
			font-weight: 700;
		}

		.iconos-caracteristicas{
			list-style: none;
			padding: 0;
			display: flex;
			justify-content: space-evenly;
		}

		.iconos-caracteristicas li{
			/* flex: 1; */
			display: flex;
		}

		.iconos-caracteristicas li img{
			margin-right: 2rem;
		}

		.ver-todas{
			display: flex;
			justify-content: flex-end;
		}
		≡

### Sección 11 Introduccion a CSS - Finalizando la Pagina Principal del Proyecto Bienes Raices

#### Video 046 Primeros pasos en el CSS del Blog.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<div class="seccion-inferior contenedor">
			<section class="blog">
				<h3>Nuestro blog</h3>
		
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog1.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<h4>Terraza en el techo de tu casa</h4>
						<p>Escrito el: <em>20/10/2019</em> por: <em>Admin</em></p>
						<p>Consejos para construir una terraza en el techo de tu casa, con los mejores materiales y ahorrando dinero</p>
					</div>
				</article>
				
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog2.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<h4>Guía para la decoración de tu hogar</h4>
						<p>Escrito el: <em>20/10/2019</em> por: <em>Admin</em></p>
						<p>Maximiza el espacio en tu hogar con esta guía, aprende a combinar muebles y colores para darle vida a tu espacio</p>
					</div>
				</article>
			</section>
		
			<section class="testimoniales">
				<h3>Testimoniales</h3>
				<blockquote>
					El personal se comportó de una excelente forma, muy buena atención y la cas que me ofrecieron cumple con tadas mis expectativas.
				</blockquote>
		
				<p>- Pedro Bazó</p>
			</section>
		</div>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡

		/** Sección inferior **/
		.seccion-inferior{
			display: flex;
			justify-content: space-between;
		}

		.seccion-inferior .blog{
			flex-basis: 60%;
		}

		.seccion-inferior .testimoniales{
			flex-basis: calc(40% - 2rem);
		}

		.entrada-blog{
			display: flex;
			justify-content: space-between;
			margin-bottom: 2rem;
		}

		.entrada-blog:last-of-type{
			margin-bottom: 0;
		}

		.entrada-blog .imagen{
			flex-basis: 40%;
		}

		.entrada-blog .texto-entrada{
			flex-basis: calc(60% - 3rem);
		}

		.texto-entrada h4{
			margin: 0;
			line-height:  1.4;
		}

#### Video 047 Finalizando el Blog.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<div class="seccion-inferior contenedor seccion">
			<section class="blog">
				<h3 class="centrar-texto fw-300">Nuestro blog</h3>
		
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog1.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="#">
							<h4>Terraza en el techo de tu casa</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Consejos para construir una terraza en el techo de tu casa, con los mejores materiales y ahorrando dinero</p>
					</div>
				</article>
				
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog2.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="#">
							<h4>Guía para la decoración de tu hogar</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Maximiza el espacio en tu hogar con esta guía, aprende a combinar muebles y colores para darle vida a tu espacio</p>
					</div>
				</article>
			</section>
		
			<section class="testimoniales">
				<h3 class="centrar-texto fw-300">Testimoniales</h3>

				<blockquote>
					El personal se comportó de una excelente forma, muy buena atención y la cas que me ofrecieron cumple con tadas mis expectativas.
				</blockquote>
		
				<p>- Pedro Bazó</p>
			</section>
		</div>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Sección inferior **/
		.seccion-inferior{
			display: flex;
			justify-content: space-between;
		}

		.seccion-inferior .blog{
			flex-basis: 60%;
		}

		.seccion-inferior .testimoniales{
			flex-basis: calc(40% - 2rem);
		}

		.entrada-blog{
			display: flex;
			justify-content: space-between;
			margin-bottom: 2rem;
		}

		.entrada-blog:last-of-type{
			margin-bottom: 0;
		}

		.entrada-blog .imagen{
			flex-basis: 40%;
		}

		.entrada-blog .texto-entrada{
			flex-basis: calc(60% - 3rem);
		}

		.texto-entrada a{
			color: #000000;
			text-decoration: none;
		}

		.texto-entrada h4{
			margin: 0;
			line-height:  1.4;
		}

		.texto-entrada h4::after{
			content: '';
			display: block;
			width: 15rem;
			height: .5rem;
			background-color: #71B100;
			margin-top: 10px;
		}

		.texto-entrada span{
			color: #E08709;
		}

#### Video 048 Estilos al Testimonial.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<section class="testimoniales">
			<h3 class="centrar-texto fw-300">Testimoniales</h3>
			<div class="testimonial">
				<blockquote>
					El personal se comportó de una excelente forma, muy buena atención y la cas que me ofrecieron cumple con tadas mis expectativas.
				</blockquote>
		
				<p>- Pedro Bazó</p>
			</div>
		</section>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Testimoniales **/
		.testimonial{
			background-color: #71B100;
			font-size: 2.4rem;
			padding: 2rem;
			color: #ffffff;
			border-radius: 2rem;
		}

		.testimonial p{
			text-align: right;
		}

		.testimonial blockquote::before{
			content: '';
			background-image: url(../img/comilla.svg);
			width: 4rem;
			height: 4rem;
			/* display: block; */
			position: absolute;
			left: -2rem;
		}

		.testimonial blockquote{
			position: relative;
			padding-left: 5rem;
			font-weight: 300;
		}

#### Video 049 Finalizando la pagina Principal.mp4
1. Modificar el archivo **index.html**:
	>

		≡
		<footer class="site-footer seccion">
			<div class="contenedor contenedro-footer">
				<nav class="navegacion">
					<a href="nosotros.html">Nosotros</a>
					<a href="anuncios.html">Anuncios</a>
					<a href="blog.html">Blog</a>
					<a href="contacto.html">Contacto</a>
				</nav>      
		
				<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
			</div>
		</footer>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Footer **/
		.site-footer{
			background-color: #333333;
			margin: 0;
		}

		.contenedro-footer{
			padding: 3rem 0;
			display: flex;
			justify-content: space-between;
		}

		.copyright{
			margin: 0;
			color: #ffffff;
		}

### Sección 12 HTML y CSS - Creando el Proyecto de Bienes Raices - Pagina de Nosotros

#### Video 050 Agregando el HTML de la pagina de Nosotros.mp4
###### https://es.lipsum.com
1. Modificar el archivo **nosotros.html**:
	>

		<!DOCTYPE html>
		<html lang="es">
		<head>
			<meta charset="utf-8" />
			<meta name="viewport" content="width=divice-width, initial-sacle=1.0">
			<meta http-equiv="X-UA-Compatible" content="ie=edge">
			<title>Bienes Raices</title>
			<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900">
			<link rel="stylesheet" href="css/normalize.css">
			<link rel="stylesheet" href="css/styles.css">
		</head>
		<body>
			<header class="site-header">
				<div class="contenedor contenido-header">
					<div class="barra">
						<a href="/">
							<img src="img/logo.svg" alt="Logotipo de Bienes Raices">
						</a>

						<nav class="navegacion">
							<a href="nosotros.html">Nosotros</a>
							<a href="anuncios.html">Anuncios</a>
							<a href="blog.html">Blog</a>
							<a href="contacto.html">Contacto</a>
						</nav>
					</div>
				</div> <!-- contenedor -->
			</header>

			<main class="contenedor">
				<h1 class="fw-300 centrar-texto">Conoce sobre nosotros</h1>
				<div class="contenido-nosotros">
					<div class="imagen">
						<img src="img/nosotros.jpg" alt="Imagen sobre nosotros">
					</div>
					<div class="texto-nosotros">
						<blockquote>25 años de experiencia</blockquote>
						<p>
							Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur et felis eget elit laoreet pulvinar. Etiam turpis dui, imperdiet eget vestibulum vel, ultricies eu risus. Vestibulum quis nisl non turpis mollis semper nec vel metus. Fusce pretium ultricies dui at cursus. Donec molestie molestie ligula vel efficitur. In sodales, libero id dictum tempor, est ex pharetra tortor, eu sagittis diam mi vel nisl. Praesent quis tristique neque. Praesent dapibus rutrum sodales.
						</p>
						<p>
							Duis sollicitudin scelerisque commodo. Aenean facilisis, sapien in iaculis semper, dolor enim scelerisque risus, vitae feugiat dui enim eu eros. Mauris sed arcu eros. Vestibulum non sodales ex, sit amet lobortis mauris. Curabitur eleifend nec justo at cursus. Fusce id semper nibh, vitae cursus ante. Integer eget interdum erat, id gravida lorem. Donec bibendum felis id nulla egestas, ac blandit erat pulvinar. Aliquam porta, leo id vulputate fermentum, mauris est lobortis nisl, sed efficitur leo odio vitae ex. Nulla nec ipsum hendrerit, finibus odio quis, rutrum orci. Vestibulum vel mi diam.
						</p>
					</div>
				</div>
			</main>

			<section class="contenedor seccion">    
				<h2 class="fw-300 centrar-texto">Más sobre nosotros</h2>

				<div class="iconos-nosotros">
					<div class="icono">
						<img src="img/icono1.svg" alt="Icono seguridad">
						<h3>Seguridad</h3>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</div>
			
					<div class="icono">
						<img src="img/icono2.svg" alt="Icono mejor precio">
						<h3>El mejor precio</h3>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</div>
			
					<div class="icono">
						<img src="img/icono3.svg" alt="Icono a tiempo">
						<h3>A tiempo</h3>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</div>
				</div>
			</section>

			<footer class="site-footer seccion">
				<div class="contenedor contenedro-footer">
					<nav class="navegacion">
						<a href="nosotros.html">Nosotros</a>
						<a href="anuncios.html">Anuncios</a>
						<a href="blog.html">Blog</a>
						<a href="contacto.html">Contacto</a>
					</nav>      
			
					<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
				</div>
			</footer>
		</body>
		</html>

#### Video 051 CSS A la pagina de Nosotros.mp4
1. Modificar el archivo **nosotros.html**:
	>

		≡
		<!DOCTYPE html>
		<html lang="es">
		<head>
			<meta charset="utf-8" />
			<meta name="viewport" content="width=divice-width, initial-sacle=1.0">
			<meta http-equiv="X-UA-Compatible" content="ie=edge">
			<title>Bienes Raices</title>
			<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900">
			<link rel="stylesheet" href="css/normalize.css">
			<link rel="stylesheet" href="css/styles.css">
		</head>
		<body>
			<header class="site-header">
				<div class="contenedor contenido-header">
					<div class="barra">
						<a href="/">
							<img src="img/logo.svg" alt="Logotipo de Bienes Raices">
						</a>

						<nav class="navegacion">
							<a href="nosotros.html">Nosotros</a>
							<a href="anuncios.html">Anuncios</a>
							<a href="blog.html">Blog</a>
							<a href="contacto.html">Contacto</a>
						</nav>
					</div>
				</div> <!-- contenedor -->
			</header>

			<main class="contenedor">
				<h1 class="fw-300 centrar-texto">Conoce sobre nosotros</h1>
				<div class="contenido-nosotros">
					<div class="imagen">
						<img src="img/nosotros.jpg" alt="Imagen sobre nosotros">
					</div>
					<div class="texto-nosotros">
						<blockquote>25 años de experiencia</blockquote>
						<p>
							Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur et felis eget elit laoreet pulvinar. Etiam turpis dui, imperdiet eget vestibulum vel, ultricies eu risus. Vestibulum quis nisl non turpis mollis semper nec vel metus. Fusce pretium ultricies dui at cursus. Donec molestie molestie ligula vel efficitur. In sodales, libero id dictum tempor, est ex pharetra tortor, eu sagittis diam mi vel nisl. Praesent quis tristique neque. Praesent dapibus rutrum sodales.
						</p>
						<p>
							Duis sollicitudin scelerisque commodo. Aenean facilisis, sapien in iaculis semper, dolor enim scelerisque risus, vitae feugiat dui enim eu eros. Mauris sed arcu eros. Vestibulum non sodales ex, sit amet lobortis mauris. Curabitur eleifend nec justo at cursus. Fusce id semper nibh, vitae cursus ante. Integer eget interdum erat, id gravida lorem. Donec bibendum felis id nulla egestas, ac blandit erat pulvinar. Aliquam porta, leo id vulputate fermentum, mauris est lobortis nisl, sed efficitur leo odio vitae ex. Nulla nec ipsum hendrerit, finibus odio quis, rutrum orci. Vestibulum vel mi diam.
						</p>
					</div>
				</div>
			</main>

			<section class="contenedor seccion">    
				<h2 class="fw-300 centrar-texto">Más sobre nosotros</h2>

				<div class="iconos-nosotros">
					<div class="icono">
						<img src="img/icono1.svg" alt="Icono seguridad">
						<h3>Seguridad</h3>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</div>
			
					<div class="icono">
						<img src="img/icono2.svg" alt="Icono mejor precio">
						<h3>El mejor precio</h3>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</div>
			
					<div class="icono">
						<img src="img/icono3.svg" alt="Icono a tiempo">
						<h3>A tiempo</h3>
						<p>Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
						proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					</div>
				</div>
			</section>

			<footer class="site-footer seccion">
				<div class="contenedor contenedro-footer">
					<nav class="navegacion">
						<a href="nosotros.html">Nosotros</a>
						<a href="anuncios.html">Anuncios</a>
						<a href="blog.html">Blog</a>
						<a href="contacto.html">Contacto</a>
					</nav>      
			
					<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
				</div>
			</footer>
		</body>
		</html>
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡

		/* Header */
		.site-header{
			background-color: #333333;
			padding: 1rem 0 3rem 0;
		}

		.site-header.inicio{
			background-image: url(../img/header.jpg);
			background-position: center center;
			background-size: cover; 
			height: 100vh;
			min-height: 60rem;
		}

		.contenido-header{
			height: 100%;
			display: flex;
			flex-direction: column;
			justify-content: space-between;
		}

		.contenido-header h1{
			color: #ffffff;
			padding-bottom: 2rem;
			max-width: 60rem;
			line-height: 2;
		}

		.barra{
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding-top: 3rem;
		}

		≡

		/** INTERNAS **/
		.contenido-nosotros{
			display: grid;
			grid-template-columns: repeat(2, 1fr);
			grid-column-gap: 2rem;
		}

		.texto-nosotros blockquote{
			font-weight: 900;
			font-size: 2rem;
			margin: 0;
			padding: 1rem 0 0 3rem 0;
		}

### Sección 13 HTML y CSS - Creando el Proyecto de Bienes Raices - Pagina de Propiedades

#### Video 052 Creando el HTML y ajustando el CSS.mp4
1. Crear el archivo **anuncios.html**:
	>

		<!DOCTYPE html>
		<html lang="es">
		<head>
			<meta charset="utf-8" />
			<meta name="viewport" content="width=divice-width, initial-sacle=1.0">
			<meta http-equiv="X-UA-Compatible" content="ie=edge">
			<title>Bienes Raices</title>
			<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900">
			<link rel="stylesheet" href="css/normalize.css">
			<link rel="stylesheet" href="css/styles.css">
		</head>
		<body>
			<header class="site-header">
				<div class="contenedor contenido-header">
					<div class="barra">
						<a href="/">
							<img src="img/logo.svg" alt="Logotipo de Bienes Raices">
						</a>

						<nav class="navegacion">
							<a href="nosotros.html">Nosotros</a>
							<a href="anuncios.html">Anuncios</a>
							<a href="blog.html">Blog</a>
							<a href="contacto.html">Contacto</a>
						</nav>
					</div>
				</div> <!-- contenedor -->
			</header>

			<main class="seccion contenedor">
				<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

				<div class="contenedor-anuncios">
					<div class="anuncio">
						<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
						<div class="contenido-anuncio">
							<h3>Casa de lujo en el lago</h3>
							<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
							<p class="precio">$3.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
						<div class="contenido-anuncio">
							<h3>Casa terminados de lujo</h3>
							<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
							<p class="precio">$2.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
						<div class="contenido-anuncio">
							<h3>Casa con alberca</h3>
							<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
							<p class="precio">$3.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->

					<div class="anuncio">
						<img src="img/anuncio4.jpg" alt="Anuncio casa de lujo">
						<div class="contenido-anuncio">
							<h3>Casa fuera de la ciudad</h3>
							<p>Casa con alberca y acabados de lujo fuera de la ciudad, excelente oportunidad</p>
							<p class="precio">$2.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>5</p>
								</li>
							</ul>
							<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio5.jpg" alt="Anuncio casa frente al bosque">
						<div class="contenido-anuncio">
							<h3>Casa frente al bosque</h3>
							<p>Casa con alberca y frente al bosque, excelente oportunidad</p>
							<p class="precio">$3.500.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio6.jpg" alt="Anuncio casa con alberca">
						<div class="contenido-anuncio">
							<h3>Casa con alberca</h3>
							<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
							<p class="precio">$4.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>5</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>7</p>
								</li>
							</ul>
							<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
				</div>
			</main>

			<footer class="site-footer seccion">
				<div class="contenedor contenedro-footer">
					<nav class="navegacion">
						<a href="nosotros.html">Nosotros</a>
						<a href="anuncios.html">Anuncios</a>
						<a href="blog.html">Blog</a>
						<a href="contacto.html">Contacto</a>
					</nav>      
			
					<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
				</div>
			</footer>
		</body>
		</html>
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Anuncios **/
		.contenedor-anuncios{
			display: flex;
			justify-content: space-between;
			flex-wrap: wrap;
		}
		.anuncio{
			flex: 0 0 calc(33.3% - 1rem);
			border: 1px solid #B5B5B5;
			background-color: #F5F5F5;
			margin-bottom: 2rem;
		}
		≡

#### Video 053 Creando la Pagina para Mostrar Una Propiedad.mp4
1. Modificar el archivo **anuncios.html**:
	>

		≡
		<main class="seccion contenedor">
			<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

			<div class="contenedor-anuncios">
				<div class="anuncio">
					<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
					<div class="contenido-anuncio">
						<h3>Casa de lujo en el lago</h3>
						<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
						<p class="precio">$3.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div> <!-- contenido anuncio -->
				</div> <!-- anuncio -->
		
				<div class="anuncio">
					<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa terminados de lujo</h3>
						<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
						<p class="precio">$2.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div> <!-- contenido anuncio -->
				</div> <!-- anuncio -->
		
				<div class="anuncio">
					<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p class="precio">$3.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div> <!-- contenido anuncio -->
				</div> <!-- anuncio -->

				<div class="anuncio">
					<img src="img/anuncio4.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa fuera de la ciudad</h3>
						<p>Casa con alberca y acabados de lujo fuera de la ciudad, excelente oportunidad</p>
						<p class="precio">$2.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>2</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>2</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>5</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div> <!-- contenido anuncio -->
				</div> <!-- anuncio -->
		
				<div class="anuncio">
					<img src="img/anuncio5.jpg" alt="Anuncio casa frente al bosque">
					<div class="contenido-anuncio">
						<h3>Casa frente al bosque</h3>
						<p>Casa con alberca y frente al bosque, excelente oportunidad</p>
						<p class="precio">$3.500.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>2</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div> <!-- contenido anuncio -->
				</div> <!-- anuncio -->
		
				<div class="anuncio">
					<img src="img/anuncio6.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p class="precio">$4.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>2</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>5</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>7</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div> <!-- contenido anuncio -->
				</div> <!-- anuncio -->
			</div>
		</main>
		≡
1. Crear el archivo **anuncio.html**:
	>

		<!DOCTYPE html>
		<html lang="es">
		<head>
			<meta charset="utf-8" />
			<meta name="viewport" content="width=divice-width, initial-sacle=1.0">
			<meta http-equiv="X-UA-Compatible" content="ie=edge">
			<title>Bienes Raices</title>
			<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900">
			<link rel="stylesheet" href="css/normalize.css">
			<link rel="stylesheet" href="css/styles.css">
		</head>
		<body>
			<header class="site-header">
				<div class="contenedor contenido-header">
					<div class="barra">
						<a href="/">
							<img src="img/logo.svg" alt="Logotipo de Bienes Raices">
						</a>

						<nav class="navegacion">
							<a href="nosotros.html">Nosotros</a>
							<a href="anuncios.html">Anuncios</a>
							<a href="blog.html">Blog</a>
							<a href="contacto.html">Contacto</a>
						</nav>
					</div>
				</div> <!-- contenedor -->
			</header>

			<main class="seccion contenedor">
				<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

				<div class="contenedor-anuncios">
					<div class="anuncio">
						<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
						<div class="contenido-anuncio">
							<h3>Casa de lujo en el lago</h3>
							<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
							<p class="precio">$3.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
						<div class="contenido-anuncio">
							<h3>Casa terminados de lujo</h3>
							<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
							<p class="precio">$2.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
						<div class="contenido-anuncio">
							<h3>Casa con alberca</h3>
							<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
							<p class="precio">$3.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->

					<div class="anuncio">
						<img src="img/anuncio4.jpg" alt="Anuncio casa de lujo">
						<div class="contenido-anuncio">
							<h3>Casa fuera de la ciudad</h3>
							<p>Casa con alberca y acabados de lujo fuera de la ciudad, excelente oportunidad</p>
							<p class="precio">$2.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>5</p>
								</li>
							</ul>
							<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio5.jpg" alt="Anuncio casa frente al bosque">
						<div class="contenido-anuncio">
							<h3>Casa frente al bosque</h3>
							<p>Casa con alberca y frente al bosque, excelente oportunidad</p>
							<p class="precio">$3.500.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>3</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>4</p>
								</li>
							</ul>
							<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
			
					<div class="anuncio">
						<img src="img/anuncio6.jpg" alt="Anuncio casa con alberca">
						<div class="contenido-anuncio">
							<h3>Casa con alberca</h3>
							<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
							<p class="precio">$4.000.000,00</p>
							<ul class="iconos-caracteristicas">
								<li>
									<img src="img/icono_wc.svg" alt="icono wc">
									<p>2</p>
								</li>
								<li>
									<img src="img/icono_estacionamiento.svg" alt="icono autos">
									<p>5</p>
								</li>
								<li>
									<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
									<p>7</p>
								</li>
							</ul>
							<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
						</div> <!-- contenido anuncio -->
					</div> <!-- anuncio -->
				</div>
			</main>

			<footer class="site-footer seccion">
				<div class="contenedor contenedro-footer">
					<nav class="navegacion">
						<a href="nosotros.html">Nosotros</a>
						<a href="anuncios.html">Anuncios</a>
						<a href="blog.html">Blog</a>
						<a href="contacto.html">Contacto</a>
					</nav>      
			
					<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
				</div>
			</footer>
		</body>
		</html>
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		/** Utilidades **/
		.seccion{
			margin-top: 2rem;
			margin-bottom: 2rem;
		}

		.fw-300{
			font-weight: 300;
		}

		.centrar-texto{
			text-align: center;
		}

		.d-block{
			display: block!important;
		}

		.contenido-centrado{
			max-width: 800px;
		}

		≡

		.iconos-caracteristicas{
			list-style: none;
			padding: 0;
			display: flex;
			justify-content: space-evenly;
			flex: 1;
			max-width: 500px;
		}

		≡

		/** INTERNAS **/
		/** Nosotros **/
		.contenido-nosotros{
			display: grid;
			grid-template-columns: repeat(2, 1fr);
			grid-column-gap: 2rem;
		}

		.texto-nosotros blockquote{
			font-weight: 900;
			font-size: 2rem;
			margin: 0;
			padding: 1rem 0 0 3rem 0;
		}

		/** Anuncios **/
		.resumen-propiedad{
			display: flex;
			justify-content: space-between;
			align-items: center;
		}		

### Sección 14 HTML y CSS - Creando el Proyecto de Bienes Raices - Pagina de Blog

#### Video 054 Creando la pagina de Blog.mp4
1. Crear el archivo **blog.html**:
	>

		<!DOCTYPE html>
		<html lang="es">
		<head>
			<meta charset="utf-8" />
			<meta name="viewport" content="width=divice-width, initial-sacle=1.0">
			<meta http-equiv="X-UA-Compatible" content="ie=edge">
			<title>Bienes Raices</title>
			<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900">
			<link rel="stylesheet" href="css/normalize.css">
			<link rel="stylesheet" href="css/styles.css">
		</head>
		<body>
			<header class="site-header">
				<div class="contenedor contenido-header">
					<div class="barra">
						<a href="/">
							<img src="img/logo.svg" alt="Logotipo de Bienes Raices">
						</a>

						<nav class="navegacion">
							<a href="nosotros.html">Nosotros</a>
							<a href="anuncios.html">Anuncios</a>
							<a href="blog.html">Blog</a>
							<a href="contacto.html">Contacto</a>
						</nav>
					</div>
				</div> <!-- contenedor -->
			</header>

			<main class="contenedor seccion contenido-centrado">
				<h1 class="fw-300 centrar-texto">Nuestro blog</h1>

				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog1.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="entrada.html">
							<h4>Terraza en el techo de tu casa</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Consejos para construir una terraza en el techo de tu casa, con los mejores materiales y ahorrando dinero</p>
					</div>
				</article>
				
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog2.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="entrada.html">
							<h4>Construye una alberca en tu hogar</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Maximiza el espacio en tu hogar con esta guía, aprende a combinar muebles y colores para darle vida a tu espacio</p>
					</div>
				</article>
				
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog3.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="entrada.html">
							<h4>Guía para la decoración de tu hogar</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Maximiza el espacio en tu hogar con esta guía, aprende a combinar muebles y colores para darle vida a tu espacio</p>
					</div>
				</article>
				
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog4.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="entrada.html">
							<h4>Guía para la decoración de tu habitación</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Maximiza el espacio en tu hogar con esta guía, aprende a combinar muebles y colores para darle vida a tu espacio</p>
					</div>
				</article>
			</main>

			<footer class="site-footer seccion">
				<div class="contenedor contenedro-footer">
					<nav class="navegacion">
						<a href="nosotros.html">Nosotros</a>
						<a href="anuncios.html">Anuncios</a>
						<a href="blog.html">Blog</a>
						<a href="contacto.html">Contacto</a>
					</nav>      
			
					<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
				</div>
			</footer>
		</body>
		</html>
1. Crear el archivo **entrada.html**:
	>

		<!DOCTYPE html>
		<html lang="es">
		<head>
			<meta charset="utf-8" />
			<meta name="viewport" content="width=divice-width, initial-sacle=1.0">
			<meta http-equiv="X-UA-Compatible" content="ie=edge">
			<title>Bienes Raices</title>
			<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:300,400,700,900">
			<link rel="stylesheet" href="css/normalize.css">
			<link rel="stylesheet" href="css/styles.css">
		</head>
		<body>
			<header class="site-header">
				<div class="contenedor contenido-header">
					<div class="barra">
						<a href="/">
							<img src="img/logo.svg" alt="Logotipo de Bienes Raices">
						</a>

						<nav class="navegacion">
							<a href="nosotros.html">Nosotros</a>
							<a href="anuncios.html">Anuncios</a>
							<a href="blog.html">Blog</a>
							<a href="contacto.html">Contacto</a>
						</nav>
					</div>
				</div> <!-- contenedor -->
			</header>

			<h1 class="fw-300 centrar-texto">Consejos para tener una alberca en tu casa sin gastar demasiado</h1>
			<img src="img/destacada2.jpg" alt="Imagen principal">

			<main class="contenedor seccion contenido-centrado texto-entrada">
				<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
				<p>
					Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dignissim dui et metus vulputate semper in vitae libero. Curabitur et fermentum odio. Nam a est elementum, commodo sem vulputate, commodo elit. Nullam iaculis faucibus congue. Nulla efficitur lacus non pellentesque porttitor. Phasellus pellentesque a metus vel varius. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Fusce vestibulum neque quis eros faucibus ullamcorper. Curabitur in interdum ligula, quis vestibulum justo. Nulla congue ante et metus elementum, nec tempus sem interdum. Duis ut ex sit amet diam pellentesque facilisis. Maecenas nibh est, blandit eu condimentum et, molestie vitae dolor. Ut commodo egestas sollicitudin. Integer augue orci, facilisis at pretium a, aliquet pellentesque enim.
				<p>
				</p>
					Aliquam mollis dui at pellentesque congue. Nam faucibus dolor in dolor posuere, et suscipit purus interdum. Integer neque metus, luctus a eleifend ut, mattis eget turpis. Donec in varius urna. Integer sapien sem, sollicitudin eget tellus non, consequat lobortis libero. Pellentesque efficitur nisl a purus placerat, id ullamcorper enim faucibus. Proin lorem felis, luctus ac erat vel, tristique suscipit urna. Aenean consequat sem elit, at luctus magna scelerisque a.
				</p>
				<p>
					Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dignissim dui et metus vulputate semper in vitae libero. Curabitur et fermentum odio. Nam a est elementum, commodo sem vulputate, commodo elit. Nullam iaculis faucibus congue. Nulla efficitur lacus non pellentesque porttitor. Phasellus pellentesque a metus vel varius. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Fusce vestibulum neque quis eros faucibus ullamcorper. Curabitur in interdum ligula, quis vestibulum justo. Nulla congue ante et metus elementum, nec tempus sem interdum. Duis ut ex sit amet diam pellentesque facilisis. Maecenas nibh est, blandit eu condimentum et, molestie vitae dolor. Ut commodo egestas sollicitudin. Integer augue orci, facilisis at pretium a, aliquet pellentesque enim.
				<p>
				</p>
					Aliquam mollis dui at pellentesque congue. Nam faucibus dolor in dolor posuere, et suscipit purus interdum. Integer neque metus, luctus a eleifend ut, mattis eget turpis. Donec in varius urna. Integer sapien sem, sollicitudin eget tellus non, consequat lobortis libero. Pellentesque efficitur nisl a purus placerat, id ullamcorper enim faucibus. Proin lorem felis, luctus ac erat vel, tristique suscipit urna. Aenean consequat sem elit, at luctus magna scelerisque a.
				</p>
			</main>

			<footer class="site-footer seccion">
				<div class="contenedor contenedro-footer">
					<nav class="navegacion">
						<a href="nosotros.html">Nosotros</a>
						<a href="anuncios.html">Anuncios</a>
						<a href="blog.html">Blog</a>
						<a href="contacto.html">Contacto</a>
					</nav>      
			
					<p class="copyright">Todos los derechos reservados 2021 &copy;</p>
				</div>
			</footer>
		</body>
		</html>
1. Modificar el archivo **index.html**:
	>

		≡
		<main class="seccion contenedor">
			<h2 class="fw-300 centrar-texto">Casas y depas en venta</h2>

			<div class="contenedor-anuncios">
				<div class="anuncio">
					<img src="img/anuncio1.jpg" alt="Anuncio casa en el lago">
					<div class="contenido-anuncio">
						<h3>Casa de lujo en el lago</h3>
						<p>Casa en el lago con excelente vista, acabado de lujo a un excelente precio</p>
						<p class="precio">$3.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio2.jpg" alt="Anuncio casa de lujo">
					<div class="contenido-anuncio">
						<h3>Casa terminados de lujo</h3>
						<p>Casa con diseño moderno, así como tecnología inteligente y amoblada</p>
						<p class="precio">$2.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="anuncio.html" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
		
				<div class="anuncio">
					<img src="img/anuncio3.jpg" alt="Anuncio casa con alberca">
					<div class="contenido-anuncio">
						<h3>Casa con alberca</h3>
						<p>Casa con alberca y acabados de lujo en la ciudad, excelente oportunidad</p>
						<p class="precio">$3.000.000,00</p>
						<ul class="iconos-caracteristicas">
							<li>
								<img src="img/icono_wc.svg" alt="icono wc">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_estacionamiento.svg" alt="icono autos">
								<p>3</p>
							</li>
							<li>
								<img src="img/icono_dormitorio.svg" alt="icono habitaciones">
								<p>4</p>
							</li>
						</ul>
						<a href="#" class="boton boton-amarillo d-block">Ver propiedad</a>
					</div>
				</div>
			</div>

			<div class="ver-todas">
				<a href="anuncios.html" class="boton boton-verde">Ver todas</a>
			</div>
		</main>
		≡
		<div class="seccion-inferior contenedor seccion">
			<section class="blog">
				<h3 class="centrar-texto fw-300">Nuestro blog</h3>
		
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog1.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="entrada.html">
							<h4>Terraza en el techo de tu casa</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Consejos para construir una terraza en el techo de tu casa, con los mejores materiales y ahorrando dinero</p>
					</div>
				</article>
				
				<article class="entrada-blog">
					<div class="imagen">
						<img src="img/blog2.jpg" alt="Entrada de blog">
					</div>
					<div class="texto-entrada">
						<a href="entrada.html">
							<h4>Guía para la decoración de tu hogar</h4>
						</a>
						<p>Escrito el: <span>20/10/2019</span> por: <span>Admin</span></p>
						<p>Maximiza el espacio en tu hogar con esta guía, aprende a combinar muebles y colores para darle vida a tu espacio</p>
					</div>
				</article>
			</section>
		
			<section class="testimoniales">
				<h3 class="centrar-texto fw-300">Testimoniales</h3>
				<div class="testimonial">
					<blockquote>
						El personal se comportó de una excelente forma, muy buena atención y la cas que me ofrecieron cumple con tadas mis expectativas.
					</blockquote>
			
					<p>- Pedro Bazó</p>
				</div>
			</section>
		</div>
		≡

### Sección 15 HTML y CSS - Creando el Proyecto de Bienes Raices - Pagina de Contacto

#### Video 055 Creando la Pagina de Contacto y Formularios Textos y Labels.mp4
1. Crear el archivo **contacto.html**:
	>

		≡
		***
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		***
		≡





#### Video ...
1. Modificar el archivo **contacto.html**:
	>

		≡
		***
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		***
		≡

#### Video ...
1. Modificar el archivo **contacto.html**:
	>

		≡
		***
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		***
		≡

#### Video ...
1. Modificar el archivo **contacto.html**:
	>

		≡
		***
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		***
		≡

#### Video ...
1. Modificar el archivo **contacto.html**:
	>

		≡
		***
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		***
		≡

#### Video ...
1. Modificar el archivo **contacto.html**:
	>

		≡
		***
		≡
1. Modificar archivo de estilo **css/styles.css**:
	>

		≡
		***
		≡



≡