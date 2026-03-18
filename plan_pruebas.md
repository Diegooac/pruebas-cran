Plan de pruebas

Objetivo
Verificar que el sistema funcione correctamente en todas sus operaciones principales.

Módulos a probar:
Registro de alumnos
Consulta de alumnos
Edición de alumnos
Eliminación de alumnos
Servicios JSON
API externa

Casos de prueba:
ID	Caso	            Pasos	                      Resultado esperado
CP1	Registrar alumno	Llenar formulario y enviar	Se guarda correctamente
CP2	Validación	      Enviar vacío	              Muestra error
CP3	Mostrar alumnos	  Cargar página	              Lista visible
CP4	Editar	          Modificar datos	            Cambios guardados
CP5	Eliminar	        Eliminar registro	          Registro eliminado
CP6	JSON	            Consultar API	              Devuelve JSON
CP7	API externa	      Cargar API	                API generada
