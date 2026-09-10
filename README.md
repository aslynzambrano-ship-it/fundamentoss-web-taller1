# fundamentoss-web-taller1
primera pagina html
# fundamentos-web-taller1

## Verificacion de codigo

### Caso A
Problema identificado:El codigo no funciona correctamente porque la etiqueta <img> utiliza el
atributo href. Para insertar una imagen, el atributo correcto es src, que indica la ruta del
recurso.
Correccion realizada:Reemplace href por src.
Codigo corregido:
<img src="multimedia/perfil.jpg" alt="Fotografia del estudiante">



### Caso B
Problema identificado:El codigo no funciona como enlace porque la etiqueta <a> utiliza el
atributo src. En un enlace, el atributo correcto es href, que especifica la direccion de destino.
Correccion realizada: Reemplace src por href.
Codigo corregido:
<a href="https://developer.mozilla.org/">
Consultar MDN
</a>



### Caso C
Problema identificado:El codigo presenta un problema porque la etiqueta <source>, utilizada
dentro de <video>, debe indicar el archivo multimedia mediante el atributo src, no mediante
href.
Correccion realizada:Reemplace href por src.
Codigo corregido:
<video controls>
<source src="multimedia/video.mp4" type="video/mp4">
</video>



### Caso D
Problema identificado:El valor correo no corresponde a un tipo valido para el atributo type de
<input>. El tipo estandar para introducir una direccion de correo electronico es email.
Correccion realizada:Cambie type="correo" por type="email".
Codigo corregido:
<input type="email" name="correo">



### Caso E
La afirmacion es: incorrecta
Justificacion: La etiqueta estandar de HTML para insertar una imagen es <img>, no <image>.
Ademas, <img> es un elemento vacio (void element), por lo que no necesita ni permite una
etiqueta de cierre como </img>.
Cdigo funcionando:
<img src="multimedia/perfil.jpg" alt="Fotografia del estudiante">
