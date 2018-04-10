# Creacion de un paquete pruebaCreacionPaqueteNpm

este es un repositorio de prueba parte del curso de fundamentos de javascript

[Fundamentos de javascripr](https://github.com/alexisMoragaa/fundamentosJavascript)

## Descripcion del paquete

para este ejemplo crearemos un lenguaje a partir de una serie de reglas
ingresaremos un texto, y manipularemos el string, en base a una serie de reglas para retornar un texto nuevo

### REGLAS

- si la palabras termina en "ar" se le quitan estas ultimas dos letras //programar = program
- si la palabra comienza co z se le agrega pe al final //zorro = zorrope
- si la palabra tiene mas de 10 letras se deve partir por la mitad y unir con un gion medio //abecedario = abce-dario
- si la palabra es un palindromo ninguna regla anterior cuenta, se retorna la misma palabra intecalando entre mayusculas y minusculas //sometemos = SoMeTeMoS


## Instalacion

```
npm install myfirstpackage
```

## Uso

```
import platzom from 'platzom'

platzom("programar") //program
```

##creditos
- [Sacha Lifszyc](https://twitter.com/@slifszic)

## Licencia
- [MIT](https://opensource.org/licenses/MIT)
