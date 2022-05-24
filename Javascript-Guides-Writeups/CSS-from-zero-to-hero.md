



# CSS by Fz3r0

## Setup Inicial

- **Full HTML Fz3r0 Jurassic Page!**

## Directorios y Archivos en el Server:  

### Directorio "root" principal: `/`

- ![image](https://user-images.githubusercontent.com/94720207/170094834-5e5a8430-9afd-4f42-bcce-b78d42c20a69.png)

### Directorio "images": `/images`

- ![image](https://user-images.githubusercontent.com/94720207/170095055-e33e59b8-daf1-43dc-879e-f21440aa51e2.png)

### Directorio "other_pages": `/other_pages`

- ![image](https://user-images.githubusercontent.com/94720207/170095288-cfd3f10d-0fa9-42f4-b3b5-30084a0aa86c.png)

## Semántica HTML
 
- **Idea aproximada de la semántica HTML que llevará la página:**

- ![image](https://user-images.githubusercontent.com/94720207/169996597-cde55d9f-4834-440d-8337-d57135dd190a.png)
 
## Index: `/index.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1)</h1>
    			<p>
    				Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1.<br>
    				Atentamente: Párrafo1 Section1		  
    			</p>
    			<p>
    				Párrafo2 Section1 Párrafo2 Section1 Párrafo2 Section1 Párrafo2 Section1.
    			</p>
    			<p>
    			<a href="https://www.youtube.com/watch?v=u6ckRTxyNyA"><img src="images/explorer.jpg" alt="alt: explorer" title="title: mouse hover"></a><br>
    			Párrafo3: Foto + Pie de foto de la Explorer de Jurassic Park
    			</p>
		</section>    
		<section>	
    		        <h2>Titulo 2 (Section2)</h2>
    			<p>
    				Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2.   
    			</p>
    			<p>---------| Termina el "contenido central" de página |---------</p>
		</section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```

</details>
	
- ![image](https://user-images.githubusercontent.com/94720207/170096441-5686606f-2e71-4734-a5de-a1cfa7aa8023.png)

## Page 1: `other_pages/whoami.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>
	
```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): WHO AM I???</h1>
    			<p>
    				Párrafo1 Section1:<br>
    				I am: | Github: Fz3r0 | Twitter: Fz3r0_OPs 		  
    			</p>
    			<p>
    				Párrafo2 Section1<br>
    				Follow me!!!
    			</p>
    			<p>
    			<a href="https://github.com/Fz3r0"><img src="https://user-images.githubusercontent.com/94720207/165896925-bb6403fc-e3b3-480f-971b-874401e43708.gif" alt="alt: explorer" title="title: mouse hover"></a><br>
    			I am Fz3r0 and the Sun no longer rises...
    			</p>
		</section>    
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```
</details>

- ![image](https://user-images.githubusercontent.com/94720207/170097670-9ad06536-2001-4c95-830b-e0ce104b0f37.png)

## Page 2: `other_pages/dino_photos.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>	
	
```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): Fotos de Dinosaurios</h1>
    			<p>
    			<h3> Foto1: </h3>
    			<a href="https://github.com/Fz3r0"><img src="../images/welcome.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 1: welcome to jurassic park!!!
    			</p>
    			<h3> Foto2: </h3>
    			<a href="https://github.com/Fz3r0"><img src="../images/brachio.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 2: welcome to jurassic park!!!
    			</p>
    			<h3> Foto3: </h3>
    			<a href="https://github.com/Fz3r0"><img src="../images/malcom.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 3: welcome to jurassic park!!!
    			</p>
		</section>    
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```

</details>

- ![image](https://user-images.githubusercontent.com/94720207/170100663-a66ee217-d8a2-44a4-9f4d-c53b7d085425.png)

## Page3 `page3_jurassic_map.html`





## Page4 `page4_prices_table.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
	<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): Dino Store</h1>
	<p>
		<img src="../images/dino_store.jpg">
	</p>
	<p>	
		Section1 Párrafo1: Bienvenidos a la tienda de Jurassic Park!.<br> 
		(No tocar al velociraptor, gracias). Ahora inicia la tabla:
	</p>
    </section>
    <section>
	<table>
		<thead>
			<tr>
				<th>Header 1</th>
				<th>Header 2</th>
				<th>Header 3</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>*</td>
				<td>Niño</td>
				<td>Adulto</td>
			</tr>
			<tr>
				<td>Entrada</td>
				<td>$500</td>
				<td>$1000</td>
			</tr>
			<tr>
				<td>Refresco</td>
				<td>$20</td>
				<td>$20</td>
			</tr>
			<tr>
				<td>Gelatina</td>
				<td>$10</td>
				<td>$10</td>
			</tr>
			<tr>
				<td>Paseo en Jeep</td>
				<td>$150</td>
				<td>$200</td>
			</tr>
			<tr>
				<td>Electroshock</td>
				<td>Gratis!</td>
				<td>N/A</td>
			</tr>
		</tbody>
	</table>
    </section>
    <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>	

```

</details>
	
- ![image](https://user-images.githubusercontent.com/94720207/170102578-25e09864-362b-4441-82e2-91667fa8b351.png)

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>
	

























---





















### Intro

- CSS: Cascade Style Sheet
- Describe la presentación de un HTML, para un HTML múltiples estilos posibles.
- Es cascada, darle estilo por estilo...por estilo....

    - Funcionamiento de CSS 

- CSS funciona a base de `selectores`. 
- Los selectores pueden ser usados en 1 o varios `elementos`
- Cada elemento seleccionado tiene sus propias `propiedades`

```css
/* Esto es un comentario en CSS */
```

```css
/* Funcionamiento básico de CSS */

html {
    test-align: left;
    color: tomato;
}

*  {
   box-sizing: border-box;
}

.card {
    background-color: white;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.3);
```







    
    - Empezar con un `index.html` Que tal el: fz3r0 super special HTML!!!



### References

- https://bootswatch.com/
- 


