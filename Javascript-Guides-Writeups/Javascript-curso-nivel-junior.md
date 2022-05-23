


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
<h1></h1>   <----| 2. Contiene algo dentro
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
		Lorem
	</p>
	    
    </body>
</html>
```

- Tipos de Tags:
	
    - Las que acompletan la caja y las que se adaptan al contenido:
    	
        - ![image](https://user-images.githubusercontent.com/94720207/169914777-145ec062-c05a-4c24-b571-31da87ce5d29.png)
        - ![image](https://user-images.githubusercontent.com/94720207/169915001-efacfa72-6f1a-4e32-9b72-78a0d8f8f393.png)

    - Ejemplo con `div`

        - ![image](https://user-images.githubusercontent.com/94720207/169915357-f34498d2-b67f-4ca7-bf51-eeb3cdbbe411.png)
        - ![image](https://user-images.githubusercontent.com/94720207/169915371-4b833337-ec08-49ac-9656-358f89d1b147.png)

     - Margen
         
	 - ![image](https://user-images.githubusercontent.com/94720207/169915530-768d8cff-d80b-4688-a5e7-0874d2235723.png)

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

### Más tags!

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

- `<ul>` listas desordenadas
- `<li>` listas ordenadas

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

###
   	
	








---

### References

- https://www.youtube.com/watch?v=z95mZVUcJ-E
