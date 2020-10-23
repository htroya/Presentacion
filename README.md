### Páginas Web 

Las **páginas web estáticas** son muy simples. Está escrito en lenguajes como HTML, JavaScript, CSS, etc. Para páginas web estáticas, cuando un servidor recibe una solicitud para una página web, el servidor envía la respuesta al cliente sin realizar ningún proceso adicional. Y estas páginas web se ven a través de un navegador web. En las páginas web estáticas, las páginas seguirán siendo las mismas hasta que alguien las cambie manualmente.

Las páginas **web dinámicas** están escritas en lenguajes como CGI, AJAX, ASP, ASP.NET, etc. En las páginas web dinámicas, el contenido de las páginas es diferente para los diferentes visitantes. Se tarda más en cargar que la página web estática. Se utilizan páginas web dinámicas donde la información se cambia con frecuencia, por ejemplo, precios de acciones, información meteorológica, etc.

El tema de esta actividad experimental es la creación de páginas web a través del servicio de GitHubPages, para esto aplicamos dos enfoques, el primero es usar el mismo servicio Markdown de GitHub [Que es markwon ?](https://github.com/ricval/Documentacion/blob/master/Guias/GitHub/mastering-markdown.md#:~:text=Markdown%20es%20un%20lenguaje%20de,escribir%20en%20la%20plataforma%20GitHub) y el segundo es la creación de páginas con lenguaje HTML puro

## Markdown

En GitHub se puden seleccionar temas pra la presentación de la página web , en esta página se esta usando el tema MINIMAL [Ver tema minimal](https://github.com/htroya/Presentacion/settings/pages/themes?select=minimal&source=main&source_dir=%2F)

# Markdown
GitHub utiliza "Markdown" que es una sintaxis ligera y fácil de usar para diseñar la página web 

```markdown
Para poner cabeceras se utiliza esta sintaxis:

# Cabecera 1 que es equivalente a la etiqueta html <H3> Título principal </ H3>
## Cabecera 2 que es equivalente a la etiqueta html <H2> Título principal </ H2>
### Cabecera 3 que es equivalente a la etiqueta html <H1> Título principal </ H1>

- listas

1. Listas con numeros

**Negrilla** , _Italica_ y `codigo` 

Para poner links se utiliza el siguinete formato 

[Link](url) and ![Image](src)
para crear un area resaltada se debe poner tres comillas(izquierdas) seguidas , luego ponemos cualquier texto y cerramos con las mismas comillas(izquierdas) seguidas.

para poner codigo html puro se lo debe digitar directamente pero debe haber una linea en blanco que rodee al HTML tanto arriba como abajo.
```

Aqui un ejemplo incrustando codigo HTML:

<html>
    <head>        
        <title>Incluyendo HMTL dentro de la pagina GitHUB usando Markdown</title>
        <script type="text/javascript">
            window.onload = function() {
                document.getElementById('alertar').onclick = function () {
                    alert('Se incrusta un boton dentro de la gina y se llama a una funcion usando javascript');
                }
            }
        </script>
    </head>
    <body>  
        <section>
            <button type="button" id="alertar">Click</button>
        </section>
    </body>
</html>

## HTML
A continuación se muestran tres link para distintas páginas web creadas solo con HTML.

Se llama a una pagina web usando html puro:

Se llama a una pagina almacenada en un servidor Oracle Cloud que usa Oracle Autonomus Transaccion, aplicación creada con oracle Apex:



