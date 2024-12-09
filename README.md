# Laboratorio virtual 1
## 1. Implementa un objeto JSON que represente el listado de doctores en el hospital
(nombre, especialidad, años de experiencia, disponibilidad).
- Usa objetos anidados para organizar información adicional de cada doctor,
como horarios disponibles y contacto.
- Utiliza destructuring para acceder a las propiedades de estos objetos y mostrar
la información de un doctor específico en la consola y en la interfaz web.

## 2. Operaciones con JSON 
- Realiza las siguientes operaciones con los objetos JSON:
- Clonación: Crea una copia de un objeto JSON y modifícalo sin afectar el
original.
- Merge: Fusiona dos objetos JSON. Por ejemplo, puedes fusionar la información
de doctores con la lista de servicios médicos disponibles.
- Recorrido y stringify: Recorre los objetos JSON para mostrar en el navegador
la lista de doctores disponibles. Convierte el objeto a una cadena JSON usando
JSON.stringify() y muestra el resultado en la consola.

## 3. Implementación de Estructuras de Datos 
- Implementa estructuras de datos en el sitio web del hospital para gestionar mejor la
información de los doctores:
- Arreglos: Utiliza un arreglo para almacenar la lista de doctores. Implementa
operaciones como agregar, eliminar y buscar doctores dentro del arreglo.
- Pilas: Implementa una pila para gestionar las citas de los pacientes (última cita
agendada, próxima cita a atender, etc.).
- Colas: Crea una cola para simular el orden de llegada de los pacientes en la
página de contacto.

**Arreglo para la lista de doctores**:

Se utiliza el arreglo equipoMedico para almacenar la información de los doctores.
Se implementan funciones para agregar, eliminar y buscar doctores dentro del arreglo.
agregarDoctor: Añade un nuevo doctor al arreglo.
eliminarDoctor: Elimina un doctor por su nombre.
buscarDoctor: Busca un doctor por su nombre.
mostrarEquipo: Muestra los doctores en la página.


## 4. Programación de Algoritmos
- Implementa un algoritmo de búsqueda que permita encontrar un doctor específico
dentro del arreglo de doctores.

La función find devuelve el primer elemento en el arreglo que cumple con una condición dada (en este caso, el nombre del doctor):
Utiliza el método find para buscar un doctor específico dentro del arreglo equipoMedico dependiendo del nombre proporcionado.

const doctor = equipoMedico.find(doctor => doctor.nombre === nombreDoctor);  

El botón hace referencia a buscarDoctor('Dr. Carlos Andrés Ruiz')
<button onclick="buscarDoctor('Dr. Carlos Andrés Ruiz')" type="button" class="btn btn-info">Buscar Doctor</button>