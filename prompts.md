# Rol
 Eres un experto en desarrollo web.
 
# Objetivo
 Crear un pagina web que incluya un cronómetro.
 
# Formato
 Quiero el codigo necesario para incluirlo en la pagina web, el codigo debe estar dividido en html, css y javascript.
 
# Historia de Usuario: Funcionalidad de cronometro en página web
 ## Resumen
 La pagina web debe incluir un cronometro funcional que muestre el tiempo en horas, minutos, segundos y milisegundos. Debe tener dos botones, uno para iniciar, pausar o continuar, y otro boton para limpiar el tiempo medido.
 ## Descripción de la Funcionalidad
 Los usuarios pueden usar un cronometro que se puede acceder a traves de una pagina web.
 - El cronometro se visualizara de la siguiente manera: "HH:MM:ss.SSS" en donde "HH" es la hora transcurrida, "mm", son los minutos transcurridos, "ss" los segundos transcurridos, y "SSS" los milisegundos transcurridos.
 - El cronometro debe iniciar en "00:00:00.000".
 - El boton de iniciar tendra tres estados: "Iniciar", "Pausar", y "Continuar".
 - EL estado "Iniciar" despues de pulsado debe empezar a avanzar el cronometro y el estado del boton debe cambiar a "Pausar".
 - El estado "Pausar" debe tener como etiqueta la palabra "Pause", y al presionarse debe conservar en pantalla el tiempo transcurrido hasta ese momento y cambiar el estado a "Continuar".
 - El estado "Continuar" debe tener como etiqueta la palabra "Continue", y al presionarse debe permitir avanzar el cronometro y cambiar al estado "Pausar".
 - El boton de limpiar solo tendra un estado el cual permitira reiniciar el cronometro.
 - El cronometro estara ubicado en el centro de la pantalla y debajo estaran los botones de inicicar y limpiar.
 - El boton de inicicar estara ubicado a la izquierda y el de limpiar a la derecha.
 - la pagina sera responsiva, y tambien debera tener opciones de accesibilidad.