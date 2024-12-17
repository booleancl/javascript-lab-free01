# Javascript Workshop Fundamentals

Nivel Intermedio

## Repaso de fundamentos de Javascript
  Conocer la sintáxis fundamental de Javascript en un contexto de propósito general.

## Unidades: Funciones y Promesas

### Capítulos
  - Declaración de funciones, expresión de funciones, funciones anónimas
  - Definición de un callback en Javascript
  - Modelo de programación asíncrono
  - Objecto Promise
  - Fetch

### Criterio de evaluación
  - Crea y usa funciones para dividir problemas de complejidad media.
  - Implementa funciones que utilizan callbacks para lograr un objetivo
  - Ejecuta y resuelve promesas entendiendo el flujo implementado

## Comienza el laboratorio

### Parte 1: Funciones y Callbacks

- Sigue las instrucciones contenidas [en esta página](https://javascript.boolean.cl/main/docs/01-fundamentos/) y corre los tests `01_naming.test.js`.

- Analiza los comentarios contenidos en el archivo `01_naming.js` y resuelve los ejercicios.

- Continua con los demás archivos contenidos en la carperta `functions`.

- Una vez terminado todo lo relativo a la carpeta `functions`, sube los cambios a GitHub y revisa la sección "Actions".

### Parte 2: Promesas

- Continua con los archivos contenidos en la carperta `promises` comenzando con los tests `01_promises.test.js`.

- Una vez terminado todo lo relativo a la carpeta `promises`, sube los cambios a GitHub y revisa la sección "Actions".

### Parte 3: Crea tus propias pruebas unitarias

- Corre el comando `npm run test:coverage` y analiza la situación del archivo `utils/getCountries.js` a través del archivo `coverage/index.html`. Este último lo puedes ver directo en tu navegador o usando el complemento de Visual Studio Code "Live Server".

- Escribe pruebas unitarias para la función `getCountries` en la carpeta `tests`.

- Mientras escribes las pruebas puedes usar el comando `npm test tests/getCountries.test.js`.

- Cuando ya estés seguro de la ejecución de las pruebas ejecuta `npm run test:coverage` y valida que ha aumentado la cobertura.

- Repite el proceso hasta completar la cobertura para la función.


¡Éxito!
