# Automatización de carga de títulos en SIU Guaraní con TagUI
Este proyecto automatiza el proceso de carga de títulos en el sistema SIU Guaraní / Mapuche, utilizando TagUI como herramienta de RPA (Robotic Process Automation).
El script simula la interacción de un usuario en el sistema: login, búsqueda de legajo, carga de estudios, selección de título, entidad otorgante y título ONA, completando los datos requeridos y registrando errores en un archivo de log.


## Objetivos
- Reducir el tiempo manual de carga de títulos en SIU Guaraní.
- Minimizar errores humanos en la búsqueda y carga de datos.
- Generar un registro automático de errores para auditoría y seguimiento.


## Funcionalidades principales
- Login automático en SIU Mapuche.
- Búsqueda de usuario por legajo.
- Carga de estudios en el currículum del alumno.
- Selección de título, entidad otorgante y título ONA mediante popups.
- Ingreso de fechas y datos adicionales (años, meses, tesis).
- Registro de errores en Error.txt cuando no se encuentra legajo, título o entidad.
- Lectura de nombre y descripción del título para asociar documentos PDF.


## Estructura del proyecto
- automatizacion.tag    → Script principal de TagUI
- Error.txt             → Log de errores en ejecuciones
- README.md             → Documentación del proyecto


## Uso
1. Instalar TagUI.
2. Configurar credenciales de acceso en el script (datosusuario, datosclave).
3. Ejecutar el script: tagui automatizacion.tag
4. Revisar Error.txt para validar registros de errores.


## Consideraciones
El script está diseñado para uso interno en entornos académicos.
