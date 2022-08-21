# Javascript Challenges

Serie de desafios de Javascript, diferentes niveles de dificultad en situaciones laborales reales

- Está permitido (y recomendado) googlear y consumir material en internet para completar los desafios
- La idea principal es entender los conceptos a utilizar, sea consciente que copiando y pegando el código podría no ser suficiente para usted, el consejo es aprender e investigar sobre cada concepto que no maneje de los desafios
- Los enunciados son redactados como si fuera un requisito de un cliente en una compañia de TI
- Como se organice y se estructure el proyecto es responsabilidad suya, pero dejaré un boilerplate de proyecto en una carpeta de este repositorio
- Mientras más prácticas de ES6+ aplique mejor 

## Instrucciones

- Realice un Fork del proyecto a su cuenta de Github
- Comience a trabajar desde el nivel que le parezca adecuado a su conocimiento
- Edite los archivos dentro de la carpeta ```\boilerplate``` puede hacer una copia por cada challenge (recomendado) o editar la misma carpeta
- Suba el avance a su cuenta de Github

## Niveles

1) ⚡
2) ⚡⚡
3) ⚡⚡⚡
4) ⚡⚡⚡⚡

## Challenges

### Accesibilidad

1) ⚡ Se necesita crear un boton en pantalla con el texto "Incrementar Título" que permita al usuario incrementar el tamaño de fuente del elemento ```H1``` de la página como medida de accesibilidad, el cliente quiere que el título incremente al menos un 20%

2) ⚡⚡ Se necesita crear un boton en pantalla con el texto "A+" que permita al usuario incrementar el tamaño de fuente de todo el texto de la página como medida de accesibilidad, el cliente pide que los títulos incrementen al menos un 20% y los párrafos al menos un 30% 

3) ⚡⚡ Se necesita crear un boton en pantalla con el texto "A-" que permita al usuario reducir el tamaño de todo el texto de la página como medida de accesibilidad, el cliente pide que los títulos se reduzcan al menos un 20% y los párrafos al menos un 30% 

4) ⚡⚡ El mismo cliente ahora necesita crear un "modo oscuro", pide que se desarrolle un botón con el texto "dark mode" que al presionar cambie el color del body a negro y los parrafos y títulos a color blanco

5) ⚡⚡⚡ El cliente necesita desarrollar una interfaz para los botones de incrementar/reducir texto además del modo oscuro, los tres botones deben estar situados al inicio de la pagina y deben cumplir las siguientes reglas:
    - Los botones que deben estar presentes son "A-" "A" "A+" y "Dark Mode"
    - El botón "A" debe volver el texto al original si es que fue clickeado uno de los otros botones anteriormente
    - Al clickear en uno de los botones "A+", "A" "A-" se deben deshabilitar para no producir un incremento o reducción de texto sin control de la página
    - El boton "Dark Mode" debe cambiar su texto a "Light mode" cuando es activado para volver al original cuando sea clickeado nuevamente
    
6) ⚡⚡ El mismo cliente ahora necesita crear un "modo simple" para resumir noticias, requiere sumar un nuevo botón a la interfaz de accesibilidad que al ser presionado esconda los dos últimos elementos ```p``` de la página sin importar cuantos hayan actualmente, además de todos los elementos ```H3```

7) ⚡⚡ El cliente le solicita encontrar la forma de crear un boton en la interfaz de accesibilidad que permita al usuario escuchar lo redactado en el título ```H1``` 

### Forms

1) ⚡ Un cliente de un banco pide una nueva funcionalidad en su aplicación, necesita que el usuario pueda ingresar su nombre en una caja de texto y mientras se vaya ingresando, las letras se transformen a letras mayúsculas

2) ⚡⚡ El mismo cliente del banco, necesita que en otra caja de texto el usuario pueda ingresar un monto en pesos chilenos y que automáticamente se transforme a formato con puntos en los números correspondientes, ejemplo: el usuario ingresa "2900000" la caja de texto debería transformarlos a "2.900.000"

3) ⚡⚡⚡ Nuevamente el cliente del banco le pide modificar su aplicación, requiere crear un validador de RUT chileno, es decir, si el usuario ingresa un rut como 18119758-7 vendría siendo válido, pero uno como 18119758-6 no sería válido por el dígito verificador, la casilla de texto debería marcar en rojo y/o dar un mensaje de error en pantalla

4) ⚡⚡⚡ El cliente ahora necesita crear un campo de texto en el mismo formulario que permita el usuario ingresar una contraseña que cumpla con las siguientes condiciones:
    - Al menos 8 letras o números (a-Z, 0-9)
    - Al menos un caracter especial (!@#$%ˆ&*()_+)
    - Al menos una letra máyuscula
    - De cumplir todas las condiciones el campo debe mostrarse en pantalla con bordes color verde
    - De no cumplir todas las condiciones el campo debe mostrarse en pantalla con bordes color rojo




