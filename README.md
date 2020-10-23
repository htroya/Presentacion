# Páginas Web 

Las **páginas web estáticas** son muy simples. Está escrito en lenguajes como HTML, JavaScript, CSS, etc. Para páginas web estáticas, cuando un servidor recibe una solicitud para una página web, el servidor envía la respuesta al cliente sin realizar ningún proceso adicional. Y estas páginas web se ven a través de un navegador web. En las páginas web estáticas, las páginas seguirán siendo las mismas hasta que alguien las cambie manualmente.

Las páginas **web dinámicas** están escritas en lenguajes como CGI, AJAX, ASP, ASP.NET, etc. En las páginas web dinámicas, el contenido de las páginas es diferente para los diferentes visitantes. Se tarda más en cargar que la página web estática. Se utilizan páginas web dinámicas donde la información se cambia con frecuencia, por ejemplo, precios de acciones, información meteorológica, etc.

El tema de esta actividad experimental es la creación de páginas web a través del servicio de GitHubPages, para esto aplicaré dos enfoques, el primero es usar el mismo servicio Markdown de GitHub [Que es markwon ?](https://github.com/ricval/Documentacion/blob/master/Guias/GitHub/mastering-markdown.md#:~:text=Markdown%20es%20un%20lenguaje%20de,escribir%20en%20la%20plataforma%20GitHub) donde incrustare html directo utilizando una pequeña función en javascript para enviar un mensaje, y el segundo es la creación de una pequeña página web usando html.

## Markdown

En GitHub se pueden seleccionar temas para la presentación de la página web , en esta página se esta usando el tema MINIMAL [Ver tema minimal](https://github.com/htroya/Presentacion/settings/pages/themes?select=minimal&source=main&source_dir=%2F)

### Markdown
GitHub utiliza "Markdown" que es una sintaxis ligera y fácil de usar para diseñar la página web 

```markdown
Para poner cabeceras se utiliza esta sintaxis:

# Cabecera 1 que es equivalente a la etiqueta html <H3> Título principal </ H3>
## Cabecera 2 que es equivalente a la etiqueta html <H2> Título principal </ H2>
### Cabecera 3 que es equivalente a la etiqueta html <H1> Título principal </ H1>

- listas

1. Listas con números

**Negrilla** , _Italica_ y `codigo` 

Para poner links se utiliza el siguiente formato 

[Link](url) and ![Image](src)
para crear un área resaltada se debe poner tres comillas(izquierdas) seguidas , luego ponemos cualquier texto y cerramos con las mismas comillas(izquierdas) seguidas.

para poner codigo html puro se lo debe digitar directamente pero debe haber una línea en blanco que rodee al HTML tanto arriba como abajo.
```

Aquí un ejemplo incrustando código HTML:

El código incrustado es:
```
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
```

<html>
    <head>        
        <title>Incluyendo HMTL dentro de la pagina GitHUB usando Markdown</title>
        <script type="text/javascript">
            window.onload = function() {
                document.getElementById('alertar').onclick = function () {
                    alert('Se incrusta un boton dentro de la pagina y se llama a una funcion usando javascript');
                }
            }
        </script>
    </head>
    <body>  
        <section>
            <button type="button" id="alertar" title="click en el boton incrustado">Click</button>
        </section>
    </body>
</html>

## HTML
A continuación se muestran links para distintas páginas web.

1.Se llama a una página web usando html puro:[pagina 1 de ejemplo](https://htroya.github.io/Presentacion/pagina_html.html)

2.Otra página web de ejemplo [pagina 2 de ejemplo](https://htroya.github.io/Presentacion/pagina_html_2.html).

3.Se llama a una página almacenada en un servidor Oracle Cloud(**producto totalmente gratuito**) que usa Oracle Autonomus Transaccion, aplicación creada con oracle Apex:[Pagina Apex](https://jytaoxmtcsm8dwl-db202008032109.adb.us-ashburn-1.oraclecloudapps.com/ords/r/stp/sistema-erp/empresas?session=12066241147506)  para ingresar en esta página use el usuario **STP**  con clave **Productos42@**  esto es un sistema transaccional creado con el framework Oracle Apex.


## Conclusiones
1.La página principal se muestra directamente usando Markdown de GitHUb en esta página se usa funcionalidades propias del Markdown , así como también se incrusta html puro para crear un botón, este invoca a una pequeña función en javscript para que emita un mensaje en pantalla.

2.La pagina [web (1)](https://htroya.github.io/Presentacion/pagina_html.html) de ejemplo esta almacenada en el mismo repositorio y se llama pagina_html esta contiene etiquetas básicas del html

3.La página [web(2)](https://htroya.github.io/Presentacion/pagina_html_2.html) de ejemplo usa una hoja de estilos que esta almacenada en el mismo repositorio , en esta página web se incluyeron tanto imágenes como video así como etiquetas básicas del html, esta página invoca a su vez a otras dos páginas web mediante la etiqueta <a href, en estas páginas web incrustó pequeños códigos en javascript para realizar esta actividad experimental , el primero se cambia el estilo de un elemento del DOM, en el segundo muestra que día es hoy.

4.La página [web(3)](https://jytaoxmtcsm8dwl-db202008032109.adb.us-ashburn-1.oraclecloudapps.com/ords/r/stp/sistema-erp/empresas?session=12066241147506) de ejemplo invoca un sitio externo, este sitio esta creado con oracle apex por lo que usa base de datos oracle 19c, y está alojado en la nube de Oracle, cabe destacar que este servicio de oracle permite mantener sitios transaccionales de manera gratuita.

Fin



