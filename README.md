Sistemas: Red Hospitalaria y Sistema de Datos Médicos
Este manual está diseñado para guiar a los usuarios en el uso de las funcionalidades de
los sistemas proporcionados.
Sistema 1: Red Hospitalaria
Introducción
El sistema de red hospitalaria permite modelar y gestionar una red de hospitales
conectados mediante grafos. Sus funcionalidades incluyen agregar hospitales, conectar
nodos, calcular rutas, transferir pacientes y visualizar la red.
Instrucciones de Uso
1. Ejecutar el Programa
a. Ejecute el archivo grafo_red_hospitalaria_final.py.
b. El programa mostrará un menú interactivo con las opciones disponibles.
Opciones del Menú
1. Agregar un hospital
a. Permite registrar un nuevo hospital en la red.
b. Pasos:
i. Ingrese el nombre del hospital.
ii. Confirme la operación.
2. Conectar hospitales
a. Crea una conexión entre dos hospitales con una distancia específica.
b. Pasos:
i. Ingrese los nombres del hospital de origen y destino.
ii. Especifique la distancia.
iii. Confirme la operación.
3. Eliminar un hospital
a. Remueve un hospital de la red, incluyendo todas sus conexiones.
b. Pasos:
i. Ingrese el nombre del hospital a eliminar.
ii. Confirme la operación.
4. Mostrar red hospitalaria
a. Lista todos los hospitales y sus conexiones con distancias.
5. Agregar un paciente a un hospital
a. Registra a un paciente en un hospital específico.
b. Pasos:
i. Ingrese el nombre del hospital.
ii. Especifique el nombre del paciente.
6. Remover un paciente de un hospital
a. Elimina un paciente de la lista de un hospital.
b. Pasos:
i. Ingrese el nombre del hospital.
ii. Especifique el nombre del paciente.
7. Transferir paciente entre hospitales
a. Mueve un paciente de un hospital a otro mediante la ruta más corta.
b. Pasos:
i. Ingrese el nombre del paciente, el hospital de origen y el de
destino.
ii. Confirme la operación.
8. Encontrar la ruta más corta entre hospitales
a. Calcula la distancia más corta usando el algoritmo de Dijkstra.
b. Pasos:
i. Ingrese el nombre del hospital de origen y el de destino.
ii. Visualice la ruta y la distancia.
9. Buscar caminos con DFS/BFS
a. Encuentra cualquier camino entre dos hospitales.
b. Pasos:
i. Especifique el hospital de inicio y objetivo.
ii. Elija entre DFS o BFS.
iii. Visualice el camino encontrado.
10.Salir
• Cierra el programa.
Sistema 2: Sistema de Datos Médicos
Introducción
Este sistema permite administrar pacientes y sus historiales clínicos mediante árboles
binarios de búsqueda (BST) y colas de prioridad. Ofrece funcionalidades como registrar
pacientes, gestionar turnos, y administrar historiales médicos.
Instrucciones de Uso
1. Ejecutar el Programa
a. Ejecute el archivo analisis_de_datos_medicos_final.py.
b. El programa mostrará un menú interactivo con las opciones disponibles.
Opciones del Menú
1. Ingresar nuevo paciente
a. Registra un paciente en el sistema.
b. Pasos:
i. Complete los datos requeridos (ID médico, nombre, DNI, etc.).
ii. Confirme la operación.
2. Eliminar paciente
a. Remueve un paciente del sistema.
b. Pasos:
i. Ingrese el ID médico del paciente.
ii. Confirme la operación.
3. Buscar paciente
a. Encuentra un paciente registrado en el sistema.
b. Pasos:
i. Ingrese el ID médico.
ii. Visualice la información del paciente.
4. Actualizar datos de un paciente
a. Modifica la información personal de un paciente.
b. Pasos:
i. Ingrese el ID médico.
ii. Complete los campos que desea actualizar.
5. Gestionar historial clínico
a. Permite administrar consultas, diagnósticos y tratamientos del historial
clínico del paciente.
b. Opciones Disponibles:
i. Agregar una consulta o diagnóstico.
ii. Asociar tratamientos a un diagnóstico.
iii. Eliminar consultas, diagnósticos o tratamientos.
iv. Visualizar el historial completo.
6. Gestionar turnos
a. Administra turnos médicos según la prioridad (gravedad).
b. Opciones Disponibles:
i. Asignar turnos: Indique el paciente y su nivel de prioridad.
ii. Llamar al próximo turno: Atiende al paciente con mayor prioridad.
7. Salir
a. Cierra el programa.
Recomendaciones Generales
• Entrada de Datos:
o Asegúrese de ingresar nombres y datos correctamente, ya que el sistema
es sensible a mayúsculas y espacios.
• Gestión de Archivos:
o Ambos sistemas utilizan archivos para guardar datos. No elimine los
archivos *.pkl generados para preservar el estado del sistema.
• Errores Comunes:
o Hospital no encontrado: Verifique que el hospital esté registrado antes de
conectarlo o transferir pacientes.
o Paciente no registrado: Compruebe que el ID del paciente exista en el
sistema.
