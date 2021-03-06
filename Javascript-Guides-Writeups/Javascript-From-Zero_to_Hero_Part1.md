
Alláaaaaa vaaan!!!

## Intro

```js
console.log(' =-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=');
console.log(' "                                                               "');
console.log(' "                                                               "');
console.log(' "      /$$$$$$$$               /$$$$$$             /$$$$$$      "');
console.log(' "     | $$_____/              /$$__  $$           /$$$_  $$     "');
console.log(' "     | $$          /$$$$$$$$|__/    $$  /$$$$$$ | $$$$  $$     "');
console.log(' "     | $$$$$ /$$$$|____ /$$/   /$$$$$/ /$$__  $$| $$ $$ $$     "');
console.log(' "     | $$__/|____/   /$$$$/   |___  $$| $$   __/| $$  $$$$     "');
console.log(' "     | $$           /$$__/   /$$    $$| $$      | $$   $$$     "');
console.log(' "     | $$          /$$$$$$$$|  $$$$$$/| $$      |  $$$$$$/     "');
console.log(' "     |__/         |________/  ______/ |__/        ______/      "');
console.log(' "                                                               "');
console.log(' "                  I can read people´s minds...                 "');
console.log(' "          I have read the pasts, presents and futures          "');
console.log(' "                And each mind that I peered into               "');
console.log(' "     was stuffed with the same single object of obssesion      "');
console.log(' "                                                               "');
console.log(' "                    -- HECHO EN MEXICO --                      "');
console.log(' "                                                               "');
console.log(' "                     Twitter:  @fz3r0_OPs                      "');
console.log(' "                     GitHub :  Fz3r0                           "');
console.log(' "                                                               "');
console.log(' "                                                               "');
console.log(' =-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=');
```

