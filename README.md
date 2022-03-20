<!--Para previsualizar el documento Markdown en VS Code solo aplicaríamos las teclas crl + shift + p, buscamos en la ventana Markdown Preview-->

<!--Titulos-->
# Título de nivel 1
## Título de nivel 2
### Título de nivel 3
####  Título de nivel 4
##### Título de nivel 5
###### Títlo de nivel 6

<!-- Itálica -->
Este es un texto en *itálica*

<!-- Negrita -->
Este es un un texto **en negrita**

<!-- Tachado -->
Este es un texto ~~tachado~~

<!-- UL -->
* manzana
    * manzana 2
* naranja
    * naranja 2
* etc

<!-- OL -->
1. manzana
    1. manzana 2
2. naranja
3. etc

<!-- Enlaces -->
[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "Título de preferencia")

<!-- Citas -->
> Esta es una cita.

<!-- Línea divisora -->
---

___

<!-- Formato de Código -->
`console.log('Hola mundo');`

```javascript
const mongoose  = require('mongoose);

mongoose.set('userFindAndModify', false);
mongoose.connect('mongodb://localhost/node-notes-db', {
    useCreateIndex: true,
    useNewUrlPraser: true
})
.then(db => console.log('DB is connected'))
.catch(err => console.error(err));
```

```Python
print("hola mundo")
```

```html
<h1>Hola mundo</h1>
```
<!-- Tablas -->
| las Tablas      |  son                 | geniales |
| --------------- |:---------------------| --------:|
| Columna 3 esta  | aliniada a la derecha|     $1600|
| Columna 2 esta  | centrada             |       $12|
| La zebra rayada | está aseada          |        $1|

<!-- Imágenes -->
![visual studio code logo](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.dinhanhthi.com%2Fimg%2Fheader%2Fvsc.png&f=1&nofb=1 "vscode logo")

<!-- GITHUB MARKDOWN -->
* [x] Task 1
* [ ] Task 2
* [x] Task 3
* [ ] Task 4

<!-- Menciones -->
@nombreUsuario

<!-- Emojis -->
:smiley:

:+1:

