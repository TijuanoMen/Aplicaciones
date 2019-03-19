<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Insertar una imagen en un Canvas</title>
</head>
<body>
<h1>Insertar una imagen en un Canvas</h1>


<canvas height="300px" width="300px" id="micanvas"></canvas>

<script>
var canvas = document.getElementById("micanvas");
var ctx = canvas.getContext("2d");
var img = new Image();
img.src = "http://img.aulambra.com/wp-content/uploads/2009/10/logo_aulambra.png";
// Importante el onload
img.onload = function(){
	ctx.drawImage(img, 0, 0);
}
</script>

<br/><br/>
<hr>
Art&iacute;culo disponible en: <a href="http://lineadecodigo.com/html5/insertar-una-imagen-en-un-canvas-html5/">http://lineadecodigo.com/html5/insertar-una-imagen-en-un-canvas-html5/</a><br/>
<a href="http://lineadecodigo.com" title="Linea de Codigo">lineadecodigo.com</a>

</body>
</html>
