# Versión del curso 
Versión actual v.1.2.2

# CABECERAS
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Undelines
Underline 1
************

Underline 2
=================

# Formatos de Enfasis
- Formato *italica* de primer forma.
- Formato letra _italica_ de segunda forma.
- Formato **bold o strong** de la primer forma
- Formato __bold o strong__ de la segunda forma
- formato ~~tachado~~
- aqui podemos usar *formato italico*, pero también **bold** y ~~tachado~~

# Listas
1. Esto es un  item de listas ordenada.
2. Esto es un  item de listas ordenada.
3. Esto es un item de listas ordenada.
- Esto es un item de lista desordenadas
- Esto es un item de lista desordenadas
- Esto es un item de lista desordenadas

# Links
- <a href = "http://google.com"> Esto es un link HTML </a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo sentra](https://www.sentra.cl/images/logo-sentra.png)


# Code Snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en JavaScripts
```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento|
|------- | ---------|----------|
|Nitza | Varas| 1234244|
|Juan | Perez | 213431|

# Citas
Esto es un texto referente a una cita:
> Esto es un a cita

Otro texto no relacionado con la cita anterior
> Esto es otra cita.

# Líneas Divisoras
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividio por guiones bajos.

___


# Saltos de línea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista
