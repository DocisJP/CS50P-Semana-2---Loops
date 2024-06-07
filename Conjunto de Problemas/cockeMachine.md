## Coke Machine

![alt text](image-1.png)

Supón que una máquina vende botellas de Coca-Cola (Coke) por 50 centavos y solo acepta monedas en estas denominaciones: 25 centavos, 10 centavos y 5 centavos.

En un archivo llamado coke.py, implementa un programa que solicite al usuario insertar una moneda, una a la vez, informando cada vez al usuario la cantidad adeudada. Una vez que el usuario haya ingresado al menos 50 centavos, muestra cuántos centavos de cambio se le deben. Supón que el usuario solo ingresará enteros y ignora cualquier entero que no sea una denominación aceptada.

## Antes de Comenzar

Inicia sesión en cs50.dev, haz clic en tu ventana de terminal y ejecuta `cd` por sí solo. Deberías ver que el indicador de la ventana de tu terminal se asemeja a lo siguiente:

```bash
$
```

Luego ejecuta

```bash
mkdir coke
```

para crear una carpeta llamada coke en tu espacio de código.

## Luego ejecuta

```bash
cd coke
```

para cambiar de directorio a esa carpeta. Ahora deberías ver el indicador de tu terminal como coke/ $. Ahora puedes ejecutar

```bash
code coke.py
```

para crear un archivo llamado coke.py donde escribirás tu programa.

## Cómo Probar

Así es como puedes probar tu código manualmente:

Ejecuta tu programa con

```bash
python coke.py
```

En tu solicitud Insert Coin:, escribe 25 y presiona Enter. Tu programa debería mostrar:

```bash
Amount Due: 25
```

y continuar solicitando al usuario que inserte monedas.

Ejecuta tu programa con

```bash
python coke.py
```

En tu solicitud Insert Coin:, escribe 10 y presiona Enter. Tu programa debería mostrar:

```bash
Amount Due: 40
```

y continuar solicitando al usuario que inserte monedas.

Ejecuta tu programa con

```bash
python coke.py
```

En tu solicitud Insert Coin:, escribe 5 y presiona Enter. Tu programa debería mostrar:

```bash
Amount Due: 45
```

y continuar solicitando al usuario que inserte monedas.

Ejecuta tu programa con

```bash
python coke.py
```

En tu solicitud Insert Coin:, escribe 30 y presiona Enter. Tu programa debería mostrar:

```bash
Amount Due: 50
```

¡porque la máquina no acepta monedas de 30 centavos! Tu programa debería continuar solicitando al usuario que inserte monedas.

Ejecuta tu programa con

```bash
python coke.py
```

En tu solicitud Insert Coin:, escribe 25 y presiona Enter, luego escribe 25 nuevamente y presiona Enter. Tu programa debería detenerse y mostrar:

```bash
Change Owed: 0
```

Ejecuta tu programa con

```bash
python coke.py
```

En tu solicitud Insert Coin:, escribe 25 y presiona Enter, luego escribe 10 y presiona Enter. Escribe 25 nuevamente y presiona Enter, después de lo cual tu programa debería detenerse y mostrar:

```bash
Change Owed: 10
```

Puedes ejecutar lo siguiente para verificar tu código usando check50, un programa que CS50 usará para probar tu código cuando lo envíes. ¡Pero asegúrate de probarlo tú mismo también!

```bash
check50 cs50/problems/2022/python/coke
```

Las caritas verdes significan que tu programa ha pasado una prueba. Las caritas rojas indicarán que tu programa mostró algo inesperado. Visita la URL que check50 te proporciona para ver la entrada que check50 entregó a tu programa, qué salida esperaba y qué salida dio tu programa realmente.

### Hint

Tendrás que tener cuidad como se imprime tu prompt, las repsutes tienen que ser exactamente como se muestran arriba. Si tu programa imprime cualquier tipo de texto
extra, puede que falle _check50_

## Cómo Enviar

En tu terminal, ejecuta lo siguiente para enviar tu trabajo.

```bash
submit50 cs50/problems/2022/python/coke
```
