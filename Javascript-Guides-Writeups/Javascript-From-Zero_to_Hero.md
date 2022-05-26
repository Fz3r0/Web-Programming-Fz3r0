
Alláaaaaa vaaan!!!

## Intro


- Hola mundo y comentarios:

1. Escribir el script

```js

// Este un comentario de una única línea

console.log('I am Fz3r0 and the Sun no longer rises...') // Hola mundo! (Comentario a un lado)

/*

Este es un comentario de varias lineas.
Varias lineas dije!...

*/

```

2. Guardarlo en formato `file_name.js` en el directorio `/` o crear un directorio especial en el `path`

    - ![image](https://user-images.githubusercontent.com/94720207/170553570-35506eb7-e479-4495-8b12-8f4a0f7b56cd.png)

3. Ejecutarlo en `Node.js`:

    - Windows: `node C:\Users\fz3r0\Desktop\fz3r0_OP_2022\fz3r0_2022_programming\javascript\js\fz3r0_index.js`
    
    - Linux: `node /home/usr/fz3r0/documents/programming/javascript/js/fz3r0_index.js`
    
        - Nota: O colocarse en el path y correrlo _(como cualquier shell básicamente :P)_  
        
    - ![image](https://user-images.githubusercontent.com/94720207/170554598-ae26aab3-d50c-418a-bc20-614b66d72bda.png)
    
## Tipos de datos en Javascript

- [Javascript Data Types Cheatlist](https://www.w3schools.com/js/js_datatypes.asp)

    - In programming, data types is an important concept.

    - To be able to operate on variables, it is important to know something about the type.

        - Without data types, a computer cannot safely solve this:

```js
let x = 16 + "Volvo";
```

- Tipos de Datos en `js`

    - `string`
    - `boolean`
    - `null`
    - `number`
    - `undefined`
    - `object`
    
        - Nota:
    
        - Un `object` puede tener cualquier combinación de tipos de datos.
       
        - Los `object` son estructuras que nos permiten agrupar **TODOS** los tipos de datos.    

## Definición de Variables

- [Javascript Variables Cheatsheet](https://www.w3schools.com/js/js_variables.asp)

- `var` es la manera legacy de declarar una variable, **ya no se utiliza.**

```js
// NO UTILIZAR "VAR" PARA DECLARAR VARIABLES!!!

var miPrimerVariable = 'fz3r0_variable_string'
```

- **La correcta manera de declarar variables en `js` es la siguiente utilizando `let` y utilizando posteriormente `console.log` para hacerle un llamado:**

```js
// FORMA CORRECTA DE DEFINIR VARIABLES:

    // 1. Declarar la variable con "let":

let miPrimerVariable = 'fz3r0_variable_string'

    // 2. Mandar a llamar a la variable cuando sea necesario:

console.log(miPrimerVariable);
```

- ![image](https://user-images.githubusercontent.com/94720207/170557784-069eb3a9-9a05-4f4e-b296-57fec771eb3e.png)

```js
// FORMA CORRECTA DE DEFINIR VARIABLES:

    // 1. Declarar la variable con "let":

let miPrimerVariable = 'fz3r0_variable_string'

    // 2. Mandar a llamar a la variable cuando sea necesario:

console.log(miPrimerVariable);

    // 3. Cambiar valores de la MISMA variable (ojo, ya no es necesario el "let"):

miPrimerVariable = 'fz3r0 ha cambiado el string! :)'

    // 4. Mandar a llamar a la variable cuando sea necesario:

console.log(miPrimerVariable);
```

- ![image](https://user-images.githubusercontent.com/94720207/170558599-fe794144-c1c8-4b70-8120-465d0060e4cd.png)

    - De esta manera se pueden ir modificando las variables, muy parecido a otros lenguajes de programación realmente. 

- 



