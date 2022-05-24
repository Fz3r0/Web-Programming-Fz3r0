
## HTML 5

---

```html
```

Comenzamos!

---

### Intro

- HTML
- CSS
- Javascript

---

### Sublime text

#### Themes and schemes

- `Ctrl+shift+P` `Install` Command 
    
    - `Install Package Control`
    - `Package Control: install package`  
    
        - Select and install package :D 
        
- Se usará `blackbrid` y `brogrammer` theme por ahora.  

---

### HTML

- HTML boxes:

    - ![image](https://user-images.githubusercontent.com/94720207/169904936-53681267-c6a7-429f-8dea-42d66a63c339.png)
    - ![developer-tools-680596380](https://user-images.githubusercontent.com/94720207/169905055-9acda36e-2c92-4299-a0d2-ac4f9cb0e10a.png)

---

### Antes que nada:

- Crear file en una carpeta nueva `fz3r0_compu_mundo`

- Dentro de la carpeta guardar `index.html`

    - ![image](https://user-images.githubusercontent.com/94720207/169905415-3544003d-239c-4b9b-9055-8a9c1966c68a.png)
    
- Nota: se recomienda ver extensiones!  

    - ![image](https://user-images.githubusercontent.com/94720207/169905695-7dcef43a-fe49-4e51-825d-68d2594f1ce1.png)
 
---

### Estructura Inicial HTML

- Comentar en HTML:

```html
<!--This is a comment. Comments are not displayed in the browser-->

<p>This is a paragraph.</p>
```
```html
<p>HTML from 0 to Hero in .html format! by Fz3r0 - En Espanglish.</p>
```

### Estructura Inicial HTML:

- Sintaxis:

    - Tags (Etiqueta)
    
        - `<etqiueta>` <---- empieza a crear un ebjeto
        - `</etqiueta>` <--- cierra ese objeto ebjeto	 

    - Las Tags contienen:
    
        - Atributos: Propiedades/características del objeto (e.g. color)

    - Los Atributos contienen:

        - Valores: Los atributos siempre tienen un valor       

```html
<etiqueta atributo="valor"> </etiqueta>

<boton color="rojo"> <boton> 

<boton color="rojo" tamaño="grande" borde="negro"> <boton> 
```

- **Tipos de Tags:**

```html
<br>        <----| 1. Dejar un espacio en linea:
```  

```html
<img>       <----| 2. Solo necesita uno
``` 

```html
<h1></h1>   <----| 3. Contiene algo dentro
``` 
- Ejemplo:

```html
<br>
<h1>

    Titulo: Fz3r0	
	
</h1> 
```

- **Basic HTML Structure:**

1. `<!DOCTYPE html>`

    - No se cierra, solo se deja al inicio
    - Indica que es la última versión de HTML
    - Siempre poner al incio

2. `<html>` `</html>`  
    
    - Adentro está TODA la página
    - Tanto lo que vemos como lo que NO vemos

        - `<body>` = Lo que podemos ver  
        - `<head>` = Lo que NO podemos ver

### Empty HTML structure:

```html
<!DOCTYPE html>
<html>
    <head>
	<title></title>
    </head>	
    <body>
	
    </body>
</html>
```

### Hello World
 
```html
<!DOCTYPE html>
<html>
    <head>
	<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
	<h1> Titulo que se ve con h1 (header1) </h1>
	<h2> (header2) I'm Fz3r0! </h2>	    
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169911577-4b90378a-6e47-4e2a-8e39-eb91819b831d.png)

---

### Concepto semántico HTML

- Poner todo de manera estructural en HTML y usar otro lenguaje como CSS para acomodar
- No es puede poner más de 1 `h1` **(es el index del titulo search optimity para crawlers)
- Es importante codificar todo de manera correcta en HTML, siempre siguiendo la misma estructura. 
- Usar tabulador para saber qué caja está dentro de otra (aunque no es necesario)

---

### Etiquetas básicas exto:

- Titulos `<h>`
- párrafo `<p>`
- negrita `<b>`
- Italica `<i>` 	
- Tachada `<strike>`	
	
```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>

		<h1> Titulo 1 (header1) </h1>
		<h2> Titulo 2 (header2) </h2>
		<h3> Titulo 3 (header3) </h3>
		<h4> Titulo 4 (header4) </h4>
		<h5> Titulo 5 (header5) </h5>
		<h6> Titulo 6 (header6) </h6>
		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat.
		</p>
    	<b>Negrita</b>
    	<i>italica</i>
    	<strike>tachada</strike>

    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169927142-398dd6c4-1f3d-4d39-b7e5-11929e6fe7ae.png)

---

### Links y tag `<a>`:

- Etqiuetas `<a></a>`

    -  Contiene atributos como
    
        - `href`  

- Tipos de Links

    - Internos (Local Host o dentro del servidonor)
    - Externos (otras URLs o direccionamiento NO local)  

- Externos:

    - Escribir "facebook.com" no funcionaría en un "href" sin usar el protocolo "html"

        -  `<a href="facebook.com">Click Aqui!</a>` incorrecto
        -  `<a href="https://www.facebook.com/">Click Aqui!</a>` correcto!   

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	<a href="https://www.facebook.com/">Click Aqui!</a>
    </body>
</html>
```

- Internos:

    - Se alojan dentor del servidor (por ejemplo para hacer links dentro de la misma página, como lo usa mark down también) 
    - Por ejemplo, si creamos una segunda página dentro del directorio que haga referencia:
       
	- ![image](https://user-images.githubusercontent.com/94720207/169917851-e8415342-2c4b-42d4-bc92-39d47a38f09a.png)
    
    - Como está dentro de la misma carpeta `root` solo es poner el nombre.
    - En caso contrario poner la ruta en el directorio: 
    
        - ![image](https://user-images.githubusercontent.com/94720207/169917481-f1eb8ee5-7131-4c6f-bfc8-582283299bfc.png)

    - Reglas:
        
	- **Mismo folder** > escribir solo el nombre del file: `page2.html` 
	- **Folder arriba** > escribir la ruta desde ubicación: `/root/page2.html` 
	- **Folder abajo** > el universal `../`
    
- Ejemplo, un loop entre página 2, página 3(otra carpeta) e Index:

- `index.html`:

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	<a href="page2.html">Click Aqui para ir a la Page2!</a>
    </body>
</html>
```

- `page2.html`:

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Page 2 !!!!</title>
    </head>	
    <body>
    	<a href="index.html">Click Aqui para volver al Index!</a>
    	<a href="/folder1/page3.html">Click Aqui para ir a página 3!</a>	    
    </body>
</html>
```

- `page3.html`:

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Page 3 !!!!</title>
    </head>	
    <body>
    	<a href="../index.html">Click Aqui para volver al Index!</a>
    	<a href="../page2.html">Click Aqui para ir a página 2!</a>	    
    </body>
</html>
```

---

### Links internos y externos

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	<h1>Titulo Principal De Página</h1>
    	<p>
    		Esto es un párrafo que estoy escribiendo en HTML, <b> esto es muy importante así que le puse negritas, </b> si quieres ir a youtube puedes dar <a href="http://www.youtube.com/">click en este link</a>.
    		<br>
    		Puse un "br" para dar un brinco y no seguir escribiendo en la misma linea del link de youtube...
    		<br>
    		<br>
    		<br>
    		Ahora puse varios para brincar más!
    		<br>
    		<br>
    		También puedes ir a un link interno de está página (servidor) haciendo click <a href="/folder1/page3.html">aquí merengues</a>, o también puedes ir a mingar a tu chadre. 
    		<br>
    		<br>
    		<br>
    		Si agrego más atributos como <b>target="_BLANK"</b>, puedo abrir el link en una nueva pestaña, solo <a href="http://www.youtube.com/" target="_BLANK">debes hacer click aquí!</a>
    		Gracias! 
    	</p>
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169919857-f3c79ebb-05a8-4e1f-9273-29889de44ddd.png)	

---

### Listas `<ul>` & `<li>`

- `<ul></ul>` listas desordenadas
- `<li></li>` listas ordenadas

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	
    	<h1>Listas del super</h1>
    		
    		<h3>Listas del super sin ordenar</h3>
    	   	<ul>
    	   		<li>zanahorias</li>
    	   		<li>harina</li>
    	   		<li>tortillas</li>
    	   		<li>agua</li>
    	   		<li>azúcar</li>
    	   	</ul>

    	<h1>Listas del super ordenadas con "ol"</h1>
    		
    		<h3>Listas del super ordenada</h3>
    	   	<ol>
    	   		<li>zanahorias</li>
    	   		<li>harina</li>
    	   		<li>tortillas</li>
    	   		<li>agua</li>
    	   		<li>azúcar</li>
    	   	</ol>	
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169920811-d0524a4f-0a10-4eea-807e-8821bba7771b.png)

---

### Multimedia Tags

- `<img>` 

- También hace referencia a local o externo:

    - ![image](https://user-images.githubusercontent.com/94720207/169921395-2421e260-4514-4388-b20e-fd96915ba4c9.png)

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	<h1>Imagen en HTML</h1>
    	<p>
    		Esta es una imágen en una carpeta local del servidor:
    		<img src="malcom.jpg">
    		<br>
    		<br>
    		Esta es una imágen desde Internet
    		<img src="https://vignette.wikia.nocookie.net/true-villains/images/6/68/2062092-dennis_nedry.jpg/revision/latest?cb=20170317171958">
    		<br>
    		<br>
    		Widht y Height modifica horrendamente las imágenes, larga historia que no explicaré aquí, pero mejor editarlas a mano, así que en caso de modificar tamaño usar solo heigh o %.
    		<br>
    		<br>
    		Además, recordar que con CSS se modifican todas esas cosas! HTML no es para que la página quede "bonita", es para estructurar
    		<br>
    		<img src="https://vignette.wikia.nocookie.net/true-villains/images/6/68/2062092-dennis_nedry.jpg/revision/latest?cb=20170317171958" height="300px" >
    		Welcome to <b>Jurassic Park</b>
    	</p>	
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169922320-b2a401de-3915-42e5-93eb-b5c837c21552.png)

### Audio y Video

- `<video>`
- `controls` atributos como controles (se deja vacío para dejar al explorador "decidir")

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	<h1>Video</h1>
    	<p>
    		<br>
    		Acá un videito sin controles todo chafa: (no se ve)
    		<br>
    		<video src="https://www.appsloveworld.com/wp-content/uploads/2018/10/640.mp4"> 
    		</video>
    		<br>
    		<br>
    		<br>
    		Acá uno con controles:
    		<br>	
    		<video src="https://www.appsloveworld.com/wp-content/uploads/2018/10/640.mp4" controls="">
    		</video>   			
    		<br>
    		<br>
    		<br>
    		Acá versión audio, así es, directo desde el video ;)
    		<br>
    		<audio src="https://www.appsloveworld.com/wp-content/uploads/2018/10/640.mp4" controls="">	
    	    <br>
  			</audio>   			
    	</p>	
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169925237-b16c1bc3-0ef7-4250-9e8f-0c58567f86ea.png)

