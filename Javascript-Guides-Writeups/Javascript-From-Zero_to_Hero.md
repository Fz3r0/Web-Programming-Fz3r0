
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

- [**Javascript Data Types Cheatlist**](https://www.w3schools.com/js/js_datatypes.asp)

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

- [**Javascript Variables Cheatsheet**](https://www.w3schools.com/js/js_variables.asp)

- `var` es la manera legacy de declarar una variable, **ya no se utiliza.**

```js
// NO UTILIZAR "VAR" PARA DECLARAR VARIABLES!!!

var miPrimerVariable = 'fz3r0_variable_string'
```

- **La correcta manera de declarar variables en `js` es la siguiente utilizando `let` y utilizando posteriormente `console.log` para hacerle un llamado:**

    - NOTA: Siempre se debe empezar la variable por un string, después ya puede ser seguida por un número, por ejemplo:
    
        - `fila_22`
        - `form-_-3`
        - `f0_$variable_radio.b_200` 

```js
// FORMA CORRECTA DE DEFINIR VARIABLES:

    // 1. Declarar la variable con "let":

let miPrimerVariable = 'fz3r0_variable_string'

    // 2. Mandar a llamar a la variable cuando sea necesario:

console.log(miPrimerVariable);
```

- ![image](https://user-images.githubusercontent.com/94720207/170557784-069eb3a9-9a05-4f4e-b296-57fec771eb3e.png)

### Mutabilidad

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
    
    - A esto de ir re-asignando variables se le llama `mutabilidad`.   

## Palabras Reservadas de Javascript

- In JavaScript you cannot use these reserved words as variables, labels, or function names: 

    - [**JavaScript Reserved Words**](https://www.w3schools.com/js/js_reserved.asp)

## Asignando otros Tipos de Datos a las variables

- Ejemplos:

```js
    // Boolean

let f0_boolean = true
let f0_otro_boolean2 = false

    // Number

let f0_number = 1
let f0_otro_number2 = 10
let f0_otro_number3 = 666
let f0_otro_number4 = 3.1416

    // Undefined (NO TIENE NINGÚN VALOR [COMO EN EL CASO DE NULL], ES SIMPLEMENTE "INDEFINIDO")
    // Como es "indefinido" no necesita un " = 0 " o nada por el estilo!!! 

let undef 

    // Null - Este SI es un valor, pero, su valor es "nulo"

let valor_nulo = null  

    // Hacer un llamado a las variables para imprimir en consola:  

console.log(undef);
console.log(valor_nulo);
console.log(f0_boolean, f0_otro_boolean2, f0_number, f0_otro_number2, f0_otro_number3, f0_otro_number4);
console.log(f0_otro_number3, f0_otro_number3, f0_otro_number3, f0_otro_number3, f0_otro_number3, f0_otro_number3);
console.log(f0_otro_number3);
console.log(valor_nulo);
console.log(undef);
console.log(f0_otro_number3);
console.log(undef, valor_nulo, f0_otro_number3, f0_otro_number2);
console.log(f0_otro_number3);
console.log(valor_nulo);
console.log(f0_otro_number3);
console.log(f0_boolean, f0_otro_boolean2, f0_number, f0_otro_number2, f0_otro_number3, f0_otro_number4);
```

- ![image](https://user-images.githubusercontent.com/94720207/170563978-22f23bda-e211-40de-8ef4-7df6ce2a6714.png)

```js
console.log(undef);
console.log(valor_nulo);
console.log(f0_boolean, f0_otro_boolean2, f0_number, f0_otro_number2, f0_otro_number3, f0_otro_number4);
console.log(f0_otro_number3, f0_otro_number3, f0_otro_number3, f0_otro_number3, f0_otro_number3, f0_otro_number3);
console.log(f0_otro_number3);
console.log(valor_nulo);
console.log(undef, "esto no es una variable, lo escribí directo ;)");
console.log(f0_otro_number3);
console.log(undef, valor_nulo, f0_otro_number3, f0_otro_number2);
console.log(f0_otro_number3, "numero sin variable:", 420);
console.log(valor_nulo, null, "<--- un null es variable, el otro es null directo");
console.log(f0_otro_number3);
console.log(f0_boolean, f0_otro_boolean2, f0_number, f0_otro_number2, f0_otro_number3, f0_otro_number4);
```

- ![image](https://user-images.githubusercontent.com/94720207/170564862-c81aeb0a-a6a9-420e-9e69-2f9703846353.png)

## Objetos en Javascript

- [**JavaScript Objects**](https://www.w3schools.com/js/js_objects.asp)

    - **Un objeto es una agrupación de datos. -> Estos datos hacen sentido entre si.**
     
        - In real life, a _**car**_ is an **`object`**.

        - A _**car**_ has **`properties`** like _**weight**_ and _**colo**r_, and **`methods`** like **_start_** and **_stop_**.
    
        - All **_cars_** have the same **`properties`**, but the **`property values`** differ from **_car_** to _**car**_.

        - All **_cars_** have the same **`methods`**, but the **`methods`** are performed at **_different times_**.
    
        - ![image](https://user-images.githubusercontent.com/94720207/170566842-d7d2829e-34f5-46c4-8cc3-8f25c7890683.png)

- Del mismo modo que ese coche son los `objetos` en Javascript, por ejemplo:

    - Un `usuario` con **nombre, apellido, contraseña, usuario, tipo de usuario, etc...** y con un objeto agruparemos esos datos en un `objeto`  


- El `object` es uno de los **tipos de datos** más utilizados en Javascript.

```js

    // Objeto vacío (no contiene ninguna propiedad):

const f0_objeto_vacio = {}

    // Objeto con "variables o valores" que se llaman << PROPIEDADES >>

    // Las "propiedades" de los "objetos" se colocan entre "{}"

        // "const" es muy similar a "let", solo que uno es para variables y otro es para objetos 

        // en lugar de usar "=" como "let", los "const" usan ":"

        // Agregar "," para agregar una siguiente propiedad

const f0_objeto = {

	f0_numero: 666,
	f0_string: "Esto es un string, padrino!",
	f0_condicion: true,

}  

    // Mandar llamar al objeto "const" para imprimir en consola el objeto "f0_objeto" 

console.log(f0_objeto)
```

- ![image](https://user-images.githubusercontent.com/94720207/170572973-4f352e44-028f-4e58-a08c-ee97f3a0d570.png) 

- Al imprimir un `object` se puede ver con la misma `sintaxis` y formato que usamos en el script. 

    - Nota: la `,` en la última propiedad del objeto no es necesaria, pero es una buena práctica (para copiar y pegar fácil y mejor uso del control de versiones)

- **También se puede tomar un objeto e imprimir una sola propiedad de este (o seleccionar la propiedad deseada):**

    - Similar a `CSS` solo se debe poner el identificador del objeto, en este caso el `const` `"f0_objeto"` seguido de `.` y el nombre de la propiedad: 

```js
    // Mandar llamar al objeto "const" "f0_objeto", pero solo las propiedades seleccionadas:

console.log(f0_objeto.f0_string, f0_objeto.f0_numero, f0_objeto.f0_string, f0_objeto.f0_numero)
console.log(f0_objeto.f0_condicion, f0_objeto.f0_condicion, f0_objeto.f0_condicion, f0_objeto.f0_condicion, )
console.log(f0_objeto.f0_string, f0_objeto.f0_numero, f0_objeto.f0_string, f0_objeto.f0_numero)
```

- ![image](https://user-images.githubusercontent.com/94720207/170575035-af97e810-f234-481c-8ff5-358772c9199d.png)










