Problema: Se necesita realizar un programa que administre turnos de una veterinaria con las siguiente especificaciones:
 
La veterinaria tiene empleados y clientes
Los empleados tienen a cargo mascotas.
Los empleados deben realizar las siguiente tareas:
Alimentar de manera justa a cada uno de las mascotas a su cargo.
Ejercitar a cada una de las mascota.
Una mascota, es un animal, que puede ser terrestre,  acuático,  anfibios.
Un animal terrestre, es aquel que puede vivir en tierra y se ejercita caminando.
Un animal acuático, es aquel que puede vivir en el agua y se ejercita nadando,
Un animal anfibio, es aquel que puede vivir en el agua y en la tierra se ejercita nadando y caminando,
 
-Un turno, involucra a un empleado y a un cliente, el turno tiene una fecha, un estado, y un identificador de número.
 
la veterinaria, puede crear un cliente nuevo a partir de una persona.
El cliente tiene, un número de cuenta, turnos asociados.
El empleado, tiene turnos y horarios de trabajo.
 
La veterinaria deberá poder ver una lista con los turnos por una fecha específica.
la veterinaria deberá poder listar los empleados.
se deberá poder cargar las mascotas, cliente, empleado y turnos desde un archivo.
 
El programa se deberá llamar por consola de la siguiente manera
Python veterniaria.py
 
Luego en la consola se debe mostrar un menú con las siguientes opciones:
AC)  Agregar cliente
AE)  Agregar empleado
CT) Crear un turno
CM) Crear mascota
AM) Asignar mascota
LT) Listar turnos pendientes
AT) Atender turno
G) Salir
 
-  AC)  Agregar cliente, deberá solicitar, nombre, apellido, y si ya se encuentra registrado imprimir que ya está registrado, si es nuevo se debe crear un cliente nuevo, generando un número de cliente que debe ser único.
 
-AE) Agregar Empleado, deberá solicitar nombre, apellido y si ya se encuentra registrado imprimir que ya está registrado, si es nuevo se debe crear un cliente nuevo, generando un número de cliente que debe ser único y hora de trabajos.
 

CT) Crear un turno: nos deberá solicitar un número de cliente, un horario,  si no se encuentra, imprimir error y abortar la creacion. Asignar un empleado al azar que trabaje en ese horario, si no hay empleado disponible, informar con un mensaje los horarios disponibles
 
CM) Crear mascota: deberá solicitar nombre, tipo de animal (anfibio,  terrícola o acuático), nombre, peso, cantidad de horas de ejercicios necesarias.
 
AM) Asignar mascota: deberá solicitar número de cliente y número de mascota.
 
LT) Listar turnos pendientes: listar los turnos de una forma amigable.
 
AT) Atender turno: se deberá solicitar un número de turno y debe hacer ejercitar a sus mascotas (como ejercitar se puede imprimir la palabra de la acción, una vez por cada una de las horas que debe ejercitar).
 
G) Salir: Al salir se debe guardar en un archivo, la representación de cada uno de los objetos. para cuando se inicie, se debe levantar los objetos desde ese archivo, y mantener el mismo estado.
