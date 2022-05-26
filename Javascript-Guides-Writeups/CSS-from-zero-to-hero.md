



# CSS by Fz3r0



## Intro de CSS

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

### Estructura y Sintaxis Básica de CSS

- Estructura básica y sintaxis de CSS, ejemplo-1:

```css
html {
    text-align: left;
    color: red;
}
```

- Estructura básica y sintaxis de CSS, ejemplo-1 - Comentado:

```css
/* Elemento "html" / Selector > se abre "{" */
html {

/* Propiedades1: "text-align" >> Con valores: "left" */
    text-align: left;

/* Propiedades2: "color" >> Con valores: "red" */
    color: red;
}
/* Termina Elemento "html" / se cierra "}" */
```

- Estructura básica y sintaxis de CSS, ejemplo-2:

```css
html {
    text-align: left;
    color: red;
}

*  {
   box-sizing: border-box;
}

.card {
    background-color: white;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.3);
}    
```

- Comentado: 

```css

/* En este caso se seleccionó 1 elemento "html" */
html {
    text-align: left;
    color: tomato;
}

/* El "*" significa que se seleccionó TODO */
*  {
   box-sizing: border-box;
}

/* Selecciona múltiples elementos con la "clase" de CSS "card" */
.card {
    background-color: white;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.3);
}    
```

## Opciones para insertar CSS _(Spoiler: solo hay una Pro)_

- Existen 3 opciones pero una no es nada recomendada, otra es meeh, y una es la Pro...

- Las primeras 2 solo haré mención para saberlas identificar en caso de un análisis o pentesting, pero para desarrollo personal no abordaré formas noobs de CSS...

1. **La peor: abrir un `style` dentro de algún elemento HTML, ejemplo:**

```html
/* Peor forma de CSS, fuchi! */

<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">
    </head>
	
    <body style="color:red">
	  
	    <h1>Titulo: Fz3r0</h1>
	    <p>Hola, soy Fz3r0!</p>
    </body>
</html>
```

2. **Forma meeeh: abrir un `style` desde el `head` del código `HTML`:**

```html
/* Forma meehhh de CSS, fuchi! */

<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">
	        
	        <style>
		   body {
		       color: red;
		   }	
		</style>	
			
    </head>
	
    <body style="color:red">
	  
	    <h1>Titulo: Fz3r0</h1>
	    <p>Hola, soy Fz3r0!</p>
    </body>
</html>
```

3. **Forma PRO de usar `CSS`: Escribir CSS Importanto un archivo `css` dentro del `html`:**

### Escribir CSS Importanto un archivo `css` dentro del `html`

- Empezaré desde un `HTML` super básico:

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">
    </head>	
    <body>
	    <h1>Titulo: Fz3r0</h1>
	    <p>Hola, soy Fz3r0!</p>
    </body>
</html>
```

- ![image](https://user-images.githubusercontent.com/94720207/170134040-840fab4e-06be-4de1-bfff-86f4ed2b379a.png)

- Dentro de head se escribe el `link rel`

    - `<link rel="stylesheet" href="style.css">`
    
        - Link relacionado al stylesheet

        - Haciendo referencia al archivo y su ubicación en el directorio (en mi caso `/css/style.css`).  

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">

		<link rel="stylesheet" href="css/style.css">

    </head>	
    <body>
	    <h1>Titulo: Fz3r0</h1>
	    <p>Hola, soy Fz3r0!</p>
    </body>
</html>
```

- El archivo `style.css` al que hace referencia es en el que empezaré la aventura:

```css
body {
    text-align: left;
    color: red;
}
```

