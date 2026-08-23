# cafeteriacoffe

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/leidylopez6/cafeteriacoffe)

BUZÓN DE SUGERENCIAS - CAFETERIA COFFE

Integrantes: Tulia Yasney Mejia Torres - Leidy López Herrera - Juan David Tapias Arcila

Este proyecto consiste en el desarrollo de un buzón de sugerencias para la cafeteria coffe en un ambiente web, con la finalidad de que los clientes plasmen las sugerencias que tienen con respecto a la cafetería completando un formulario.
La página fue desarrollada en la herramienta stackblitz.com utilizando Node.js, Express, HTML, JavaScript y CSS, y fue publicada mediante la herramienta Render.

Historias de usuario:
1:
  Como cliente 
  sugiero la utilización de herramientas de pago como Nequi,
  para que sea más accesible los métodos de pago.
2:
 Como cliente de la cafetería.
 Quiero ver el menú del día y las ofertas vigentes desde mi celular.
 Para decidir qué pedir por mi cuenta de forma rápida y sin depender de un mesero.
3:
 Como cliente
 Quiero como sugerencia que la cafetería implemente el servicio a domicilio 
 para brindar mayor comodidad a los clientes,  especialmente a quienes se encuentran en oficinas u otros  lugares de trabajo.

Casos de prueba:
         Acción	           |                       Resultado esperado	                           | ¿Pasó?
Enviar sugerencia completa |	Se guarda la sugerencia y luego del mensaje se limpia el formulario|	✅
Enviar con mensaje vacío   |	El servidor no la guarda porque el campo está vacío                |	✅
Ver panel de administración|	Aparece la lista completa de las sugerencias realizadas            |	✅
Visitar ruta inexistente   |	Devuelve un error 404 en formato JSON                              |  ✅

Enviar sugerencia completa: <img width="1488" height="757" alt="image" src="https://github.com/user-attachments/assets/9e76473e-5ef2-44d2-88ea-bc0832a45664" />
Enviar con mensaje vacío: <img width="1499" height="758" alt="image" src="https://github.com/user-attachments/assets/e5ebce41-9fa5-4eaf-af9d-e17cb2e79f34" />
Ver panel de administración: <img width="1527" height="662" alt="image" src="https://github.com/user-attachments/assets/3789dc91-cec0-4136-8274-2dffdd5795b2" />
Visitar una ruta inexistente: <img width="1497" height="725" alt="image" src="https://github.com/user-attachments/assets/ffafe964-3600-47cf-a0b0-ef0cc48edabc" />

Retrospectiva:
¿Qué funcionó bien?
A la primera nos funcionó la conexión entre el formulario y el panel de administración, no tuvimos ningún inconveniente con enviar el formulario completo y luego visualizarlo por medio del admin.html. También nos funcionó muy bien la pagina publicada ya que la probamos en diferentes dispositivos (computadores y celulares) y el registro se guardaba correctamente. 

¿Qué nos costó más trabajo?
Los tres ambientes (stackblitz, render y Github) eran muy nuevos para nosotros por eso se nos dificulto un poco realizar la conexión del proyecto a Github para luego ser publicado por medio de render. Primero no sabíamos como encontrar el botón "Connect Repository" y luego de que por fín logramos pasar el proyecto a github, nos topamos con render que presentaba errores al momento de publicar la página por que escribimos en la parte de Start command: node index.js un punto final y no nos habíamos percatado de eso hasta después de media hora donde ya habíamos intentado eliminar y volver a montar el proyecto. Gracias a estas dificultades aprendimos a desenvolvernos en estos tres ambiente web.

¿Qué harían distinto si empezaran de nuevo?
Organizaríamos mejor cada parte del proyecto por que con nuestro equipo nos adelantábamos los pasos por que los considerábamos menos importantes y por eso cometimos errores en partes como la publicación en github y render. Si tuviéramos que comenzar de nuevo este proyecto nos percataríamos más en los detalles de los ambientes web y en las instrucciones de la guía, también realizaríamos pruebas para cada cambio que diera nuestra página con la finalidad de comprender y agilizar nuestro aprendizaje en programación.

¿Qué le agregarían al buzón en una siguiente versión?
Nos gustaría agregarle un campo de contacto, donde el cliente deje su correo electrónico o su número telefónico y así el encargado del buzón de sugerencias deje saber por medio de un mensaje al cliente si su sugerencia fue aceptada o no.
También agregaríamos almacenamiento permanente para que las sugerencias no se pierdan al reiniciar el servidor.
finalmente, También le daríamos más estilo a la página como colores, tipografías y otras opciones de diseño para hacerla más atractiva y agradable para los usuarios.

Enlace:
Pagina publicada: https://cafeteriacoffe.onrender.com
Repositorio en GitHub: https://github.com/leidylopez6/cafeteriacoffe


