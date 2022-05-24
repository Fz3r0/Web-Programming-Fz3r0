



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

## Opciones para insertar CSS (Spoiler: solo hay una)

- Existen 3 opciones pero una no es nada recomendada, otra es meeh, y una es la Pro...No revisaré las maneras noobs de programar en CSS siquiera... así que solo utilizaré la siguiente opción:

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

        - Haciendo referencia al archivo y su ubicación en el directorio.  

```html
<!DOCTYPE html>
<html>
    <head>
		<title> Fz3r0 CSS </title>
		<meta charser="utf-8">

		<link rel="stylesheet" href="style.css">

    </head>	
    <body>
	    <h1>Titulo: Fz3r0</h1>
	    <p>Hola, soy Fz3r0!</p>
    </body>
</html>
```






### References

- https://bootswatch.com/
- 