- Lo guardaré en una carpeta llamada `css` creada en mi root `/`

    - ![image](https://user-images.githubusercontent.com/94720207/170135921-587c0fcd-bb00-407d-ae1b-579b6f692089.png)
    
    - ![image](https://user-images.githubusercontent.com/94720207/170135974-0f33aaf0-8a5c-4a48-86fc-cf75b8ce8a10.png)

- Si ejecuto el `index.html` nuevamente el `body` toma el style de CSS! 

    - ![image](https://user-images.githubusercontent.com/94720207/170136248-4575c2f7-f102-48fe-8bb8-696c8a228b89.png)

- Inspeccionar los cambios:

    - ![image](https://user-images.githubusercontent.com/94720207/170147728-3a43e5c2-6931-4c7f-ae0b-3bc99173f8fb.png)

    - ![image](https://user-images.githubusercontent.com/94720207/170147944-71306a18-7011-4409-83f1-3d27293b504d.png)

## Selectores en CSS

- Para poder tener bien especificados los selectores hay que agregarles `id` a los elementos de `HTML`

- Por ejemplo agregaré ID al título, después iré agregando ID básicamente a todo (**u otros selectores**)... Mientras más identificado, seleccionado y ordenado, mejor! 

    - En este caso utilizaré los selectores:
    
        - `id`
        - `class`   

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">

		<!-- Importando el style.css --> 

		<link rel="stylesheet" href="css/style.css">

    </head>	
    <body>
	    
            <!-- Agregando "id" para titulo, "class_texto" para párrafo --> 

	    <h1 id="id_titulo">Titulo: Fz3r0</h1>
	    
	    <p class="class_texto">1 Hola, soy Fz3r0! 1</p>
	    
	    <p class="class_texto">2 Hola, soy Fz3r0! 2</p>
	    
	    <p class="class_texto">3 Hola, soy Fz3r0! 3</p>
    
    </body>
</html>
```

- Ahora para poderlo aplicar en `CSS:`

    - Titulos:
    
        - Con `#` se indica a `CSS` que debe ir  abuscar un elemento con propiedad `id` que tenga el id `id_titulo`.
        - Solo los titulos **(H1,H2,H3,H4,H5,H6)** contienen esta propiedad. 
    
    - Párrafos:

        - Con `p` se seleccionan **todos los `p`**.
        - Con `.` se indica a `CSS` que debe seleccionar solo `1` clase.
        - Se debe indicar el nombre de la `clase` osea `id_texto`. 
    
    - Nota: con `*` se selecciona TODO, pero por FUERA de un estilo, no confundir! (eso se verá mas adelante)

- Seleccionar todo con `p` _(excepto titulo que ya se especificó)_

```css
#id_titulo {
    text-align: left;
    color: red;
}

p {
    text-align: right;
    color: blue;
}     
```

- Solo 1 por 1 `class` usando `.`

```css
#id_titulo {
    text-align: left;
    color: red;
}

.class_texto {
    text-align: right;
    color: blue;
}     
```
- ![image](https://user-images.githubusercontent.com/94720207/170150812-c491199f-8c7b-4568-81dc-b16b7008b950.png)

- ![image](https://user-images.githubusercontent.com/94720207/170150766-685b4061-056a-467e-ad9e-61c1146cf2c5.png)

- Ahora seleccionó todos los "p" en azul, ya que aunque usé `.` todos se llaman `class_texto`, o mejor dicho como lo entendería el explorador:

    - **`p.class_texto`** 

- Así que para que no cambien todos juntos, tendría que seleccionar **un nombre por `class`** desde mi `HTML`, así tendría por ejemplo:

    - **`p.class_texto1`** 
    - **`p.class_texto2`** 
    - **`p.class_texto3`** 

- Ahora se va aterrizando el por qué escribir el código HTML con semántica perfecta y tener todo bien identificado desde un principio, por ejemplo:


- **`index.html`:**

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">

		<!-- Importando el style.css --> 

		<link rel="stylesheet" href="css/style.css">

    </head>	
    <body>
	    
            <!-- Agregando "id" para titulo, 

                "class_text1", "class_text2", "class_text3" para cada párrafo --> 

	    <h1 id="id_titulo">Titulo: Fz3r0</h1>
	    
	    <p class="class_texto1">1 Hola, soy Fz3r0! 1</p>
	    
	    <p class="class_texto2">2 Hola, soy Fz3r0! 2</p>
	    
	    <p class="class_texto3">3 Hola, soy Fz3r0! 3</p>
    
    </body>
</html>
```

- **`style.css`:**

```css
#id_titulo {
    text-align: left;
    color: red;
}

.class_texto1 {
    text-align: right;
    color: blue;
}

.class_texto2 {
    text-align: center;
    color: purple;
}

.class_texto3 {
    text-align: left;
    color: green;
}

```

- ![image](https://user-images.githubusercontent.com/94720207/170358890-6758da0c-93a1-47dc-ae96-1907c34e905c.png)

- **Ojito!**

- También se pueden seleccionar varias clases al mismo tiempo dentro de un mismo párrafo `p`

- Esto permite seleccionar 2 o más elementos que compartan aunque sea 1 clase de todas las que tengan. 

- Por ejemplo, utilizando exactamente el mismo `style.css` pero cambiando lo siguiente en el `HTML`:

    - Le pondré nuevamente a los primeros 2 `p` la clase `class_texto1`, pero! seguido de otra `class` secundaria diferente en el segundo y tercer párrafo `p`. 
    - El tercer `p` se llamará totalmente diferente, es decir, los 3 `p`'s tendrán un "nombre completo" diferente, pero algunos coincidirán en algunos "nombres" o mejor dicho: `class`.

- `index.html`

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">

		<!-- Importando el style.css --> 

		<link rel="stylesheet" href="css/style.css">

    </head>	
    <body>
	    
            <!-- p1 y p2 comparten la class "class_texto1" --> 

	    <h1 id="id_titulo">Titulo: Fz3r0</h1>
	    
	    <p class="class_texto1">1 Hola, soy Fz3r0! 1</p>
	    
	    <p class="class_texto1 class_soy_otra_class">2 Hola, soy Fz3r0! 2</p>
	    
	    <p class="class_texto3 class_soy_otra_class">3 Hola, soy Fz3r0! 3</p>
    
    </body>
</html>
```

- `style.css`

```css
#id_titulo {
    text-align: left;
    color: red;
}

p.class_texto1 {
    text-align: right;
    color: blue;
}

p.class_texto2 {
    text-align: center;
    color: purple;
}

p.class_texto3 {
    text-align: left;
    color: green;
}

```

- ![image](https://user-images.githubusercontent.com/94720207/170362594-922c5334-5a90-4e0e-8e21-d850c06f5cae.png)

- Si después de eso yo agregara otro `selector` como `p.class_soy_otra_class` entonces cambiarían 2 y 3. 

- Esto pasa por la **`cascada`** de `CSS`, tomaría la segunda elección ya que ´p2´ compartiría ya 2 selectores para 2 clases diferentes:

- `style.css`

```css
#id_titulo {
    text-align: left;
    color: red;
}

p.class_texto1 {
    text-align: right;
    color: blue;
}

p.class_texto2 {
    text-align: center;
    color: purple;
}

p.class_texto3 {
    text-align: left;
    color: green;
}

p.class_soy_otra_class {
    text-align: center;
    color: brown;
    font-weight: bold;
    font-family: "Lucida Console";
    font-size: 21px
}
```

- ![image](https://user-images.githubusercontent.com/94720207/170364801-af487209-7beb-4dc3-8fb1-0c9682e4031a.png)

## Usando "div" en selectores CSS

- Los `<div></div>` que eran muy importantes para la semántica de `HTML` pero no se notaban en lo más minimo es justo para que "algo" como `CSS` lo pueda identificar! así de fácil.

- Ahora los "bloques" con `div` podrán ser seleccionados y referenciados!

- Para tener un buen laboratorio con varios escenarios y variables hice este script de `css` que tiene varias combinaciones de clases:

    - Clases que se repiten en `TODOS`
    - Clases que `NO` se repiten
    - Clases que solo se repiten en `1` y `2`
    - Clases que solo se repiten en `2` y `3` 

- `index.html`

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">
		<link rel="stylesheet" href="css/style.css">
    </head>	
    <body>

    	<div>
    		<h1 id="id_titulo">Titulo1: Div1</h1>
	    
	    		<p class="text class_A class_1 diferente_1">1 Hola, soy Fz3r0! 1</p>
	    
	    		<p class="text class_A class_9 diferente_2">2 Hola, soy Fz3r0! 2</p>
	    
	    		<p class="text class_Z class_9 diferente_3">3 Hola, soy Fz3r0! 3</p>  		
    	</div>

    	<div>
    		<h1 id="id_titulo">Titulo2: Div2</h1>
	    
	    		<p class="text class_A class_1 diferente_1">1 Hola, soy Fz3r0! 1</p>
	    
	    		<p class="text class_A class_9 diferente_2">2 Hola, soy Fz3r0! 2</p>
	    
	    		<p class="text class_Z class_9 diferente_3">3 Hola, soy Fz3r0! 3</p> 		
    	</div>

    </body>
</html>
```

- Esta es una prueba con `CSS` para identificar los divs, párrafos y clases:

- `style.css`

```css
#id_titulo {
    text-align: left;
    color: black;
    font-weight: bold;
}

p.diferente_1 {
    text-align: right;
    color: blue;
    font-weight: bold;
    font-size: 22px
}

p.diferente_2 {
    text-align: center;
    color: purple;
    font-weight: bold;
    font-size: 22px
}

p.diferente_3 {
    text-align: left;
    color: green;
    font-weight: bold;
    font-size: 22px
}
```

- ![image](https://user-images.githubusercontent.com/94720207/170375860-5a5e5b6c-9bd7-4b4e-a581-f2df2024b28b.png)

- Ahora que ya tengo el `HTML` y lo probé con el `CSS` que usaré en los próximos ejemplos, mostraré la primer prueba con `CSS`

    - **Seleccionaré `div p` osea **TODOS** los `p` (párrafos) dentro del `div` (**o cualquier div ya que aún no están identificados**)**
    
    - **Lo mismo haré con los titulos `h2` (en este ejemplo ambos titulos de ambas `divs` son `h2`)** 

- `style.css`

```css
#id_titulo {
    text-align: left;
    color: black;
    font-weight: bold;
}
div p {
    text-align: center;
    color: magenta;
    font-weight: bold;
    font-size: 22px

}
```
- ![image](https://user-images.githubusercontent.com/94720207/170376463-693463d8-dbf1-4feb-bfd1-a9f7d208d7a8.png)

- Pero, si pongo la base inicial de mi `style.css` donde ya había especificado las clases **NO CAMBIARÁ EL ESTILO DE LOS `p`, A PESAR DE ESTAR HASTA ABAJO DE LA CASCADA:**

    -  Esto es por el **selector**!!! Estoy seleccionando `TODOS` los `TAGS` de `p`... No los que ya tengo identificados como `p.texto` ;)
    -  Algo similar pasaría con el titulo, ya que ya hemos declarado un estilo con el selector `#`
    -  Regresamos a lo mismo, por eso es bueno tener bien identifcado todo con buena semántica `HTML`, los `p` con sus clases, cada sección con `div`, etc. 

- `style.css`

```css
#id_titulo {
    text-align: left;
    color: black;
    font-weight: bold;
}

p.diferente_1 {
    text-align: right;
    color: blue;
    font-weight: bold;
    font-size: 22px
}

p.diferente_2 {
    text-align: center;
    color: purple;
    font-weight: bold;
    font-size: 22px
}

p.diferente_3 {
    text-align: left;
    color: green;
    font-weight: bold;
    font-size: 22px
}

/* Los siguientes "div p" o "div h1" no tendrían sentido, ya que he identificado cada titulo y párrafo de la página */

div p {
    text-align: center;
    color: magenta;
    font-weight: bold;
    font-size: 22px

}

div h1 {
    text-align: center;
    color: lime;
    font-weight: bold;
    font-size: 22px

}
```

- ![image](https://user-images.githubusercontent.com/94720207/170376753-3819c24e-3384-4416-a830-fe78170f9e36.png)

- También se puede aplicar **el mismo estilo** para varios **elementos**

    - Por ejemplo, que tal que yo tengo varios tipos de titulo como `h1` para `titulo1` y `h2` para `titulo2` pero quiero el mismo estilo para los 2 titulos:
    - Ojo! como TODO debería estar dentro de su `div` de manera limpia y elegante, obvio se especifica su `div`
    
        - `div h1, div h2`  
    
    - Nota: quitaré los primeros estilos a los `p` y `h` para que no sobrepongan los estilos de los `div`: 

```css
/* Aplicando el mismo estilo para h1 y h2 en el div para titulos */

div p {
    text-align: left;
    color: magenta;
    font-weight: bold;
    font-size: 22px

}

div h1, div h2 {
    text-align: center;
    color: lime;
    font-weight: bold;
    font-size: 22px

}
```

- ![image](https://user-images.githubusercontent.com/94720207/170381252-cf60b1b8-dd6e-4f05-84a9-64f48f19cb3f.png)

- Para seleccionar `TODO` lo que se encuentre dentro del documento `HTML` se usa `*`

- De la misma manera funciona, si ya se ha seleccionado algo no lo tomará en cuenta.

- En este ejemplo a ninguna selección le hemos declarado un tipo de letra, entonces aunque estén declarados, al no haber declado el tipo de letra eso si cambiaría por ejemplo, pero no el color que si cambiamos. 

- Sin embargo, el "text align" no lo cambiará, ya que esa propiedad ya había sido seleccionada independientemente en cada "tag" 

- Es decir, las propiedades también las podría tomar en cuenta por ejemplo:

    - Usando el `.HTML` y `.CSS` con el que inicié esta sección de `div` no seleccioné ningín tipo de letra, entonces eso si lo podría cambiar:

```css
#id_titulo {
    text-align: left;
    color: black;
    font-weight: bold;
}

p.diferente_1 {
    text-align: right;
    color: blue;
    font-weight: bold;
    font-size: 22px
}

p.diferente_2 {
    text-align: center;
    color: purple;
    font-weight: bold;
    font-size: 22px
}

p.diferente_3 {
    text-align: left;
    color: green;
    font-weight: bold;
    font-size: 22px
}

/* Los siguientes "div p" o "div h1" no tendrían sentido, ya que he identificado cada titulo y párrafo de la página */

div p {
    text-align: center;
    color: magenta;
    font-weight: bold;
    font-size: 22px

}

div h1 {
    text-align: center;
    color: lime;
    font-weight: bold;
    font-size: 22px

}

/* Este "div" seleccionadno todo "*" si funcionaría para la tipografía, ya que aunque ya estén decladas varias propiedas, no lo estaba la de tipo de letra */

/* Sin embargo, el "text align" no lo cambiará, ya que esa propiedad ya había sido seleccionada independientemente en cada"tag" */

* {
    font-family: papyrus;
    text-align: right
}
```

- ![image](https://user-images.githubusercontent.com/94720207/170383004-88afeb2d-edd2-4e52-bfd4-520e40bb8fc1.png)

- En resumen:

    - Si hay un `tag` que ya ha sido identificado con alguna clase, unas propiedades generalizadas escritas más adelante no sobre esribirían la configuración ya realizada. 
    - Lo mismo para con las `propiedades` y `elementos` dentro de cada `tag`.
    - Es por eso que siempre hay que tener en cuenta la cascada y los selectores que hemos utilizado. 

## Colores, Medidas y Valores convencionales en general

- Adjunto herramientas para poder revisar, calcular y modificar los valores convencionales de `CSS`:

    - [CSS Units](https://www.w3schools.com/cssref/css_units.asp)
    - [PX to EM Conversion](https://www.w3schools.com/cssref/css_pxtoemconversion.asp)
    - [CSS Colors](https://www.w3schools.com/cssref/css_colors.asp)
    - [CSS Legal Color Values](https://www.w3schools.com/cssref/css_colors_legal.asp)

- En general de esta página se pueden sacar todos esos datos que se utilizarán en un futuro:

    - **[CSS References](https://www.w3schools.com/cssref/default.asp)**

## Borders

- Adjunto la cheatsheet de borders:

    - [CSS Borders](https://www.w3schools.com/Css/css_border.asp)

- Ejemplo:

- `style.css`

```css
#id_titulo {
    text-align: left;
    color: black;
    font-weight: bold;
    
    border: 10px royalblue dashed;
}

p.diferente_1 {
    text-align: right;
    color: blue;
    font-weight: bold;
    font-size: 22px

    border: 5px darkred outset;
}


div p {
    text-align: center;
    color: magenta;
    font-weight: bold;
    font-size: 22px

}

div h1 {
    text-align: center;
    color: lime;
    font-weight: bold;
    font-size: 22px

}


* {
    font-family: monospace;
    border: 5px lightgray double;
}
```

## Background 

- Adjunto la cheatsheet de background:

    - [CSS Background](https://www.w3schools.com/Css/css_background.asp)

Ejemplo básico:

```css
h1 {
  background-color: green;
}

div {
  background-color: lightblue;
}

p {
  background-color: yellow;
}
```

- Más ejemplos:

```css

div.uno {
   background-color: lightblue 
   opacity: 0.3; 
}

div.dos {
   background-color: lightblue 
   background: rgba(0, 128, 0, 0.3)
}


```

Background image:

```css
body {
  background-image: url("paper.gif");
  background-repeat: norepeat;
  background-position: right top;
  background-attachment: fixed;
}
```

### Background EZ hint:

- **CSS background - Shorthand property**

    - **To shorten the code, it is also possible to specify all the background properties in one single property. This is called a shorthand property.**

```css
body {
  background-color: #ffffff;
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}
```

## CSS Box Model

- Adjunto la cheatsheet de background:

    - [CSS Box Model](https://www.w3schools.com/Css/css_boxmodel.asp)

- ![image](https://user-images.githubusercontent.com/94720207/170388070-4baa079a-d2e6-44d3-a601-c86d77b426b7.png)

- Ejemplo:

```css
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

## CSS Outline

- Adjunto la cheatsheet de background:

    - [CSS Outline](https://www.w3schools.com/Css/css_outline.asp)

- ![image](https://user-images.githubusercontent.com/94720207/170388806-fb7da099-7a7a-42f7-82fd-e5f5f636bf22.png)

- Ejemplo:

```css
body {
  outline-style: groove
}
```

```css
p.dotted {outline-style: dotted;}
p.dashed {outline-style: dashed;}
p.solid {outline-style: solid;}
p.double {outline-style: double;}
p.groove {outline-style: groove;}
p.ridge {outline-style: ridge;}
p.inset {outline-style: inset;}
p.outset {outline-style: outset;}
```

## CSS Text Formatting

- Adjunto la cheatsheet de todo el formato en cuanto a texto, fuente, tipografía en CSS:

    - [Text Formatting on CSS](https://www.w3schools.com/Css/css_text.asp)

### Cargar tipografía online de `google fonts`

- Entrar a: 

    - https://fonts.google.com/ 

- Seleccionar tiografía

    - ![image](https://user-images.githubusercontent.com/94720207/170390762-20c5105e-a70f-4d99-9e50-efb15203d967.png)

- Copiar link:

    - ![image](https://user-images.githubusercontent.com/94720207/170390891-b9e7d869-9105-40ed-ade6-ba4bac995d90.png)

- Pegar en `head` de código `HTML`:


```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">
		<link rel="stylesheet" href="css/style.css">
	    
                <!-- Código de Tipografía: -->
	    
	        <link rel="preconnect" href="https://fonts.googleapis.com">
                <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
                <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
	    	        
    </head>	
    <body>
    	<div>
    		<h1 id="id_titulo">Titulo1: Div1</h1>   
	    		<p class="text class_A class_1 diferente_1">1 Hola, soy Fz3r0! 1</p>	    
	    		<p class="text class_A class_9 diferente_2">2 Hola, soy Fz3r0! 2</p>	    
	    		<p class="text class_Z class_9 diferente_3">3 Hola, soy Fz3r0! 3</p>  		
    	</div>
    	<div>
    		<h1 id="id_titulo">Titulo2: Div2</h1>	    
	    		<p class="text class_A class_1 diferente_1">1 Hola, soy Fz3r0! 1</p>	    
	    		<p class="text class_A class_9 diferente_2">2 Hola, soy Fz3r0! 2</p>	    
	    		<p class="text class_Z class_9 diferente_3">3 Hola, soy Fz3r0! 3</p> 		
    	</div>
    </body>
</html>
```
 




### References

- https://www.w3schools.com/cssref/default.asp
- https://youtu.be/wZniZEbPAzk 
- https://bootswatch.com/
- https://fonts.google.com/
- 
- 


