jQuery fontSizer
---

 *Un plugin para A+ a-*

Adjuntar jquery.js y jquery.fontSizer.js entre las etiquetas `<head></head>`

Definir id’s para ambos links, por ejemplo `#aumentar` (+) y `#disminuir` (-)

Inicializar el plugin, como en el ejemplo:

	$(document).ready(function(){
   	 	$("#aumentar").fontSizer({
     	  action: "up"
    	});
    	$("#disminuir").fontSizer({
     	  action: "down",
    	});
	});
	
Eso es. El único parámetro obligatorio es indicar la acción de cada link mediante action. 

Los parámetros son:

	action: "up/down" (requerido).
	elements: "elemento" (un id, class o etiqueta donde actuará el cambio de tamaño de fuente).
	increment: número (en cuántos pasos serán el cambio de tamaño; por defecto es de 1 en 1).
	max: número (tamaño máximo del tamaño de fuente; por defecto es 30px).
	min: número (tamaño mínimo del tamaño de fuente; por defecto es 8px).
	
Por ahora solo ha sido probado con jQuery 1.2.6

[http://www.csslab.cl/2008/08/07/jquery-plugin-fontsizer/](http://www.csslab.cl/2008/08/07/jquery-plugin-fontsizer/)

