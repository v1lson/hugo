+++
title = 'Plantilla'
date = 2023-09-19T10:48:58+02:00
draft = false
weight = 10
+++

# Titulo de plantilla

## Subtitulo de plantilla

```
# Titulo de plantilla

## Subtitulo de plantilla
```
## Texto

```
Aqui probamos el texto **en negrita**, aqui en *cursiva* y aqui ~~tachado~~

**_~~Combo~~_**
```
Aqui probamos el texto **en negrita**, aqui en *cursiva* y aqui ~~tachado~~

**_~~Combo~~_**

## Lista

```
1. Lista numerada
>    * Sublista 
```

1. Lista numerada
>    * Sublista 

## Link
```
[Ejemplo de link](http://google.com)
```
[Ejemplo de link](http://google.com)

## Imagen
```
Imagen metida directamente: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Titulo del logo")

Referencia de imagen: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Titulo del logo"
```

Imagen metida directamente: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Titulo del logo")

Referencia de imagen: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Titulo del logo"

## Tabla
 ```
 | Por defecto | Centrado  | Izqerda|
| ------------- |:-------------:| -------------:| 
| Normal | 0$ | aaa| 
| Anormal | 1000000$ | aaaa|

 ```
| Por defecto | Centrado  | Izqerda|
| ------------- |:-------------:| -------------:| 
| Normal | 0$ | aaa| 
| Anormal | 1000000$ | aaaa|

## Video 
```
{{/<youtube jfKfPfyJRdk>}}
sin /
```

{{<youtube jfKfPfyJRdk>}}

## Codigo 

{{< highlight lineNos="true" hl_lines="2 4" lineNoStart="1" type="py" >}}
# the hardest part is to start writing code; here's a kickstart;
print("Hello")
print(" ")
print("World")
print("!")
{{< /highlight >}}

