1️⃣ Estructura del Proyecto

Se organizó el código en clases bien definidas.

Libro: Representa un libro con su título, autor, ISBN, año de publicación y estado de disponibilidad.

Usuario: Representa un usuario de la biblioteca, con su ID, nombre y correo electrónico.

Prestamo: Administra los préstamos, registrando fechas y calculando retrasos.

Biblioteca: Centraliza la gestión de libros, usuarios y préstamos.

Main: Punto de entrada del programa para demostrar su funcionalidad.

2️⃣ Uso de ArrayList para almacenamiento dinámico

Se utilizaron ArrayList en lugar de arrays fijos para permitir la expansión dinámica de libros, usuarios y préstamos sin restricciones de tamaño.

3️⃣ Uso de LocalDate para fechas

En lugar de usar int para fechas, se implementó LocalDate para manejar fechas de préstamo y devolución con mayor precisión y facilidad de manipulación.

4️⃣ Manejo de préstamos y devoluciones

Se verifica si un libro está disponible antes de prestarlo.

Al devolver un libro, se actualiza su estado de disponibilidad.

Se calcula automáticamente el retraso en la devolución, si aplica.

5️⃣ Mensajes informativos en consola

Cada acción imprime un mensaje en la consola para que el usuario pueda visualizar el estado del sistema en todo momento.
