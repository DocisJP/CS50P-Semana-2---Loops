# Nutrition Facts

La Administración de Alimentos y Medicamentos de los EE. UU. (FDA) ofrece carteles descargables/imprimibles que “muestran información nutricional para las 20 frutas crudas más frecuentemente consumidas ... en los Estados Unidos. Las tiendas minoristas pueden descargar los carteles, imprimirlos, exhibirlos y/o distribuirlos a los consumidores cerca de los alimentos relevantes en las tiendas.”

En un archivo llamado nutrition.py, implementa un programa que solicite a los usuarios consumidores que ingresen una fruta (sin importar mayúsculas o minúsculas) y luego muestre la cantidad de calorías en una porción de esa fruta, según el cartel de la FDA para frutas, que también está disponible como texto. Aparte de la capitalización, asume que los usuarios ingresarán las frutas exactamente como están escritas en el cartel (por ejemplo, strawberries, no strawberry). Ignora cualquier entrada que no sea una fruta.

### Pistas

En lugar de usar una condicional con 20 expresiones Booleanas, una para cada fruta, es mejor usar un dict para asociar una fruta con sus calorías.
Si k es una cadena (str) y d es un diccionario (dict), puedes verificar si k es una clave en d con un código como:

```python
if k in d:
    ...
```

Asegúrate de mostrar las calorías de la fruta, ¡no las calorías provenientes de la grasa!

## Antes de Comenzar

Inicia sesión en cs50.dev, haz clic en tu ventana de terminal y ejecuta `cd` por sí solo. Deberías ver que el indicador de la ventana de tu terminal se asemeja a lo siguiente:

```bash
$
```

Luego ejecuta

```bash
mkdir nutrition
```

para crear una carpeta llamada nutrition en tu espacio de código.

Luego ejecuta

```bash
cd nutrition
```

para cambiar de directorio a esa carpeta. Ahora deberías ver el indicador de tu terminal como nutrition/ $. Ahora puedes ejecutar

```bash
code nutrition.py
```

para crear un archivo llamado nutrition.py donde escribirás tu programa.

## Cómo Probar

Así es como puedes probar tu código manualmente:

Ejecuta tu programa con

```bash
python nutrition.py
```

Escribe Apple y presiona Enter. Tu programa debería mostrar:

```bash
Calories: 130
```

Ejecuta tu programa con

```bash
python nutrition.py
```

Escribe Avocado y presiona Enter. Tu programa debería mostrar:

```bash
Calories: 50
```

Ejecuta tu programa con

```bash
python nutrition.py
```

Escribe Sweet Cherries y presiona Enter. Tu programa debería mostrar:

```bash
Calories: 100
```

Ejecuta tu programa con

```bash
python nutrition.py
```

Escribe Tomato y presiona Enter. Tu programa no debería mostrar nada.

Asegúrate de probar otras frutas y variar el uso de mayúsculas y minúsculas en tu entrada. Tu programa debería comportarse como se espera, sin importar mayúsculas o minúsculas.

Puedes ejecutar lo siguiente para verificar tu código usando check50, un programa que CS50 usará para probar tu código cuando lo envíes. ¡Pero asegúrate de probarlo tú mismo también!

```bash
check50 cs50/problems/2022/python/nutrition
```

Las caritas verdes significan que tu programa ha pasado una prueba. Las caritas rojas indicarán que tu programa mostró algo inesperado. Visita la URL que check50 te proporciona para ver la entrada que check50 entregó a tu programa, qué salida esperaba y qué salida dio tu programa realmente.

## Cómo Enviar

En tu terminal, ejecuta lo siguiente para enviar tu trabajo.

```bash
submit50 cs50/problems/2022/python/nutrition
```
