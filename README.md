# Unidad 4

Juan Diego Maldonado 
Isaac Pineda

## documentacion actividades de la unidad

Una vez se pudo instalar el package ejn unity se empezo a provar y tras resolver el problema del dtr se logra ver el programa en funcionamiento 

![image](https://github.com/user-attachments/assets/e8a7eab0-4b2d-4cc8-8fc8-d57d394ec850)

Ya funcionando se hace el experimento propuesto de comentar una linea de codigo y sigue funcionando.

![image](https://github.com/user-attachments/assets/2e1b37b0-f45d-4c0e-a464-d4a1ac9b87c6)

El segundo experimento como era de esperarse ya no funcionó lo que arrojo como resultado lo siguiente 

![image](https://github.com/user-attachments/assets/a4ce27da-c94f-4745-99d2-9666fa8733f8)

Por lo que se puede concluir lo siguiente: 

La línea parece estar presente como una referencia opcional para quienes quieran trabajar directamente con serialController en el código de ejemplo, sin ser estrictamente necesaria en este caso. Sin embargo, el objeto debe existir en la escena para que el sistema funcione en su conjunto, ya que otros scripts o dependencias de Ardity pueden necesitar el SerialController como punto de referencia o configuración de comunicación.

El siguiente ejercicio con la funcion update deja como resultado lo siguiente:

Envío de la letra "A" o "Z": La letra "A" o "Z" se envía solo cuando el usuario presiona la tecla correspondiente.

Mientras que la aplicación intenta leer mensajes del Arduino en cada frame, sin importar si hay un mensaje o no. Esto significa que si la aplicación corre a 60 FPS, el código intentará leer 60 veces por segundo. Sin embargo, solo procesará el mensaje si recibe un dato válido o un evento de conexión/desconexión; de lo contrario, el método Update simplemente sigue al siguiente frame.



