# Implementación-de-algoritmos-recursivos

Se aplicó la implementación de un algoritmo recursivo para buscar un mensaje específico en una conversación de WhatsApp.

Función recursiva para buscar un mensaje específico en una conversación de WhatsApp.

   Args:
   - conversacion: Lista de mensajes en la conversación.
   - mensaje_buscar: Mensaje que se desea buscar en la conversación.
   - índice: Índice actual en la conversación (por defecto, se inicia en 0).

   Returns:
   - El índice del mensaje buscado si se encuentra, o -1 si no se encuentra.
     

La función buscar_mensaje recibe como entrada la conversación de WhatsApp, el mensaje que se desea buscar y el índice actual en la conversación.

En el caso base, si el índice supera el límite de la conversación, significa que el mensaje no se encontró, por lo que se devuelve -1.
Si el mensaje en el índice actual coincide con el mensaje buscado, se devuelve el índice.
Si no se encuentra el mensaje en el índice actual, se realiza una llamada recursiva para buscar en el resto de la conversación.

Este algoritmo demuestra cómo se puede aplicar la programación recursiva para buscar un mensaje específico en una conversación de WhatsApp. Esta técnica puede ser útil para la lógica de respuesta automática, como la detección de ciertos mensajes clave para activar respuestas automáticas personalizadas.

