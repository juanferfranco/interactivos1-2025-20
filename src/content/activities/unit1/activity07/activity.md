#### Generando de imágenes en micro:bit

Crea un programa en p5.js con cuatro botones. Cada botón le indicará al micro:bit qué imagen debe mostrar.
Para solucionar este problema, debes analizar el funcionamiento de la actividad 03.

Para el micro:bit, nota que al recibir un mensaje desde p5.js con el carácter 'h', el micro:bit mostrará un corazón.

```python
    if uart.any():
        data = uart.read(1)
        if data:
            if data[0] == ord('h'):
                display.show(Image.HEART)
```

Nota entonces que puedes verificar otros valores de `data[0]` para mostrar diferentes imágenes. 

Para el código de p5.js, el siguiente código crea un botón y almacena su referencia en la variable `sendBtn`.
Luego agrega un evento `mousePressed` que envía el carácter 'h' al micro:bit cuando se presiona el botón. Toma 
este código como punto de partida para añadir los otros botones y enviar los caracteres correspondientes.

```js
let sendBtn = createButton('Send Love');
sendBtn.position(220, 300);
sendBtn.mousePressed(sendBtnClick);
```

:::caution[📤 Bitácora]
En tu bitácora:
* Escribe el enlace a tu programa en el editor de p5.js.
* Copia el código de tu programa en la bitácora (recuerda insertarlo usando
markdown y el lenguaje javascript).
* Copia el código del micro:bit en la bitácora (recuerda insertarlo usando markdown y el lenguaje python).
:::