---

### div

- Realmente el uso real se ve en CSS, pero vaya que se deben utilizar divs!!! ;) 
- El div divide diferentes elementos en la pàgina
- Por ejemplo si hay 2 "noticias" se pondría 1 div para cada subtíutlo....
     
     - Y un div para el pie de página...y otro para "la barra" de "deportes"....etc... 

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
		<div>
			<h3>Producto 1</h3>
				<p>
					El producto 1 cuesta X
				</p>
		</div>
		<div>
			<h3>Producto 2</h3>
				<p>
					El producto 2 cuesta Y
				</p>
		</div>
		<div>
			<h3>Producto 3</h3>
				<p>
					El producto 3 cuesta Z
				</p>
		</div>	
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169925971-34519419-2862-402f-b496-e84886534ccd.png)

---

### Form / Formulario

- Input

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
    </head>	
    <body>
    	<form>
    		<br>
    		<h1> Inputs en HTML del padrino </h1>
    		<br>
    		En esta primer linea el input que se ingrese se quedará en la variable "nombre" para después ser usada en el server, base de datos, etc.
    		Se usa en "backend" 
    		<br>
    		<input type="" name="name">
    		<br>
    		<br>
    		Aquí no tiene ningún nombre el input, aún así puedo escribir en el text box. Y tiene el default texto, dejarlo vacío o con texto, es lo mismo.
    		Como tiene el atributo requiered, es necesario para enviar el formulario del button "send"
    		<input type="text" requiered="">
    		<br>
    		<input type="text" value="este input text tiene un 'vaule' con este texto">    		
    		<br>
    		Aquí el type es "password"
    		<br>
    		<input type="password">
    		<br>
    		Números:
    		<br>
    		<input type="number">
    		<br>
    		<br>
    		Solo formato mail con @
    		<br>
    		<input type="email">
    		<br>
    		<br>
    		Y muchos más:
    		<input type="color">
    		<input type="range">
    		<input type="time">
    		<input type="date">
    		<br>
    		Solo 5 pasos de rango:
    		<input type="range" min="1" max="5">
    		<br>
    		<br>
    		El submit no necesita value para que salga el default "send". Además el submit siempre enviará los datos de las cajas (por ejemplo los mails no se podrían mandar aunque es mejor hacerlo en backend)
            <input type="submit">
            <br>
            <br>  
            Pero si no se pone nada en un "button" sale vacío
            <input type="button" value="presionar!">
            <input type="button">
    	</form>	
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169956890-2d25f381-25fe-4c15-83fa-d28f2c2ad7c0.png)

