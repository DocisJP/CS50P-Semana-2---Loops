# Vanity Plates

En Massachusetts, hogar de la Universidad de Harvard, es posible solicitar una placa de matrícula personalizada para tu auto, con tu elección de letras y números en lugar de aleatorios. Sin embargo, entre los requisitos, se encuentran:

"Todas las placas personalizadas deben comenzar con al menos dos letras."
"... las placas personalizadas pueden contener un máximo de 6 caracteres (letras o números) y un mínimo de 2 caracteres."
"Los números no se pueden usar en el medio de una placa; deben estar al final. Por ejemplo, AAA222 sería una placa personalizada aceptable; AAA22A no sería aceptable. El primer número utilizado no puede ser un '0'."
"No se permiten puntos, espacios ni signos de puntuación."
En plates.py, implementa un programa que solicite al usuario una placa personalizada y luego muestre "Valid" si cumple con todos los requisitos o "Invalid" si no los cumple. Supón que cualquier letra en la entrada del usuario estará en mayúsculas. Estructura tu programa según lo siguiente, donde `is_valid` devuelve True si s cumple con todos los requisitos y False si no los cumple. Supón que s será una cadena (str). Puedes implementar funciones adicionales para que `is_valid` las llame (por ejemplo, una función por requisito).

```python
def main():
    plate = input("Plate: ")
    if is_valid(plate):
        print("Valid")
    else:
        print("Invalid")


def is_valid(s):
    ...


main()
```

### Pistas

Recuerda que una cadena (str) tiene bastantes métodos, según docs.python.org/3/library/stdtypes.html#string-methods.
Al igual que una lista, una cadena es una "secuencia" (de caracteres), lo que significa que se puede "dividir" en cadenas más cortas con una sintaxis como s[i:j]. Por ejemplo, si s es "CS50", entonces s[0:2] sería "CS".

## Antes de Comenzar

Inicia sesión en cs50.dev, haz clic en tu ventana de terminal y ejecuta `cd` por sí solo. Deberías ver que el indicador de la ventana de tu terminal se asemeja a lo siguiente:

```bash
$
```

Luego ejecuta

```bash
mkdir plates
```

para crear una carpeta llamada plates en tu espacio de código.

Luego ejecuta

```bash
cd plates
```

para cambiar de directorio a esa carpeta. Ahora deberías ver el indicador de tu terminal como plates/ $. Ahora puedes ejecutar

```bash
code plates.py
```

para crear un archivo llamado plates.py donde escribirás tu programa.

## Cómo Probar

Así es como puedes probar tu código manualmente:

Ejecuta tu programa con

```bash
python plates.py
```

Escribe CS50 y presiona Enter. Tu programa debería mostrar:

```bash
Valid
```

Ejecuta tu programa con

```bash
python plates.py
```

Escribe CS05 y presiona Enter. Tu programa debería mostrar:

```bash
Invalid
```

Ejecuta tu programa con

```bash
python plates.py
```

Escribe CS50P y presiona Enter. Tu programa debería mostrar:

```bash
Invalid
```

Ejecuta tu programa con

```bash
python plates.py
```

Escribe PI3.14 y presiona Enter. Tu programa debería mostrar:

```bash
Invalid
```

Ejecuta tu programa con

```bash
python plates.py
```

Escribe H y presiona Enter. Tu programa debería mostrar:

```bash
Invalid
```

Ejecuta tu programa con

```bash
python plates.py
```

Escribe OUTATIME y presiona Enter. Tu programa debería mostrar:

```bash
Invalid
```

Puedes ejecutar lo siguiente para verificar tu código usando check50, un programa que CS50 usará para probar tu código cuando lo envíes. ¡Pero asegúrate de probarlo tú mismo también!

```bash
check50 cs50/problems/2022/python/plates
```

Las caritas verdes significan que tu programa ha pasado una prueba. Las caritas rojas indicarán que tu programa mostró algo inesperado. Visita la URL que check50 te proporciona para ver la entrada que check50 entregó a tu programa, qué salida esperaba y qué salida dio tu programa realmente.

## Cómo Enviar

En tu terminal, ejecuta lo siguiente para enviar tu trabajo.

```bash
submit50 cs50/problems/2022/python/plates
```
