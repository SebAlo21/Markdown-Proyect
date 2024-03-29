# Blog escrito con marcación MARKDOWN

```
Este será un proyecto de escritura MARKDOWN
```
---
## Encabezados
---
Para hacer referencia de un encabezado en markdown lo definimos:
```
# title h1
## title h2
### title h3
#### title h4
##### title h5
###### title h6
```
- Es decir la cantidad de # denota la jerarquia de los encabezados/titulos.
---
## Estilos de texto
---
- italic
   ```
   this is an *italic* text
   ```
   this is an *italic* text

- strong/negrita
   ```
   this is an **strong** text
   ```
   this is an **strong** text

- strikethrough/tachado
    ```
    this is an ~~strikethrough~~ text
    ```
    this is an ~~strikethrough~~ text
- strong and italic
    ```
    this is an ***strong and italic*** text
    ```
    this is an ***strong and italic*** text

## citas textuales
---
Para hacer referencia a una cita textual :
```
>Las tardes no florecen como ayer,cuando tus labios eran lo mejor.

```
>Las tardes no florecen como ayer,cuando tus labios eran lo mejor.

## links
---
Para hacer referencia a un enlace externo:
```
 visita la pagina web[link-externo.com](goggle.com)
```
visita la pagina web [link-externo.com](https://www.google.com)
- Podemos agregar un mensaje modal al hacer hover al link:
visita la pagina web [link-externo.com](goggle.com " Este es un texto modal")
## Listas
---
Para crear listas :
```
 - o * denotan un elemento de lista sin orden
 1. denota un elemento de lista con orden
```
-Anidar elementos dentro de un elemento de lista 
```
* apple
    * apple2
```
* apple
    * apple2

## Imagenes
---
Para introducir una imagen ,se realiza la referencia de un LINK:
```
![imagen.png](link_de_imagen)
```
![imagen.png](https://estaticos.miarevista.es/media/cache/1140x_thumb/uploads/images/gallery/59144d795cafe812663c986a/razonescomermanzana-int.jpg)

## Codigo embed
---
Para que el archivo markdown reconozca el codigo se agrega :
```
`javascript(python,html,css,etc)
console.log("hello")
`
```
- Para bloques grandes codigo usamos el triple backstick.
```
    ```javascript
            const openYellow=document.getElementById('open-yellow');
        const panelYellow=document.getElementById('panel-yellow');
        const closeYellow=document.getElementById('close-yellow');
        const togglePanelYellow=()=>panelYellow.classList.toggle('active')
            openYellow.addEventListener('click',togglePanelYellow)
            closeYellow.addEventListener('click',togglePanelYellow)
    ```
```
```javascript
            const openYellow=document.getElementById('open-yellow');
        const panelYellow=document.getElementById('panel-yellow');
        const closeYellow=document.getElementById('close-yellow');
        const togglePanelYellow=()=>panelYellow.classList.toggle('active')
            openYellow.addEventListener('click',togglePanelYellow)
            closeYellow.addEventListener('click',togglePanelYellow)
```
## Task list(Github)
---
Podemos crear listas de tareas con la implementación de Markdown a github.
```
- [ ] Task 1 
- [x] Task 2 
- [] Task 3 
- [x] Task 4 
```
- [ ] Task 1 
- [x] Task 2 
- [ ] Task 3 
- [x] Task 4 
---
## Emojis(Github)
---
Gracias a la implementación del marcado rápido,podemos hacer uso de emojis de una gran lista disponible en: 
[emojis-github](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md),
para el uso de los emojis :
```
:smile:
:relaxed:
:hugs:
```
:smile:

:relaxed:

:hugs:

---
## Notas de pie (github)
Para crear notas de pie usamos:
```
Mi primera linea[^1].
La practica hace al maestro[^2].
Crear desde cero no es como vivir desde cero[^frase]


[^1]:Referencia a la primera linea.  
[^2]:Referencia a una frase. 
[^frase]:Podemos hacer uso de palabras como referencia a las notas. 
```
Mi primera linea[^1].
La practica hace al maestro[^2].
Crear desde cero no es como vivir desde cero[^frase]


[^1]:Referencia a la primera linea.  
[^2]:Referencia a una frase. 
[^frase]:Podemos hacer uso de palabras como referencia a las notas. 

## Ocultar Markdown
---
Es muy común que deseeamos ocultar texto para ciertas partes de la documentación del proyecto,   
por ello existe la opción de ocultar el marcado mediante el uso de los comentarios de HTML. 
```
<!-- Este texto esta completamente oculto por el motor de renderizado -->
```
<!-- Este texto esta completamente ignorado por el motor de renderizado -->

## Ignorar el formato de Markdown
---
Por otra parte podemos escapar del renderizado de Markdown para establecer texto literario sin marcado.
```
El siguiente texto no se renderizara en \*italica\*,pero este si *italica*.
```
El siguiente texto no se renderizara en \*italica\*,pero este si *italica*.

## Deshabilitar el visualizador de Markdown
---
Mediante el boton <> podemos hacer una vista del documento origen(es decir ,sin renderizado).
![Imagen de visualizador](https://docs.github.com/assets/cb-17832/images/help/writing/display-markdown-as-source.png)

# ACTUALIZADO 12/26/2021