---

### Metadatos

- `meta`
 
- se pone en el `head`
- donde no se puede ver (son metadatos)
- Por ejemplo sirven para poner acento y codificarse en `UTF-8`

    - Ejemplos:

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
		<meta charser="utf-8">
		<meta name="keywords" content="harina, leche, jugo, droga, armas, galletas, keywords para crawlers y demás">
		<meta name="description" content="Una descripción de la página, útil para los crawlers entre otras cosillas, hay caracteres ideales entre 70 y 140">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporation SA de CV">
		<meta name="robots" content="noindex">
		<meta name="robots" content="nofollow">
    </head>	
    <body>

    </body>
</html>
```

---

### HTML Semantic Tags

- [Instrucciones Pro completas](https://www.semrush.com/blog/semantic-html5-guide/)

- ![image](https://user-images.githubusercontent.com/94720207/169968546-55c2a86d-dda3-43fa-9cfd-b8d05118fd5e.png)

    - Super simple semantic HTML5 Example:

- ![image](https://user-images.githubusercontent.com/94720207/169968613-631bd37b-f8d1-475f-862d-8f547af4c131.png)

    - Using sections and articles:

- ![image](https://user-images.githubusercontent.com/94720207/169968847-7b0fda95-0cf0-434e-b1b3-f92893a9da52.png)

    - Related Aside: 

- ![image](https://user-images.githubusercontent.com/94720207/169968823-ec0d3075-e40c-4810-a685-a2e8cbafdd38.png)

    - Indirectly Related Aside:
    
- ![image](https://user-images.githubusercontent.com/94720207/169968943-768920dc-3ae5-4b8e-98c9-27df72cd6204.png)

    - Section VS Article:
    
- ![image](https://user-images.githubusercontent.com/94720207/169969015-fca3d05e-ce4d-42d2-829e-23b4dac3aa70.png)

    - **NOT TO DO**

- ![image](https://user-images.githubusercontent.com/94720207/169969111-10a3bcc9-7bc3-41d2-9f40-e77c5a4ef452.png)

    - **GOOD SEMANTICS = GOOD FOR HUMANS, GOOD FOR ROBOTS! HTML GOOD SEMANTICS ARE YOUR FRIEND :)**

- ![image](https://user-images.githubusercontent.com/94720207/169969401-cf461e31-059c-402d-85f5-4104c679494c.png)
  
### Semantics usando los ejemplos:

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 HTML course">
		<meta name="description" content="Fz3r0 Labs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporation SA de CV">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
    </head>	
    <body>
    	<header>
    		<nav>
    			<ul>
    				<li><a href="index.html" >index!</a></li>
    				<li><a href="page2.html"></a>page1</li>
    				<li><a href="page3.html"></a>page2!</li>
    				<br>
    				<p>---------termina el header y su nav-------------------</p>
    			</ul>
    		</nav>
    	</header>
    <article>
		<section>	
    		<p>---------empieza el "contenido de la página"----------</p>
    		<h1> Titulo 1!! Comienza "article" con su respectiva "section", con este Titulo 1 a partir de aquí puede cambiar, todo lo de arriba SIEMPRE DEBE SER IGUAL</h1>
    			<p>
    				Semánticamente ahora si está bien puesta la página con un "article" que después contiene un "section", ya dentro de ese section está el título y los párrafos, como este!!!
    				<br>
    				<br>
    				Así los cambios de página se verán limpios.
    				<br>
    				<br>
    				Este ya es el párrafo del index, la page 1 y page 2 tendrán otra cosa seguramente, pero siempre con su footer y su header, pa' que se vea bonito y pro. (o por lo menos casi siempre) ya que es el header de toda la página aunque vayas y vengas y cambies de página. Es la "buena práctica"
    			</p>
		</section>    
		<section>	
    		<h3> Titulo 2!! esta es otra section!!!! pero sigue dentro del mismo article!!! </h2>
    			<p>
    				Super pro, 2 "sections" pero todo dentro del "article" como muestran las imágenes, además, aún vienen los asides y el footer después de esto!
    				<br>
    				<br>
    				Arriba el header, metadatos y demás cosas invisibles
    				<br>
    				Abajo los asides y después el footer. 
    			</p>
    			<p>---------termina el contenido "central"de la page, pero comienza el "aside" (justo acabando esta "section" y su "article")----------</p>
		</section>
	    <section>
	    	<aside>
	    		<h3>Titulo aside 1, cosillas a un lado, una lista, link, o lo que sea!!! solo que con únicamente HTML no se notará, se verá abajo, pero el CSS si lo identificará como un aside</h3>
	    		<p>Este sería el contenido del aside</p>
	    	</aside>
	    </section>
	    <section>
	    	<aside>
	    		<h3>Titulo aside 2, con su respectiva section</h3>
	    		<p>después de este aside acaba ahora si el "article" (que contiene todo lo "central")</p>
	    	</aside>
	    </section>
	</article>        
	<aside>
	    <h3>Titulo aside 3, sin section y fuera del article, último aside</h3>
	    <p>Es el aside que marca la imágen fuera de todo del lado derecho, pero aún dentro del "main"</p>
	</aside>
    	<footer>
    		<nav>
    			<p>--------------comienza footer y su nav ----------------</p>	
    			<ul>
    			<li><a href="index.html" >index!</a></li>
				<li><a href="page666.html"></a>page666!</li>
    			</ul>
				<p>Este es el footer con su nav, y en teoría tampoco debería cambiar nunca!</p>
    		</nav>
    	</footer>	    
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169978795-93cd1399-4c34-41cc-8f19-90821ebef8f5.png)

---

### Tablas

---

### Cosillas extras

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Titulo: Fz3r0 Compumundo Hypermegared</title>
		<meta charset="utf-8">
		<link href="favicon.ico" rel="icon" type="image/x-icon">	
    </head>	
    <body>
        <center>
    	<h1>Cosillas extra: center, alt(ceo), favicon, link misma página  </h1>
    	<p>
    		Todo irá centrado ya que el "center" lo marqué para todo el body, ingue su! 
    		<br>
    		<br>
    		Lo del favicon va arriba en meta! con "link = rel" debe ir en formato .ico
    		<br>
    		Esta imagen tiene más propiedades que las anteriores "alt", "title"(mouse hover)
    		<br>
    		<img src="malcom.jpg" alt="por si no carga la imagen" title="mouse hover fz3r0">
    		<br>
    		<br>
    		Otra cosilla que faltó, son los links a la misma página pero otra altura, por ejemplo los titulos del mark down (irónico el ejemplo ya que mark down funciona en base a html jaja!)
    		<br>
    		Este > <a href="#ejemplo_titulo">es el link hacia el titulo de "hasta abajo" después de "mucho texto" :P</a> se debe usar # dentro de href seguido del titulo!!!
    		<br>
    		Para eso debemos agregar el "id" en los titulos para que tenha un identificador por ejemplo:
    		<br>
    		<br>
    		<p><i>Fz3r0_SpAm_Fz3r0_SpAm_Fz3r0_SpAm_ (simulando mucho texto, spam de espacios incoming!!!)</i></p>
    		<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

    		<h3 id="ejemplo_titulo">hacia este titulo habrá un link al inicio de la página para no pasar por "mucho" este titulo tiene el ID "ejemplo_titulo" texto" </h3>
    	</p>
    	</center>
    	<p>Esto no irá centrado, así porque si</p> </p>
    	<p><b> EL CENTER ES MEJOR HACERLO ES CSS Y NUNCA EN HTML </b></p>
    	<br>	
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/169988375-5585f018-0644-4023-a57b-cb2c843c8b59.png)

- ![image](https://user-images.githubusercontent.com/94720207/169988662-254f4372-c99d-4316-8cc1-ccb57060fa59.png)

--- 

### Errores Comunes de HTML

- Tratar de hacer que se vea bien (para eso es CSS), solo usar bien la semántica HTML y ya!
- Usar tags obsoletas
- Mientras mejor semántica mejores robots, mejores crawlers, etc...
- Usar mal los DIV.... con las imágenes que puse queda mñas que claro donde va cada cosa, es muy importante ya estando en CSS
- Ya no se usa combinar lenguajes y meter a fuerza con calzador CSS o javascript entre tags HTML, no se deberían combinar, sino que cada uno tener "su propio espacio"
- por ejemplo escribir `<script src""></script>` ahí si sería modularizar, y meter el otro script ahí dentro
- A eso se le llama modularizar, separar lenguajes, modularizar....

---

### Archivos utilizados

- Malcom: ![malcom](https://user-images.githubusercontent.com/94720207/169991408-0d1a37e8-8ee8-4dbc-8ae4-6fcecd3a596e.jpg)
- Favicon: https://www.favicon.cc/?action=icon&file_id=820354

### References

- https://www.youtube.com/watch?v=z95mZVUcJ-E
- https://www.w3schools.com/html/html_intro.asp
- https://www.youtube.com/watch?v=TC8bT7zTdoE
- https://www.html.am/html-codes/
- https://www.semrush.com/blog/semantic-html5-guide/
- https://www.favicon.cc/
