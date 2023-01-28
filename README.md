# Tu menu para una web

Hola este es un pequeño menu muy basico para tu sitio web! es minimalista y agradable a la vista y es muy facil de integrar a su sitio web.

Antes que nada para que tu sitio web detecte el archivo "estilo.css" debes añadir la siguiente etiqueta:

	<link rel="stylesheet" type="text/css" href="estilo.css">

Si quieres eliminar el color de fondo del sitio unicamente elimina esta etiqueta o edita su valor

	.menu li a:hover{
	background: #ef8354;
	}

Este codigo  se encuentra en la linea 27 del archivo "estilo.css"

Para crear un menu, debes estar ubicado dentro de la etiqueta body y añadir este codigo 

	<ul class="menu"> 
       <li><a href="#">Inicio</a>   </li>
       <li><a href="#">Soporte</a>   </li>
       <li><a href="#">Contact Us</a>   </li>
       <li><a href="#">Info</a>   </li>
       <li><a href="#">More</a>   </li>
       </ul>
este es el codigo de nuestro menu  en  donde se encuentran las almohadilla "#" podras insertar la url donde quieres que te lleve el boton de cada parte del menu si quieres añadir mas secciones inserta :
 
 	<li><a href="#">(name)</a>   </li>
Antes de 

  	   </ul>
y edita el nombre y adonde quieres que te dirija el menu

Quieres ver como se ve el menu? observa la demo!: http://menu-html.thec23projects.top