- ![image](https://user-images.githubusercontent.com/94720207/170615647-c7d688d3-f967-4e85-ab09-8e770eaf7bd1.png)


## Bienvenido al mundo de Javascript, abandonad toda esperanza

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
    
    - ![image](https://user-images.githubusercontent.com/94720207/170601505-ab4fa255-6db1-411f-95cd-3f8ec48ac19c.png)
   
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

## Arreglos en Javascript

- [**JavaScript Arrays**](https://www.w3schools.com/js/js_arrays.asp)

    - An array is a special variable, which can hold more than one value:

```js
const cars = ["Saab", "Volvo", "BMW"]; 
```

Ejemplo:

```js
    // Objeto del ejemplo anterior:

const f0_objeto = {
	f0_numero: 666,
	f0_string: "Esto es un string (que viene de un objeto), padrino!",
	f0_condicion: true,
} 


    // Array vacío (no contiene ningún dato):

const f0_array_vacio = []


    // Array con << DATOS >>

    // Los datos de un "Array" se colocan entre "[]"

        // El array que contiene varios tipos de datos diferentes

        // Incluyendo variables, objetos, strings puestos directamente, números, etc

const f0_array = [1, 2.9, 'fz3r0', f0_objeto.f0_numero, '|XYZ_dentro_de_array|', null, f0_objeto]

const f0_array_2 = ["Así de fácil son los array", f0_objeto.f0_numero, "Son la bolsa del mandado"]

// Mandar llamar a los 2 array que acabo de crear "f0_array", "f0_array_2" a imprimir a consola

console.log(f0_array)

console.log(f0_array_2)
```

- ![image](https://user-images.githubusercontent.com/94720207/170583157-a4ef1ef1-8022-4e48-8742-d2607b333304.png)

---

### Push Method

- Para poder meter más `datos` o `elementos` a un `array` se utiliza el `push`

- Muy similar al verbo en `git`, osea "empujar" más propiedades al `array` previamente creado y que quizás contenga más datos (o esté vacío)

- Para esto no se usa `const` sino que solo el `identificador` del `array` por ejemplo `fz3r0_array` seguido de `.` y `push`, donte dentro se contendrán los nuevos `datos` o `elementos` 

- Ejemplo:

```javascript
    // Hago "push" a nuevos datos o elementos hacia el "array"

f0_array.push(12345, 'push cosas al array 1', f0_objeto.numero)

f0_array_2.push("push al array 2: Los push también están en corto!", 3.1416, "Solo es echarle más cosas a la bolsa del mandado")

    // Mandar llamar a los 2 array que acabo de crear "f0_array", "f0_array_2" a imprimir a consola

console.log(f0_array)

console.log(f0_array_2)
```

- Si lo vuelvo a ejecutar:

- ![image](https://user-images.githubusercontent.com/94720207/170586274-2d9863f8-deb4-4ac3-a27d-dc3b4e722dbc.png)

## Operadores Matemáticos en Javascript 

- [Javascript Operators](https://www.w3schools.com/js/js_operators.asp)

---

### JavaScript Arithmetic Operators

| **Operator** | **Description **              |
|--------------|-------------------------------|
| +            | Addition                      |
| -            | Subtraction                   |
| *            | Multiplication                |
| **           | Exponentiation (ES2016)       |
| /            | Division                      |
| %            | Modulus (Division Remainder)  |
| ++           | Increment                     |
| --           | Decrement                     |

- Ejemplo 

```js
const suma = 1 + 2
const restar = 2 - 1
const dividir = 10 / 5
const exponente = 10 ** 2

    // El modulus/modulo: toma los 2 número que le indiquemos, después los divide, pero, REGRESA EL VALOR QUE SOBRA
    
        // Ejemplo:  10 % 3   --   10 / 3 = 9 (10 entre 3 igual a 9)... sobra << 1 >> Ese es el modulus!!! ;) 

const modulo = 10 % 3

        // Incremento o decremento: Toma un valor, por ejemplo a "f0_num" le daré el valor "5". 
	
	                         // A ese valor yo le quiero incrementar << +1 >> de una manera más "rápida"
				    
				 // Entonces escribo:   x_num = (5)   >>>   x_num++    >>>    (6)    >>>    x_num++    >>>    (7)
				 
    // Valor "base" = 5

const f0_num = 5

    // "++" a la variable = 5 + 5

f0_num++

    // imprime el resultado:

console.log(f0_num)
```

- ![image](https://user-images.githubusercontent.com/94720207/170591780-66317846-ce4a-421e-a34a-c9e4f6f98af2.png)

- **OJITO CON EL ERROR!!!**

    -  **`const` NO PERMITE SER MODIFICADO, ESA ES SU DIFERENCIA CON `let`**

- Usando exactamente el mismo ejemplo pero usando `let` para definir la `variable`  

```js
let sumar = 1 + 2
let restar = 2 - 1
let dividir = 10 / 5
let exponente = 10 ** 2

    // El modulus/modulo: toma los 2 número que le indiquemos, después los divide, pero, REGRESA EL VALOR QUE SOBRA
    
        // Ejemplo:  10 % 3   --   10 / 3 = 9 (10 entre 3 igual a 9)... sobra << 1 >> Ese es el modulus!!! ;) 

let modulo = 10 % 3

        // Incremento o decremento: Toma un valor, por ejemplo a "f0_num" le daré el valor "5". 
	
	                         // A ese valor yo le quiero incrementar << +1 >> de una manera más "rápida"
				    
				 // Entonces escribo:   x_num = (5)   >>>   x_num++    >>>    (6)    >>>    x_num++    >>>    (7)
				 
    // Valor "base" = 5

let f0_num_incremento = 5

    // "++" a la variable = 5 + 1

f0_num_incremento++

    // imprime el resultado: (resultado: 5 + 1 = 6) 

// Imprimir resultados a consola:

console.log("")
console.log("RESULTADOS fz3r0:")
console.log("")
console.log("suma: ", sumar)
console.log("resta: ", restar)
console.log("dividir: ", dividir)
console.log("exponente: ", exponente)
console.log("modulo: ", modulo)
console.log("incremento: ", f0_num_incremento)

    // "++" a la variable = 6 + 1

f0_num_incremento++

console.log("incremento: ", f0_num_incremento)

    // "++" a la variable = 7 + 1

f0_num_incremento++

console.log("incremento: ", f0_num_incremento)

    // "++" a la variable = 8 + 1

f0_num_incremento++

console.log("incremento: ", f0_num_incremento)

    // "++" a la variable = 9 + 1 + 1 + 1 + 1 + 1 + 1 + 1

f0_num_incremento++
f0_num_incremento++
f0_num_incremento++
f0_num_incremento++
f0_num_incremento++
f0_num_incremento++
f0_num_incremento++

console.log("hyper incremento '++'!!! ", f0_num_incremento)

// "--" decremento! lo mismo pero resntando << -1 >> cada vez. 

f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--
f0_num_incremento--

console.log("decremento (-10 en total) también se puede con: '--'", f0_num_incremento)
```

- ![image](https://user-images.githubusercontent.com/94720207/170594347-4c9d9944-495f-449d-839c-61c075fda8d0.png)

---

### JavaScript Assignment Operators

| **Operator** | **Example** | **Same As**  |
|--------------|-------------|--------------|
| =            | x = y       | x = y        |
| +=           | x += y      | x = x + y    |
| -=           | x -= y      | x = x - y    |
| *=           | x *= y      | x = x * y    |
| /=           | x /= y      | x = x / y    |
| %=           | x %= y      | x = x % y    |
| **=          | x **= y     | x = x ** y   |

- **Nos permiten poder realizar una operación matemática sobre el mismo número que hemos definido y cambiar inmediatamente su valor.** 

- Por ejemplo:

    - Un ejemplo sencillo es tomar el `++` del capítulo pasado, ahí el incremento era forzosamente << +1 >> 
    
    - En este caso yo puedo tomar un `+=` y ponerle un valor:
    
        - `f0_num_original = 10`  >>>> `f0_num_original += 3` >>>> **`f0_num_original = 13`**

```js
    // Usando operando "=+""

console.log(); 

let f0_num_original = 10

console.log("Número original:      ", f0_num_original); 

console.log(); 

f0_num_original += 3

console.log("Usando operador += 3: ", f0_num_original); 

f0_num_original += 3

console.log("Usando operador += 3: ", f0_num_original); 

f0_num_original += 3

console.log("Usando operador += 3: ", f0_num_original); 

f0_num_original += 3

console.log("Usando operador += 3: ", f0_num_original); 

f0_num_original += 3

console.log("Usando operador += 3: ", f0_num_original); 

f0_num_original += 3
```

- ![image](https://user-images.githubusercontent.com/94720207/170597025-3238a466-48c4-4e06-b090-4897a2567e40.png)

```js
    // Usando los demás operadores

console.log(); 

let f0_num_original = 10

console.log("Número original:      ", f0_num_original); 

console.log(); 

f0_num_original -= 3

console.log("Usando operador -= 3: ", f0_num_original); 

f0_num_original += 3

console.log("Usando operador += 3: ", f0_num_original); 

f0_num_original *= 3

console.log("Usando operador *= 3: ", f0_num_original); 

f0_num_original /= 3

console.log("Usando operador /= 3: ", f0_num_original); 
```

- ![image](https://user-images.githubusercontent.com/94720207/170598723-c7f91644-2b70-45cd-853f-8f5da204f6a7.png)

---

### JavaScript Comparison Operators

| **Operator** | **Description**                    |
|--------------|------------------------------------|
| ==           | equal to                           |
| ===          | equal value and equal type         |
| !=           | not equal                          |
| !==          | not equal value or not equal type  |
| >            | greater than                       |
| <            | less than                          |
| >=           | greater than or equal to           |
| <=           | less than or equal to              |
| ?            | ternary operator                   |

Ejemplo:

```js
    // El operador "===" Es estricto, forzosamente compara un valor y debe ser idéntico. 
    
        // Número original = << 5 >>, a ese "5" lo comparo con un "6" y pregunto:
        // Acaso ese 5 es igual a 6, Oh! señor Don Javascript?
        // A lo cual el viejo "js" nos responderá con un: TRUE or FALSE

let f0_resultado1 = 5 === 6

console.log();	
console.log("Señor Don Javascript, es acaso 5 igual a 6? (usando ===)"); 
console.log();	
console.log("js responde: ", f0_resultado1);

f0_resultado1 = 5 === 5	

console.log();	
console.log();	
console.log("Señor Don Javascript, es acaso 5 igual a 5? (usando ===)"); 
console.log();	
console.log("js responde: ", f0_resultado1);


    // Ahora, si utilizo "==" también me dará 5... ¡¿pero por que existen 2 para lo mismo?!
    // No!!! uno compara VALOR y TIPO (5, es un número entero)
    
    // Pero también podría poner un 5 con string, solo lo debo poner dentro de ""
    
    // Así que no es lo mismo comparar << 5 === 5 >> con << 5 === "5" >> 

f0_resultado1 = 5 === '5'	

console.log();	
console.log();	
console.log("pregunta 1: Señor Don Javascript, es acaso 5 igual a '5'? (usando ===)"); 
console.log();	
console.log("js responde: ", f0_resultado1); 

f0_resultado1 = 5 == '5'	

console.log();	
console.log();	
console.log("pregunta 2: Señor Don Javascript, es acaso 5 igual a '5'? (usando ==)"); 
console.log();	
console.log("js responde: ", f0_resultado1); 
```

![image](https://user-images.githubusercontent.com/94720207/170603660-dcb0feff-73e3-4729-a65a-7c6325f3a2e5.png)

- **Como nos podemos dar cuenta el Señor Javascript puede comparar `strings` con `numbers`, y si usamos `==` encuentra una relación de valor, aunque no de tipo. (una aberración en otros lenguajes), _welcome to javascript son!_**

- Esto es permitido en `js` ya que aveces es necesario un tipo de comparación que no sea tan estricta. 

    - Otros ejemplos de operadores de comparación:

```js
    // Otros ejemplos de operadores de comparación:
    
let f0_resultado1 = 10

console.log();
console.log("El número original es ", f0_resultado1);
console.log();

f0_resultado1 = 10 < 20

console.log();	
console.log("Señor Don Javascript, es acaso 10 MENOR a 20? (usando <)"); 
console.log();	
console.log("js responde: ", f0_resultado1);

f0_resultado1 = 10 > 20

console.log();	
console.log("Señor Don Javascript, es acaso 10 MAYOR a 20? (usando >)"); 
console.log();	
console.log("js responde: ", f0_resultado1);

f0_resultado1 = 10 >= 100

console.log();	
console.log("Señor Don Javascript, es acaso 10 MAYOR O IGUAL a 100? (usando >=)"); 
console.log();	
console.log("js responde: ", f0_resultado1);

f0_resultado1 = 10 <= 100

console.log();	
console.log("Señor Don Javascript, es acaso 10 MENOR O IGUAL a 100? (usando <=)"); 
console.log();	
console.log("js responde: ", f0_resultado1);
```

- ![image](https://user-images.githubusercontent.com/94720207/170604779-258246aa-c85b-442e-b6c2-7729bc86666e.png)

---

### JavaScript Logical Operators

| **Operator** | **Description**  |
|--------------|------------------|
| &&           | logical and      |
| II           | logical or       |
| !            | logical not      |

- Determina la lógica entre variables o valores.

- Logical operators are used to determine the logic between variables or values.

    - Por ejemplo:

```js
                                  /* || (or) */

console.log()

    // Or - El operador "||" lo primero que hará es evaluar el primer valor con el que se encuentre o retorne el script en TRUE
    
         // Por ejemplo, si yo tengo un FALSE pero también un TRUE, el resultado que dará "||" (or) será = TRUE

         // La única manera que un "||" regrese un valor de "false", es que ambos valores sean "False"
	    
const f0_resultado_or1 = false || true

console.log('El resultado entre "false || true" es : ', f0_resultado_or1);

const f0_resultado_or2 = true || false

console.log('El resultado entre "true || false" es : ', f0_resultado_or2);

const f0_resultado_or3 = true || true

console.log('El resultado entre "true || true" es  : ', f0_resultado_or3);

const f0_resultado_or4 = false || false

console.log('El resultado entre "false || false" es: ', f0_resultado_or4, '<<< único false');

                                  /* && (and) */

console.log()

    // Or - El operador "&&" (and) es similar a los resultados con "or", también recibe esos 2 valores

         // Pero! "&&" a diferencia, siempre buscará el primer FALSE
    
         // Por ejemplo, si yo tengo un FALSE pero también un TRUE, el resultado que dará "&&" (and) será = FALSE

         // La única manera que un "&&" regrese un valor de "true", es que ambos valores sean "True"
	    
const f0_resultado_and1 = false && true

console.log('El resultado entre "false && true" es : ', f0_resultado_and1);

const f0_resultado_and2 = true && false

console.log('El resultado entre "true && false" es : ', f0_resultado_and2);

const f0_resultado_and3 = true && true

console.log('El resultado entre "true && true" es  : ', f0_resultado_and3, '<<< único true');

const f0_resultado_and4 = false && false

console.log('El resultado entre "false && false" es: ', f0_resultado_and4);

const f0_resultado_and5 = true && true && true && true && true && false

console.log()
console.log('Nota: en caso que haya chingomil true, pero solo un false, el resultado será:', f0_resultado_and5);

                                  /* ! (not) */

console.log()

    // Or - El operador "not" va "a dar vuelta" el valor que este tiene

         // Es decir, tendrá el valor completamente opuesto en caso que sea boolean (1 y 0) 
    
         // Por ejemplo:  Si yo tengo un valor X = !true  >> el resultado será false

                       // Si yo tengo un valor X = !false  >> el resultado será true 

const f0_resultado_not1 = !true

console.log('El resultado de !true : ', f0_resultado_not1);

const f0_resultado_not2 = !false

console.log('El resultado de !false : ', f0_resultado_not2);
```

- ![image](https://user-images.githubusercontent.com/94720207/170729674-9bdcbde4-8110-4d11-b5b2-138bb124543e.png)

- **NOTA: `js` y sus operadores de `||` y `&&`  funcionan con `short circuit evaluation`, lo que hace básicamente es al encontrar el primer resultado que busca, detener la demás operación.** 

- **NOTA SUPER IMPORTANTE: STRINGS, OBJETOS, NÚMEROS TODOS SON `TRUE` EXCEPTO EL `0`.** 

- **EL `0` ES EL ÚNICO `FALSE`.** (Por eso en el siguiente ejemplo puedo usar un string como TRUE pero solo un "0" como false)

    - Por ejemplo:

        - La única manera que un "||" regrese un valor de "False", es que ambos valores sean "False"
            - Entonces: `false || false || false || "string, objeto, número (excepto 0), o true"` **`<--- stop!!!`**
            - Entonces: `false || false || false || true` **`<--- stop!!!`** 

        - La única manera que un "&&" regrese un valor de "True", es que ambos valores sean "True"
            - Entonces: `true && true && true && 0` **`<--- stop!!!`** 
            - Entonces: `true && true && true && false` **`<--- stop!!!`** 

- Es decir, en el caso de `||` si encuentra el primer `FALSE` después de `5 TRUE` en una lista de `3000 TRUE`, la búsqueda se detiene en `5 TRUE`.

## Conditional Statements / Control de Flujo 

- Nos permite realizar iteraciones o también evaluar condiciones:

    - Yo puedo evaluar una condición en caso que sea TRUE or FALSE, puedo realizar o saltarme esa lógica.
    
    - El clásico `if`... `If 10 == 10 > then: "si es 10" > else: "no es 10"`  

## If / If Else / Else If

- **[If / If Else / Else If](https://www.w3schools.com/js/js_if_else.asp)**

## If

- Ejemplo básico de un `if`:

```js
    // If vacío en su estado puro:
    
if (true){}


if (false){}
    
    // instrucción: << IF >> en su estado puro

    // Sin comparar nada, solo como un demo "true" o "false"

        // En caso de "true" imprimirá la instrucción:

if (true){

	console.log('Fz3r0: Estoy dentro de un << IF >>')

}

        // En caso de "false" se brincará la instrucción y no imprimirá nada:

if (false){

	console.log('Fz3r0: Estoy dentro de un << IF >>')

}
```

- ![image](https://user-images.githubusercontent.com/94720207/170620813-110788d7-8c41-4fd2-bf13-036a96a1519a.png)

- También se pueden recibir otros tipos de `operadores lógicos`:

```js
    // If evaluando la condición: >>>>  solo números entre 5 y 18

const f0_edad = 10

if (f0_edad > 5 && f0_edad < 18) {

   console.log('Estoy dentro de un if! El if solicita una edad entre 5 y 18 años, yo tengo 10!!! hurra!!!');
   
}
```

- ![image](https://user-images.githubusercontent.com/94720207/170622208-f78d7c0e-8a3c-4230-add5-070f1898763f.png)

- Si quiero agregar el `else` se realiza de la siguiente manera: 

## Else 

- Un ejemplo usando el mismo código del if, pero ahora será un viejo cascarrabias el que trate de pasar por el programa:

```js
    // If-Else vacío en su estado puro:
    
if (true){}

else {}


if (false){}

else {}

    // If evaluando la condición: >>>>  solo números entre 5 y 18

const f0_edad = 49

if (f0_edad > 5 && f0_edad < 18) {

   console.log('Estoy dentro de un if! El if solicita una edad entre 5 y 18 años, yo tengo 10!!! hurra!!!');
   
} else {

    console.log('Estoy dentro de un if! El if solicita una edad entre 5 y 18 años, yo tengo 49!!! soy un viejo!!! D:');

}
```

- ![image](https://user-images.githubusercontent.com/94720207/170622937-9873943c-2884-41df-86d3-15be9e098b40.png)

- Nota: Los `if` o `else` solo aplica para lo que esté dentro de los mismos bloques `if` o `else`... obviamente...

## While

- `While` se quedará iterando (o haciendo loops) de manera infinita a menos que le indiquemos lo contrario.

    - Por ejemplo:

        - "Mientras no sean las 8am, no abrirá la cafetería"

        - "Mientras sean entre 8am y 16pm, la cafetería permanecerá abierta" 

```js
    // While vacío
    
while (1 < 100) {}   

    // While evaluando la condición: >>>>  La cafetería abre hasta las 8am

let f0_hora = 5

while (f0_hora < 8) {

	console.log('Aún no es hora de abrir, son las: ', f0_hora);

	f0_hora++

}

console.log('El restaurante está abierto! Son las: ', f0_hora);
```

- ![image](https://user-images.githubusercontent.com/94720207/170624046-8e94e754-e58e-4a87-8999-1c4197e5ce76.png)

- Por ejemplo:

    - "Mientras sean entre 8am y 16pm, la cafetería permanecerá abierta" 

```js
    // While evaluando la condición: >>>>  La cafetería está abierta entre 8am y 16pm

    // Detalle jocoso: Debo poner <= 15, ya que por lógica: si el restaurante cierra a las 16, 15 es la última hora que pasará abierto ;) ... ++1 16, en 16 cierra

let f0_hora = 0

while (f0_hora < 8) {

	console.log('Son las: ', f0_hora, ' Y estoy en el primer while, cuando den las 8, entro al segundo while');

	f0_hora++

}

console.log('------ Cambio de while 1 a while 2!!!, son las: ', f0_hora);

while (f0_hora >= 8 && f0_hora <= 15) {

	console.log('Cafatería abierta, son las: ', f0_hora);

	f0_hora++

}

console.log('El restaurante ha cerrado! son las: ', f0_hora);

console.log('Nos vemos mañana en cafetería Fz3r0 :D');
```
- ![image](https://user-images.githubusercontent.com/94720207/170626161-7b9047dc-55cb-4990-9c26-badf49cb2bfc.png)

- **NOTA: Las evaluaciones pueden ser de distintos tipos, como `true` o `false`**

## Switch

[JavaScript Switch Statement](https://www.w3schools.com/js/js_switch.asp)

- The switch statement is used to perform different actions based on different conditions.

- **Use the switch statement to select one of many code blocks to be executed.**

    - Ejemplo:

```js
let f0_expression1 = 1
console.log()
console.log('Caso 1:')

    // Switch vacío:
    
        // Nota: OJO! el default ya no necesita "break;"

switch(f0_expression1) {

  case (1):
    // code block 1
    break;
    
  case (2):
    // code block 2
    break;
    
  default:
    // code block 3 (default) 
    
}

    // Ejemplo jocoso de "switch"
    
    // Así de fácil es el switch, se espera algún dato, como las compuertas de un juego de feria, donde está la bolita?!
    
    // Cada switch tiene un valor, dato, etc. Si son iguales, ese switch entra:

let f0_expression2 = "cualquier otra cosa, o valor, o número"
console.log()

switch(f0_expression2) {

  case ("A"):
    // code block 1
    console.log('Has seleccionado: ', f0_expression2, '>>> Aquí no está la bolita :(, pero hay bomba apestosa');
    break;
    
  case ("B"):
    console.log('Has seleccionado: ', f0_expression2, '>>> Aquí está la bolita!!! :D llamen a los golpeadores y huyan!');  
    break;
 
  case ("C"):
    console.log('Has seleccionado: ', f0_expression2, '>>> Aquí no está la bolita :(, pero hay un chicle laxante');  
    break;

  default:
    console.log('Has seleccionado: ', f0_expression2, '>>> No has seleccionado ninguna de las 3 opciones!!! Golpeadores!!! a el!!!');
}

console.log()
console.log()
console.log('Caso 2:')

    // En cambio, si escribo cualquier otra cosa que no corresponda con nada, irá al default:

let f0_expression3 = "666"
console.log()

switch(f0_expression3) {

  case ("A"):
    // code block 1
    console.log('Has seleccionado: ', f0_expression3, '>>> Aquí no está la bolita :(, pero hay bomba apestosa');
    break;
    
  case ("B"):
    console.log('Has seleccionado: ', f0_expression3, '>>> Aquí está la bolita!!! :D llamen a los golpeadores y huyan!');  
    break;
 
  case ("C"):
    console.log('Has seleccionado: ', f0_expression3, '>>> Aquí no está la bolita :(, pero hay un chicle laxante');  
    break;

  default:
    console.log('Has seleccionado: ', f0_expression3, '>>> No has seleccionado ninguna de las 3 opciones!!! Golpeadores!!! a el!!!');
}
```

- ![image](https://user-images.githubusercontent.com/94720207/170776822-c3a9c484-6631-400c-924d-6396d71595ce.png)

## For

- **[The For Loop](https://www.w3schools.com/js/js_loop_for.asp)**

- The for loop has the following syntax:

```js
    // Ejemplo puro:

for (statement 1; statement 2; statement 3) {
  // code block to be executed
} 
```

- `Statement 1` is executed `one time`** before the execution of the code block.**

- `Statement 2` defines **the condition for executing the code block.**

- `Statement 3` is executed `every time` **after the code block has been executed.**

    - **El `for` es similar a `while`, nos permite iteral o permanecer dentro de un `loop` HASTA QUE SE CUMPLA UNA INSTRUCCIÓN.**


| **Instrucción** | **Resultado** |
|-----------------|---------------|
| **SINTAXIS FOR**| `for (statement 1; statement 2; statement 3)`
| **EJEMPLO FOR:**| `for (let i = 0; i < 10; )`
| for             | instrucción for             |
| ()              | Dentro de paréntesis van las **3 INSTRUCCIONES** que debe seguir `for` |
| let i = 0       | **Instrucción-1**: **EL VALOR DE LA VARIABLE** que vamos a iterar <br> (En este caso `i` vale `0`) |
| i <          | **Instrucción-2**: La condición que la variable `i` debe de cumplir **PARA SEGUIRSE EJECUTANDO** <br> (En este caso que `i` sea menor a `10`, es decir: `máximo 9`) |
| i++ | **Instrucción-3:** **Que se realice ESTA operación HASTA QUE SE CUMPLA LA CONDICIÓN.** <br> En este caso, la operación es sumar "+1" <br> <br> (Después el loop termina y **regresa de nuevo a la INSTRUCCIÓN 2**)|
|{}| Dentro de las llaves va el code block. <br> En este caso una consola imprimiendo el valor de `i` cada que pasa por la comparación de la condición. 

- Ejemplo:

```js
for (let i = 0; i <; i++) {}
```

- Ejemplo completo:

```js
    // Ejemplo for:

for (let i = 0; i < 10; i++) {
	console.log('El valor de "i" es: ', i);
}

// Fuera del for... lo que sigue del programa:

console.log();
console.log('Se ha acabado el loop del for, aquí "afuera" ya no funciona mi variable "i"');
console.log('Si yo utilizara la "i" acá afuera, marcaría error. Solo funciona para ese "for"');
console.log();
console.log('HINT: "i" casi siempre se usa para el "for", solo porque se puede repetir...');
console.log('      y se hace costumbre siempre usarla, ya que "i" recuerda a uno "instrucción" :P');
```

- ![image](https://user-images.githubusercontent.com/94720207/170785989-da8269df-d7fa-4758-92c9-edeb66947683.png)

## Accediendo a los elementos de un arreglo

- Se puede acceder a cada uno de los `elementos` de un `array` usando un `for`.

- Primero declararé un arreglo que contenga algunos elementos aleatorios solo para probar. 

- Despúes haré el codeblock del `for` para acceder a dichos `elementos`.

    - **IMPORTANTE: En `js` hay una propiedad que tienen TODOS los `array` que es el `lenght`**
        
	- `lenght` permite obtener el "largo" de un `array`
        
	- Es decir, contar la cantidad de elementos!!! fácil!!!
	    - Por ejemplo: un arreglo `[1, 2, 3, 4, 5]` tiene un `leght` de `5`
	    - Por ejemplo: un arreglo `[a, b, c]` tiene un `leght` de `3`
	    - Por ejemplo: un arreglo `['hola amigos', 666, user123, 'p@ssw00rd']` tiene un `lenght` de `4`

- El `lenght` es importante ya que permite acceder a los `index` de cada uno de los `elementos` del `array`

```js
console.log()

        // Accediendo a los elementos sin "for", directo de la consola like a boss:

const numeros_1 = [1, 2, 3, 4, 5] 

console.log('Primer ejemplo, usando [0]:   ', numeros_1[0]);
console.log();

        // Así de fácil mostré todos los elementos del array, ya que [] significa TODO dentro del array
	
	    // Pero, que pasa si pongo varios???

console.log('Segundo ejemplo, usando [0, 3, 4] (si pongo varios toma el último osea 4(5)) :   ', numeros_1[0, 3, 4]);
console.log('Tercer ejemplo, usando [0, 3] (si pongo varios toma el último osea 3(4))     :   ', numeros_1[0, 3]);	
console.log();

        // Los índices en js como todo en este mundo, se empieza a contar de 0, es por eso que 3 es 4, etc...

console.log();

    // La misma lógica utiliza el for para sacar esos elementos:

    // Selecciona un número del Index del array y listo! sabrá que hay dentro de ese elemento.  

        // Ejempplo: Accediendo a los elementos de un arreglo:

        // Declaración del Array:
    
const numeros = [1, 2, 3, 'La bolita', 5, 'otra variable', 7, 8, 'un objeto!']  

        // Loop for: en este caso la iteración (instrucción2) "numeros.lenght[i]" se está comaprando con su lenghtr mismo total (oseea 10)

for (let i = 0; i < numeros.length; i++) {
	console.log('Estoy dentro del for, "i" va contando el length del array y va en el elemento:  ', i);
}	

console.log();
console.log('Estoy fuera del for');
```

- ![image](https://user-images.githubusercontent.com/94720207/170794789-5ca9dce5-e1a3-4af1-bee1-56b8fa0c541d.png)


## Funciones en Javascript

- **[Javascript Functions](https://www.w3schools.com/js/js_functions.asp)**

    - A JavaScript function is a block of code designed to perform a particular task.

    - A JavaScript function is executed when "something" invokes it (calls it).  
    
    - **Nota: Como las funciones en python y demás**
    
- **Las funciones en `js` se pueden escribir de 2 formas:**

1. Forma 1:

```js
funtion f0_funcion_1() {
    // code block
}
```

2. Forma 2

```js
funtion f0_funcion_1() {
    // code block
}
```

- **Ejemplo de Forma 1:**

```js
console.log()

    // Ejemplo de function con un for
    
    // Este "for" originalmente cuanta el lenght de la constante "f0_numeros_const_10"
    
    // Pero qué tal que yo tengo otra constante que se llame "f0_palabras_1"? y tenga strings
    
    // O que sea de "f0_usuarios", o cualquier otra cosa que hayamos creado...
    
        // Y TODAS ESAS QUIERO CONTAR SUS ELEMENTOS CON UN FOR....
    
            // En este caso el próximo for no serviría de nada ya que solo fucniona con "f0_numeros_const_10":



    // FOR USANDO "f0_numeros_const_10.length" en su segunda "instrucción" 

const f0_numeros_const_10 = [1, 2, 3, 4, 'cinco :3', 6, 7, 8, 9, 'diez :D']

for (let i = 0; i < f0_numeros_const_10.length; i++) {
	console.log('Estoy dentro del "for" que usa la constante "f0_numeros_const_10".... Contando i:  ', i);
}	

console.log()
console.log('Estoy fuera del "for" que usa "f0_numeros_const_10.length"');
console.log()



    // Para poder "reutilizar" ese pedazo de código nececisto "meterlo" en una FUNCIÓN!!!!	

    // Cuando se mande llamar a "f0_iterar_lengths", se ejecutará el código dentro de {}


        // 1. Voy a repetir exactamente el for de arriba dentro de los {} (incluyendo variables y todo)

        // 2. Revisar que esté bien identado todo!

function f0_iterar_lengths() {

	// Code Block:

	const f0_numeros_const_666 = [1, 2, 3, 4, 'cinco :3', 666, 7, 8, 9, 'diez :D']

	for (let i = 0; i < f0_numeros_const_666.length; i++) {
	console.log('Esta ya es la FUNCION ;).... Contando i:  ', i);
	}	

	console.log()
	console.log('Estoy fuera del "for" DE LA FUNCION"');
	console.log()
	console.log('Ojo: fuera del for, pero sigo dentro de la "función" :o AH PERRO!');
	console.log()
	console.log()

}     

console.log()
console.log('Ya está creada la "f0_numeros_const_666.length", obviamente nunca se vió en consola');
console.log()
console.log('Pero ahora la mandaré a llamar 2 veces consecutivas con la función "f0_iterar_lengths":');
console.log()
console.log()
console.log()
console.log()
console.log('FUNCIÓN "f0_iterar_lengths" YO TE ELIJO 2 VECES!!!:');
console.log()
console.log()
console.log()
console.log()


    // Así de sencillo se manda llamar de la forma más básica: 

f0_iterar_lengths()
f0_iterar_lengths()

console.log('__________________________________________________________________________')
console.log('Acaba el programa, esta linea es un "adiós mundo"')
```

- ![image](https://user-images.githubusercontent.com/94720207/170804364-34b1af05-f883-4d97-b403-6e1bf5691011.png)

- Ahora ya logré mandar llamar la función 2 veces, pero ahora quiero que esa función `f0_iterar_lengths()` para contar.

- Por el momento solo mandé llamar a la función 2 veces con el comando `f0_iterar_lengths()` pero aún no le ponemos dentro los **`ARGUMENTOS`**

    - Una `function` recibe `arguments` que permiten cambiar el contenido de la `function` de forma **`dinámica`** de lo que está dentro de `{}`
    
    - Es decir: **El valor que va a tener un `argumento` va a ser iguál al valor que estará dentro de `()` cuando lo mandemos llamar.**
    
        - Por ejemplo:
    
```js
    // Esta vez dentro de los "()" irán los argumentos "f0_arg_1"

    // En este caso "f0_arg_1" quedó definido también como una variable, pero no tenemos idea cuanto vale ARG1

    // Es decir >>>> FUNCION1 >>>> VA A ITERAR >>>> EL ARGUMENTO1 

        // Donde ese ARGUMENTO1 podrá ser modifcado a placer así como se repitió la función 2 veces en el ejemplo anterior

           
           // SUPER MEGA ARCHI OJOOOOO!!!!!!!!!!!!!!!!!! <------------------------

           // CUANDO F0_ARG_1 ESTÁ DECLARANDOSE EN LA FUNCIÓN COMO AQUÍ ABAJO SE LE LLAMA "ARGUMENTO"
           // PERO! CUANDO SE USA YA FUERA DE LA FUNCIÓN CUANDO SE PASA EL VALOR (MÁS ADELANTE LEER EL OJO2!) 
           // SE CONOCE COMO:       "PARÁMETRO"


function f0_iterar_lengths(f0_arg_1) {

	// Code Block:

	const f0_numeros_const = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

	// Ahora los argumentos irán en lugar de la variable o constante que usabamos antes, y usaré "f0_arg_1"

	for (let i = 0; i < f0_arg_1.length; i++) {
	console.log()
	console.log('Por ejemplo, esta función sirve para contar lenghts de arrays!!! mira como cuenta ----->>>>  ', (f0_arg_1[i]));
	}	
}   

    // Aquí ya acaba la función y podemos empezarla a llamar durante el código del programa

    // Por ejemplo, crearé los siguientes 2 arrays los cuales los quiero contar!

    // En lugar de hacer 2 for mandaré llamar a la función

const f0_numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
const f0_nombres = ['abc', 'fff', 'Vegeta', 'Mr Popo', 'Goku']
const f0_user_dt = ['User1', 'Password', 'Address', 'Type of Account', 'Credit Card']


        // OJITO!!! AQUÍ ES DONDE VA EL "PARÁMETRO" DEL QUE HABLABA ANTES!!! .... (EL QUE EN LA FUNCIÓN SE LLAMA "ARGUMENTO")

	// Ahora los argumentos irán en lugar de la variable o constante que usabamos antes 

console.log() 

f0_iterar_lengths(f0_numeros)  // <-- contando el array 1

console.log() 

f0_iterar_lengths(f0_nombres)  // <-- contando el array 1

console.log() 

f0_iterar_lengths(f0_user_dt)  // <-- contando el array 3

console.log() 
```

- ![image](https://user-images.githubusercontent.com/94720207/170806829-d2d899f8-9c22-4dcd-900c-9d7e422ae1a7.png)

## Más funciones en Javascript (un número más otro)

- Apenas el bloque pasado es una mini-embarrada de lo que realmente son las `funciones` en `js`

- En este caso presentaré otro poco más en cuanto a `funciones`

    - Ejemplo de función `f0_suma`

```js
console.log()

// Función suma

    // Esta función tendrá como objetivo sumar 2 números diferentes ARGUMENTOS(futuros parámetros): "A" + "B"

    // Después imprimirá el resultado de la suma de A + B

function f0_suma (a, b) {
	console.log(a + b);
}


    // Ahora mandaré llamar la función, tomando ambos parámetros de A y B

    // Nota: recordar que no necesita console log ni nada, solo se manda llamar la FUNCIÓN con sus PARÁMETROS que utilizará(antiguos argumentos)

        // En este ejemplo usaré los PARÁMETROS de 1 y 2

            // Es decir, la función "suma" que sirve para sumar 2 números sumará: 1 y 2 >>> 1 + 2 = 3

f0_suma(1, 2); 
f0_suma(2, 2); 
f0_suma(10, 10); 
f0_suma(100, 250); 
```

- ![image](https://user-images.githubusercontent.com/94720207/170807770-00789ded-d2c8-4f1c-aad8-5821a642b3aa.png)

- Ahora, el único problema aquí es que para mandar llamar a esa función no he usado "console" y yo lo quiero en una variable para console, entonces solo debo desclararlo en una variable:

```js
console.log()

// Función suma

    // Esta función tendrá como objetivo sumar 2 números diferentes ARGUMENTOS(futuros parámetros): "A" + "B"

    // Después imprimirá el resultado de la suma de A + B

function f0_suma (a, b) {
	console.log(a + b);
}


    // Ahora mandaré llamar la función, tomando ambos parámetros de A y B

    // Nota: recordar que no necesita console log ni nada, solo se manda llamar la FUNCIÓN con sus PARÁMETROS que utilizará(antiguos argumentos)

        // En este ejemplo usaré los PARÁMETROS de 1 y 2

            // Es decir, la función "suma" que sirve para sumar 2 números sumará: 1 y 2 >>> 1 + 2 = 3

f0_suma(1, 2); 
f0_suma(2, 2); 
f0_suma(10, 10); 
f0_suma(100, 250);


    //  Ahora si, pondré el resultado de alguna de esas sumas pero dentro de una variable o constante
console.log()

const Resultado_en_constante1 = f0_suma(10, 10); 
const Resultado_en_constante2 = f0_suma(100, 250);
const Resultado_en_constante3 = f0_suma(100, 250);
    
    
```

## Más funciones en Javascript - Callback

- Un `callback` es una `function` que se ejecutará al final de otra `function`

```js
console.log()

// Función suma

    // Esta función tendrá como objetivo sumar 2 números diferentes ARGUMENTOS(futuros parámetros): "A" + "B"

    // Después imprimirá el resultado de la suma de A + B

function f0_suma (a, b) {
	console.log(a + b);
}


    // Ahora mandaré llamar la función, tomando ambos parámetros de A y B

    // Nota: recordar que no necesita console log ni nada, solo se manda llamar la FUNCIÓN con sus PARÁMETROS que utilizará(antiguos argumentos)

        // En este ejemplo usaré los PARÁMETROS de 1 y 2

            // Es decir, la función "suma" que sirve para sumar 2 números sumará: 1 y 2 >>> 1 + 2 = 3

f0_suma(1, 2); 
f0_suma(2, 2);           //  <<<<    En caso de usar console.log será esto lo que regresará a consola
f0_suma(10, 10); 
f0_suma(100, 250);


    //  Ahora si, pondré el resultado de alguna de esas sumas pero dentro de una variable o constante
console.log()

const Resultado_en_constante1 = f0_suma(10000, 123423); 
const Resultado_en_constante2 = f0_suma(100000, 250234);
const Resultado_en_constante3 = f0_suma(1000000, 24442);
    

// ----------------------------------------------------------------------------------------------
//
// AHORA EXACTAMENTE LO MISMO PERO CAMBIANDO EL CONSOLE.LOG DEL FUNCTION POR UN "RETURN":
    

console.log()

// Función suma

    // Esta función tendrá como objetivo sumar 2 números diferentes ARGUMENTOS(futuros parámetros): "A" + "B"

    // Después imprimirá el resultado de la suma de A + B

function f0_suma_2 (a, b) {
	return(a + b);
}


    // Ahora mandaré llamar la función, tomando ambos parámetros de A y B

    // Nota: recordar que no necesita console log ni nada, solo se manda llamar la FUNCIÓN con sus PARÁMETROS que utilizará(antiguos argumentos)

        // En este ejemplo usaré los PARÁMETROS de 1 y 2

            // Es decir, la función "suma" que sirve para sumar 2 números sumará: 1 y 2 >>> 1 + 2 = 3

f0_suma_2(1, 2); 
f0_suma_2(2, 2); 
f0_suma_2(10, 10); 
f0_suma_2(100, 250);


    //  Ahora si, pondré el resultado de alguna de esas sumas pero dentro de una variable o constante
console.log()

const Resultado_en_constante1_2 = f0_suma_2(10000, 123423); 
const Resultado_en_constante2_2 = f0_suma_2(100000, 250234);     //  <<<<    En caso de usar console.log será esto lo que regresará a consola
const Resultado_en_constante3_2 = f0_suma_2(1000000, 24442);    
```

- ![image](https://user-images.githubusercontent.com/94720207/170809263-9272ea99-1787-401b-9cff-fafc9ff53234.png)







































